<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fffd9ib1u"/><path class="acib1losd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alerting" /></template>
<style>
.acib1losd {
  d: path("m6.5 17l4-3.5l3 2l6-10M6 10h2.5m2.5 0h2.5m6.5 0h1.5");
}

.fffd9ib1u {
  d: path("M3 3v17.5h18.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
