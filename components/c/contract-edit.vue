<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv_ha0pim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contract-edit" /></template>
<style>
.fv_ha0pim {
  fill: currentColor;
  d: path("M9.385 8.385v-1h8.23v1zm0 2.769v-1h8.23v1zM14.23 21v-2.21l5.333-5.307q.148-.13.307-.19q.16-.062.32-.062q.165 0 .334.064q.17.065.298.194l.925.944q.123.148.187.308q.065.159.065.319t-.052.322t-.2.31L16.44 21zm5.96-4.985l.925-.956l-.925-.943l-.95.95zM6 21q-.846 0-1.423-.577T4 19v-2.77h3V3h13v7.871q-.27.008-.513.057t-.487.14V4H8v12.23h5.346l-1.5 1.5V21z");
}

</style>
