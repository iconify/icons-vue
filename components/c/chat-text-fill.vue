<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkb8zkbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-text-fill" /></template>
<style>
.qkb8zkbvj {
  fill: currentColor;
  d: path("M8 18c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3Zm8-11H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-3 4H8a1 1 0 0 0 0 2h5a1 1 0 0 0 0-2");
}

</style>
