<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8c9hebsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goal-tile-11" /></template>
<style>
.c8c9hebsq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.75h8.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 2.123-1.501 3.624t-3.624 1.501h-8.25q-2.123 0-3.624-1.501T2.75 16.125v-8.25q0-2.123 1.501-3.624T7.875 2.75m-.294 4.831Q5.75 9.411 5.75 12t1.831 4.419T12 18.25t4.419-1.831Q18.25 14.589 18.25 12t-1.831-4.419Q14.589 5.75 12 5.75T7.581 7.581");
}

</style>
