<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkk011b-k"/><path class="nt8r6djex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:macave" /></template>
<style>
.mkk011b-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.898 5.576c9.719 0 17.602 7.882 17.602 17.602c0 9.733-7.882 17.615-17.602 17.615S7.296 32.91 7.296 23.178c0-9.72 7.882-17.602 17.602-17.602M5.5 42.424l6.84-6.648");
}

.nt8r6djex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.73 39.71V27.468c-.302-4.29 3.467-4.29 3.467-8.197v-7.623h2.839v7.623c0 3.907 3.715 3.907 3.715 8.197V39.71m-10.02-10.706h10.02m-10.02 6.099h10.02");
}

</style>
