<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slx4rzbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hdmi-fill-sharp" /></template>
<style>
.slx4rzbxr {
  fill: currentColor;
  d: path("M21 6a1 1 0 0 1 1 1v4a1 1 0 0 1-.168.555l-4 6A1 1 0 0 1 17 18H7a1 1 0 0 1-.832-.445l-4-6A1 1 0 0 1 2 11V7a1 1 0 0 1 1-1ZM8 10a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Z");
}

</style>
