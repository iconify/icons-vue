<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikvlocc4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:3k-rounded" /></template>
<style>
.ikvlocc4z {
  fill: currentColor;
  d: path("m13.77 12.327l2.165 2.225q.05.056.319.14q.29 0 .404-.262t-.085-.478l-1.939-1.99l1.964-1.958q.198-.196.075-.446t-.4-.25q-.079 0-.158.036q-.08.037-.142.104l-2.204 2.186V9.75q0-.19-.126-.316t-.316-.126t-.316.126t-.126.316v4.5q0 .19.126.316t.316.126t.316-.126t.126-.316zm-3.885 1.48H7.326q-.19 0-.317.127q-.126.126-.126.316t.126.316t.317.126H10q.329 0 .549-.22t.22-.549v-3.846q0-.329-.22-.549T10 9.308H7.327q-.19 0-.316.126t-.126.316t.126.316t.316.126h2.558v1.423H8.269q-.161 0-.273.112q-.112.111-.112.273t.112.273t.273.111h1.615zM5.615 20q-.69 0-1.152-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
