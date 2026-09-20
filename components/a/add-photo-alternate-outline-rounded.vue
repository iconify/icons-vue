<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqi187-cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-photo-alternate-outline-rounded" /></template>
<style>
.fqi187-cj {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h6.5q.213 0 .356.143q.144.144.144.357t-.144.357Q12.329 5 12.116 5h-6.5q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.443v-6.5q0-.213.143-.356q.143-.144.357-.144t.357.144t.143.356v6.5q0 .691-.462 1.153T18.384 20zm1.153-3.616h10.462L14 12.077l-3 3.789l-2-2.404zM17 7h-1.5q-.213 0-.357-.143T15 6.5t.143-.357T15.5 6H17V4.5q0-.213.143-.357T17.5 4t.357.143T18 4.5V6h1.5q.214 0 .357.143T20 6.5t-.143.357T19.5 7H18v1.5q0 .214-.143.357T17.5 9t-.357-.143T17 8.5z");
}

</style>
