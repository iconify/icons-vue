<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrdy2xbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-landscape-24-filled" /></template>
<style>
.wrdy2xbyx {
  fill: currentColor;
  d: path("M22 12h-6a2 2 0 0 1-2-2V4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2zm-.5-1.5H16a.5.5 0 0 1-.5-.5V4.5z");
}

</style>
