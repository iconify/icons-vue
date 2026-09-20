<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5fc5-bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-add-outline-sharp" /></template>
<style>
.d5fc5-bjz {
  fill: currentColor;
  d: path("M3 19h5.808v-5.808H3zm1-9.192V6h6.808v3.808zm-1 1h8.808V5H3zM12.192 18v-3.808H20V18zm-1 1H21v-5.808h-9.808zM4 18v-3.808h3.808V18zm14-7.192q-1.671 0-2.835-1.165Q14 8.48 14 6.808t1.165-2.836T18 2.808t2.836 1.164T22 6.808q0 1.67-1.164 2.835Q19.67 10.808 18 10.808m-.385-1.116h.77v-2.5h2.5v-.769h-2.5v-2.5h-.77v2.5h-2.5v.77h2.5zm-9.807 4.5");
}

</style>
