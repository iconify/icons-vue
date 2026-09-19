<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i43b3bb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-table-rows" /></template>
<style>
.i43b3bb4i {
  fill: currentColor;
  d: path("M21 8H3V4h18zm0 2H3v4h18zm0 6H3v4h18z");
}

</style>
