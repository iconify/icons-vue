<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGICRETdzN" x1="49.994%" x2="49.994%" y1=".226%" y2="99.725%"><stop offset="0%" class="lksp3gt7g"/><stop offset="66%" class="gjuor2bpt"/></linearGradient><linearGradient id="SVGPN4omccq" x1="36.626%" x2="64.01%" y1="20.358%" y2="100.652%"><stop offset="0%" class="dk8d3t44m"/><stop offset="100%" class="stui2mbih"/></linearGradient><linearGradient id="SVGpecrgAGw" x1="68.935%" x2="31.065%" y1="65.756%" y2="35.799%"><stop offset="0%" class="o18fyxbgj"/><stop offset="100%" class="b8btyqb8s"/></linearGradient><linearGradient id="SVGLUBszbWP" x1="62.531%" x2="24.779%" y1="13.086%" y2="100.996%"><stop offset="0%" class="o18fyxbgj"/><stop offset="100%" class="b8btyqb8s"/></linearGradient><linearGradient id="SVGTsQK6cSw" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="o18fyxbgj"/><stop offset="100%" class="b8btyqb8s"/></linearGradient><path id="SVGIUTKp2rM" class="e2moz0qdx"/><path id="SVG4Cc6jeMG" class="dcwa4qblj"/><path id="SVGsauddeCj" class="x0_83tyor"/><path id="SVGMn4Yrd1Y" class="m-yox4x9o"/><path id="SVGyFcYRckV" class="z5tuulbtv"/><path id="SVGsP4sGdiH" class="jmqhy_ldh"/><radialGradient id="SVGkOYyLd2f" cx="10.105%" cy="14.269%" r="144.565%" fx="10.105%" fy="14.269%" gradientTransform="matrix(.68182 0 0 1 .032 0)"><stop offset="0%" class="dk8d3t44m"/><stop offset="100%" class="stui2mbih"/></radialGradient><radialGradient id="SVGTCLUYd1O" cx="14.489%" cy="14.584%" r="99.973%" fx="14.489%" fy="14.584%"><stop offset="0%" class="dk8d3t44m"/><stop offset="100%" class="stui2mbih"/></radialGradient><radialGradient id="SVGkwwRAdjY" cx="10.105%" cy="14.269%" r="144.568%" fx="10.105%" fy="14.269%" gradientTransform="matrix(.68181 0 0 1 .032 0)"><stop offset="0%" class="dk8d3t44m"/><stop offset="100%" class="stui2mbih"/></radialGradient><filter id="SVGfTbhlbLT" width="159.3%" height="134.8%" x="-29.7%" y="-12.4%" filterUnits="objectBoundingBox"><feOffset dy="2" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="2"/><feColorMatrix in="shadowBlurOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/></filter><filter id="SVGFLKEUOMR" width="151.4%" height="130.1%" x="-25.7%" y="-10.8%" filterUnits="objectBoundingBox"><feOffset dy="2" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="2"/><feColorMatrix in="shadowBlurOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.1 0"/></filter></defs><g class="ft5dv1b6b"><circle class="pdygfrbtr"/><path class="t7bw_5mxx"/><g transform="translate(158.51 73.81)"><mask id="SVGj013bj3L" class="n1mjunbsu"><use href="#SVGIUTKp2rM"/></mask><g mask="url(#SVGj013bj3L)"><path class="d3e-_qg9y"/><path class="lso520bsp"/><path fill="url(#SVGICRETdzN)" class="q1m7vd6od"/><g transform="translate(23.594 15.73)"><mask id="SVG5ruVOd1e" class="n1mjunbsu"><use href="#SVG4Cc6jeMG"/></mask><g mask="url(#SVG5ruVOd1e)"><g transform="translate(-.72 -16.45)"><use filter="url(#SVGfTbhlbLT)" href="#SVGsauddeCj" class="ivjvz2eii"/><use href="#SVGsauddeCj" class="ar77q_88i"/></g></g></g><circle class="dsct2hddo"/><path class="ooc7b2bxs"/><path class="ph5-apbdb"/></g></g><path fill="url(#SVGkOYyLd2f)" class="pu25xacxm"/><path class="f-xmvob4j"/><path class="jy15_-bhc"/><path class="kn4lx1bmx"/><path class="f6j9ox_8g"/><path fill="url(#SVGPN4omccq)" class="x4wj1kb_n"/><path fill="url(#SVGpecrgAGw)" class="fizmcjw5b"/><path fill="url(#SVGLUBszbWP)" class="bjolwhbwe"/><path fill="url(#SVGTsQK6cSw)" transform="matrix(-1 0 0 1 197.473 0)" class="eup21rbrq"/><circle fill="url(#SVGTCLUYd1O)" class="bjgkos9ns"/><path class="om2agnuie"/><g transform="translate(31.217 100.913)"><mask id="SVGLOTy0ciP" class="n1mjunbsu"><use href="#SVGMn4Yrd1Y"/></mask><g mask="url(#SVGLOTy0ciP)"><path class="o3rvtmbdx"/><path class="kbcyqoj9b"/><path fill="url(#SVGICRETdzN)" class="m6cu19bah"/><g transform="translate(27.225 18.15)"><mask id="SVGt3PrsbmF" class="n1mjunbsu"><use href="#SVGyFcYRckV"/></mask><g mask="url(#SVGt3PrsbmF)"><g transform="translate(-.445 -18.594)"><use filter="url(#SVGFLKEUOMR)" href="#SVGsP4sGdiH" class="ivjvz2eii"/><use href="#SVGsP4sGdiH" class="ar77q_88i"/></g></g></g><circle class="lo-9-bcxe"/><path class="xnpkz9b5h"/><path class="t6jmc9bqt"/></g></g><path fill="url(#SVGkwwRAdjY)" class="v9rrufsxj"/><g class="gjs9mpioz"><path class="n8k9c5j5d"/><path class="fri3e9ycw"/></g><circle fill="url(#SVGTCLUYd1O)" class="bjgkos9ns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lighthouse" /></template>
<style>
.ar77q_88i {
  fill: var(--svg-color--e1e1e1, #e1e1e1);
}

.b8btyqb8s {
  stop-color: var(--svg-color--262626, #262626);
  stop-opacity: 0;
}

.bjgkos9ns {
  cx: 127.777px;
  cy: 127.777px;
  r: 127.777px;
}

.bjolwhbwe {
  d: path("M127.777 255.551a127.7 127.7 0 0 1-63.24-16.72l14.56-109.604h48.678v126.324z");
}

.d3e-_qg9y {
  fill: var(--svg-color--eaeaea, #eaeaea);
  d: path("M53.483 15.73h-7.645C42.598 6.56 33.866 0 23.594 0C10.57 0 0 10.57 0 23.594s10.57 23.597 23.594 23.597h29.889c8.686-.004 15.727-7.045 15.73-15.732c-.004-8.686-7.044-15.726-15.73-15.73");
}

.dcwa4qblj {
  d: path("M29.887 0H0v31.459h29.887c8.685-.004 15.725-7.044 15.729-15.73C45.612 7.045 38.572.005 29.886 0");
}

.dk8d3t44m {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.1;
}

.dsct2hddo {
  cx: 23.594px;
  cy: 23.594px;
  r: 23.594px;
  fill: var(--svg-color--eee, #eee);
}

.e2moz0qdx {
  d: path("M53.483 15.73h-7.645C42.598 6.56 33.866 0 23.594 0C10.57 0 0 10.57 0 23.594s10.57 23.597 23.594 23.597h29.889c8.686-.004 15.727-7.045 15.73-15.732c-.004-8.686-7.044-15.726-15.73-15.73");
}

.eup21rbrq {
  d: path("M69.696 105.997h58.081v23.232H69.696z");
}

.f-xmvob4j {
  fill: var(--svg-color--fff176, #fff176);
  d: path("M92.929 53.725h66.792v58.08H92.929z");
}

.f6j9ox_8g {
  fill: var(--svg-color--f4481e, #f4481e);
  d: path("m64.536 238.83l19.68-132.835h87.12l19.679 132.836c-18.646 10.641-40.232 16.72-63.238 16.72c-23.007 0-44.593-6.079-63.24-16.72m89.253-92.758l-54.655 17.76l-6.643 44.833l67.33-21.88l-6.032-40.715z");
}

.fizmcjw5b {
  d: path("M127.777 105.997H81.311V59.531l46.466-29.039z");
}

.fri3e9ycw {
  fill: var(--svg-color--263238, #263238);
  d: path("M255.538 127.108c-.364 70.262-57.412 127.108-127.761 127.108c-70.35 0-127.4-56.846-127.762-127.108c0 .233-.015.45-.015.669C0 198.344 57.21 255.55 127.777 255.55S255.55 198.344 255.55 127.777c0-.218-.013-.436-.013-.669");
}

.ft5dv1b6b {
  fill: none;
}

.gjs9mpioz {
  opacity: var(--svg-opacity--0-1, 0.1);
}

.gjuor2bpt {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.jmqhy_ldh {
  d: path("m.445.445l14.719 46.483C20.084 41.99 27.67 35.184 27.67 27.67C27.67 12.642 15.473.445.445.445");
}

.jy15_-bhc {
  fill: var(--svg-color--fff, #fff);
  d: path("M85.667 142.295h79.861v79.861H85.667z");
}

.kbcyqoj9b {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M79.86 36.519V36.3c0-10.02-8.132-18.152-18.15-18.152h-9.074v.455h9.073c9.933 0 18.02 7.983 18.152 17.915");
}

.kn4lx1bmx {
  fill: var(--svg-color--f4481e, #f4481e);
  d: path("M174.24 105.997h11.615v23.23H69.696v-23.23h11.615V59.53l46.466-29.039l46.463 29.04zm-23.233 0v-33.59l-23.23-14.516l-23.233 14.517v33.589z");
}

.lksp3gt7g {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0.04;
}

.lo-9-bcxe {
  cx: 27.225px;
  cy: 27.225px;
  r: 27.225px;
  fill: var(--svg-color--fff, #fff);
}

.lso520bsp {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M69.212 31.649v-.19c-.003-8.686-7.043-15.726-15.729-15.73h-7.867v.393h7.867c8.609.001 15.617 6.92 15.73 15.529z");
}

.m-yox4x9o {
  d: path("M61.71 18.15h-8.822C49.151 7.568 39.078 0 27.225 0C12.197 0 0 12.197 0 27.225S12.197 54.45 27.225 54.45h34.484c10.02 0 18.152-8.13 18.152-18.15c0-10.018-8.133-18.15-18.152-18.15");
}

.m6cu19bah {
  d: path("M89.206 54.45H27.225l25.683-36.301z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n8k9c5j5d {
  fill: var(--svg-color--fff, #fff);
  d: path("M127.777 1.335c70.35 0 127.397 56.846 127.761 127.108c0-.218.013-.435.013-.666C255.551 57.21 198.344 0 127.777 0S0 57.21 0 127.777c0 .217.015.435.015.666C.377 58.181 57.427 1.335 127.777 1.335");
}

.o18fyxbgj {
  stop-color: var(--svg-color--262626, #262626);
  stop-opacity: 0.1;
}

.o3rvtmbdx {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M61.71 18.15h-8.822C49.151 7.568 39.078 0 27.225 0C12.197 0 0 12.197 0 27.225S12.197 54.45 27.225 54.45h34.484c10.02 0 18.152-8.13 18.152-18.15c0-10.018-8.133-18.15-18.152-18.15");
}

.om2agnuie {
  d: path("M27.589 82.764h87.12v87.12h-87.12z");
}

.ooc7b2bxs {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M23.594.392c12.962 0 23.486 10.461 23.597 23.407v-.187C47.19 10.587 36.619.015 23.594.015C10.57.015 0 10.57 0 23.595v.189C.109 10.853 10.633.392 23.594.392");
}

.pdygfrbtr {
  cx: 127.777px;
  cy: 127.777px;
  r: 127.777px;
  fill: var(--svg-color--0535c1, #0535c1);
}

.ph5-apbdb {
  fill: var(--svg-color--212121, #212121);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M53.483 46.796H23.594C10.635 46.796.111 36.336 0 23.392v.19c0 13.024 10.57 23.593 23.594 23.593h29.889c8.686-.003 15.726-7.043 15.73-15.729v-.187c-.109 8.61-7.118 15.536-15.73 15.54z");
}

.pu25xacxm {
  d: path("M211.993 89.54h-7.644c-3.241-9.17-11.973-15.73-22.244-15.73c-13.025 0-23.595 10.57-23.595 23.594s10.57 23.597 23.595 23.597h29.888c8.687-.004 15.727-7.045 15.73-15.732c-.004-8.685-7.044-15.726-15.73-15.73");
}

.q1m7vd6od {
  d: path("M77.312 47.191H23.594L45.853 15.73z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t6jmc9bqt {
  fill: var(--svg-color--212121, #212121);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M61.71 53.997H27.224C12.269 53.997.126 41.927 0 26.99v.218c0 15.028 12.197 27.225 27.225 27.225h34.484c10.02 0 18.152-8.133 18.152-18.152v-.218c-.129 9.93-8.205 17.934-18.152 17.934");
}

.t7bw_5mxx {
  d: path("M155.363 58.081h75.505v75.504h-75.505z");
}

.v9rrufsxj {
  d: path("M92.927 119.063h-8.821c-3.738-10.581-13.811-18.15-25.664-18.15c-15.028 0-27.225 12.197-27.225 27.225s12.197 27.225 27.225 27.225h34.485c10.018 0 18.151-8.13 18.151-18.149s-8.133-18.151-18.151-18.151");
}

.x0_83tyor {
  d: path("m.72.72l12.756 40.284c4.26-4.28 10.838-10.178 10.838-16.69C24.314 11.29 13.744.72.72.72");
}

.x4wj1kb_n {
  d: path("m174.129 129.227l16.237 109.604c-18.646 10.641-40.232 16.72-63.238 16.72c-23.007 0-44.593-6.079-63.24-16.72l16.238-109.604h-10.43v-23.23h11.615V59.53l46.466-29.039l46.463 29.04v46.465h11.615v23.23H174.13");
}

.xnpkz9b5h {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M27.225.453c14.956 0 27.099 12.07 27.225 27.007v-.218C54.45 12.214 42.253.017 27.225.017S0 12.197 0 27.225v.218C.126 12.523 12.269.453 27.225.453");
}

.z5tuulbtv {
  d: path("M34.484 0H0v36.3h34.484c10.02 0 18.152-8.132 18.152-18.15C52.636 8.13 44.503 0 34.484 0");
}

</style>
