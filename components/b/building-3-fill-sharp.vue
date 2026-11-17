<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oio_i1biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-fill-sharp" /></template>
<style>
.oio_i1biu {
  fill: currentColor;
  d: path("M6 4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v15h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-6a1 1 0 0 1 .375-.781L6 10.919Zm3.375 4.219a1 1 0 0 1 1.25 0l5 4A1 1 0 0 1 16 13v6h2V5H8v4.319Z");
}

</style>
