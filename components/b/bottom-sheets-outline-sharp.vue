<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew2xp-bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-sheets-outline-sharp" /></template>
<style>
.ew2xp-bxh {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-7.384h14V5H5zm0 1V19h14v-5.384zm0 0V19z");
}

</style>
