<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cqkjt_y4w"/><path class="s41gnm2lu"/><path class="fhwlwbxfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:batch-edit" /></template>
<style>
.cqkjt_y4w {
  d: path("M5.125 7.5h6.25A2.625 2.625 0 0 1 14 10.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-6.25A2.625 2.625 0 0 1 2.5 13.875v-3.75A2.625 2.625 0 0 1 5.125 7.5");
}

.fhwlwbxfv {
  d: path("M8.5 2h10A1.5 1.5 0 0 1 20 3.5v7m-14.5 3L8 11l1.75 1.75L11 11.5m4.125 8.375l.27-.991a1.5 1.5 0 0 1 .387-.666l2.468-2.468a1.414 1.414 0 0 1 2 0a1.414 1.414 0 0 1 0 2l-2.468 2.468a1.5 1.5 0 0 1-.666.387l-.991.27a.814.814 0 0 1-1-1M15.5 18.5l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s41gnm2lu {
  d: path("M5.5 4.75h10q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T17 6.25v6.979");
}

</style>
