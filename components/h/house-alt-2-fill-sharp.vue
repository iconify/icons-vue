<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7pctvthv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-fill-sharp" /></template>
<style>
.a7pctvthv {
  fill: currentColor;
  d: path("m12.659 2.247l8 7c.217.19.341.465.341.753v10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0M14 17a2 2 0 1 0-4 0v3h4Z");
}

</style>
