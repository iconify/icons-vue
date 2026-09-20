<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdu38ct0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-access-disabled-outline-sharp" /></template>
<style>
.kdu38ct0d {
  fill: currentColor;
  d: path("M3 17V4.04h1.425l.96.96H4v11h10.97L1.776 2.808l.708-.708l18.684 18.685l-.707.707L15.969 17H13v2h2v1H9v-1h2v-2zm17.066-.15l-.85-.85H20V5H8.216l-1-1H21v12.85zm-6.35-6.35");
}

</style>
