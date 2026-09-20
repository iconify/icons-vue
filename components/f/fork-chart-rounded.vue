<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz5yzsbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fork-chart-rounded" /></template>
<style>
.gz5yzsbqt {
  fill: currentColor;
  d: path("M3.692 19v-7.404q-.534-.098-.92-.479q-.388-.38-.388-1.086V6.384q0-.161.112-.273Q2.608 6 2.77 6t.273.112t.112.273V9.23h.596V6.385q0-.162.112-.273T4.134 6t.274.112t.111.273V9.23h.597V6.385q0-.162.111-.273T5.5 6t.273.112t.112.273v3.646q0 .706-.387 1.086t-.921.48V19zM19.806 7.35q.838.929 1.304 2.109T21.577 12q0 1.342-.47 2.503q-.468 1.16-1.269 2.09L15.267 12zm-4.729-2.333q1.138.067 2.155.49q1.016.422 1.841 1.13l-3.996 4.155zM14.577 19q-2.927 0-4.973-2.037T7.558 12q0-2.786 1.887-4.796t4.632-2.192v7.202l5.067 5.092q-.91.8-2.08 1.247T14.578 19");
}

</style>
