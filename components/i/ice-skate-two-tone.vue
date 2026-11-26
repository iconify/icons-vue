<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skj37dbto"/><path class="xsq94y6ea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ice-skate-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.skj37dbto {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 18L5.5 18C4.1193 18 3 16.8807 3 15.5L3 6C3 5.5535 3.296 5.1611 3.7253 5.0385L10.7253 3.0385C10.8146 3.0129 10.9071 3 11 3C11.5523 3 12 3.4477 12 4L12 9.0328C15.0214 9.2341 17.0144 10.3267 18.364 11.2762C19.4343 12.0292 20 13.2689 20 14.5135L20 15.5C20 16.8807 18.8807 18 17.5 18L15 18L15 22C15 22.5523 14.5523 23 14 23L7 23C6.4477 23 6 22.5523 6 22Z");
  stroke: none;
}

.xsq94y6ea {
  d: path("M11 4L4 6V15.5C4 16.3284 4.6716 17 5.5 17H17.5C18.3284 17 19 16.3284 19 15.5V14.5135C19 13.5617 18.5671 12.6418 17.7886 12.0941C16.4131 11.1263 14.3296 10 11 10V2M7 17V22M14 17V22M3 22H19C20.1046 22 21 21.1046 21 20");
}

</style>
