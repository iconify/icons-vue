<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGFmn9jbEc)" class="f9syocd2u"/><defs><linearGradient id="SVGFmn9jbEc" x1="20.394" x2="3.939" y1="4.123" y2="19.015" gradientUnits="userSpaceOnUse"><stop class="yacl3vbcn"/><stop offset=".464" class="f3prw0a_k"/><stop offset="1" class="u8qw5jg4g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eurs" /></template>
<style>
.f3prw0a_k {
  stop-color: var(--svg-color--2b7fef, #2b7fef);
}

.f9syocd2u {
  d: path("M18.437 18.29A8.97 8.97 0 0 0 21 12a8.99 8.99 0 0 0-3.445-7.082l-1.612.062c-2.375.271-4.472 1.647-5.516 3.643h8.885l-1.125 2.25H9.755l-.005.05c-.109.867-.097 1.334 0 2.143l.007.059h7.306l-1.126 2.25h-5.326c.925 1.334 2.481 2.227 4.253 2.53a28 28 0 0 0 3.573.385m-2.603 1.854A9 9 0 0 1 3 12a9 9 0 0 1 11.042-8.767a8.48 8.48 0 0 0-6.07 5.39H6.374l-1.125 2.25H7.5v.002c-.068.909-.06 1.398 0 2.25H6.375l-1.125 2.25h2.88c1.303 2.622 4.307 4.378 6.734 4.667q.516.061.97.102");
}

.ft5dv1b6b {
  fill: none;
}

.u8qw5jg4g {
  stop-color: var(--svg-color--15bcff, #15bcff);
}

.yacl3vbcn {
  stop-color: var(--svg-color--b030ec, #b030ec);
}

</style>
