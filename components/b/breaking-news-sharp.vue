<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie7vqfb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:breaking-news-sharp" /></template>
<style>
.ie7vqfb5w {
  fill: currentColor;
  d: path("M6 17h2v-2H6zm0-4h2V7H6zm5 4h7v-2h-7zm0-4h7v-2h-7zm0-4h7V7h-7zM2 21V3h20v18z");
}

</style>
