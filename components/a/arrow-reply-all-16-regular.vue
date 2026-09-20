<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qm_shkbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-all-16-regular" /></template>
<style>
.qm_shkbpe {
  fill: currentColor;
  d: path("M6.354 4.354a.5.5 0 1 0-.708-.708l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L3.207 7.5zm3 0a.5.5 0 1 0-.708-.708l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L6.707 8H8.5a4.5 4.5 0 0 1 4.5 4.5a.5.5 0 0 0 1 0A5.5 5.5 0 0 0 8.5 7H6.707z");
}

</style>
