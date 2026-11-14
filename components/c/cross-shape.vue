<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojvc0fd8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cross-shape" /></template>
<style>
.ojvc0fd8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 1.75h3q2.25 0 2.25 2.25v1q0 .75.75.75H18q2.25 0 2.25 2.25v3q0 .932-.659 1.591T18 13.25h-1.5q-.75 0-.75.75v6q0 2.25-2.25 2.25h-3q-2.25 0-2.25-2.25v-6q0-.75-.75-.75H6q-.932 0-1.591-.659T3.75 11V8q0-2.25 2.25-2.25h1.5q.75 0 .75-.75V4q0-2.25 2.25-2.25");
}

</style>
