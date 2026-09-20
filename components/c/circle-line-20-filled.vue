<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pqphanbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-line-20-filled" /></template>
<style>
.pqphanbpv {
  fill: currentColor;
  d: path("M17.985 10.5H2.015a8 8 0 0 0 15.97 0m0-1H2.015a8 8 0 0 1 15.97 0");
}

</style>
