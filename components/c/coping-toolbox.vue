<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v96ly0mrn"/><path class="mob8s9bqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coping-toolbox" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mob8s9bqm {
  d: path("m13.484 2.911l1.88.685a1.5 1.5 0 0 1 .896 1.922a1.5 1.5 0 0 1-1.922.897l-1.88-.684a1.5 1.5 0 0 1-.896-1.923a1.5 1.5 0 0 1 1.922-.897M11.75 11.5h.5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.v96ly0mrn {
  d: path("M5.625 11.5h12.75A2.625 2.625 0 0 1 21 14.125v4.25A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-4.25A2.625 2.625 0 0 1 5.625 11.5m.49-8.078L20.68 8.723a1.25 1.25 0 0 1 .748 1.602a1.25 1.25 0 0 1-1.603.747L5.26 5.771a1.25 1.25 0 0 1-.747-1.602a1.25 1.25 0 0 1 1.602-.747");
}

</style>
