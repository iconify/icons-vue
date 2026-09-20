<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_01v-bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-outline-sharp" /></template>
<style>
.w_01v-bto {
  fill: currentColor;
  d: path("M5 21V3h14v18l-7-3zm2-3.05l5-2.15l5 2.15V5H7zM7 5h10z");
}

</style>
