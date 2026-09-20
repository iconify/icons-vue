<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c9q1b2rxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:elevator-fill" /></template>
<style>
.c9q1b2rxk {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-96 24h32a8 8 0 0 1 0 16h-32a8 8 0 0 1 0-16m8 152H64V96h56Zm72 0h-56V96h56Z");
}

</style>
