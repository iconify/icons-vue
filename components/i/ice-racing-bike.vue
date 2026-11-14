<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pymbtmfnr"/><path class="jujijob5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-racing-bike" /></template>
<style>
.jujijob5d {
  d: path("M5.5 8.5L8 5h4.75l1.75 3.5Zm12 0L15.25 3h2.5M18 14.75v6.75m-3-5l6 3.25m-6 0l6-3.25m-4.25-1L18 16.75l1.25-1.25m-2.5 5.25L18 19.5l1.25 1.25");
}

.pymbtmfnr {
  d: path("M2 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm15.164 3.484q.168.016.336.016q.172 0 .343-.017t.34-.05q.168-.034.333-.084t.323-.115t.311-.147t.294-.177q.143-.095.276-.204q.133-.11.255-.231q.121-.122.231-.255q.109-.133.204-.276q.096-.142.177-.294t.147-.311t.115-.323t.084-.333q.033-.169.05-.34T21 8.5t-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294q-.095-.143-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T17.5 5t-.343.017t-.34.05q-.168.034-.333.084t-.323.115t-.311.147t-.294.177q-.143.095-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333t-.05.34Q14 8.328 14 8.5q0 .14.011.279t.033.277t.056.274t.077.268t.098.262q.054.128.118.252q.065.124.139.243q.074.118.157.23t.175.218t.192.203t.208.186q.107.09.221.17q.115.081.235.152t.246.132t.255.112q.131.051.264.092");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
