<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kxau-952q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-circle-dollar-thin" /></template>
<style>
.kxau-952q {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92m36-72a24 24 0 0 1-24 24h-8v12a4 4 0 0 1-8 0v-12h-20a4 4 0 0 1 0-8h36a16 16 0 0 0 0-32h-24a24 24 0 0 1 0-48h8V72a4 4 0 0 1 8 0v12h20a4 4 0 0 1 0 8h-36a16 16 0 0 0 0 32h24a24 24 0 0 1 24 24");
}

</style>
