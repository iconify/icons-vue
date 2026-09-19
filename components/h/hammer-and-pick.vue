<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPJnUJd)"><path class="e61-7wb3x"/><path fill="url(#imlFyHy)" class="l8rjiwbzb"/><path fill="url(#iebrAZc)" class="l8rjiwbzb"/></g><path fill="url(#iXrkSic)" class="l8rjiwbzb"/><path fill="url(#iVPfUOb)" class="l8rjiwbzb"/><path fill="url(#i1FZPzc)" class="l8rjiwbzb"/><path fill="url(#irQN8wV)" class="l8rjiwbzb"/><path fill="url(#inWPKZp)" class="l8rjiwbzb"/><g filter="url(#iwHjRXY)"><path fill="url(#iWgSIDq)" class="bog7zw9ca"/><path fill="url(#iFnsdhc)" class="bog7zw9ca"/><path fill="url(#iBHDq9d)" class="bog7zw9ca"/></g><g filter="url(#iZZc9cb)"><path class="djytvabxs"/><path fill="url(#iE00MEe)" class="apkw_ubsu"/><path fill="url(#ipLkfPd)" class="apkw_ubsu"/></g><path fill="url(#i4yFkSb)" class="apkw_ubsu"/><path fill="url(#ibNqLYb)" class="apkw_ubsu"/><path fill="url(#iTUOnCc)" class="apkw_ubsu"/><g filter="url(#ihzHeve)"><path fill="url(#iCMHONd)" transform="rotate(-45 10.7 11.309)" class="x3hlz9ypi"/></g><g filter="url(#iWo8Ndd)"><path fill="url(#iZ2KK1r)" transform="rotate(-45 18.875 20.234)" class="xuqu7jbbb"/></g><g filter="url(#iP1ItVd)"><path fill="url(#ilLjAjp)" transform="scale(-1 1)rotate(-45 18.177 28.002)" class="n9m44_xxg"/></g><g filter="url(#iYdjicb)"><path fill="url(#iXPWEye)" class="hd0qp8bvq"/><path fill="url(#iCMbOze)" class="hd0qp8bvq"/><path fill="url(#iKXcbce)" class="hd0qp8bvq"/></g><defs><linearGradient id="imlFyHy" x1="2.984" x2="7.867" y1="26.778" y2="21.895" gradientUnits="userSpaceOnUse"><stop offset=".065" class="kgv3yxbue"/><stop offset="1" class="e31_17snh"/></linearGradient><linearGradient id="iebrAZc" x1="17.176" x2="13.171" y1="19.717" y2="15.572" gradientUnits="userSpaceOnUse"><stop offset=".058" class="m1mq_hbaa"/><stop offset="1" class="g8jajs8rt"/></linearGradient><linearGradient id="iVPfUOb" x1="29.109" x2="16.141" y1="5.063" y2="18.25" gradientUnits="userSpaceOnUse"><stop offset=".471" class="r7dz2wbmp"/><stop offset="1" class="esc_m31gw"/></linearGradient><linearGradient id="iWgSIDq" x1="23.655" x2="26.256" y1="3.161" y2="15.493" gradientUnits="userSpaceOnUse"><stop class="tjj0raj0b"/><stop offset="1" class="i9g5uwb_s"/></linearGradient><linearGradient id="iFnsdhc" x1="20.064" x2="21.575" y1="4.168" y2="5.628" gradientUnits="userSpaceOnUse"><stop class="q7kcjdbmc"/><stop offset="1" class="r6yw7zbfg"/></linearGradient><linearGradient id="iBHDq9d" x1="22.883" x2="24.041" y1="12.473" y2="11.316" gradientUnits="userSpaceOnUse"><stop class="f1r-z3_mj"/><stop offset="1" class="z3bk5ub_w"/></linearGradient><linearGradient id="iE00MEe" x1="29.232" x2="24.349" y1="26.616" y2="21.733" gradientUnits="userSpaceOnUse"><stop offset=".065" class="kgv3yxbue"/><stop offset="1" class="e31_17snh"/></linearGradient><linearGradient id="ipLkfPd" x1="15.039" x2="19.044" y1="19.555" y2="15.409" gradientUnits="userSpaceOnUse"><stop offset=".058" class="m1mq_hbaa"/><stop offset="1" class="g8jajs8rt"/></linearGradient><linearGradient id="iCMHONd" x1="10.964" x2="11.02" y1="12.066" y2="21.413" gradientUnits="userSpaceOnUse"><stop class="w_u_rhbst"/><stop offset="1" class="rmau5hbgg"/></linearGradient><linearGradient id="iZ2KK1r" x1="19.744" x2="19.76" y1="20.973" y2="30.09" gradientUnits="userSpaceOnUse"><stop class="ot02i3ueq"/><stop offset="1" class="ywtoqn53o"/></linearGradient><linearGradient id="ilLjAjp" x1=".497" x2=".588" y1="9.347" y2=".178" gradientUnits="userSpaceOnUse"><stop class="uz5vn86ga"/><stop offset="1" class="tovghdccl"/></linearGradient><linearGradient id="iXPWEye" x1="8.195" x2="8.195" y1="4.875" y2="16.239" gradientUnits="userSpaceOnUse"><stop class="pl537vbbl"/><stop offset="1" class="ycopytb1g"/></linearGradient><linearGradient id="iCMbOze" x1="5.064" x2="5.87" y1="7.037" y2="7.742" gradientUnits="userSpaceOnUse"><stop class="wp31v5x5w"/><stop offset="1" class="aasc_ac5p"/></linearGradient><linearGradient id="iKXcbce" x1="13.269" x2="12.59" y1="4.571" y2="5.25" gradientUnits="userSpaceOnUse"><stop offset=".106" class="p4ajf1uih"/><stop offset="1" class="c8q-m9b-k"/></linearGradient><radialGradient id="iXrkSic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93751 2.1875 -5.42317 -4.80341 15.547 18.313)" gradientUnits="userSpaceOnUse"><stop class="hgh6tubnu"/><stop offset="1" class="e70sunbha"/></radialGradient><radialGradient id="i1FZPzc" cx="0" cy="0" r="1" gradientTransform="matrix(5.56245 -5.5938 1.0344 1.0286 4.016 25.75)" gradientUnits="userSpaceOnUse"><stop class="fvk3mq_lu"/><stop offset="1" class="gxa9nhbrj"/></radialGradient><radialGradient id="irQN8wV" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .34374 -1.108 -1.00728 13.874 20.047)" gradientUnits="userSpaceOnUse"><stop class="w65ty0bvk"/><stop offset="1" class="or3ta-b7m"/></radialGradient><radialGradient id="inWPKZp" cx="0" cy="0" r="1" gradientTransform="rotate(134.453 12.433 7.793)scale(13.8776 1.86565)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="gwnu5vbsx"/><stop offset="1" class="w-nmwbcmn"/></radialGradient><radialGradient id="i4yFkSb" cx="0" cy="0" r="1" gradientTransform="rotate(110.866 1.503 4.724)scale(3.50943 3.02107)" gradientUnits="userSpaceOnUse"><stop class="v82w97b1v"/><stop offset="1" class="c7rbyibkh"/></radialGradient><radialGradient id="ibNqLYb" cx="0" cy="0" r="1" gradientTransform="rotate(45 -8.365 17.894)scale(2.23181 5.67895)" gradientUnits="userSpaceOnUse"><stop class="v82w97b1v"/><stop offset="1" class="c7rbyibkh"/></radialGradient><radialGradient id="iTUOnCc" cx="0" cy="0" r="1" gradientTransform="rotate(135 6.21 13.006)scale(3.40295 1.5468)" gradientUnits="userSpaceOnUse"><stop class="q-dl9jw8y"/><stop offset="1" class="xu-g48b6p"/></radialGradient><filter id="iPJnUJd" width="24.59" height="24.759" x="4.202" y="4.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.384314 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23875"/></filter><filter id="iwHjRXY" width="11.906" height="13.69" x="17.452" y="2.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.847059 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23875"/></filter><filter id="iZZc9cb" width="24.027" height="24.177" x="3.986" y="4.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.384314 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23875"/></filter><filter id="ihzHeve" width="8.798" height="8.798" x="10.099" y="10.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23875" stdDeviation=".3"/></filter><filter id="iWo8Ndd" width="10.853" height="10.853" x="17.675" y="17.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23875" stdDeviation=".6"/></filter><filter id="iP1ItVd" width="11.189" height="11.189" x="4.487" y="18.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23875" stdDeviation=".6"/></filter><filter id="iYdjicb" width="14.197" height="14.697" x="1.097" y="1.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.572549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23875"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hammer-and-pick" /></template>
<style>
.aasc_ac5p {
  stop-color: var(--svg-color--9b95a2, #9B95A2);
  stop-opacity: 0;
}

.apkw_ubsu {
  d: path("M4.06 6.815a.25.25 0 0 0 0 .354L16.514 19.62l.035.037a1 1 0 0 1 .254.63l.012.317a2 2 0 0 0 .584 1.341l7.01 7.01a.25.25 0 0 0 .354 0l3.177-3.178a.25.25 0 0 0 0-.353l-7.014-7.014a2 2 0 0 0-1.33-.584l-.326-.014a1 1 0 0 1-.662-.29l-.256-.253l-.002.002L6.153 5.075a.25.25 0 0 0-.353 0z");
}

.bog7zw9ca {
  d: path("M23.591 2.66a1.25 1.25 0 0 0-1.767 0l-3.506 3.506a1.25 1.25 0 0 0 0 1.768l7.437 7.437c.975.975 2.643.491 2.945-.855l.513-2.292a6 6 0 0 0-1.612-5.554z");
}

.c7rbyibkh {
  stop-color: var(--svg-color--603b37, #603B37);
  stop-opacity: 0;
}

.c8q-m9b-k {
  stop-color: var(--svg-color--c4bdcc, #C4BDCC);
  stop-opacity: 0;
}

.djytvabxs {
  fill: var(--svg-color--a3796e, #A3796E);
  d: path("M4.06 6.815a.25.25 0 0 0 0 .354L16.514 19.62l.035.037a1 1 0 0 1 .254.63l.012.317a2 2 0 0 0 .584 1.341l7.01 7.01a.25.25 0 0 0 .354 0l3.177-3.178a.25.25 0 0 0 0-.353l-7.014-7.014a2 2 0 0 0-1.33-.584l-.326-.014a1 1 0 0 1-.662-.29l-.256-.253l-.002.002L6.153 5.075a.25.25 0 0 0-.353 0z");
}

.e31_17snh {
  stop-color: var(--svg-color--7f494f, #7F494F);
  stop-opacity: 0;
}

.e61-7wb3x {
  fill: var(--svg-color--a3796e, #A3796E);
  d: path("M28.719 6.396a.25.25 0 0 1 0 .354L15.7 19.784l-.034.037a1 1 0 0 0-.255.63l-.012.317a2 2 0 0 1-.584 1.34l-7.01 7.01a.25.25 0 0 1-.353 0l-3.178-3.177a.25.25 0 0 1 0-.354l7.014-7.014a2 2 0 0 1 1.33-.584l.326-.013a1 1 0 0 0 .663-.29l.256-.254l.002.002l12.76-12.778a.25.25 0 0 1 .354 0z");
}

.e70sunbha {
  stop-color: var(--svg-color--5c2e34, #5C2E34);
  stop-opacity: 0;
}

.esc_m31gw {
  stop-color: var(--svg-color--603345, #603345);
  stop-opacity: 0;
}

.f1r-z3_mj {
  stop-color: var(--svg-color--906faa, #906FAA);
}

.ft5dv1b6b {
  fill: none;
}

.fvk3mq_lu {
  stop-color: var(--svg-color--a68b85, #A68B85);
}

.g8jajs8rt {
  stop-color: var(--svg-color--7c425a, #7C425A);
  stop-opacity: 0;
}

.gwnu5vbsx {
  stop-color: var(--svg-color--715b5a, #715B5A);
}

.gxa9nhbrj {
  stop-color: var(--svg-color--a68b85, #A68B85);
  stop-opacity: 0;
}

.hd0qp8bvq {
  d: path("M9.786 2.277a.8.8 0 0 1 1.131 0l4.142 4.142a.8.8 0 0 1 0 1.131l-8.454 8.455a.8.8 0 0 1-1.132 0l-4.142-4.142a.8.8 0 0 1 0-1.132z");
}

.hgh6tubnu {
  stop-color: var(--svg-color--5c2e34, #5C2E34);
}

.i9g5uwb_s {
  stop-color: var(--svg-color--af9fbf, #AF9FBF);
}

.kgv3yxbue {
  stop-color: var(--svg-color--7f494f, #7F494F);
}

.l8rjiwbzb {
  d: path("M28.719 6.396a.25.25 0 0 1 0 .354L15.7 19.784l-.034.037a1 1 0 0 0-.255.63l-.012.317a2 2 0 0 1-.584 1.34l-7.01 7.01a.25.25 0 0 1-.353 0l-3.178-3.177a.25.25 0 0 1 0-.354l7.014-7.014a2 2 0 0 1 1.33-.584l.326-.013a1 1 0 0 0 .663-.29l.256-.254l.002.002l12.76-12.778a.25.25 0 0 1 .354 0z");
}

.m1mq_hbaa {
  stop-color: var(--svg-color--733464, #733464);
}

.n9m44_xxg {
  d: path("M0 0h2.099v10.33H0z");
}

.or3ta-b7m {
  stop-color: var(--svg-color--8d6a69, #8D6A69);
  stop-opacity: 0;
}

.ot02i3ueq {
  stop-color: var(--svg-color--9a726d, #9A726D);
}

.p4ajf1uih {
  stop-color: var(--svg-color--c4bdcc, #C4BDCC);
}

.pl537vbbl {
  stop-color: var(--svg-color--a99eb3, #A99EB3);
}

.q-dl9jw8y {
  stop-color: var(--svg-color--794b41, #794B41);
}

.q7kcjdbmc {
  stop-color: var(--svg-color--9d99a1, #9D99A1);
}

.r6yw7zbfg {
  stop-color: var(--svg-color--9d99a1, #9D99A1);
  stop-opacity: 0;
}

.r7dz2wbmp {
  stop-color: var(--svg-color--603345, #603345);
}

.rmau5hbgg {
  stop-color: var(--svg-color--926d6b, #926D6B);
}

.tjj0raj0b {
  stop-color: var(--svg-color--aa9eb8, #AA9EB8);
}

.tovghdccl {
  stop-color: var(--svg-color--8b5864, #8B5864);
}

.uz5vn86ga {
  stop-color: var(--svg-color--935c68, #935C68);
}

.v82w97b1v {
  stop-color: var(--svg-color--603b37, #603B37);
}

.w_u_rhbst {
  stop-color: var(--svg-color--8f6d6c, #8F6D6C);
}

.w-nmwbcmn {
  stop-color: var(--svg-color--715b5a, #715B5A);
  stop-opacity: 0;
}

.w65ty0bvk {
  stop-color: var(--svg-color--8d6a69, #8D6A69);
}

.wp31v5x5w {
  stop-color: var(--svg-color--9b95a2, #9B95A2);
}

.x3hlz9ypi {
  d: path("M10.699 11.309h.641v10.104h-.641z");
}

.xu-g48b6p {
  stop-color: var(--svg-color--794b41, #794B41);
  stop-opacity: 0;
}

.xuqu7jbbb {
  d: path("M18.875 20.234h2.099v9.855h-2.099z");
}

.ycopytb1g {
  stop-color: var(--svg-color--bda6d3, #BDA6D3);
}

.ywtoqn53o {
  stop-color: var(--svg-color--a0716e, #A0716E);
}

.z3bk5ub_w {
  stop-color: var(--svg-color--ae98c3, #AE98C3);
  stop-opacity: 0;
}

</style>
