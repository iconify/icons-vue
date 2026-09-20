<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyragkbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-check-sharp" /></template>
<style>
.qyragkbkz {
  fill: currentColor;
  d: path("m10.95 13.289l4.239-4.239l-.714-.708l-3.525 3.544l-1.425-1.424l-.713.713zM6 19.5V4h12v15.5l-6-2.577z");
}

</style>
