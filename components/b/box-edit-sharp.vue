<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-e-03ksn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:box-edit-sharp" /></template>
<style>
.t-e-03ksn {
  fill: currentColor;
  d: path("M4 20V6.916L6.416 4h11.15L20 6.954v1.729l-5 4.98V7.808H9v6.788l3-1.5l2.383 1.185l-2.537 2.511V20zm10.23 0v-2.21l5.96-5.934l2.19 2.204L16.44 20zm5.96-4.985l.925-.956l-.924-.943l-.95.95zM5.38 6.808H18.6L17.096 5H6.885z");
}

</style>
