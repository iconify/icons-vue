<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh3wi6bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-box-labelled" /></template>
<style>
.qh3wi6bho {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.364 7.602Q3.25 7.785 3.25 8v11q0 2.75 2.75 2.75h12q2.75 0 2.75-2.75V7.987q-.004-.208-.114-.384l-.001-.001l-2.499-3.999q-.051-.081-.12-.147t-.152-.112q-.084-.046-.176-.07q-.093-.024-.188-.024h-11q-.095 0-.188.024q-.092.024-.176.07t-.152.112q-.069.066-.12.147zM4.75 8.75h14.5V19q0 1.25-1.25 1.25H6q-1.25 0-1.25-1.25zm6 2.5h2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T8.25 13.75q0-2.5 2.5-2.5");
}

</style>
