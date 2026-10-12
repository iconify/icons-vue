<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w434jz9wf"/><circle class="p374bcbxq"/><circle class="id0kkljei"/><circle class="u9x99hfmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-share" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.id0kkljei {
  cx: 19.5px;
  cy: 14.75px;
  r: 1.25px;
}

.p374bcbxq {
  cx: 15.25px;
  cy: 17.5px;
  r: 1.5px;
}

.u9x99hfmy {
  cx: 19.5px;
  cy: 20px;
  r: 1.25px;
}

.w434jz9wf {
  d: path("M11.75 19.25h-6.5a2.5 2.5 0 0 1-2.5-2.5v-9.5a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v2.25m-18.5-1.8h12m1.75 6l2-1.25m-2 2.75l2 1.25");
}

</style>
