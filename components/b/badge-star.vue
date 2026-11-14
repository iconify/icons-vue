<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="op4vu5bde"/><path class="aa6zz4fbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-star" /></template>
<style>
.aa6zz4fbs {
  d: path("m12 8l1.176 2.632l2.866.305l-2.14 1.931l.596 2.82L12 14.25l-2.498 1.438l.596-2.82l-2.14-1.931l2.866-.305Z");
}

.op4vu5bde {
  d: path("m12 2.25l2.135 1.781l2.74-.475l.959 2.61l2.61.959l-.475 2.74L21.75 12l-1.781 2.135l.475 2.74l-2.61.959l-.959 2.61l-2.74-.475L12 21.75l-2.135-1.781l-2.74.475l-.959-2.61l-2.61-.959l.475-2.74L2.25 12l1.781-2.135l-.475-2.74l2.61-.959l.959-2.61l2.74.475Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
