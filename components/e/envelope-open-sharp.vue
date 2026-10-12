<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bptsqeb5r"/><path class="aba5w4h0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:envelope-open-sharp" /></template>
<style>
.aba5w4h0a {
  d: path("M2.75 11.75L12 17.5l9.25-5.75");
}

.bptsqeb5r {
  d: path("M2.75 10.75L12 4l9.25 6.75v10.5H2.75v-2Zm6.25-.5h6m-5 2.5h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
