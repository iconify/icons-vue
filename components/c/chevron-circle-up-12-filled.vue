<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g_bjgpbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-up-12-filled" /></template>
<style>
.g_bjgpbqm {
  fill: currentColor;
  d: path("M6 11A5 5 0 1 1 6 1a5 5 0 0 1 0 10M4.146 6.146a.5.5 0 1 0 .708.708L6 5.707l1.146 1.147a.5.5 0 1 0 .708-.708l-1.5-1.5a.5.5 0 0 0-.708 0z");
}

</style>
