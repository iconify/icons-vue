<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGvdUiqbRl)" class="xmrvo-b5c"/><defs><linearGradient id="SVGvdUiqbRl" x1="7.251" x2="18.113" y1="5.262" y2="17.71" gradientUnits="userSpaceOnUse"><stop class="i4kbb-7zf"/><stop offset="1" class="w6k954b6m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dad" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i4kbb-7zf {
  stop-color: var(--svg-color--00edef, #00edef);
}

.w6k954b6m {
  stop-color: var(--svg-color--0094ff, #0094ff);
}

.xmrvo-b5c {
  d: path("M12.712 3H3.6v3.6h7.835c1.514.04 4.765 1.803 4.765 5.172c0 4.038-3.103 5.628-4.765 5.628H7.2V21h5.512c2.581 0 7.805-2.574 7.686-9.228C20.28 5.119 15.145 3 12.712 3M9 10.2h1.8a1.8 1.8 0 1 1 0 3.6H9zM3.6 12a1.8 1.8 0 0 1 1.8-1.8v3.6A1.8 1.8 0 0 1 3.6 12");
}

</style>
