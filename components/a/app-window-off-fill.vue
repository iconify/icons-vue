<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="trg5zsbhu"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-off-fill" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.trg5zsbhu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.8284 20.8284C20.1046 21.5523 19.1046 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 4.8955 2.4477 3.8955 3.1716 3.1716ZM20.2929 16.0502L7.9498 3.7071C7.7688 3.5261 7.6569 3.2761 7.6569 3C7.6569 2.4477 8.1046 2 8.6569 2L18 2C20.2091 2 22 3.7909 22 6L22 15.3431C22 15.8954 21.5523 16.3431 21 16.3431C20.7239 16.3431 20.4739 16.2312 20.2929 16.0502ZM16 7C16 6.4477 15.5523 6 15 6C14.4477 6 14 6.4477 14 7C14 7.5523 14.4477 8 15 8C15.5523 8 16 7.5523 16 7Z");
  stroke: none;
}

</style>
