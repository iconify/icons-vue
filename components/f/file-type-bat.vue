<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGy1pJOGBU" cx="22.74" cy="22.74" r="3.63" gradientTransform="rotate(-81.5 21.8 23.55)scale(1 1.071)" gradientUnits="userSpaceOnUse"><stop offset="0" class="u-g7kcrga"/><stop offset=".5" class="if4itl3ut"/><stop offset="1" class="a16vb7bpj"/></radialGradient><radialGradient id="SVG0EwDaceR" cx="11.34" cy="11.34" r="5.2" gradientTransform="rotate(-81.5 10.87 11.74)scale(1 1.071)" href="#SVGy1pJOGBU"/></defs><path class="egm_4pyhf"/><g class="ft5dv1b6b"><g class="z9i2y7bkf"><circle class="jzxsgulpx"/><circle class="l3e092whm"/></g><g class="k-rlgpaxz"><circle class="xl8ylw7qf"/><circle class="jbh9_khau"/></g><circle stroke="url(#SVGy1pJOGBU)" class="b0_obdc-p"/><circle stroke="url(#SVG0EwDaceR)" class="lf63rv2rb"/><g class="k-rlgpaxz"><circle class="c69l8rvju"/><circle class="vvpa_xwyj"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-bat" /></template>
<style>
.a16vb7bpj {
  stop-color: var(--svg-color--404f5c, #404f5c);
  stop-opacity: 0.84;
}

.b0_obdc-p {
  cx: 22.74px;
  cy: 22.74px;
  r: 2.85px;
  stroke-width: var(--svg-stroke-width--1-55px, 1.55px);
}

.c69l8rvju {
  cx: 22.74px;
  cy: 22.74px;
  r: 1.91px;
  stroke-width: var(--svg-stroke-width--0-32px, 0.32px);
}

.egm_4pyhf {
  fill: var(--svg-color--silver, silver);
  d: path("m24.81 27.32l2.4-2.41l1.21 2.41l-1.2 1.2zm-3.85.12h3.4l-.84 2.55h-1.7zm-2.8-2.63l2.4 2.4l-2.4 1.2l-1.2-1.2zm-.12-3.85v3.4l-2.55-.85v-1.7zm2.63-2.8l-2.41 2.4l-1.2-2.4l1.2-1.2zm3.84-.13h-3.4l.85-2.55h1.7zm2.8 2.63l-2.4-2.4l2.4-1.2l1.2 1.2zm.14 3.85v-3.4l2.55.85v1.7zM6.57 16.98l2.27 1.26l-1.47 1.57l-1.36-.76zm-2.18-3.15l1.33 2.23l-2.05.63l-.8-1.34zm-.3-3.8l.02 2.6l-2.09-.49l-.03-1.56zm1.6-3.47L4.44 8.84L2.87 7.37l.75-1.36zm3.15-2.18L6.6 5.72l-.63-2.05l1.34-.8zm3.81-.32l-2.6.05l.48-2.09l1.56-.03zm3.46 1.63l-2.28-1.26l1.47-1.56l1.36.75zm2.18 3.14l-1.34-2.22L19 5.98l.8 1.34zm.32 3.82l-.05-2.6l2.1.48l.02 1.56zm-1.63 3.46l1.26-2.27l1.57 1.46l-.76 1.36zm-3.14 2.18l2.23-1.34l.62 2.05l-1.33.8zm-3.81.32l2.6-.05l-.5 2.1l-1.55.02z");
}

.ft5dv1b6b {
  fill: none;
}

.if4itl3ut {
  stop-color: var(--svg-color--8e9e9e, #8e9e9e);
  stop-opacity: 0.74;
}

.jbh9_khau {
  cx: 11.34px;
  cy: 11.34px;
  r: 6.22px;
  stroke-width: var(--svg-stroke-width--1-04px, 1.04px);
}

.jzxsgulpx {
  cx: 22.74px;
  cy: 22.74px;
  r: 3.47px;
  stroke-width: var(--svg-stroke-width--3-14px, 3.14px);
}

.k-rlgpaxz {
  stroke: var(--svg-color--a9a9a9, #a9a9a9);
}

.l3e092whm {
  cx: 11.34px;
  cy: 11.34px;
  r: 5.16px;
  stroke-width: var(--svg-stroke-width--4-69px, 4.69px);
}

.lf63rv2rb {
  cx: 11.34px;
  cy: 11.34px;
  r: 4.02px;
  stroke-width: var(--svg-stroke-width--2-36px, 2.36px);
}

.u-g7kcrga {
  stop-color: var(--svg-color--bedcdc, #bedcdc);
}

.vvpa_xwyj {
  cx: 11.34px;
  cy: 11.34px;
  r: 2.87px;
  stroke-width: var(--svg-stroke-width--0-48px, 0.48px);
}

.xl8ylw7qf {
  cx: 22.74px;
  cy: 22.74px;
  r: 4.31px;
  stroke-width: var(--svg-stroke-width--0-72px, 0.72px);
}

.z9i2y7bkf {
  stroke: var(--svg-color--silver, silver);
}

</style>
