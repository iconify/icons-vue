<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j99w9-bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-hygiene-kit" /></template>
<style>
.j99w9-bal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 12.143V8.5H4V18q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022t.147.007h6.679M4 8.5l-1.5-5H8l2.5 5l2.5-5h5.5l-1.5 5m1 6.25c1.5 2 3 3 3 4.25a3 3 0 0 1-6 0c0-1.25 1.5-2.25 3-4.25");
}

</style>
