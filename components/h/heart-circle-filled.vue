<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGFu4GlbfV"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="b1hh0tx-e"/></mask></defs><circle mask="url(#SVGFu4GlbfV)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:heart-circle-filled" /></template>
<style>
.b1hh0tx-e {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M9.032 8.594C7.89 8.866 7 9.696 7 11.163c0 1.967 1.676 4.094 6 6.226c4.324-2.132 6-4.26 6-6.226c0-1.467-.889-2.297-2.032-2.57c-1.218-.29-2.523.103-3.167.965a1 1 0 0 1-1.602 0c-.644-.862-1.95-1.255-3.167-.964M13 7.543c-1.25-.98-2.965-1.245-4.432-.895C6.678 7.1 5 8.621 5 11.163c0 3.326 2.88 6.016 7.571 8.24a1 1 0 0 0 .857 0C18.12 17.18 21 14.49 21 11.164c0-2.542-1.678-4.064-3.568-4.515c-1.467-.35-3.183-.084-4.432.895");
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

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
