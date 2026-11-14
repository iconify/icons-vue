<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="poz_fvbbz"/><path class="hn-qdiukc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loyalty-card-pharmacy" /></template>
<style>
.hn-qdiukc {
  d: path("m12.5 9.25l.158.474a1.5 1.5 0 0 0 1.423 1.026h.568a.562.562 0 0 1 .351 1l-.453.363a1.5 1.5 0 0 0-.497 1.612l.221.717a.6.6 0 0 1-.896.683l-.57-.363a1.5 1.5 0 0 0-1.61 0l-.57.363a.6.6 0 0 1-.896-.683l.221-.717a1.5 1.5 0 0 0-.497-1.612L9 11.75a.562.562 0 0 1 .351-1h.568a1.5 1.5 0 0 0 1.423-1.026l.158-.474a.527.527 0 0 1 1 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.poz_fvbbz {
  d: path("M6.875 5h10.25A4.375 4.375 0 0 1 21.5 9.375v5.25A4.375 4.375 0 0 1 17.125 19H6.875A4.375 4.375 0 0 1 2.5 14.625v-5.25A4.375 4.375 0 0 1 6.875 5");
}

</style>
