<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ib7Zkib)" class="xzqkqgrsz"/><path fill="url(#i5ab9Vd)" class="xzqkqgrsz"/><path fill="url(#iQ8Vf8b)" class="ilosvxboq"/><g clip-rule="evenodd" filter="url(#iaPx2HI)" class="d2kvgvbvc"><path fill="url(#iAgVKve)" class="g7e8aablc"/><path fill="url(#irV69hU)" class="g7e8aablc"/></g><path fill="url(#i96fQcd)" clip-rule="evenodd" class="q68v-7b3u"/><path fill="url(#igrgQDw)" class="l6l-1byuh"/><path fill="url(#iDuluBb)" class="l6l-1byuh"/><path fill="url(#ia8rXTH)" class="l6l-1byuh"/><path fill="url(#igrgQDw)" class="yav56ob9d"/><path fill="url(#iDuluBb)" class="yav56ob9d"/><path fill="url(#ia8rXTH)" class="yav56ob9d"/><path fill="url(#irgJwZd)" class="uvh2l3b_g"/><path fill="url(#icyhNde)" class="uvh2l3b_g"/><path fill="url(#iAcPbfV)" class="uvh2l3b_g"/><path fill="url(#ioa8YRd)" class="uvh2l3b_g"/><g filter="url(#iWKgiEe)"><path fill="url(#i1r8MAc)" class="ob4q8w1qm"/></g><g filter="url(#isqKTrT)"><path fill="url(#ia8gTSd)" class="o0xyil93m"/></g><g filter="url(#iTy5RIa)"><path stroke="url(#ilcA7MJ)" class="ug9j6ob3t"/></g><defs><radialGradient id="ib7Zkib" cx="0" cy="0" r="1" gradientTransform="rotate(-152.154 10.121 8.147)scale(5.41069 4.24838)" gradientUnits="userSpaceOnUse"><stop class="efc85_53z"/><stop offset="1" class="j7uccabzz"/></radialGradient><radialGradient id="i5ab9Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78125 -4.67188 0 13.977 17.378)" gradientUnits="userSpaceOnUse"><stop class="tubjn2bip"/><stop offset="1" class="cqriijcmc"/></radialGradient><radialGradient id="iQ8Vf8b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.97793 -2.31968 2.07476 -2.66352 13.428 22.674)" gradientUnits="userSpaceOnUse"><stop class="xvzg_abgt"/><stop offset="1" class="nogyb-blk"/></radialGradient><radialGradient id="iAgVKve" cx="0" cy="0" r="1" gradientTransform="matrix(-16.07307 10.95896 -7.9909 -11.71994 26.013 10)" gradientUnits="userSpaceOnUse"><stop class="fgjvektso"/><stop offset="1" class="szjg1fb1r"/></radialGradient><radialGradient id="irV69hU" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68909 6.7081 -5.46182 -4.63213 23.914 17.88)" gradientUnits="userSpaceOnUse"><stop class="rg3n2_b4b"/><stop offset="1" class="dxyp9sb9a"/></radialGradient><radialGradient id="igrgQDw" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37548 0 0 -3.04657 14.21 22.948)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="dw5lw2z1e"/><stop offset="1" class="q8vevylxo"/></radialGradient><radialGradient id="iDuluBb" cx="0" cy="0" r="1" gradientTransform="matrix(.72908 9.08535 -10.30019 .82656 8.502 17.704)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="ptrirg6xc"/><stop offset="1" class="e2s5h_bgt"/></radialGradient><radialGradient id="ia8rXTH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34634 1.37173 -1.19847 -1.1763 11.283 22.556)" gradientUnits="userSpaceOnUse"><stop class="ovix1ebyr"/><stop offset="1" class="pih9qk2my"/></radialGradient><radialGradient id="irgJwZd" cx="0" cy="0" r="1" gradientTransform="matrix(3.05212 -3.15273 3.32482 3.21872 12.539 30.441)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="rg4k0nb5q"/><stop offset="1" class="ln7kki0yi"/></radialGradient><radialGradient id="icyhNde" cx="0" cy="0" r="1" gradientTransform="rotate(-116.147 19.652 6.518)scale(3.82937 5.64714)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ysytpib0b"/><stop offset="1" class="cp_3wfbrf"/></radialGradient><radialGradient id="iAcPbfV" cx="0" cy="0" r="1" gradientTransform="matrix(2.33508 -1.82561 .80542 1.03018 27.268 21.277)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="vhjvvxb2h"/><stop offset="1" class="oe1lqnr7n"/></radialGradient><radialGradient id="ioa8YRd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.46589 5.91432 -6.69746 -11.85172 19.59 22.408)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="csxetu56u"/><stop offset="1" class="dtuud4bgf"/></radialGradient><linearGradient id="i96fQcd" x1="16.994" x2="16" y1="6.162" y2="11.937" gradientUnits="userSpaceOnUse"><stop class="d7zzrtbax"/><stop offset="1" class="jxftj84gg"/></linearGradient><linearGradient id="i1r8MAc" x1="5.872" x2="18.653" y1="19.889" y2="11.984" gradientUnits="userSpaceOnUse"><stop class="kw7d_d-jx"/><stop offset="1" class="z2j_3qbhm"/></linearGradient><linearGradient id="ia8gTSd" x1="4.941" x2="8.062" y1="17.62" y2="17.62" gradientUnits="userSpaceOnUse"><stop class="h673f0b8e"/><stop offset="1" class="hwqn56bsj"/></linearGradient><linearGradient id="ilcA7MJ" x1="15.424" x2="19.945" y1="25.63" y2="21.057" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><filter id="iaPx2HI" width="28.891" height="22.545" x="2.055" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.129412 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3230"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.164706 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3230" result="effect2_innerShadow_20020_3230"/></filter><filter id="iWKgiEe" width="17.949" height="11.368" x="2.479" y="8.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3230" stdDeviation="1.25"/></filter><filter id="isqKTrT" width="5.916" height="11.3" x="3.441" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3230" stdDeviation=".75"/></filter><filter id="iTy5RIa" width="10.331" height="10.026" x="12.799" y="18.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3230" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:left-facing-fist-dark" /></template>
<style>
.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.cp_3wfbrf {
  stop-color: var(--svg-color--483146, #483146);
  stop-opacity: 0;
}

.cqriijcmc {
  stop-color: var(--svg-color--0d0404, #0D0404);
  stop-opacity: 0;
}

.csxetu56u {
  stop-color: var(--svg-color--574846, #574846);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d7zzrtbax {
  stop-color: var(--svg-color--584441, #584441);
}

.dtuud4bgf {
  stop-color: var(--svg-color--574846, #574846);
}

.dw5lw2z1e {
  stop-color: var(--svg-color--211212, #211212);
}

.dxyp9sb9a {
  stop-color: var(--svg-color--665150, #665150);
  stop-opacity: 0;
}

.e2s5h_bgt {
  stop-color: var(--svg-color--381d33, #381D33);
}

.efc85_53z {
  stop-color: var(--svg-color--331e21, #331E21);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.fgjvektso {
  stop-color: var(--svg-color--644d4a, #644D4A);
}

.ft5dv1b6b {
  fill: none;
}

.g7e8aablc {
  d: path("M7.555 8a5.5 5.5 0 0 0-5.5 5.5v5.625h.004v.398c-.01.724.205 2.58 1.043 3.805c1.046 1.531 2.859 2.75 4.64 2.75h2.104c-.075.28-.102.573-.134.921l-.001.017c0 1.023.437 2.562 2.64 3c.985.148 2-.274 2.829-.93a95 95 0 0 0 1.961-1.64l.703-.594l.129-.11c.357-.31.862-.747 1.472-.789c.835-.058 2.42-.38 4.352-2.219c.78-.742 1.4-1.748 1.755-2.322c.093-.15.167-.271.221-.35q.08-.116.138-.212c.235-.374.328-.522 1.331-.522l-.007-.008h.71a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2zm7.302 12.3c.273-.474.686-1.272.87-1.917c.273-.961-.24-1.071-.485-1.117c-.37-.07-.942-.062-1.536-.053q-.303.005-.604.006q-.357 0-.758.005c-1.227.012-2.667.026-3.399-.193c-.133.065-.398.317-.398.805v.1c-.002.582-.004 1.208.476 1.533c.178.12.531.147.965.18c.487.036 1.075.08 1.631.273h.002l.062.023c.245.09.482.21.701.373a3.33 3.33 0 0 1 1.228 1.743c.701-.82 1.131-1.54 1.228-1.752z");
}

.h673f0b8e {
  stop-color: var(--svg-color--523f3e, #523F3E);
}

.hwqn56bsj {
  stop-color: var(--svg-color--523f3e, #523F3E);
  stop-opacity: 0;
}

.ilosvxboq {
  d: path("M9.692 18.761a4.8 4.8 0 0 1 .066-1.823H6.96v7.296h6.703c1.078 0 1.899-1.609 1.633-2.843c-.266-1.235-1.432-2.277-2.711-2.203c-.963.055-1.893.016-2.524-.074a.43.43 0 0 1-.37-.353");
}

.j7uccabzz {
  stop-color: var(--svg-color--12080a, #12080A);
}

.jxftj84gg {
  stop-color: var(--svg-color--584441, #584441);
  stop-opacity: 0;
}

.kw7d_d-jx {
  stop-color: var(--svg-color--291418, #291418);
}

.l6l-1byuh {
  d: path("M2.055 17.063v2.062h.004v.398c-.01.724.205 2.58 1.043 3.805c.818 1.198 2.105 2.204 3.479 2.586c.372.1.75.155 1.126.155h2.141c.082-.293.328-.887.968-1.465c.116-.111.341-.3.62-.531c.692-.578 1.642-1.268 2.181-2.007c-.141-.47-.509-1.23-1.233-1.747a2.8 2.8 0 0 0-.763-.397h-.002c-.556-.193-1.144-.237-1.631-.274c-.434-.032-.787-.059-.965-.18c-.48-.324-.478-.95-.476-1.532v-.1c0-.43.206-.676.346-.773z");
}

.ln7kki0yi {
  stop-color: var(--svg-color--3f2238, #3F2238);
  stop-opacity: 0;
}

.nogyb-blk {
  stop-color: var(--svg-color--150908, #150908);
}

.o0xyil93m {
  d: path("M7.857 19.611v-3.085L4.941 13.47v8.3z");
}

.ob4q8w1qm {
  d: path("m4.979 10.663l3.99 6.029c1.083.445 5.095.106 5.647.148c.442.034.75.142.85.191l2.462-6.368z");
}

.oe1lqnr7n {
  stop-color: var(--svg-color--564459, #564459);
  stop-opacity: 0;
}

.ovix1ebyr {
  stop-color: var(--svg-color--4d3d3c, #4D3D3C);
}

.pih9qk2my {
  stop-color: var(--svg-color--4d3d3c, #4D3D3C);
  stop-opacity: 0;
}

.ptrirg6xc {
  stop-color: var(--svg-color--381d33, #381D33);
  stop-opacity: 0;
}

.q68v-7b3u {
  fill-rule: evenodd;
  d: path("M7.555 8a5.5 5.5 0 0 0-5.5 5.5v5.625h.004v.398c-.01.724.205 2.58 1.043 3.805c1.046 1.531 2.859 2.75 4.64 2.75h2.104c-.075.28-.102.573-.134.921l-.001.017c0 1.023.437 2.562 2.64 3c.985.148 2-.274 2.829-.93a95 95 0 0 0 1.961-1.64l.703-.594l.129-.11c.357-.31.862-.747 1.472-.789c.835-.058 2.42-.38 4.352-2.219c.78-.742 1.4-1.748 1.755-2.322c.093-.15.167-.271.221-.35q.08-.116.138-.212c.235-.374.328-.522 1.331-.522l-.007-.008h.71a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2zm7.302 12.3c.273-.474.686-1.272.87-1.917c.273-.961-.24-1.071-.485-1.117c-.37-.07-.942-.062-1.536-.053q-.303.005-.604.006q-.357 0-.758.005c-1.227.012-2.667.026-3.399-.193c-.133.065-.398.317-.398.805v.1c-.002.582-.004 1.208.476 1.533c.178.12.531.147.965.18c.487.036 1.075.08 1.631.273h.002l.062.023c.245.09.482.21.701.373a3.33 3.33 0 0 1 1.228 1.743c.701-.82 1.131-1.54 1.228-1.752z");
}

.q8vevylxo {
  stop-color: var(--svg-color--211212, #211212);
  stop-opacity: 0;
}

.rg3n2_b4b {
  stop-color: var(--svg-color--665150, #665150);
}

.rg4k0nb5q {
  stop-color: var(--svg-color--3f2238, #3F2238);
}

.szjg1fb1r {
  stop-color: var(--svg-color--3f2323, #3F2323);
}

.tubjn2bip {
  stop-color: var(--svg-color--0d0404, #0D0404);
}

.ug9j6ob3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.424 25.63l5.08-4.776");
}

.uvh2l3b_g {
  d: path("M13.707 14.771h16.238v3.55a2 2 0 0 1-2 2h-.71l.007.007a5 5 0 0 0-.526.021c-.357.036-.516.12-.64.262a2 2 0 0 0-.165.24q-.058.096-.138.212a7 7 0 0 0-.171.268l-.05.081c-.354.574-.975 1.58-1.755 2.322c-1.932 1.84-3.517 2.161-4.352 2.22c-.61.041-1.115.478-1.472.787l-.13.11l-.702.596a95 95 0 0 1-1.961 1.639c-.828.656-1.844 1.078-2.828.93c-2.204-.438-2.641-1.977-2.641-3l.001-.017c.109-1.191.157-1.725 2.304-3.397a11.6 11.6 0 0 0 2.061-2.119c.427-.564.69-1.014.763-1.174l.017-.01c.273-.473.686-1.27.87-1.916c.273-.961-.24-1.071-.485-1.117c-.37-.07-.941-.062-1.535-.053z");
}

.vhjvvxb2h {
  stop-color: var(--svg-color--564459, #564459);
}

.xvzg_abgt {
  stop-color: var(--svg-color--201113, #201113);
}

.xzqkqgrsz {
  d: path("M7.836 16.096h9.563v7.109H7.836z");
}

.yav56ob9d {
  d: path("m9.061 17.063l.036.008l-.011-.009z");
}

.ysytpib0b {
  stop-color: var(--svg-color--483146, #483146);
}

.z2j_3qbhm {
  stop-color: var(--svg-color--200d11, #200D11);
  stop-opacity: 0;
}

</style>
