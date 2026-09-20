<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i72xmaboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:kiosk-24-regular" /></template>
<style>
.i72xmaboz {
  fill: currentColor;
  d: path("M4 4.25A2.25 2.25 0 0 1 6.25 2h11.5A2.25 2.25 0 0 1 20 4.25v6.5A2.25 2.25 0 0 1 17.75 13H14.5v7.5h1.75a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5H9.5V13H6.25A2.25 2.25 0 0 1 4 10.75zM11 13v7.5h2V13zM6.25 3.5a.75.75 0 0 0-.75.75v6.5c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75v-6.5a.75.75 0 0 0-.75-.75z");
}

</style>
