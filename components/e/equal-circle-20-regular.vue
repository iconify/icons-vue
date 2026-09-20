<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tai632byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-circle-20-regular" /></template>
<style>
.tai632byr {
  fill: currentColor;
  d: path("M13.5 9a.5.5 0 0 0 0-1h-7a.5.5 0 0 0 0 1zm0 3a.5.5 0 0 0 0-1h-7a.5.5 0 0 0 0 1zm4.5-2a8 8 0 1 0-16 0a8 8 0 0 0 16 0m-8-7a7 7 0 1 1 0 14a7 7 0 0 1 0-14");
}

</style>
