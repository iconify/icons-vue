<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crfeiwerh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:3p-sharp" /></template>
<style>
.crfeiwerh {
  fill: currentColor;
  d: path("M8 14h8v-.55q0-1.1-1.1-1.775T12 11t-2.9.675T8 13.45zm5.413-4.587Q14 8.825 14 8t-.587-1.412T12 6t-1.412.588T10 8t.588 1.413T12 10t1.413-.587M2 22V2h20v16H6z");
}

</style>
