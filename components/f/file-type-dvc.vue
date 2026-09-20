<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g clip-path="url(#SVGbZii27FA)" transform="matrix(.7 0 0 .7 2 .26)"><path class="tmypvi7zo"/><path class="si4nn9bnk"/><path class="ltayv5bbt"/><path class="e45a892zb"/></g><defs><clipPath id="SVGbZii27FA"><path class="i72psgb8a"/></clipPath></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dvc" /></template>
<style>
.e45a892zb {
  fill: var(--svg-color--13adc7, #13adc7);
  d: path("M0 29.1V10.54a.5.5 0 0 1 .15-.38a.4.4 0 0 1 .33-.16h6.54c2.68.2 4.68.98 6.52 2.9c1.84 1.91 2.58 4.09 2.82 6.9c.23 2.68-.86 5.02-2.7 6.95a9 9 0 0 1-6.64 2.89H.48a.4.4 0 0 1-.33-.16a.5.5 0 0 1-.15-.38m4.18-14.05v10.44h2.57q2.25 0 3.74-1.65a5.8 5.8 0 0 0 1.48-4.05a5.8 5.8 0 0 0-1.48-4.02a4.8 4.8 0 0 0-3.74-1.65H4.18z");
}

.i72psgb8a {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h40v40H0z");
}

.ltayv5bbt {
  fill: var(--svg-color--f46737, #f46737);
  d: path("M26.28 26.83c-1.9-1.91-2.78-4.23-2.78-6.96s.87-5.06 2.78-6.99S30.5 10 33.21 10q3.8 0 6.56 2.54q.42.38.03.77l-2.11 2.21q-.36.33-.68 0a5.3 5.3 0 0 0-3.66-1.4q-2.28 0-3.8 1.66a5.6 5.6 0 0 0-1.46 3.98c0 1.53.45 2.84 1.47 3.92s2.3 1.62 3.81 1.62q2.12 0 3.64-1.3q.38-.33.7.02l2.12 2.27q.36.36-.03.74a9 9 0 0 1-6.59 2.65a9.5 9.5 0 0 1-6.93-2.86z");
}

.si4nn9bnk {
  fill: var(--svg-color--71548f, #71548f);
  d: path("m26.96 20.3l-2.47 5.47a10.4 10.4 0 0 1-1.68-6.52l1.6-3.66q.11-.3.46-.3zm-11.63 5.6l-2.83-6.3l2.4-4.33q.36 0 .47.3l1.69 3.88l.03.27a9 9 0 0 1-1.77 6.16z");
}

.tmypvi7zo {
  fill: var(--svg-color--945dd6, #945dd6);
  d: path("m26.96 20.3l-6.5 14.37q-.16.3-.46.3h-.27q-.3 0-.45-.3L12.5 19.61l2.4-4.33q.36 0 .47.3l4.43 10.13h.17L24.4 15.6q.11-.3.46-.3z");
}

</style>
