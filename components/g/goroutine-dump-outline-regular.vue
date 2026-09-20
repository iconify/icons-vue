<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="g587irb4v"/><path class="hv3ppsbji"/><path class="hd5-m5bld"/><path class="ffipo4b5s"/><path class="h1j63eveo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:goroutine-dump-outline-regular" /></template>
<style>
.ffipo4b5s {
  d: path("M9 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g587irb4v {
  d: path("M7 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.h1j63eveo {
  d: path("M13 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hd5-m5bld {
  d: path("M15 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hv3ppsbji {
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
