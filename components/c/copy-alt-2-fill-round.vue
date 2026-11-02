<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eko1wh1jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-2-fill-round" /></template>
<style>
.eko1wh1jk {
  fill: currentColor;
  d: path("M11 2h6a5 5 0 0 1 5 5v6a3 3 0 0 1-3 3a1 1 0 0 1 0-2a1 1 0 0 0 1-1V7a3 3 0 0 0-3-3h-6a.997.997 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3M2 13a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

</style>
