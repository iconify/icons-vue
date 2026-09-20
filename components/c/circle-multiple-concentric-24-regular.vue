<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-ctg_bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-multiple-concentric-24-regular" /></template>
<style>
.d-ctg_bsa {
  fill: currentColor;
  d: path("M3.5 12a8.5 8.5 0 1 1 17 0a8.5 8.5 0 0 1-17 0M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2M7.5 12a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0M12 6a6 6 0 1 0 0 12a6 6 0 0 0 0-12");
}

</style>
