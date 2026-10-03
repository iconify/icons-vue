<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="scjcnkjad"/><path clip-rule="evenodd" class="ykzngxbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-list-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.scjcnkjad {
  d: path("M7 4L4 4L4 22L20 22L20 4L17 4M7 2L17 2L17 7L7 7L7 2ZM11 13L17 13M11 17L17 17");
}

.ykzngxbve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 13C9 13.5523 8.5523 14 8 14C7.4477 14 7 13.5523 7 13C7 12.4477 7.4477 12 8 12C8.5523 12 9 12.4477 9 13ZM9 17C9 17.5523 8.5523 18 8 18C7.4477 18 7 17.5523 7 17C7 16.4477 7.4477 16 8 16C8.5523 16 9 16.4477 9 17Z");
  stroke: none;
}

</style>
