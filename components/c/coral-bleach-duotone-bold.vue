<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v_nyfvbyu"/><path class="y3t077e3v"/><path class="ujl-4mb1n"/><path class="kkm03rbxe"/><path class="yavpvp81d"/><path class="tqt64acjw"/><path class="bpe7e61mu"/><path class="w5v-kac9c"/><path class="og6hgh--o"/><path class="bos0j4biy"/><path class="xdkb5ybpc"/><path class="hhrer6blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coral-bleach-duotone-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.bpe7e61mu {
  d: path("M8 21v-9L5 9");
}

.hhrer6blk {
  d: path("m21 4 -5 5");
}

.kkm03rbxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.og6hgh--o {
  d: path("M15 21V11l-3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tqt64acjw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 4 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ujl-4mb1n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 21V11l-3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v_nyfvbyu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21v-9L5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w5v-kac9c {
  d: path("m8 15 4 -4");
}

.xdkb5ybpc {
  d: path("m16 4 5 5");
}

.y3t077e3v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yavpvp81d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 4 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
