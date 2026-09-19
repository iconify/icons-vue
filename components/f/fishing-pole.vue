<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYHPZTd)"><path fill="url(#i5cu3kb)" class="ii-87ggrs"/><path fill="url(#iEk1M8c)" class="ii-87ggrs"/></g><path fill="url(#idwu4xc)" class="i6xlaub0x"/><path fill="url(#iBpCTVd)" class="i6xlaub0x"/><path class="pgvlt2m-w"/><path fill="url(#iSoIU5c)" class="rhb33xbwr"/><path fill="url(#ishXfyd)" class="rhb33xbwr"/><g filter="url(#ic9qJGe)"><path clip-rule="evenodd" class="rl9c19eez"/></g><path fill="url(#iyFqYle)" clip-rule="evenodd" class="j9jetbckr"/><path fill="url(#iaOfhpO)" clip-rule="evenodd" class="j9jetbckr"/><path fill="url(#iirfk6s)" clip-rule="evenodd" class="j9jetbckr"/><g filter="url(#ifvun9c)"><rect class="q1-5mcpxi"/><rect fill="url(#ios3JOb)" class="xt3m_ac0b"/></g><g filter="url(#iE9Fnne)"><path class="sqriuff8s"/></g><g filter="url(#indBkGc)"><rect class="ojtjzxb4f"/></g><rect fill="url(#iBfU3oc)" class="lrt9t0bkr"/><rect fill="url(#iwzqZpG)" class="lrt9t0bkr"/><g filter="url(#iaHu30D)"><path stroke="url(#iz3CNHd)" class="gl7eveblb"/><path stroke="url(#iw1Jf1c)" class="gl7eveblb"/></g><g filter="url(#iOPtrle)"><circle class="qpqu-ib4a"/></g><circle fill="url(#iBqqNrb)" class="sm6pc1b0i"/><circle fill="url(#iVWSZze)" transform="rotate(90 23.543 20.477)" class="oan0_v53z"/><circle fill="url(#iiEMUFe)" class="d-uc8hbkh"/><circle fill="url(#iQNLONW)" transform="rotate(90 19.512 20.477)" class="sivyq3brk"/><defs><radialGradient id="i5cu3kb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15944 11.37356 -6.346 -.64692 13.182 20.38)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="ifpsiab7h"/><stop offset="1" class="anzbwbbxu"/></radialGradient><radialGradient id="iEk1M8c" cx="0" cy="0" r="1" gradientTransform="rotate(-162.239 9.47 13.145)scale(3.71039 4.64964)" gradientUnits="userSpaceOnUse"><stop class="uveic7bxw"/><stop offset="1" class="ou7emdblc"/></radialGradient><radialGradient id="idwu4xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.49541 6.83835 0 13.19 20.933)" gradientUnits="userSpaceOnUse"><stop class="i0bnrk_sk"/><stop offset="1" class="e5nw9dbep"/></radialGradient><radialGradient id="iBpCTVd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6316 -3.80958 4.26552 -6.3056 12.52 19.497)" gradientUnits="userSpaceOnUse"><stop offset=".697" class="x5uejwblh"/><stop offset="1" class="azb7gac4x"/></radialGradient><radialGradient id="ishXfyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.9324 -1.64523 0 11.004 7.958)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="g3ahygm1n"/><stop offset="1" class="piw9bobac"/></radialGradient><radialGradient id="iaOfhpO" cx="0" cy="0" r="1" gradientTransform="matrix(1.26819 -1.82211 2.63214 1.83197 10.614 8.712)" gradientUnits="userSpaceOnUse"><stop class="cbpenrnst"/><stop offset="1" class="zx9klzbvm"/></radialGradient><radialGradient id="iirfk6s" cx="0" cy="0" r="1" gradientTransform="rotate(117.316 5.104 18.233)scale(2.98595 1.62031)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="cfqs2s-vu"/><stop offset="1" class="k1gyqelks"/></radialGradient><radialGradient id="iwzqZpG" cx="0" cy="0" r="1" gradientTransform="matrix(-.911 0 0 -.76096 12.037 13.176)" gradientUnits="userSpaceOnUse"><stop class="r-4w9n6_c"/><stop offset="1" class="gk4bhrb7q"/></radialGradient><radialGradient id="iBqqNrb" cx="0" cy="0" r="1" gradientTransform="matrix(.86003 -.61223 .62776 .88186 21.08 18.843)" gradientUnits="userSpaceOnUse"><stop class="uwl_seblg"/><stop offset="1" class="ez265xb6q"/></radialGradient><radialGradient id="iVWSZze" cx="0" cy="0" r="1" gradientTransform="matrix(-.58307 -.80174 .82207 -.59786 24.024 20.84)" gradientUnits="userSpaceOnUse"><stop class="uwl_seblg"/><stop offset="1" class="ez265xb6q"/></radialGradient><radialGradient id="iiEMUFe" cx="0" cy="0" r="1" gradientTransform="matrix(.86003 -.61223 .62776 .88186 21.08 22.875)" gradientUnits="userSpaceOnUse"><stop class="uwl_seblg"/><stop offset="1" class="ez265xb6q"/></radialGradient><radialGradient id="iQNLONW" cx="0" cy="0" r="1" gradientTransform="matrix(-.55393 -.8163 .83701 -.56798 19.992 20.861)" gradientUnits="userSpaceOnUse"><stop class="uwl_seblg"/><stop offset="1" class="ez265xb6q"/></radialGradient><filter id="iYHPZTd" width="9.246" height="15.674" x="6.065" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.517647 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2881"/></filter><filter id="ic9qJGe" width="17.081" height="29.003" x="9.603" y="1.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.290196 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2881"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.247059 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2881" result="effect2_innerShadow_18_2881"/></filter><filter id="ifvun9c" width="2.234" height="1.234" x="11.004" y="17.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2881"/></filter><filter id="iE9Fnne" width="3.716" height="3.286" x="10.722" y="26.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2881" stdDeviation=".2"/></filter><filter id="indBkGc" width="3.918" height="1.7" x="8.743" y="12.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.576471 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2881"/></filter><filter id="iaHu30D" width="15.886" height="27.565" x="10.159" y="1.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2881" stdDeviation=".325"/></filter><filter id="iOPtrle" width="7.674" height="7.674" x="17.56" y="16.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.639216 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2881"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".34" dy="-.34"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.505882 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2881" result="effect2_innerShadow_18_2881"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.35" dy=".35"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.921569 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_2881" result="effect3_innerShadow_18_2881"/></filter><linearGradient id="iSoIU5c" x1="9.885" x2="10.67" y1="12.044" y2="12.044" gradientUnits="userSpaceOnUse"><stop class="x427r5b4x"/><stop offset="1" class="ktn6l_ben"/></linearGradient><linearGradient id="iyFqYle" x1="24.331" x2="24.331" y1="29.837" y2="27.808" gradientUnits="userSpaceOnUse"><stop class="x4nk_3bph"/><stop offset="1" class="rdm4mebmf"/></linearGradient><linearGradient id="ios3JOb" x1="11.996" x2="11.996" y1="18" y2="18.406" gradientUnits="userSpaceOnUse"><stop class="s-o9m2c2v"/><stop offset="1" class="xffoocb-d"/></linearGradient><linearGradient id="iBfU3oc" x1="8.743" x2="9.393" y1="13.618" y2="13.618" gradientUnits="userSpaceOnUse"><stop class="ln3ocac2q"/><stop offset="1" class="n094q8bhg"/></linearGradient><linearGradient id="iz3CNHd" x1="24.486" x2="24.311" y1="27.021" y2="2.981" gradientUnits="userSpaceOnUse"><stop class="gst11s1pm"/><stop offset="1" class="i-t-pic6y"/></linearGradient><linearGradient id="iw1Jf1c" x1="11.309" x2="18.889" y1="6.555" y2="3.406" gradientUnits="userSpaceOnUse"><stop class="is1qf1cjl"/><stop offset="1" class="wt0nsnbyb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fishing-pole" /></template>
<style>
.anzbwbbxu {
  stop-color: var(--svg-color--3c9fff, #3C9FFF);
}

.azb7gac4x {
  stop-color: var(--svg-color--96d1d7, #96D1D7);
}

.cbpenrnst {
  stop-color: var(--svg-color--623a4d, #623A4D);
}

.cfqs2s-vu {
  stop-color: var(--svg-color--5e2d40, #5E2D40);
}

.d-uc8hbkh {
  cx: 21.527px;
  cy: 22.492px;
  r: 0.648px;
}

.e5nw9dbep {
  stop-color: var(--svg-color--66d0f0, #66D0F0);
}

.ez265xb6q {
  stop-color: var(--svg-color--7b7184, #7B7184);
}

.ft5dv1b6b {
  fill: none;
}

.g3ahygm1n {
  stop-color: var(--svg-color--ac9bbd, #AC9BBD);
}

.gk4bhrb7q {
  stop-color: var(--svg-color--51bfff, #51BFFF);
  stop-opacity: 0;
}

.gl7eveblb {
  stroke-linecap: round;
  d: path("M11.309 6.788c.544-1.263 2.598-4.053 6.413-3.79c5.073.35 7.172 4.397 7.172 7.289v17.958");
}

.gst11s1pm {
  stop-color: var(--svg-color--8f6367, #8F6367);
}

.i-t-pic6y {
  stop-color: var(--svg-color--906864, #906864);
}

.i0bnrk_sk {
  stop-color: var(--svg-color--7bfcff, #7BFCFF);
}

.i6xlaub0x {
  d: path("M6.146 18.615a9 9 0 0 1 .472-1.944c.575-1.568 2.144-2.599 3.82-2.566c1.614 0 3.138.707 3.82 2.566c.218.596.381 1.25.472 1.944c-.531 2.116-2.252 3.666-4.292 3.666s-3.761-1.55-4.292-3.666");
}

.ifpsiab7h {
  stop-color: var(--svg-color--6ce8ff, #6CE8FF);
}

.ii-87ggrs {
  d: path("M6.618 16.671c-1.006 2.745-.841 6.742 2.206 10.012a.5.5 0 0 1 .14.348a.51.51 0 0 1-.365.485c-.376.115-.94.302-1.186.457c-.348.222-.932.75-1.034 1.556c-.018.137.096.25.234.25h1.615a3 3 0 0 0 1.684-.517l.301-.205a.4.4 0 0 1 .45 0l.301.205a3 3 0 0 0 1.684.517h1.615c.138 0 .252-.113.234-.25c-.103-.806-.686-1.334-1.035-1.556c-.245-.155-.81-.342-1.186-.457a.51.51 0 0 1-.364-.485c0-.13.051-.254.14-.348c3.047-3.27 3.212-7.267 2.206-10.012c-.682-1.859-2.206-2.566-3.82-2.566c-1.676-.033-3.245.998-3.82 2.566");
}

.is1qf1cjl {
  stop-color: var(--svg-color--7f5159, #7F5159);
}

.j9jetbckr {
  fill-rule: evenodd;
  d: path("M17.394 4.884c-3.033 0-4.649 2.043-5.13 3.038a1.4 1.4 0 0 1-2.52-1.22a8.48 8.48 0 0 1 7.65-4.618c2.716 0 4.858 1.222 6.3 2.788c1.406 1.528 2.24 3.49 2.24 5.16v18.406a1.4 1.4 0 1 1-2.8 0V10.03c0-.83-.47-2.142-1.5-3.263c-.996-1.082-2.424-1.884-4.24-1.884");
}

.k1gyqelks {
  stop-color: var(--svg-color--5e2d40, #5E2D40);
  stop-opacity: 0;
}

.ktn6l_ben {
  stop-color: var(--svg-color--c5b8ba, #C5B8BA);
  stop-opacity: 0;
}

.ln3ocac2q {
  stop-color: var(--svg-color--408dd8, #408DD8);
}

.lrt9t0bkr {
  width: 3.518px;
  height: 1.3px;
  x: 8.743px;
  y: 12.967px;
  rx: 0.65px;
}

.n094q8bhg {
  stop-color: var(--svg-color--408dd8, #408DD8);
  stop-opacity: 0;
}

.oan0_v53z {
  cx: 23.543px;
  cy: 20.477px;
  r: 0.648px;
}

.ojtjzxb4f {
  width: 3.518px;
  height: 1.3px;
  x: 8.743px;
  y: 12.967px;
  fill: var(--svg-color--43a5e3, #43A5E3);
  rx: 0.65px;
}

.ou7emdblc {
  stop-color: var(--svg-color--72dbff, #72DBFF);
  stop-opacity: 0;
}

.pgvlt2m-w {
  fill: var(--svg-color--e2deec, #E2DEEC);
  d: path("M9.988 8.141h1.016V13.5H9.988z");
}

.piw9bobac {
  stop-color: var(--svg-color--ac9bbd, #AC9BBD);
  stop-opacity: 0;
}

.q1-5mcpxi {
  width: 1.984px;
  height: 0.984px;
  x: 11.004px;
  y: 18px;
  fill: var(--svg-color--625357, #625357);
  rx: 0.492px;
}

.qpqu-ib4a {
  cx: 21.402px;
  cy: 20.477px;
  r: 3.492px;
  fill: var(--svg-color--cbc1d4, #CBC1D4);
}

.r-4w9n6_c {
  stop-color: var(--svg-color--51bfff, #51BFFF);
}

.rdm4mebmf {
  stop-color: var(--svg-color--74335f, #74335F);
  stop-opacity: 0;
}

.rhb33xbwr {
  d: path("M9.988 8.141h1.016V13.5H9.988z");
}

.rl9c19eez {
  fill: var(--svg-color--784c45, #784C45);
  fill-rule: evenodd;
  d: path("M17.394 4.884c-3.033 0-4.649 2.043-5.13 3.038a1.4 1.4 0 0 1-2.52-1.22a8.48 8.48 0 0 1 7.65-4.618c2.716 0 4.858 1.222 6.3 2.788c1.406 1.528 2.24 3.49 2.24 5.16v18.406a1.4 1.4 0 1 1-2.8 0V10.03c0-.83-.47-2.142-1.5-3.263c-.996-1.082-2.424-1.884-4.24-1.884");
}

.s-o9m2c2v {
  stop-color: var(--svg-color--4a393c, #4A393C);
}

.sivyq3brk {
  cx: 19.512px;
  cy: 20.477px;
  r: 0.648px;
}

.sm6pc1b0i {
  cx: 21.527px;
  cy: 18.461px;
  r: 0.648px;
}

.sqriuff8s {
  stroke: var(--svg-color--85e4ff, #85E4FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.25 26.979c-.028.22.177.778 1.214 1.242c1.038.464 1.394.828 1.45.994");
}

.uveic7bxw {
  stop-color: var(--svg-color--72dbff, #72DBFF);
}

.uwl_seblg {
  stop-color: var(--svg-color--a6a3a8, #A6A3A8);
}

.wt0nsnbyb {
  stop-color: var(--svg-color--7f5159, #7F5159);
  stop-opacity: 0;
}

.x427r5b4x {
  stop-color: var(--svg-color--c5b8ba, #C5B8BA);
}

.x4nk_3bph {
  stop-color: var(--svg-color--74335f, #74335F);
}

.x5uejwblh {
  stop-color: var(--svg-color--96d1d7, #96D1D7);
  stop-opacity: 0;
}

.xffoocb-d {
  stop-color: var(--svg-color--4a393c, #4A393C);
  stop-opacity: 0;
}

.xt3m_ac0b {
  width: 1.984px;
  height: 0.984px;
  x: 11.004px;
  y: 18px;
  rx: 0.492px;
}

.zx9klzbvm {
  stop-color: var(--svg-color--623a4d, #623A4D);
  stop-opacity: 0;
}

</style>
