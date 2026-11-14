<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="df095h88a"/><path class="wr3-6wb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bivouac" /></template>
<style>
.df095h88a {
  d: path("M2.5 17.5v-3q0-2 2-2h6c.5-7.5 11-8 11 2v3m-19 0h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wr3-6wb6k {
  d: path("M13 17.5v-2.25a2.75 2.75 0 0 1 5.5 0v2.25");
}

</style>
