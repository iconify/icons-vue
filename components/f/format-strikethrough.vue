<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9c4kb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-strikethrough" /></template>
<style>
.ta9c4kb7d {
  fill: currentColor;
  d: path("M2 14v-2h20v2zm8.5-4V7H5V4h14v3h-5.5v3zm0 10v-4h3v4z");
}

</style>
