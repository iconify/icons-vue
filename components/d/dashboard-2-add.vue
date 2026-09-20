<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccoea-90k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-add" /></template>
<style>
.ccoea-90k {
  fill: currentColor;
  d: path("M3 19h5.808v-5.808H3zm0-8.192h8.808V5H3zM11.192 19H21v-5.808h-9.808zM18 10.808q-1.671 0-2.835-1.165Q14 8.48 14 6.808t1.165-2.836T18 2.808t2.836 1.164T22 6.808q0 1.67-1.164 2.835Q19.67 10.808 18 10.808m-.385-1.116h.77v-2.5h2.5v-.769h-2.5v-2.5h-.77v2.5h-2.5v.77h2.5z");
}

</style>
