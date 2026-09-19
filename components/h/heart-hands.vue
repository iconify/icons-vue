<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i06PUOk)" class="d2kvgvbvc"><path fill="url(#iz64eQd)" class="vlrp0sb4o"/><path fill="url(#iw7WhFb)" class="vlrp0sb4o"/></g><g filter="url(#iXWlEdc)"><path class="b5wh7t32v"/><path fill="url(#ic655ld)" class="f0hy8z89m"/><path fill="url(#i08gbEb)" class="f0hy8z89m"/><path fill="url(#ittq2ce)" class="f0hy8z89m"/></g><path clip-rule="evenodd" class="a77423b-y"/><path fill="url(#iyeStJC)" clip-rule="evenodd" class="ll5z8_jbf"/><path fill="url(#ihCBQEd)" clip-rule="evenodd" class="ll5z8_jbf"/><g filter="url(#ioNeGIc)"><path class="giif2rbkz"/></g><g filter="url(#iH8dEqB)"><path stroke="url(#idYGzsb)" class="mq8hv6blr"/></g><g filter="url(#ieq8Ryd)"><path stroke="url(#ivG6PAe)" class="kxa3dybww"/></g><g filter="url(#iODMpVd)"><path stroke="url(#iNG0Ntc)" class="wm1f61b_p"/></g><g filter="url(#icB3qbe)"><path stroke="url(#inV0u6d)" class="yv6_67sif"/></g><defs><radialGradient id="iz64eQd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.34381 6.31243 -6.97483 -9.21937 14.969 11.406)" gradientUnits="userSpaceOnUse"><stop class="fnmzzppts"/><stop offset="1" class="cqhoskb0n"/></radialGradient><radialGradient id="iw7WhFb" cx="0" cy="0" r="1" gradientTransform="rotate(123.476 .716 10.133)scale(4.64565 3.41798)" gradientUnits="userSpaceOnUse"><stop offset=".497" class="tibitla2j"/><stop offset="1" class="q4alg44hw"/></radialGradient><radialGradient id="ic655ld" cx="0" cy="0" r="1" gradientTransform="matrix(-7.375 -2.42806 1.75385 -5.32716 14.75 29.803)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="sf07l7umz"/><stop offset="1" class="xli795nyd"/></radialGradient><radialGradient id="i08gbEb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.919 14.291 8.66)scale(6.46664 2.55443)" gradientUnits="userSpaceOnUse"><stop class="rp47rsbhd"/><stop offset="1" class="hd9wgoeca"/></radialGradient><radialGradient id="ittq2ce" cx="0" cy="0" r="1" gradientTransform="rotate(132.013 3.793 11.161)scale(5.08924 3.88381)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="k2ay_tffl"/><stop offset="1" class="ijzc0be1w"/></radialGradient><radialGradient id="iyeStJC" cx="0" cy="0" r="1" gradientTransform="matrix(-10.37497 -9.90623 3.07089 -3.2162 26.938 16.656)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="bj4_ow3-r"/><stop offset="1" class="u28jkyopl"/></radialGradient><radialGradient id="ihCBQEd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 3.5 -1.5575 1.22374 22.781 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="tppfvyb7w"/><stop offset="1" class="nelidxbhk"/></radialGradient><radialGradient id="ivG6PAe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.37496 4.62505 -3.3986 -4.68448 30.844 19.438)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="shq45--je"/><stop offset="1" class="kwr2t4bui"/></radialGradient><filter id="i06PUOk" width="11.192" height="9.903" x="4.983" y="9.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.662745 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7181"/></filter><filter id="iXWlEdc" width="16.457" height="19.582" x="1.897" y="10.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.639216 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7181" result="effect2_innerShadow_20020_7181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.521569 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_7181" result="effect3_innerShadow_20020_7181"/></filter><filter id="ioNeGIc" width="16.457" height="19.582" x="13.825" y="10.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.639216 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7181" result="effect2_innerShadow_20020_7181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.521569 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_7181" result="effect3_innerShadow_20020_7181"/></filter><filter id="iH8dEqB" width="9.25" height="8.72" x="17.031" y="10.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7181" stdDeviation=".5"/></filter><filter id="ieq8Ryd" width="6.406" height="11.906" x="23.781" y="16.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7181" stdDeviation=".5"/></filter><filter id="iODMpVd" width="8.094" height="7.844" x="13.469" y="21.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7181" stdDeviation=".5"/></filter><filter id="icB3qbe" width="9.398" height="10.094" x="6.427" y="17.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7181" stdDeviation=".5"/></filter><linearGradient id="idYGzsb" x1="24.281" x2="15.375" y1="17.156" y2="11.219" gradientUnits="userSpaceOnUse"><stop class="shq45--je"/><stop offset="1" class="kwr2t4bui"/></linearGradient><linearGradient id="iNG0Ntc" x1="15.906" x2="19.499" y1="28.094" y2="22.981" gradientUnits="userSpaceOnUse"><stop class="twmptbbnk"/><stop offset="1" class="w1cjmjs8m"/></linearGradient><linearGradient id="inV0u6d" x1="11.688" x2="9.817" y1="19.688" y2="24.428" gradientUnits="userSpaceOnUse"><stop class="vzuf8c4vc"/><stop offset="1" class="kwr2t4bui"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:heart-hands" /></template>
<style>
.a77423b-y {
  fill: var(--svg-color--e8b12d, #E8B12D);
  fill-rule: evenodd;
  d: path("M21.141 14.519c-.749-.46-1.716-.382-2.349-.065a2.1 2.1 0 0 1-1.878-3.757c1.62-.81 4.17-1.141 6.424.242c3.087 1.895 3.357 4.894 3.357 6.859a2.1 2.1 0 1 1-4.2 0c0-1.637-.24-2.596-1.354-3.28");
}

.b5wh7t32v {
  fill: var(--svg-color--ffc34c, #FFC34C);
  d: path("m14.151 15.998l-.014-.015l-.045-.042a2 2 0 0 0-.158-.124a2.3 2.3 0 0 0-.49-.258a1.9 1.9 0 0 0-1.248-.052c-.975.295-1.535 1.074-1.895 2.208c-.16.897-.145 2.622.676 3.433c.24.27.764.61 1.435 1.046c1.412.918 3.475 2.26 4.936 4.251c1.044 1.331.095 2.741-.423 3.024c-.72.392-1.528.54-2.367-.125c-.838-.666-2.18-1.623-3.636-1.367s-2.03.351-2.88.351H3.697a1.8 1.8 0 0 1-1.8-1.8v-4.512c0-1.957 1.231-4.44 3.197-5.123c.638-.221 1.243-.634 1.5-1.258c.682-1.648 1.943-3.41 4.389-4.148c2.983-.901 5.437.691 6.373 1.796a2.1 2.1 0 0 1-3.204 2.715");
}

.bj4_ow3-r {
  stop-color: var(--svg-color--ffeb63, #FFEB63);
}

.cqhoskb0n {
  stop-color: var(--svg-color--fdb046, #FDB046);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.f0hy8z89m {
  d: path("m14.151 15.998l-.014-.015l-.045-.042a2 2 0 0 0-.158-.124a2.3 2.3 0 0 0-.49-.258a1.9 1.9 0 0 0-1.248-.052c-.975.295-1.535 1.074-1.895 2.208c-.16.897-.145 2.622.676 3.433c.24.27.764.61 1.435 1.046c1.412.918 3.475 2.26 4.936 4.251c1.044 1.331.095 2.741-.423 3.024c-.72.392-1.528.54-2.367-.125c-.838-.666-2.18-1.623-3.636-1.367s-2.03.351-2.88.351H3.697a1.8 1.8 0 0 1-1.8-1.8v-4.512c0-1.957 1.231-4.44 3.197-5.123c.638-.221 1.243-.634 1.5-1.258c.682-1.648 1.943-3.41 4.389-4.148c2.983-.901 5.437.691 6.373 1.796a2.1 2.1 0 0 1-3.204 2.715");
}

.fnmzzppts {
  stop-color: var(--svg-color--fcd038, #FCD038);
}

.ft5dv1b6b {
  fill: none;
}

.giif2rbkz {
  fill: var(--svg-color--ffc34c, #FFC34C);
  d: path("m17.527 15.998l.014-.015l.045-.042q.058-.054.157-.124c.134-.093.3-.186.49-.258a1.9 1.9 0 0 1 1.249-.052c.975.295 1.535 1.074 1.895 2.208c.16.897.145 2.622-.676 3.433c-.24.27-.765.61-1.436 1.046c-1.41.918-3.475 2.26-4.935 4.251c-1.044 1.331-.095 2.741.423 3.024c.719.392 1.528.54 2.366-.125c.84-.666 2.182-1.623 3.637-1.367s2.03.351 2.88.351h4.345a1.8 1.8 0 0 0 1.8-1.8v-4.512c0-1.957-1.23-4.44-3.197-5.123c-.637-.221-1.242-.634-1.5-1.258c-.681-1.648-1.942-3.41-4.388-4.148c-2.983-.901-5.437.691-6.373 1.796a2.1 2.1 0 1 0 3.204 2.715");
}

.hd9wgoeca {
  stop-color: var(--svg-color--d49637, #D49637);
  stop-opacity: 0;
}

.ijzc0be1w {
  stop-color: var(--svg-color--ed8c50, #ED8C50);
  stop-opacity: 0;
}

.k2ay_tffl {
  stop-color: var(--svg-color--ed8c50, #ED8C50);
}

.kwr2t4bui {
  stop-color: var(--svg-color--ffe660, #FFE660);
  stop-opacity: 0;
}

.kxa3dybww {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M25.781 18.125c.802.375 2.407 1.637 2.407 3.688v4.218");
}

.ll5z8_jbf {
  fill-rule: evenodd;
  d: path("M21.141 14.519c-.749-.46-1.716-.382-2.349-.065a2.1 2.1 0 0 1-1.878-3.757c1.62-.81 4.17-1.141 6.424.242c3.087 1.895 3.357 4.894 3.357 6.859a2.1 2.1 0 1 1-4.2 0c0-1.637-.24-2.596-1.354-3.28");
}

.mq8hv6blr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.031 12.438c1.375-.042 4.275.843 5.25 4.718");
}

.nelidxbhk {
  stop-color: var(--svg-color--fec731, #FEC731);
  stop-opacity: 0;
}

.q4alg44hw {
  stop-color: var(--svg-color--efa128, #EFA128);
  stop-opacity: 0;
}

.rp47rsbhd {
  stop-color: var(--svg-color--d49637, #D49637);
}

.sf07l7umz {
  stop-color: var(--svg-color--fd985b, #FD985B);
}

.shq45--je {
  stop-color: var(--svg-color--ffe660, #FFE660);
}

.tibitla2j {
  stop-color: var(--svg-color--efa128, #EFA128);
}

.tppfvyb7w {
  stop-color: var(--svg-color--fec731, #FEC731);
}

.twmptbbnk {
  stop-color: var(--svg-color--ffc452, #FFC452);
}

.u28jkyopl {
  stop-color: var(--svg-color--ffeb63, #FFEB63);
  stop-opacity: 0;
}

.vlrp0sb4o {
  d: path("M10.537 14.519c.749-.46 1.716-.382 2.348-.065a2.1 2.1 0 0 0 1.879-3.757c-1.62-.81-4.17-1.141-6.424.242c-3.087 1.895-3.357 4.894-3.357 6.859a2.1 2.1 0 1 0 4.2 0c0-1.637.24-2.596 1.354-3.28");
}

.vzuf8c4vc {
  stop-color: var(--svg-color--ffd454, #FFD454);
}

.w1cjmjs8m {
  stop-color: var(--svg-color--ffc452, #FFC452);
  stop-opacity: 0;
}

.wm1f61b_p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.469 27.781c.52-.854 2.493-2.668 4.094-3.843");
}

.xli795nyd {
  stop-color: var(--svg-color--fd985b, #FD985B);
  stop-opacity: 0;
}

.yv6_67sif {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.45 19.031c-.105.802.093 2.607 1.718 3.407c1.676 1.062 3.115 2.125 3.657 2.687");
}

</style>
