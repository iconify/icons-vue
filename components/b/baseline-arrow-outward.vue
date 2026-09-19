<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4dnnzrwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-arrow-outward" /></template>
<style>
.n4dnnzrwg {
  fill: currentColor;
  d: path("M6 6v2h8.59L5 17.59L6.41 19L16 9.41V18h2V6z");
}

</style>
