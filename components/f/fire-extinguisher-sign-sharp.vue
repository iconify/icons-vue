<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="c4oy5i2ao"/><path class="zvragb-kt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-extinguisher-sign-sharp" /></template>
<style>
.c4oy5i2ao {
  d: path("M10 18.25V8.5h4v9.75Z");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvragb-kt {
  d: path("M12 8.5V6m-1.75 0h3.5l1.75 1.25l1.75 1.05V15");
}

</style>
