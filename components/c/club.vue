<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m71t_kb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:club" /></template>
<style>
.m71t_kb_u {
  fill: currentColor;
  d: path("M184 88h-2.33a56 56 0 1 0-107.34 0H72a56 56 0 1 0 24.54 106.35l-8.2 27.35A8 8 0 0 0 96 232h64a8 8 0 0 0 7.66-10.3l-8.2-27.35A56 56 0 1 0 184 88m0 96a40 40 0 0 1-33.4-18a8 8 0 0 0-14.33 6.71l13 43.26h-42.5l13-43.26A8 8 0 0 0 105.4 166a40 40 0 1 1-19.93-59.71a8 8 0 0 0 9.33-12a40 40 0 1 1 66.4 0a8 8 0 0 0 9.33 12A40 40 0 1 1 184 184");
}

</style>
