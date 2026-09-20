<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedBxx0)" clip-rule="evenodd" class="zezwhcb2l"/><path fill="url(#tokenBrandedBxx1)" class="d_n2ms6om"/><path fill="url(#tokenBrandedBxx2)" class="wznoiyc8o"/><path fill="url(#tokenBrandedBxx3)" class="wk_hgzpfm"/><defs><linearGradient id="tokenBrandedBxx0" x1="21.999" x2="2.013" y1="11.821" y2="11.286" gradientUnits="userSpaceOnUse"><stop class="dpbuq29nd"/><stop offset="1" class="rc1tvr4hn"/></linearGradient><linearGradient id="tokenBrandedBxx1" x1="22" x2="2.013" y1="11.821" y2="11.286" gradientUnits="userSpaceOnUse"><stop class="dpbuq29nd"/><stop offset="1" class="rc1tvr4hn"/></linearGradient><linearGradient id="tokenBrandedBxx2" x1="22" x2="2.013" y1="11.821" y2="11.286" gradientUnits="userSpaceOnUse"><stop class="dpbuq29nd"/><stop offset="1" class="rc1tvr4hn"/></linearGradient><linearGradient id="tokenBrandedBxx3" x1="22" x2="2.013" y1="11.821" y2="11.286" gradientUnits="userSpaceOnUse"><stop class="dpbuq29nd"/><stop offset="1" class="rc1tvr4hn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bxx" /></template>
<style>
.d_n2ms6om {
  d: path("M7.714 8.667h1.924l4.743 6.666h-1.924z");
}

.dpbuq29nd {
  stop-color: var(--svg-color--59b5f6, #59B5F6);
}

.ft5dv1b6b {
  fill: none;
}

.rc1tvr4hn {
  stop-color: var(--svg-color--1648c7, #1648C7);
}

.wk_hgzpfm {
  d: path("M21.524 8.667H19.6l-4.743 6.666h1.924z");
}

.wznoiyc8o {
  d: path("M13.905 8.667h-1.924L7.24 15.333h1.923zm1.429 0h1.923L22 15.333h-1.924z");
}

.zezwhcb2l {
  fill-rule: evenodd;
  d: path("M2 8.667h3.195A1.833 1.833 0 0 1 7.028 10.5a1.267 1.267 0 0 1-1.266 1.267h-.053A1.533 1.533 0 0 1 7.238 13.3a2.033 2.033 0 0 1-2.033 2.033H2zm1.429.952h1.428a.952.952 0 0 1 0 1.905H3.43zm0 2.857h1.428a.952.952 0 1 1 0 1.905H3.43z");
}

</style>
