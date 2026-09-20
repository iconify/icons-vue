<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azo_6dgni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:developer-mode-tv-outline-sharp" /></template>
<style>
.azo_6dgni {
  fill: currentColor;
  d: path("M2 7V3h20v4h-2V5H4v2zm6 14v-2H2v-4h2v2h16v-2h2v4h-6v2zM4.8 11l2.6-2.6L6 7l-4 4l4 4l1.4-1.4zm14.4 0l-2.6 2.6L18 15l4-4l-4-4l-1.4 1.4z");
}

</style>
