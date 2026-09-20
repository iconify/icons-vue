<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py67ssbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keep" /></template>
<style>
.py67ssbip {
  fill: currentColor;
  d: path("M15 12.423L16.577 14v1H12.5v5l-.5.5l-.5-.5v-5H7.423v-1L9 12.423V5H8V4h8v1h-1z");
}

</style>
