# zafazu
my first try (test) for testing  


<h2>Featured Items on ROBLOX</h2>
<div class="col-xs-12">
	<div class="row">
		<h3>Created by Olais Only</h3>
	</div>
	<div class="col-xs-3" style="border: 1px solid #777;background: #efefef;height:125px">
		<h2>Step 1 </h2>
		<h3>Subscribe</h3> <a class="btn-secondary-xs btn-more btn-fixed-width" data-ytta-id="-" target="_blank" href="https://www.youtube.com/channel/UCsg5gJlRSnAg3fvELfBk5MA?sub_confirmation=1"</a> 
		<img src="http://pre04.deviantart.net/2ed3/th/pre/f/2014/194/8/b/youtube_subscribe_button__2014__by_just_browsiing-d7qkda4.png" width="83" height="24"/>
		</a>
		<br>
		This step increase your success rate by 99% and if you don't do it the other steps will not work.
	</div>
	<div class="col-xs-1"> </div>
	<div class="col-xs-3" style="border: 1px solid #777;background: #efefef;height:125px">
		<h2>Step 2 </h2>
		<h3>Enter Item ID</h3>
		<center>
		<input id="catalog-input" oninput="document.getElementById('getItem').className = 'btn-medium btn-primary';" class="form-control input-field" style="width:160px" type="number" placeholder="2799053" />
		<center>
		The item ID can be found at the end of a catalog item's URL
	</div>
	<div class="col-xs-1"> </div>
	<div class="col-xs-3" style="border: 1px solid #777;background: #efefef;height:125px">
		<h2>Step 3 </h2>
		<h3>Press this button</h3>
		<br>
		<center>
			<a class="btn-medium btn-primary" id="saveButton" onclick="if(typeof(sp)==='undefined'){sp = 1; setInterval(function(){document.getElementById('saveButton').innerHTML = 'Saving [' + (100 - ((1.0 / sp) * 100)).toFixed(2) + '%]'; sp+=0.01}, 0.01); };"> [Add To Account]</a><br><br>
		</center>
	</div>
</div>
