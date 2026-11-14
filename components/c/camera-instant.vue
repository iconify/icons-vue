<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dn9ldzb0r"/><path class="b1wrq7q0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-instant" /></template>
<style>
.b1wrq7q0c {
  d: path("M9 8.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm8-3h.01M5.5 19h13");
}

.dn9ldzb0r {
  d: path("M3 2.5h18V15H3ZM5.5 15v7h13v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
