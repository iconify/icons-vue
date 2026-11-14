<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs030ebrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-rec" /></template>
<style>
.qs030ebrb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 5.25h4.25q2.123 0 3.624 1.501q1.09 1.091 1.389 2.509l2.352-1.373q1.25-.729 2.505-.008t1.255 2.168v3.906q0 1.447-1.255 2.168t-2.505-.008l-2.352-1.373q-.299 1.418-1.389 2.509q-1.501 1.501-3.624 1.501h-4.25q-2.123 0-3.624-1.501T1.75 13.625v-3.25q0-2.123 1.501-3.624T6.875 5.25");
}

</style>
