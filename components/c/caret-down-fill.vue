<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oimxsbabk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-down-fill" /></template>
<style>
.oimxsbabk {
  fill: currentColor;
  d: path("M16 9a1.002 1.002 0 0 1 .707 1.707l-4 4a1 1 0 0 1-1.414 0l-4-4A1 1 0 0 1 8 9Z");
}

</style>
