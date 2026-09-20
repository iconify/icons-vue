<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ub6qlnb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-lock-16-regular" /></template>
<style>
.ub6qlnb9r {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7q-.001.133-.007.265a2 2 0 0 0-.493-.202V8a3 3 0 0 0-.892-2.133a6.001 6.001 0 1 0-10.678 5.34a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052c.66.419 1.407.711 2.208.846V14c0 .347.088.674.244.959a7 7 0 0 1-2.782-.92l-2.804.936a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m3.5 5a2 2 0 0 1 2 2v1h.5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h.5V8a2 2 0 0 1 2-2m0 5.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m0-4.25a1 1 0 0 0-1 1v1h2V8a1 1 0 0 0-1-1");
}

</style>
