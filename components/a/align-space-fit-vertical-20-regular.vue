<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xpkbbiulf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-space-fit-vertical-20-regular" /></template>
<style>
.xpkbbiulf {
  fill: currentColor;
  d: path("M6 1a2 2 0 0 0-2 2v4.5a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2zM5 3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v4.5a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1zm1 7.5a2 2 0 0 0-2 2V17a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-4.5a2 2 0 0 0-2-2zm-1 2a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V17a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1z");
}

</style>
