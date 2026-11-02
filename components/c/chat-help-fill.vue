<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-b-obhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-help-fill" /></template>
<style>
.h6-b-obhl {
  fill: currentColor;
  d: path("m6.707 18.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H8c-.468 0-.98.395-1.293.707M9.236 7.832A3 3 0 0 0 9 9a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 12 10a1 1 0 0 0 0 2a3 3 0 1 0-2.764-4.168M12.01 13H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
