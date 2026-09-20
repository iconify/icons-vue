<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj-t4226c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-color-outline" /></template>
<style>
.uj-t4226c {
  fill: currentColor;
  d: path("M2 24v-2h20v2zm4-7.173h1.073l8.8-8.794l-.532-.552l-.547-.527L6 15.754zm-1 1v-2.5L16.22 4.113q.159-.16.348-.232t.386-.073t.381.073t.35.238l1.029 1.035q.165.16.235.345q.07.186.07.384q0 .186-.073.379q-.073.192-.233.351L7.5 17.827zM18.02 5.881l-1.074-1.073zm-2.147 2.152l-.533-.552l-.546-.527z");
}

</style>
