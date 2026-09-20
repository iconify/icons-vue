<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cidamgb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gesture-select-sharp" /></template>
<style>
.cidamgb0r {
  fill: currentColor;
  d: path("M2.346 11.462V10.23h1.231v1.23zm18.077 0V10.23h1.23v1.23zM2.346 7.846v-1.23h1.231v1.23zm18.077 0v-1.23h1.23v1.23zM2.346 4.231V3h1.231v1.23zm3.616 7.23v-1.23h1.23v1.23zm10.846 0v-1.23h1.23v1.23zm3.615-7.23V3h1.23v1.23zm-14.461 0V3h1.23v1.23zm3.615 0V3h1.23v1.23zm3.615 0V3h1.231v1.23zm3.616 0V3h1.23v1.23zm-5.14 17.25q-.5 0-.945-.187t-.807-.546l-4.354-4.344l1.003-1.029l2.781.627V7.5h1v7.308h1.77v-4.27h1v4.27h1.769v-2.885h1v2.885h1.769v-.5h1v3.673q0 1.457-1.021 2.478t-2.48 1.022z");
}

</style>
