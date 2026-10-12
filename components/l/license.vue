<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mz2kk-h8b"/><path class="srpu1rb2a"/><circle class="v1wf5pbfy"/><path class="n2554bvcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:license" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mz2kk-h8b {
  d: path("M12.75 21.25h-5.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5V12");
}

.n2554bvcg {
  d: path("M15.5 18.25v3l1.5-1l1.5 1v-3");
}

.srpu1rb2a {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 3h4m-4 3.25h2.5");
}

.v1wf5pbfy {
  cx: 17px;
  cy: 15.75px;
  r: 2.75px;
}

</style>
