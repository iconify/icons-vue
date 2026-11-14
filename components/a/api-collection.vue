<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bv_wmcbol"/><path class="ba-nq4p4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-collection" /></template>
<style>
.ba-nq4p4h {
  d: path("M5.5 11.5h5V17h-5Zm7.75 0h5V17h-5ZM5.5 13.75h5m2.75 0h5");
}

.bv_wmcbol {
  d: path("M2.5 6.5a2 2 0 0 1 2-2h5l2 2h8a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
