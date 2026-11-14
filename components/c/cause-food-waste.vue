<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljtph1ftu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cause-food-waste" /></template>
<style>
.ljtph1ftu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 6l1.25 13.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036t.146.022t.147.007h3.321m6.315-8.37L18.5 6m-15 0h17m-11 0V3.5h5V6m.5 15.5c0-4.25 2.25-6.5 6.5-6.5c0 4.25-2.25 6.5-6.5 6.5Zm0 0l3.5-3.5");
}

</style>
