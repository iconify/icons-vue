<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGHYvOBclV)" class="secckib8p"/><defs><linearGradient id="SVGHYvOBclV" x1="6.536" x2="15.8" y1="6.143" y2="19.209" gradientUnits="userSpaceOnUse"><stop class="fome5h43s"/><stop offset=".48" class="z1zmnjbaf"/><stop offset="1" class="vzkprab5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fevr" /></template>
<style>
.fome5h43s {
  stop-color: var(--svg-color--e752f5, #e752f5);
}

.ft5dv1b6b {
  fill: none;
}

.secckib8p {
  d: path("M12.36 4H3.667A.667.667 0 0 0 3 4.667v14.666a.667.667 0 0 0 .667.667H7v-5.333h2.547l1.053-4H7V8h4.307zm.18 6.667h2.294a1.332 1.332 0 1 0 0-2.667h-1.587L14.3 4h.387a5.333 5.333 0 0 1 3.013 9.733L21 20h-4.46l-2.813-5.333h-2.24z");
}

.vzkprab5v {
  stop-color: var(--svg-color--44019c, #44019c);
}

.z1zmnjbaf {
  stop-color: var(--svg-color--5c0ca9, #5c0ca9);
}

</style>
