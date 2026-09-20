<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_limobum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ar-on-you" /></template>
<style>
.g_limobum {
  fill: currentColor;
  d: path("M16.964 7.034Q19 9.067 19 11.997t-2.033 4.967T12.003 19t-4.966-2.033T5 12.003t2.034-4.966T11.997 5t4.967 2.034m-3.025 7.51Q14.81 13.97 15.23 13H8.769q.42.971 1.292 1.543q.873.573 1.939.573t1.939-.573m-4.936-3.965q.233.23.577.23t.575-.233t.23-.578t-.233-.575q-.234-.23-.578-.23t-.575.234t-.23.577t.234.575m4.846 0q.233.23.578.23t.574-.233t.23-.578t-.233-.575t-.578-.23t-.575.234t-.23.577t.234.575M2 6V3.616q0-.667.475-1.142T3.614 2H6v1H3.616q-.27 0-.443.173T3 3.616V6zm4 16H3.616q-.667 0-1.142-.475T2 20.386V18h1v2.385q0 .269.173.442t.443.173H6zm12-.192v-1h2.385q.269 0 .442-.174q.173-.173.173-.442v-2.384h1v2.384q0 .667-.475 1.141t-1.14.475zM21 6V3.616q0-.27-.173-.443T20.385 3H18V2h2.385q.666 0 1.14.475T22 3.614V6z");
}

</style>
