<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uui15ob0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ketupat" /></template>
<style>
.uui15ob0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.85 6.91l5.3 5.68q.85.91 0 1.82l-5.3 5.68q-.85.91-1.7 0l-5.3-5.68q-.85-.91 0-1.82l5.3-5.68q.85-.91 1.7 0M9.4 10.75l5.2 5.5m0-5.5l-5.2 5.5M12 6c0-1.75 1.25-2.75 3.25-3.25M12 6c-.5-1.5-1.75-2.5-3.5-3");
}

</style>
