<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG5Aqv6vwR" x1="18.92" x2="26.55" y1="10.58" y2="9.6" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vkycrabwj"/><stop offset="1" class="rq18-yb9t"/></linearGradient><linearGradient id="SVGXYLGobRk" x1="11.46" x2="7.6" y1="13.46" y2="3.34" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset=".01" class="bmf-vqb0i"/><stop offset="1" class="lw719q8gl"/></linearGradient><linearGradient id="SVG5Gp2HeUN" x1="20.67" x2="27.15" y1="23.36" y2="13.54" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="bvjo_qbel"/><stop offset="1" class="qrb-49b8g"/></linearGradient><linearGradient id="SVGIMXiXp2h" x1="10.7" x2="17.69" y1="20.5" y2="14.45" href="#SVG5Gp2HeUN"/><linearGradient id="SVGQhapfdvD" x1="24.45" x2="3.9" y1="16.91" y2="23.83" href="#SVG5Gp2HeUN"/></defs><path fill="url(#SVG5Aqv6vwR)" class="b94cbhbnh"/><path fill="url(#SVGXYLGobRk)" class="yznrh4-uj"/><path fill="url(#SVG5Gp2HeUN)" class="o5c-gnycy"/><path fill="url(#SVGIMXiXp2h)" class="n7ix3wbah"/><path fill="url(#SVGQhapfdvD)" class="vasx4rbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-gridsome" /></template>
<style>
.b94cbhbnh {
  fill-rule: evenodd;
  d: path("M27.32 13.59A2.57 2.57 0 0 1 30 15.92c.5 6.53-5.36 13.83-13.76 14.06a2.43 2.43 0 0 1-2.54-2.38a2.45 2.45 0 0 1 2.37-2.52c5.58-.15 9.11-5 8.92-8.93a2.45 2.45 0 0 1 2.32-2.56Z");
}

.bmf-vqb0i {
  stop-color: var(--svg-color--168a81, #168a81);
}

.bvjo_qbel {
  stop-color: var(--svg-color--27a59b, #27a59b);
}

.lw719q8gl {
  stop-color: var(--svg-color--31a97f, #31a97f);
}

.n7ix3wbah {
  d: path("M13.51 16.09A2.5 2.5 0 1 1 16 18.61a2.5 2.5 0 0 1-2.49-2.52");
}

.o5c-gnycy {
  d: path("M21.22 16.09a2.51 2.51 0 0 1 2.52-2.51h3.67a2.51 2.51 0 1 1 0 5h-3.67a2.51 2.51 0 0 1-2.52-2.51Z");
}

.qrb-49b8g {
  stop-color: var(--svg-color--64d8a2, #64d8a2);
}

.rq18-yb9t {
  stop-color: var(--svg-color--1a8864, #1a8864);
}

.vasx4rbcq {
  fill-rule: evenodd;
  d: path("M18.44 4.35a2.44 2.44 0 0 1-2.33 2.55c-5.82.24-9.37 4.82-9.2 9.17a2.41 2.41 0 0 1-2.31 2.54A2.52 2.52 0 0 1 2 16.22A14 14 0 0 1 15.9 2a2.45 2.45 0 0 1 2.54 2.35");
}

.vkycrabwj {
  stop-color: var(--svg-color--1a7d75, #1a7d75);
}

.yznrh4-uj {
  fill-rule: evenodd;
  d: path("M4.47 13.45a2.45 2.45 0 0 1 2.44 2.45A9 9 0 0 0 16 25.1a2.43 2.43 0 0 1 2.5 2.38A2.45 2.45 0 0 1 16.1 30A13.91 13.91 0 0 1 2 15.9a2.47 2.47 0 0 1 2.47-2.45");
}

</style>
