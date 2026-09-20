<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liso50err"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-front-outline" /></template>
<style>
.liso50err {
  fill: currentColor;
  d: path("M4 20v-1h2V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19h2v1zm13-1V5.616q0-.231-.192-.424T16.384 5H7.616q-.231 0-.424.192T7 5.616V19zm-2.77-6.23q.31 0 .54-.23T15 12t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23M7 5v14z");
}

</style>
