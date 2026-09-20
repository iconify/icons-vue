<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pdamdwx-i"/><path class="c4o3x9bhp"/><path class="zg6lybc6r"/><path class="h-fyw90ib"/><path class="c19ia0bqf"/><path class="e6eq72cni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dog-walk-outline-bold" /></template>
<style>
.c19ia0bqf {
  d: path("M3 13h3");
}

.c4o3x9bhp {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e6eq72cni {
  d: path("M3 17h3");
}

.h-fyw90ib {
  d: path("M16 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pdamdwx-i {
  d: path("M13 19c-2.5 0 -4.5 -2 -4.5 -4s2 -3.5 4.5 -3.5 4.5 1.5 4.5 3.5 -2 4 -4.5 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zg6lybc6r {
  d: path("M12 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
