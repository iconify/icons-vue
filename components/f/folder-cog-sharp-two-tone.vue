<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rdgb62bqf"/><path class="t5-u2wxzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-cog-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rdgb62bqf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.5 3C9.7652 3 10.0195 3.10547 10.207 3.29297L12.4141 5.5H21C21.5523 5.5 22 5.9477 22 6.5V8C22 8.5523 21.5523 9 21 9H10V20C10 20.5523 9.5523 21 9 21H3C2.4477 21 2 20.5523 2 20V4C2 3.4477 2.4477 3 3 3H9.5Z");
  stroke: none;
}

.t5-u2wxzi {
  d: path("M10 20L3 20L3 4L9.5 4L12 6.5L21 6.5L21 9M19.6667 16C19.6667 17.4728 18.4728 18.6667 17 18.6667C15.5272 18.6667 14.3333 17.4728 14.3333 16C14.3333 14.5272 15.5272 13.3333 17 13.3333C18.4728 13.3333 19.6667 14.5272 19.6667 16ZM19.99 16L22 16M19.1142 18.1142L20.5355 19.5355M17 18.99L17 21M14.8858 18.1142L13.4645 19.5355M14.01 16L12 16M14.8858 13.8858L13.4645 12.4645M17 13.01L17 11M19.1142 13.8858L20.5355 12.4645");
}

</style>
