<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hz9_lxbmj"/><path class="v_miqkb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entrance-exam" /></template>
<style>
.hz9_lxbmj {
  d: path("M7.5 2.5H18q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T19.5 4v4.279m0 8.1V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_miqkb4a {
  d: path("M5.1 21.5H4v-16h12v1.6m0 12.8v.4M7 10h6m-6 3.5h.8m1.4 0h.4m-.227 4.152l7.779-7.779l2.475 2.475l-7.779 7.779Zm0 0l-1.237 3.712l3.712-1.237Z");
}

</style>
