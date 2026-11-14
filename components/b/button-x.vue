<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pgqcibc_e"/><path class="b06ufhbjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:button-x" /></template>
<style>
.b06ufhbjo {
  d: path("M12.75 11.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0m2-1l2 2m0-2l-2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pgqcibc_e {
  d: path("M7.5 5.5h9c3 0 5 2.5 5 6.5v3.5c0 2-1.5 3-3 3c-1.25 0-2-.75-2.75-2h-7.5c-.75 1.25-1.5 2-2.75 2c-1.5 0-3-1-3-3V12c0-4 2-6.5 5-6.5m-2 5.75h4m-2-2v4");
}

</style>
