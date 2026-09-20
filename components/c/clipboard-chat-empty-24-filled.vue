<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrie0v59v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-24-filled" /></template>
<style>
.mrie0v59v {
  fill: currentColor;
  d: path("M13.75 2a2.25 2.25 0 0 1 2.236 2h1.764A2.25 2.25 0 0 1 20 6.25v3.254A7.53 7.53 0 0 0 15.5 8a7.5 7.5 0 0 0-6.802 10.66l-.625 2.088A1.75 1.75 0 0 0 8.17 22H6.25A2.25 2.25 0 0 1 4 19.75V6.25A2.25 2.25 0 0 1 6.25 4h1.764a2.25 2.25 0 0 1 2.236-2zm-3.5 1.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM22 15.5a6.5 6.5 0 0 1-9.57 5.729l-2.464.74a.751.751 0 0 1-.935-.934l.739-2.467c-.51-.95-.752-1.995-.77-3.068A6.5 6.5 0 0 1 15.5 9c3.59 0 6.5 2.888 6.5 6.5");
}

</style>
