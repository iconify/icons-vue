<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgpspid6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-gb-english-outline-sharp" /></template>
<style>
.hgpspid6g {
  fill: currentColor;
  d: path("M15 15h4v-2h-4zm0-4h4V9h-4zM3 17V7h8v2H5v6h4v-2H7v-2h4v6zm10 0V7h7l1 1v3l-1 1l1 1v3l-1 1z");
}

</style>
