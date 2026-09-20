<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvuhk_boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:list-bar-24-filled" /></template>
<style>
.pvuhk_boo {
  fill: currentColor;
  d: path("M9.5 21H19a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2H9.5zm0-6.5H19a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2H9.5zM8 9.5v5H5a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2zM9.5 8H19a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H9.5zM8 3v5H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zm0 13v5H5a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2z");
}

</style>
