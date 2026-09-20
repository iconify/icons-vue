<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guy1zib6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:breaking-news-alt-1-outline-sharp" /></template>
<style>
.guy1zib6k {
  fill: currentColor;
  d: path("M6 17h5v-2H6zm10 0h2v-2h-2zM6 13h5v-2H6zm10 0h2V7h-2zM6 9h5V7H6zM2 21V3h20v18zm2-2h16V5H4zm0 0V5z");
}

</style>
