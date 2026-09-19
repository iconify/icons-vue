<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="othhkgbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungthai-one" /></template>
<style>
.othhkgbzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.726 37.33c-1.658.518-3.42.797-5.249.797c-9.706 0-17.574-7.868-17.574-17.575S12.77 2.977 22.477 2.977C34.087 2.977 43.5 12.39 43.5 24s-9.412 21.023-21.023 21.023c-6.982 0-14.154-3.404-17.977-8.643");
}

</style>
