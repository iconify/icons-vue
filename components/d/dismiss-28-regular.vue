<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="m1lh-xb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-28-regular" /></template>
<style>
.m1lh-xb2a {
  fill: currentColor;
  d: path("M22.47 4.47a.75.75 0 1 1 1.06 1.06L15.06 14l8.47 8.47a.75.75 0 1 1-1.06 1.06L14 15.06l-8.47 8.47a.75.75 0 0 1-1.06-1.06L12.94 14L4.47 5.53a.75.75 0 0 1 1.06-1.06L14 12.94z");
}

</style>
