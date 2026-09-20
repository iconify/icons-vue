<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g33ab7d-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fiber-smart-record-sharp" /></template>
<style>
.g33ab7d-m {
  fill: currentColor;
  d: path("M9.004 18q-2.506 0-4.255-1.745T3 12.004t1.745-4.255T8.996 6t4.255 1.745T15 11.996t-1.745 4.255T9.004 18M16 17.9v-1q1.75-.35 2.875-1.725T20 12t-1.125-3.175T16 7.1v-1q2.177.35 3.589 2.024T21 12t-1.412 3.876T16 17.9");
}

</style>
