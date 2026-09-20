<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wben2rbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-videocam-sharp" /></template>
<style>
.wben2rbfb {
  fill: currentColor;
  d: path("M2 20V4h16v6.5l4-4v11l-4-4V20H2Zm8-4l1.25-2.75L14 12l-2.75-1.25L10 8l-1.25 2.75L6 12l2.75 1.25L10 16Z");
}

</style>
