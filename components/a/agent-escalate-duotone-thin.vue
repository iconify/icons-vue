<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qv4kmp1lx"/><path class="v1898kstq"/><path class="fajysd5vp"/><path class="qvqi41cih"/><path class="j2aic6ujd"/><path class="c3xkdj8uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-escalate-duotone-thin" /></template>
<style>
.c3xkdj8uw {
  d: path("M14.5 5H19v4.5");
}

.fajysd5vp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 5H19v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2aic6ujd {
  d: path("m12 12 7 -7");
}

.qv4kmp1lx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qvqi41cih {
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
}

.v1898kstq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
