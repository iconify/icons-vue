<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ons2e9rtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-supervised" /></template>
<style>
.ons2e9rtu {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v2.294q-.76-.452-1.602-.681T17.668 10q-2.797 0-4.646 1.947t-1.849 4.567q0 .646.127 1.261T11.68 19zm9.769 0v-.165q0-.876.869-1.355t2.438-.48t2.439.48t.869 1.355V19zm2.241-4.049q-.434-.434-.434-1.066t.434-1.067t1.066-.433t1.067.433t.433 1.067t-.433 1.066t-1.067.434t-1.066-.434");
}

</style>
