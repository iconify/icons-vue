<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="admyrfbak"/><path class="elpvour1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-injector" /></template>
<style>
.admyrfbak {
  width: 4.5px;
  height: 2.5px;
  x: 9.75px;
  y: 2.75px;
  rx: 0.75px;
}

.elpvour1q {
  d: path("M9 5.25h6q.75 0 .75.75v4.25q0 .75-.46 1.34l-1.58 2.07q-.46.59-1.21.59h-1q-.75 0-1.21-.59l-1.58-2.07q-.46-.59-.46-1.34V6q0-.75.75-.75M8.25 8.5h7.5M12 18.25v3m-3-3l-1.5 3m7.5-3l1.5 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
