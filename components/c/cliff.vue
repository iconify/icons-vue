<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnx1rchzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cliff" /></template>
<style>
.hnx1rchzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.45V7.8q0-.8.79-.94l9.67-1.72q.79-.14 1.4.37l.28.23q.61.51.25 1.23l-1.03 2.06q-.36.72-.09 1.47l.71 2q.27.75-.05 1.49l-.86 2.02q-.32.74-.15 1.52l.66 2.94q.17.78-.63.78H3.55q-.8 0-.8-.8m2.75-6.2L11 13m6.25 2.75c.67-.5 1.33-.5 2 0s1.33.5 2 0m-4 3.75c.67-.5 1.33-.5 2 0s1.33.5 2 0");
}

</style>
