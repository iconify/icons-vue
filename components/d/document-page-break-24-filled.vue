<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tac8biecw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-page-break-24-filled" /></template>
<style>
.tac8biecw {
  fill: currentColor;
  d: path("M2.5 12a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5A.75.75 0 0 1 2.5 12m4 0a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5A.75.75 0 0 1 6.5 12m4 0a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1-.75-.75m4 0a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1-.75-.75m4 0a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1-.75-.75M5 2a1 1 0 0 0-1 1v4a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V3a1 1 0 0 0-1-1zm14 20a1 1 0 0 0 1-1v-4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v4a1 1 0 0 0 1 1z");
}

</style>
