<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-f0xibar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-fill-sharp" /></template>
<style>
.b-f0xibar {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 1 1v14a1 1 0 0 1-2 0V4H7a1 1 0 0 1 0-2ZM2 21V7a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
