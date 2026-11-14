<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiv4at65l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:b-cell" /></template>
<style>
.kiv4at65l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 6.107L7.527 3.082q-.057-.046-.104-.103q-.048-.057-.083-.122t-.057-.136q-.021-.07-.029-.144t-.001-.147t.028-.144t.056-.136q.034-.066.081-.123q.094-.116.225-.187t.28-.086t.291.027q.143.043.259.137L12 4.784l3.527-2.866q.116-.094.259-.137q.143-.042.291-.027q.149.015.28.086t.225.187q.047.057.081.123q.035.065.056.136t.028.144t-.001.147t-.029.144t-.057.136t-.083.122t-.104.103L12.75 6.107v1.677q2.523.236 4.377 2.089Q19.25 11.997 19.25 15t-2.123 5.127T12 22.25t-5.127-2.123Q4.75 18.003 4.75 15t2.123-5.127Q8.727 8.02 11.25 7.784zM7.75 16.25Q7.75 19 10.5 19t2.75-2.75t-2.75-2.75t-2.75 2.75");
}

</style>
