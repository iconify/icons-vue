<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikg5npbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:intraoral-scanner" /></template>
<style>
.ikg5npbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 19.25l10-10L14.5 4.5h5.25a1.75 1.75 0 0 1 0 3.5H17.5L4.75 21.25a1.5 1.5 0 0 1-2-2M17 15.5c-1.25 0-1.75.75-1.75 2s.75 2 1 2.75l.5 1.5h1l.5-1.5l.5 1.5h1l.5-1.5c.25-.75 1-1.5 1-2.75s-.5-2-1.75-2c-.5 0-.75.25-1.25.25s-.75-.25-1.25-.25");
}

</style>
