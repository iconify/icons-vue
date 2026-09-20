<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xuw7-xb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:diamonds-four-bold" /></template>
<style>
.xuw7-xb0k {
  fill: currentColor;
  d: path("M119.51 108.49a12 12 0 0 0 17 0l38-38a12 12 0 0 0 0-17l-38-38a12 12 0 0 0-17 0l-38 38a12 12 0 0 0 0 17ZM128 41l21 21l-21 21l-21-21Zm8.49 106.54a12 12 0 0 0-17 0l-38 38a12 12 0 0 0 0 17l38 38a12 12 0 0 0 17 0l38-38a12 12 0 0 0 0-17ZM128 215l-21-21l21-21l21 21Zm-19.51-95.52l-38-38a12 12 0 0 0-17 0l-38 38a12 12 0 0 0 0 17l38 38a12 12 0 0 0 17 0l38-38a12 12 0 0 0 0-16.97ZM62 149l-21-21l21-21l21 21Zm178.49-29.52l-38-38a12 12 0 0 0-17 0l-38 38a12 12 0 0 0 0 17l38 38a12 12 0 0 0 17 0l38-38a12 12 0 0 0 0-16.97ZM194 149l-21-21l21-21l21 21Z");
}

</style>
