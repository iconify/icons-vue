<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ojq3d2bwe"/><path class="ni-_lk7vs"/><path class="c3wl0l-ou"/><path class="hpd-e505b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-load-outline-bold" /></template>
<style>
.c3wl0l-ou {
  d: path("M19 13v6");
}

.hpd-e505b {
  d: path("M16.5 15.5 19 13l2.5 2.5");
}

.ni-_lk7vs {
  d: path("M5 5h10v6H5");
}

.ojq3d2bwe {
  d: path("M5 3v18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
