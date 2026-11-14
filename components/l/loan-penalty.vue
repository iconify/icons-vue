<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ec-sy5buu"/><path class="zxaxrrbew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-penalty" /></template>
<style>
.ec-sy5buu {
  d: path("M5.625 3h4.788a2.63 2.63 0 0 1 1.856.769l6.875 6.875a2.625 2.625 0 0 1 0 3.712l-4.788 4.788a2.625 2.625 0 0 1-3.712 0l-6.875-6.875A2.63 2.63 0 0 1 3 10.413V5.625A2.625 2.625 0 0 1 5.625 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxaxrrbew {
  d: path("M6 7.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m7 2.25v4m0 2.75h.01");
}

</style>
