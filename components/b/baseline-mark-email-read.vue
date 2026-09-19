<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx34b9b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-mark-email-read" /></template>
<style>
.qx34b9b5q {
  fill: currentColor;
  d: path("M12 19a6.995 6.995 0 0 1 10-6.32V6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h8.08c-.05-.33-.08-.66-.08-1M4 6l8 5l8-5v2l-8 5l-8-5zm13.34 16l-3.54-3.54l1.41-1.41l2.12 2.12l4.24-4.24L23 16.34z");
}

</style>
