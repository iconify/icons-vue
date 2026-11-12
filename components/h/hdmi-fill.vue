<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du7r9rb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hdmi-fill" /></template>
<style>
.du7r9rb5t {
  fill: currentColor;
  d: path("M19 6a3 3 0 0 1 3 3v2a1 1 0 0 1-.168.555l-4 6A1 1 0 0 1 17 18H7a1 1 0 0 1-.832-.445l-4-6A1 1 0 0 1 2 11V9a3 3 0 0 1 3-3ZM8 12h8a1 1 0 0 0 0-2H8a1 1 0 0 0 0 2");
}

</style>
