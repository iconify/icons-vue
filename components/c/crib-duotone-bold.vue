<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nu0ti3ggl"/><path class="hpm6v1-ys"/><path class="f1jx28xzz"/><path class="ln_5yacac"/><path class="i54rsub8x"/><path class="mvhgd7dyo"/><path class="vhnbtvbtn"/><path class="jkuojibnm"/><path class="h7wibbbny"/><path class="ler50rfbf"/><path class="xl6k1lbjd"/><path class="y4qjbbcmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crib-duotone-bold" /></template>
<style>
.f1jx28xzz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7wibbbny {
  d: path("M3 6v14");
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i54rsub8x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.ln_5yacac {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mvhgd7dyo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nu0ti3ggl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
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
