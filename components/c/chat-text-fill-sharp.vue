<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa_xhkb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-text-fill-sharp" /></template>
<style>
.xa_xhkb8q {
  fill: currentColor;
  d: path("m7.414 18l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1ZM16 7H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-3 4H8a1 1 0 0 0 0 2h5a1 1 0 0 0 0-2");
}

</style>
