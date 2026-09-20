<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ipb0p6bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-1-dot-20-filled" /></template>
<style>
.ipb0p6bhs {
  fill: currentColor;
  d: path("M3.5 11a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M8 11a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m4.5 0a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m6-1.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
