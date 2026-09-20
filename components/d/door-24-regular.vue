<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6n8hbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-24-regular" /></template>
<style>
.zx6n8hbhn {
  fill: currentColor;
  d: path("M17.75 2A2.25 2.25 0 0 1 20 4.25v15.5A2.25 2.25 0 0 1 17.75 22H6.25A2.25 2.25 0 0 1 4 19.75V4.25A2.25 2.25 0 0 1 6.25 2zM6.25 3.5a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75V4.25a.75.75 0 0 0-.75-.75zm2.25 6.75a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
