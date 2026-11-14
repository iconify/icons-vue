<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd3lt1l8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hidden-gem" /></template>
<style>
.xd3lt1l8h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.236 3.25H7.764q-1.146 0-1.82.927L3.059 8.144q-.245.337-.366.672q.146-.066.307-.066h18q.161 0 .307.066q-.121-.335-.366-.672l-2.885-3.967q-.674-.927-1.82-.927m-2.667 7h-3.138L12 17.469zm-.729 10.416l2.264-10.416H21q.147 0 .283-.055q-.134.33-.39.658l-7.121 9.1q-.395.504-.932.713M3 10.25h5.896l2.264 10.417q-.537-.21-.931-.714l-7.122-9.1q-.256-.328-.39-.658q.136.055.283.055");
}

</style>
