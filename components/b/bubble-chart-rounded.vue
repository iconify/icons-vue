<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5mmyxsqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bubble-chart-rounded" /></template>
<style>
.w5mmyxsqk {
  fill: currentColor;
  d: path("M12.73 19.346q-.653-.654-.653-1.577t.654-1.577t1.577-.653t1.577.653t.654 1.577t-.654 1.577t-1.577.654t-1.577-.654m.571-7.648Q12 10.396 12 8.5t1.302-3.198T16.5 4t3.198 1.302T21 8.5t-1.302 3.198T16.5 13t-3.198-1.302m-6.071 5.533q-1.342 0-2.287-.945T4 14t.944-2.286t2.287-.945t2.286.944t.945 2.287t-.945 2.286t-2.286.945");
}

</style>
