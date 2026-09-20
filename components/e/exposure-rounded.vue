<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj5rmtbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:exposure-rounded" /></template>
<style>
.jj5rmtbmw {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.116-.048-.222q-.048-.105-.144-.202L5.192 18.808q.097.096.202.144t.222.048m9.192-3.308H13.25q-.19 0-.316-.126q-.126-.125-.126-.316t.126-.316t.316-.126h1.558V13.25q0-.19.126-.316q.125-.126.316-.126t.316.126t.126.316v1.558h1.558q.19 0 .316.126q.126.125.126.316t-.126.316q-.125.126-.316.126h-1.558v1.558q0 .19-.126.316q-.125.126-.316.126t-.316-.126q-.126-.125-.126-.316zm-4.558-7.5q.19 0 .316-.126t.126-.316t-.126-.316t-.316-.126h-3.5q-.19 0-.316.126t-.126.316t.126.316t.316.126z");
}

</style>
