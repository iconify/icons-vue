<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lycioqbci"/><path class="m6yp35b3l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dweb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lycioqbci {
  fill: var(--svg-color--4d99f1, #4d99f1);
  d: path("M24 0H0v24h24z");
}

.m6yp35b3l {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.47 11.059c.156-1.318.58-2.273 1.323-3.294h.56a6.14 6.14 0 0 0-1.435 3.294zm3.902-5.177h-.843a8.2 8.2 0 0 1 3.53-1.388v.447a7.9 7.9 0 0 0-2.687.941m10.71 5.177c-.169-1.337-.489-2.297-1.289-3.294h.56c.743 1.02 1.021 1.976 1.176 3.294zm-3.454-5.177h.843a8.2 8.2 0 0 0-3.53-1.411v.447c.918.113 1.91.536 2.687.964M7.53 18.118a8.2 8.2 0 0 0 3.53 1.411v-.447a7.9 7.9 0 0 1-2.687-.964zm-1.736-1.883h.56a6.34 6.34 0 0 1-1.459-3.346h-.452c.156 1.318.607 2.325 1.35 3.346m9.835 1.883c-.776.428-1.77.847-2.687.964v.447c1.252-.145 2.541-.73 3.53-1.411zm2.019-1.883h.56a6.5 6.5 0 0 0 1.322-3.294h-.447a6.14 6.14 0 0 1-1.435 3.294M6.824 6.353h.94v.941h-.94zm9.411 0h.942v.941h-.942zM6.824 16.706h.94v.941h-.94zM4 11.529h.941v.942H4zm15.059 0H20v.942h-.941zM11.529 20v-.941h.942V20zm0-15.059V4h.942v.941zm4.706 11.765h.942v.941h-.942zm-3.708-7.53l.885.302l-1.939 5.345l-.885-.3zm-2.988.942L7.294 12l2.245 1.882l.579-.8L8.776 12l1.342-1.082zm4.922 0L16.706 12l-2.245 1.882l-.579-.8L15.224 12l-1.342-1.082z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
