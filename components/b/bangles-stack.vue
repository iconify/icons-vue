<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ssdt96b_e"/><path class="xmms1nfsq"/><path class="qcyrzdcmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bangles-stack" /></template>
<style>
.qcyrzdcmv {
  d: path("M6.5 17a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0Z");
}

.ssdt96b_e {
  d: path("M2.5 7a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmms1nfsq {
  d: path("M4.5 12a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0Z");
}

</style>
