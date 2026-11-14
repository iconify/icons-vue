<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5bcdvbpf"/><path class="tqvqwlvwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:internet-cafe" /></template>
<style>
.tqvqwlvwx {
  d: path("M7 11h10v5.5H7Zm5 5.5v1.75m-2.5 0h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5bcdvbpf {
  d: path("M3.5 10L12 3l8.5 7v11h-17Z");
}

</style>
