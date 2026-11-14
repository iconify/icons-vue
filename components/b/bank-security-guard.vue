<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysqhhlbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bank-security-guard" /></template>
<style>
.ysqhhlbds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.258 2.046l7.5 2.75q.108.04.2.11q.091.07.157.165q.066.094.1.204q.035.11.035.225v6q0 7.276-7.973 10.447Q12.144 22 12 22t-.277-.053Q3.75 18.776 3.75 11.5v-6q0-.115.035-.225q.034-.11.1-.204q.066-.095.157-.165q.092-.07.2-.11l7.5-2.75Q11.867 2 12 2t.258.046M15 9.5q0-3-3-3t-3 3t3 3t3-3m-3 3.25q-3.452 0-4.233 3.591q-.016.072-.017.146t.012.146t.04.142q.027.068.067.131q.04.062.091.115q.052.053.112.095t.129.072q.067.029.14.045q.145.032.292.005q.147-.026.273-.107q.125-.081.21-.203t.117-.269Q9.757 14.25 12 14.25t2.767 2.409q.032.146.117.269q.085.122.21.203q.126.081.273.107q.147.027.292-.005q.146-.032.269-.117q.122-.085.203-.21q.081-.126.107-.273q.027-.147-.005-.292Q15.452 12.75 12 12.75");
}

</style>
