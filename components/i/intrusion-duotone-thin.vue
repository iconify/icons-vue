<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja0_o1hya"/><path class="beqem0mpw"/><path class="tpht7obqo"/><path class="q7wdp7bit"/><path class="ftqzjnb8u"/><path class="u649he-6w"/><path class="f-x5yl3mg"/><path class="vsmfi0bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:intrusion-duotone-thin" /></template>
<style>
.beqem0mpw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f-x5yl3mg {
  d: path("M2 12h11");
}

.ftqzjnb8u {
  d: path("M6 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja0_o1hya {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q7wdp7bit {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tpht7obqo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u649he-6w {
  d: path("M18 3v18");
}

.vsmfi0bcq {
  d: path("m10 9 3 3 -3 3");
}

</style>
