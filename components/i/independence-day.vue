<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tpz9-jbcg"/><path class="ed4d5aclx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:independence-day" /></template>
<style>
.ed4d5aclx {
  d: path("m12 6.25l.823 1.867l2.03.206l-1.522 1.36l.432 1.994L12 10.65l-1.763 1.027l.432-1.994l-1.522-1.36l2.03-.206Z");
}

.tpz9-jbcg {
  d: path("M4.5 2.5v19m0-18c3.5-1.5 6 1.5 9 .25c2.5-1 4.5-.75 6-.25v11c-1.5-.5-3.5-.75-6 .25c-3 1.25-5.5-1.75-9-.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
