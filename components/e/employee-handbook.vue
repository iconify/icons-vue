<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1oqy_-_m"/><circle class="pw_u43c3e"/><path class="yycu1e_9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:employee-handbook" /></template>
<style>
.g1oqy_-_m {
  d: path("M4.75 18.75V5.25a2.5 2.5 0 0 1 2.5-2.5h10a2 2 0 0 1 2 2v11.5H6.75a2 2 0 0 0-2 2Zm0 0a2.5 2.5 0 0 0 2.5 2.5h12v-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pw_u43c3e {
  cx: 12px;
  cy: 9.75px;
  r: 3.5px;
}

.yycu1e_9d {
  d: path("M12 9.5v2m0-3.75v.01");
}

</style>
