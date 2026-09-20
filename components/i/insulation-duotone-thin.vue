<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jb48lmb-m"/><path class="kq_o6ubcg"/><path class="r7xk8o29f"/><path class="s7eyaw7qq"/><path class="tkeq0bpvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:insulation-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jb48lmb-m {
  fill: currentColor;
  d: path("M4 4v16h6V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kq_o6ubcg {
  d: path("M4 4v16h6V4Z");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s7eyaw7qq {
  d: path("M15 4v16");
}

.tkeq0bpvv {
  d: path("M18 4v16");
}

</style>
