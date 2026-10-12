<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="kj3gwgbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-csv-sharp" /></template>
<style>
.kj3gwgbaa {
  d: path("M13.75 2.75v5.5h5.5m-11 3h7.5v6.5h-7.5Zm0 3.25h7.5M12 11.25v6.5");
}

.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
