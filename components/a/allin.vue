<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG0d9Y6cxz)" clip-rule="evenodd" class="w0m4htbjl"/><path class="zppdh1_8t"/><defs><linearGradient id="SVG0d9Y6cxz" x1="5.044" x2="19.36" y1="15.937" y2="15.937" gradientUnits="userSpaceOnUse"><stop class="zth7k7bex"/><stop offset=".69" class="hqp-w58rr"/><stop offset="1" class="o2kkjgxkq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:allin" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hqp-w58rr {
  stop-color: var(--svg-color--e2fafc, #e2fafc);
}

.o2kkjgxkq {
  stop-color: var(--svg-color--7aebef, #7aebef);
}

.w0m4htbjl {
  fill-rule: evenodd;
  d: path("M3 19.875h4.45l.652-2.25h5.546l.652 2.25h4.45l-5.372-15.75H8.372zm9.562-5.625l-1.687-5.676l-1.688 5.676z");
}

.zppdh1_8t {
  fill: var(--svg-color--77ebef, #77ebef);
  d: path("M17.063 4.125H21v15.75h-3.937z");
}

.zth7k7bex {
  stop-color: var(--svg-color--fdfeff, #fdfeff);
}

</style>
