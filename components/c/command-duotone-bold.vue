<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m7v_-fb1c"/><path class="ba2-z1m9x"/><path class="wptmod37f"/><path class="o9x6y_bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:command-duotone-bold" /></template>
<style>
.ba2-z1m9x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 10 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7v_-fb1c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 4v10H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o9x6y_bij {
  d: path("m9 10 -4 4 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wptmod37f {
  d: path("M21 4v10H5");
}

</style>
