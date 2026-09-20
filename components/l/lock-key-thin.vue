<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xqyqtnb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lock-key-thin" /></template>
<style>
.xqyqtnb3o {
  fill: currentColor;
  d: path("M208 84h-36V56a44 44 0 0 0-88 0v28H48a12 12 0 0 0-12 12v112a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V96a12 12 0 0 0-12-12M92 56a36 36 0 0 1 72 0v28H92Zm120 152a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V96a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4Zm-84-92a24 24 0 0 0-4 47.66V184a4 4 0 0 0 8 0v-20.34a24 24 0 0 0-4-47.66m0 40a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

</style>
