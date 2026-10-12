<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fwbdkpbsq"/><circle class="whyy68m-y"/><path class="h05bcep8g"/><path class="u34vhtb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-officer" /></template>
<style>
.fwbdkpbsq {
  d: path("M7.5 6.5h9m-7.25 0l.4-2.5a1.25 1.25 0 0 1 1.23-1.25h2.24A1.25 1.25 0 0 1 14.35 4l.4 2.5");
}

.h05bcep8g {
  d: path("M4.5 21.25a7.5 5.95 0 0 1 15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u34vhtb2i {
  d: path("m12.12 17.42l.2.45q.12.27.42.3l.48.05q.3.04.08.24l-.36.32q-.23.2-.16.5l.1.47q.06.29-.2.14l-.42-.24q-.26-.15-.52 0l-.42.24q-.26.15-.2-.14l.1-.47q.07-.3-.16-.5l-.36-.32q-.22-.2.08-.24l.48-.05q.3-.03.42-.3l.2-.45q.12-.27.24 0");
}

.whyy68m-y {
  cx: 12px;
  cy: 10.9px;
  r: 2px;
}

</style>
