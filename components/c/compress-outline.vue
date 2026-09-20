<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h02qa9sxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:compress-outline" /></template>
<style>
.h02qa9sxs {
  fill: currentColor;
  d: path("M4 14v-2h16v2zm0-3V9h16v2zm7 11v-3.2l-1.6 1.6L8 19l4-4l4 4l-1.4 1.4l-1.6-1.55V22zm1-14L8 4l1.4-1.4L11 4.2V1h2v3.2l1.6-1.6L16 4z");
}

</style>
