<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="admat9drz"/><path class="cgnyx9bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-air-balloon-science" /></template>
<style>
.admat9drz {
  d: path("M9.5 15.5c-2.75-2-4.25-4-4.25-6.25a6.75 6.75 0 0 1 13.5 0c0 2.25-1.5 4.25-4.25 6.25Zm1.5 2.75h2a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 9.5 20v-.25a1.5 1.5 0 0 1 1.5-1.5");
}

.cgnyx9bkt {
  d: path("M12 2.5c-4.5 3.5-3.5 10-2.5 13m2.5-13c4.5 3.5 3.5 10 2.5 13m-5 0v2.75m5-2.75v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
