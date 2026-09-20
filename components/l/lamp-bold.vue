<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q07ka-gah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lamp-bold" /></template>
<style>
.q07ka-gah {
  fill: currentColor;
  d: path("m251 147.27l-48-112A12 12 0 0 0 192 28H64a12 12 0 0 0-11 7.27l-48 112A12 12 0 0 0 16 164h100v40H96a12 12 0 0 0 0 24h64a12 12 0 0 0 0-24h-20v-40h48v28a12 12 0 0 0 24 0v-28h28a12 12 0 0 0 11-16.73M34.2 140l37.71-88h112.18l37.71 88Z");
}

</style>
