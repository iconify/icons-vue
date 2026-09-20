<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="illmc7b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:currency-franc" /></template>
<style>
.illmc7b9d {
  fill: currentColor;
  d: path("M7 21v-3H5v-2h2V3h11v2H9v6h8v2H9v3h4v2H9v3z");
}

</style>
