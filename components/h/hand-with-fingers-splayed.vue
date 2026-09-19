<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i0Lowhe)"><path class="l1ojvebhx"/><path fill="url(#igOCqrb)" class="oclkj3b_e"/><path fill="url(#iPMaa2b)" class="oclkj3b_e"/></g><g filter="url(#iwjtSuc)"><path class="ji35zvb_m"/></g><path fill="url(#idmIWeb)" class="l3yprorsp"/><path fill="url(#ibZUHSd)" class="l3yprorsp"/><g filter="url(#i7OwEwc)"><path class="nc5dd-bwc"/></g><path fill="url(#iHJMvoe)" class="sc-gytp_y"/><path fill="url(#iUcA84d)" class="sc-gytp_y"/><path fill="url(#iMFUoac)" class="sc-gytp_y"/><path fill="url(#iXv3fEe)" class="sc-gytp_y"/><path fill="url(#iyBGDcc)" class="sc-gytp_y"/><g filter="url(#iKNWY8d)"><path class="bm_-lxghj"/></g><path fill="url(#iKUYfnb)" class="s8yccubfp"/><path fill="url(#iNGYJ2c)" class="s8yccubfp"/><path fill="url(#ieyHg8b)" class="s8yccubfp"/><path fill="url(#iV6vvdc)" class="s8yccubfp"/><path fill="url(#ix7TSub)" class="s8yccubfp"/><path fill="url(#iv6M0Id)" class="s8yccubfp"/><g filter="url(#ihuzFLe)"><path stroke="url(#iDYWqhd)" class="a9etxybfs"/></g><path fill="url(#iY9C2rg)" class="ehw7uqban"/><path fill="url(#iFOhy5b)" class="ehw7uqban"/><path fill="url(#imRzIWb)" class="ehw7uqban"/><path fill="url(#iJnpRbe)" class="ehw7uqban"/><g filter="url(#iBW8Hye)"><path stroke="url(#iUF34Uz)" class="wrn2qvpjw"/></g><g filter="url(#iu9mLBI)"><path stroke="url(#iokczAc)" class="spzvncc1a"/></g><path fill="url(#inqIWtd)" class="oclkj3b_e"/><path fill="url(#iTx0XAe)" class="oclkj3b_e"/><path fill="url(#i8kHzab)" class="oclkj3b_e"/><path fill="url(#im1eb8b)" class="oclkj3b_e"/><path fill="url(#iakBqce)" class="oclkj3b_e"/><defs><radialGradient id="igOCqrb" cx="0" cy="0" r="1" gradientTransform="rotate(162.091 11.104 8.207)scale(21.5439 35.6329)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="nj9iqtbxt"/><stop offset="1" class="p0d-gqmyc"/></radialGradient><radialGradient id="iPMaa2b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25965 -5.35333 11.99579 -2.82264 20.674 27.015)" gradientUnits="userSpaceOnUse"><stop class="cmfwf7b3m"/><stop offset="1" class="rvj7ocbif"/></radialGradient><radialGradient id="iMFUoac" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 -.125 1.0637 7.71184 8.24 13.429)" gradientUnits="userSpaceOnUse"><stop class="jzsiojb7a"/><stop offset="1" class="o3aagk31j"/></radialGradient><radialGradient id="iyBGDcc" cx="0" cy="0" r="1" gradientTransform="rotate(58.762 .568 9.775)scale(2.71164 3.33266)" gradientUnits="userSpaceOnUse"><stop class="df1-pbbwn"/><stop offset="1" class="hb8digx3r"/></radialGradient><radialGradient id="ieyHg8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 -.14063 .82423 -4.48734 18.084 12.367)" gradientUnits="userSpaceOnUse"><stop class="r7y21vb4e"/><stop offset="1" class="lyhuktbwr"/></radialGradient><radialGradient id="iV6vvdc" cx="0" cy="0" r="1" gradientTransform="matrix(1.85792 .12598 -.55446 8.17727 11.922 12.594)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="r7y21vb4e"/><stop offset="1" class="lyhuktbwr"/></radialGradient><radialGradient id="ix7TSub" cx="0" cy="0" r="1" gradientTransform="matrix(.8993 3.08605 -4.6524 1.35576 15.1 1.57)" gradientUnits="userSpaceOnUse"><stop class="dq4qw5daa"/><stop offset="1" class="m0y4bvbuj"/></radialGradient><radialGradient id="imRzIWb" cx="0" cy="0" r="1" gradientTransform="rotate(86.629 8.2 13.01)scale(2.96891 .47158)" gradientUnits="userSpaceOnUse"><stop class="dq4qw5daa"/><stop offset="1" class="m0y4bvbuj"/></radialGradient><radialGradient id="iJnpRbe" cx="0" cy="0" r="1" gradientTransform="rotate(-155.639 12.702 5.798)scale(1.09854 3.0178)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="tkjwlunaw"/><stop offset="1" class="zkxm6qb0r"/></radialGradient><radialGradient id="inqIWtd" cx="0" cy="0" r="1" gradientTransform="rotate(149.088 12.674 11.228)scale(3.21012 4.30538)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></radialGradient><radialGradient id="iTx0XAe" cx="0" cy="0" r="1" gradientTransform="rotate(124.237 10.578 9.036)scale(2.72162 3.51855)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></radialGradient><radialGradient id="i8kHzab" cx="0" cy="0" r="1" gradientTransform="rotate(115.187 8.414 6.774)scale(3.65668 4.0446)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></radialGradient><radialGradient id="im1eb8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.64998 2.7415 -2.6143 -.61983 11.281 4.234)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></radialGradient><radialGradient id="iakBqce" cx="0" cy="0" r="1" gradientTransform="rotate(109.44 .391 6.373)scale(1.6901 1.80451)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></radialGradient><linearGradient id="idmIWeb" x1="8.538" x2="7.944" y1="12.07" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="zoth-obxo"/><stop offset="1" class="fwolbsx6p"/></linearGradient><linearGradient id="ibZUHSd" x1="9.381" x2="7.866" y1="15.538" y2="14.804" gradientUnits="userSpaceOnUse"><stop class="l1q9t0b4m"/><stop offset="1" class="e4xk64bwe"/></linearGradient><linearGradient id="iHJMvoe" x1="13.35" x2="12.616" y1="10.132" y2="10.195" gradientUnits="userSpaceOnUse"><stop class="pou5-fhtp"/><stop offset="1" class="hwopmvbnw"/></linearGradient><linearGradient id="iUcA84d" x1="7.662" x2="10.569" y1="10.788" y2="10.463" gradientUnits="userSpaceOnUse"><stop class="inxfieqfn"/><stop offset="1" class="chmurpb6s"/></linearGradient><linearGradient id="iXv3fEe" x1="13.475" x2="12.756" y1="14.913" y2="12.57" gradientUnits="userSpaceOnUse"><stop class="l1q9t0b4m"/><stop offset="1" class="e4xk64bwe"/></linearGradient><linearGradient id="iKUYfnb" x1="12.35" x2="15.256" y1="8.788" y2="9.195" gradientUnits="userSpaceOnUse"><stop class="u0ijg4b_j"/><stop offset="1" class="smglpl-wu"/></linearGradient><linearGradient id="iNGYJ2c" x1="18.365" x2="17.319" y1="11.463" y2="11.305" gradientUnits="userSpaceOnUse"><stop class="hqaga8b8y"/><stop offset="1" class="eoln5ptso"/></linearGradient><linearGradient id="iv6M0Id" x1="14.896" x2="15.194" y1="14.938" y2="11.726" gradientUnits="userSpaceOnUse"><stop class="l1q9t0b4m"/><stop offset="1" class="e4xk64bwe"/></linearGradient><linearGradient id="iDYWqhd" x1="21.475" x2="25.256" y1="14.726" y2="1.82" gradientUnits="userSpaceOnUse"><stop class="rb_5d-bcl"/><stop offset="1" class="hgaovzbdo"/></linearGradient><linearGradient id="iY9C2rg" x1="17.525" x2="20.881" y1="9.506" y2="10.775" gradientUnits="userSpaceOnUse"><stop class="wcyzgac_a"/><stop offset="1" class="uhasexvcb"/></linearGradient><linearGradient id="iFOhy5b" x1="17.998" x2="18.848" y1="16.592" y2="14.86" gradientUnits="userSpaceOnUse"><stop class="l1q9t0b4m"/><stop offset="1" class="e4xk64bwe"/></linearGradient><linearGradient id="iUF34Uz" x1="27.725" x2="27.228" y1="15.413" y2="21.284" gradientUnits="userSpaceOnUse"><stop class="rb_5d-bcl"/><stop offset="1" class="hgaovzbdo"/></linearGradient><linearGradient id="iokczAc" x1="18.029" x2="3.418" y1="17.064" y2="17.82" gradientUnits="userSpaceOnUse"><stop class="wvw_iccfb"/><stop offset="1" class="gc-5zl1_f"/></linearGradient><filter id="i0Lowhe" width="26.723" height="28.316" x="2.994" y="1.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.486275 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1337"/></filter><filter id="iwjtSuc" width="6.71" height="11.835" x="3.184" y="6.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1337" stdDeviation=".9"/></filter><filter id="i7OwEwc" width="6.36" height="12.844" x="8.147" y="3.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1337" stdDeviation="1"/></filter><filter id="iKNWY8d" width="6.422" height="14.453" x="13.287" y="1.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1337" stdDeviation="1"/></filter><filter id="ihuzFLe" width="6.219" height="12.656" x="18.787" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1337" stdDeviation=".625"/></filter><filter id="iBW8Hye" width="10.125" height="9.875" x="19.6" y="13.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1337" stdDeviation=".75"/></filter><filter id="iu9mLBI" width="17.782" height="6.78" x="4.383" y="12.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1337" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-fingers-splayed" /></template>
<style>
.a9etxybfs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.413 16.476c.354-1.25 1.468-5.256 2.968-9.406");
}

.bm_-lxghj {
  stroke: var(--svg-color--ffda3e, #FFDA3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.96 4.71l-.922 8.953");
}

.chmurpb6s {
  stop-color: var(--svg-color--e29208, #E29208);
  stop-opacity: 0;
}

.cmfwf7b3m {
  stop-color: var(--svg-color--ffcc46, #FFCC46);
}

.df1-pbbwn {
  stop-color: var(--svg-color--e2a53a, #E2A53A);
}

.dq4qw5daa {
  stop-color: var(--svg-color--dba737, #DBA737);
}

.e4xk64bwe {
  stop-color: var(--svg-color--ffc23f, #FFC23F);
  stop-opacity: 0;
}

.ehw7uqban {
  d: path("m21.526 16.433l-.008.004q.145-.556.309-1.128c.764-2.663 1.808-5.5 2.586-7.468q.094-.24.137-.487c.202-1.147-.419-2.33-1.567-2.706c-1.453-.422-2.621.365-3.094 1.594c-.28.621-.585 1.374-.904 2.206c-.35.913-.714 1.921-1.075 2.954l.004-.032l-.01.042l-.599 2.03c-.184.63-.397 2.08 1.04 3c1.435.92 2.837.598 3.176 0z");
}

.eoln5ptso {
  stop-color: var(--svg-color--cd8921, #CD8921);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwolbsx6p {
  stop-color: var(--svg-color--d38c08, #D38C08);
  stop-opacity: 0;
}

.gc-5zl1_f {
  stop-color: var(--svg-color--ffd544, #FFD544);
  stop-opacity: 0;
}

.hb8digx3r {
  stop-color: var(--svg-color--e2a53a, #E2A53A);
  stop-opacity: 0;
}

.hgaovzbdo {
  stop-color: var(--svg-color--ffda3e, #FFDA3E);
  stop-opacity: 0;
}

.hqaga8b8y {
  stop-color: var(--svg-color--cd8921, #CD8921);
}

.hwopmvbnw {
  stop-color: var(--svg-color--c78a3b, #C78A3B);
  stop-opacity: 0;
}

.inxfieqfn {
  stop-color: var(--svg-color--e29208, #E29208);
}

.ji35zvb_m {
  stroke: var(--svg-color--ffda3e, #FFDA3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.734 9.054l1.61 6.734");
}

.jzsiojb7a {
  stop-color: var(--svg-color--743200, #743200);
}

.l_iu3xbdk {
  stop-color: var(--svg-color--ffe949, #FFE949);
  stop-opacity: 0;
}

.l1ojvebhx {
  fill: var(--svg-color--ffc23f, #FFC23F);
  d: path("M14.046 4.124a2.415 2.415 0 1 1 4.784.666l-.92 6.613c.69-1.975 1.393-3.857 1.98-5.162c.472-1.228 1.64-2.015 3.093-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.125 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176a24 24 0 0 1-1.293 1.824a10 10 0 0 1-2.304 2.148l-.009-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.291-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.53-3.709l-.756-3.082a2.415 2.415 0 1 1 4.69-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.l1q9t0b4m {
  stop-color: var(--svg-color--ffc23f, #FFC23F);
}

.l3yprorsp {
  d: path("m4.37 17.4l-.02-.174a25 25 0 0 0-.53-3.709l-.756-3.082a2.415 2.415 0 1 1 4.69-1.15l.656 2.676l.87 3.32c.266 1.905-2.672 3.574-4.91 2.12");
}

.lyhuktbwr {
  stop-color: var(--svg-color--854104, #854104);
  stop-opacity: 0;
}

.m0y4bvbuj {
  stop-color: var(--svg-color--dba737, #DBA737);
  stop-opacity: 0;
}

.nc5dd-bwc {
  stroke: var(--svg-color--ffda3e, #FFDA3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.897 6.32l.86 7.343");
}

.nj9iqtbxt {
  stop-color: var(--svg-color--f5a732, #F5A732);
  stop-opacity: 0;
}

.o3aagk31j {
  stop-color: var(--svg-color--743200, #743200);
  stop-opacity: 0;
}

.oclkj3b_e {
  d: path("M14.046 4.124a2.415 2.415 0 1 1 4.784.666l-.92 6.613c.69-1.975 1.393-3.857 1.98-5.162c.472-1.228 1.64-2.015 3.093-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.125 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176a24 24 0 0 1-1.293 1.824a10 10 0 0 1-2.304 2.148l-.009-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.291-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.53-3.709l-.756-3.082a2.415 2.415 0 1 1 4.69-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.p0d-gqmyc {
  stop-color: var(--svg-color--f5a732, #F5A732);
}

.pou5-fhtp {
  stop-color: var(--svg-color--c78a3b, #C78A3B);
}

.r7y21vb4e {
  stop-color: var(--svg-color--854104, #854104);
}

.rb_5d-bcl {
  stop-color: var(--svg-color--ffda3e, #FFDA3E);
}

.rhhh3kv2j {
  stop-color: var(--svg-color--ffe949, #FFE949);
}

.rvj7ocbif {
  stop-color: var(--svg-color--ffcc46, #FFCC46);
  stop-opacity: 0;
}

.s8yccubfp {
  d: path("M13.455 14.38c.31.287.72.536 1.254.69c1.613.462 2.493-1.04 2.688-1.985l.513-1.683l.92-6.612a2.415 2.415 0 0 0-4.784-.666l-.899 6.463z");
}

.sc-gytp_y {
  d: path("M13.475 14.632c0 .766-.422 1.828-1.766 2.047c-1.427.232-2.306-1.061-2.504-1.582l-.804-3.164l-.404-5.104a2.415 2.415 0 1 1 4.814-.388z");
}

.smglpl-wu {
  stop-color: var(--svg-color--d58c07, #D58C07);
  stop-opacity: 0;
}

.spzvncc1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.134 16.56c1.952-.965 7.142-2.317 12.28 0");
}

.tkjwlunaw {
  stop-color: var(--svg-color--dfa63d, #DFA63D);
}

.u0ijg4b_j {
  stop-color: var(--svg-color--d58c07, #D58C07);
}

.uhasexvcb {
  stop-color: var(--svg-color--ce8716, #CE8716);
  stop-opacity: 0;
}

.wcyzgac_a {
  stop-color: var(--svg-color--ce8716, #CE8716);
}

.wrn2qvpjw {
  stroke-linecap: round;
  d: path("M27.725 15.413c-1.333.855-4.425 3.225-6.125 5.875");
}

.wvw_iccfb {
  stop-color: var(--svg-color--ffd544, #FFD544);
}

.zkxm6qb0r {
  stop-color: var(--svg-color--dfa63d, #DFA63D);
  stop-opacity: 0;
}

.zoth-obxo {
  stop-color: var(--svg-color--d38c08, #D38C08);
}

</style>
