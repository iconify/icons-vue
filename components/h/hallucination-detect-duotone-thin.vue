<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nowdsq6_v"/><path class="bkcnp6b8w"/><path class="hgou-o1yg"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="ov4z8dh4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hallucination-detect-duotone-thin" /></template>
<style>
.bkcnp6b8w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hgou-o1yg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 13.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moha5wbmp {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

.nowdsq6_v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ov4z8dh4a {
  d: path("m8 13.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
}

.yix-58bnj {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
