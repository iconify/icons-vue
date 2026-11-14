<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fjtjqhb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-32-light" /></template>
<style>
.fjtjqhb_b {
  fill: currentColor;
  d: path("M29.5 26a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1z");
}

</style>
