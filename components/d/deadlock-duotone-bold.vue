<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fnc3mtkwk"/><path class="y7qci6b0u"/><path class="fz5akybya"/><path class="dp2edxbew"/><path class="rncaisbya"/><path class="bqqmp9bon"/><path class="a1z8vac9r"/><path class="yzk-0x3pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deadlock-duotone-bold" /></template>
<style>
.a1z8vac9r {
  d: path("M17.5 16H22");
}

.bqqmp9bon {
  d: path("M6.5 5.5 9 8l-2.5 2.5");
}

.dp2edxbew {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 13.5 15 16l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnc3mtkwk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fz5akybya {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rncaisbya {
  d: path("M2 8h4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y7qci6b0u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.5 5.5 9 8l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yzk-0x3pl {
  d: path("M17.5 13.5 15 16l2.5 2.5");
}

</style>
