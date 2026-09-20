<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m57lysibs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-arrow-up-20-filled" /></template>
<style>
.m57lysibs {
  fill: currentColor;
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h2.482c.464 0 .91.184 1.238.513l1.28 1.28l-2.06 2.06A.5.5 0 0 1 7.085 7H2zM2 8v6.5A2.5 2.5 0 0 0 4.5 17h5.1a5.5 5.5 0 0 1 8.4-6.743V7.5A2.5 2.5 0 0 0 15.5 5h-4.793l-2.56 2.56A1.5 1.5 0 0 1 7.085 8zm17 6.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4.854-2.353l-2 2a.5.5 0 0 0 .708.707L14 13.707V16.5a.5.5 0 0 0 1 0v-2.793l1.146 1.147a.5.5 0 0 0 .708-.708l-2-2a.5.5 0 0 0-.351-.146h-.006a.5.5 0 0 0-.348.144z");
}

</style>
