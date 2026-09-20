<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="epnnrbb2h"/><path class="w7vum8war"/><path class="lf5ycds2m"/><path class="fce-vbb2c"/><path class="z6s_w0bbl"/><path class="a7h45wbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deploy-agent-duotone-thin" /></template>
<style>
.a7h45wbtv {
  d: path("M15.5 8.5 18 6l2.5 2.5");
}

.epnnrbb2h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.11 9.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fce-vbb2c {
  d: path("M10.11 9.47a5 5 0 1 1 -4.22 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf5ycds2m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 8.5 18 6l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w7vum8war {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 8v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z6s_w0bbl {
  d: path("M18 8v11");
}

</style>
