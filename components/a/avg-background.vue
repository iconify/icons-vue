<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGXGO2hcQt)" class="qzjv7jxan"/><path fill="url(#SVGAzDZrbrl)" class="v-j7_vb-l"/><path fill="url(#SVGiynTpcCF)" class="osc1ombis"/><path clip-rule="evenodd" class="nwe2tjuas"/><path class="vfq02mbug"/><path class="gzo_dus5i"/></g><defs><linearGradient id="SVGXGO2hcQt" x1="20" x2="4" y1="11.204" y2="11.204" gradientUnits="userSpaceOnUse"><stop class="sey7ayb3j"/><stop offset="1" class="cs9eo6b4e"/></linearGradient><linearGradient id="SVGAzDZrbrl" x1="4.729" x2="16.989" y1="9.992" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="t7_8n_b0w"/><stop offset="1" class="ym090cbhp"/></linearGradient><linearGradient id="SVGiynTpcCF" x1="4.833" x2="21.326" y1="13.338" y2="15.794" gradientUnits="userSpaceOnUse"><stop class="g-hyr5b_b"/><stop offset="1" class="ngyu11bwp"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avg-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cs9eo6b4e {
  stop-color: var(--svg-color--4e984d, #4e984d);
}

.ft5dv1b6b {
  fill: none;
}

.g-hyr5b_b {
  stop-color: var(--svg-color--a07b58, #a07b58);
}

.gzo_dus5i {
  fill: var(--svg-color--3c8655, #3c8655);
  d: path("M7.035 7.09c.1.155.23.29.375.4c-.57 1.87 1.34 5.38 2.05 6.375c.805 1.145 4.18 4.76 6.065 3.43c.69-.485.8-1.41.615-2.45l.435-.18c.295 1.45.1 2.62-.665 3.16c-1.485 1.045-4.55-.73-6.835-3.96c-1.835-2.59-2.62-5.335-2.095-6.86l.05.085zm7.645 3.315l-.23-.33c-2.13-3-4.92-4.745-6.5-4.14c.215.1.42.265.575.47c1.93-.48 4.8 2.625 5.545 3.67l.16.245z");
}

.ngyu11bwp {
  stop-color: var(--svg-color--b9966d, #b9966d);
}

.nwe2tjuas {
  fill: var(--svg-color--3c8655, #3c8655);
  fill-rule: evenodd;
  d: path("M11.76 18.785c0-.176-.05-.396-.16-.596s-.24-.32-.33-.364a.16.16 0 0 0-.08-.026l-.01.006c-.024.024-.08.11-.075.3c0 .184.05.4.165.6c.11.2.236.32.33.365c.04.024.07.024.075.024l.01-.005c.025-.024.08-.11.075-.3zm.15.544c.25-.224.24-.8-.02-1.29c-.264-.485-.68-.7-.934-.475c-.25.226-.24.805.02 1.29c.264.49.68.7.934.476M7.83 7.36c.2.09.365.09.47.05c.09-.034.15-.1.165-.224c.015-.125-.02-.315-.155-.52c-.14-.2-.33-.36-.525-.45c-.2-.085-.365-.09-.47-.05c-.09.035-.15.105-.16.225c-.02.13.015.315.15.52c.14.205.33.36.525.45m-.8-.27c.34.51.965.79 1.39.62c.43-.164.5-.71.165-1.22c-.34-.51-.96-.79-1.39-.624c-.43.165-.5.715-.16 1.225z");
}

.osc1ombis {
  d: path("M8.295 11.45a.29.29 0 0 1-.15-.3c.195-1.18 1.44-2.095 2.95-2.095c1.64 0 2.974 1.09 2.974 2.43c0 .1-.01.195-.02.29c-.02.11-.1.2-.214.23a7.57 7.57 0 0 1-5.54-.555");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qzjv7jxan {
  d: path("m7.48 11l-.33-.975c-.55.22-1.65.845-1.65 1.62c0 .975 1.98 4.535 4.615 4.535s3.95-.97 5.27-1.295S20 13.915 20 11.97c0-1.55-3.13-2.16-5.105-2.265l.82 1.295z");
}

.sey7ayb3j {
  stop-color: var(--svg-color--99c454, #99c454);
}

.t7_8n_b0w {
  stop-color: var(--svg-color--b8cf52, #b8cf52);
}

.v-j7_vb-l {
  d: path("M18.775 12.144c-.065.864-2.92 1.38-6.375 1.15c-3.455-.22-6.21-1.105-6.15-1.97c.065-.865 2.92-1.385 6.375-1.16c3.46.23 6.21 1.115 6.15 1.98");
}

.vfq02mbug {
  fill: var(--svg-color--3c8655, #3c8655);
  d: path("M14.4 9.054C12.88 7.16 8.43 2.904 5.61 5.09c-2.82 2.18.35 7.9 1.87 9.8a16 16 0 0 0 3.32 2.965c-.035.15-.035.335 0 .525a16.9 16.9 0 0 1-3.68-3.44C3.885 10.9 3.025 6.264 5.205 4.58c2.175-1.68 6.29.44 9.525 4.475l.5.65h-.34q-.271-.374-.49-.65m2.965 5.275c.575 1.745.62 3.45-.66 4.44c-1.285.995-3 .67-4.625-.155c.025.185.015.36-.035.5c1.965 1.015 3.815 1.215 4.99.3c1.26-.97 1.37-2.935.615-5.205z");
}

.ym090cbhp {
  stop-color: var(--svg-color--d7dd50, #d7dd50);
}

</style>
