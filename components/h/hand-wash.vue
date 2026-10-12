<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta2xqz_lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-wash" /></template>
<style>
.ta2xqz_lr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h6.5a2.5 2.5 0 0 1 2.5 2.5v.5m0 2c.85 1.15 1.5 1.95 1.5 2.65a1.5 1.5 0 0 1-3 0c0-.7.65-1.5 1.5-2.65m-9 6.5h12.5l3.4-2.2a1.6 1.6 0 0 1 2 2.45l-4.3 4.65a3.6 3.6 0 0 1-2.65 1.1H6.5a3.75 3.75 0 0 1-3.75-3.75Z");
}

</style>
