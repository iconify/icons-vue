<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q_xpl5b9t"/><path class="tbylcsjks"/><path class="byfgwnb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-line-duotone" /></template>
<style>
.byfgwnb1r {
  d: path("M9 17H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_xpl5b9t {
  d: path("M20 7L4 7");
}

.tbylcsjks {
  d: path("M15 12L4 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
