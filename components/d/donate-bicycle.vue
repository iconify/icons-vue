<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vid20v69c"/><path class="jgyzz0b8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-bicycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jgyzz0b8u {
  d: path("M5.5 12h6L16 5.5l2.5 6.5M9 4.5h3m-1.5 0l1 7.5M16 5.5l-1-2h-1.5m3 13h3A1.5 1.5 0 0 1 21 18v2a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 15 20v-2a1.5 1.5 0 0 1 1.5-1.5m-.5-2.25l2 2.25l2-2.25m-2 2.25v5");
}

.vid20v69c {
  d: path("M2 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m19.987.296Q22 12.148 22 12q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T18.5 8.5q-.159 0-.318.014q-.158.015-.315.044q-.156.028-.31.071q-.153.043-.302.1t-.292.126t-.279.153t-.264.177q-.128.095-.247.201q-.119.105-.228.222q-.109.116-.206.241q-.098.126-.184.26t-.16.275t-.134.289t-.107.299q-.046.153-.079.308q-.033.156-.051.314");
}

</style>
