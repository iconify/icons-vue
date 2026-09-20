<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3qusubtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autopilot-20-regular" /></template>
<style>
.o3qusubtv {
  fill: currentColor;
  d: path("M16 3a3 3 0 0 1 3 3v.098a3 3 0 0 1-1.052 2.28l-6.997 5.977l-3.639 3.108a2.25 2.25 0 0 1-1.46.537a2.23 2.23 0 0 1-2.163-1.68a2.22 2.22 0 0 1 .26-1.695l3.385-5.54l-4.083-1.928A2.183 2.183 0 0 1 4.184 3zM4.802 15.147c-.17.278-.221.613-.142.93c.135.539.63.923 1.193.923c.296 0 .587-.106.81-.297l3.653-3.122a1.993 1.993 0 0 0-.459-3.304l-1.614-.762zM9.32 4a2.84 2.84 0 0 1 .263 3.323l-.815 1.333l1.59.751A2.87 2.87 0 0 1 12 12v.08l-.002.065l5.3-4.527A2 2 0 0 0 18 6.098V6a2 2 0 0 0-2-2zM4.184 4a1.184 1.184 0 0 0-.506 2.253l4.18 1.974l.871-1.425A1.84 1.84 0 0 0 7.346 4.01L7.16 4z");
}

</style>
