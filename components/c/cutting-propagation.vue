<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vu9shvz5y"/><path class="q40u_qb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cutting-propagation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q40u_qb4d {
  d: path("m10 18.5l2-2l2 2");
}

.vu9shvz5y {
  d: path("m6 6l1.5 15.5h9L18 6M6.5 10h11M12 2.5v14");
}

</style>
