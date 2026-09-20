<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eutkufbau"/><path class="khi6_jbul"/><path class="j46kunmxj"/><path class="pl_bf8bxp"/><path class="rdh7npbwk"/><path class="cr7psearj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-agent-duotone-thin" /></template>
<style>
.cr7psearj {
  d: path("m15 13 2.5 2.5L15 18");
}

.eutkufbau {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.69 2.87a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j46kunmxj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 13 2.5 2.5L15 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khi6_jbul {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 13 -2.5 2.5L9 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pl_bf8bxp {
  d: path("M13.69 2.87a4 4 0 1 1 -3.38 0");
}

.rdh7npbwk {
  d: path("m9 13 -2.5 2.5L9 18");
}

</style>
