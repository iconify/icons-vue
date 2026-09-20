<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGU6jlCUnn" x1="16" x2="16" y1="2.72" y2="29.28" gradientTransform="translate(-.583 -.563)scale(1.0352)" gradientUnits="userSpaceOnUse"><stop offset="0" class="c_w9v9bli"/><stop offset="1" class="p--8tsehm"/></linearGradient></defs><path fill="url(#SVGU6jlCUnn)" class="plyc2bgxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-glyphs" /></template>
<style>
.c_w9v9bli {
  stop-color: var(--svg-color--00bf52, #00bf52);
}

.p--8tsehm {
  stop-color: var(--svg-color--00c67e, #00c67e);
}

.plyc2bgxl {
  d: path("M23.289 15.265a6.646 6.646 0 0 0 6.667-6.946V2.252H16.623v6.119c0 5.29 4.275 6.894 6.666 6.894m6.667 14.482V16.321H16.623c0 7.909 5.424 13.426 13.333 13.426m-14.524 0V2.252c-7.816 0-13.426 5.932-13.426 13.789c0 7.774 5.517 13.706 13.426 13.706");
}

</style>
