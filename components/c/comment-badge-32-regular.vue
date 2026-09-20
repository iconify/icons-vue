<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="inwl58ujf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-badge-32-regular" /></template>
<style>
.inwl58ujf {
  fill: currentColor;
  d: path("M23.17 3a5 5 0 0 0-.646 2H6.5A2.5 2.5 0 0 0 4 7.5v12A2.5 2.5 0 0 0 6.5 22H9a1 1 0 0 1 1 1v5.081l6.852-5.842A1 1 0 0 1 17.5 22h8a2.5 2.5 0 0 0 2.5-2.5v-9.025a5 5 0 0 0 2-.646V19.5a4.5 4.5 0 0 1-4.5 4.5h-7.632l-6.57 5.602C9.999 30.71 8 29.787 8 28.083V24H6.5A4.5 4.5 0 0 1 2 19.5v-12A4.5 4.5 0 0 1 6.5 3zm4.33-1a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7");
}

</style>
