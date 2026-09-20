<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9bu7pbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-truck-sharp" /></template>
<style>
.p9bu7pbqg {
  fill: currentColor;
  d: path("M5.144 19.468q-.76-.763-.76-1.852H2V11h11V6h3.5V4.692h2V6h1.764L22 11.148v6.468h-2.384q0 1.09-.765 1.852t-1.855.763t-1.852-.763t-.76-1.852H9.616q0 1.096-.765 1.855q-.764.76-1.856.76q-1.091 0-1.85-.763m3-.707q.47-.47.47-1.136t-.47-1.145T7 16t-1.145.48t-.47 1.145t.47 1.136T7 19.23t1.145-.47m10 0q.47-.47.47-1.136t-.47-1.145T17 16t-1.145.48t-.47 1.145t.47 1.136t1.145.47t1.145-.47M14 11h6.9l-1.33-4H14zM2 10v-.885h1v-2.23H2V6h9.385v.885h-1v2.23h1V10zm1.885-.885H6.25v-2.23H3.884zm3.25 0H9.5v-2.23H7.134z");
}

</style>
