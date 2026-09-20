<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-b4lb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:finance-outline-sharp" /></template>
<style>
.ba-b4lb8p {
  fill: currentColor;
  d: path("M3 21V3h2v16h16v2zm3-3V9h4v9zm5 0V4h4v14zm5 0v-5h4v5z");
}

</style>
