<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xraoffbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-infographic-20-filled" /></template>
<style>
.xraoffbvd {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM7.5 9a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m4 .5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 1 0V10a.5.5 0 0 0-.5-.5m2-1a.5.5 0 0 0-.5.5v4.5a.5.5 0 0 0 1 0V9a.5.5 0 0 0-.5-.5m-6 1.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3M6 6a.5.5 0 0 0 0 1h8a.5.5 0 0 0 0-1z");
}

</style>
