<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5sio_aje"/><path class="fz6tc-4je"/><path class="q7wdp7bit"/><path class="vgx27qokn"/><path class="o8scmcc3i"/><path class="vsmfi0bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:login-duotone-thin" /></template>
<style>
.fz6tc-4je {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8scmcc3i {
  d: path("M3 12h10");
}

.q7wdp7bit {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vgx27qokn {
  d: path("M15 3h6v18h-6");
}

.vsmfi0bcq {
  d: path("m10 9 3 3 -3 3");
}

.z5sio_aje {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 3h6v18h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
