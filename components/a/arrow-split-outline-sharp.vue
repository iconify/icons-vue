<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6w_aebsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-split-outline-sharp" /></template>
<style>
.e6w_aebsk {
  fill: currentColor;
  d: path("M5 12.5v-1h6.792l5.5-5.5H14V5h5v5h-1V6.708L12.208 12.5zm9 6.5v-1h3.292l-3.854-3.842l.72-.72L18 17.293V14h1v5z");
}

</style>
