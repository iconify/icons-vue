<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re8kpxgll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:imagesmode-rounded" /></template>
<style>
.re8kpxgll {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm2.692-3.5h7.538q.243 0 .354-.217t-.03-.43l-2.02-2.712q-.13-.162-.323-.162q-.192 0-.323.162l-2.292 2.898l-1.427-1.725q-.131-.143-.314-.143q-.182 0-.313.162l-1.154 1.52q-.162.213-.05.43t.354.217m.899-7.293Q9.5 8.914 9.5 8.5t-.293-.707T8.5 7.5t-.707.293T7.5 8.5t.293.707t.707.293t.707-.293");
}

</style>
