<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrhtr9bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-bubble-sharp" /></template>
<style>
.yrhtr9bqg {
  fill: currentColor;
  d: path("M2 22V2h20v16H6z");
}

</style>
