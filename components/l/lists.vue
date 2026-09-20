<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz2kiccjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lists" /></template>
<style>
.uz2kiccjn {
  fill: currentColor;
  d: path("M2 20v-4h4v4zm6 0v-4h14v4zm-6-6v-4h4v4zm6 0v-4h14v4zM2 8V4h4v4zm6 0V4h14v4z");
}

</style>
