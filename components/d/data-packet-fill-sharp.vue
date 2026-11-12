<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9kg02b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:data-packet-fill-sharp" /></template>
<style>
.s9kg02b7m {
  fill: currentColor;
  d: path("M22 8H8V5a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1ZM5 7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm17 3v9a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-9ZM5 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm9 2a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 3v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0M5 15a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
