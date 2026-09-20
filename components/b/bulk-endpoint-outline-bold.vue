<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n0n63pb2v"/><path class="g5avrpbyu"/><path class="pty_wsbvs"/><path class="d1t4ffbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bulk-endpoint-outline-bold" /></template>
<style>
.d1t4ffbbq {
  d: path("M8 12.5h8");
}

.g5avrpbyu {
  d: path("M8 5.5h8");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
