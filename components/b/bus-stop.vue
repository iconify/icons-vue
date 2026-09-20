<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="z-mcnqb8k"/><path class="k_1nrvv6b"/><path class="m2-b9yi1p"/><path class="djmox0sbv"/><path class="c676xsboq"/><circle class="y9nw9x_3m"/><path class="y2z2-1o0r"/><path class="xynx6bb3e"/><path class="wzikjsb_j"/><path class="lhs89ubga"/><path class="k0so0oyav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bus-stop" /></template>
<style>
.c676xsboq {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M21 34H9l-1 1v1h14v-1zm-2-2h-8l-1 1v1h10v-1z");
}

.djmox0sbv {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M29 13v-3a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1v3z");
}

.k_1nrvv6b {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M15 19h3v2h-3zm0-6h3v2h-3z");
}

.k0so0oyav {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M13 2h4v4h-4zm7 8h7v2h-7z");
}

.lhs89ubga {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M24 21h3v3h-3z");
}

.m2-b9yi1p {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M29 24a1 1 0 0 1-1 1h-9a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1z");
}

.wzikjsb_j {
  fill: var(--svg-color--808285, #808285);
  d: path("M24 13h3v3h-3zm0 4h3v3h-3z");
}

.xynx6bb3e {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M20 17h3v3h-3zm0 4h3v3h-3z");
}

.y2z2-1o0r {
  fill: var(--svg-color--808285, #808285);
  d: path("M20 13h3v3h-3z");
}

.y9nw9x_3m {
  cx: 15px;
  cy: 4px;
  r: 4px;
  fill: var(--svg-color--be1931, #be1931);
}

.z-mcnqb8k {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M14 7h2v29h-2z");
}

</style>
