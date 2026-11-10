<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2z-ecbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:electric-kettle" /></template>
<style>
.h2z-ecbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 5.5H5C3.8954 5.5 3 6.4 3 7.5V9.41C3 10.14 3.0388 10.88 3.3833 11.52C3.8221 12.33 4.6422 13.23 6 13.5M16.5 5.5H19.9955C20.7545 5.5 21.2368 6.31 20.8734 6.98L18.5 11M11 9V13M6 21H19M18 17H6.9592C6.4231 17 5.9813 16.58 5.9784 16.04C5.955 11.61 6.8978 3 12 3C16.7762 3 18.8149 8.93 18.9879 16C19.0014 16.55 18.5523 17 18 17Z");
}

</style>
