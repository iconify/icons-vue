<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5-q74p6w"/><path class="os0u_ybvj"/><path class="lo-takblv"/><path class="vzmsaswpp"/><path class="ic5avwb5p"/><path class="qg3b3u-3z"/><path class="n7pu66d5h"/><path class="kr6epu66n"/><path class="uobswubeq"/><path class="p-u3ngpfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-room-duotone-thin" /></template>
<style>
.f5-q74p6w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18v-8h10v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic5avwb5p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 15.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr6epu66n {
  d: path("M4 10V7h4v3");
}

.lo-takblv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10V7h4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n7pu66d5h {
  d: path("M2 13.5h10");
}

.os0u_ybvj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p-u3ngpfy {
  d: path("M15 15.5h7");
}

.qg3b3u-3z {
  d: path("M2 18v-8h10v8");
}

.uobswubeq {
  d: path("M15 18v-5h7v5");
}

.vzmsaswpp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 18v-5h7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
