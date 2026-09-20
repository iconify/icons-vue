<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a3au15bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:finn-the-human-light" /></template>
<style>
.a3au15bsh {
  fill: currentColor;
  d: path("M168 106H88a38 38 0 0 0-38 38v8a38 38 0 0 0 38 38h80a38 38 0 0 0 38-38v-8a38 38 0 0 0-38-38m26 46a26 26 0 0 1-26 26H88a26 26 0 0 1-26-26v-8a26 26 0 0 1 26-26h80a26 26 0 0 1 26 26Zm14-110a30.05 30.05 0 0 0-29.4 24H77.4A30 30 0 0 0 18 72v80a70.08 70.08 0 0 0 70 70h80a70.08 70.08 0 0 0 70-70V72a30 30 0 0 0-30-30m18 110a58.07 58.07 0 0 1-58 58H88a58.07 58.07 0 0 1-58-58V72a18 18 0 0 1 36 0a6 6 0 0 0 6 6h112a6 6 0 0 0 6-6a18 18 0 0 1 36 0Zm-124-4a10 10 0 1 1-10-10a10 10 0 0 1 10 10m72 0a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
