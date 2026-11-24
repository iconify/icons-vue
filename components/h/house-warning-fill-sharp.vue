<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2rzyac1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-warning-fill-sharp" /></template>
<style>
.m2rzyac1t {
  fill: currentColor;
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0ZM13 14v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m-.99 2H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
