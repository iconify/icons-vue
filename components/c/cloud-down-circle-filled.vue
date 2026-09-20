<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGA7vNQcod"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="pmkzvubfa"/><path class="egb1hfh1g"/><path class="sqw2zmb3y"/><path class="w8llo8bvc"/></g></mask></defs><circle mask="url(#SVGA7vNQcod)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cloud-down-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.egb1hfh1g {
  d: path("M12.5 13a1 1 0 1 1 2 0v7.5a1 1 0 1 1-2 0z");
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

.pmkzvubfa {
  fill-rule: evenodd;
  d: path("M14 6h-1a4 4 0 0 0-3.874 3H9a4 4 0 1 0 0 8h8a4 4 0 0 0 .899-7.899A4 4 0 0 0 14 6m-3.324 5l.387-1.501A2 2 0 0 1 13 8h1c.937 0 1.743.65 1.95 1.549l.28 1.221l1.221.28A2.002 2.002 0 0 1 17 15H9a2 2 0 1 1 0-4z");
}

.sqw2zmb3y {
  d: path("M15.375 17.72a1 1 0 1 1 1.25 1.56l-2.5 2a1 1 0 0 1-1.25-1.56z");
}

.w8llo8bvc {
  d: path("M10.375 19.28a1 1 0 1 1 1.25-1.56l2.5 2a1 1 0 0 1-1.25 1.56z");
}

</style>
