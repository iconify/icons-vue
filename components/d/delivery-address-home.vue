<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6zf6db1g"/><path class="uxje_8buy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-address-home" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxje_8buy {
  d: path("M5 9.5v11h8.4m5.6-9.2V9.5m-1 12.25L15.75 19a3 3 0 1 1 4.5 0ZM18 17h.01");
}

.z6zf6db1g {
  d: path("m2.5 11.5l9.5-8l9.5 8");
}

</style>
