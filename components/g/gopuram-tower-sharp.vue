<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="all8ubb6f"/><path class="jpou_dbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gopuram-tower-sharp" /></template>
<style>
.all8ubb6f {
  d: path("M4.25 20.85V17.5H5.5V14h1.25v-3.5H8V7h8v3.5h1.25V14h1.25v3.5h1.25v3.75H4.25zM8 7V4h8v3Zm2-3V2.75M14 4V2.75");
}

.jpou_dbqd {
  d: path("M10.5 21.25v-4h3v4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
