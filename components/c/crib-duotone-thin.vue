<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9jzbjbwv"/><path class="hsnj9o-9y"/><path class="rcvpd8b-f"/><path class="n8sts3-0i"/><path class="rvgi8v2qv"/><path class="yf6o7bb_j"/><path class="vhnbtvbtn"/><path class="jkuojibnm"/><path class="h7wibbbny"/><path class="ler50rfbf"/><path class="xl6k1lbjd"/><path class="y4qjbbcmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crib-duotone-thin" /></template>
<style>
.h7wibbbny {
  d: path("M3 6v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsnj9o-9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.n8sts3-0i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rcvpd8b-f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rvgi8v2qv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s9jzbjbwv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.yf6o7bb_j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
