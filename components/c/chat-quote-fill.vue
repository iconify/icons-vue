<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znmxywp-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-quote-fill" /></template>
<style>
.znmxywp-i {
  fill: currentColor;
  d: path("m6.707 18.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H8c-.468 0-.98.395-1.293.707M10 7H8a1 1 0 0 0 0 2h1v.586l-1.707 1.707a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 11 10V8a1 1 0 0 0-1-1m6 0h-2a1 1 0 0 0 0 2h1v.586l-1.707 1.707a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 17 10V8a1 1 0 0 0-1-1");
}

</style>
