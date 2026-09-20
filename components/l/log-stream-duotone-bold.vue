<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="ppqzlq-xl"/><path class="esmr09stj"/><path class="s6ccfofjv"/><path class="i592trbjx"/><path class="k6nj2fbya"/><path class="sixdm4bhp"/><path class="k62k_4bsl"/><path class="n7wfhbrgu"/><path class="cxodqhtoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:log-stream-duotone-bold" /></template>
<style>
.cxodqhtoo {
  d: path("m19 17 2 2 -2 2");
}

.esmr09stj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i592trbjx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 17 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k62k_4bsl {
  d: path("M3 13h16");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.n7wfhbrgu {
  d: path("M3 17h11");
}

.ppqzlq-xl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s6ccfofjv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sixdm4bhp {
  d: path("M3 9h14");
}

</style>
