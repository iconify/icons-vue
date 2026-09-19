<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imEFGed)"><path class="au1y2uvlr"/></g><path fill="url(#i4fLi9b)" class="vu2f16bpy"/><path fill="url(#i6Gq2Rd)" class="vu2f16bpy"/><path fill="url(#iL0WcqP)" class="vu2f16bpy"/><path fill="url(#iY0T1sz)" class="vu2f16bpy"/><path fill="url(#ixZRYCe)" class="vu2f16bpy"/><g filter="url(#icuwOhb)"><path class="g6d_tnb9l"/></g><g filter="url(#i5XH2cw)"><path class="fer4c4bif"/></g><g filter="url(#iW0U7pd)"><path class="ntobp_bki"/></g><g filter="url(#iEBeypr)"><path fill="url(#ieSA7Nc)" class="x32ai7b6d"/><path fill="url(#id7gcxe)" class="x32ai7b6d"/></g><path fill="url(#iYbmjyb)" class="x32ai7b6d"/><path fill="url(#ihFTvfe)" class="x32ai7b6d"/><g filter="url(#i8WshJd)"><rect transform="rotate(-3.35 8.302 14.061)" class="vc4wpn4vp"/></g><g filter="url(#iouSoWd)"><path fill="url(#iKwXbGd)" class="inh5-xb7q"/><path fill="url(#iWj9XEb)" class="inh5-xb7q"/><path fill="url(#iAgNqPe)" class="inh5-xb7q"/><path fill="url(#ihPFs4T)" class="inh5-xb7q"/><path fill="url(#iJzFXgx)" class="inh5-xb7q"/></g><g filter="url(#iRgWGDd)"><rect fill="url(#iIjs90d)" transform="rotate(-1.407 12.867 11.807)" class="ha9pd0-sq"/></g><g filter="url(#iwihr6d)"><path fill="url(#iJC6UOd)" class="mp7-bha1d"/></g><g filter="url(#iOEmf8b)"><rect transform="rotate(-1.407 18.129 11.489)" class="vm5g7qe5w"/></g><path fill="url(#ixNpwIc)" class="toyule75s"/><path fill="url(#it9Ttyb)" class="toyule75s"/><path fill="url(#i2k9ApM)" class="toyule75s"/><path fill="url(#i9j1Wmb)" class="toyule75s"/><g filter="url(#iUHh7Mf)"><path stroke="url(#iqWQUde)" class="d5xlfib-d"/></g><g filter="url(#iVkSjle)"><rect class="w0n6qib0c"/></g><defs><filter id="imEFGed" width="20.934" height="28.788" x="5.684" y="1.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.286275 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5596"/></filter><filter id="icuwOhb" width="14.516" height="10.203" x="12.258" y="13.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation="1.25"/></filter><filter id="i5XH2cw" width="9.153" height="11.219" x="4.823" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation="1.25"/></filter><filter id="iW0U7pd" width="9.825" height="12.747" x="8.675" y="10.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation="1.25"/></filter><filter id="iEBeypr" width="5.431" height="8.136" x="5.684" y="12.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.313726 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5596"/></filter><filter id="i8WshJd" width="4.869" height="7.227" x="6.851" y="12.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation=".75"/></filter><filter id="iouSoWd" width="5.272" height="8.719" x="10.532" y="10.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.290196 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5596"/></filter><filter id="iRgWGDd" width="5.019" height="8.302" x="11.391" y="10.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation=".75"/></filter><filter id="iwihr6d" width="5.414" height="9.427" x="15.662" y="10.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.184314 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5596"/></filter><filter id="iOEmf8b" width="5.045" height="9.019" x="16.652" y="9.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation=".75"/></filter><filter id="iUHh7Mf" width="8.894" height="7.704" x="17.114" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation=".625"/></filter><filter id="iVkSjle" width="5.688" height="15.594" x="21.195" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5596" stdDeviation="1"/></filter><radialGradient id="i4fLi9b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56216 -6.90397 4.82919 -4.5901 25.445 17.248)" gradientUnits="userSpaceOnUse"><stop class="klh24zbqk"/><stop offset="1" class="zay_9p1oa"/></radialGradient><radialGradient id="i6Gq2Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86066 3.08361 -3.55273 -3.29586 20.43 21.186)" gradientUnits="userSpaceOnUse"><stop class="r7udrlbjv"/><stop offset="1" class="kqlyp1brb"/></radialGradient><radialGradient id="iY0T1sz" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.28124 -1.43471 -1.1198 24.164 3.875)" gradientUnits="userSpaceOnUse"><stop class="fxywcj73h"/><stop offset="1" class="xrdcusbnk"/></radialGradient><radialGradient id="ixZRYCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.61097 0 0 5.50045 20.023 13.017)" gradientUnits="userSpaceOnUse"><stop class="rnex3kbdo"/><stop offset="1" class="e28y277by"/></radialGradient><radialGradient id="iYbmjyb" cx="0" cy="0" r="1" gradientTransform="matrix(.22676 -2.36686 3.52277 .3375 7.592 20.23)" gradientUnits="userSpaceOnUse"><stop class="eujq7sx2e"/><stop offset="1" class="xd37muika"/></radialGradient><radialGradient id="ihFTvfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05924 .64915 -1.06456 -1.73707 11.115 13.026)" gradientUnits="userSpaceOnUse"><stop class="bjs8-3bhr"/><stop offset="1" class="csio_zwnn"/></radialGradient><radialGradient id="iAgNqPe" cx="0" cy="0" r="1" gradientTransform="rotate(-82.532 17.437 2.64)scale(3.14412 4.97212)" gradientUnits="userSpaceOnUse"><stop class="gxydj6bhi"/><stop offset="1" class="y67e99jat"/></radialGradient><radialGradient id="ihPFs4T" cx="0" cy="0" r="1" gradientTransform="matrix(-.67768 .30875 -.56066 -1.2306 15.803 12.7)" gradientUnits="userSpaceOnUse"><stop class="za8-v5r8c"/><stop offset="1" class="gm2wbfbbj"/></radialGradient><radialGradient id="iJzFXgx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68416 -.7271 .95657 -2.2157 15.804 18.249)" gradientUnits="userSpaceOnUse"><stop class="s4ow685hd"/><stop offset="1" class="hlxiqjbdk"/></radialGradient><radialGradient id="iIjs90d" cx="0" cy="0" r="1" gradientTransform="rotate(91.407 .111 13.737)scale(7.23413 3.88646)" gradientUnits="userSpaceOnUse"><stop class="bwg1p8b-i"/><stop offset="1" class="qvnsdsxex"/></radialGradient><radialGradient id="it9Ttyb" cx="0" cy="0" r="1" gradientTransform="matrix(3.40306 3.0913 -2.37051 2.60958 19.62 21.933)" gradientUnits="userSpaceOnUse"><stop class="w5sbs8nfi"/><stop offset="1" class="zm8xf8bwb"/></radialGradient><linearGradient id="iL0WcqP" x1="26.82" x2="23.086" y1="12.219" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="t7i74zl-e"/><stop offset="1" class="ului_hb8y"/></linearGradient><linearGradient id="ieSA7Nc" x1="9.44" x2="4.525" y1="14.556" y2="15.006" gradientUnits="userSpaceOnUse"><stop class="kxq4jkutd"/><stop offset="1" class="eucwrjbls"/></linearGradient><linearGradient id="id7gcxe" x1="11.445" x2="9.683" y1="15.721" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="wwi4mebsv"/><stop offset="1" class="bo__mc-7r"/></linearGradient><linearGradient id="iKwXbGd" x1="15.559" x2="10.809" y1="14.438" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="wd1nypbbl"/><stop offset="1" class="ter92bcdr"/></linearGradient><linearGradient id="iWj9XEb" x1="16.124" x2="14.412" y1="14.753" y2="14.855" gradientUnits="userSpaceOnUse"><stop class="g7tzf_b0v"/><stop offset="1" class="n1i303bed"/></linearGradient><linearGradient id="iJC6UOd" x1="16.653" x2="20.72" y1="13.868" y2="13.868" gradientUnits="userSpaceOnUse"><stop class="qot0pwbpf"/><stop offset="1" class="dvyrp5bps"/></linearGradient><linearGradient id="ixNpwIc" x1="24.175" x2="20.542" y1="17.178" y2="21.929" gradientUnits="userSpaceOnUse"><stop class="n0bwn6bue"/><stop offset="1" class="etvdl-b6n"/></linearGradient><linearGradient id="i2k9ApM" x1="22.555" x2="22.519" y1="26.284" y2="22.217" gradientUnits="userSpaceOnUse"><stop offset=".382" class="v8vydcq5h"/><stop offset="1" class="nunphccoi"/></linearGradient><linearGradient id="i9j1Wmb" x1="15.758" x2="19.333" y1="18.375" y2="18.375" gradientUnits="userSpaceOnUse"><stop class="ml8zr5ilx"/><stop offset="1" class="xt5uxkbgn"/></linearGradient><linearGradient id="iqWQUde" x1="21.039" x2="24.547" y1="17.781" y2="20.397" gradientUnits="userSpaceOnUse"><stop offset=".452" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-up-medium-dark" /></template>
<style>
.au1y2uvlr {
  fill: var(--svg-color--84555e, #84555E);
  d: path("M23.136 1.906a2.656 2.656 0 0 0-2.656 2.657v11.25H5.684v4.227c0 5.553 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.347l.003.003c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.563a2.656 2.656 0 0 0-2.657-2.657");
}

.bjs8-3bhr {
  stop-color: var(--svg-color--502c20, #502C20);
}

.bo__mc-7r {
  stop-color: var(--svg-color--653e2f, #653E2F);
  stop-opacity: 0;
}

.bwg1p8b-i {
  stop-color: var(--svg-color--9d7b70, #9D7B70);
}

.csio_zwnn {
  stop-color: var(--svg-color--502c20, #502C20);
  stop-opacity: 0;
}

.d5xlfib-d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M18.989 17.11c1.201 0 3.21 0 3.946.944c1.075 1.052 1.137 2.589 1.198 3.009");
}

.dvyrp5bps {
  stop-color: var(--svg-color--916855, #916855);
}

.e28y277by {
  stop-color: var(--svg-color--5b3225, #5B3225);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etvdl-b6n {
  stop-color: var(--svg-color--79504d, #79504D);
}

.eucwrjbls {
  stop-color: var(--svg-color--78524d, #78524D);
}

.eujq7sx2e {
  stop-color: var(--svg-color--733e5b, #733E5B);
}

.fer4c4bif {
  fill: var(--svg-color--4b2333, #4B2333);
  d: path("M7.323 16.103c0-1.057.843-1.844 1.914-1.913c.996-.048 1.986.563 2.07 1.776l.165 2.303c.083 1.155-.994 2.137-2.153 2.137a1.996 1.996 0 0 1-1.996-1.995z");
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g6d_tnb9l {
  fill: var(--svg-color--4b2333, #4B2333);
  d: path("M14.758 18.875c0-1.433 1.124-2.594 2.512-2.594l2.315.11c.346.042.69.14 1.008.288c1.91.805 3.389 2.644 3.68 4.805h-6.585a3 3 0 0 0-.313-.015h-.105c-1.388 0-2.512-1.162-2.512-2.594");
}

.g7tzf_b0v {
  stop-color: var(--svg-color--654034, #654034);
}

.gm2wbfbbj {
  stop-color: var(--svg-color--513024, #513024);
  stop-opacity: 0;
}

.gxydj6bhi {
  stop-color: var(--svg-color--744158, #744158);
}

.ha9pd0-sq {
  width: 1.936px;
  height: 5.303px;
  x: 12.867px;
  y: 11.807px;
  rx: 0.968px;
}

.hlxiqjbdk {
  stop-color: var(--svg-color--51252d, #51252D);
  stop-opacity: 0;
}

.inh5-xb7q {
  d: path("M10.532 13.502a2.636 2.636 0 0 1 5.272 0v3.447a2.636 2.636 0 0 1-2.636 2.636c-1.456 0-2.424-.756-2.424-2.345z");
}

.klh24zbqk {
  stop-color: var(--svg-color--a17e70, #A17E70);
}

.kqlyp1brb {
  stop-color: var(--svg-color--704651, #704651);
  stop-opacity: 0;
}

.kxq4jkutd {
  stop-color: var(--svg-color--8f695a, #8F695A);
}

.ml8zr5ilx {
  stop-color: var(--svg-color--6a443d, #6A443D);
}

.mp7-bha1d {
  d: path("M15.662 13.008c0-1.574 1.212-2.85 2.707-2.85s2.707 1.276 2.707 2.85v3.727c0 1.574-1.212 2.85-2.707 2.85s-2.707-.732-2.707-2.45z");
}

.n0bwn6bue {
  stop-color: var(--svg-color--8d6350, #8D6350);
}

.n1i303bed {
  stop-color: var(--svg-color--654034, #654034);
  stop-opacity: 0;
}

.ntobp_bki {
  fill: var(--svg-color--4b2333, #4B2333);
  d: path("M11.175 15.658c0-1.294 1.08-2.343 2.412-2.343c1.333 0 2.413 1.049 2.413 2.343v3.062c0 1.294-1.08 2.343-2.413 2.343s-2.218-.672-2.218-2.084z");
}

.nunphccoi {
  stop-color: var(--svg-color--84555e, #84555E);
  stop-opacity: 0;
}

.qot0pwbpf {
  stop-color: var(--svg-color--734e46, #734E46);
}

.qvnsdsxex {
  stop-color: var(--svg-color--9d7b70, #9D7B70);
  stop-opacity: 0;
}

.r7udrlbjv {
  stop-color: var(--svg-color--704651, #704651);
}

.rnex3kbdo {
  stop-color: var(--svg-color--5b3225, #5B3225);
}

.s4ow685hd {
  stop-color: var(--svg-color--51252d, #51252D);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.t7i74zl-e {
  stop-color: var(--svg-color--997265, #997265);
}

.ter92bcdr {
  stop-color: var(--svg-color--6e413b, #6E413B);
}

.toyule75s {
  d: path("M18.27 15.281c-1.388 0-2.512 1.161-2.512 2.594s1.124 2.594 2.512 2.594h.105c.821 0 1.64.317 2.067 1.02a6 6 0 0 1 .874 3.136c0 .878-.186 1.712-.521 2.463c2.598-.625 4.531-2.995 4.531-5.822c0-2.492-1.597-4.686-3.733-5.587a3.4 3.4 0 0 0-1.008-.288z");
}

.ului_hb8y {
  stop-color: var(--svg-color--997265, #997265);
  stop-opacity: 0;
}

.v8vydcq5h {
  stop-color: var(--svg-color--84555e, #84555E);
}

.vc4wpn4vp {
  width: 1.722px;
  height: 4.231px;
  x: 8.302px;
  y: 14.061px;
  fill: var(--svg-color--9f7c73, #9F7C73);
  rx: 0.861px;
}

.vm5g7qe5w {
  width: 1.945px;
  height: 6.02px;
  x: 18.129px;
  y: 11.489px;
  fill: var(--svg-color--a68174, #A68174);
  rx: 0.973px;
}

.vu2f16bpy {
  d: path("M23.136 1.906a2.656 2.656 0 0 0-2.656 2.657v11.25H5.684v4.227c0 5.553 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.347l.003.003c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.563a2.656 2.656 0 0 0-2.657-2.657");
}

.w0n6qib0c {
  width: 1.688px;
  height: 11.594px;
  x: 23.195px;
  y: 3.531px;
  fill: var(--svg-color--a27e71, #A27E71);
  rx: 0.844px;
}

.w5sbs8nfi {
  stop-color: var(--svg-color--713a54, #713A54);
}

.wd1nypbbl {
  stop-color: var(--svg-color--906c5b, #906C5B);
}

.wwi4mebsv {
  stop-color: var(--svg-color--653e2f, #653E2F);
}

.x32ai7b6d {
  d: path("M5.684 14.6c0-1.382 1.102-2.412 2.503-2.502c1.302-.063 2.596.735 2.707 2.323l.215 3.013c.108 1.51-1.3 2.796-2.815 2.796a2.61 2.61 0 0 1-2.61-2.61z");
}

.xd37muika {
  stop-color: var(--svg-color--733e5b, #733E5B);
  stop-opacity: 0;
}

.xrdcusbnk {
  stop-color: var(--svg-color--a47f73, #A47F73);
  stop-opacity: 0;
}

.xt5uxkbgn {
  stop-color: var(--svg-color--6a443d, #6A443D);
  stop-opacity: 0;
}

.y67e99jat {
  stop-color: var(--svg-color--744158, #744158);
  stop-opacity: 0;
}

.za8-v5r8c {
  stop-color: var(--svg-color--513024, #513024);
}

.zay_9p1oa {
  stop-color: var(--svg-color--a17e70, #A17E70);
  stop-opacity: 0;
}

.zm8xf8bwb {
  stop-color: var(--svg-color--713a54, #713A54);
  stop-opacity: 0;
}

</style>
