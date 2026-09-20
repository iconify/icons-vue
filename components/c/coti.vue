<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGUNt78cUL)" class="noffwpyxe"/><path fill="url(#SVGTwKLJbLG)" class="gc63z2boj"/><path class="qkezs9boi"/><defs><linearGradient id="SVGUNt78cUL" x1="13.658" x2="12.366" y1="17.748" y2="6.215" gradientUnits="userSpaceOnUse"><stop offset=".1" class="up1ci3wji"/><stop offset=".5" class="tozbrd8sb"/><stop offset=".8" class="qevv1ubck"/></linearGradient><linearGradient id="SVGTwKLJbLG" x1="13.98" x2="12.267" y1="4.505" y2="19.79" gradientUnits="userSpaceOnUse"><stop offset=".1" class="up1ci3wji"/><stop offset=".5" class="tozbrd8sb"/><stop offset=".8" class="qevv1ubck"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coti" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gc63z2boj {
  d: path("M20.584 13.513c.287 0 .416-.129.416-.388v-6.62c0-.293-.13-.388-.416-.388c-3.206-.029-7.06 2.795-10.271 5.017v7.616c3.178-2.188 7.154-5.304 10.27-5.237");
}

.noffwpyxe {
  d: path("M3.416 10.52c-.287 0-.416.13-.416.389v6.62c0 .287.13.383.416.383c3.178.033 7.06-2.796 10.271-5.012V5.25c-3.178 2.188-7.155 5.304-10.27 5.27");
}

.qevv1ubck {
  stop-color: var(--svg-color--2bbfdf, #2bbfdf);
}

.qkezs9boi {
  fill: var(--svg-color--194aad, #194aad);
  d: path("M13.687 12.832v-4q-1.707 1.125-3.374 2.306v4.05c1.18-.77 2.306-1.591 3.374-2.362z");
}

.tozbrd8sb {
  stop-color: var(--svg-color--248fcb, #248fcb);
}

.up1ci3wji {
  stop-color: var(--svg-color--194aad, #194aad);
}

</style>
