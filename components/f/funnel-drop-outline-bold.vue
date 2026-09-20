<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ozi-k-boi"/><path class="wlp3ibbib"/><path class="c3wl0l-ou"/><path class="yhbiuccel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funnel-drop-outline-bold" /></template>
<style>
.c3wl0l-ou {
  d: path("M19 13v6");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

.yhbiuccel {
  d: path("m16 16 3 3 3 -3");
}

</style>
