<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwb1tcb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-comment-outline-sharp" /></template>
<style>
.pwb1tcb3u {
  fill: currentColor;
  d: path("M11.5 13.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
