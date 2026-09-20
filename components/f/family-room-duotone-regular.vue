<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hukhzyb1k"/><path class="xqf0gobwm"/><path class="vnt7vst1g"/><path class="r7hxvljcl"/><path class="xsfomkbcp"/><path class="qg3b3u-3z"/><path class="n7pu66d5h"/><path class="kr6epu66n"/><path class="uobswubeq"/><path class="p-u3ngpfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-room-duotone-regular" /></template>
<style>
.hukhzyb1k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18v-8h10v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr6epu66n {
  d: path("M4 10V7h4v3");
}

.n7pu66d5h {
  d: path("M2 13.5h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-u3ngpfy {
  d: path("M15 15.5h7");
}

.qg3b3u-3z {
  d: path("M2 18v-8h10v8");
}

.r7hxvljcl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 18v-5h7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uobswubeq {
  d: path("M15 18v-5h7v5");
}

.vnt7vst1g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10V7h4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xqf0gobwm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 13.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xsfomkbcp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 15.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
