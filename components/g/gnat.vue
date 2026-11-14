<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hng2hsm0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gnat" /></template>
<style>
.hng2hsm0v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 6q0-3 3-3t3 3t-3 3t-3-3m18 3q0-3-3-3t-3 3t3 3t3-3M10 21q-3 0-3-3t3-3t3 3t-3 3");
}

</style>
