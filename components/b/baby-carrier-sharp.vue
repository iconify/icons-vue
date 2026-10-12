<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xnvdsxiko"/><path class="g2gmo4b-k"/><circle class="oicbsxx-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-carrier-sharp" /></template>
<style>
.g2gmo4b-k {
  d: path("M7.5 13.75h9a4.5 4.5 0 0 1-9 0Z");
}

.oicbsxx-q {
  cx: 12px;
  cy: 9.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xnvdsxiko {
  d: path("M3.75 21.25V2.75H10v2h4v-2h6.25v18.5ZM7.5 2.9v10.85m9-10.85v10.85");
}

</style>
