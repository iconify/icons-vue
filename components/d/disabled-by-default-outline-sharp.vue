<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o91o80bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:disabled-by-default-outline-sharp" /></template>
<style>
.o91o80bsg {
  fill: currentColor;
  d: path("M5 19h14V5H5zm-2 2V3h18v18zm5.4-4l3.6-3.6l3.6 3.6l1.4-1.4l-3.6-3.6L17 8.4L15.6 7L12 10.6L8.4 7L7 8.4l3.6 3.6L7 15.6zM5 19V5z");
}

</style>
