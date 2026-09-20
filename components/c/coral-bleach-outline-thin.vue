<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpe7e61mu"/><path class="w5v-kac9c"/><path class="og6hgh--o"/><path class="bos0j4biy"/><path class="xdkb5ybpc"/><path class="hhrer6blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coral-bleach-outline-thin" /></template>
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og6hgh--o {
  d: path("M15 21V11l-3 -3");
}

.w5v-kac9c {
  d: path("m8 15 4 -4");
}

.xdkb5ybpc {
  d: path("m16 4 5 5");
}

</style>
