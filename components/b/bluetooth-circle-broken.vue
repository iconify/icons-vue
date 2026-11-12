<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bvqamvbai"/><path class="x-s0u0b9w"/><path class="si3inpc3v"/><path class="i70bgdbfl"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-circle-broken" /></template>
<style>
.bvqamvbai {
  d: path("M11 12L14.2 9.5929C14.7333 9.19171 15 8.99112 15 8.71759C15 8.44405 14.7333 8.24346 14.2 7.84228L12.7455 6.74814C11.9838 6.17524 11.603 5.88879 11.3015 6.04C11 6.1912 11 6.66862 11 7.62345V12Z");
}

.i70bgdbfl {
  d: path("M11 12L8 14.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.si3inpc3v {
  d: path("M11 12L8 9.5");
}

.x-s0u0b9w {
  d: path("M12.7455 17.2519L14.2 16.1577C14.7333 15.7565 15 15.5559 15 15.2824C15 15.0089 14.7333 14.8083 14.2 14.4071L11 12V16.3766C11 17.3314 11 17.8088 11.3015 17.96C11.603 18.1112 11.9838 17.8248 12.7455 17.2519Z");
}

</style>
