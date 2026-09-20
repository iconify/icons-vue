<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsg7xacht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-back-outline" /></template>
<style>
.lsg7xacht {
  fill: currentColor;
  d: path("M4 20v-1h2V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19h2v1zm3-1h10V5.616q0-.231-.192-.424T16.384 5H7.616q-.231 0-.424.192T7 5.616zm2.77-6.23q.309 0 .539-.23t.23-.54t-.23-.54t-.54-.23t-.54.23T9 12t.23.54t.54.23M7 5v14z");
}

</style>
