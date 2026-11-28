<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(1.09 .16)scale(.932)"><defs><clipPath id="SVGseksXbjI"><path class="yheihnbxw"/></clipPath></defs><g clip-path="url(#SVGseksXbjI)"><g transform="translate(2 2)"><rect fill="url(#SVGdgVwsblS)" class="iwecndb-j"/><rect filter="url(#SVGIgrzkcFw)" class="err34w4bf"/><rect filter="url(#SVGcWQYvekC)" class="la1t-8qad"/><rect fill="url(#SVG4UiP5nmy)" class="evgi_uonx"/><rect fill="url(#SVGZzxN0v1p)" class="kiti5abqw"/></g><defs><linearGradient id="SVGdgVwsblS" x1="13.57" x2="25.89" y1="0" y2="26.09" gradientUnits="userSpaceOnUse"><stop class="o19ptqc3p"/><stop offset="1" class="cequoob6b"/></linearGradient><linearGradient id="SVG4UiP5nmy" x1="9.3" x2="19.65" y1="7" y2="27.07" gradientUnits="userSpaceOnUse"><stop class="hn2esfblp"/><stop offset="1" class="o19ptqc3p"/></linearGradient><linearGradient id="SVGZzxN0v1p" x1="3.46" x2="9.18" y1="14" y2="27.56" gradientUnits="userSpaceOnUse"><stop class="lgwa88bup"/><stop offset="1" class="hn2esfblp"/></linearGradient><filter id="SVGIgrzkcFw" width="9.8" height="21.47" x="9.06" y="6.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur stdDeviation=".12"/></filter><filter id="SVGcWQYvekC" width="14" height="25.67" x="6.96" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur stdDeviation="1.17"/></filter></defs></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-powerbi" /></template>
<style>
.cequoob6b {
  stop-color: var(--svg-color--c87e0e, #c87e0e);
}

.err34w4bf {
  width: 9.33px;
  height: 21px;
  x: 9.3px;
  y: 7px;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  rx: 1.17px;
}

.evgi_uonx {
  width: 9.33px;
  height: 21px;
  x: 9.3px;
  y: 7px;
  rx: 1.17px;
}

.hn2esfblp {
  stop-color: var(--svg-color--f6d751, #f6d751);
}

.iwecndb-j {
  width: 9.33px;
  height: 28px;
  x: 15.13px;
  rx: 1.17px;
}

.kiti5abqw {
  width: 9.33px;
  height: 14px;
  x: 3.46px;
  y: 14px;
  rx: 1.17px;
}

.la1t-8qad {
  width: 9.33px;
  height: 21px;
  x: 9.3px;
  y: 7px;
  fill-opacity: var(--svg-fill-opacity--0-18, 0.18);
  rx: 1.17px;
}

.lgwa88bup {
  stop-color: var(--svg-color--f9e589, #f9e589);
}

.o19ptqc3p {
  stop-color: var(--svg-color--e6ad10, #e6ad10);
}

.yheihnbxw {
  d: path("M0 0h32v32H0z");
}

</style>
