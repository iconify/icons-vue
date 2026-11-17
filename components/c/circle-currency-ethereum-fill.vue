<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll1tlqo7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-ethereum-fill" /></template>
<style>
.ll1tlqo7e {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107m8.382 10.448a1 1 0 0 0 1.664 0l4-6a1 1 0 0 0 0-1.11l-4-6a1 1 0 0 0-.636-.426h-.002a1 1 0 0 0-.749.149l-.001.001a1 1 0 0 0-.276.276l-4 6a1 1 0 0 0 0 1.11Zm3.213-7.181L12 11.969l-2.381-.595L12 7.803Zm-4.114 2.223l1.49.373a1 1 0 0 0 .486 0l1.49-.373l-1.733 2.6Z");
}

</style>
