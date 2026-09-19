<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#is6viUb)"><path class="l657qactb"/><path fill="url(#iMcpLlb)" class="yrchscb4h"/><path fill="url(#iY9oJFe)" class="yrchscb4h"/><path fill="url(#ioPbzTb)" class="yrchscb4h"/><path fill="url(#iHR6a3b)" class="yrchscb4h"/></g><path fill="url(#igXbPse)" class="yrchscb4h"/><path fill="url(#iYRgOOe)" class="yrchscb4h"/><g filter="url(#i61aRoc)"><rect class="wkyh76n3h"/></g><g filter="url(#iGRHWBc)"><rect class="v7ggp-biv"/></g><path class="v0ae66bjg"/><path fill="url(#insFYEb)" class="m8qlwsl0w"/><path fill="url(#ijEZjwd)" class="m8qlwsl0w"/><path fill="url(#ic9F4md)" class="m8qlwsl0w"/><path fill="url(#isaR8Ec)" class="m8qlwsl0w"/><path fill="url(#iOWpwGd)" class="ev070190d"/><path fill="url(#iCSKtCe)" class="ev070190d"/><path fill="url(#ilqFShC)" class="ev070190d"/><path fill="url(#iN3EI6d)" class="ev070190d"/><g filter="url(#ip2yt4c)"><rect fill="url(#iiDrUwc)" class="w4lncgbrh"/><rect fill="url(#iYltHIc)" class="w4lncgbrh"/><rect fill="url(#ikndd4b)" class="w4lncgbrh"/></g><g filter="url(#iom89ie)"><rect fill="url(#ixewUgd)" class="uu3_-ib2n"/></g><g filter="url(#iXEyDkb)"><rect fill="url(#idjxJRb)" class="osyl__8fc"/></g><g filter="url(#i1R7ftb)"><rect class="s88on3oro"/></g><g filter="url(#ipUi0qd)"><rect fill="url(#irdZNae)" class="outzmcc6o"/></g><g filter="url(#ikxqBld)"><rect class="qb-xaibaz"/></g><defs><radialGradient id="iMcpLlb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.14246 2.5592 -1.38196 -3.8569 10.573 11.301)" gradientUnits="userSpaceOnUse"><stop class="s7n8m0bbd"/><stop offset="1" class="enftyvurl"/></radialGradient><radialGradient id="iY9oJFe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.93158 3.02526 -4.1051 -12.11964 23.37 18.295)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="xbpiv709r"/><stop offset="1" class="l82nk1bkn"/></radialGradient><radialGradient id="ioPbzTb" cx="0" cy="0" r="1" gradientTransform="translate(7.496 7.465)scale(1.81597)" gradientUnits="userSpaceOnUse"><stop class="gbypyogjw"/><stop offset="1" class="xahdoorij"/></radialGradient><radialGradient id="iHR6a3b" cx="0" cy="0" r="1" gradientTransform="matrix(3.37505 -12.56253 11.31033 3.03864 8.184 34.937)" gradientUnits="userSpaceOnUse"><stop class="i7a2l4b0o"/><stop offset="1" class="g09328pji"/><stop offset="1" class="dz_af6sqm"/></radialGradient><radialGradient id="insFYEb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.26776 -.44576 .97334 -13.68603 27.924 16.387)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="l82nk1bkn"/><stop offset=".975" class="xbpiv709r"/></radialGradient><radialGradient id="ijEZjwd" cx="0" cy="0" r="1" gradientTransform="rotate(135.167 9.188 15.316)scale(8.73491 2.30407)" gradientUnits="userSpaceOnUse"><stop class="t66lkub2g"/><stop offset="1" class="aq02qtbkv"/></radialGradient><radialGradient id="ic9F4md" cx="0" cy="0" r="1" gradientTransform="rotate(144.638 12.257 11.59)scale(2.76123 1.79671)" gradientUnits="userSpaceOnUse"><stop class="ccglv8ldx"/><stop offset="1" class="e4omxmbdx"/></radialGradient><radialGradient id="isaR8Ec" cx="0" cy="0" r="1" gradientTransform="rotate(131.704 9.87 11.897)scale(4.63886 1.53956)" gradientUnits="userSpaceOnUse"><stop class="jvowg1bdc"/><stop offset="1" class="ns74x0bhl"/></radialGradient><radialGradient id="ilqFShC" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 0 0 1.53125 21.247 3.773)" gradientUnits="userSpaceOnUse"><stop class="l5p9pz4rq"/><stop offset="1" class="tay44oboe"/></radialGradient><radialGradient id="iN3EI6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.25183 0 0 3.53051 16.834 9.88)" gradientUnits="userSpaceOnUse"><stop class="f817y8s4v"/><stop offset="1" class="ycg9odlti"/></radialGradient><radialGradient id="ikndd4b" cx="0" cy="0" r="1" gradientTransform="rotate(149.179 5.105 6.958)scale(1.07751 2.24971)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="ebxllzb7m"/><stop offset="1" class="j_33xv_zs"/></radialGradient><linearGradient id="igXbPse" x1="4.122" x2="7.434" y1="19.773" y2="19.836" gradientUnits="userSpaceOnUse"><stop class="gogfdzbcw"/><stop offset="1" class="b5a0cacid"/></linearGradient><linearGradient id="iYRgOOe" x1="3.431" x2="4.247" y1="18.516" y2="18.516" gradientUnits="userSpaceOnUse"><stop class="f6kibjgzw"/><stop offset="1" class="kk8oa4ims"/></linearGradient><linearGradient id="iOWpwGd" x1="17.306" x2="20.143" y1="8.355" y2="8.355" gradientUnits="userSpaceOnUse"><stop class="w0ehejbgg"/><stop offset="1" class="ym2681wfs"/></linearGradient><linearGradient id="iCSKtCe" x1="19.084" x2="19.084" y1="12.748" y2="10.371" gradientUnits="userSpaceOnUse"><stop class="ajfs3hb7t"/><stop offset="1" class="smew-ib-y"/></linearGradient><linearGradient id="iiDrUwc" x1="9.201" x2="12.028" y1="11.502" y2="11.616" gradientUnits="userSpaceOnUse"><stop class="ku-02pclg"/><stop offset="1" class="qdmgghsma"/></linearGradient><linearGradient id="iYltHIc" x1="12.493" x2="11.782" y1="12.965" y2="12.965" gradientUnits="userSpaceOnUse"><stop class="f2hd1gbhl"/><stop offset="1" class="s2r9bwbgc"/></linearGradient><linearGradient id="ixewUgd" x1="13.297" x2="17.523" y1="10.576" y2="10.576" gradientUnits="userSpaceOnUse"><stop class="f63qnrbis"/><stop offset="1" class="l0-l--b6z"/></linearGradient><linearGradient id="idjxJRb" x1="20.397" x2="20.397" y1="3.657" y2="14.102" gradientUnits="userSpaceOnUse"><stop class="bwp7pnbqb"/><stop offset="1" class="b4gpdrxyu"/><stop offset="1" class="gib-zub8b"/></linearGradient><linearGradient id="irdZNae" x1="6.708" x2="6.708" y1="8.046" y2="19.378" gradientUnits="userSpaceOnUse"><stop class="mzl_h2r6k"/><stop offset="1" class="mz-7uabeh"/></linearGradient><filter id="is6viUb" width="26.567" height="28.515" x="3.431" y="1.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.494118 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2381"/></filter><filter id="i61aRoc" width="6.696" height="8.966" x="10.551" y="9.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2381" stdDeviation=".75"/></filter><filter id="iGRHWBc" width="8.409" height="11.255" x="5.442" y="8.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2381" stdDeviation="1"/></filter><filter id="ip2yt4c" width="5.922" height="9.222" x="7.882" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.580392 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2381"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.658824 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2381" result="effect2_innerShadow_20020_2381"/></filter><filter id="iom89ie" width="5.828" height="11.084" x="12.445" y="6.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.556863 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2381"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".6"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.631373 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2381" result="effect2_innerShadow_20020_2381"/></filter><filter id="iXEyDkb" width="4.636" height="13.444" x="18.079" y="2.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2381" stdDeviation=".75"/></filter><filter id="i1R7ftb" width="5.468" height="10.264" x="13.266" y="7.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2381" stdDeviation="1"/></filter><filter id="ipUi0qd" width="4.468" height="11.935" x="4.474" y="5.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2381" stdDeviation=".75"/></filter><filter id="ikxqBld" width="4.027" height="7.274" x="8.968" y="8.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2381" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:love-you-gesture-light" /></template>
<style>
.ajfs3hb7t {
  stop-color: var(--svg-color--fad3bd, #FAD3BD);
}

.aq02qtbkv {
  stop-color: var(--svg-color--d1a19e, #D1A19E);
  stop-opacity: 0;
}

.b4gpdrxyu {
  stop-color: var(--svg-color--cca48d, #CCA48D);
  stop-opacity: 0;
}

.b5a0cacid {
  stop-color: var(--svg-color--dca591, #DCA591);
  stop-opacity: 0;
}

.bwp7pnbqb {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
}

.ccglv8ldx {
  stop-color: var(--svg-color--ffe5c8, #FFE5C8);
}

.dz_af6sqm {
  stop-color: var(--svg-color--eeb5ad, #EEB5AD);
  stop-opacity: 0;
}

.e4omxmbdx {
  stop-color: var(--svg-color--ffe5c8, #FFE5C8);
  stop-opacity: 0;
}

.ebxllzb7m {
  stop-color: var(--svg-color--c38764, #C38764);
}

.enftyvurl {
  stop-color: var(--svg-color--c7826f, #C7826F);
  stop-opacity: 0;
}

.ev070190d {
  d: path("M22.223 12.5h-5.289l.039-7.503c0-1.844 1.219-2.97 2.625-2.97c1.5 0 2.625 1.298 2.625 2.97z");
}

.f2hd1gbhl {
  stop-color: var(--svg-color--dc9f7d, #DC9F7D);
}

.f63qnrbis {
  stop-color: var(--svg-color--e5b397, #E5B397);
}

.f6kibjgzw {
  stop-color: var(--svg-color--f0b49b, #F0B49B);
}

.f817y8s4v {
  stop-color: var(--svg-color--e8a17c, #E8A17C);
}

.ft5dv1b6b {
  fill: none;
}

.g09328pji {
  stop-color: var(--svg-color--ae797e, #AE797E);
  stop-opacity: 0;
}

.gbypyogjw {
  stop-color: var(--svg-color--ffdec0, #FFDEC0);
}

.gib-zub8b {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
  stop-opacity: 0;
}

.gogfdzbcw {
  stop-color: var(--svg-color--dca591, #DCA591);
}

.i7a2l4b0o {
  stop-color: var(--svg-color--eeb5ad, #EEB5AD);
}

.j_33xv_zs {
  stop-color: var(--svg-color--c38764, #C38764);
  stop-opacity: 0;
}

.jvowg1bdc {
  stop-color: var(--svg-color--e1aa8b, #E1AA8B);
}

.kk8oa4ims {
  stop-color: var(--svg-color--f0b49b, #F0B49B);
  stop-opacity: 0;
}

.ku-02pclg {
  stop-color: var(--svg-color--e1af92, #E1AF92);
}

.l0-l--b6z {
  stop-color: var(--svg-color--ffd7b6, #FFD7B6);
}

.l5p9pz4rq {
  stop-color: var(--svg-color--ffe4c6, #FFE4C6);
}

.l657qactb {
  fill: var(--svg-color--f2bcab, #F2BCAB);
  d: path("M28.742 13.567c-.7-.809-2.063-1.29-3.297-.649c-1.235.641-2.209 1.377-2.578 1.723c0 0-.649.444-.649-.384v-9.26c0-1.672-1.125-2.97-2.625-2.97c-1.406 0-2.625 1.126-2.625 2.97l-.038 7.506H8.656V8.528c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.102 4.328 10.26 9.653 10.26c2.709 0 5.41-1.221 7.189-3.093c2.258-2.375 1.562-3.312 3.96-5.867c1.212-1.383 3.14-2.707 4.196-3.578s1.258-2.695.313-3.789");
}

.l82nk1bkn {
  stop-color: var(--svg-color--ffe0c6, #FFE0C6);
  stop-opacity: 0;
}

.m8qlwsl0w {
  d: path("M25.445 12.919c1.234-.641 2.598-.16 3.297.648c.945 1.094.743 2.918-.313 3.79c-.278.229-.617.49-.988.775c-1.035.797-2.315 1.784-3.207 2.802c-.794.845-1.248 1.513-1.584 2.115c-1.491-3.69-1.036-6.778-.366-8.437c.165.315.583.03.583.03c.37-.347 1.343-1.083 2.578-1.723");
}

.mz-7uabeh {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
  stop-opacity: 0;
}

.mzl_h2r6k {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
}

.ns74x0bhl {
  stop-color: var(--svg-color--e1aa8b, #E1AA8B);
  stop-opacity: 0;
}

.osyl__8fc {
  width: 1.636px;
  height: 10.444px;
  x: 19.579px;
  y: 3.657px;
  rx: 0.818px;
}

.outzmcc6o {
  width: 1.468px;
  height: 8.935px;
  x: 5.974px;
  y: 7.065px;
  rx: 0.734px;
}

.qb-xaibaz {
  width: 1.027px;
  height: 4.274px;
  x: 10.468px;
  y: 10.485px;
  fill: var(--svg-color--ffd2bb, #FFD2BB);
  rx: 0.513px;
}

.qdmgghsma {
  stop-color: var(--svg-color--eebea3, #EEBEA3);
}

.s2r9bwbgc {
  stop-color: var(--svg-color--dc9f7d, #DC9F7D);
  stop-opacity: 0;
}

.s7n8m0bbd {
  stop-color: var(--svg-color--c7826f, #C7826F);
}

.s88on3oro {
  width: 1.468px;
  height: 6.264px;
  x: 15.266px;
  y: 9.052px;
  fill: var(--svg-color--ffe6c8, #FFE6C8);
  rx: 0.734px;
}

.smew-ib-y {
  stop-color: var(--svg-color--fad3bd, #FAD3BD);
  stop-opacity: 0;
}

.t66lkub2g {
  stop-color: var(--svg-color--d1a19e, #D1A19E);
}

.tay44oboe {
  stop-color: var(--svg-color--ffe4c6, #FFE4C6);
  stop-opacity: 0;
}

.uu3_-ib2n {
  width: 5.078px;
  height: 9.734px;
  x: 12.445px;
  y: 7.317px;
  rx: 2.539px;
}

.v0ae66bjg {
  fill: var(--svg-color--fcc8ad, #FCC8AD);
  d: path("M25.445 12.919c1.234-.641 2.598-.16 3.297.648c.945 1.094.743 2.918-.313 3.79c-.278.229-.617.49-.988.775c-1.035.797-2.315 1.784-3.207 2.802c-.794.845-1.248 1.513-1.584 2.115c-1.491-3.69-1.036-6.778-.366-8.437c.165.315.583.03.583.03c.37-.347 1.343-1.083 2.578-1.723");
}

.v7ggp-biv {
  width: 4.409px;
  height: 7.256px;
  x: 7.442px;
  y: 10.195px;
  fill: var(--svg-color--a55e53, #A55E53);
  rx: 2.204px;
}

.w0ehejbgg {
  stop-color: var(--svg-color--eba784, #EBA784);
}

.w4lncgbrh {
  width: 5.172px;
  height: 8.172px;
  x: 7.882px;
  y: 8.879px;
  rx: 2.539px;
}

.wkyh76n3h {
  width: 3.696px;
  height: 5.966px;
  x: 12.051px;
  y: 11.484px;
  fill: var(--svg-color--a55e53, #A55E53);
  rx: 1.848px;
}

.xahdoorij {
  stop-color: var(--svg-color--ffdec0, #FFDEC0);
  stop-opacity: 0;
}

.xbpiv709r {
  stop-color: var(--svg-color--ffe0c6, #FFE0C6);
}

.ycg9odlti {
  stop-color: var(--svg-color--e8a17c, #E8A17C);
  stop-opacity: 0;
}

.ym2681wfs {
  stop-color: var(--svg-color--eba784, #EBA784);
  stop-opacity: 0;
}

.yrchscb4h {
  d: path("M28.742 13.567c-.7-.809-2.063-1.29-3.297-.649c-1.235.641-2.209 1.377-2.578 1.723c0 0-.649.444-.649-.384v-9.26c0-1.672-1.125-2.97-2.625-2.97c-1.406 0-2.625 1.126-2.625 2.97l-.038 7.506H8.656V8.528c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.102 4.328 10.26 9.653 10.26c2.709 0 5.41-1.221 7.189-3.093c2.258-2.375 1.562-3.312 3.96-5.867c1.212-1.383 3.14-2.707 4.196-3.578s1.258-2.695.313-3.789");
}

</style>
