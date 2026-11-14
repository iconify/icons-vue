<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l--5wrgxh"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clapperboard-check" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l--5wrgxh {
  d: path("M13.315 20.5H6.5q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 17v-4q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6.5 9.5h11q.17 0 .34.017q.169.016.336.049t.33.082t.321.113t.308.144t.293.174t.274.201q.133.107.254.226t.23.251q.11.13.205.271q.096.141.178.29t.149.306t.118.319q.052.162.087.328q.036.167.055.336t.022.34M2.896 7.85l-.021-.1a1.726 1.726 0 0 1 1.387-2.061l13.576-2.396a1.75 1.75 0 0 1 2.016 1.357l.021.1a1.726 1.726 0 0 1-1.387 2.061L4.912 9.207A1.75 1.75 0 0 1 2.896 7.85m5.354-3.1L10 8.25m3.5-4.5l1.75 3.5");
}

</style>
