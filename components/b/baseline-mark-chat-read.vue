<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fec_-r03e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-mark-chat-read" /></template>
<style>
.fec_-r03e {
  fill: currentColor;
  d: path("m17.34 20l-3.54-3.54l1.41-1.41l2.12 2.12l4.24-4.24L23 14.34zM12 17a6.995 6.995 0 0 1 10-6.32V4c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v18l4-4h6c0-.17.01-.33.03-.5A4 4 0 0 1 12 17");
}

</style>
