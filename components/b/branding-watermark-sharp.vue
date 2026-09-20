<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhm3sgb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:branding-watermark-sharp" /></template>
<style>
.dhm3sgb_q {
  fill: currentColor;
  d: path("M10.5 16.5h8v-5.692h-8zM3 19V5h18v14z");
}

</style>
