<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hzy-ywbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-fit-16-filled" /></template>
<style>
.hzy-ywbld {
  fill: currentColor;
  d: path("M5 1a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2zm0 3a1 1 0 0 1 1-1h1a.5.5 0 0 1 0 1H6v1a.5.5 0 0 1-1 0zm0 8v-1a.5.5 0 0 1 1 0v1h1a.5.5 0 0 1 0 1H6a1 1 0 0 1-1-1m5-9a1 1 0 0 1 1 1v1a.5.5 0 0 1-1 0V4H9a.5.5 0 0 1 0-1zm1 9a1 1 0 0 1-1 1H9a.5.5 0 0 1 0-1h1v-1a.5.5 0 0 1 1 0z");
}

</style>
