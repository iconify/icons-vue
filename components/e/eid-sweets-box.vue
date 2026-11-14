<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbdci4ksx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eid-sweets-box" /></template>
<style>
.mbdci4ksx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18v4.5H3Zm1.5 4.5V19q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6 20.5h6.179m7.321-8.657V11.5M12 7v8.9m0 4.2v.4M12 7C9.5 2.5 5.5 5 9 7m3 0c2.5-4.5 6.5-2 3 0m4.75 8a3.5 3.5 0 1 0 1.5 4a3 3 0 0 1-1.5-4Z");
}

</style>
