<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teg8udb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-currency-yuan" /></template>
<style>
.teg8udb9t {
  fill: currentColor;
  d: path("M13.28 12H18v2h-5v7h-2v-7H6v-2h4.72L5 3h2.37L12 10.29L16.63 3H19z");
}

</style>
