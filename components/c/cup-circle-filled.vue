<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG6POIMcQZ"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="eun8dxeqc"/><path class="jxvp-qbrm"/></g></mask></defs><circle mask="url(#SVG6POIMcQZ)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cup-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.eun8dxeqc {
  fill-rule: evenodd;
  d: path("M18.5 7h-12a1 1 0 0 0-1 1c0 4.918 3.061 9 7 9s7-4.082 7-9a1 1 0 0 0-1-1m-6 8c-2.455 0-4.596-2.57-4.949-6h9.898c-.353 3.43-2.494 6-4.949 6");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.jxvp-qbrm {
  d: path("M7 17.5h11a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2m10.024-3.69l.552-1.923c.257.074.539.113.831.113c1.107 0 1.893-.543 1.893-1s-.786-1-1.893-1V8c2.088 0 3.893 1.248 3.893 3s-1.805 3-3.893 3c-.477 0-.945-.065-1.383-.19");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
