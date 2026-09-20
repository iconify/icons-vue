<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dazmnqbya"/><path class="emo-jf0pj"/><path class="d_b1a31kv"/><path class="sbr7qlk2q"/><path class="kfx9jcc5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deepfake-detect-outline-thin" /></template>
<style>
.d_b1a31kv {
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dazmnqbya {
  d: path("M3 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.emo-jf0pj {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfx9jcc5b {
  d: path("m19.5 19.5 2 2");
}

.sbr7qlk2q {
  d: path("M12.5 16.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
