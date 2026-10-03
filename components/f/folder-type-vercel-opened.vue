<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGlXKITdib" x1="44.08" x2="22.89" y1="49.98" y2="20.89" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs><path class="aswo0abpu"/><path fill="url(#SVGlXKITdib)" class="q4efucbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vercel-opened" /></template>
<style>
.aswo0abpu {
  fill: var(--svg-color--666, #666);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21zm0 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1v2.1zm-1.7 4H.5l3.8 12.8h25.2z");
}

.q4efucbmz {
  d: path("m22.01 14.09l8.38 14.9H13.63z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
