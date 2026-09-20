<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1frjnbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-request-closed-20-filled" /></template>
<style>
.f1frjnbfp {
  fill: currentColor;
  d: path("M5.5 7.959a3 3 0 1 0-1 0v4.082a3 3 0 1 0 1 0zM18 15a3 3 0 1 1-3.5-2.959V8.5a.5.5 0 0 1 1 0v3.541A3 3 0 0 1 18 15M13.354 2.646a.5.5 0 0 0-.708.708L14.293 5l-1.647 1.646a.5.5 0 0 0 .708.708L15 5.707l1.646 1.647a.5.5 0 0 0 .708-.708L15.707 5l1.647-1.646a.5.5 0 0 0-.708-.708L15 4.293z");
}

</style>
