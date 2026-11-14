<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3-vmcbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anonymous-user" /></template>
<style>
.b3-vmcbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3 13c0-3.5 3-6 7-6c1.689 0 3.2.446 4.381 1.224m.927.744A5.54 5.54 0 0 1 16.5 20.5m.25-6.75A2.5 2.5 0 1 1 20.5 16c-.75.5-1.25 1-1.25 2m0 2.75h.01");
}

</style>
