<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="et-iwmblh"/><path class="wg1ykyaxv"/><path class="rc8xkcb_g"/><path class="qitpg1b_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:double-bed-outline-bold" /></template>
<style>
.et-iwmblh {
  d: path("M2 18v-7h20v7");
}

.qitpg1b_y {
  d: path("M13 11V8h5v3");
}

.rc8xkcb_g {
  d: path("M4 11V8h5v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wg1ykyaxv {
  d: path("M2 14.5h20");
}

</style>
