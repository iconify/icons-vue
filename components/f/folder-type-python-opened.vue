<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGOAXdgbWL" x1="-132.23" x2="-132.18" y1="235.872" y2="235.822" gradientTransform="matrix(189.38 0 0 -189.81 25054.681 44783.902)" gradientUnits="userSpaceOnUse"><stop offset="0" class="aw-t_bg-j"/><stop offset="1" class="z8bgr0bko"/></linearGradient><linearGradient id="SVG2td0AdDw" x1="-132.549" x2="-132.492" y1="236.178" y2="236.128" gradientTransform="matrix(189.38 0 0 -189.81 25120.681 44848.152)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h2odc0bvt"/><stop offset="1" class="jxpbwgawm"/></linearGradient></defs><path class="j5qncub6k"/><path fill="url(#SVGOAXdgbWL)" class="x9l708buf"/><path fill="url(#SVG2td0AdDw)" class="scwmvdb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-python-opened" /></template>
<style>
.aw-t_bg-j {
  stop-color: var(--svg-color--387eb8, #387eb8);
}

.h2odc0bvt {
  stop-color: var(--svg-color--ffe052, #ffe052);
}

.j5qncub6k {
  fill: var(--svg-color--84ce7c, #84ce7c);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.jxpbwgawm {
  stop-color: var(--svg-color--ffc331, #ffc331);
}

.scwmvdb5c {
  d: path("M21.061 31c5.071 0 4.75-2.214 4.75-2.214V26.5h-4.822v-.72h6.765S31 26.145 31 21s-2.866-4.968-2.866-4.968h-1.677v2.384a2.72 2.72 0 0 1-2.786 2.884h-4.832a2.586 2.586 0 0 0-2.7 2.627v4.408S15.734 31 21.03 31zm2.665-1.544a.872.872 0 1 1 .845-.894v.022a.87.87 0 0 1-.867.872z");
}

.x9l708buf {
  d: path("M20.918 11.009c-5.072 0-4.751 2.206-4.751 2.206v2.293h4.823v.719h-6.744S11 15.825 11 21s2.866 4.968 2.866 4.968h1.655v-2.412a2.72 2.72 0 0 1 2.786-2.884h4.83a2.583 2.583 0 0 0 2.694-2.626v-4.378S26.24 11 20.944 11Zm-2.666 1.536a.872.872 0 1 1-.845.894v-.014a.87.87 0 0 1 .867-.873Z");
}

.z8bgr0bko {
  stop-color: var(--svg-color--366994, #366994);
}

</style>
