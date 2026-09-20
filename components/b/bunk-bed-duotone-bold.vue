<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ii7e-fwzi"/><path class="uda6dfbwy"/><path class="ep-y49mzs"/><path class="kr5tlbbsn"/><path class="oti3l4bvo"/><path class="ozi-k-boi"/><path class="hdk8dzk2v"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bunk-bed-duotone-bold" /></template>
<style>
.ep-y49mzs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21v-7h18v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hdk8dzk2v {
  d: path("M3 21v-7h18v7");
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.ii7e-fwzi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11V4h18v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr5tlbbsn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oti3l4bvo {
  d: path("M3 11V4h18v7");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uda6dfbwy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
