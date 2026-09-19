<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igsD0Qb)" class="xzqkqgrsz"/><path fill="url(#it3Ympc)" class="xzqkqgrsz"/><g filter="url(#iNvbddd)"><path fill="url(#ibhiawb)" class="ilosvxboq"/></g><g clip-rule="evenodd" filter="url(#iJOPaLe)" class="d2kvgvbvc"><path fill="url(#iBxLUUd)" class="g7e8aablc"/><path fill="url(#iF2eBKb)" class="g7e8aablc"/></g><path fill="url(#iAqSUJe)" clip-rule="evenodd" class="q68v-7b3u"/><path fill="url(#i44CAyY)" clip-rule="evenodd" class="q68v-7b3u"/><path fill="url(#iVHWjBe)" class="l6l-1byuh"/><path fill="url(#im5fpOc)" class="l6l-1byuh"/><path fill="url(#iLdQFMb)" class="l6l-1byuh"/><path fill="url(#iVHWjBe)" class="yav56ob9d"/><path fill="url(#im5fpOc)" class="yav56ob9d"/><path fill="url(#iLdQFMb)" class="yav56ob9d"/><path fill="url(#iub0wKl)" class="uvh2l3b_g"/><path fill="url(#ipGcmmd)" class="uvh2l3b_g"/><path fill="url(#iWy6lGd)" class="uvh2l3b_g"/><path fill="url(#iy7gneV)" class="uvh2l3b_g"/><g filter="url(#i749GKb)"><path fill="url(#i5ApOcd)" class="ob4q8w1qm"/></g><g filter="url(#i8gAIsd)"><path fill="url(#iegynuQ)" class="o0xyil93m"/></g><g filter="url(#iU1Jymc)"><path stroke="url(#iI7Zi8c)" class="ug9j6ob3t"/></g><defs><radialGradient id="igsD0Qb" cx="0" cy="0" r="1" gradientTransform="rotate(-152.154 10.121 8.147)scale(5.41069 4.24838)" gradientUnits="userSpaceOnUse"><stop class="c4xriu7wl"/><stop offset="1" class="n7ycspb_w"/></radialGradient><radialGradient id="it3Ympc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78125 -4.67188 0 13.977 17.378)" gradientUnits="userSpaceOnUse"><stop class="g88tywb2y"/><stop offset="1" class="ky3iwu_uh"/></radialGradient><radialGradient id="ibhiawb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.97793 -2.31968 2.07476 -2.66352 13.428 22.674)" gradientUnits="userSpaceOnUse"><stop class="f0u-sws4m"/><stop offset="1" class="h3s2tg8hp"/></radialGradient><radialGradient id="iBxLUUd" cx="0" cy="0" r="1" gradientTransform="matrix(-16.07307 10.95896 -7.9909 -11.71994 26.013 10)" gradientUnits="userSpaceOnUse"><stop class="a2q-gub5a"/><stop offset="1" class="ci-glpb1o"/></radialGradient><radialGradient id="iF2eBKb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68909 6.7081 -5.46182 -4.63213 23.914 17.88)" gradientUnits="userSpaceOnUse"><stop class="s72n_eb6g"/><stop offset="1" class="osqpgdrkk"/></radialGradient><radialGradient id="iVHWjBe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37548 0 0 -3.04657 14.21 22.948)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="oze16tbmr"/><stop offset="1" class="vajkbmvki"/></radialGradient><radialGradient id="im5fpOc" cx="0" cy="0" r="1" gradientTransform="matrix(.72908 9.08535 -10.30019 .82656 8.502 17.704)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="wdbv_ebin"/><stop offset="1" class="wl6joioaj"/></radialGradient><radialGradient id="iLdQFMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34634 1.37173 -1.19847 -1.1763 11.283 22.556)" gradientUnits="userSpaceOnUse"><stop class="ec-624yqy"/><stop offset="1" class="zeqo4xbzj"/></radialGradient><radialGradient id="iub0wKl" cx="0" cy="0" r="1" gradientTransform="matrix(8.26407 -6.87499 3.7143 4.46477 11.564 32.39)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bxcea8bme"/><stop offset="1" class="akazwo4yd"/></radialGradient><radialGradient id="ipGcmmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41548 -3.5526 5.239 -2.0874 22.11 26.38)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="jtu86n92c"/><stop offset="1" class="v3_h24bov"/></radialGradient><radialGradient id="iWy6lGd" cx="0" cy="0" r="1" gradientTransform="matrix(2.33508 -1.82561 .80542 1.03018 27.268 21.277)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="mdklrbbwg"/><stop offset="1" class="pb945739n"/></radialGradient><radialGradient id="iy7gneV" cx="0" cy="0" r="1" gradientTransform="matrix(-14.15639 7.36966 -8.34555 -16.03098 23.28 20.953)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="wavoo2mio"/><stop offset="1" class="kev99_b8m"/></radialGradient><linearGradient id="iAqSUJe" x1="16.994" x2="16" y1="6.162" y2="11.937" gradientUnits="userSpaceOnUse"><stop class="dii5cjb5j"/><stop offset="1" class="lcrwdtb3r"/></linearGradient><linearGradient id="i44CAyY" x1="2.055" x2="2.814" y1="16.052" y2="16.052" gradientUnits="userSpaceOnUse"><stop class="js_f7_nbz"/><stop offset="1" class="g_fv71bsp"/></linearGradient><linearGradient id="i5ApOcd" x1="8.014" x2="18.653" y1="17.031" y2="11.984" gradientUnits="userSpaceOnUse"><stop class="e5vk05coe"/><stop offset=".281" class="z04te9buo"/><stop offset="1" class="l9qqkvrel"/><stop offset="1" class="oaj3tbcmn"/></linearGradient><linearGradient id="iegynuQ" x1="4.941" x2="8.062" y1="17.62" y2="17.62" gradientUnits="userSpaceOnUse"><stop class="xq5h8wb5f"/><stop offset="1" class="j-d5pibun"/></linearGradient><linearGradient id="iI7Zi8c" x1="15.424" x2="19.945" y1="25.63" y2="21.057" gradientUnits="userSpaceOnUse"><stop class="iixkl8r3r"/><stop offset="1" class="ldpst2wuy"/></linearGradient><filter id="iNvbddd" width="8.636" height="7.547" x="6.711" y="16.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.156863 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3250"/></filter><filter id="iJOPaLe" width="29.391" height="22.545" x="2.055" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.321569 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3250"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.4 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3250" result="effect2_innerShadow_20020_3250"/></filter><filter id="i749GKb" width="17.949" height="11.368" x="2.479" y="8.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3250" stdDeviation="1.25"/></filter><filter id="i8gAIsd" width="5.916" height="11.3" x="3.441" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3250" stdDeviation=".75"/></filter><filter id="iU1Jymc" width="10.331" height="10.026" x="12.799" y="18.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3250" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:left-facing-fist-medium" /></template>
<style>
.a2q-gub5a {
  stop-color: var(--svg-color--c39c80, #C39C80);
}

.akazwo4yd {
  stop-color: var(--svg-color--9c5980, #9C5980);
  stop-opacity: 0;
}

.bxcea8bme {
  stop-color: var(--svg-color--9c5980, #9C5980);
}

.c4xriu7wl {
  stop-color: var(--svg-color--643840, #643840);
}

.ci-glpb1o {
  stop-color: var(--svg-color--9e7866, #9E7866);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dii5cjb5j {
  stop-color: var(--svg-color--c09a7b, #C09A7B);
}

.e5vk05coe {
  stop-color: var(--svg-color--915e63, #915E63);
}

.ec-624yqy {
  stop-color: var(--svg-color--a27f70, #A27F70);
}

.f0u-sws4m {
  stop-color: var(--svg-color--643e39, #643E39);
}

.ft5dv1b6b {
  fill: none;
}

.g_fv71bsp {
  stop-color: var(--svg-color--9d796b, #9D796B);
  stop-opacity: 0;
}

.g7e8aablc {
  d: path("M7.555 8a5.5 5.5 0 0 0-5.5 5.5v5.625h.004v.398c-.01.724.205 2.58 1.043 3.805c1.046 1.531 2.859 2.75 4.64 2.75h2.104c-.075.28-.102.573-.134.921l-.001.017c0 1.023.437 2.562 2.64 3c.985.148 2-.274 2.829-.93a95 95 0 0 0 1.961-1.64l.703-.594l.129-.11c.357-.31.862-.747 1.472-.789c.835-.058 2.42-.38 4.352-2.219c.78-.742 1.4-1.748 1.755-2.322c.093-.15.167-.271.221-.35q.08-.116.138-.212c.235-.374.328-.522 1.331-.522l-.007-.008h.71a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2zm7.302 12.3c.273-.474.686-1.272.87-1.917c.273-.961-.24-1.071-.485-1.117c-.37-.07-.942-.062-1.536-.053q-.303.005-.604.006q-.357 0-.758.005c-1.227.012-2.667.026-3.399-.193c-.133.065-.398.317-.398.805v.1c-.002.582-.004 1.208.476 1.533c.178.12.531.147.965.18c.487.036 1.075.08 1.631.273h.002l.062.023c.245.09.482.21.701.373a3.33 3.33 0 0 1 1.228 1.743c.701-.82 1.131-1.54 1.228-1.752z");
}

.g88tywb2y {
  stop-color: var(--svg-color--41251d, #41251D);
}

.h3s2tg8hp {
  stop-color: var(--svg-color--52352a, #52352A);
}

.iixkl8r3r {
  stop-color: var(--svg-color--cfa68d, #CFA68D);
}

.ilosvxboq {
  d: path("M9.692 18.761a4.8 4.8 0 0 1 .066-1.823H6.96v7.296h6.703c1.078 0 1.899-1.609 1.633-2.843c-.266-1.235-1.432-2.277-2.711-2.203c-.963.055-1.893.016-2.524-.074a.43.43 0 0 1-.37-.353");
}

.j-d5pibun {
  stop-color: var(--svg-color--b88f81, #B88F81);
  stop-opacity: 0;
}

.js_f7_nbz {
  stop-color: var(--svg-color--9d796b, #9D796B);
}

.jtu86n92c {
  stop-color: var(--svg-color--9f6590, #9F6590);
}

.kev99_b8m {
  stop-color: var(--svg-color--9b726c, #9B726C);
}

.ky3iwu_uh {
  stop-color: var(--svg-color--41251d, #41251D);
  stop-opacity: 0;
}

.l6l-1byuh {
  d: path("M2.055 17.063v2.062h.004v.398c-.01.724.205 2.58 1.043 3.805c.818 1.198 2.105 2.204 3.479 2.586c.372.1.75.155 1.126.155h2.141c.082-.293.328-.887.968-1.465c.116-.111.341-.3.62-.531c.692-.578 1.642-1.268 2.181-2.007c-.141-.47-.509-1.23-1.233-1.747a2.8 2.8 0 0 0-.763-.397h-.002c-.556-.193-1.144-.237-1.631-.274c-.434-.032-.787-.059-.965-.18c-.48-.324-.478-.95-.476-1.532v-.1c0-.43.206-.676.346-.773z");
}

.l9qqkvrel {
  stop-color: var(--svg-color--7e4e51, #7E4E51);
  stop-opacity: 0;
}

.lcrwdtb3r {
  stop-color: var(--svg-color--c09a7b, #C09A7B);
  stop-opacity: 0;
}

.ldpst2wuy {
  stop-color: var(--svg-color--cfa68d, #CFA68D);
  stop-opacity: 0;
}

.mdklrbbwg {
  stop-color: var(--svg-color--9d6a93, #9D6A93);
}

.n7ycspb_w {
  stop-color: var(--svg-color--492c27, #492C27);
}

.o0xyil93m {
  d: path("M7.857 19.611v-3.085L4.941 13.47v8.3z");
}

.oaj3tbcmn {
  stop-color: var(--svg-color--89595f, #89595F);
  stop-opacity: 0;
}

.ob4q8w1qm {
  d: path("m4.979 10.663l3.99 6.029c1.083.445 5.095.106 5.647.148c.442.034.75.142.85.191l2.462-6.368z");
}

.osqpgdrkk {
  stop-color: var(--svg-color--d3aa90, #D3AA90);
  stop-opacity: 0;
}

.oze16tbmr {
  stop-color: var(--svg-color--633f3a, #633F3A);
}

.pb945739n {
  stop-color: var(--svg-color--9d6a93, #9D6A93);
  stop-opacity: 0;
}

.q68v-7b3u {
  fill-rule: evenodd;
  d: path("M7.555 8a5.5 5.5 0 0 0-5.5 5.5v5.625h.004v.398c-.01.724.205 2.58 1.043 3.805c1.046 1.531 2.859 2.75 4.64 2.75h2.104c-.075.28-.102.573-.134.921l-.001.017c0 1.023.437 2.562 2.64 3c.985.148 2-.274 2.829-.93a95 95 0 0 0 1.961-1.64l.703-.594l.129-.11c.357-.31.862-.747 1.472-.789c.835-.058 2.42-.38 4.352-2.219c.78-.742 1.4-1.748 1.755-2.322c.093-.15.167-.271.221-.35q.08-.116.138-.212c.235-.374.328-.522 1.331-.522l-.007-.008h.71a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2zm7.302 12.3c.273-.474.686-1.272.87-1.917c.273-.961-.24-1.071-.485-1.117c-.37-.07-.942-.062-1.536-.053q-.303.005-.604.006q-.357 0-.758.005c-1.227.012-2.667.026-3.399-.193c-.133.065-.398.317-.398.805v.1c-.002.582-.004 1.208.476 1.533c.178.12.531.147.965.18c.487.036 1.075.08 1.631.273h.002l.062.023c.245.09.482.21.701.373a3.33 3.33 0 0 1 1.228 1.743c.701-.82 1.131-1.54 1.228-1.752z");
}

.s72n_eb6g {
  stop-color: var(--svg-color--d3aa90, #D3AA90);
}

.ug9j6ob3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.424 25.63l5.08-4.776");
}

.uvh2l3b_g {
  d: path("M13.707 14.771h16.238v3.55a2 2 0 0 1-2 2h-.71l.007.007a5 5 0 0 0-.526.021c-.357.036-.516.12-.64.262a2 2 0 0 0-.165.24q-.058.096-.138.212a7 7 0 0 0-.171.268l-.05.081c-.354.574-.975 1.58-1.755 2.322c-1.932 1.84-3.517 2.161-4.352 2.22c-.61.041-1.115.478-1.472.787l-.13.11l-.702.596a95 95 0 0 1-1.961 1.639c-.828.656-1.844 1.078-2.828.93c-2.204-.438-2.641-1.977-2.641-3l.001-.017c.109-1.191.157-1.725 2.304-3.397a11.6 11.6 0 0 0 2.061-2.119c.427-.564.69-1.014.763-1.174l.017-.01c.273-.473.686-1.27.87-1.916c.273-.961-.24-1.071-.485-1.117c-.37-.07-.941-.062-1.535-.053z");
}

.v3_h24bov {
  stop-color: var(--svg-color--9f6590, #9F6590);
  stop-opacity: 0;
}

.vajkbmvki {
  stop-color: var(--svg-color--633f3a, #633F3A);
  stop-opacity: 0;
}

.wavoo2mio {
  stop-color: var(--svg-color--9b726c, #9B726C);
  stop-opacity: 0;
}

.wdbv_ebin {
  stop-color: var(--svg-color--8e4f78, #8E4F78);
  stop-opacity: 0;
}

.wl6joioaj {
  stop-color: var(--svg-color--8e4f78, #8E4F78);
}

.xq5h8wb5f {
  stop-color: var(--svg-color--b88f81, #B88F81);
}

.xzqkqgrsz {
  d: path("M7.836 16.096h9.563v7.109H7.836z");
}

.yav56ob9d {
  d: path("m9.061 17.063l.036.008l-.011-.009z");
}

.z04te9buo {
  stop-color: var(--svg-color--89595f, #89595F);
}

.zeqo4xbzj {
  stop-color: var(--svg-color--a27f70, #A27F70);
  stop-opacity: 0;
}

</style>
