<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k_-6n6bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hand-soap-bold" /></template>
<style>
.k_-6n6bog {
  fill: currentColor;
  d: path("M188 97.68V92a36 36 0 0 0-36-36h-12V36h28a4 4 0 0 1 4 4a12 12 0 0 0 24 0a28 28 0 0 0-28-28h-64a12 12 0 0 0 0 24h12v20h-12a36 36 0 0 0-36 36v5.68A44.06 44.06 0 0 0 36 140v76a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20v-76a44.06 44.06 0 0 0-32-42.32M104 80h48a12 12 0 0 1 12 12v4H92v-4a12 12 0 0 1 12-12m92 132H60v-72a20 20 0 0 1 20-20h96a20 20 0 0 1 20 20Z");
}

</style>
