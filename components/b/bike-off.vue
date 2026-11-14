<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h2plpsbdm"/><path class="uzf2_rbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-off" /></template>
<style>
.h2plpsbdm {
  d: path("M2 15.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm19.426 1.921q.281-.428.427-.919q.147-.49.147-1.002q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T18.5 12q-.515 0-1.009.148q-.493.149-.923.433");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzf2_rbmd {
  d: path("M5.5 15.5h6.1m3.395-4.493L16 9.5l1.842 4.421M5.5 15.5l2.753-3.303M13.39 9.5H16m0 0L15 7h2.5m-14-3.5l17 17");
}

</style>
