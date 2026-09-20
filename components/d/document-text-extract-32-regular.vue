<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s88cak6pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-extract-32-regular" /></template>
<style>
.s88cak6pb {
  fill: currentColor;
  d: path("M18.172 2a3 3 0 0 1 2.121.879l5.828 5.828A3 3 0 0 1 27 10.828V27a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-4.5h2V27a1 1 0 0 0 1 1h16a1 1 0 0 0 1-1V12h-5a3 3 0 0 1-3-3V4H8a1 1 0 0 0-1 1v12.5H5V5a3 3 0 0 1 3-3zM21 23a1 1 0 1 1 0 2H11a1 1 0 1 1 0-2zm-8-4a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm8-4a1 1 0 1 1 0 2H11a1 1 0 1 1 0-2zm-2-6a1 1 0 0 0 1 1h4.586L19 4.414z");
}

</style>
