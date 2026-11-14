<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpjl4rq7a"/><path class="ozgpk1bjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lock-star" /></template>
<style>
.hpjl4rq7a {
  d: path("M4.5 10h15v11h-15ZM8 10V7a4 4 0 0 1 8 0v3");
}

.ozgpk1bjy {
  d: path("m12 12.5l.882 1.786l1.971.287l-1.426 1.391l.336 1.963L12 17l-1.763.927l.336-1.963l-1.426-1.391l1.971-.287Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
