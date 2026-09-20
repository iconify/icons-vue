<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bn_pu6j-z"/><path class="a620nromn"/><path class="trhc5pjmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-symlink-outline-bold" /></template>
<style>
.a620nromn {
  d: path("m9 17 5 -5");
}

.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.trhc5pjmi {
  d: path("M10.5 11.5h4v4");
}

</style>
