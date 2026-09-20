<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hb_6svr8j"/><path class="bi34yzw-v"/><path class="urzumpb2c"/><path class="qowfo405a"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-view-outline-bold" /></template>
<style>
.bi34yzw-v {
  d: path("M12 21V4h7v17");
}

.hb_6svr8j {
  d: path("M3 21V10h7v11");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.qowfo405a {
  d: path("M12 9h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.urzumpb2c {
  d: path("M3 14h7");
}

</style>
