<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ubat_lb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-28-filled" /></template>
<style>
.ubat_lb1v {
  fill: currentColor;
  d: path("M25 22a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-6a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-6a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-6a1 1 0 1 1 0 2H3a1 1 0 0 1 0-2z");
}

</style>
