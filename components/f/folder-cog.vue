<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q3wixnhae"/><path class="yl3-2bb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:folder-cog" /></template>
<style>
.q3wixnhae {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yl3-2bb3t {
  d: path("m11.474 11.056l.06-1.025h.932l.06 1.025l.83.344l.767-.682l.659.659l-.682.767l.344.83l1.025.06v.932l-1.025.06l-.344.83l.682.767l-.659.659l-.767-.682l-.83.344l-.06 1.025h-.932l-.06-1.025l-.83-.344l-.767.682l-.659-.659l.682-.767l-.344-.83l-1.025-.06v-.932l1.025-.06l.344-.83l-.682-.767l.659-.659l.767.682Z");
}

</style>
