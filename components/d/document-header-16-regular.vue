<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qqtg-g_0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-16-regular" /></template>
<style>
.qqtg-g_0j {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 0 0 2h4a1 1 0 1 0 0-2zM4.75 1A1.75 1.75 0 0 0 3 2.75v10.5c0 .966.784 1.75 1.75 1.75h6.5A1.75 1.75 0 0 0 13 13.25V2.75A1.75 1.75 0 0 0 11.25 1zM4 2.75A.75.75 0 0 1 4.75 2h6.5a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-6.5a.75.75 0 0 1-.75-.75z");
}

</style>
