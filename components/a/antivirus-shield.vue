<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm8lo6v1l"/><circle class="uoogiib0w"/><path class="m6dfuopld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:antivirus-shield" /></template>
<style>
.cm8lo6v1l {
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6dfuopld {
  d: path("M12 6.5v1.75m0 6V16m-4.75-4.75H9m6 0h1.75M8.65 7.9l1.2 1.2m4.3 4.3l1.2 1.2m0-6.7l-1.2 1.2m-4.3 4.3l-1.2 1.2");
}

.uoogiib0w {
  cx: 12px;
  cy: 11.25px;
  r: 2.5px;
}

</style>
