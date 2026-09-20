<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGalVpBdLH"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="fq1jjqbbs"/><path class="sea5x9bwf"/></g></mask></defs><circle mask="url(#SVGalVpBdLH)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:eye-closed-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.fq1jjqbbs {
  d: path("M4.688 11.306a1 1 0 1 1 1.624-1.167c.304.423.773.827 1.38 1.177c1.293.746 3.085 1.184 5.012 1.184c1.928 0 3.72-.437 5.013-1.184c.607-.35 1.076-.754 1.38-1.177a1 1 0 1 1 1.624 1.167c-.48.669-1.164 1.257-2.004 1.742c-1.612.93-3.748 1.452-6.013 1.452s-4.4-.522-6.012-1.452c-.84-.485-1.524-1.073-2.004-1.742");
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

.sea5x9bwf {
  d: path("M14 14a1 1 0 1 0-2 0v2.5a1 1 0 1 0 2 0zm-5.47-.242a1 1 0 0 1 1.94.485l-.5 2a1 1 0 1 1-1.94-.485zm8.44 0a1 1 0 0 0-1.94.485l.5 2a1 1 0 1 0 1.94-.485zm2.555-2.465a1 1 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414-1.414zm-13.447.034a1 1 0 0 1 1.48 1.346l-1.818 2a1 1 0 1 1-1.48-1.346z");
}

</style>
