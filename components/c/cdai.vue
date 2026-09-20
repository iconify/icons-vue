<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGfWL5Tcwj)" class="fm6-vmb1x"/><path fill="url(#SVGUO4W2bVY)" clip-rule="evenodd" class="rt37f_bbp"/><defs><linearGradient id="SVGfWL5Tcwj" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="f9j1pub1a"/><stop offset="1" class="aeh1xlsmk"/></linearGradient><linearGradient id="SVGUO4W2bVY" x1="13.742" x2="13.742" y1="8.295" y2="15.177" gradientUnits="userSpaceOnUse"><stop class="wx6yv0b2d"/><stop offset="1" class="oy5o7-bdd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cdai" /></template>
<style>
.aeh1xlsmk {
  stop-color: var(--svg-color--9388fd, #9388fd);
}

.f9j1pub1a {
  stop-color: var(--svg-color--27d3a2, #27d3a2);
}

.fm6-vmb1x {
  d: path("M19.677 5.065A9.9 9.9 0 0 0 13.588 3c-5.114 0-9.264 4.03-9.264 9s4.15 9 9.264 9a9.43 9.43 0 0 0 6.089-2.202L18.67 17.58a7.86 7.86 0 0 1-5.083 1.832c-4.235 0-7.676-3.32-7.676-7.412s3.441-7.412 7.676-7.412c1.864 0 3.749.636 5.083 1.705z");
}

.ft5dv1b6b {
  fill: none;
}

.oy5o7-bdd {
  stop-color: var(--svg-color--5d6e7d, #5d6e7d);
}

.rt37f_bbp {
  fill-rule: evenodd;
  d: path("M13.588 8.295h-2.912v2.647H9.618v.53h1.058v1.058H9.618v.53h1.058v2.117h2.912a3.44 3.44 0 0 0 3.177-2.117h.794v-.53h-.62a3.5 3.5 0 0 0 .08-1.059h.54v-.53h-.62a3.44 3.44 0 0 0-3.35-2.646m2.806 4.235a2.9 2.9 0 0 0 .095-1.059h-5.283v1.059zm-5.188.53v1.588h2.382a2.91 2.91 0 0 0 2.594-1.588zm0-2.118h5.188a2.91 2.91 0 0 0-2.806-2.118h-2.382z");
}

.wx6yv0b2d {
  stop-color: var(--svg-color--304250, #304250);
}

</style>
