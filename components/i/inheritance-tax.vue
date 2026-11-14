<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w39n957js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inheritance-tax" /></template>
<style>
.w39n957js {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.6 11.5H2.5v-4h19v3.6M4 11.5V20q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022t.147.007h5.579M20 12.043V11.5m-8-4v12.6m0-12.6c-2.5 0-4.5-1-4-3c.5-1.5 3-.5 4 3m0 0c2.5 0 4.5-1 4-3c-.5-1.5-3-.5-4 3m2.75 13.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
