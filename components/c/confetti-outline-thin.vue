<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-0o544te"/><path class="pfvjrtb4r"/><path class="p59zvybqt"/><path class="nk-dq3bmo"/><path class="som9nz4hy"/><path class="k04qs_b8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confetti-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k04qs_b8d {
  d: path("m9 18 3 3");
}

.nk-dq3bmo {
  d: path("m16 14 3 3");
}

.p59zvybqt {
  d: path("m4 13 3 3");
}

.pfvjrtb4r {
  d: path("m15 5 3 3");
}

.r-0o544te {
  d: path("m5 4 3 3");
}

.som9nz4hy {
  d: path("m10 10 3 3");
}

</style>
