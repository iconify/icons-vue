<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zay2ahbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:4g-mobiledata-sharp" /></template>
<style>
.zay2ahbkc {
  fill: currentColor;
  d: path("M7.5 16.5v-3h-4v-6h1v5h3v-5h1v5h2v1h-2v3zm5 0v-9h8v1h-7v7h6v-3H17v-1h3.5v5z");
}

</style>
