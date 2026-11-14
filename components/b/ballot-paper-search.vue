<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlpaf1bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ballot-paper-search" /></template>
<style>
.rlpaf1bml {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v6.551q-.589-.176-1.25-.176q-1.76 0-3.005 1.245T13.25 17.5t1.245 3.005q.762.762 1.718 1.058q-1.152.687-2.588.687h-6.25q-2.123 0-3.624-1.501T2.25 17.125V6.875q0-2.123 1.501-3.624T7.375 1.75m3 3h-1.75q-3.375 0-3.375 3.375v1.75q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-1.75q0-3.375-3.375-3.375M17.5 14.5q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5m-.25-1.5q0 .25.25.25t.25-.25t-.25-.25t-.25.25");
}

</style>
