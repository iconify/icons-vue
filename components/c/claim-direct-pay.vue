<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i82h73b3i"/><path class="omtlvp22t"/><path class="grzcwm7uo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:claim-direct-pay" /></template>
<style>
.grzcwm7uo {
  d: path("M17.25 17.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i82h73b3i {
  d: path("M16.653 11.25H2.5V8q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 6.5h1.5l2-3h6l2.5 3h3.5q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T21 8v3.25h-.747");
}

.omtlvp22t {
  d: path("M2.75 13a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8 1h3.5A1.75 1.75 0 0 1 22 15.75v3a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 15 18.75v-3A1.75 1.75 0 0 1 16.75 14");
}

</style>
