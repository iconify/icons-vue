<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uew37acet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:barcode-scanner-sharp" /></template>
<style>
.uew37acet {
  fill: currentColor;
  d: path("M1.5 20.5v-4h1v3h3v1zm17 0v-1h3v-3h1v4zM4 18V6h2v12zm3 0V6h1v12zm3 0V6h2v12zm3 0V6h3v12zm4 0V6h1v12zm2 0V6h1v12zM1.5 7.5v-4h4v1h-3v3zm20 0v-3h-3v-1h4v4z");
}

</style>
