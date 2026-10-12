<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r71z_8blh"/><path class="o4reiccib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eviction-notice" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o4reiccib {
  d: path("M6.75 21v-3.5a2 2 0 0 1 4 0V21m5.75-5.5h4.75M19 13.25l2.25 2.25L19 17.75");
}

.r71z_8blh {
  d: path("m3.63 10.12l4.24-4.24q.88-.88 1.76 0l4.24 4.24q.88.88.88 2.13V20q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25v-7.75q0-1.25.88-2.13");
}

</style>
