<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezkcbrr8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-outline-sharp" /></template>
<style>
.ezkcbrr8q {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4zm2.5-2.5h7v-1h-7zm0-3h11v-1h-11zm0-3h11v-1h-11z");
}

</style>
