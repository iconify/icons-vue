<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac2xoqbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-4mp" /></template>
<style>
.ac2xoqbgb {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-7 15.5h-1.5V14h-1v3H8v-3H7v4.5H5.5v-5c0-.55.45-1 1-1H11c.55 0 1 .45 1 1zm3-8.5h-1v1.5h-1.5V10h-3V5.5H11v3h1.5v-3H14v3h1zm.5 8.5H14v-6h3.5c.55 0 1 .45 1 1V16c0 .55-.45 1-1 1h-2zm0-4.5H17v1.5h-1.5z");
}

</style>
