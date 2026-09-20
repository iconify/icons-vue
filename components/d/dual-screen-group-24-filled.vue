<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqahm-3db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-group-24-filled" /></template>
<style>
.aqahm-3db {
  fill: currentColor;
  d: path("M20.253 4.004c.966 0 1.75.784 1.75 1.75V18.25a1.75 1.75 0 0 1-1.75 1.75h-7.248q-.13 0-.255-.019V4.023q.125-.018.255-.019zm-9.248-.002q.126 0 .246.017V19.98q-.12.017-.246.017H3.758a1.75 1.75 0 0 1-1.75-1.75V5.752c0-.967.783-1.75 1.75-1.75z");
}

</style>
