<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedBtsg0)" class="tdx1lo9_f"/><defs><linearGradient id="tokenBrandedBtsg0" x1="12" x2="12" y1="2" y2="22" gradientUnits="userSpaceOnUse"><stop class="bmty7wb2d"/><stop offset="1" class="fppkwnvlm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btsg" /></template>
<style>
.bmty7wb2d {
  stop-color: var(--svg-color--9f559b, #9F559B);
}

.fppkwnvlm {
  stop-color: var(--svg-color--f70762, #F70762);
}

.ft5dv1b6b {
  fill: none;
}

.tdx1lo9_f {
  d: path("M8.522 18.478V2H6.348v16.478c0 .265.221.478.495.478h1.183a.486.486 0 0 0 .496-.478m4.408-7.782c-.274 0-.495.243-.495.543v10.217c0 .3.221.544.495.544h1.183c.274 0 .496-.244.496-.544V11.24c0-.3-.222-.543-.496-.543zM9.887 12c-.274 0-.496.24-.496.54v8.486c0 .3.222.54.496.54h1.182c.274 0 .496-.24.496-.54V12.54c0-.3-.222-.539-.496-.539zm5.591.983c0-.305.222-.548.496-.548h1.182c.274 0 .496.243.496.548v7.165c0 .304-.222.548-.496.548h-1.182c-.274 0-.496-.244-.496-.548z");
}

</style>
