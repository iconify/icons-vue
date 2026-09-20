<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a8ek1tvsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gift-card-16-regular" /></template>
<style>
.a8ek1tvsn {
  fill: currentColor;
  d: path("M1 5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2zm12 7a1 1 0 0 0 1-1V8H6.707l1.147 1.146a.5.5 0 1 1-.708.708L6 8.707V12zM7.915 7H14V5a1 1 0 0 0-1-1H6v1.085q.236-.084.5-.085a1.5 1.5 0 0 1 1.415 2M6.5 7a.5.5 0 1 0-.5-.5V7zM5 5.085V4H3a1 1 0 0 0-1 1v2h1.085A1.5 1.5 0 0 1 5 5.085M4.5 7H5v-.5a.5.5 0 1 0-.5.5m-.207 1H2v3a1 1 0 0 0 1 1h2V8.707L3.854 9.854a.5.5 0 0 1-.708-.708z");
}

</style>
