<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1qkg-blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-24-filled" /></template>
<style>
.a1qkg-blr {
  fill: currentColor;
  d: path("M14.08 8.8a1.75 1.75 0 0 0-1.33 1.7v3a3.25 3.25 0 0 1-2.815 3.221A4.001 4.001 0 1 1 9.92 15.2a1.75 1.75 0 0 0 1.33-1.699v-3a3.25 3.25 0 0 1 2.815-3.221A4.001 4.001 0 0 1 22 8a4 4 0 0 1-7.92.8");
}

</style>
