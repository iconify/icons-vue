<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_utjtbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-outline-sharp" /></template>
<style>
.e_utjtbdl {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4zm2-2h8v-2H6zm0-3h12V9H6zm0-3h12V6H6z");
}

</style>
