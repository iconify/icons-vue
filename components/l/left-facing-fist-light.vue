<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5gMbFe)" class="xzqkqgrsz"/><path fill="url(#ii0OK5j)" class="xzqkqgrsz"/><g filter="url(#iUdFJKd)"><path fill="url(#ivNIwbc)" class="ilosvxboq"/></g><g clip-rule="evenodd" filter="url(#i8KMWud)" class="d2kvgvbvc"><path fill="url(#ismgi3d)" class="g7e8aablc"/><path fill="url(#iz2Fstc)" class="g7e8aablc"/></g><path fill="url(#iVnWdse)" clip-rule="evenodd" class="q68v-7b3u"/><path fill="url(#iSeNYTb)" clip-rule="evenodd" class="q68v-7b3u"/><path fill="url(#icRpAhb)" class="l6l-1byuh"/><path fill="url(#iPvrcDc)" class="l6l-1byuh"/><path fill="url(#idPEHid)" class="l6l-1byuh"/><path fill="url(#icRpAhb)" class="yav56ob9d"/><path fill="url(#iPvrcDc)" class="yav56ob9d"/><path fill="url(#idPEHid)" class="yav56ob9d"/><path fill="url(#iwkuOve)" class="y30sqtbzg"/><path fill="url(#iHtp8rd)" class="y30sqtbzg"/><path fill="url(#iMwx8zb)" class="y30sqtbzg"/><path fill="url(#iALbAKe)" class="y30sqtbzg"/><g filter="url(#i36N1Rd)"><path fill="url(#iePIEpc)" class="ob4q8w1qm"/><path fill="url(#icpsoRc)" class="ob4q8w1qm"/></g><g filter="url(#iQgl5Ee)"><path fill="url(#iRvzMVb)" class="o0xyil93m"/></g><g filter="url(#i16l1ye)"><path stroke="url(#iUx6Vfe)" class="ug9j6ob3t"/></g><defs><radialGradient id="i5gMbFe" cx="0" cy="0" r="1" gradientTransform="rotate(-152.154 10.121 8.147)scale(5.41069 4.24838)" gradientUnits="userSpaceOnUse"><stop class="onb16fbbl"/><stop offset="1" class="cxa-avsml"/></radialGradient><radialGradient id="ii0OK5j" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78125 -4.67188 0 13.977 17.378)" gradientUnits="userSpaceOnUse"><stop class="r84ypn4bn"/><stop offset="1" class="iguuhjbui"/></radialGradient><radialGradient id="ivNIwbc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.97793 -2.31968 2.07476 -2.66352 13.428 22.674)" gradientUnits="userSpaceOnUse"><stop class="leg7ltzbf"/><stop offset="1" class="rapchz6jy"/></radialGradient><radialGradient id="ismgi3d" cx="0" cy="0" r="1" gradientTransform="matrix(-16.07307 10.95896 -7.9909 -11.71994 26.013 10)" gradientUnits="userSpaceOnUse"><stop class="ovy1v8_tl"/><stop offset="1" class="m_979ebac"/></radialGradient><radialGradient id="iz2Fstc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68909 6.7081 -5.46182 -4.63213 23.914 17.88)" gradientUnits="userSpaceOnUse"><stop class="t0lk-t-xf"/><stop offset="1" class="k9h_v7bop"/></radialGradient><radialGradient id="icRpAhb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37548 0 0 -3.04657 14.21 22.948)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="jzllaejwd"/><stop offset="1" class="z7px7cbix"/></radialGradient><radialGradient id="iPvrcDc" cx="0" cy="0" r="1" gradientTransform="matrix(.72908 9.08535 -10.30019 .82656 8.502 17.704)" gradientUnits="userSpaceOnUse"><stop offset=".602" class="q_5b96a5f"/><stop offset="1" class="x89q4zbnq"/></radialGradient><radialGradient id="idPEHid" cx="0" cy="0" r="1" gradientTransform="rotate(127.504 .218 13.7)scale(1.69385 1.72441)" gradientUnits="userSpaceOnUse"><stop class="ryzwjubdo"/><stop offset="1" class="jxm6p95xq"/></radialGradient><radialGradient id="iwkuOve" cx="0" cy="0" r="1" gradientTransform="matrix(8.26407 -6.87499 3.7143 4.46477 11.564 32.39)" gradientUnits="userSpaceOnUse"><stop class="tdjaugc4v"/><stop offset="1" class="m4d4zew3y"/></radialGradient><radialGradient id="iHtp8rd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5111 -4.12637 6.08513 -2.2284 22.204 26.954)" gradientUnits="userSpaceOnUse"><stop class="g5scszrmo"/><stop offset="1" class="jamy06b-n"/></radialGradient><radialGradient id="iMwx8zb" cx="0" cy="0" r="1" gradientTransform="matrix(2.33508 -1.82561 .80542 1.03018 27.268 21.277)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="q_bj6sb1p"/><stop offset="1" class="yc-gxpyjg"/></radialGradient><radialGradient id="iALbAKe" cx="0" cy="0" r="1" gradientTransform="matrix(-14.15639 7.36966 -8.34555 -16.03098 23.28 20.953)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="h1ojt3b7b"/><stop offset="1" class="v5v_gabuy"/></radialGradient><radialGradient id="iePIEpc" cx="0" cy="0" r="1" gradientTransform="matrix(6.0699 -6.28102 11.12402 10.7501 9.444 18.856)" gradientUnits="userSpaceOnUse"><stop class="kml_gpgmh"/><stop offset=".156" class="iuh4pqidl"/><stop offset="1" class="cdiqf4mcs"/></radialGradient><radialGradient id="icpsoRc" cx="0" cy="0" r="1" gradientTransform="matrix(.21108 -7.2311 16.99666 .49614 10.817 18.961)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="hwif3mb0s"/><stop offset=".571" class="m1y68wbxs"/></radialGradient><filter id="iUdFJKd" width="8.636" height="7.547" x="6.711" y="16.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.341176 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3270"/></filter><filter id="i8KMWud" width="29.391" height="22.545" x="2.055" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.682353 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3270"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.639216 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3270" result="effect2_innerShadow_20020_3270"/></filter><filter id="i36N1Rd" width="17.949" height="11.368" x="2.479" y="8.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3270" stdDeviation="1.25"/></filter><filter id="iQgl5Ee" width="5.916" height="11.3" x="3.441" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3270" stdDeviation=".75"/></filter><filter id="i16l1ye" width="10.331" height="10.026" x="12.799" y="18.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3270" stdDeviation="1"/></filter><linearGradient id="iVnWdse" x1="16.994" x2="16" y1="6.162" y2="11.937" gradientUnits="userSpaceOnUse"><stop class="h1c3298fx"/><stop offset="1" class="q23ofie8z"/></linearGradient><linearGradient id="iSeNYTb" x1="2.055" x2="2.814" y1="16.052" y2="16.052" gradientUnits="userSpaceOnUse"><stop class="c5x5l1b9a"/><stop offset="1" class="qxkgj14re"/></linearGradient><linearGradient id="iRvzMVb" x1="4.941" x2="8.062" y1="17.62" y2="17.62" gradientUnits="userSpaceOnUse"><stop class="npa3cp-du"/><stop offset="1" class="dh_ab1bus"/></linearGradient><linearGradient id="iUx6Vfe" x1="15.424" x2="19.945" y1="25.63" y2="21.057" gradientUnits="userSpaceOnUse"><stop class="kxj84ccvl"/><stop offset="1" class="jgec3ixja"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:left-facing-fist-light" /></template>
<style>
.c5x5l1b9a {
  stop-color: var(--svg-color--edb59c, #EDB59C);
}

.cdiqf4mcs {
  stop-color: var(--svg-color--cd9087, #CD9087);
  stop-opacity: 0;
}

.cxa-avsml {
  stop-color: var(--svg-color--9d5745, #9D5745);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dh_ab1bus {
  stop-color: var(--svg-color--ffcbb6, #FFCBB6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5scszrmo {
  stop-color: var(--svg-color--be859b, #BE859B);
}

.g7e8aablc {
  d: path("M7.555 8a5.5 5.5 0 0 0-5.5 5.5v5.625h.004v.398c-.01.724.205 2.58 1.043 3.805c1.046 1.531 2.859 2.75 4.64 2.75h2.104c-.075.28-.102.573-.134.921l-.001.017c0 1.023.437 2.562 2.64 3c.985.148 2-.274 2.829-.93a95 95 0 0 0 1.961-1.64l.703-.594l.129-.11c.357-.31.862-.747 1.472-.789c.835-.058 2.42-.38 4.352-2.219c.78-.742 1.4-1.748 1.755-2.322c.093-.15.167-.271.221-.35q.08-.116.138-.212c.235-.374.328-.522 1.331-.522l-.007-.008h.71a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2zm7.302 12.3c.273-.474.686-1.272.87-1.917c.273-.961-.24-1.071-.485-1.117c-.37-.07-.942-.062-1.536-.053q-.303.005-.604.006q-.357 0-.758.005c-1.227.012-2.667.026-3.399-.193c-.133.065-.398.317-.398.805v.1c-.002.582-.004 1.208.476 1.533c.178.12.531.147.965.18c.487.036 1.075.08 1.631.273h.002l.062.023c.245.09.482.21.701.373a3.33 3.33 0 0 1 1.228 1.743c.701-.82 1.131-1.54 1.228-1.752z");
}

.h1c3298fx {
  stop-color: var(--svg-color--ffd4b5, #FFD4B5);
}

.h1ojt3b7b {
  stop-color: var(--svg-color--e6ae9b, #E6AE9B);
  stop-opacity: 0;
}

.hwif3mb0s {
  stop-color: var(--svg-color--b06d65, #B06D65);
}

.iguuhjbui {
  stop-color: var(--svg-color--985340, #985340);
  stop-opacity: 0;
}

.ilosvxboq {
  d: path("M9.692 18.761a4.8 4.8 0 0 1 .066-1.823H6.96v7.296h6.703c1.078 0 1.899-1.609 1.633-2.843c-.266-1.235-1.432-2.277-2.711-2.203c-.963.055-1.893.016-2.524-.074a.43.43 0 0 1-.37-.353");
}

.iuh4pqidl {
  stop-color: var(--svg-color--cd9087, #CD9087);
}

.jamy06b-n {
  stop-color: var(--svg-color--be859b, #BE859B);
  stop-opacity: 0;
}

.jgec3ixja {
  stop-color: var(--svg-color--ffe4ca, #FFE4CA);
  stop-opacity: 0;
}

.jxm6p95xq {
  stop-color: var(--svg-color--ebb7a1, #EBB7A1);
  stop-opacity: 0;
}

.jzllaejwd {
  stop-color: var(--svg-color--b27262, #B27262);
}

.k9h_v7bop {
  stop-color: var(--svg-color--ffe8cc, #FFE8CC);
  stop-opacity: 0;
}

.kml_gpgmh {
  stop-color: var(--svg-color--d49387, #D49387);
}

.kxj84ccvl {
  stop-color: var(--svg-color--ffe4ca, #FFE4CA);
}

.l6l-1byuh {
  d: path("M2.055 17.063v2.062h.004v.398c-.01.724.205 2.58 1.043 3.805c.818 1.198 2.105 2.204 3.479 2.586c.372.1.75.155 1.126.155h2.141c.082-.293.328-.887.968-1.465c.116-.111.341-.3.62-.531c.692-.578 1.642-1.268 2.181-2.007c-.141-.47-.509-1.23-1.233-1.747a2.8 2.8 0 0 0-.763-.397h-.002c-.556-.193-1.144-.237-1.631-.274c-.434-.032-.787-.059-.965-.18c-.48-.324-.478-.95-.476-1.532v-.1c0-.43.206-.676.346-.773z");
}

.leg7ltzbf {
  stop-color: var(--svg-color--af6f64, #AF6F64);
}

.m_979ebac {
  stop-color: var(--svg-color--efbba4, #EFBBA4);
}

.m1y68wbxs {
  stop-color: var(--svg-color--b06d65, #B06D65);
  stop-opacity: 0;
}

.m4d4zew3y {
  stop-color: var(--svg-color--b76f8f, #B76F8F);
  stop-opacity: 0;
}

.npa3cp-du {
  stop-color: var(--svg-color--ffcbb6, #FFCBB6);
}

.o0xyil93m {
  d: path("M7.857 19.611v-3.085L4.941 13.47v8.3z");
}

.ob4q8w1qm {
  d: path("m4.979 10.663l3.99 6.029c1.083.445 5.095.106 5.647.148c.442.034.75.142.85.191l2.462-6.368z");
}

.onb16fbbl {
  stop-color: var(--svg-color--a7645d, #A7645D);
}

.ovy1v8_tl {
  stop-color: var(--svg-color--ffe1c3, #FFE1C3);
}

.q_5b96a5f {
  stop-color: var(--svg-color--b7778c, #B7778C);
  stop-opacity: 0;
}

.q_bj6sb1p {
  stop-color: var(--svg-color--b78399, #B78399);
}

.q23ofie8z {
  stop-color: var(--svg-color--ffd4b5, #FFD4B5);
  stop-opacity: 0;
}

.q68v-7b3u {
  fill-rule: evenodd;
  d: path("M7.555 8a5.5 5.5 0 0 0-5.5 5.5v5.625h.004v.398c-.01.724.205 2.58 1.043 3.805c1.046 1.531 2.859 2.75 4.64 2.75h2.104c-.075.28-.102.573-.134.921l-.001.017c0 1.023.437 2.562 2.64 3c.985.148 2-.274 2.829-.93a95 95 0 0 0 1.961-1.64l.703-.594l.129-.11c.357-.31.862-.747 1.472-.789c.835-.058 2.42-.38 4.352-2.219c.78-.742 1.4-1.748 1.755-2.322c.093-.15.167-.271.221-.35q.08-.116.138-.212c.235-.374.328-.522 1.331-.522l-.007-.008h.71a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2zm7.302 12.3c.273-.474.686-1.272.87-1.917c.273-.961-.24-1.071-.485-1.117c-.37-.07-.942-.062-1.536-.053q-.303.005-.604.006q-.357 0-.758.005c-1.227.012-2.667.026-3.399-.193c-.133.065-.398.317-.398.805v.1c-.002.582-.004 1.208.476 1.533c.178.12.531.147.965.18c.487.036 1.075.08 1.631.273h.002l.062.023c.245.09.482.21.701.373a3.33 3.33 0 0 1 1.228 1.743c.701-.82 1.131-1.54 1.228-1.752z");
}

.qxkgj14re {
  stop-color: var(--svg-color--edb59c, #EDB59C);
  stop-opacity: 0;
}

.r84ypn4bn {
  stop-color: var(--svg-color--985340, #985340);
}

.rapchz6jy {
  stop-color: var(--svg-color--a76551, #A76551);
}

.ryzwjubdo {
  stop-color: var(--svg-color--ebb7a1, #EBB7A1);
}

.t0lk-t-xf {
  stop-color: var(--svg-color--ffe8cc, #FFE8CC);
}

.tdjaugc4v {
  stop-color: var(--svg-color--bd7e94, #BD7E94);
}

.ug9j6ob3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.424 25.63l5.08-4.776");
}

.v5v_gabuy {
  stop-color: var(--svg-color--e6ae9b, #E6AE9B);
}

.x89q4zbnq {
  stop-color: var(--svg-color--b7778c, #B7778C);
}

.xzqkqgrsz {
  d: path("M7.836 16.096h9.563v7.109H7.836z");
}

.y30sqtbzg {
  d: path("M13.707 14.771h16.238v3.55a2 2 0 0 1-2 2h-.71l.007.007a5 5 0 0 0-.526.021c-.357.036-.516.12-.64.262c-.057.067-.106.146-.165.24q-.058.096-.138.212a7 7 0 0 0-.171.268l-.05.081c-.354.574-.975 1.58-1.755 2.322c-1.932 1.84-3.517 2.161-4.352 2.22c-.61.041-1.115.478-1.472.787l-.13.11l-.702.596a95 95 0 0 1-1.961 1.639c-.828.656-1.844 1.078-2.828.93c-2.204-.438-2.641-1.977-2.641-3l.001-.017c.109-1.191.157-1.725 2.304-3.397a11.6 11.6 0 0 0 2.061-2.119c.427-.564.69-1.014.763-1.174l.017-.01c.273-.473.686-1.27.87-1.916c.273-.961-.24-1.07-.485-1.117c-.37-.07-.941-.062-1.535-.053z");
}

.yav56ob9d {
  d: path("m9.061 17.063l.036.008l-.011-.009z");
}

.yc-gxpyjg {
  stop-color: var(--svg-color--b78399, #B78399);
  stop-opacity: 0;
}

.z7px7cbix {
  stop-color: var(--svg-color--b27262, #B27262);
  stop-opacity: 0;
}

</style>
