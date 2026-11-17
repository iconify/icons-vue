<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-2x4sb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-bitcoin-fill-sharp" /></template>
<style>
.y-2x4sb8q {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107m11.829 3.364A2.996 2.996 0 0 0 14 7.764V7a1 1 0 0 0-2 0h-2a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0h2a1 1 0 0 0 2 0v-.171a3 3 0 0 0 .615-5.358M12 11h-2V9h2a1 1 0 0 1 0 2m1 4h-3v-2h3a1 1 0 0 1 0 2");
}

</style>
