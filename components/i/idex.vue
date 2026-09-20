<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG4IV6QiwO)" clip-rule="evenodd" class="y5249tz5x"/><defs><linearGradient id="SVG4IV6QiwO" x1="6.034" x2="18.731" y1="21" y2="5.128" gradientUnits="userSpaceOnUse"><stop class="dfpk2nbcd"/><stop offset=".78" class="z5ro-b9uf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idex" /></template>
<style>
.dfpk2nbcd {
  stop-color: var(--svg-color--9722ad, #9722ad);
}

.ft5dv1b6b {
  fill: none;
}

.y5249tz5x {
  fill-rule: evenodd;
  d: path("M4.954 3h14.014L21 5.59l-4.976 6.462L21 18.467L18.994 21H4.954L3 18.467l4.944-6.415L3 5.59zm.052.894L17.863 20.35H5.109l-.978-1.273h9.586c.128 0 .205-.154.128-.257L3.624 5.623l1.388-1.736zm4.963 10.748l1.986 2.5H8.921a.465.465 0 0 1-.465-.513a.46.46 0 0 1 .098-.238zm5.689-3.08l-1.684-2.114l1.44-1.8c.25-.302.032-.79-.367-.79h-3.066l-.264-.387c-.129-.205.013-.257.257-.257h8.049l-4.371 5.349z");
}

.z5ro-b9uf {
  stop-color: var(--svg-color--592e9c, #592e9c);
}

</style>
