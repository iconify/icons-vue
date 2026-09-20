<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kzwfngmve"/><path class="yyw12k01a"/><path class="e2nq-yvbg"/><path class="cmfzxibyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:glacier-tier-outline-thin" /></template>
<style>
.cmfzxibyz {
  d: path("M17 15v3.5");
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzwfngmve {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.yyw12k01a {
  d: path("M7 15v3.5");
}

</style>
