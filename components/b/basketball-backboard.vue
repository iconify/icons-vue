<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf9tidbco"/><path class="om_avib3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-backboard" /></template>
<style>
.om_avib3w {
  d: path("M9 5.5h6v4H9ZM9 21l3-5.5l3 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf9tidbco {
  d: path("M3 2.5h18v10H3Zm4 10L9 21h6l2-8.5");
}

</style>
