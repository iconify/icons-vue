<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9twz8lyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aviator-goggles" /></template>
<style>
.y9twz8lyb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.818 7.318q-1.3 1.3-1.318 3.132q-.473 3.763 2.7 6.006q2.714 1.919 6.8 1.919t6.8-1.919q3.173-2.243 2.7-6.006q-.018-1.832-1.318-3.132Q18.864 6 17 6t-3.182 1.318q-.807.807-1.12 1.819Q12.358 9 12 9t-.698.137q-.313-1.012-1.12-1.819Q8.864 6 7 6T3.818 7.318m2.248 7.913q-.332-.234-.612-.49Q6.173 15 7 15q1.864 0 3.182-1.318q1.212-1.212 1.309-2.885q.294-.297.509-.297t.509.297q.097 1.673 1.309 2.885Q15.136 15 17 15q.827 0 1.546-.259q-.28.256-.612.49q-2.325 1.644-5.934 1.644t-5.934-1.644");
}

</style>
