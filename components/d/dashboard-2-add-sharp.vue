<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wygk3lbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-add-sharp" /></template>
<style>
.wygk3lbni {
  fill: currentColor;
  d: path("M2 20h7v-7H2zm0-9h10V4H2zm9 9h11v-7H11zm7-9q-2.075 0-3.537-1.463T13 6t1.463-3.537T18 1t3.538 1.463T23 6t-1.463 3.538T18 11m-.5-2h1V6.5H21v-1h-2.5V3h-1v2.5H15v1h2.5z");
}

</style>
