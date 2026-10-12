<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f7gde_fqn"/><rect class="ntfxyx1qi"/><path class="lxn3b3blr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buddhist-temple" /></template>
<style>
.f7gde_fqn {
  d: path("m12.39 3.21l3.72 4.33q.39.46.99.46h1.55q.6 0 .91.51l1.38 2.23q.31.51-.29.51H3.35q-.6 0-.29-.51l1.38-2.23Q4.75 8 5.35 8H6.9q.6 0 .99-.46l3.72-4.33q.39-.46.78 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxn3b3blr {
  d: path("M10.25 21.25V18a1.75 1.75 0 0 1 3.5 0v3.25");
}

.ntfxyx1qi {
  width: 12px;
  height: 10px;
  x: 6px;
  y: 11.25px;
  rx: 0.5px;
}

</style>
