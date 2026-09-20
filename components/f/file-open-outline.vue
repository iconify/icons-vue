<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaytir-iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-open-outline" /></template>
<style>
.aaytir-iq {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v6h-2V9h-5V4H6v16h9v2zm15.95.375L19 19.425v2.225h-2V16h5.65v2H20.4l2.95 2.95zM6 20V4z");
}

</style>
