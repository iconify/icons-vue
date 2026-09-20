<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la70tlbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gif-box-sharp" /></template>
<style>
.la70tlbsl {
  fill: currentColor;
  d: path("M4 20V4h16v16zm7.539-5.288h.884V9.327h-.884zm-5.154 0h3.769v-2.539h-.885v1.654h-2v-3.615h2.885v-.885h-3.77zm7.538 0h.885v-2.154h1.923v-.885h-1.923v-1.461h2.923v-.885h-3.808z");
}

</style>
