<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e4gk14b9q"/><path class="dou4n5biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-mouse" /></template>
<style>
.dou4n5biz {
  d: path("m6.5 6.5l3 2.5l-3 2.5m5 0h4");
}

.e4gk14b9q {
  d: path("M2.5 2.5h19v13h-19Zm2 16h15v3h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
