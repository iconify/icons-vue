<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znuihejcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-badge-24-filled" /></template>
<style>
.znuihejcj {
  fill: currentColor;
  d: path("M20.5 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 1c.537 0 1.045-.12 1.5-.337v7.087A3.25 3.25 0 0 1 18.75 18H13l-5 3.75c-.824.618-2 .03-2-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h12.087A3.5 3.5 0 0 0 20.5 8");
}

</style>
