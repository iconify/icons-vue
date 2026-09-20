<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2iqzxb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-outer-outline-sharp" /></template>
<style>
.g2iqzxb8e {
  fill: currentColor;
  d: path("M5 19h14V5H5zm-1 1V4h16v16zm3.692-7.384v-1.231h1.231v1.23zm3.692 3.692v-1.231h1.231v1.23zm0-3.692v-1.231h1.231v1.23zm0-3.693v-1.23h1.231v1.23zm3.693 3.693v-1.231h1.23v1.23z");
}

</style>
