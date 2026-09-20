<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iduv_-qnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-style-outline-sharp" /></template>
<style>
.iduv_-qnu {
  fill: currentColor;
  d: path("M3 20v-2h2v2zm0-4v-2h5v2zm0-4v-2h8v2zm0-4V4h18v4zm4 12v-2h2v2zm2.5-4v-2h5v2zm1.5 4v-2h2v2zm2-8v-2h8v2zm2 8v-2h2v2zm1-4v-2h5v2zm3 4v-2h2v2z");
}

</style>
