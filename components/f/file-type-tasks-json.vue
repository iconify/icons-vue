<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.59 .53)scale(23.306)"><defs><clipPath id="SVGEalBS0ki"><path class="nccdubclb powerclip"/></clipPath></defs><path clip-path="url(#SVGEalBS0ki)" class="j-5r9o77h"/><path class="h_b0t_b7h"/><path class="xxd0hy91x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tasks-json" /></template>
<style>
.h_b0t_b7h {
  fill: var(--svg-color--gray, gray);
  d: path("M.33.73h.4v.05h-.4zm0 .2h.35v.05H.33zm0-.4h.61v.05h-.6z");
}

.j-5r9o77h {
  fill: var(--svg-color--gray, gray);
  d: path("M.48 1.12h-.2V.28H.4V.4h.48V.28H1v.36h.08V.28A.1.1 0 0 0 1 .2H.88V.16A.1.1 0 0 0 .8.08H.48A.1.1 0 0 0 .4.16V.2H.28A.1.1 0 0 0 .2.28v.84a.1.1 0 0 0 .08.08h.2zm0-.96H.8v.16H.48z");
}

.nccdubclb {
  fill: none;
  stroke-width: var(--svg-stroke-width--0-04px, 0.04px);
  d: path("M-4.8-4.92H6.1v11.1H-4.8zM.99.57v.08h.1V.57z");
}

.xxd0hy91x {
  fill: var(--svg-color--f5df19, #f5df19);
  stroke: var(--svg-color--fbc12d, #fbc12d);
  stroke-width: var(--svg-stroke-width--0-01px, 0.01px);
  d: path("M.64.92L.68.9L.7.87V.73L.73.68V.66L.77.64h.06v.05H.81L.77.7L.76.75v.1L.72.92L.7.94l.05.04l.02.1v.07l.01.03l.04.01h.01v.05H.76L.73 1.2L.7 1.17V1L.68.98L.64.97zm.6.05H1.2l-.02.04v.16l-.03.04l-.03.03h-.06V1.2h.05l.01-.04v-.07l.02-.1l.05-.04l-.04-.03l-.02-.05v-.1L1.1.7h-.04V.64h.06l.03.02l.01.02l.01.05V.8l.01.07l.02.03l.04.02z");
}

</style>
