<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcpntjlpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:first-contact-resolution" /></template>
<style>
.tcpntjlpg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.952 5.083Q16.185 2.75 12 2.75T5.048 5.083Q2.25 7.442 2.25 11q0 2.946 1.936 5.435l-.916 3.893q-.032.137-.013.275q.019.139.087.261q.036.065.084.121t.106.102t.123.08t.137.054t.145.026q.073.007.147-.002q.073-.008.143-.031q.071-.023.135-.058l4.244-2.358q1.911.452 3.392.452q4.185 0 6.952-2.333Q21.75 14.558 21.75 11t-2.798-5.917m-7.978 7.83l4.471-4.918q.05-.054.109-.098q.06-.044.126-.075q.067-.032.139-.05t.145-.021t.147.007t.143.036t.133.063q.063.038.118.088q.11.1.173.235q.064.135.071.284t-.043.29t-.151.251l-5 5.5l-.025.025q-.105.106-.243.163T11 14.75t-.287-.057t-.243-.163l-3-3q-.106-.105-.163-.243T7.25 11t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 10.25t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
