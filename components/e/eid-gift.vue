<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu3869b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eid-gift" /></template>
<style>
.iu3869b1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7h13.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 9.75v-1A1.75 1.75 0 0 1 4.25 7M4 11.5V20q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022t.147.007h7.579M18 12.243V11.5M11 7v14.5M11 7C8.5 7 6.5 5.5 7.5 4s3 .5 3.5 3c.5-2.5 2.5-4.5 3.5-3s-1 3-3.5 3m9 8.25a3.5 3.5 0 1 0 1.5 5.25a2.75 2.75 0 0 1-1.5-5.25");
}

</style>
