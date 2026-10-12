<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="efpjp4buu"/><path class="szqse9bfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:floor-plan-sharp" /></template>
<style>
.efpjp4buu {
  d: path("M4.25 2.75h17v18.5H2.75V2.75zm7.75 0v6.5M2.75 12.5h5.5m3.75 0h9.25m-9.25 0v8.75");
}

.szqse9bfm {
  d: path("M8.25 12.5v3.75H12V12.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
