<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mnck9hmel"/><path class="nawnxybiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-vertical-arrow-left-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mnck9hmel {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 1C19.209 1 21 2.79 21 5C21 6.86 19.725 8.43 18 8.87V15.13C19.725 15.57 21 17.14 21 19C21 21.21 19.209 23 17 23C14.791 23 13 21.21 13 19C13 17.14 14.275 15.57 16 15.13V8.87C14.275 8.43 13 6.86 13 5C13 2.79 14.791 1 17 1ZM9.401 6.71C9.704 6.49 10.11 6.45 10.448 6.62C10.786 6.79 11 7.13 11 7.51V16.49C11 16.86 10.786 17.21 10.448 17.38C10.11 17.55 9.704 17.51 9.401 17.29L3.401 12.8C3.149 12.61 3 12.32 3 12C3 11.68 3.149 11.39 3.401 11.2L9.401 6.71Z");
  stroke: none;
}

.nawnxybiz {
  d: path("M17 8C18.657 8 20 6.66 20 5C20 3.34 18.657 2 17 2C15.343 2 14 3.34 14 5C14 6.66 15.343 8 17 8ZM17 8V16M17 16C15.343 16 14 17.34 14 19C14 20.66 15.343 22 17 22C18.657 22 20 20.66 20 19C20 17.34 18.657 16 17 16ZM10 7.51L4 12L10 16.49V7.51Z");
}

</style>
