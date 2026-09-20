<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja0_o1hya"/><path class="kh4dfab7k"/><path class="ypf3r7bct"/><path class="k8uwgqv6n"/><path class="ftqzjnb8u"/><path class="tkvxdludj"/><path class="k58vknb8e"/><path class="a1go-lhea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-failed-duotone-thin" /></template>
<style>
.a1go-lhea {
  d: path("m21 13 -5 5");
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

.k58vknb8e {
  d: path("m16 13 5 5");
}

.k8uwgqv6n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 13 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kh4dfab7k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3h9l-3 3 3 3H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tkvxdludj {
  d: path("M6 3h9l-3 3 3 3H6");
}

.ypf3r7bct {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 13 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
