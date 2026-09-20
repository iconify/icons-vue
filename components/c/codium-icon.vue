<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":170};
const content = `<defs><radialGradient id="SVG3jLyTd8N" cx="0" cy="0" r="1" gradientTransform="rotate(180.8 59.832 42.11)scale(93.95894 137.04928)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGN7znTdPE" cx="0" cy="0" r="1" gradientTransform="rotate(195.945 91.909 -1.284)scale(52.25395 53.72032)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVG7nN61bhF" cx="0" cy="0" r="1" gradientTransform="rotate(195.945 101.498 67.186)scale(52.25395 53.72032)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVG9ywN0dWE" cx="0" cy="0" r="1" gradientTransform="rotate(203.552 129.467 55.192)scale(50.14304 74.34663)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGBoHVMccf" cx="0" cy="0" r="1" gradientTransform="rotate(203.552 116.29 -8.016)scale(50.14304 74.34663)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGCOJglbGE" cx="0" cy="0" r="1" gradientTransform="matrix(29.90682 0 0 147.52703 229.683 83.74)" gradientUnits="userSpaceOnUse"><stop class="hhuzirqnc"/><stop offset=".32" class="z3kum0amo"/><stop offset=".903" class="trt-7yvfu"/></radialGradient></defs><path fill="url(#SVG3jLyTd8N)" class="yin0x6bld"/><path fill="url(#SVGN7znTdPE)" class="xh-d92bph"/><path fill="url(#SVG7nN61bhF)" class="hnuhhejfl"/><path class="y-lrxib5o"/><path fill="url(#SVG9ywN0dWE)" class="mxxtpnl1d"/><path fill="url(#SVGBoHVMccf)" class="tsflsbhll"/><path class="eomhivbei"/><path class="k-56bibyd"/><path class="ktw94g7ww"/><path fill="url(#SVGCOJglbGE)" class="v2ivbcefv"/><path class="nevod9yxf"/><path class="sp597bcrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codium-icon" /></template>
<style>
.c7a5eqb3i {
  stop-color: var(--svg-color--13ceb9, #13ceb9);
}

.d5m3ylb7d {
  stop-color: var(--svg-color--565ef3, #565ef3);
}

.dkf2kbqmk {
  stop-color: var(--svg-color--3a8ddb, #3a8ddb);
}

.eomhivbei {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M151.704 136.929c11.216-14.382 17.92-32.465 17.92-52.12c0-19.652-6.704-37.735-17.92-52.116c4.98-11.48 11.553-20.599 19.141-26.264c13.683 7.281 25.029 20.327 32.247 36.756c-2.32 12.29-3.633 26.49-3.633 41.611s1.33 29.312 3.633 41.605c-7.218 16.435-18.564 29.481-32.247 36.761c-7.588-5.651-14.161-14.767-19.141-26.263z");
}

.fgqc6yrld {
  stop-color: var(--svg-color--2f9fd1, #2f9fd1);
}

.hhuzirqnc {
  stop-color: var(--svg-color--05e5ad, #05e5ad);
}

.hnuhhejfl {
  d: path("M151.691 136.942c4.971 11.488 11.55 20.591 19.132 26.258c-7.772 4.145-16.29 6.435-25.216 6.435c-9.478 0-18.469-2.575-26.601-7.204c12.897-5.695 24.121-14.512 32.698-25.489z");
}

.k-56bibyd {
  fill: var(--svg-color--321bb2, #321bb2);
  d: path("M151.696 136.942c-6.236-14.389-9.951-32.47-9.951-52.124c0-19.647 3.729-37.73 9.951-52.12c11.224 14.39 17.928 32.473 17.928 52.12c0 19.654-6.704 37.735-17.928 52.124");
}

.k8dyzbkww {
  stop-color: var(--svg-color--4e6cec, #4e6cec);
}

.kcnmjrfdk {
  stop-color: var(--svg-color--0dd8b4, #0dd8b4);
}

.ktw94g7ww {
  fill: var(--svg-color--05e6ad, #05e6ad);
  d: path("M213.144 12.132C217.4 4.433 222.38 0 227.724 0C243.343 0 256 37.98 256 84.818c0 46.84-12.657 84.817-28.276 84.817c-5.331 0-10.324-4.438-14.58-12.132c13.682-14.85 22.837-41.828 22.837-72.685c0-30.855-9.155-57.85-22.837-72.686");
}

.m7qmil68t {
  stop-color: var(--svg-color--1bc0c0, #1bc0c0);
}

.mxxtpnl1d {
  d: path("M203.084 126.414c2.399 12.788 5.872 23.514 10.06 31.083c-7.085 7.7-15.391 12.13-24.289 12.13c-6.383 0-12.467-2.29-18.023-6.435c13.688-7.283 25.034-20.326 32.252-36.756z");
}

.n5f14sbtv {
  stop-color: var(--svg-color--06e4ae, #06e4ae);
}

.nevod9yxf {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M211.58 84.826c0-15.13-3.087-29.321-8.496-41.611c2.399-12.79 5.872-23.508 10.068-31.077c13.68 14.835 22.834 41.847 22.834 72.688c0 30.832-9.154 57.849-22.834 72.685c-4.183-7.574-7.648-18.295-10.068-31.083c5.396-12.29 8.496-26.481 8.496-41.602");
}

.nymsyzbpn {
  stop-color: var(--svg-color--25b1c8, #25b1c8);
}

.p7dtvc89w {
  stop-color: var(--svg-color--08dfb0, #08dfb0);
}

.rabz67xrh {
  stop-color: var(--svg-color--5c54f8, #5c54f8);
}

.sp597bcrz {
  fill: var(--svg-color--321bb2, #321bb2);
  d: path("M203.084 126.423c-2.317-12.293-3.634-26.484-3.634-41.605c0-15.127 1.33-29.321 3.634-41.611c5.396 12.29 8.496 26.484 8.496 41.611c0 15.121-3.087 29.312-8.496 41.605");
}

.trt-7yvfu {
  stop-color: var(--svg-color--6447ff, #6447ff);
}

.tsflsbhll {
  d: path("M170.832 6.435C176.388 2.29 182.472 0 188.855 0c8.885 0 17.191 4.433 24.289 12.132c-4.175 7.566-7.648 18.287-10.06 31.075c-7.218-16.438-18.564-29.476-32.252-36.756z");
}

.v2ivbcefv {
  d: path("M213.144 12.132C217.4 4.433 222.38 0 227.724 0C243.343 0 256 37.98 256 84.818c0 46.84-12.657 84.817-28.276 84.817c-5.331 0-10.324-4.438-14.58-12.132c13.682-14.85 22.837-41.828 22.837-72.685c0-30.855-9.155-57.85-22.837-72.686");
}

.w0symgbtm {
  stop-color: var(--svg-color--614dfc, #614dfc);
}

.w4rdmeouv {
  stop-color: var(--svg-color--447be4, #447be4);
}

.xh-d92bph {
  d: path("M151.704 32.693c-8.577-10.977-19.777-19.794-32.698-25.489C127.151 2.576 136.145 0 145.607 0c8.926 0 17.46 2.304 25.216 6.435c-7.582 5.646-14.161 14.77-19.132 26.258z");
}

.y-lrxib5o {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M79.639 84.818c0-34.665 16.196-64.461 39.367-77.614c12.897 5.695 24.121 14.512 32.698 25.489c-6.244 14.389-9.959 32.47-9.959 52.125c0 19.646 3.729 37.735 9.959 52.119a85.1 85.1 0 0 1-32.698 25.494c-23.185-13.153-39.367-42.954-39.367-77.613");
}

.yin0x6bld {
  d: path("M84.818 0c12.181 0 23.731 2.576 34.196 7.204c-23.187 13.153-39.367 42.949-39.367 77.614c0 34.659 16.196 64.46 39.367 77.613a84.4 84.4 0 0 1-34.196 7.204C37.977 169.635 0 131.658 0 84.818C0 37.98 37.977 0 84.818 0");
}

.z3kum0amo {
  stop-color: var(--svg-color--05e5ad, #05e5ad);
  stop-opacity: 0;
}

.zhql8_o0h {
  stop-color: var(--svg-color--6348fe, #6348fe);
}

</style>
