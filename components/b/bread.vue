<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ilQyRLb)" class="zah2urbgs"/><path fill="url(#iFPPREb)" class="qrumd9b_t"/><path fill="url(#irjeT6b)" class="toumfgwsq"/><g filter="url(#ibhkele)"><path stroke="url(#ixxKgIb)" class="efmf4rftk"/></g><path fill="url(#ibtdaOd)" class="zhfumov0r"/><path class="zbowe0brg"/><ellipse fill="url(#ifBIHbb)" transform="rotate(-17.946 7.653 13.563)" class="t2ta3wbfr"/><ellipse fill="url(#idZCcXb)" transform="rotate(-17.946 5.692 14.528)" class="rieq7lbug"/><ellipse fill="url(#iBxSvbc)" transform="rotate(-17.946 5.692 17.472)" class="voc01qx8m"/><ellipse fill="url(#idtORvA)" transform="rotate(-17.946 5.63 21.472)" class="nq68u94qb"/><ellipse fill="url(#ifcNEBb)" transform="rotate(-17.946 7.614 20.472)" class="tfdktqfvz"/><ellipse fill="url(#iTQzt5d)" transform="rotate(-17.946 7.614 16.472)" class="chkw6_4lc"/><ellipse fill="url(#iSDcoEc)" transform="rotate(-17.946 9.622 15.472)" class="ph73m6bps"/><ellipse fill="url(#iwBp4bb)" transform="rotate(-17.946 11.57 14.528)" class="n6xhac_4w"/><ellipse fill="url(#ihQPtbb)" transform="rotate(-17.946 11.5 18.528)" class="c6zm8fbxy"/><ellipse fill="url(#iiaQxfc)" transform="rotate(-17.946 9.57 19.528)" class="p2cav7_xw"/><ellipse fill="url(#iJV2gJd)" transform="rotate(-17.946 9.524 23.356)" class="xrne1g9vd"/><ellipse fill="url(#isJu91d)" transform="rotate(-17.946 11.5 22.341)" class="v57l59v3f"/><ellipse fill="url(#i65HDAd)" transform="rotate(-17.946 13.43 24.472)" class="mh11vlb3t"/><ellipse fill="url(#iwRLzEe)" transform="rotate(-17.946 13.43 21.417)" class="pqw8m3utv"/><ellipse fill="url(#irGiN8b)" transform="rotate(-17.946 13.465 17.57)" class="bl-xr8b5f"/><g filter="url(#ifYdwUd)"><path stroke="url(#iUVwVRd)" class="lc95_8mnn"/></g><defs><radialGradient id="ibtdaOd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.596 57.007 8.937)scale(20.965 19.3732)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="gsil-7bvo"/><stop offset="1" class="i6lz2qbme"/></radialGradient><radialGradient id="ifBIHbb" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 7.081 13.934)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="idZCcXb" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 5.12 14.899)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iBxSvbc" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 5.12 17.842)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="idtORvA" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 5.058 21.842)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="ifcNEBb" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 7.042 20.842)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iTQzt5d" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 7.042 16.842)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iSDcoEc" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 9.05 15.842)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iwBp4bb" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 10.999 14.899)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="ihQPtbb" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 10.929 18.899)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iiaQxfc" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 8.999 19.899)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iJV2gJd" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 8.952 23.727)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="isJu91d" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 10.929 22.712)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="i65HDAd" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 12.858 24.842)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iwRLzEe" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 12.858 21.787)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="irGiN8b" cx="0" cy="0" r="1" gradientTransform="matrix(.98016 -.2379 .158 .65098 12.893 17.941)" gradientUnits="userSpaceOnUse"><stop class="c0s60ab0j"/><stop offset="1" class="un2y4q4ca"/></radialGradient><radialGradient id="iUVwVRd" cx="0" cy="0" r="1" gradientTransform="rotate(98.319 .633 9.556)scale(6.00063 13.6225)" gradientUnits="userSpaceOnUse"><stop class="u3mjub5-s"/><stop offset="1" class="i1-a97ldz"/></radialGradient><linearGradient id="ilQyRLb" x1="22" x2="26.5" y1="16.375" y2="28" gradientUnits="userSpaceOnUse"><stop class="j82-lw01v"/><stop offset=".677" class="zts2ymbea"/><stop offset=".845" class="mklfr2bil"/></linearGradient><linearGradient id="iFPPREb" x1="13.75" x2="19.375" y1="3.005" y2="18.25" gradientUnits="userSpaceOnUse"><stop offset=".025" class="zwff1kb5f"/><stop offset=".102" class="ng3uuccku"/><stop offset=".644" class="qf7ot3bsa"/><stop offset=".754" class="gzqi5er7j"/><stop offset=".876" class="j9ilhybgg"/><stop offset="1" class="ol1cebcvq"/></linearGradient><linearGradient id="irjeT6b" x1="1.688" x2="14.625" y1="8.875" y2="30.067" gradientUnits="userSpaceOnUse"><stop class="icwbbzbna"/><stop offset=".483" class="s2hbp3sgm"/><stop offset="1" class="qlbpzy6bs"/></linearGradient><linearGradient id="ixxKgIb" x1="4.063" x2="15.781" y1="7.75" y2="29.844" gradientUnits="userSpaceOnUse"><stop class="qhgkvyblh"/><stop offset=".427" class="wrki96b2w"/><stop offset="1" class="qlbpzy6bs"/></linearGradient><filter id="ibhkele" width="13.765" height="20.999" x="4.485" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32476" stdDeviation=".1"/></filter><filter id="ifYdwUd" width="15.307" height="9.449" x="2.532" y="7.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32476" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bread" /></template>
<style>
.bl-xr8b5f {
  cx: 13.465px;
  cy: 17.571px;
  rx: 0.304px;
  ry: 0.457px;
}

.c0s60ab0j {
  stop-color: var(--svg-color--ac8761, #AC8761);
  stop-opacity: 0;
}

.c6zm8fbxy {
  cx: 11.5px;
  cy: 18.528px;
  rx: 0.304px;
  ry: 0.457px;
}

.chkw6_4lc {
  cx: 7.614px;
  cy: 16.472px;
  rx: 0.304px;
  ry: 0.457px;
}

.efmf4rftk {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m4.702 7.513l10.04 3.765a5.02 5.02 0 0 1 2.415 7.487L17 19v9.065");
}

.ft5dv1b6b {
  fill: none;
}

.gsil-7bvo {
  stop-color: var(--svg-color--caa177, #CAA177);
}

.gzqi5er7j {
  stop-color: var(--svg-color--ffbb6e, #FFBB6E);
}

.i1-a97ldz {
  stop-color: var(--svg-color--ffebcb, #FFEBCB);
  stop-opacity: 0;
}

.i6lz2qbme {
  stop-color: var(--svg-color--be977c, #BE977C);
}

.icwbbzbna {
  stop-color: var(--svg-color--df994e, #DF994E);
}

.j82-lw01v {
  stop-color: var(--svg-color--c3844a, #C3844A);
}

.j9ilhybgg {
  stop-color: var(--svg-color--e09f59, #E09F59);
}

.lc95_8mnn {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M2.672 8.281c.344-.453 1.182-.744 1.64-.61c.532.157 7.198 2.641 10.75 3.985c1.037.392 3.094 2.313 2.532 5.172");
}

.mh11vlb3t {
  cx: 13.43px;
  cy: 24.472px;
  rx: 0.304px;
  ry: 0.457px;
}

.mklfr2bil {
  stop-color: var(--svg-color--895461, #895461);
}

.n6xhac_4w {
  cx: 11.57px;
  cy: 14.528px;
  rx: 0.304px;
  ry: 0.457px;
}

.ng3uuccku {
  stop-color: var(--svg-color--ffc974, #FFC974);
}

.nq68u94qb {
  cx: 5.629px;
  cy: 21.472px;
  rx: 0.304px;
  ry: 0.457px;
}

.ol1cebcvq {
  stop-color: var(--svg-color--9c5c44, #9C5C44);
}

.p2cav7_xw {
  cx: 9.57px;
  cy: 19.528px;
  rx: 0.304px;
  ry: 0.457px;
}

.ph73m6bps {
  cx: 9.622px;
  cy: 15.472px;
  rx: 0.304px;
  ry: 0.457px;
}

.pqw8m3utv {
  cx: 13.43px;
  cy: 21.417px;
  rx: 0.304px;
  ry: 0.457px;
}

.qf7ot3bsa {
  stop-color: var(--svg-color--ffcb79, #FFCB79);
}

.qhgkvyblh {
  stop-color: var(--svg-color--df9a4f, #DF9A4F);
}

.qlbpzy6bs {
  stop-color: var(--svg-color--925440, #925440);
}

.qrumd9b_t {
  d: path("M14.59 3.262L3.202 7.556L17 19l10.98-3.8A3 3 0 0 0 30 12.364v-.904a5 5 0 0 0-3.239-4.679l-9.35-3.52a4 4 0 0 0-2.821 0");
}

.rieq7lbug {
  cx: 5.692px;
  cy: 14.528px;
  rx: 0.304px;
  ry: 0.457px;
}

.s2hbp3sgm {
  stop-color: var(--svg-color--e0994d, #E0994D);
}

.t2ta3wbfr {
  cx: 7.653px;
  cy: 13.563px;
  rx: 0.304px;
  ry: 0.457px;
}

.tfdktqfvz {
  cx: 7.614px;
  cy: 20.472px;
  rx: 0.304px;
  ry: 0.457px;
}

.toumfgwsq {
  d: path("M3 13.5v9.955a3 3 0 0 0 1.903 2.793l9.366 3.679A2 2 0 0 0 17 28.065V19l.157-.235a5.02 5.02 0 0 0-2.415-7.487L4.702 7.513A2 2 0 0 0 2 9.386v1.403a4 4 0 0 0 .672 2.219z");
}

.u3mjub5-s {
  stop-color: var(--svg-color--f2ce97, #F2CE97);
}

.un2y4q4ca {
  stop-color: var(--svg-color--956b54, #956B54);
}

.v57l59v3f {
  cx: 11.5px;
  cy: 22.341px;
  rx: 0.304px;
  ry: 0.457px;
}

.voc01qx8m {
  cx: 5.692px;
  cy: 17.472px;
  rx: 0.304px;
  ry: 0.457px;
}

.wrki96b2w {
  stop-color: var(--svg-color--e2994d, #E2994D);
}

.xrne1g9vd {
  cx: 9.524px;
  cy: 23.356px;
  rx: 0.304px;
  ry: 0.457px;
}

.zah2urbgs {
  d: path("M27.34 25.593L15 30V16.5L29 13v10.238a2.5 2.5 0 0 1-1.66 2.355");
}

.zbowe0brg {
  fill: var(--svg-color--c4c4c4, #C4C4C4);
  d: path("M8 13.566c0 .24-.138.434-.309.434s-.308-.194-.308-.434s.033-.421.203-.421s.414.182.414.421");
}

.zhfumov0r {
  d: path("M3.083 13.598v9.8c0 1.214.746 2.304 1.882 2.748l9.263 3.622c1.298.507 2.6-.445 2.6-1.832v-8.924l.155-.231a4.93 4.93 0 0 0 .834-2.742c0-2.06-1.183-3.904-3.121-4.628l-9.93-3.706c-1.293-.482-2.672.469-2.672 1.844v1.38c0 .778.23 1.538.664 2.185z");
}

.zts2ymbea {
  stop-color: var(--svg-color--bc7b46, #BC7B46);
}

.zwff1kb5f {
  stop-color: var(--svg-color--ffc173, #FFC173);
}

</style>
