<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e51dusbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-request-draft-20-filled" /></template>
<style>
.e51dusbof {
  fill: currentColor;
  d: path("M5.5 7.959a3 3 0 1 0-1 0v4.082a3 3 0 1 0 1 0zM18 15a3 3 0 1 1-6 0a3 3 0 0 1 6 0m-1.75-6.5a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M15 5.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

</style>
