<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b2vh0lbrc"/><path class="dgvbys_fx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-date" /></template>
<style>
.b2vh0lbrc {
  d: path("M3 4.5h18v17H3Zm0 5h18m-13-7v4m8-4v4");
}

.dgvbys_fx {
  d: path("M12.5 13h5v5h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
