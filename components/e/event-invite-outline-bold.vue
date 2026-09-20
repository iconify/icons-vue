<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gd3gqxb-h"/><path class="xat4txb_y"/><path class="bswpu5b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-invite-outline-bold" /></template>
<style>
.bswpu5b0n {
  d: path("M8 11V4h8v7");
}

.gd3gqxb-h {
  d: path("M6 11v9h12v-9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xat4txb_y {
  d: path("m6 11 6 6 6 -6");
}

</style>
