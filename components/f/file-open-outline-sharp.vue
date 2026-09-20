<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0z9bru1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-open-outline-sharp" /></template>
<style>
.w0z9bru1s {
  fill: currentColor;
  d: path("M4 22V2h10l6 6v6h-2V9h-5V4H6v16h9v2zm17.95.375L19 19.425v2.225h-2V16h5.65v2H20.4l2.95 2.95zM6 20V4z");
}

</style>
