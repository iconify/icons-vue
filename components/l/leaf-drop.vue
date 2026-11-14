<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8wp1bcmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-drop" /></template>
<style>
.h8wp1bcmm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.81 11.43Q4.328 9.354 2.789 4.738q.046.137.139.247t.22.177l8 4.25q.065.035.136.056q.071.022.144.029q.074.007.147-.001q.074-.007.145-.029q.07-.021.135-.056t.122-.082t.104-.105t.081-.122t.056-.136t.029-.144q.007-.074-.001-.147q-.007-.074-.029-.145q-.021-.07-.056-.135t-.082-.122t-.105-.104t-.122-.081l-8-4.25q-.107-.057-.227-.077q-.119-.021-.239-.002q5.258-.809 9.346 1.159q4.362 2.1 5.736 6.614q.043.142.028.291q-.014.148-.084.28t-.186.226q-.115.095-.258.139q-.046.014-.095.022q-4.985.831-9.063-1.06m8.435 2.515q.052-.047.111-.083t.124-.062t.132-.037q.069-.013.138-.013t.138.013t.132.037q.065.025.124.062q.059.036.111.083q2.995 2.723 2.995 4.805q0 3.5-3.5 3.5t-3.5-3.5q0-2.082 2.995-4.805");
}

</style>
