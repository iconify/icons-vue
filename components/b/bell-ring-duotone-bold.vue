<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yt70p9btb"/><path class="hpm6v1-ys"/><path class="nyemwxbgc"/><path class="qnl8qubgm"/><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="qbvk0cc3q"/><path class="v4cpchbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-ring-duotone-bold" /></template>
<style>
.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nyemwxbgc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qbvk0cc3q {
  d: path("m3 9 2 -2");
}

.qnl8qubgm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 9 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.v4cpchbya {
  d: path("m21 9 -2 -2");
}

.yt70p9btb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
