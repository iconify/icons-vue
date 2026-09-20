<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cj98zxbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-heart-light" /></template>
<style>
.cj98zxbzs {
  fill: currentColor;
  d: path("M34 64a6 6 0 0 1 6-6h176a6 6 0 0 1 0 12H40a6 6 0 0 1-6-6m6 70h64a6 6 0 0 0 0-12H40a6 6 0 0 0 0 12m80 52H40a6 6 0 0 0 0 12h80a6 6 0 0 0 0-12m126-42c0 35.3-49.22 60.32-51.32 61.37a6 6 0 0 1-5.36 0C187.22 204.32 138 179.3 138 144a30 30 0 0 1 54-18a30 30 0 0 1 54 18m-12 0a18 18 0 0 0-36 0a6 6 0 0 1-12 0a18 18 0 0 0-36 0c0 14.15 11.78 27 21.67 35.25A139 139 0 0 0 192 193.19a138 138 0 0 0 20.33-13.94C222.22 171 234 158.15 234 144");
}

</style>
