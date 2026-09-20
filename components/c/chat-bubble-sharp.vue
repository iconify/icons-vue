<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meinyobsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-bubble-sharp" /></template>
<style>
.meinyobsi {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077z");
}

</style>
