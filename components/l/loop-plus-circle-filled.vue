<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGKpZoQRLj"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="a5r0_s7lj"/><path class="cgdb-gjlb"/><path class="do7vzsb6t"/></g></mask></defs><circle mask="url(#SVGKpZoQRLj)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:loop-plus-circle-filled" /></template>
<style>
.a5r0_s7lj {
  fill-rule: evenodd;
  d: path("M7.828 7.828a6 6 0 1 0 8.486 8.486a6 6 0 0 0-8.486-8.486M14.9 14.9a4 4 0 1 1-5.656-5.656A4 4 0 0 1 14.9 14.9");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.cgdb-gjlb {
  d: path("M14.9 17.728a1.5 1.5 0 1 1 2.12-2.121l3.536 3.535a1.5 1.5 0 1 1-2.121 2.121zm-4.693-4.564a1 1 0 0 1 0-2h4a1 1 0 1 1 0 2z");
}

.do7vzsb6t {
  d: path("M11.207 10.164a1 1 0 0 1 2 0v4a1 1 0 1 1-2 0z");
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

</style>
