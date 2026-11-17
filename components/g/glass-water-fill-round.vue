<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt021s14d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:glass-water-fill-round" /></template>
<style>
.qt021s14d {
  fill: currentColor;
  d: path("m19.552 7.086l-1.163 10.466A5 5 0 0 1 13.42 22h-2.84a5 5 0 0 1-4.969-4.448l-.605-5.442v-.002l-.558-5.022A4.577 4.577 0 0 1 9 2h6a4.58 4.58 0 0 1 4.552 5.086M6.436 6.865L6.895 11h10.21l.459-4.135a2.58 2.58 0 0 0-.641-2.006A2.6 2.6 0 0 0 15 4H9c-.734 0-1.433.313-1.923.859a2.58 2.58 0 0 0-.641 2.006");
}

</style>
