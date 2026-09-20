<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w612o8bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:certificate-off-20-regular" /></template>
<style>
.w612o8bgu {
  fill: currentColor;
  d: path("M8 18a.5.5 0 0 1-.8.4l-1.4-1.05a.5.5 0 0 0-.6 0L3.8 18.4A.5.5 0 0 1 3 18v-2.758A4.5 4.5 0 0 0 5.5 16c.925 0 1.785-.28 2.5-.758zM2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L14.293 15H9v-.67a5 5 0 0 0 .242-.33h4.051L3.455 4.162A1 1 0 0 0 3 5v2.758c-.378.253-.715.56-1 .913V5c0-.627.29-1.185.741-1.552l-.595-.594a.5.5 0 0 1 0-.707M5.5 8a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M16 3a2 2 0 0 1 2 2v8c0 .78-.447 1.452-1.097 1.782l-.789-.789A1 1 0 0 0 17 13V5a1 1 0 0 0-1-1H6.121l-1-1zm-1.5 3a.5.5 0 0 1 0 1H9.121l-1-1z");
}

</style>
