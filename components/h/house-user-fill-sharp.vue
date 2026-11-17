<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e32fofwvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-fill-sharp" /></template>
<style>
.e32fofwvp {
  fill: currentColor;
  d: path("M20 22H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0l8 7c.217.19.341.465.341.753v11a1 1 0 0 1-1 1M9.236 9.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M16.901 20a5.003 5.003 0 0 0-9.802 0Z");
}

</style>
