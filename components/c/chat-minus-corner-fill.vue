<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfhfacb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-minus-corner-fill" /></template>
<style>
.wfhfacb6t {
  fill: currentColor;
  d: path("M10 11v6a1 1 0 0 1-1 1H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1H11a.997.997 0 0 0-1 1m3 4h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
