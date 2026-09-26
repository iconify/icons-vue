<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="ysebjhopi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-3-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x-_5ilohg {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

.ysebjhopi {
  fill: currentColor;
  d: path("M7.25 5.75C8.0784 5.75 8.75 6.4216 8.75 7.25C8.75 8.0784 8.0784 8.75 7.25 8.75C6.4216 8.75 5.75 8.0784 5.75 7.25C5.75 6.4216 6.4216 5.75 7.25 5.75ZM12 10.5C12.8284 10.5 13.5 11.1716 13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5ZM16.75 15.25C17.5784 15.25 18.25 15.9216 18.25 16.75C18.25 17.5784 17.5784 18.25 16.75 18.25C15.9216 18.25 15.25 17.5784 15.25 16.75C15.25 15.9216 15.9216 15.25 16.75 15.25Z");
  stroke: none;
}

</style>
