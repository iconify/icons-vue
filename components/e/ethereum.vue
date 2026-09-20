<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i5thgwb7f"/><path class="e7x044bzp"/><path class="eazczkbqw"/><path class="pa1ihcb9y"/><path class="n8-gsvb8m"/><path class="vc3pl-2fy"/><path clip-rule="evenodd" class="bo960ilcn"/><path clip-rule="evenodd" class="gg4suglzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ethereum" /></template>
<style>
.bo960ilcn {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 15.43l-5.625-3.263L12 3l5.624 9.166zm-5.252-3.528l5.161-8.41v6.114zm-.077.229l5.238-2.327v5.364zm5.418-2.327v5.364l5.234-3.037zm0-.198l5.161 2.296l-5.161-8.41z");
}

.e7x044bzp {
  fill: var(--svg-color--cabcf8, #cabcf8);
  d: path("m12 3l-5.625 9.166L12 9.653z");
}

.eazczkbqw {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("M12 16.478V21l5.625-7.784z");
}

.ft5dv1b6b {
  fill: none;
}

.gg4suglzr {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 16.406l-5.625-3.195L12 21l5.624-7.79zm-4.995-2.633l4.904 2.79v4.005zm5.084 2.79v4.005l4.905-6.795z");
}

.i5thgwb7f {
  fill: var(--svg-color--8ffcf3, #8ffcf3);
  d: path("M12 3v6.651l5.625 2.516z");
}

.n8-gsvb8m {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("m12 15.43l5.625-3.263L12 9.652z");
}

.pa1ihcb9y {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("M12 21v-4.522l-5.625-3.262z");
}

.vc3pl-2fy {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("M6.375 12.167L12 15.43V9.652z");
}

</style>
