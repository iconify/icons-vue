<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xr4at1b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flag-light" /></template>
<style>
.xr4at1b3u {
  fill: currentColor;
  d: path("M44.08 51.37A6 6 0 0 0 42 55.9V224a6 6 0 0 0 12 0v-45.22c28.08-22.79 51.88-11 79.34 2.57c16.12 8 33.49 16.58 52 16.58c13.57 0 27.76-4.6 42.56-17.42A6 6 0 0 0 230 176V55.9a6 6 0 0 0-9.93-4.54c-29 25.12-53.28 13.09-81.41-.84c-27.89-13.81-59.66-29.36-94.58.85M218 173.17c-28.08 22.8-51.88 11-79.34-2.58C113.4 158.08 85.09 144.07 54 164V58.72c28.08-22.8 51.88-11 79.34 2.56C158.6 73.79 186.91 87.8 218 67.91Z");
}

</style>
