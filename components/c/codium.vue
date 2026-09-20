<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":94};
const content = `<defs><radialGradient id="SVGw00Fqe9V" cx="0" cy="0" r="1" gradientTransform="rotate(180.8 22.11 31.318)scale(34.54826 50.39238)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGJN9BXvrA" cx="0" cy="0" r="1" gradientTransform="rotate(195.945 36.012 15.363)scale(19.21353 19.75271)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGXJxMT19X" cx="0" cy="0" r="1" gradientTransform="rotate(195.945 39.538 40.539)scale(19.21353 19.75271)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGlnoWp0aF" cx="0" cy="0" r="1" gradientTransform="rotate(203.552 50.906 36.129)scale(18.43736 27.3369)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVGf9vcncVD" cx="0" cy="0" r="1" gradientTransform="rotate(203.552 46.06 12.887)scale(18.43736 27.3369)" gradientUnits="userSpaceOnUse"><stop class="trt-7yvfu"/><stop offset=".067" class="zhql8_o0h"/><stop offset=".133" class="w0symgbtm"/><stop offset=".2" class="rabz67xrh"/><stop offset=".267" class="d5m3ylb7d"/><stop offset=".333" class="k8dyzbkww"/><stop offset=".4" class="w4rdmeouv"/><stop offset=".467" class="dkf2kbqmk"/><stop offset=".533" class="fgqc6yrld"/><stop offset=".6" class="nymsyzbpn"/><stop offset=".667" class="m7qmil68t"/><stop offset=".733" class="c7a5eqb3i"/><stop offset=".8" class="kcnmjrfdk"/><stop offset=".867" class="p7dtvc89w"/><stop offset=".933" class="n5f14sbtv"/><stop offset="1" class="hhuzirqnc"/></radialGradient><radialGradient id="SVG7h9vRcbs" cx="0" cy="0" r="1" gradientTransform="matrix(10.9966 0 0 54.245 84.453 62.46)" gradientUnits="userSpaceOnUse"><stop class="hhuzirqnc"/><stop offset=".32" class="z3kum0amo"/><stop offset=".903" class="trt-7yvfu"/></radialGradient></defs><path class="snrh8_b9m"/><path fill="url(#SVGw00Fqe9V)" class="mu2kd6bjd"/><path fill="url(#SVGJN9BXvrA)" class="c0lie21pm"/><path fill="url(#SVGXJxMT19X)" class="x1wuu7bgv"/><path class="t8zzuzbiq"/><path fill="url(#SVGlnoWp0aF)" class="j45d0fnfc"/><path fill="url(#SVGf9vcncVD)" class="vcjancbri"/><path class="gcjqazbwm"/><path class="gi3jqobpz"/><path class="r-ijr91no"/><path fill="url(#SVG7h9vRcbs)" class="kx7boxecq"/><path class="hnf5u3bzg"/><path class="m98vzbb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codium" /></template>
<style>
.c0lie21pm {
  d: path("M55.781 43.691a31.3 31.3 0 0 0-12.023-9.372c2.995-1.702 6.302-2.649 9.781-2.649c3.282 0 6.42.847 9.272 2.366c-2.788 2.076-5.207 5.431-7.035 9.655z");
}

.c7a5eqb3i {
  stop-color: var(--svg-color--13ceb9, #13ceb9);
}

.d5m3ylb7d {
  stop-color: var(--svg-color--565ef3, #565ef3);
}

.dkf2kbqmk {
  stop-color: var(--svg-color--3a8ddb, #3a8ddb);
}

.fgqc6yrld {
  stop-color: var(--svg-color--2f9fd1, #2f9fd1);
}

.gcjqazbwm {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M55.781 82.018a31.06 31.06 0 0 0 6.589-19.164a31.06 31.06 0 0 0-6.589-19.163c1.831-4.221 4.248-7.574 7.038-9.657c5.031 2.677 9.203 7.474 11.857 13.515c-.853 4.519-1.336 9.74-1.336 15.3s.489 10.778 1.336 15.298c-2.654 6.043-6.826 10.84-11.857 13.517c-2.79-2.078-5.207-5.43-7.038-9.657z");
}

.gi3jqobpz {
  fill: var(--svg-color--321bb2, #321bb2);
  d: path("M55.778 82.023c-2.293-5.291-3.659-11.939-3.659-19.166c0-7.224 1.371-13.873 3.659-19.164a31.05 31.05 0 0 1 6.592 19.164a31.05 31.05 0 0 1-6.592 19.166");
}

.hhuzirqnc {
  stop-color: var(--svg-color--05e5ad, #05e5ad);
}

.hnf5u3bzg {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M77.797 62.86c0-5.563-1.135-10.781-3.124-15.3c.882-4.703 2.159-8.644 3.702-11.427c5.03 5.455 8.396 15.387 8.396 26.727c0 11.337-3.366 21.271-8.396 26.726c-1.538-2.785-2.812-6.727-3.702-11.429c1.984-4.519 3.124-9.737 3.124-15.297");
}

.j45d0fnfc {
  d: path("M74.673 78.152c.882 4.702 2.159 8.646 3.699 11.429c-2.605 2.831-5.659 4.46-8.931 4.46c-2.347 0-4.584-.842-6.627-2.366c5.033-2.678 9.205-7.474 11.859-13.515z");
}

.k8dyzbkww {
  stop-color: var(--svg-color--4e6cec, #4e6cec);
}

.kcnmjrfdk {
  stop-color: var(--svg-color--0dd8b4, #0dd8b4);
}

.kx7boxecq {
  d: path("M78.372 36.131c1.565-2.831 3.396-4.461 5.361-4.461c5.743 0 10.397 13.965 10.397 31.187s-4.654 31.187-10.397 31.187c-1.96 0-3.796-1.632-5.361-4.461c5.031-5.46 8.397-15.38 8.397-26.726s-3.366-21.271-8.397-26.726");
}

.m7qmil68t {
  stop-color: var(--svg-color--1bc0c0, #1bc0c0);
}

.m98vzbb_j {
  fill: var(--svg-color--321bb2, #321bb2);
  d: path("M74.673 78.155c-.852-4.52-1.336-9.738-1.336-15.298c0-5.562.489-10.781 1.336-15.3c1.984 4.519 3.124 9.738 3.124 15.3c0 5.56-1.135 10.778-3.124 15.298");
}

.mu2kd6bjd {
  d: path("M31.187 31.67c4.479 0 8.726.947 12.574 2.649c-8.526 4.836-14.475 15.792-14.475 28.538c0 12.744 5.955 23.702 14.475 28.538a31 31 0 0 1-12.574 2.649C13.964 94.044 0 80.08 0 62.857S13.964 31.67 31.187 31.67");
}

.n5f14sbtv {
  stop-color: var(--svg-color--06e4ae, #06e4ae);
}

.nymsyzbpn {
  stop-color: var(--svg-color--25b1c8, #25b1c8);
}

.p7dtvc89w {
  stop-color: var(--svg-color--08dfb0, #08dfb0);
}

.r-ijr91no {
  fill: var(--svg-color--05e6ad, #05e6ad);
  d: path("M78.372 36.131c1.565-2.831 3.396-4.461 5.361-4.461c5.743 0 10.397 13.965 10.397 31.187s-4.654 31.187-10.397 31.187c-1.96 0-3.796-1.632-5.361-4.461c5.031-5.46 8.397-15.38 8.397-26.726s-3.366-21.271-8.397-26.726");
}

.rabz67xrh {
  stop-color: var(--svg-color--5c54f8, #5c54f8);
}

.snrh8_b9m {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M139.049 31.254c5.189 0 10.617 1.207 14.962 3.739v16.529c-4.103-2.895-8.327-4.342-12.911-4.342c-9.17 0-16.168 6.394-16.168 15.443c0 8.929 6.877 15.443 16.168 15.443c4.705 0 9.292-1.93 13.032-4.584v16.65c-4.826 2.653-10.136 3.861-15.325 3.861c-18.338 0-31.611-12.669-31.611-31.37c0-17.978 13.152-31.369 31.853-31.369m50.181 0c18.462 0 32.337 13.633 32.337 31.369s-13.875 31.37-32.337 31.37c-18.459 0-32.335-13.634-32.335-31.37s13.876-31.369 32.335-31.369m0 46.694c8.205 0 14.961-6.759 14.961-15.325s-6.756-15.322-14.961-15.322c-8.203 0-14.962 6.757-14.962 15.322c0 8.566 6.759 15.325 14.962 15.325M290.272 7.969v84.456h-17.497v-7.963c-4.1 6.033-11.461 9.41-19.303 9.41c-16.048 0-28.232-13.513-28.232-31.249c0-17.615 12.184-31.248 28.232-31.248c7.842 0 15.203 3.016 19.303 9.168V7.969Zm-32.217 70.097c8.569 0 15.325-6.877 15.325-15.443s-6.756-15.443-15.325-15.443c-8.565 0-15.321 6.878-15.321 15.443c0 8.566 6.756 15.443 15.321 15.443m40.384 14.359V32.821h17.615v59.604Zm64.6-59.604h17.615v59.604h-17.615v-7.6c-3.501 5.67-9.534 9.168-17.376 9.168c-13.513 0-21.836-9.41-21.836-24.372v-36.8h17.615v32.577c0 7.842 3.86 12.429 10.496 12.429c6.756 0 11.101-5.068 11.101-13.515Zm43.4 59.604h-17.615V32.821h17.615v7.482c3.137-5.431 8.928-9.049 16.771-9.049c8.084 0 14.238 3.86 17.497 10.375c3.739-6.273 10.495-10.375 19.182-10.375c13.633 0 21.355 9.289 21.355 23.769v37.402h-17.615v-33.3c0-7.361-3.377-11.824-9.531-11.824c-6.033 0-10.136 4.947-10.257 12.911v32.213h-17.615v-33.06c0-7.601-3.376-12.064-9.409-12.064c-6.275 0-10.378 5.066-10.378 13.271ZM502.09 8.802v19.072h-5.522v-2.546c-1.312 1.931-3.667 3.011-6.178 3.011c-5.135 0-9.033-4.325-9.033-10.001c0-5.635 3.898-9.998 9.033-9.998c2.511 0 4.866.965 6.178 2.933V8.802Zm-10.232 14.48c2.742 0 4.904-2.201 4.904-4.944c0-2.739-2.162-4.941-4.904-4.941s-4.904 2.202-4.904 4.941c0 2.743 2.162 4.944 4.904 4.944m14.042 4.592V8.802h5.638v19.072Zm2.82-21.311c-1.815 0-3.283-1.506-3.283-3.28c0-1.777 1.468-3.283 3.283-3.283S512 1.506 512 3.283c0 1.774-1.465 3.28-3.28 3.28M307.247 7.842c5.67 0 10.254 4.708 10.254 10.257s-4.584 10.254-10.254 10.254s-10.257-4.705-10.257-10.254s4.587-10.257 10.257-10.257");
}

.t8zzuzbiq {
  fill: var(--svg-color--7962fe, #7962fe);
  d: path("M29.283 62.857c0-12.746 5.955-23.702 14.475-28.538a31.36 31.36 0 0 1 12.023 9.372c-2.296 5.291-3.662 11.939-3.662 19.166c0 7.224 1.371 13.875 3.662 19.164a31.3 31.3 0 0 1-12.023 9.374c-8.525-4.836-14.475-15.794-14.475-28.538");
}

.trt-7yvfu {
  stop-color: var(--svg-color--6447ff, #6447ff);
}

.vcjancbri {
  d: path("M62.814 34.036c2.043-1.524 4.28-2.366 6.627-2.366c3.267 0 6.321 1.63 8.931 4.461c-1.535 2.782-2.812 6.724-3.699 11.426c-2.654-6.044-6.826-10.838-11.859-13.515z");
}

.w0symgbtm {
  stop-color: var(--svg-color--614dfc, #614dfc);
}

.w4rdmeouv {
  stop-color: var(--svg-color--447be4, #447be4);
}

.x1wuu7bgv {
  d: path("M55.776 82.023c1.828 4.224 4.247 7.571 7.035 9.655c-2.858 1.524-5.99 2.366-9.272 2.366c-3.485 0-6.791-.947-9.781-2.649a31.36 31.36 0 0 0 12.023-9.372z");
}

.z3kum0amo {
  stop-color: var(--svg-color--05e5ad, #05e5ad);
  stop-opacity: 0;
}

.zhql8_o0h {
  stop-color: var(--svg-color--6348fe, #6348fe);
}

</style>
