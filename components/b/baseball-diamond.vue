<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sskg1dx8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baseball-diamond" /></template>
<style>
.sskg1dx8x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.406 2.345q-.582-.582-1.405-.582t-1.405.582t-.583 1.406q0 .314.085.592l-5.755 5.755q-.278-.085-.592-.085q-.823 0-1.405.582q-.583.583-.583 1.406t.582 1.405q.583.583 1.406.583q.314 0 .592-.085l6.067 6.066q.659.66 1.591.66t1.591-.66l6.067-6.066q.278.085.592.085q.823 0 1.405-.582q.583-.583.583-1.406t-.582-1.405l-.001-.001q-.582-.582-1.405-.582q-.314 0-.592.085l-5.755-5.755q.085-.278.085-.592q0-.823-.582-1.405M9.75 12q0-2.25 2.25-2.25T14.25 12T12 14.25T9.75 12");
}

</style>
