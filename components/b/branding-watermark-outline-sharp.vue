<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0931em8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:branding-watermark-outline-sharp" /></template>
<style>
.v0931em8p {
  fill: currentColor;
  d: path("M10.5 16.5h8v-5.692h-8zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
