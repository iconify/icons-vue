<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezfuhbbdz"/><path class="oa2vm-8uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hazard-flame" /></template>
<style>
.ezfuhbbdz {
  d: path("m12 2.5l9.5 9.5l-9.5 9.5L2.5 12Z");
}

.oa2vm-8uh {
  d: path("M12 16.5a3 3 0 0 1-3-3c0-2 1.5-3 1.5-5.5c1.5 1 2.25 2.25 2.25 3.5c.5-.5.75-1.25.75-2c1 1 1.5 2.5 1.5 4a3 3 0 0 1-3 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
