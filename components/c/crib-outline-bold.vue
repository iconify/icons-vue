<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vhnbtvbtn"/><path class="jkuojibnm"/><path class="h7wibbbny"/><path class="ler50rfbf"/><path class="xl6k1lbjd"/><path class="y4qjbbcmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crib-outline-bold" /></template>
<style>
.h7wibbbny {
  d: path("M3 6v14");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.xl6k1lbjd {
  d: path("M15 8v12");
}

.y4qjbbcmm {
  d: path("M21 6v14");
}

</style>
