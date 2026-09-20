<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v3fde-ptt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cardholder-thin" /></template>
<style>
.v3fde-ptt {
  fill: currentColor;
  d: path("M208 52H48a20 20 0 0 0-20 20v112a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V72a20 20 0 0 0-20-20M36 92h184v24h-60a4 4 0 0 0-4 4a28 28 0 0 1-56 0a4 4 0 0 0-4-4H36Zm12-32h160a12 12 0 0 1 12 12v12H36V72a12 12 0 0 1 12-12m160 136H48a12 12 0 0 1-12-12v-60h56.22a36 36 0 0 0 71.56 0H220v60a12 12 0 0 1-12 12");
}

</style>
