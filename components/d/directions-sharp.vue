<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wonepdvpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-sharp" /></template>
<style>
.wonepdvpb {
  fill: currentColor;
  d: path("M8 15h2v-3h3.5v2.5L17 11l-3.5-3.5V10H8zm4 7.8L1.2 12L12 1.2L22.8 12z");
}

</style>
