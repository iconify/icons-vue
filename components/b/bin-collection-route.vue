<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dnz72yc2k"/><path class="q4ris7c2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-collection-route" /></template>
<style>
.dnz72yc2k {
  d: path("M12 9.5h9.5m-8.5 0l1 11h5.5l1-11m-5.25-2.75h3M2.5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.q4ris7c2o {
  d: path("M4.5 7v7.5a4 4 0 0 0 4 4H11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
