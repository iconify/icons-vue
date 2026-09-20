<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kldjgvbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airlines-sharp" /></template>
<style>
.kldjgvbca {
  fill: currentColor;
  d: path("M3 19L13.289 5h7.73l-2.807 14zm11.289-5.616q.78 0 1.342-.544t.561-1.333q0-.807-.561-1.35t-1.342-.542q-.765 0-1.315.539q-.551.539-.551 1.352q0 .794.55 1.336q.551.542 1.316.542");
}

</style>
