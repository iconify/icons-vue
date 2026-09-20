<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyp55dbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:demography-outline-sharp" /></template>
<style>
.dyp55dbup {
  fill: currentColor;
  d: path("M4 20V4h16v7.566q-.263-.091-.504-.148q-.24-.056-.496-.112V5H5v14h6.28q.037.28.094.521q.057.24.147.479zm1-2v1V5v6.306v-.075zm2.5-1.73h3.96q.055-.257.15-.497l.2-.504H7.5zm0-3.77h6.58q.493-.346.971-.586q.478-.241 1.026-.378V11.5H7.5zm0-3.77h9v-1h-9zM18 22.117q-1.671 0-2.835-1.165Q14 19.787 14 18.116t1.165-2.836T18 14.116t2.836 1.164T22 18.116q0 1.67-1.164 2.835Q19.67 22.116 18 22.116m1.063-4.438q.437-.437.437-1.062t-.437-1.063T18 15.116t-1.062.437t-.438 1.063t.438 1.062t1.062.438t1.063-.438m.343 3.088q.644-.35 1.069-.975q-.558-.362-1.185-.53q-.628-.169-1.29-.169t-1.29.169q-.627.168-1.185.53q.425.625 1.07.975t1.405.35t1.406-.35");
}

</style>
