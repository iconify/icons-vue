<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z1pik0bhr"/><path class="yvhx9r25z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-rotate" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvhx9r25z {
  d: path("m21 8l-1.5 2.25L17 8.5");
}

.z1pik0bhr {
  d: path("M3 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0h12m-2.5 0V19m-3-2.5v2M4.614 10.198a7.5 7.5 0 0 1 14.772 0");
}

</style>
