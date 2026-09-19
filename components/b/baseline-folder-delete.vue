<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h89un3b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-folder-delete" /></template>
<style>
.h89un3b5j {
  fill: currentColor;
  d: path("M22 8v10c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2l.01-12c0-1.1.89-2 1.99-2h6l2 2h8c1.1 0 2 .9 2 2m-5.5 2V9h-2v1H12v1.5h1v4c0 .83.67 1.5 1.5 1.5h2c.83 0 1.5-.67 1.5-1.5v-4h1V10zm0 5.5h-2v-4h2z");
}

</style>
