<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja_bpvq1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:10k-rounded" /></template>
<style>
.ja_bpvq1d {
  fill: currentColor;
  d: path("M6.77 10.192v4.058q0 .19.125.316q.126.126.317.126q.19 0 .316-.126t.126-.316v-4.5q0-.19-.126-.316t-.316-.126H5.826q-.19 0-.317.126q-.126.126-.126.316t.126.316t.317.126zm3.115 4.5h2.346q.328 0 .549-.22q.22-.22.22-.549v-3.846q0-.329-.22-.549t-.55-.22H9.886q-.33 0-.55.22t-.22.549v3.846q0 .329.22.549t.55.22m.115-.884v-3.616h2.116v3.616zm5.346-1.481l2.166 2.225q.05.056.319.14q.29 0 .404-.262q.113-.263-.085-.478l-1.938-1.99l1.963-1.958q.198-.196.075-.446t-.4-.25q-.079 0-.159.036q-.08.037-.141.104l-2.204 2.187V9.75q0-.19-.126-.316t-.316-.126t-.316.126t-.126.316v4.5q0 .19.126.316t.316.126t.316-.126t.126-.316zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
