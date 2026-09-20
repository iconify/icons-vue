<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGRpn8XbER"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="zj74v7g4a"/><path class="bb2tmt6kq"/><path clip-rule="evenodd" class="zi2_l-w0e"/></g></mask></defs><circle mask="url(#SVGRpn8XbER)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:lock-open-circle-filled" /></template>
<style>
.bb2tmt6kq {
  d: path("M11 11a1 1 0 1 1-2 0V7a4 4 0 1 1 8 0v.5a1 1 0 1 1-2 0V7a2 2 0 1 0-4 0z");
}

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

.zi2_l-w0e {
  fill-rule: evenodd;
  d: path("M11 16a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2.5 0a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.zj74v7g4a {
  fill-rule: evenodd;
  d: path("M16 10h-6a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-4a4 4 0 0 0-4-4m-8 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2z");
}

</style>
