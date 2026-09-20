<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucwd6cyij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:high-quality-off-outline" /></template>
<style>
.ucwd6cyij {
  fill: currentColor;
  d: path("m17.385 14.727l-.885-.885V10.5q0-.115-.096-.212t-.212-.096h-2q-.115 0-.211.096q-.097.096-.097.212v.727L13 10.361v-.052q.039-.418.345-.71q.307-.291.732-.291h2.23q.445 0 .761.316q.316.317.316.76zm-10.77-.035V9.308H7.5v2.5h2.616v-1.5l.884.884v3.5h-.885v-2H7.5v2zm-2 4.308q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h.193l1 1H4.616q-.231 0-.424.192T4 6.616v10.769q0 .269.173.442t.443.173H16.38L2.36 3.97l.708-.708l17.15 17.15l-.707.707L17.38 19zm16.173-.87L20 17.343V6.616q0-.27-.173-.443T19.385 6H8.658l-1-1h11.727q.69 0 1.153.463T21 6.616v10.746q0 .217-.04.41t-.172.359m-10.31-6.033");
}

</style>
