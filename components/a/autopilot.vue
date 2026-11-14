<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_gkrx4hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autopilot" /></template>
<style>
.u_gkrx4hq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9c.9 0 1.5.9 1.5 1.75v2.75l7 3.5v1.75l-7-2V19l1.75 1.25v1.25L12 20.75l-3.25.75v-1.25L10.5 19v-2.25l-7 2V17l7-3.5v-2.75C10.5 9.9 11.1 9 12 9Zm0-6h.01M12 6h.01");
}

</style>
