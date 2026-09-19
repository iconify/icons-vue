<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyb3Dbe)"><path class="ocx8xcc4s"/><path fill="url(#iYMxh7d)" class="qg1_p62ax"/><path fill="url(#iaKhnNe)" class="qg1_p62ax"/></g><g filter="url(#idRTzyb)"><path class="cxvze7b1m"/></g><path fill="url(#iF9u5hc)" class="r7j58b-_c"/><path fill="url(#iyo7a8d)" class="r7j58b-_c"/><path fill="url(#iWhWLLV)" class="r7j58b-_c"/><circle fill="url(#iDKEHge)" class="ze_3k2b3x"/><circle fill="url(#i3dqlEA)" class="ze_3k2b3x"/><path fill="url(#ivy2Ude)" class="bfuc7dbkm"/><path fill="url(#iV8Et9H)" class="bfuc7dbkm"/><path fill="url(#iPZ4q2c)" class="bfuc7dbkm"/><path fill="url(#i3ZBoSd)" class="bfuc7dbkm"/><g filter="url(#ikX3Pcc)"><path fill="url(#iwhXBhb)" class="pw2t7y4_u"/></g><g filter="url(#iqahtVb)"><path fill="url(#iQ18UEb)" class="f-pv5ubve"/><path fill="url(#iKFBAwI)" class="f-pv5ubve"/></g><g filter="url(#iY7qgCb)"><path fill="url(#idssH3c)" class="us-fe6bhl"/><path fill="url(#iq4GDce)" class="us-fe6bhl"/></g><defs><linearGradient id="iYMxh7d" x1="24.363" x2="25.238" y1="11.25" y2="12.156" gradientUnits="userSpaceOnUse"><stop offset=".334" class="u3t3wsbpr"/><stop offset="1" class="rm_dr0bko"/></linearGradient><linearGradient id="iF9u5hc" x1="5.144" x2="4.676" y1="29.188" y2="27.688" gradientUnits="userSpaceOnUse"><stop offset=".117" class="cugqclb3d"/><stop offset="1" class="lggwidbsv"/></linearGradient><linearGradient id="iyo7a8d" x1="10.644" x2="8.722" y1="26.063" y2="24.984" gradientUnits="userSpaceOnUse"><stop offset=".349" class="qsco87qdf"/><stop offset="1" class="k6phhdcga"/></linearGradient><linearGradient id="ivy2Ude" x1="27.582" x2="7.019" y1="3.187" y2="23.125" gradientUnits="userSpaceOnUse"><stop class="bj6f4gbee"/><stop offset="1" class="b5kohe6uk"/></linearGradient><linearGradient id="iV8Et9H" x1="13.301" x2="15.832" y1="12.656" y2="15.25" gradientUnits="userSpaceOnUse"><stop class="ggzrfyb4e"/><stop offset="1" class="zyssq2q5m"/></linearGradient><linearGradient id="iPZ4q2c" x1="19.953" x2="18.663" y1="16.854" y2="15.435" gradientUnits="userSpaceOnUse"><stop offset=".161" class="hq3aktbhm"/><stop offset="1" class="ncd2w5rnm"/></linearGradient><linearGradient id="i3ZBoSd" x1="7.738" x2="8.957" y1="23.672" y2="22.344" gradientUnits="userSpaceOnUse"><stop class="ol-hzsb6v"/><stop offset="1" class="c04nowvhn"/></linearGradient><linearGradient id="iwhXBhb" x1="27.298" x2="8.838" y1="4.6" y2="23.061" gradientUnits="userSpaceOnUse"><stop class="dqhmiwabv"/><stop offset="1" class="ax6higbpm"/></linearGradient><linearGradient id="iQ18UEb" x1="12.989" x2="18.276" y1="13.544" y2="18.358" gradientUnits="userSpaceOnUse"><stop class="iutuewb6e"/><stop offset="1" class="pjlzf8b3t"/></linearGradient><linearGradient id="idssH3c" x1="23.014" x2="28.152" y1="3.642" y2="8.321" gradientUnits="userSpaceOnUse"><stop class="iutuewb6e"/><stop offset="1" class="pjlzf8b3t"/></linearGradient><radialGradient id="iaKhnNe" cx="0" cy="0" r="1" gradientTransform="rotate(135 12.88 10.076)scale(.97227 .7734)" gradientUnits="userSpaceOnUse"><stop class="etfa927oo"/><stop offset="1" class="rnq0obcva"/></radialGradient><radialGradient id="iWhWLLV" cx="0" cy="0" r="1" gradientTransform="rotate(136.292 -.207 14.156)scale(1.46983 5.23343)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="qf5ggo0bi"/><stop offset="1" class="mobdv4umb"/></radialGradient><radialGradient id="iDKEHge" cx="0" cy="0" r="1" gradientTransform="rotate(-31.328 49.518 4.202)scale(.84143)" gradientUnits="userSpaceOnUse"><stop class="fruzx-fap"/><stop offset="1" class="fsjph7zrq"/></radialGradient><radialGradient id="i3dqlEA" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 -2 1.6524 .38728 5.02 26.922)" gradientUnits="userSpaceOnUse"><stop offset=".547" class="ffruenb1e"/><stop offset=".93" class="p9-zqlbwg"/></radialGradient><radialGradient id="iKFBAwI" cx="0" cy="0" r="1" gradientTransform="rotate(136.637 5.386 10.88)scale(2.12836 3.1968)" gradientUnits="userSpaceOnUse"><stop class="wls1ypbcc"/><stop offset="1" class="m-pyldb9i"/></radialGradient><radialGradient id="iq4GDce" cx="0" cy="0" r="1" gradientTransform="rotate(135.361 12.289 8.051)scale(2.45618 3.68919)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="wls1ypbcc"/><stop offset="1" class="m-pyldb9i"/></radialGradient><filter id="iyb3Dbe" width="7.48" height="7.58" x="22.071" y="7.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.470588 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22308"/></filter><filter id="idRTzyb" width="12.078" height="11.695" x="1.536" y="18.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.647059 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22308"/></filter><filter id="ikX3Pcc" width="22.001" height="22.001" x="6.986" y="2.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22308" stdDeviation=".75"/></filter><filter id="iqahtVb" width="6.356" height="6.506" x="12.334" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.541176 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22308"/></filter><filter id="iY7qgCb" width="6.328" height="6.328" x="22.376" y="2.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.615686 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22308"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fountain-pen" /></template>
<style>
.ax6higbpm {
  stop-color: var(--svg-color--477ec2, #477EC2);
}

.b5kohe6uk {
  stop-color: var(--svg-color--3270b0, #3270B0);
}

.bfuc7dbkm {
  d: path("M23.026 3.625a3.36 3.36 0 0 1 4.751 4.75L10.86 25.293a1 1 0 0 1-1.414 0l-3.337-3.337a1 1 0 0 1 0-1.414z");
}

.bj6f4gbee {
  stop-color: var(--svg-color--3a81c6, #3A81C6);
}

.c04nowvhn {
  stop-color: var(--svg-color--3372b3, #3372B3);
  stop-opacity: 0;
}

.cugqclb3d {
  stop-color: var(--svg-color--957baf, #957BAF);
}

.cxvze7b1m {
  fill: var(--svg-color--b9b4c1, #B9B4C1);
  d: path("m8.598 18.64l4.015 4.016l-5.503 5.58a1 1 0 0 1-.437.258L2.046 29.82a.4.4 0 0 1-.496-.49l1.245-4.564a1 1 0 0 1 .25-.436z");
}

.dqhmiwabv {
  stop-color: var(--svg-color--6d9ede, #6D9EDE);
}

.etfa927oo {
  stop-color: var(--svg-color--e3e2e5, #E3E2E5);
}

.f-pv5ubve {
  d: path("M13.37 12.884a.4.4 0 0 1 .565 0l4.638 4.638a.4.4 0 0 1 0 .566l-.92.918a.4.4 0 0 1-.565 0l-4.637-4.637a.4.4 0 0 1 0-.566z");
}

.ffruenb1e {
  stop-color: var(--svg-color--645d6b, #645D6B);
  stop-opacity: 0;
}

.fruzx-fap {
  stop-color: var(--svg-color--a9a8ab, #A9A8AB);
}

.fsjph7zrq {
  stop-color: var(--svg-color--7c7b7e, #7C7B7E);
}

.ft5dv1b6b {
  fill: none;
}

.ggzrfyb4e {
  stop-color: var(--svg-color--3f70ab, #3F70AB);
}

.hq3aktbhm {
  stop-color: var(--svg-color--456ab9, #456AB9);
}

.iutuewb6e {
  stop-color: var(--svg-color--afaeb0, #AFAEB0);
}

.k6phhdcga {
  stop-color: var(--svg-color--9a86b1, #9A86B1);
  stop-opacity: 0;
}

.lggwidbsv {
  stop-color: var(--svg-color--b5aac2, #B5AAC2);
  stop-opacity: 0;
}

.m-pyldb9i {
  stop-color: var(--svg-color--d7d5db, #D7D5DB);
  stop-opacity: 0;
}

.mobdv4umb {
  stop-color: var(--svg-color--7a738e, #7A738E);
  stop-opacity: 0;
}

.ncd2w5rnm {
  stop-color: var(--svg-color--3677b8, #3677B8);
  stop-opacity: 0;
}

.ocx8xcc4s {
  fill: var(--svg-color--c3c0c9, #C3C0C9);
  d: path("M29.14 9.348a.89.89 0 1 0-1.257-1.258l-5.551 5.55a.89.89 0 1 0 1.258 1.258z");
}

.ol-hzsb6v {
  stop-color: var(--svg-color--3752ae, #3752AE);
}

.p9-zqlbwg {
  stop-color: var(--svg-color--645d6b, #645D6B);
}

.pjlzf8b3t {
  stop-color: var(--svg-color--c0b9c8, #C0B9C8);
}

.pw2t7y4_u {
  d: path("M26.388 4.6a.644.644 0 1 1 .91.91L9.47 23.34a.25.25 0 0 1-.354 0l-.557-.557a.25.25 0 0 1 0-.354z");
}

.qf5ggo0bi {
  stop-color: var(--svg-color--7a738e, #7A738E);
}

.qg1_p62ax {
  d: path("M29.14 9.348a.89.89 0 1 0-1.257-1.258l-5.551 5.55a.89.89 0 1 0 1.258 1.258z");
}

.qsco87qdf {
  stop-color: var(--svg-color--9a86b1, #9A86B1);
}

.r7j58b-_c {
  d: path("m8.598 18.64l4.015 4.016l-5.503 5.58a1 1 0 0 1-.437.258L2.046 29.82a.4.4 0 0 1-.496-.49l1.245-4.564a1 1 0 0 1 .25-.436z");
}

.rm_dr0bko {
  stop-color: var(--svg-color--a7a7b6, #A7A7B6);
  stop-opacity: 0;
}

.rnq0obcva {
  stop-color: var(--svg-color--e3e2e5, #E3E2E5);
  stop-opacity: 0;
}

.u3t3wsbpr {
  stop-color: var(--svg-color--a7a7b6, #A7A7B6);
}

.us-fe6bhl {
  d: path("M23.456 3.033a.5.5 0 0 1 .707 0l4.244 4.245a.5.5 0 0 1 0 .707l-1.02 1.02a.2.2 0 0 1-.284 0l-4.668-4.668a.2.2 0 0 1 0-.282z");
}

.wls1ypbcc {
  stop-color: var(--svg-color--d7d5db, #D7D5DB);
}

.ze_3k2b3x {
  cx: 5.277px;
  cy: 26.086px;
  r: 0.977px;
}

.zyssq2q5m {
  stop-color: var(--svg-color--3f70ab, #3F70AB);
  stop-opacity: 0;
}

</style>
