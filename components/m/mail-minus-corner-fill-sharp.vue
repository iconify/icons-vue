<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1zw8acnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-minus-corner-fill-sharp" /></template>
<style>
.v1zw8acnv {
  fill: currentColor;
  d: path("m4.414 5l-1-1h17.172l-6 6H9.414ZM2 19V5.414l6.293 6.293A1 1 0 0 0 9 12h3v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M20 7.414l2-2V11a1 1 0 0 1-1 1h-5.586ZM15 16h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
