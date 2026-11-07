<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhhk1-b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-fill" /></template>
<style>
.qhhk1-b0p {
  fill: currentColor;
  d: path("m4.129 5.887l-1.125-.556q.052-.03.106-.056l.004-.002l8-3.951a2 2 0 0 1 .872-.207h.028c.303.003.6.073.872.207l8.004 3.953q.054.027.106.056L12 9.774ZM11 11.51v11.111l-7.886-3.894A2 2 0 0 1 2 16.934V7.066Zm2 0l9-4.444v9.868a2 2 0 0 1-1.114 1.793L13 22.621Z");
}

</style>
