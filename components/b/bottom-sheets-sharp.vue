<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfbdq0bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-sheets-sharp" /></template>
<style>
.pfbdq0bib {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-7.384h14V5H5z");
}

</style>
