<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gqqvc-t3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hand-deposit-fill" /></template>
<style>
.gqqvc-t3l {
  fill: currentColor;
  d: path("M232 198.65V240a8 8 0 0 1-16 0v-41.35A74.84 74.84 0 0 0 192 144v58.35a8 8 0 0 1-14.69 4.38l-10.68-16.31c-.08-.12-.16-.25-.23-.38a12 12 0 0 0-20.89 11.83l22.13 33.79a8 8 0 0 1-13.39 8.76l-22.26-34l-.24-.38c-.38-.66-.73-1.33-1.05-2H56a8 8 0 0 1-8-8V96a16 16 0 0 1 16-16h48v48a8 8 0 0 0 16 0V80h48a16 16 0 0 1 16 16v27.62a90.89 90.89 0 0 1 40 75.03M128 35.31l18.34 18.35a8 8 0 0 0 11.32-11.32l-32-32a8 8 0 0 0-11.32 0l-32 32a8 8 0 0 0 11.32 11.32L112 35.31V80h16Z");
}

</style>
