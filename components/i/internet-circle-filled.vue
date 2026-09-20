<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGxMn5herp"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="a90nci_vp"/><path clip-rule="evenodd" class="u7slk2b6h"/><path class="uvr9qxb8p"/></g></mask></defs><circle mask="url(#SVGxMn5herp)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:internet-circle-filled" /></template>
<style>
.a90nci_vp {
  fill-rule: evenodd;
  d: path("M4.25 13a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 0 0-17.5 0m16 0a7.25 7.25 0 1 1-14.5 0a7.25 7.25 0 0 1 14.5 0");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.u7slk2b6h {
  fill-rule: evenodd;
  d: path("M9.25 13c0 4.522 1.491 8.25 3.75 8.25s3.75-3.728 3.75-8.25S15.259 4.75 13 4.75S9.25 8.478 9.25 13m6 0c0 3.762-1.195 6.75-2.25 6.75s-2.25-2.988-2.25-6.75S11.945 6.25 13 6.25s2.25 2.988 2.25 6.75");
}

.uvr9qxb8p {
  d: path("m6.602 8.467l1.006-1.112q.15.136.325.267c1.271.952 3.3 1.54 5.515 1.54c1.891 0 3.653-.427 4.931-1.158q.463-.265.819-.57l.974 1.141q-.466.399-1.048.73c-1.516.868-3.534 1.356-5.676 1.356c-2.522 0-4.865-.678-6.415-1.839a6 6 0 0 1-.431-.355m0 9.082l1.006 1.112q.15-.136.325-.267c1.271-.952 3.3-1.54 5.515-1.54c1.891 0 3.653.427 4.931 1.158q.463.265.819.57l.974-1.141a7 7 0 0 0-1.048-.73c-1.516-.868-3.534-1.356-5.676-1.356c-2.522 0-4.865.678-6.415 1.839a6 6 0 0 0-.431.355M4.75 13.75v-1.5h16.5v1.5z");
}

</style>
