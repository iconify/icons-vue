<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crq40ivwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-alert" /></template>
<style>
.crq40ivwt {
  fill: currentColor;
  d: path("M3 20v-2h12v2zm9.463-8.462Q11 10.075 11 8t1.463-3.537T16 3t3.538 1.463T21 8t-1.463 3.538T16 13t-3.537-1.463M3 12v-2h6.3q.175.55.4 1.05t.55.95zm0 4v-2h9.4q.575.35 1.225.588t1.375.337V16zm12.5-7h1V5h-1zm.85 1.85q.15-.15.15-.35t-.15-.35T16 10t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
