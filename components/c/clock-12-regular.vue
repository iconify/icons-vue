<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ilw6vfbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-12-regular" /></template>
<style>
.ilw6vfbia {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 1 0 10A5 5 0 0 1 6 1m0 1a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-.5 1.5a.5.5 0 0 1 .492.41L6 4v2h1.5a.5.5 0 0 1 .09.992L7.5 7h-2a.5.5 0 0 1-.492-.41L5 6.5V4a.5.5 0 0 1 .5-.5");
}

</style>
