<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n33v6cbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:infinity-army" /></template>
<style>
.n33v6cbrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 39.696L23.913 8.304L42 39.696l-14.609-4.087l-.174-5.13l4.957 1.651l-8.261-14.608l-8 14.26l4.783-1.304l-.087 5.13z");
}

</style>
