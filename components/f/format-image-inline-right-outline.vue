<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3x1webuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-inline-right-outline" /></template>
<style>
.w3x1webuz {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm8-4V7h10v10zm2-2h6V9h-6zM3 5V3h18v2zm0 12v-2h6v2zm13-5");
}

</style>
