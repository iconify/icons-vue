<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4jaxn14z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:house-sharp" /></template>
<style>
.q4jaxn14z {
  fill: currentColor;
  d: path("M5 20v-9.15L2.2 13L1 11.4L12 3l4 3.05V4h3v4.35l4 3.05l-1.2 1.6l-2.8-2.15V20h-5v-6h-4v6zm5-9.975h4q0-.8-.6-1.313T12 8.2t-1.4.513t-.6 1.312");
}

</style>
