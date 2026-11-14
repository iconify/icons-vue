<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jhm3h8n4w"/><path class="oam1xruay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:care-instructions-tag" /></template>
<style>
.jhm3h8n4w {
  d: path("M2.5 5.5h19v13h-19Zm4 0v13M4.5 8h.01m-.01 4h.01m-.01 4h.01");
}

.oam1xruay {
  d: path("M8.75 16H19c0-2.25-1-3.75-3-3.75h-4.75c-1.5.5-2.25 2-2.5 3.75ZM12 12.25c0-2.25.75-3 2.25-3H17v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
