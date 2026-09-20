<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rbwrj-biq"/><path class="uwjz-dbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cloud-check-outline-bold" /></template>
<style>
.rbwrj-biq {
  d: path("M4 18a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 9a5.5 5.5 0 0 1 4.5 9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uwjz-dbef {
  d: path("m9 12 2 2 4 -4");
}

</style>
