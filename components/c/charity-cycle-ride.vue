<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcga50_0s"/><path class="gxz3vrb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-cycle-ride" /></template>
<style>
.fcga50_0s {
  d: path("M2 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm19.799 1.168Q22 12.601 22 12q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T18.5 8.5t-.343.017t-.34.05q-.168.034-.333.084t-.323.115t-.311.147t-.294.177q-.143.095-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34T15 12q0 .386.084.764");
}

.gxz3vrb3i {
  d: path("M5.5 12h6L16 5.5l2.5 6.5M9 4.5h3m-1.5 0l1 7.5m3-6.5h3m.5 16l-3.25-3.25A2 2 0 0 1 18 16a2 2 0 0 1 3.25 2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
