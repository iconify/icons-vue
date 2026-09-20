<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGhk1GpesM)" class="i02wq_bky"/><path fill="url(#SVGhk1GpesM)" clip-rule="evenodd" class="wb40365gc"/><defs><linearGradient id="SVGhk1GpesM" x1="20.382" x2="6.66" y1="3.528" y2="22.89" gradientUnits="userSpaceOnUse"><stop class="u1swwbwez"/><stop offset="1" class="iixe92buh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:four" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i02wq_bky {
  d: path("m9.6 12l2.4-.6v-3l-.6.3l-1.8 2.7z");
}

.iixe92buh {
  stop-color: var(--svg-color--3c554f, #3c554f);
}

.u1swwbwez {
  stop-color: var(--svg-color--92988a, #92988a);
}

.wb40365gc {
  fill-rule: evenodd;
  d: path("M3 5.646L21 3v16.41L3 21zm10.8 5.455V6.6h-2.4L7.2 12v1.8l4.8-.6v4.2l1.8-.6v-3.9l2.4-.6v-1.8z");
}

</style>
