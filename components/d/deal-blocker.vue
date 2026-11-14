<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dki0_i09k"/><path class="izj-g0gjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deal-blocker" /></template>
<style>
.dki0_i09k {
  d: path("M12.131 19.5H9.905q-.161 0-.322-.02q-.16-.02-.316-.059q-.157-.039-.308-.097q-.15-.058-.293-.135q-.142-.076-.274-.169t-.251-.201q-.12-.109-.225-.231t-.195-.257l-3.25-4.875q-.107-.161-.19-.336q-.082-.174-.138-.359t-.085-.377Q4.03 12.193 4.03 12t.028-.384q.029-.192.085-.377t.138-.359q.083-.175.19-.336l3.25-4.875q.09-.134.195-.257q.105-.122.225-.231q.119-.108.251-.201t.274-.169t.293-.135t.308-.097q.156-.039.316-.059q.161-.02.322-.02h6.97q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v5.012M8.25 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izj-g0gjm {
  d: path("M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m1 2.25l4.5-4.5");
}

</style>
