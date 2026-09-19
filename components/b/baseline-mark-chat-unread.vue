<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jifwvwbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-mark-chat-unread" /></template>
<style>
.jifwvwbtz {
  fill: currentColor;
  d: path("M22 6.98V16c0 1.1-.9 2-2 2H6l-4 4V4c0-1.1.9-2 2-2h10.1A5.002 5.002 0 0 0 19 8c1.13 0 2.16-.39 3-1.02M16 3c0 1.66 1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3");
}

</style>
