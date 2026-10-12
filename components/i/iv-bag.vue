<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wl0gfnrqa"/><path class="z72oj--0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iv-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wl0gfnrqa {
  d: path("M6.75 4.75a2 2 0 0 1 2-2h6.5a2 2 0 0 1 2 2v10.5a3 3 0 0 1-3 3h-4.5a3 3 0 0 1-3-3Zm4 .5h2.5");
}

.z72oj--0z {
  d: path("M9.25 10.25h5.5v4a1.5 1.5 0 0 1-1.5 1.5h-2.5a1.5 1.5 0 0 1-1.5-1.5Zm2.75 8v3");
}

</style>
