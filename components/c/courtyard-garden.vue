<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="syuefq-jr"/><path class="ga4lwvxac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:courtyard-garden" /></template>
<style>
.ga4lwvxac {
  d: path("M12 13c-3 0-5-2-5-5c3 0 5 2 5 5Zm0-2c0-3 2-5 5-5c0 3-2 5-5 5Z");
}

.syuefq-jr {
  d: path("M9.5 21.5h-5a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2h-5M12 18v-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
