<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3ox6q7or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:barcode" /></template>
<style>
.m3ox6q7or {
  fill: currentColor;
  d: path("M2.692 18.308V6.462h1.693v11.846zm2.539 0V6.462h1.692v11.846zm2.538 0V6.462h.847v11.846zm2.539 0V6.462H12v11.846zm2.538 0V6.462h2.539v11.846zm3.385 0V6.462h.846v11.846zm2.538 0V6.462h2.539v11.846z");
}

</style>
