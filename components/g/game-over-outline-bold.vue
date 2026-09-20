<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cnjkjfbvs"/><path class="po0gsxbro"/><path class="x5uilr-gd"/><path class="j3tm7xb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-over-outline-bold" /></template>
<style>
.cnjkjfbvs {
  d: path("M3 5v14h18V5Z");
}

.j3tm7xb5y {
  d: path("M14 15h4");
}

.po0gsxbro {
  d: path("m8 10 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x5uilr-gd {
  d: path("m12 10 -4 4");
}

</style>
