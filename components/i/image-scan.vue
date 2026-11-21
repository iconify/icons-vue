<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qnlt1jb1a"/><path class="isy2lrdil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-scan" /></template>
<style>
.isy2lrdil {
  fill: currentColor;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qnlt1jb1a {
  d: path("M3 18C3 19.6569 4.3431 21 6 21H13M3 18V6C3 4.3431 4.3431 3 6 3H13M3 18L7.9393 13.0607C8.5251 12.4749 9.4749 12.4749 10.0607 13.0607L12.0801 15.0801C12.3353 15.3353 12.6626 15.481 13 15.5128M13 3V2M13 3V15.5128M13 15.5128V21M13 22V21M17 3V10M17 21V14M21 20V18M21 14V10M21 6V4");
}

</style>
