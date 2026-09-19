<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z500bs11b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:add-to-queue" /></template>
<style>
.z500bs11b {
  fill: currentColor;
  d: path("M21 3H3c-1.11 0-2 .89-2 2v12a2 2 0 0 0 2 2h5v2h8v-2h5c1.1 0 1.99-.9 1.99-2L23 5a2 2 0 0 0-2-2m0 14H3V5h18zm-5-7v2h-3v3h-2v-3H8v-2h3V7h2v3z");
}

</style>
