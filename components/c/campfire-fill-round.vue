<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjqaasbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:campfire-fill-round" /></template>
<style>
.vjqaasbjs {
  fill: currentColor;
  d: path("M15.1 5.95a1 1 0 0 1 .107.093a5 5 0 0 1 1.224 2.049c.242.776.319 1.598.319 2.408A4.747 4.747 0 0 1 12 15.25a4.74 4.74 0 0 1-3.359-1.391A4.74 4.74 0 0 1 7.25 10.5c0-.518.077-1.037.259-1.523c.147-.391.36-.76.657-1.057a1 1 0 0 1 1.416-.002a1 1 0 0 1 .293.707c0 .101.06.193.154.232a.25.25 0 0 0 .346-.232c0-.187-.015-.38-.075-.558c-.056-.165-.146-.32-.23-.471a9 9 0 0 1-.214-.399c-.417-.833-.536-1.723-.256-2.62c.301-.962 1.003-1.739 1.775-2.358a1 1 0 0 1 1.606.585c.263 1.315 1.062 2.353 2.119 3.146M4.243 16.03L12 17.969l7.757-1.939a1 1 0 0 1 .486 1.94L16.123 19l4.12 1.03a1 1 0 0 1-.486 1.94L12 20.031L4.243 21.97a1 1 0 0 1-.486-1.94L7.877 19l-4.12-1.03a1 1 0 0 1 .486-1.94");
}

</style>
