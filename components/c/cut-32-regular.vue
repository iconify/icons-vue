<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gwo0-rmen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cut-32-regular" /></template>
<style>
.gwo0-rmen {
  fill: currentColor;
  d: path("M8.454 2.162a1 1 0 0 1 1.324.209l.06.083l11.05 16.969a5.5 5.5 0 1 1-1.678 1.09L16 15.582l-3.21 4.933a5.5 5.5 0 1 1-1.678-1.09l3.695-5.676L8.162 3.546l-.052-.089a1 1 0 0 1 .344-1.295M9 21a3.5 3.5 0 1 0 2.085.689l-.176-.123A3.5 3.5 0 0 0 9 21m14 0a3.5 3.5 0 0 0-1.91.566l-.175.123A3.5 3.5 0 1 0 23 21m-.778-18.629a1.001 1.001 0 0 1 1.668 1.086l-.052.089l-5.75 8.829l-1.194-1.833l5.268-8.088z");
}

</style>
