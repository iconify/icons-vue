<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhbcwncwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-fill-sharp" /></template>
<style>
.fhbcwncwj {
  fill: currentColor;
  d: path("M8 8V3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7.625c0-.288.124-.563.341-.753l5-4.375C7.524 8.088 7.758 8 8 8m12 12V4H10v5.421l3.659 3.201c.217.19.341.465.341.753V20ZM13 6h.01a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
