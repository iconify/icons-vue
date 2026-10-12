<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5cfamwul"/><path class="rpns7lb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circus-tent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5cfamwul {
  d: path("m12.28 2.86l3.44 1.28q.28.11 0 .22l-3.44 1.28q-.28.11-.28-.19v-2.4q0-.3.28-.19M12 5.75c-2 3-4.75 4.75-8.75 5.75a2.19 2.19 0 0 0 4.38 0a2.19 2.19 0 0 0 4.37 0a2.19 2.19 0 0 0 4.38 0a2.19 2.19 0 0 0 4.37 0c-4-1-6.75-2.75-8.75-5.75M5.75 16.5h12.5q1 0 1 1v2.75q0 1-1 1H5.75q-1 0-1-1V17.5q0-1 1-1");
}

.rpns7lb4p {
  d: path("M9.25 21.25L12 18l2.75 3.25");
}

</style>
