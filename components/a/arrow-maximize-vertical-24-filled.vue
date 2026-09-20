<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgaps7syd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-vertical-24-filled" /></template>
<style>
.qgaps7syd {
  fill: currentColor;
  d: path("M15.207 6.207a1 1 0 0 1-1.414 0L13 5.414V9a1 1 0 1 1-2 0V5.414l-.793.793a1 1 0 0 1-1.414-1.414l2.5-2.5A1 1 0 0 1 11.997 2h.006a1 1 0 0 1 .704.293l2.5 2.5a1 1 0 0 1 0 1.414M5 11a1 1 0 1 0 0 2h14a1 1 0 1 0 0-2zm7.01 11a1 1 0 0 0 .697-.293l2.5-2.5a1 1 0 0 0-1.414-1.414l-.793.793V15a1 1 0 1 0-2 0v3.586l-.793-.793a1 1 0 0 0-1.414 1.414l2.5 2.5a1 1 0 0 0 .698.293");
}

</style>
