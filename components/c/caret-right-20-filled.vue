<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ydqfpzbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-right-20-filled" /></template>
<style>
.ydqfpzbil {
  fill: currentColor;
  d: path("M7 14.204a1 1 0 0 0 1.628.778l4.723-3.815a1.5 1.5 0 0 0 0-2.334L8.628 5.02A1 1 0 0 0 7 5.797z");
}

</style>
