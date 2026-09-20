<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oucg--bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-off-24-regular" /></template>
<style>
.oucg--bpf {
  fill: currentColor;
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06L6.94 8H3.75a.75.75 0 0 0 0 1.5h4.69l5 5H3.75a.75.75 0 0 0 0 1.5h11.19l5.78 5.78a.75.75 0 0 0 1.06-1.06zM20.25 14.5h-2.568l1.5 1.5h1.068a.75.75 0 0 0 0-1.5M11.182 8l1.5 1.5h7.568a.75.75 0 0 0 0-1.5z");
}

</style>
