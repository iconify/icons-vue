<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brf054g3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-settings-outline-sharp" /></template>
<style>
.brf054g3u {
  fill: currentColor;
  d: path("M8 14.192h.885v-3H8v1.058H6.5v.885H8zm1.885-1.057H17.5v-.885H9.885zm5.23-2.327H16V9.75h1.5v-.885H16V7.809h-.885zM6.5 9.75h7.616v-.885H6.5zM9 20v-2H3V4h18v14h-6v2zm-5-3h16V5H4zm0 0V5z");
}

</style>
