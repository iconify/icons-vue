<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szhdb3b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-32-filled" /></template>
<style>
.szhdb3b-b {
  fill: currentColor;
  d: path("M19.09 10.5H19a2 2 0 0 0-2 2v7a4 4 0 0 1-4 4h-.09A5.502 5.502 0 0 1 2 22.5a5.5 5.5 0 0 1 10.91-1H13a2 2 0 0 0 2-2v-7a4 4 0 0 1 4-4h.09A5.502 5.502 0 0 1 30 9.5a5.5 5.5 0 0 1-10.91 1");
}

</style>
