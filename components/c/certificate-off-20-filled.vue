<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j68fa8crd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:certificate-off-20-filled" /></template>
<style>
.j68fa8crd {
  fill: currentColor;
  d: path("M8 18a.5.5 0 0 1-.8.4l-1.4-1.05a.5.5 0 0 0-.6 0L3.8 18.4A.5.5 0 0 1 3 18v-2.758A4.5 4.5 0 0 0 5.5 16c.925 0 1.785-.28 2.5-.758zM2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L14.293 15H9v-.67a4.48 4.48 0 0 0 .912-3.71L6.381 7.087A4.49 4.49 0 0 0 2 8.67V5a1.99 1.99 0 0 1 .74-1.552l-.595-.594a.5.5 0 0 1 0-.707M5.5 8a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M16 3a2 2 0 0 1 2 2v8c0 .78-.447 1.452-1.097 1.782L9.121 7H14.5a.5.5 0 0 0 0-1H8.121l-3-3z");
}

</style>
