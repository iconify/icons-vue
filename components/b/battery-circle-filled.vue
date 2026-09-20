<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGOMHuxdkb"><path class="k5-vjlrin"/><g transform="translate(3 3)" class="ivjvz2eii"><rect class="xwhj4xbwf"/><path class="yyulwlb7u"/><path clip-rule="evenodd" class="yhxyf4f2m"/></g></mask></defs><circle mask="url(#SVGOMHuxdkb)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:battery-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.xwhj4xbwf {
  width: 2px;
  height: 5px;
  x: 17px;
  y: 7.5px;
  rx: 0.5px;
}

.yhxyf4f2m {
  fill-rule: evenodd;
  d: path("M14 4.5H4a3 3 0 0 0-3 3v5a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-5a3 3 0 0 0-3-3m-11 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

.yyulwlb7u {
  d: path("M4 7.5h3v5H4zm3.5 0h3v5h-3zm3.5 0h3v5h-3z");
}

</style>
