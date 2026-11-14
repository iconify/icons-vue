<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oq8n5bcja"/><path class="uvnx9sh3k"/><path class="gxfnifbgh"/><path class="tdqo1wtow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corner-lot" /></template>
<style>
.gxfnifbgh {
  d: path("M21.5 2.5v19h-19M19 4v2.5m0 3V12");
}

.oq8n5bcja {
  fill: currentColor;
  d: path("M2.5 2.5H14V14H2.5Z");
}

.tdqo1wtow {
  d: path("M19 15v4h-4m-3 0H9.5m-3 0H4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvnx9sh3k {
  d: path("M16.5 2.5v14h-14");
}

</style>
