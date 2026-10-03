<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGlXKITdib" x1="44.08" x2="22.89" y1="49.98" y2="20.89" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs><path class="tf-6btbdi"/><path fill="url(#SVGlXKITdib)" class="q4efucbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vercel" /></template>
<style>
.q4efucbmz {
  d: path("m22.01 14.09l8.38 14.9H13.63z");
}

.tf-6btbdi {
  fill: var(--svg-color--52525b, #52525b);
  d: path("M27.37 5.52h-9.3l-2.1 4.2H4.27v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
