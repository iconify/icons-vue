<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uv9rg25wm"/><path class="j2omq6gic"/><path class="p36xabcxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:condo" /></template>
<style>
.j2omq6gic {
  fill: currentColor;
  d: path("M13.5 5.25h3v2.5h-3Z");
}

.p36xabcxn {
  d: path("M7.5 10.5h3m3 0h3m-9 4h3m3 0h3m-6 7v-3.25h3v3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv9rg25wm {
  d: path("M4.5 2.5h15v19h-15Zm3 4h3");
}

</style>
