<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<defs><linearGradient id="SVGyxSw6z8F" x1="77.389%" x2="14.764%" y1="-5.286%" y2="120.915%"><stop offset="0%" class="d786-imda"/><stop offset="48%" class="pylvrxbdk"/><stop offset="100%" class="ug73ozgnz"/></linearGradient><linearGradient id="SVGlOlHzc0y" x1="100.371%" x2="16.71%" y1="-50.113%" y2="64.217%"><stop offset="0%" class="d786-imda"/><stop offset="26%" class="pylvrxbdk"/><stop offset="48%" class="ug73ozgnz"/><stop offset="76%" class="up4374dmx"/><stop offset="100%" class="vnmfwlljb"/></linearGradient><linearGradient id="SVGFPVJ3dsi" x1="7.177%" x2="96.901%" y1="104.165%" y2="11.678%"><stop offset="0%" class="ug73ozgnz"/><stop offset="48%" class="up4374dmx"/><stop offset="100%" class="fswu6ne0s"/></linearGradient></defs><path class="vx-4psbst"/><path fill="url(#SVGyxSw6z8F)" class="vwwmw7bpn"/><path fill="url(#SVGlOlHzc0y)" transform="rotate(-9.18 87.215 86.378)" class="z3pfw559v"/><path fill="url(#SVGFPVJ3dsi)" class="yv_m3ld-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:apostrophe" /></template>
<style>
.d786-imda {
  stop-color: var(--svg-color--cc9300, #cc9300);
}

.fswu6ne0s {
  stop-color: var(--svg-color--00c09a, #00c09a);
}

.pylvrxbdk {
  stop-color: var(--svg-color--ea433a, #ea433a);
}

.ug73ozgnz {
  stop-color: var(--svg-color--b327bf, #b327bf);
}

.up4374dmx {
  stop-color: var(--svg-color--66f, #66f);
}

.vnmfwlljb {
  stop-color: var(--svg-color--00bf9a, #00bf9a);
}

.vwwmw7bpn {
  d: path("M179.299 94.86c-20.539 0-37.188 16.65-37.188 37.188s16.65 37.189 37.188 37.189s37.188-16.65 37.188-37.189c0-20.538-16.65-37.188-37.188-37.188m0 11.983c13.92 0 25.205 11.285 25.205 25.205s-11.285 25.205-25.205 25.205s-25.205-11.285-25.205-25.205s11.285-25.205 25.205-25.205");
}

.vx-4psbst {
  d: path("M122.798 254.854c-33.177 5.447-46.052 3.466-59.422-.99A66.36 66.36 0 0 1 30.694 229.6l-1.485-1.486c-7.428-10.399-12.875-22.283-17.827-52.985L3.459 123.63c-5.447-33.672-3.962-46.547.99-59.917a73.24 73.24 0 0 1 23.77-33.178l1.98-1.485c10.399-7.428 22.283-12.875 52.49-17.827L133.196 3.3c33.178-5.447 46.052-3.466 59.422.99a66.36 66.36 0 0 1 32.683 24.265l1.485 1.98c7.428 10.4 12.875 22.284 17.827 52.985l7.923 51.004c5.447 33.673 3.961 46.547-.99 59.917a70.1 70.1 0 0 1-23.77 33.178l-1.98 1.485c-10.4 7.428-22.284 12.875-52.49 17.827z");
}

.yv_m3ld-l {
  d: path("m99.322 144.91l-23.77 67.345c-1.512 4.286 2.113 8.63 6.6 7.91l67.841-10.894c4.502-.723 6.579-6.01 3.773-9.603l-44.071-56.451c-2.913-3.731-8.798-2.77-10.373 1.693m7.66 14.304l31.098 39.833l-47.87 7.685z");
}

.z3pfw559v {
  d: path("M115.515 52.062h-56.6a6.016 6.016 0 0 0-6.016 6.016v56.6a6.016 6.016 0 0 0 6.016 6.016h56.6a6.016 6.016 0 0 0 6.016-6.016v-56.6a6.016 6.016 0 0 0-6.016-6.016m-6.017 12.032v44.567H64.93V64.094z");
}

</style>
