<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lotfavbxd"/><path class="z2s01qsld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baggage-scanner-sharp" /></template>
<style>
.lotfavbxd {
  d: path("M5.75 15.25V4.75h12.5v10.5m-15.5 0h18.5m-17.5 3.5h16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2s01qsld {
  d: path("M9 10.75h6v4.5H9zm1.75 0V8h2.5v2.75");
}

</style>
