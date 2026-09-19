<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVIuvYc)"><path class="l7azkxbxt"/></g><path fill="url(#iSrCycc)" class="mijx5fbik"/><path fill="url(#iHfe79E)" class="mijx5fbik"/><path fill="url(#in9IYZc)" class="mijx5fbik"/><path fill="url(#ihV1Udc)" class="mijx5fbik"/><path fill="url(#imH8r9b)" class="mijx5fbik"/><path fill="url(#ijtpMPb)" class="mijx5fbik"/><g filter="url(#ioiC1mc)"><path fill="url(#ixrwf4N)" class="vnohmlfxs"/></g><path fill="url(#i9XViYJ)" class="vnohmlfxs"/><path fill="url(#iIeSF6b)" class="vnohmlfxs"/><path fill="url(#iRi9URF)" class="n8adkuu_h"/><path fill="url(#iAab15c)" class="n8adkuu_h"/><path fill="url(#in8TPIe)" class="n8adkuu_h"/><path fill="url(#ieBvRgU)" class="n8adkuu_h"/><path fill="url(#izlS9Pc)" class="n8adkuu_h"/><path fill="url(#iyMMbCN)" class="n8adkuu_h"/><path fill="url(#iBrloke)" class="n8adkuu_h"/><g filter="url(#iAvL9La)"><path fill="url(#icEDr2d)" class="kvp4zpbvw"/></g><g filter="url(#i24a1XZ)"><path fill="url(#iFgcSmd)" class="oj4q3nj8n"/><path fill="url(#im3B1Tb)" class="oj4q3nj8n"/></g><g filter="url(#iF6AgZs)"><path fill="url(#isPGHYb)" class="r66up1ipw"/></g><g filter="url(#iaOMSQb)"><path fill="url(#iyrM3Yb)" class="g23fycblc"/></g><g filter="url(#iaeSd5H)"><path fill="url(#ib1dJif)" class="rnk55tb-l"/></g><path fill="url(#iRxGAwd)" class="gs0o4bbln"/><path fill="url(#irefecc)" class="gs0o4bbln"/><g filter="url(#iXfhhGd)"><path stroke="url(#ial6v8c)" class="q-asutk8k"/></g><g filter="url(#iaD8efb)"><path fill="url(#iwE5N6S)" class="jwyrmckbq"/></g><path fill="url(#i0MzpCc)" class="jwyrmckbq"/><path fill="url(#ixnjpec)" class="jwyrmckbq"/><g filter="url(#i4RyY8b)"><path stroke="url(#i5HrwGA)" class="gl-wdbbqw"/></g><g filter="url(#iX33B6d)"><path class="axgmd9_oo"/></g><g filter="url(#iLkUedE)"><path class="bu5w2px6p"/></g><defs><linearGradient id="iSrCycc" x1="19.779" x2="12.62" y1="16.284" y2="10.451" gradientUnits="userSpaceOnUse"><stop class="iwo1sbsge"/><stop offset=".981" class="l24lvv5sr"/></linearGradient><linearGradient id="in9IYZc" x1="10" x2="10.979" y1="15.024" y2="15.024" gradientUnits="userSpaceOnUse"><stop class="j6_7in9qm"/><stop offset="1" class="w3gx7dbxf"/></linearGradient><linearGradient id="ihV1Udc" x1="18.995" x2="18.483" y1="9.386" y2="10.095" gradientUnits="userSpaceOnUse"><stop class="bs-57ccig"/><stop offset="1" class="z-w16_bph"/></linearGradient><linearGradient id="imH8r9b" x1="22" x2="21.194" y1="15.73" y2="15.73" gradientUnits="userSpaceOnUse"><stop class="k8kukpbaz"/><stop offset="1" class="fi93wyrfo"/></linearGradient><linearGradient id="ixrwf4N" x1="13.025" x2="20.088" y1="11.995" y2="5.988" gradientUnits="userSpaceOnUse"><stop class="u87nlxb6h"/><stop offset="1" class="yhy_g5bdi"/></linearGradient><linearGradient id="i9XViYJ" x1="12.225" x2="12.599" y1="8.177" y2="8.69" gradientUnits="userSpaceOnUse"><stop class="b-vtekbyd"/><stop offset="1" class="g_sgiabkw"/></linearGradient><linearGradient id="iIeSF6b" x1="9.228" x2="10.3" y1="12.116" y2="11.287" gradientUnits="userSpaceOnUse"><stop offset=".214" class="hjhngccau"/><stop offset="1" class="rjz61abfs"/></linearGradient><linearGradient id="iRi9URF" x1="16.759" x2="13.356" y1="18.22" y2="30.644" gradientUnits="userSpaceOnUse"><stop class="n2dmfj1ig"/><stop offset="1" class="s78ggj16a"/></linearGradient><linearGradient id="iAab15c" x1="13.813" x2="13.813" y1="28.967" y2="25.945" gradientUnits="userSpaceOnUse"><stop class="m7mawobkj"/><stop offset="1" class="x64dy0b2z"/></linearGradient><linearGradient id="in8TPIe" x1="28" x2="26.806" y1="26.489" y2="26.489" gradientUnits="userSpaceOnUse"><stop class="b7vv-xjnu"/><stop offset="1" class="qi7vzhnkm"/></linearGradient><linearGradient id="izlS9Pc" x1="22.772" x2="22.158" y1="19.578" y2="20.56" gradientUnits="userSpaceOnUse"><stop class="dp5s-lkhq"/><stop offset="1" class="bgv12ccfr"/></linearGradient><linearGradient id="iyMMbCN" x1="4" x2="5.343" y1="27.24" y2="27.24" gradientUnits="userSpaceOnUse"><stop class="yk8wlcc2o"/><stop offset="1" class="yowv8bb7d"/></linearGradient><linearGradient id="icEDr2d" x1="14.21" x2="17.595" y1="15.99" y2="9.797" gradientUnits="userSpaceOnUse"><stop class="ndhgjrb8s"/><stop offset="1" class="fk6fa6byv"/><stop offset="1" class="ucufa8wjq"/></linearGradient><linearGradient id="iFgcSmd" x1="14" x2="18" y1="24.637" y2="24.637" gradientUnits="userSpaceOnUse"><stop class="js24ohbcb"/><stop offset="1" class="s79sm875q"/></linearGradient><linearGradient id="im3B1Tb" x1="14" x2="14.227" y1="25.342" y2="25.342" gradientUnits="userSpaceOnUse"><stop class="q1wsohr_o"/><stop offset="1" class="ul_5fxoay"/></linearGradient><linearGradient id="isPGHYb" x1="9.025" x2="12.796" y1="27.99" y2="22.573" gradientUnits="userSpaceOnUse"><stop class="ndhgjrb8s"/><stop offset="1" class="fk6fa6byv"/><stop offset="1" class="ucufa8wjq"/></linearGradient><linearGradient id="iyrM3Yb" x1="20.146" x2="23.909" y1="27.99" y2="22.55" gradientUnits="userSpaceOnUse"><stop class="ndhgjrb8s"/><stop offset="1" class="fk6fa6byv"/><stop offset="1" class="ucufa8wjq"/></linearGradient><linearGradient id="ib1dJif" x1="10.179" x2="21.657" y1="23.996" y2="12.066" gradientUnits="userSpaceOnUse"><stop class="u87nlxb6h"/><stop offset="1" class="yhy_g5bdi"/></linearGradient><linearGradient id="iRxGAwd" x1="8.61" x2="9.165" y1="17.868" y2="18.797" gradientUnits="userSpaceOnUse"><stop class="b-vtekbyd"/><stop offset="1" class="g_sgiabkw"/></linearGradient><linearGradient id="irefecc" x1="2.732" x2="13.914" y1="24.19" y2="13.534" gradientUnits="userSpaceOnUse"><stop class="hjhngccau"/><stop offset="1" class="rjz61abfs"/></linearGradient><linearGradient id="ial6v8c" x1="11.586" x2="17.023" y1="9.084" y2="9.084" gradientUnits="userSpaceOnUse"><stop offset=".754" class="pb55k2bdp"/><stop offset=".907" class="frddwlnoa"/></linearGradient><linearGradient id="iwE5N6S" x1="5.859" x2="28.132" y1="28.98" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="fjg1tz-fa"/><stop offset="1" class="nrh57cc2g"/></linearGradient><linearGradient id="i0MzpCc" x1="26.078" x2="26.04" y1="27.98" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="x-rf2_5mx"/><stop offset="1" class="zswqp9blv"/></linearGradient><linearGradient id="ixnjpec" x1="30.351" x2="29.158" y1="29.673" y2="29.673" gradientUnits="userSpaceOnUse"><stop class="xhvas2-1c"/><stop offset="1" class="ck02h4b-m"/></linearGradient><linearGradient id="i5HrwGA" x1="6.558" x2="17.901" y1="19.307" y2="19.307" gradientUnits="userSpaceOnUse"><stop offset=".597" class="pb55k2bdp"/><stop offset=".907" class="frddwlnoa"/></linearGradient><filter id="iVIuvYc" width="3.25" height="6.3" x="14.49" y="1.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.227451 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/></filter><filter id="ioiC1mc" width="14.48" height="6.408" x="8.85" y="5.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/></filter><filter id="iAvL9La" width="4.7" height="5.25" x="13.5" y="10.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.415686 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7177" result="effect2_innerShadow_18_7177"/></filter><filter id="i24a1XZ" width="4.5" height="8.25" x="13.5" y="19.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.105882 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/></filter><filter id="iF6AgZs" width="3.59" height="6.357" x="8.61" y="22.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.486275 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7177" result="effect2_innerShadow_18_7177"/></filter><filter id="iaOMSQb" width="3.61" height="6.357" x="19.73" y="22.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.486275 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7177" result="effect2_innerShadow_18_7177"/></filter><filter id="iaeSd5H" width="28.21" height="10.043" x="1.99" y="13.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/></filter><filter id="iXfhhGd" width="14.406" height="6.208" x="8.929" y="5.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7177" stdDeviation=".4"/></filter><filter id="iaD8efb" width="28.28" height="2.25" x="1.97" y="27.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7177"/></filter><filter id="i4RyY8b" width="27.88" height="10.023" x="2.103" y="13.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7177" stdDeviation=".4"/></filter><filter id="iX33B6d" width="1.1" height="4.357" x="15.493" y="1.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7177" stdDeviation=".2"/></filter><filter id="iLkUedE" width="3.165" height="1.1" x="14.461" y="2.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7177" stdDeviation=".2"/></filter><radialGradient id="iHfe79E" cx="0" cy="0" r="1" gradientTransform="matrix(6.79588 -5.76686 6.4966 7.65584 10 17.41)" gradientUnits="userSpaceOnUse"><stop class="leffv5-_p"/><stop offset="1" class="smnk-2b5t"/></radialGradient><radialGradient id="ijtpMPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2118 -2.54895 5.63451 -.4682 16 15.81)" gradientUnits="userSpaceOnUse"><stop class="scvd_rbiu"/><stop offset="1" class="b08-qvbfa"/></radialGradient><radialGradient id="ieBvRgU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17188 0 0 -2.04242 27.89 22.49)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="dxplrqi7b"/><stop offset="1" class="lsmhutyox"/></radialGradient><radialGradient id="iBrloke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07206 -.57857 0 3.903 23.121)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k-eeqz9hv"/><stop offset="1" class="hezunu0fm"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:church" /></template>
<style>
.axgmd9_oo {
  stroke: var(--svg-color--a0776e, #A0776E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.043 2.4v3.258");
}

.b-vtekbyd {
  stop-color: var(--svg-color--735b52, #735B52);
}

.b08-qvbfa {
  stop-color: var(--svg-color--e3b384, #E3B384);
  stop-opacity: 0;
}

.b7vv-xjnu {
  stop-color: var(--svg-color--fdd2ab, #FDD2AB);
}

.bgv12ccfr {
  stop-color: var(--svg-color--ab716c, #AB716C);
  stop-opacity: 0;
}

.bs-57ccig {
  stop-color: var(--svg-color--a56a60, #A56A60);
}

.bu5w2px6p {
  stroke: var(--svg-color--a0776e, #A0776E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.01 3.425h2.066");
}

.ck02h4b-m {
  stop-color: var(--svg-color--b78d82, #B78D82);
  stop-opacity: 0;
}

.dp5s-lkhq {
  stop-color: var(--svg-color--ab716c, #AB716C);
}

.dxplrqi7b {
  stop-color: var(--svg-color--a27166, #A27166);
}

.fi93wyrfo {
  stop-color: var(--svg-color--ffe7b9, #FFE7B9);
  stop-opacity: 0;
}

.fjg1tz-fa {
  stop-color: var(--svg-color--765755, #765755);
}

.fk6fa6byv {
  stop-color: var(--svg-color--3892e6, #3892E6);
}

.frddwlnoa {
  stop-color: var(--svg-color--b28070, #B28070);
}

.ft5dv1b6b {
  fill: none;
}

.g_sgiabkw {
  stop-color: var(--svg-color--735b52, #735B52);
  stop-opacity: 0;
}

.g23fycblc {
  d: path("M23.14 24.57c0-.87-.71-1.58-1.58-1.58s-1.58.71-1.58 1.58v4.527h3.16z");
}

.gl-wdbbqw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.103 22.907l12.94-7.988l12.94 7.988");
}

.gs0o4bbln {
  d: path("m2.38 22.4l12.25-7.65c.85-.53 1.92-.53 2.76 0l12.23 7.65a.801.801 0 1 1-.85 1.36l-11.11-6.92c-1.43-.8-1.98-.79-3.31 0L3.22 23.87c-.53.34-1.244-.055-1.244-.685c0-.48.225-.673.404-.785");
}

.hezunu0fm {
  stop-color: var(--svg-color--5e3d34, #5E3D34);
  stop-opacity: 0;
}

.hjhngccau {
  stop-color: var(--svg-color--593d48, #593D48);
}

.iwo1sbsge {
  stop-color: var(--svg-color--eec096, #EEC096);
}

.j6_7in9qm {
  stop-color: var(--svg-color--9f7350, #9F7350);
}

.js24ohbcb {
  stop-color: var(--svg-color--4e3960, #4E3960);
}

.jwyrmckbq {
  d: path("M30 29.98H1.97v-.66c0-.74.6-1.34 1.34-1.34h25.35c.74 0 1.34.6 1.34 1.34z");
}

.k-eeqz9hv {
  stop-color: var(--svg-color--5e3d34, #5E3D34);
}

.k8kukpbaz {
  stop-color: var(--svg-color--ffe7b9, #FFE7B9);
}

.kvp4zpbvw {
  d: path("M17.58 15.99h-3.16c-.23 0-.42-.19-.42-.42v-2.58c0-1.1.9-2 2-2s2 .9 2 2v2.58c0 .23-.19.42-.42.42");
}

.l24lvv5sr {
  stop-color: var(--svg-color--e9b188, #E9B188);
}

.l7azkxbxt {
  fill: var(--svg-color--8f6058, #8F6058);
  d: path("M16.99 2.99h-.5v-.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5v.5h-.5c-.28 0-.5.22-.5.5s.22.5.5.5h.5v3.8c0 .28.22.5.5.5s.5-.22.5-.5v-3.8h.5c.28 0 .5-.22.5-.5c0-.27-.23-.5-.5-.5");
}

.leffv5-_p {
  stop-color: var(--svg-color--e1a470, #E1A470);
}

.lsmhutyox {
  stop-color: var(--svg-color--a27166, #A27166);
  stop-opacity: 0;
}

.m7mawobkj {
  stop-color: var(--svg-color--c89d78, #C89D78);
}

.mijx5fbik {
  d: path("M22 17.99H10v-6.47l5.99-4.53L22 11.52z");
}

.n2dmfj1ig {
  stop-color: var(--svg-color--eaaf8a, #EAAF8A);
}

.n8adkuu_h {
  d: path("M28 29.99H4v-7.5l11.99-7.5L28 22.49z");
}

.ndhgjrb8s {
  stop-color: var(--svg-color--56c7f5, #56C7F5);
}

.nrh57cc2g {
  stop-color: var(--svg-color--9a5e5e, #9A5E5E);
}

.oj4q3nj8n {
  d: path("M18 21.99c0-1.1-.9-2-2-2s-2 .9-2 2v6h4z");
}

.pb55k2bdp {
  stop-color: var(--svg-color--94665f, #94665F);
}

.q-asutk8k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.93 11.084l5.636-4.022a1 1 0 0 1 1.164.001l5.606 4.02");
}

.q1wsohr_o {
  stop-color: var(--svg-color--3e2651, #3E2651);
}

.qi7vzhnkm {
  stop-color: var(--svg-color--fdd2ab, #FDD2AB);
  stop-opacity: 0;
}

.r66up1ipw {
  d: path("M12 24.56c0-.87-.7-1.57-1.57-1.57s-1.57.7-1.57 1.57v4.537h3.13V24.56z");
}

.rjz61abfs {
  stop-color: var(--svg-color--593d48, #593D48);
  stop-opacity: 0;
}

.rnk55tb-l {
  d: path("M2 23.08c0-.28.14-.53.38-.68l12.25-7.65c.85-.53 1.92-.53 2.76 0l12.23 7.65a.801.801 0 1 1-.85 1.36l-11.11-6.92c-1.43-.8-1.98-.79-3.31 0L3.22 23.87c-.53.34-1.23-.05-1.23-.68v-.11z");
}

.s78ggj16a {
  stop-color: var(--svg-color--e3a46d, #E3A46D);
}

.s79sm875q {
  stop-color: var(--svg-color--382e40, #382E40);
}

.scvd_rbiu {
  stop-color: var(--svg-color--e3b384, #E3B384);
}

.smnk-2b5t {
  stop-color: var(--svg-color--e1a470, #E1A470);
  stop-opacity: 0;
}

.u87nlxb6h {
  stop-color: var(--svg-color--764742, #764742);
}

.ucufa8wjq {
  stop-color: var(--svg-color--2f95db, #2F95DB);
}

.ul_5fxoay {
  stop-color: var(--svg-color--3e2651, #3E2651);
  stop-opacity: 0;
}

.vnohmlfxs {
  d: path("m10.18 11.84l5.05-3.61c.46-.33 1.08-.33 1.54 0l5.05 3.61a.83.83 0 0 0 1.31-.68c0-.27-.13-.52-.35-.68l-5.89-4.2a1.53 1.53 0 0 0-1.8 0l-5.89 4.2c-.22.16-.35.41-.35.68c.02.68.78 1.07 1.33.68");
}

.w3gx7dbxf {
  stop-color: var(--svg-color--9f7350, #9F7350);
  stop-opacity: 0;
}

.x-rf2_5mx {
  stop-color: var(--svg-color--996752, #996752);
}

.x64dy0b2z {
  stop-color: var(--svg-color--c89d78, #C89D78);
  stop-opacity: 0;
}

.xhvas2-1c {
  stop-color: var(--svg-color--b78d82, #B78D82);
}

.yhy_g5bdi {
  stop-color: var(--svg-color--b68473, #B68473);
}

.yk8wlcc2o {
  stop-color: var(--svg-color--9c704f, #9C704F);
}

.yowv8bb7d {
  stop-color: var(--svg-color--9c704f, #9C704F);
  stop-opacity: 0;
}

.z-w16_bph {
  stop-color: var(--svg-color--a56a60, #A56A60);
  stop-opacity: 0;
}

.zswqp9blv {
  stop-color: var(--svg-color--996752, #996752);
  stop-opacity: 0;
}

</style>
