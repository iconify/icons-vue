<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2iu7lbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:altitude-outline-sharp" /></template>
<style>
.r2iu7lbqq {
  fill: currentColor;
  d: path("M18.5 12V7.108l-2.1 2.08l-.688-.688L19 5.212L22.288 8.5l-.688.714l-2.1-2.1V12zM2.904 20.173l4.192-5.615l3.462 4.615h8.538l-5-6.65l-3 3.993l-.634-.843l3.634-4.846l7 9.346zm8.192-1");
}

</style>
