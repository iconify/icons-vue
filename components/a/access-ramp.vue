<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="okkn7y67n"/><path class="i70b4acue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:access-ramp" /></template>
<style>
.i70b4acue {
  d: path("M7 15.5v-4L13 7v4");
}

.okkn7y67n {
  d: path("M2.5 18.5h19M3 18.5l12-9h6v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
