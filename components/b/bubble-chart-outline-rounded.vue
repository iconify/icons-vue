<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whjg6z14r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bubble-chart-outline-rounded" /></template>
<style>
.whjg6z14r {
  fill: currentColor;
  d: path("M12.73 19.35q-.653-.649-.653-1.576t.65-1.582t1.576-.653q.928 0 1.581.649q.655.649.655 1.577t-.65 1.581q-.65.654-1.577.654t-1.581-.65m2.443-.714q.365-.365.365-.867t-.365-.866t-.866-.365t-.867.365t-.364.866t.364.867t.867.364q.501 0 .866-.365m-1.872-6.937Q12 10.396 12 8.5t1.302-3.198T16.5 4t3.198 1.302T21 8.5t-1.302 3.198T16.5 13t-3.198-1.302m5.686-.71Q20 9.975 20 8.5t-1.012-2.488T16.5 5t-2.488 1.013T13 8.5t1.013 2.488T16.5 12t2.488-1.012M7.23 17.23q-1.333 0-2.282-.95T4 14t.944-2.282t2.287-.949t2.286.944t.945 2.287t-.95 2.286t-2.281.945m1.576-1.656q.655-.655.655-1.576t-.656-1.575t-1.576-.655t-1.575.656T5 14t.656 1.575t1.576.655t1.575-.656M7.23 14");
}

</style>
