<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzeve79sx"/><path class="kr_5zj0-c"/><path class="k8amg6c_b"/><path class="n9yjqng3t"/><path class="l597m_b4s"/><path class="m0rrtedwx"/><path class="ymw3aibdo"/><path class="tturp2djn"/><path class="maut9lbea"/><path class="vzsi2jzmx"/><path class="efnc6pc0s"/><path class="a0o0t-zvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:community-duotone-thin" /></template>
<style>
.a0o0t-zvo {
  d: path("M15 19a3 3 0 0 1 6 0");
}

.efnc6pc0s {
  d: path("M16 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k8amg6c_b {
  fill: currentColor;
  d: path("M16 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kr_5zj0-c {
  fill: currentColor;
  d: path("M4 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l597m_b4s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m0rrtedwx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 19a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.maut9lbea {
  d: path("M4 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n9yjqng3t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tturp2djn {
  d: path("M9 11a3 3 0 0 1 6 0");
}

.vzsi2jzmx {
  d: path("M3 19a3 3 0 0 1 6 0");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
