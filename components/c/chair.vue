<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isbNPGd)" class="a0n5cqf2m"/><path fill="url(#iSfV2tc)" class="a0n5cqf2m"/><path fill="url(#iJnyPkd)" class="a0n5cqf2m"/><path fill="url(#ipaYRyb)" class="tnwc4y-3z"/><path fill="url(#iX2Crcd)" class="tnwc4y-3z"/><path fill="url(#i8iarod)" class="tnwc4y-3z"/><path fill="url(#iWwC4tb)" class="bq_-v9byh"/><path fill="url(#iZaDTtd)" class="rkvbvobwt"/><path fill="url(#i8EaPod)" class="rkvbvobwt"/><g filter="url(#idbUkjb)"><path class="ynmgfo-as"/><path fill="url(#i6vqEqc)" class="v2dlwexpa"/></g><path fill="url(#i60X3Yc)" class="srywytbxq"/><path fill="url(#iUvkx4c)" class="srywytbxq"/><g filter="url(#ieOzTge)"><path class="iti-3db-s"/><path fill="url(#inLfzvb)" class="ikm7hmske"/></g><g filter="url(#iVL9v1a)"><path class="g7oqvhtjp"/></g><g filter="url(#i105v6d)"><path fill="url(#i5UIJnb)" class="vnsdzidxf"/></g><path fill="url(#iGvIQDc)" class="tsrpbac8h"/><path class="lhgisvlzg"/><path fill="url(#iQSaTzb)" class="dvkx3z6-e"/><path stroke="url(#icj9SNc)" class="g23kaymdl"/><defs><linearGradient id="isbNPGd" x1="11.369" x2="12.619" y1="11.539" y2="11.539" gradientUnits="userSpaceOnUse"><stop class="tbk24cgyh"/><stop offset="1" class="exu_fdcng"/></linearGradient><linearGradient id="iSfV2tc" x1="11.057" x2="11.588" y1="12.797" y2="12.797" gradientUnits="userSpaceOnUse"><stop class="pkhi4s04u"/><stop offset="1" class="eyubtl-uk"/></linearGradient><linearGradient id="ipaYRyb" x1="19.307" x2="20.557" y1="11.539" y2="11.539" gradientUnits="userSpaceOnUse"><stop class="tbk24cgyh"/><stop offset=".813" class="exu_fdcng"/></linearGradient><linearGradient id="iX2Crcd" x1="18.994" x2="19.525" y1="12.797" y2="12.797" gradientUnits="userSpaceOnUse"><stop class="pkhi4s04u"/><stop offset="1" class="eyubtl-uk"/></linearGradient><linearGradient id="iWwC4tb" x1="16.01" x2="16.01" y1="2.906" y2="9.203" gradientUnits="userSpaceOnUse"><stop class="zekpbtb4o"/><stop offset="1" class="vbogsiv_a"/></linearGradient><linearGradient id="i8EaPod" x1="10.979" x2="11.807" y1="22.453" y2="22.484" gradientUnits="userSpaceOnUse"><stop class="lbtghqb9f"/><stop offset="1" class="fcku2lc1c"/></linearGradient><linearGradient id="iUvkx4c" x1="21.002" x2="20.174" y1="22.453" y2="22.484" gradientUnits="userSpaceOnUse"><stop class="lbtghqb9f"/><stop offset="1" class="fcku2lc1c"/></linearGradient><linearGradient id="i5UIJnb" x1="7.464" x2="9.791" y1="28.932" y2="20.825" gradientUnits="userSpaceOnUse"><stop offset=".487" class="z0svhibil"/><stop offset="1" class="bjrn5ed-y"/></linearGradient><linearGradient id="iGvIQDc" x1="16" x2="16" y1="13.984" y2="21.156" gradientUnits="userSpaceOnUse"><stop offset=".22" class="dwazn5x9a"/><stop offset=".878" class="s6o1_dhnh"/></linearGradient><linearGradient id="iQSaTzb" x1="6.975" x2="9.682" y1="19.97" y2="19.97" gradientUnits="userSpaceOnUse"><stop class="xg_eh7bno"/><stop offset="1" class="j26-mklsp"/></linearGradient><linearGradient id="icj9SNc" x1="3.4" x2="26.932" y1="20.626" y2="20.626" gradientUnits="userSpaceOnUse"><stop offset=".136" class="o6hbzm8om"/><stop offset=".421" class="l2gx7-bpa"/><stop offset=".805" class="l2gx7-bpa"/><stop offset=".901" class="o6hbzm8om"/></linearGradient><radialGradient id="iJnyPkd" cx="0" cy="0" r="1" gradientTransform="rotate(95.412 2.2 9.927)scale(1.49102 3.6804)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="tt5qttbiq"/><stop offset="1" class="r3v2tg1yi"/></radialGradient><radialGradient id="i8iarod" cx="0" cy="0" r="1" gradientTransform="matrix(.32814 1.59375 -3.93396 .80996 19.759 8.562)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="tt5qttbiq"/><stop offset="1" class="r3v2tg1yi"/></radialGradient><radialGradient id="iZaDTtd" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -5.90625 3.47248 .22048 11.838 26.5)" gradientUnits="userSpaceOnUse"><stop class="kenehfbms"/><stop offset="1" class="yvxjtykgk"/></radialGradient><radialGradient id="i6vqEqc" cx="0" cy="0" r="1" gradientTransform="rotate(110.368 -2.17 13.733)scale(2.90644 4.6918)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="ey3ez_t8r"/><stop offset="1" class="a0bq8ubid"/></radialGradient><radialGradient id="i60X3Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -5.90625 3.47248 -.22048 20.143 26.5)" gradientUnits="userSpaceOnUse"><stop class="kenehfbms"/><stop offset="1" class="yvxjtykgk"/></radialGradient><radialGradient id="inLfzvb" cx="0" cy="0" r="1" gradientTransform="matrix(.84822 2.01205 -3.248 1.36926 21.627 20.786)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="ey3ez_t8r"/><stop offset="1" class="a0bq8ubid"/></radialGradient><filter id="idbUkjb" width="5.12" height="9.594" x="6.628" y="20.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.254902 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25742"/></filter><filter id="ieOzTge" width="4.87" height="9.594" x="20.753" y="20.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.254902 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25742"/></filter><filter id="iVL9v1a" width="3.756" height="9.216" x="21.875" y="20.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25742" stdDeviation=".3"/></filter><filter id="i105v6d" width="4.196" height="9.081" x="6.747" y="20.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25742" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chair" /></template>
<style>
.a0bq8ubid {
  stop-color: var(--svg-color--804044, #804044);
  stop-opacity: 0;
}

.a0n5cqf2m {
  d: path("M11.057 7.867h1.93v7.344h-1.93z");
}

.bjrn5ed-y {
  stop-color: var(--svg-color--9d6c67, #9D6C67);
  stop-opacity: 0;
}

.bq_-v9byh {
  d: path("M8.979 4.656c0-.966.783-1.75 1.75-1.75H21.29c.966 0 1.75.784 1.75 1.75v1.297a3.25 3.25 0 0 1-3.25 3.25h-7.562a3.25 3.25 0 0 1-3.25-3.25z");
}

.dvkx3z6-e {
  d: path("M6.982 18.785c-.092 1.203.838 2.371 2.197 2.371h13.642c1.362 0 2.29-1.171 2.197-2.372c-.081 1.077-.96 2.044-2.197 2.044H9.179c-1.234 0-2.116-.964-2.197-2.043");
}

.dwazn5x9a {
  stop-color: var(--svg-color--8a4c40, #8A4C40);
}

.exu_fdcng {
  stop-color: var(--svg-color--905b58, #905B58);
}

.ey3ez_t8r {
  stop-color: var(--svg-color--531c30, #531C30);
}

.eyubtl-uk {
  stop-color: var(--svg-color--6f4239, #6F4239);
  stop-opacity: 0;
}

.fcku2lc1c {
  stop-color: var(--svg-color--554344, #554344);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g23kaymdl {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.982 18.785c.081 1.079.963 2.043 2.197 2.043h13.642c1.237 0 2.116-.967 2.197-2.044");
}

.g7oqvhtjp {
  fill: var(--svg-color--9d6c67, #9D6C67);
  d: path("M22.475 21.023h.809l1.741 7.712a.249.249 0 0 1-.483.118z");
}

.ikm7hmske {
  d: path("m23.76 29.337l-3.007-8.79h2.843l1.758 8.343a.83.83 0 0 1-1.593.447");
}

.iti-3db-s {
  fill: var(--svg-color--803f44, #803F44);
  d: path("m23.76 29.337l-3.007-8.79h2.843l1.758 8.343a.83.83 0 0 1-1.593.447");
}

.j26-mklsp {
  stop-color: var(--svg-color--825257, #825257);
  stop-opacity: 0;
}

.kenehfbms {
  stop-color: var(--svg-color--602e49, #602E49);
}

.l2gx7-bpa {
  stop-color: var(--svg-color--af736c, #AF736C);
}

.lbtghqb9f {
  stop-color: var(--svg-color--554344, #554344);
}

.lhgisvlzg {
  fill: var(--svg-color--903f64, #903F64);
  d: path("M6.982 18.785c-.092 1.203.838 2.371 2.197 2.371h13.642c1.362 0 2.29-1.171 2.197-2.372c-.081 1.077-.96 2.044-2.197 2.044H9.179c-1.234 0-2.116-.964-2.197-2.043");
}

.o6hbzm8om {
  stop-color: var(--svg-color--af736c, #AF736C);
  stop-opacity: 0;
}

.pkhi4s04u {
  stop-color: var(--svg-color--6f4239, #6F4239);
}

.r3v2tg1yi {
  stop-color: var(--svg-color--7a4145, #7A4145);
  stop-opacity: 0;
}

.rkvbvobwt {
  d: path("M10.979 20.188h2.07l-.591 6.267a.67.67 0 0 1-1.338-.048z");
}

.s6o1_dhnh {
  stop-color: var(--svg-color--9b5c4c, #9B5C4C);
}

.srywytbxq {
  d: path("M21.002 20.188h-2.07l.59 6.267a.67.67 0 0 0 1.339-.048z");
}

.tbk24cgyh {
  stop-color: var(--svg-color--7d4240, #7D4240);
}

.tnwc4y-3z {
  d: path("M18.994 7.867h1.93v7.344h-1.93z");
}

.tsrpbac8h {
  d: path("M9.5 14.63a1.5 1.5 0 0 1 1.233-.646h10.434c.48 0 .932.23 1.214.62l2.22 3.06c1.056 1.455.017 3.492-1.78 3.492H9.179c-1.775 0-2.82-1.994-1.808-3.453z");
}

.tt5qttbiq {
  stop-color: var(--svg-color--4c1d28, #4C1D28);
}

.v2dlwexpa {
  d: path("m8.24 29.337l3.007-8.79H8.404L6.646 28.89a.83.83 0 0 0 1.593.447");
}

.vbogsiv_a {
  stop-color: var(--svg-color--9d5c5a, #9D5C5A);
}

.vnsdzidxf {
  d: path("M10.344 21.437h-.81l-2.177 7.565a.248.248 0 0 0 .474.145z");
}

.xg_eh7bno {
  stop-color: var(--svg-color--825257, #825257);
}

.ynmgfo-as {
  fill: var(--svg-color--803f44, #803F44);
  d: path("m8.24 29.337l3.007-8.79H8.404L6.646 28.89a.83.83 0 0 0 1.593.447");
}

.yvxjtykgk {
  stop-color: var(--svg-color--3e1531, #3E1531);
}

.z0svhibil {
  stop-color: var(--svg-color--9d6c67, #9D6C67);
}

.zekpbtb4o {
  stop-color: var(--svg-color--925253, #925253);
}

</style>
