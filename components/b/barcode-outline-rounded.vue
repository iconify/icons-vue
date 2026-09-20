<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjf5n1bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:barcode-outline-rounded" /></template>
<style>
.vjf5n1bbw {
  fill: currentColor;
  d: path("M1 19V5h2v14zm3 0V5h2v14zm3 0V5h1v14zm3 0V5h2v14zm3 0V5h3v14zm4 0V5h1v14zm3 0V5h3v14z");
}

</style>
