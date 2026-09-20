<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnfp5p4vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-sharp" /></template>
<style>
.rnfp5p4vo {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077zM6.5 13.5h7v-1h-7zm0-3h11v-1h-11zm0-3h11v-1h-11z");
}

</style>
