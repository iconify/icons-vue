<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k3f54ndjx"/><path class="itix1i2bj"/><path class="xj2shibjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-mailbox" /></template>
<style>
.itix1i2bj {
  d: path("M8 6.5h8v6H8Z");
}

.k3f54ndjx {
  d: path("M4 15.5v-10a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v10m-17.5 4l1.5-4h16l1.5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xj2shibjb {
  d: path("M8.25 7L12 9.75L15.75 7");
}

</style>
