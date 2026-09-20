<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ljoz9kbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-data-bar-20-filled" /></template>
<style>
.ljoz9kbux {
  fill: currentColor;
  d: path("M18 7.373V11a2 2 0 0 0-1 .268V11a2 2 0 0 0-1.785-1.989zM4.5 17H10v-2a2 2 0 0 1 3-1.732V11c0-.276.056-.538.157-.777l-2.903 1.708a.5.5 0 0 1-.507 0L2 7.373V14.5A2.5 2.5 0 0 0 4.5 17m11-13a2.5 2.5 0 0 1 2.485 2.223L10 10.92L2.015 6.223A2.5 2.5 0 0 1 4.5 4zm-.5 6a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0v-7a1 1 0 0 0-1-1m3 2a1 1 0 0 0-1 1v5a1 1 0 1 0 2 0v-5a1 1 0 0 0-1-1m-7 3a1 1 0 1 1 2 0v3a1 1 0 1 1-2 0z");
}

</style>
