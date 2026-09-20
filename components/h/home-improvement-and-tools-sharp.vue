<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn-26sb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-improvement-and-tools-sharp" /></template>
<style>
.jn-26sb5l {
  fill: currentColor;
  d: path("M6 2h12l-3 4.2V10H9V6.2zm3 10h6v2H9zm0 4h6v3l-3 3l-3-3z");
}

</style>
