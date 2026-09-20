<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="av_kt1b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-horizontal-20-filled" /></template>
<style>
.av_kt1b3x {
  fill: currentColor;
  d: path("M4 2a2 2 0 1 0 0 4h5a2 2 0 1 0 0-4zm0 6a2 2 0 1 0 0 4h8a2 2 0 1 0 0-4zm0 6a2 2 0 1 0 0 4h12a2 2 0 1 0 0-4z");
}

</style>
