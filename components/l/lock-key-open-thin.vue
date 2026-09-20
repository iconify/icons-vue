<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lrt5uer-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lock-key-open-thin" /></template>
<style>
.lrt5uer-o {
  fill: currentColor;
  d: path("M208 84H92V56a36 36 0 0 1 36-36c17.24 0 32.75 12.38 36.08 28.8a4 4 0 1 0 7.84-1.6C167.78 26.81 149.31 12 128 12a44.05 44.05 0 0 0-44 44v28H48a12 12 0 0 0-12 12v112a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V96a12 12 0 0 0-12-12m4 124a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V96a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4Zm-84-92a24 24 0 0 0-4 47.66V184a4 4 0 0 0 8 0v-20.34a24 24 0 0 0-4-47.66m0 40a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

</style>
