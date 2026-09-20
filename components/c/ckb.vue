<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vli-ujzjg"/><path class="lh2ch-34c"/><path class="rh9imbbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ckb" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lh2ch-34c {
  fill: var(--svg-color--d8d8d8, #d8d8d8);
  d: path("M12 4.125h2.998L21 10.313h-2.813zm-9 9.563h2.813L12 19.875H9.002z");
}

.rh9imbbqb {
  fill: var(--svg-color--3cc68a, #3cc68a);
  d: path("M14.813 6.937v6.587l-9-9.281v9.444l3.375 3.375v-6.34l9 9.153v-9.563z");
}

.vli-ujzjg {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 4.125v9.563h2.813V4.124zm15.187 6.188v9.562H21v-9.562zM12 4.125v6.536l2.813 2.897v-6.62zM9.187 10.56v6.502L12 19.876v-6.294z");
}

</style>
