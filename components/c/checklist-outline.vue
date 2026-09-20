<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwi9k6v-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:checklist-outline" /></template>
<style>
.dwi9k6v-v {
  fill: currentColor;
  d: path("M5.55 19L2 15.45l1.4-1.4l2.125 2.125l4.25-4.25l1.4 1.425zm0-8L2 7.45l1.4-1.4l2.125 2.125l4.25-4.25l1.4 1.425zM13 17v-2h9v2zm0-8V7h9v2z");
}

</style>
