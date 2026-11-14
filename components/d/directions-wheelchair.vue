<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x7e9hn3ip"/><path class="zcp4kvp5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:directions-wheelchair" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7e9hn3ip {
  d: path("M7.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 4.5V14H15l2.5 5.5h2M9.5 11h4");
}

.zcp4kvp5k {
  d: path("M14.763 12.75a5.5 5.5 0 0 1-7.513 7.513");
}

</style>
