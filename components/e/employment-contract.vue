<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rd38379um"/><path class="fkdpf8nez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:employment-contract" /></template>
<style>
.fkdpf8nez {
  d: path("M14 16h8v5.5h-8Zm2.75 0v-1.25h2.5V16");
}

.rd38379um {
  d: path("M11.2 21.5H4.5v-19h15v9.4M8 7h8m-8 3.5h8M8 14h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
