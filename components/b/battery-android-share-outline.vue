<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7himcb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-share-outline" /></template>
<style>
.i7himcb2p {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h14.175l-2 2H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h7v2zM3 8v8zm10 8v-3q0-.825.588-1.412T15 11h4.175L17.6 9.4L19 8l4 4l-4 4l-1.425-1.425l1.6-1.575H15v3z");
}

</style>
