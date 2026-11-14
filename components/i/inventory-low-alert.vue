<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suvf1jb1f"/><path class="xt4x_vybz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inventory-low-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.suvf1jb1f {
  d: path("M20 12.543V7.5H3v12q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036t.146.022T4.5 21h10.679M3 7.5l-.5-4h6l3 4m8.5 0l.5-4h-6l-3 4");
}

.xt4x_vybz {
  d: path("M7.5 13.5h1A1.5 1.5 0 0 1 10 15v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 6 16v-1a1.5 1.5 0 0 1 1.5-1.5m10.5 1V18m0 3h.01");
}

</style>
