<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="is4rzhsst"/><path class="tc-ybhuxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collapse-block-outline-bold" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.is4rzhsst {
  d: path("m10 7 2 2 2 -2");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tc-ybhuxl {
  d: path("m10 17 2 -2 2 2");
}

</style>
