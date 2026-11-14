<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="an9unmb4t"/><path class="s0wlx0b_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ar-game" /></template>
<style>
.an9unmb4t {
  d: path("M6.5 11.5h11c2.5 0 4 2 4 5s-2.5 4-4.5 2L15.5 17h-7L7 18.5c-2 2-4.5 1-4.5-2s1.5-5 4-5Zm-1 3.25h3M7 13.25v3m10-1.5h.01M12 2.5L15 4v3l-3 1.5L9 7V4Z");
}

.s0wlx0b_c {
  d: path("m9 4l3 1.5L15 4m-3 1.5v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
