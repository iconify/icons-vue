<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx3jwl65d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-left-24-filled" /></template>
<style>
.gx3jwl65d {
  fill: currentColor;
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10m3.25-12.5h-4.74l5.268 5.217a.75.75 0 1 1-1.056 1.066L9.5 10.61v4.639a.75.75 0 0 1-1.5 0v-6.5A.75.75 0 0 1 8.75 8h6.5a.75.75 0 0 1 0 1.5");
}

</style>
