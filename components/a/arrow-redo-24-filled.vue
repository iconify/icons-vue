<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wciwc7bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-redo-24-filled" /></template>
<style>
.wciwc7bzk {
  fill: currentColor;
  d: path("m18 7.586l-3.64-3.635a6.66 6.66 0 1 0-9.42 9.42l8.339 8.337a1 1 0 0 0 1.414-1.415l-8.339-8.336A4.66 4.66 0 0 1 12.771 5.2l.174.166l3.64 3.633H12a1 1 0 0 0-.993.884L11 10a1 1 0 0 0 .883.993l.117.006h7a1 1 0 0 0 .993-.883L20 10V3.002a1 1 0 0 0-1.993-.116L18 3.002zl-3.64-3.635z");
}

</style>
