<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cd_q5uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-partial-fill-round" /></template>
<style>
.w-cd_q5uv {
  fill: currentColor;
  d: path("M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5Zm12 3H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
