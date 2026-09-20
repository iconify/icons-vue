<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wj0e81goz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-underline-circle-20-filled" /></template>
<style>
.wj0e81goz {
  fill: currentColor;
  d: path("M10 18a8 8 0 1 0 0-16a8 8 0 0 0 0 16m3.854-11.854a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.708L9.5 9.793l3.646-3.647a.5.5 0 0 1 .708 0M7.5 13h4.998a.5.5 0 0 1 0 1H7.5a.5.5 0 0 1 0-1");
}

</style>
