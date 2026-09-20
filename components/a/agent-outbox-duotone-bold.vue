<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ni70f7bxk"/><path class="y5cv68hjs"/><path class="h92mhcbzw"/><path class="q72gad6sw"/><path class="rk0ztqbwb"/><path class="ag39tfb0x"/><path class="zy0mbfbon"/><path class="inae6abkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-outbox-duotone-bold" /></template>
<style>
.ag39tfb0x {
  d: path("M12 15v6h10v-6");
}

.h92mhcbzw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 8v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.inae6abkl {
  d: path("M14.5 10.5 17 8l2.5 2.5");
}

.ni70f7bxk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q72gad6sw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 10.5 17 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rk0ztqbwb {
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y5cv68hjs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 15v6h10v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zy0mbfbon {
  d: path("M17 8v5");
}

</style>
