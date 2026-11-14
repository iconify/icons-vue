<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzyu7yv_t"/><path class="twkdnqbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bikes-available" /></template>
<style>
.twkdnqbru {
  d: path("M6.5 11H10l3.5-6l2 6M10 11L8.75 5m-1.5 0h3m3.25 0L13 3.5h2.5M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzyu7yv_t {
  d: path("M3 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm12.164 3.484q.168.016.336.016q.172 0 .343-.017t.34-.05q.168-.034.333-.084t.323-.115t.311-.147t.294-.177q.143-.095.276-.204q.133-.11.255-.231q.121-.122.231-.255q.109-.133.204-.276q.096-.142.177-.294t.147-.311t.115-.323t.084-.333q.033-.169.05-.34T19 11t-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T15.5 7.5t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34T12 11q0 .14.011.279t.033.277t.056.274t.077.268t.098.262q.054.128.118.252q.065.124.139.243q.074.118.157.23t.175.218t.192.203t.208.186q.107.09.221.17q.115.081.235.152t.246.132t.255.112q.131.051.264.092");
}

</style>
