<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwt1zxbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:change-history-outline-sharp" /></template>
<style>
.wwt1zxbjc {
  fill: currentColor;
  d: path("M2 20L12 4l10 16zm3.6-2h12.8L12 7.75zm6.4-5.125");
}

</style>
