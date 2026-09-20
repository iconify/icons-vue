<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bywuxhbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-clock-sharp" /></template>
<style>
.bywuxhbcm {
  fill: currentColor;
  d: path("M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v6.867q-.244-.09-.494-.134T19 11.652v-1.036H5V20h7.32q.078.28.2.521q.122.24.255.479zm11.549-.164Q14.385 19.67 14.385 18t1.164-2.835T18.384 14q1.672 0 2.836 1.165q1.165 1.164 1.165 2.835t-1.165 2.836T18.385 22t-2.836-1.164m4.492-.634l.546-.546l-1.818-1.818v-2.722H18v3.046z");
}

</style>
