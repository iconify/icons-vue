<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEYBtzW)" clip-rule="evenodd" class="dytdg4bua"/><path fill="url(#imkdObb)" clip-rule="evenodd" class="dytdg4bua"/><g filter="url(#igCNdZb)"><path fill="url(#iuXcioc)" class="b9i2_lzjx"/></g><path fill="url(#iVVhC8L)" class="b9i2_lzjx"/><g filter="url(#iJzMeGc)"><path fill="url(#iSKOQib)" class="k42xs2brd"/></g><path fill="url(#iBA3OHc)" class="k42xs2brd"/><g filter="url(#i4QGHUX)"><path fill="url(#iAykbhQ)" class="m41hqfvqy"/></g><g filter="url(#iJqJame)"><path stroke="url(#idsmoSd)" class="cofn78y8l"/></g><path fill="url(#iVd9Vbc)" class="k_yq9bcts"/><path fill="url(#iBG4Yqd)" class="k_yq9bcts"/><path fill="url(#igkkRcq)" class="k_yq9bcts"/><path fill="url(#isVMU3b)" class="k_yq9bcts"/><g filter="url(#inz0SWo)" class="r_hayobsq"><path stroke="url(#iVwU8Dm)" class="heg0lsb3q"/><path stroke="url(#iOQ3T7d)" class="heg0lsb3q"/></g><g filter="url(#iJy6lib)"><path fill="url(#imXnbtb)" class="ig4ivpcvk"/></g><defs><linearGradient id="iEYBtzW" x1="6.418" x2="7.684" y1="24.323" y2="25.589" gradientUnits="userSpaceOnUse"><stop offset=".384" class="t12ys4bka"/><stop offset="1" class="wg968sbbv"/></linearGradient><linearGradient id="iuXcioc" x1="19.8" x2="22.988" y1="9.339" y2="12.758" gradientUnits="userSpaceOnUse"><stop class="s16hycc4v"/><stop offset="1" class="xoipp876r"/></linearGradient><linearGradient id="iSKOQib" x1="13.021" x2="28.685" y1="19.863" y2="4.284" gradientUnits="userSpaceOnUse"><stop offset=".501" class="j5w0ukb6y"/><stop offset="1" class="s7_flcbak"/></linearGradient><linearGradient id="iAykbhQ" x1="23.641" x2="28.173" y1="1.953" y2="11.26" gradientUnits="userSpaceOnUse"><stop class="f74x2gbof"/><stop offset="1" class="bq0_vwbbq"/></linearGradient><linearGradient id="idsmoSd" x1="5.636" x2="9.1" y1="26.491" y2="22.97" gradientUnits="userSpaceOnUse"><stop offset=".558" class="wox-bybuw"/><stop offset="1" class="kzovzybyu"/></linearGradient><linearGradient id="iVd9Vbc" x1="3.153" x2="5.322" y1="26.573" y2="28.742" gradientUnits="userSpaceOnUse"><stop class="h3yvppbxw"/><stop offset="1" class="r_r5oqjnz"/></linearGradient><linearGradient id="isVMU3b" x1="2.836" x2="3.529" y1="29.45" y2="28.786" gradientUnits="userSpaceOnUse"><stop class="gf619ubxs"/><stop offset="1" class="w_qb-zz_q"/></linearGradient><linearGradient id="iVwU8Dm" x1="13.385" x2="23.756" y1="18.02" y2="8.225" gradientUnits="userSpaceOnUse"><stop class="ss6cgdcdo"/><stop offset="1" class="k_y-9p0wa"/></linearGradient><linearGradient id="imXnbtb" x1="23.622" x2="29.345" y1="2.867" y2="8.782" gradientUnits="userSpaceOnUse"><stop class="ay-r-v5ba"/><stop offset="1" class="g6orgrbct"/></linearGradient><radialGradient id="imkdObb" cx="0" cy="0" r="1" gradientTransform="matrix(3.75207 -3.69436 1.32814 1.34889 5.607 26.333)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="iho1vwi7b"/><stop offset=".971" class="of81qhn7z"/></radialGradient><radialGradient id="iVVhC8L" cx="0" cy="0" r="1" gradientTransform="matrix(4.82057 1.95896 -1.95723 4.8163 18.763 10.261)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="bhhph123e"/><stop offset=".88" class="f_a1l7b3m"/></radialGradient><radialGradient id="iBA3OHc" cx="0" cy="0" r="1" gradientTransform="matrix(16.2433 -16.14117 7.67233 7.72088 9.207 22.724)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="hsv_g_b9r"/><stop offset="1" class="uy6ktqbbw"/></radialGradient><radialGradient id="iBG4Yqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62645 2.48214 -.72767 -.76998 5.29 26.65)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="f1p_zcc4f"/><stop offset="1" class="sa9o1abkk"/></radialGradient><radialGradient id="igkkRcq" cx="0" cy="0" r="1" gradientTransform="matrix(-.44736 .4185 -.82896 -.88612 5.319 26.535)" gradientUnits="userSpaceOnUse"><stop class="d0tzg_bvs"/><stop offset="1" class="ruwd3kb8z"/></radialGradient><radialGradient id="iOQ3T7d" cx="0" cy="0" r="1" gradientTransform="rotate(-38.418 33.457 -10.131)scale(1.42172 1.60748)" gradientUnits="userSpaceOnUse"><stop class="bgkapu5lr"/><stop offset="1" class="ve04rzb3f"/></radialGradient><filter id="igCNdZb" width="6.058" height="7.106" x="18.044" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.309804 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_915"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".6"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.415686 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4791_915" result="effect2_innerShadow_4791_915"/></filter><filter id="iJzMeGc" width="19.414" height="19.812" x="8.387" y="3.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.521569 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_915"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.667329 0 0 0 0 0.624199 0 0 0 0 0.71585 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4791_915" result="effect2_innerShadow_4791_915"/></filter><filter id="i4QGHUX" width="8.495" height="8.791" x="21.505" y="1.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.309804 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_915"/></filter><filter id="iJqJame" width="4.188" height="4.161" x="5.043" y="22.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_915" stdDeviation=".15"/></filter><filter id="inz0SWo" width="14.496" height="14.278" x="12.554" y="5.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_915" stdDeviation=".2"/></filter><filter id="iJy6lib" width="8.897" height="8.863" x="21.488" y="1.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_915" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crutch" /></template>
<style>
.ay-r-v5ba {
  stop-color: var(--svg-color--7d7fb3, #7D7FB3);
}

.b9i2_lzjx {
  d: path("m22.544 13.89l-4.5-4.5l1.558-1.606l4.5 4.5z");
}

.bgkapu5lr {
  stop-color: var(--svg-color--cac5d0, #CAC5D0);
}

.bhhph123e {
  stop-color: var(--svg-color--504a77, #504A77);
  stop-opacity: 0;
}

.bq0_vwbbq {
  stop-color: var(--svg-color--554688, #554688);
}

.cofn78y8l {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m5.448 26.492l3.377-3.348");
}

.d0tzg_bvs {
  stop-color: var(--svg-color--7f78ad, #7F78AD);
}

.dytdg4bua {
  fill-rule: evenodd;
  d: path("M12.027 19.94a.7.7 0 0 1 0 .99l-7 7a.7.7 0 1 1-.99-.99l7-7a.7.7 0 0 1 .99 0");
}

.f_a1l7b3m {
  stop-color: var(--svg-color--504a77, #504A77);
}

.f1p_zcc4f {
  stop-color: var(--svg-color--6d62a2, #6D62A2);
}

.f74x2gbof {
  stop-color: var(--svg-color--6466a4, #6466A4);
}

.ft5dv1b6b {
  fill: none;
}

.g6orgrbct {
  stop-color: var(--svg-color--776c9a, #776C9A);
}

.gf619ubxs {
  stop-color: var(--svg-color--6b4da4, #6B4DA4);
}

.h3yvppbxw {
  stop-color: var(--svg-color--645d9b, #645D9B);
}

.heg0lsb3q {
  d: path("m22.22 5.537l-7.874 7.912c-.18.308-.538.73-.538 1.806c0 .7-.145 1.592-.606 2.333c-.203.328-.21.768.062 1.041c.246.246.638.275.947.117c.575-.293 1.446-.61 2.286-.61c1.46 0 2.035-.385 3.188-1.537l6.894-6.895");
}

.hsv_g_b9r {
  stop-color: var(--svg-color--807491, #807491);
  stop-opacity: 0;
}

.ig4ivpcvk {
  d: path("M28.987 8.158L23.595 2.8a.502.502 0 0 0-.708.712l5.392 5.359a.502.502 0 1 0 .708-.713");
}

.iho1vwi7b {
  stop-color: var(--svg-color--967eae, #967EAE);
  stop-opacity: 0;
}

.j5w0ukb6y {
  stop-color: var(--svg-color--bab1c3, #BAB1C3);
}

.k_y-9p0wa {
  stop-color: var(--svg-color--c6c1cb, #C6C1CB);
  stop-opacity: 0;
}

.k_yq9bcts {
  d: path("m3.25 29.62l-.945-.953c-.3-.3-.3-.974 0-1.274L3.86 25.84c.3-.3.976-.422 1.398 0l.836.836c.387.386.453.984 0 1.43l-1.39 1.398c-.3.3-.946.601-1.454.117");
}

.k42xs2brd {
  d: path("m9.634 23.284l-1.035-1c-.3-.3-.273-.908.024-1.17l1.992-2.086c.6-.5 2.04-2.101 2.084-3.544c.197-2.276 2-3.9 2.1-4l7.2-7.2l1.2 1.2l-7.3 7.3c-.1.1-1.5 1.4-1.5 2.8c0 .749-.312 1.537-.716 2.242c-.102.178.197.478.376.376c.715-.405 1.527-.718 2.34-.718c1.607-.151 2.747-1.518 2.747-1.518l7.336-7.43l1.219 1.234l-7.289 7.305s-1.703 1.91-4.133 2.063c-1.5.18-2.469 1.28-3.445 2.132l-2 1.914c-.382.382-.889.412-1.2.1");
}

.kzovzybyu {
  stop-color: var(--svg-color--a699b5, #A699B5);
  stop-opacity: 0;
}

.m41hqfvqy {
  d: path("m27.184 9.903l-5.2-5.2c-.6-.6-.703-1.395.07-2.169c.774-.773 1.63-.731 2.23-.131l5.2 5.2c.6.6.79 1.455-.054 2.3c-.89.834-1.646.6-2.246 0");
}

.of81qhn7z {
  stop-color: var(--svg-color--967eae, #967EAE);
}

.r_hayobsq {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.r_r5oqjnz {
  stop-color: var(--svg-color--6952a3, #6952A3);
}

.ruwd3kb8z {
  stop-color: var(--svg-color--7f78ad, #7F78AD);
  stop-opacity: 0;
}

.s16hycc4v {
  stop-color: var(--svg-color--645e95, #645E95);
}

.s7_flcbak {
  stop-color: var(--svg-color--968f9f, #968F9F);
}

.sa9o1abkk {
  stop-color: var(--svg-color--6d62a2, #6D62A2);
  stop-opacity: 0;
}

.ss6cgdcdo {
  stop-color: var(--svg-color--c6c1cb, #C6C1CB);
}

.t12ys4bka {
  stop-color: var(--svg-color--ada7b5, #ADA7B5);
}

.uy6ktqbbw {
  stop-color: var(--svg-color--807491, #807491);
}

.ve04rzb3f {
  stop-color: var(--svg-color--cac5d0, #CAC5D0);
  stop-opacity: 0;
}

.w_qb-zz_q {
  stop-color: var(--svg-color--6b4da4, #6B4DA4);
  stop-opacity: 0;
}

.wg968sbbv {
  stop-color: var(--svg-color--af97c7, #AF97C7);
}

.wox-bybuw {
  stop-color: var(--svg-color--b4afbc, #B4AFBC);
}

.xoipp876r {
  stop-color: var(--svg-color--5d5583, #5D5583);
}

</style>
