<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jd882cb_k"/><path class="j33qrnb7r"/><path class="nq0_nyzpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:iron-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j33qrnb7r {
  d: path("M10 11c0 -6 7 -6 7 0");
}

.jd882cb_k {
  d: path("m4 16 5 -5h9v5Z");
}

.nq0_nyzpb {
  d: path("M4 19h14");
}

</style>
