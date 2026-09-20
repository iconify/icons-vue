<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfu0zhkvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-share-24-filled" /></template>
<style>
.hfu0zhkvd {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h6a3.25 3.25 0 0 1 3.25 3.25a.75.75 0 0 1-1.5 0a1.75 1.75 0 0 0-1.75-1.75h-6A1.75 1.75 0 0 0 4.5 6.25v6c0 .966.784 1.75 1.75 1.75h5.854a2.751 2.751 0 1 1 0 1.5H6.25A3.25 3.25 0 0 1 3 12.25zM17.75 10c.966 0 1.75.784 1.75 1.75v6a1.75 1.75 0 0 1-1.75 1.75h-6A1.75 1.75 0 0 1 10 17.75a.75.75 0 0 0-1.5 0A3.25 3.25 0 0 0 11.75 21h6A3.25 3.25 0 0 0 21 17.75v-6a3.25 3.25 0 0 0-3.25-3.25h-5.853a2.751 2.751 0 1 0 0 1.5z");
}

</style>
