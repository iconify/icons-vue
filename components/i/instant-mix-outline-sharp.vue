<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbi1fhn1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:instant-mix-outline-sharp" /></template>
<style>
.vbi1fhn1v {
  fill: currentColor;
  d: path("M5 20v-7H3v-2h6v2H7v7zM5 9V4h2v5zm4 0V7h2V4h2v3h2v2zm2 11v-9h2v9zm6 0v-3h-2v-2h6v2h-2v3zm0-7V4h2v9z");
}

</style>
