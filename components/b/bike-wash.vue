<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ifwqm4b9r"/><path class="ik7n1dbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-wash" /></template>
<style>
.ifwqm4b9r {
  d: path("M2.75 17.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm12 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ik7n1dbod {
  d: path("M6 17.75h5.5L15 12.5H9.75l1.75 5.25M15 12.5l3 5.25m-3-5.25l-.5-2h2.25M6 2.5L7.5 5a1.5 1.5 0 0 1-3 0Zm6 0L13.5 5a1.5 1.5 0 0 1-3 0Zm6 0L19.5 5a1.5 1.5 0 0 1-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
