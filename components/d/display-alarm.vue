<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c1vr_eblx"/><path class="fja4m5b2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:display-alarm" /></template>
<style>
.c1vr_eblx {
  d: path("m11.22 2.626l6.401 1.128l-2.084 11.818l-6.401-1.129ZM6.5 17v1.75a5.5 2 0 0 0 11 0V17");
}

.fja4m5b2t {
  d: path("M6.5 17a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Zm7.776-11.551h.01M6.371 11.75a6.5 6.5 0 0 1 0-6.5m11.258 0a6.5 6.5 0 0 1 0 6.5m-14.012.659a9.25 9.25 0 0 1 0-7.818m16.766 0a9.25 9.25 0 0 1 0 7.818");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
