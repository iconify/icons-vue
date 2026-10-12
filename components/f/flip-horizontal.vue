<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb8zptfkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flip-horizontal" /></template>
<style>
.bb8zptfkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25v2.5m0 2.5v2.5m0 2.5v2.5m0 2.5v2.5M9 8.575v6.85q0 1.2-1.2 1.2H4.2q-1.2 0-.55-1.01l4.7-7.23q.65-1.01.65.19m6 0v6.85q0 1.2 1.2 1.2h3.6q1.2 0 .55-1.01l-4.7-7.23q-.65-1.01-.65.19");
}

</style>
