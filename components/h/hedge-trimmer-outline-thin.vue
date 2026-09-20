<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ah8uvpf1o"/><path class="svo3n0y2p"/><path class="opzncliew"/><path class="fbw2ldgtv"/><path class="x6walc0pr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hedge-trimmer-outline-thin" /></template>
<style>
.ah8uvpf1o {
  d: path("M3 10h13");
}

.fbw2ldgtv {
  d: path("M12 10v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.opzncliew {
  d: path("M8 10v7");
}

.svo3n0y2p {
  d: path("M4 10v7");
}

.x6walc0pr {
  d: path("M16 7h5v6h-5Z");
}

</style>
