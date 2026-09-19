<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll9yllb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-dialer-sip" /></template>
<style>
.ll9yllb4y {
  fill: currentColor;
  d: path("M17 3h-1v5h1zm-2 2h-2V4h2V3h-3v3h2v1h-2v1h3zm3-2v5h1V6h2V3zm2 2h-1V4h1zm0 10.5c-1.25 0-2.45-.2-3.57-.57a1 1 0 0 0-1.01.24l-2.2 2.2a15.05 15.05 0 0 1-6.59-6.59l2.2-2.21c.27-.26.35-.65.24-1A11.4 11.4 0 0 1 8.5 4c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1c0 9.39 7.61 17 17 17c.55 0 1-.45 1-1v-3.5c0-.55-.45-1-1-1");
}

</style>
