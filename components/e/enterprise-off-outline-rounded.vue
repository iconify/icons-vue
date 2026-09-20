<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql5d9wb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:enterprise-off-outline-rounded" /></template>
<style>
.ql5d9wb6b {
  fill: currentColor;
  d: path("M19.8 22.6L18.2 21H4q-.825 0-1.412-.587T2 19V8q0-.825.588-1.412T4 6h2l2 2H4v11h12.175L1.4 4.2q-.275-.275-.287-.688T1.4 2.8q.275-.275.7-.275t.7.275l18.4 18.4q.275.275.275.7t-.275.7t-.7.275t-.7-.275M22 8v8.75q0 .5-.312.75t-.688.25t-.687-.262t-.313-.763V8h-8.325q-.4 0-.763-.15t-.637-.425l-1.7-1.7Q8.3 5.45 8.15 5.088T8 4.325V4q0-.825.587-1.412T10 2h4q.825 0 1.413.588T16 4v2h4q.825 0 1.413.588T22 8M10 6h4V4h-4zm.7 7.5");
}

</style>
