<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5fngqb7w"/><path class="q60f8gb4t"/><path class="m396qprpg"/><path class="jya260dbk"/><path class="kb54x75jw"/><path class="w0g35mhsz"/><path class="r-0o544te"/><path class="pfvjrtb4r"/><path class="p59zvybqt"/><path class="nk-dq3bmo"/><path class="som9nz4hy"/><path class="k04qs_b8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confetti-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jya260dbk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k04qs_b8d {
  d: path("m9 18 3 3");
}

.kb54x75jw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m396qprpg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 13 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.q60f8gb4t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r-0o544te {
  d: path("m5 4 3 3");
}

.som9nz4hy {
  d: path("m10 10 3 3");
}

.w0g35mhsz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 18 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w5fngqb7w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
