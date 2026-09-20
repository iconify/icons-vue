<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nfb24vvyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:class-20-regular" /></template>
<style>
.nfb24vvyl {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 1-1.732V16a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1h-2V2h2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm2-2v6.5a.5.5 0 0 0 .8.4l1.7-1.275L10.2 8.9a.5.5 0 0 0 .8-.4V2zm1 5.5V3h3v4.5l-1.2-.9a.5.5 0 0 0-.6 0z");
}

</style>
