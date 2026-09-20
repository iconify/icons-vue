<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j96v-hb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:breaking-news-outline-sharp" /></template>
<style>
.j96v-hb0x {
  fill: currentColor;
  d: path("M6 17h2v-2H6zm0-4h2V7H6zm5 4h7v-2h-7zm0-4h7v-2h-7zm0-4h7V7h-7zM2 21V3h20v18zm2-2h16V5H4zm0 0V5z");
}

</style>
