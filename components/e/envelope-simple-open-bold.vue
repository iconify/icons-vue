<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v5tevmfiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:envelope-simple-open-bold" /></template>
<style>
.v5tevmfiz {
  fill: currentColor;
  d: path("m230.66 86l-96-64a12 12 0 0 0-13.32 0l-96 64A12 12 0 0 0 20 96v104a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V96a12 12 0 0 0-5.34-10M128 46.42l74.86 49.91L141.61 140h-27.22L53.14 96.33ZM44 196v-76.71l59.58 42.48a12 12 0 0 0 7 2.23h34.9a12 12 0 0 0 7-2.23L212 119.29V196Z");
}

</style>
