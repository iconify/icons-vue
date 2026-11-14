<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-ns0bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inheritance-tax" /></template>
<style>
.z4-ns0bzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5h15.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 9.75v-.5A1.75 1.75 0 0 1 4.25 7.5m-.25 4V20q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022t.147.007h6.479M20 12.243V11.5m-8-4v14m0-14c-2.5 0-4.5-1-4-3c.5-1.5 3-.5 4 3m0 0c2.5 0 4.5-1 4-3c-.5-1.5-3-.5-4 3m2.75 13.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
