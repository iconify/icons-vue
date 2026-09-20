<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8jiiqcba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chevron-line-up-outline" /></template>
<style>
.p8jiiqcba {
  fill: currentColor;
  d: path("M6.5 7.77v-1h11v1zm.9 10.015l-.708-.708L12 11.769l5.308 5.308l-.708.707l-4.6-4.6z");
}

</style>
