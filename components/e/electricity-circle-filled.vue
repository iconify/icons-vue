<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGLesRFdkf"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="xi3btdzxz"/></mask></defs><circle mask="url(#SVGLesRFdkf)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:electricity-circle-filled" /></template>
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

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.xi3btdzxz {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M18 11h-3.055l1.974-4.606A1 1 0 0 0 16 5h-5a1 1 0 0 0-.92.606l-3 7A1 1 0 0 0 8 14h1.734l-2.662 6.627c-.4.995.835 1.836 1.614 1.1l5.024-4.742l4.94-4.225c.706-.604.279-1.76-.65-1.76m-5.49.606A1 1 0 0 0 13.428 13h1.864l-2.92 2.498l-1.748 1.65l1.517-3.775A1 1 0 0 0 11.214 12H9.517l2.142-5h2.824z");
}

</style>
