<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3b8w1bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-16-filled" /></template>
<style>
.z3b8w1bgp {
  fill: currentColor;
  d: path("M8 1.75A6.25 6.25 0 0 1 14.25 8a.75.75 0 0 1-1.5 0a4.75 4.75 0 1 0-8.25 3.212v-.462a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h.913A6.25 6.25 0 0 1 8 1.75m0 4a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 0 1 0-4.5m0 1.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
