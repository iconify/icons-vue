<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m04f4sbdi"/><path class="q8y76ib-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:igloo-sharp" /></template>
<style>
.m04f4sbdi {
  d: path("M2.75 21.25a9.25 14 0 0 1 18.5 0Zm2.16-9h14.18m-9.59 0v-4.4m5 4.4v-4.4");
}

.q8y76ib-c {
  d: path("M8.5 21.25V19a3.5 3.5 0 0 1 7 0v2.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
