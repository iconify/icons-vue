<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et8z96_iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-neck-guard" /></template>
<style>
.et8z96_iv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.61 5.564Q8.261 7.875 12 7.875t5.389-2.31l.001-.001q.055-.078.129-.14h.001l3-2.5q.057-.047.121-.083q.065-.035.136-.057q.07-.022.144-.03t.147-.001t.144.028t.137.055q.065.034.122.081q.058.046.105.103q.096.114.14.257q.044.142.031.291q-.014.148-.083.281q-.069.132-.184.227l-2.73 2.275V12q0 3.875-2.025 6.575Q14.719 21.25 12 21.25t-4.725-2.675Q5.25 15.875 5.25 12V6.351L2.52 4.076q-.057-.047-.103-.105q-.047-.057-.081-.122q-.034-.066-.055-.137t-.028-.144t.001-.147t.03-.144t.057-.136q.036-.064.083-.121t.105-.103t.122-.081q.066-.034.137-.055t.144-.028t.147.001t.144.03t.136.057q.064.036.121.083l3 2.5q.074.061.13.139z");
}

</style>
