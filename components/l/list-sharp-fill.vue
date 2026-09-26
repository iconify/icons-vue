<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j4qvjhbhb"/><path class="o5tl1grlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j4qvjhbhb {
  fill: currentColor;
  d: path("M5 5C5 5.8284 4.3284 6.5 3.5 6.5C2.6716 6.5 2 5.8284 2 5C2 4.1716 2.6716 3.5 3.5 3.5C4.3284 3.5 5 4.1716 5 5ZM5 12C5 12.8284 4.3284 13.5 3.5 13.5C2.6716 13.5 2 12.8284 2 12C2 11.1716 2.6716 10.5 3.5 10.5C4.3284 10.5 5 11.1716 5 12ZM5 19C5 19.8284 4.3284 20.5 3.5 20.5C2.6716 20.5 2 19.8284 2 19C2 18.1716 2.6716 17.5 3.5 17.5C4.3284 17.5 5 18.1716 5 19Z");
  stroke: none;
}

.o5tl1grlc {
  d: path("M7 5L22 5M7 12L22 12M7 19L22 19");
}

</style>
