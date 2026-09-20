<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgsi7w_iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-add" /></template>
<style>
.sgsi7w_iu {
  fill: currentColor;
  d: path("M18 9V6h-3V5h3V2h1v3h3v1h-3v3zm-3 11H9v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h8.197q-.099.36-.148.74t-.049.78q0 2.443 1.711 4.154q1.71 1.71 4.155 1.71q.683 0 1.314-.145q.632-.145 1.205-.424v5.57q0 .69-.462 1.152T19.385 18H15z");
}

</style>
