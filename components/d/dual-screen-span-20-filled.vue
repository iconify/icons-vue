<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ittam0a_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-span-20-filled" /></template>
<style>
.ittam0a_j {
  fill: currentColor;
  d: path("M16 16h-5.5v-5.5h3.793l-1.147 1.146a.5.5 0 0 0 .708.708l2-2a.5.5 0 0 0 0-.708l-2-2a.5.5 0 0 0-.708.708L14.293 9.5H10.5V4H16a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2M9.5 9.5V4H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h5.5v-5.5H5.707l1.147 1.146a.5.5 0 0 1-.708.708l-2-2a.5.5 0 0 1 0-.708l2-2a.5.5 0 1 1 .708.708L5.707 9.5z");
}

</style>
