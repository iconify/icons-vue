<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txo-rs7zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graphics-card-fill-sharp" /></template>
<style>
.txo-rs7zp {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 2 0v1h17a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-3v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-3H4v3a1 1 0 0 1-2 0Zm3.236 6.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335m8 0a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M8 20h8v-2H8Z");
}

</style>
