<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkcnt2bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-alt-rounded" /></template>
<style>
.fkcnt2bgt {
  fill: currentColor;
  d: path("M8.665 16.317q.22-.221.22-.549t-.222-.548t-.549-.22t-.548.222t-.22.549t.222.547t.549.22t.548-.221m0-3.77q.22-.22.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.55t.222.547t.549.22t.548-.221m0-3.77q.22-.221.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.549t.222.548t.549.22t.548-.221m3.027 7.49h4.385q.213 0 .356-.144t.144-.356t-.144-.356t-.356-.144h-4.385q-.212 0-.356.144t-.144.357t.144.356t.356.143m0-3.769h4.385q.213 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-4.385q-.212 0-.356.144t-.144.357t.144.356t.356.143m0-3.77h4.385q.213 0 .356-.143q.144-.144.144-.357t-.144-.356t-.356-.143h-4.385q-.212 0-.356.144t-.144.357t.144.356t.356.143M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
