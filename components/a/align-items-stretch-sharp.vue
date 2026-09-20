<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-nr8zbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-items-stretch-sharp" /></template>
<style>
.h-nr8zbtq {
  fill: currentColor;
  d: path("M7 18V6h3v12zm7 0V6h3v12zM2 4V2h20v2zm0 18v-2h20v2z");
}

</style>
