<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ygrlccbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-out-thin" /></template>
<style>
.ygrlccbdy {
  fill: currentColor;
  d: path("M212 48v48a4 4 0 0 1-8 0V57.66l-49.17 49.17a4 4 0 0 1-5.66-5.66L198.34 52H160a4 4 0 0 1 0-8h48a4 4 0 0 1 4 4M101.17 149.17L52 198.34V160a4 4 0 0 0-8 0v48a4 4 0 0 0 4 4h48a4 4 0 0 0 0-8H57.66l49.17-49.17a4 4 0 0 0-5.66-5.66M208 156a4 4 0 0 0-4 4v38.34l-49.17-49.17a4 4 0 0 0-5.66 5.66L198.34 204H160a4 4 0 0 0 0 8h48a4 4 0 0 0 4-4v-48a4 4 0 0 0-4-4M57.66 52H96a4 4 0 0 0 0-8H48a4 4 0 0 0-4 4v48a4 4 0 0 0 8 0V57.66l49.17 49.17a4 4 0 0 0 5.66-5.66Z");
}

</style>
