<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="unjh48car"/><path class="ik93a37tn"/><path class="b3h_rz89d"/><path class="hqwsf4bjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kill-switch-outline-bold" /></template>
<style>
.b3h_rz89d {
  d: path("m6 11 2 2");
}

.hqwsf4bjq {
  d: path("m8 11 -2 2");
}

.ik93a37tn {
  d: path("M4 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.unjh48car {
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
}

</style>
