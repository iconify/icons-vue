<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byvke7bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-frames-outline-sharp" /></template>
<style>
.byvke7bis {
  fill: currentColor;
  d: path("M2 22V4h6l4-4l4 4h6v18zm2-2h16V6H4zm2-2V8h12v10zm2-2h8v-6H8zm4-3");
}

</style>
