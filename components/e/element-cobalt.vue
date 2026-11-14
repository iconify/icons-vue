<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_ej2rbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-cobalt" /></template>
<style>
.d_ej2rbgt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25m-3.497 4.036l3.25 1.882q.261.151.461.337q.053.007.104.02q.144.039.263.129q.118.091.193.22q.044.076.069.16t.031.171q.005.088-.01.174t-.05.167q.061.267.061.569v3.77q0 1.297-1.122 1.947l-3.25 1.882q-.263.152-.526.234q-.053.07-.12.126q-.067.057-.145.096q-.079.04-.164.06t-.173.02t-.173-.02t-.164-.06q-.078-.039-.145-.096q-.067-.056-.12-.126q-.263-.082-.526-.234l-3.25-1.882Q6.5 15.182 6.5 13.885v-3.77q0-.302.061-.569q-.035-.081-.05-.167t-.01-.174q.006-.087.031-.171t.069-.16q.044-.075.104-.139q.059-.063.132-.111t.155-.078t.169-.041q.2-.186.461-.337l3.25-1.882q1.128-.653 2.256 0");
}

</style>
