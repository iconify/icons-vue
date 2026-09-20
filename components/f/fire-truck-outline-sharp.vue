<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dge27-b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-truck-outline-sharp" /></template>
<style>
.dge27-b2o {
  fill: currentColor;
  d: path("M5.144 19.471q-.76-.76-.76-1.855H2V11h11V6h3.5V4.692h2V6h1.764L22 11.148v6.468h-2.384q0 1.096-.76 1.855q-.76.76-1.856.76t-1.856-.76t-.76-1.855H9.616q0 1.096-.76 1.855q-.76.76-1.856.76t-1.856-.76m3.001-.71q.47-.47.47-1.145q0-.656-.47-1.136T7 16t-1.145.48t-.47 1.135q0 .676.47 1.146T7 19.23t1.145-.47m10 0q.47-.47.47-1.145q0-.656-.47-1.136T17 16t-1.145.48t-.47 1.135q0 .676.47 1.146t1.145.47t1.145-.47M3 12v4.616h1.64q.272-.725.914-1.17Q6.196 15 7 15t1.446.445t.913 1.17H13V12zm11 4.616h.64q.271-.725.914-1.17Q16.196 15 17 15t1.446.445t.913 1.17H21V12h-7zM14 11h6.9l-1.33-4H14zM2 10v-.885h1v-2.23H2V6h9.385v.885h-1v2.23h1V10zm1.885-.885H6.25v-2.23H3.884zm3.25 0H9.5v-2.23H7.134zM13 12H3zm1 0h7z");
}

</style>
