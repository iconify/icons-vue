<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqokf7-mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:broad-activity-feed-24-filled" /></template>
<style>
.vqokf7-mr {
  fill: currentColor;
  d: path("M9.246 14.001c.967 0 1.75.784 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75H3.75A1.75 1.75 0 0 1 2 19.251v-3.5c0-.966.784-1.75 1.75-1.75zm11.004 0c.966 0 1.75.784 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-5.496a1.75 1.75 0 0 1-1.75-1.75v-3.5c0-.966.783-1.75 1.75-1.75zm0-11.005c.966 0 1.75.784 1.75 1.75v5.503A1.75 1.75 0 0 1 20.25 12H3.75A1.75 1.75 0 0 1 2 10.25V4.746a1.75 1.75 0 0 1 1.606-1.744l.144-.006z");
}

</style>
