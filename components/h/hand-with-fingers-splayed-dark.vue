<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#il6smZd)"><path class="buzzgibur"/><path fill="url(#iMI9yxe)" class="b3szag0eu"/><path fill="url(#iFxkuUc)" class="b3szag0eu"/></g><path fill="url(#i0DJnHd)" class="nv7cu4bsu"/><path fill="url(#iSB7Dbc)" class="nv7cu4bsu"/><g filter="url(#iUMgkPc)"><path class="w1sgtxb5h"/></g><path fill="url(#iLndAtd)" class="ln9bh8bli"/><path fill="url(#iJnQ1kb)" class="ln9bh8bli"/><path fill="url(#iB47f1p)" class="ln9bh8bli"/><path fill="url(#iAn9rwX)" class="ln9bh8bli"/><path fill="url(#i0Y8yRG)" class="ln9bh8bli"/><path fill="url(#iBMCefb)" class="ln9bh8bli"/><path fill="url(#iZrZu0o)" class="yaakutb3z"/><path fill="url(#iUQHU6d)" class="yaakutb3z"/><path fill="url(#iNVFkue)" class="yaakutb3z"/><path fill="url(#iDQWG6c)" class="yaakutb3z"/><g filter="url(#igraUqd)"><path class="kxdho6bla"/></g><g filter="url(#iD0CCbd)"><path stroke="url(#idAVjqc)" class="rj7r7mn5o"/></g><g filter="url(#iCQbr0b)"><path stroke="url(#iQ12aue)" class="vs42d0bky"/></g><path fill="url(#iYfJrJd)" class="cu8qy7bam"/><path fill="url(#iaYxKeb)" class="cu8qy7bam"/><path fill="url(#iSuxied)" class="cu8qy7bam"/><g filter="url(#iu4xaae)"><path stroke="url(#iyOaCvc)" class="cyxe9kdog"/></g><path fill="url(#iwwu6Je)" class="b3szag0eu"/><path fill="url(#iC0p8vk)" class="b3szag0eu"/><path fill="url(#ivRuSno)" class="b3szag0eu"/><path fill="url(#itOn07c)" class="b3szag0eu"/><path fill="url(#iMgtoIe)" class="b3szag0eu"/><g filter="url(#iqgln9d)"><path stroke="url(#i97sDCJ)" class="a64o18b2b"/></g><g filter="url(#ifGgUHe)"><path stroke="url(#ivtnEzc)" class="x-wfh68jq"/></g><g filter="url(#iiGk74d)"><path stroke="url(#iOtKpob)" class="b5to99ryy"/></g><g filter="url(#iHkaOud)"><path stroke="url(#izwbchb)" class="i5n3yo_4m"/></g><defs><linearGradient id="i0DJnHd" x1="9.443" x2="8.849" y1="12.07" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="vte6syb8p"/><stop offset="1" class="lwq_tmbkn"/></linearGradient><linearGradient id="iSB7Dbc" x1="10.46" x2="8.771" y1="15.993" y2="14.804" gradientUnits="userSpaceOnUse"><stop class="zujlh0ooq"/><stop offset="1" class="usyjoccdp"/></linearGradient><linearGradient id="iLndAtd" x1="13.255" x2="16.161" y1="8.788" y2="9.195" gradientUnits="userSpaceOnUse"><stop class="t00x1lb2b"/><stop offset="1" class="kunl4sllw"/></linearGradient><linearGradient id="iJnQ1kb" x1="19.27" x2="18.224" y1="11.463" y2="11.305" gradientUnits="userSpaceOnUse"><stop class="zthnik08w"/><stop offset="1" class="vx_y1db5l"/></linearGradient><linearGradient id="iBMCefb" x1="15.801" x2="16.099" y1="14.938" y2="11.726" gradientUnits="userSpaceOnUse"><stop class="j8qvdbb-n"/><stop offset="1" class="vdljnwb7q"/></linearGradient><linearGradient id="iZrZu0o" x1="14.255" x2="13.521" y1="10.132" y2="10.195" gradientUnits="userSpaceOnUse"><stop class="h6hzpeqiq"/><stop offset="1" class="t4587jbtf"/></linearGradient><linearGradient id="iUQHU6d" x1="8.567" x2="11.474" y1="10.788" y2="10.463" gradientUnits="userSpaceOnUse"><stop class="i1qx6fbqb"/><stop offset="1" class="kwbuu-bni"/></linearGradient><linearGradient id="iDQWG6c" x1="13.847" x2="13.424" y1="15.318" y2="11.97" gradientUnits="userSpaceOnUse"><stop offset=".29" class="zujlh0ooq"/><stop offset="1" class="usyjoccdp"/></linearGradient><linearGradient id="idAVjqc" x1="17.887" x2="16.713" y1="6.821" y2="16.608" gradientUnits="userSpaceOnUse"><stop class="w-iwpvbqx"/><stop offset="1" class="cmzx9vb6f"/></linearGradient><linearGradient id="iQ12aue" x1="22.38" x2="26.161" y1="14.726" y2="1.82" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></linearGradient><linearGradient id="iYfJrJd" x1="18.43" x2="21.785" y1="9.506" y2="10.775" gradientUnits="userSpaceOnUse"><stop class="jneuh0suz"/><stop offset="1" class="jsyp66b8s"/></linearGradient><linearGradient id="iaYxKeb" x1="19.063" x2="19.971" y1="17.277" y2="13.281" gradientUnits="userSpaceOnUse"><stop class="zujlh0ooq"/><stop offset="1" class="usyjoccdp"/></linearGradient><linearGradient id="iyOaCvc" x1="28.63" x2="28.133" y1="15.413" y2="21.284" gradientUnits="userSpaceOnUse"><stop class="uvbb_ob1p"/><stop offset="1" class="h-5k69ibw"/></linearGradient><linearGradient id="i97sDCJ" x1="9.617" x2="7.872" y1="16.357" y2="17.172" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="jvjb-yvus"/></linearGradient><linearGradient id="ivtnEzc" x1="13.474" x2="11.556" y1="14.283" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="jvjb-yvus"/></linearGradient><linearGradient id="iOtKpob" x1="16.942" x2="15.354" y1="14.767" y2="13.677" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="jvjb-yvus"/></linearGradient><linearGradient id="izwbchb" x1="20.974" x2="19.386" y1="17.295" y2="16.206" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="jvjb-yvus"/></linearGradient><radialGradient id="iMI9yxe" cx="0" cy="0" r="1" gradientTransform="rotate(162.091 11.557 8.278)scale(21.5439 35.6329)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="j4vl0dbto"/><stop offset="1" class="fxvp7ob8x"/></radialGradient><radialGradient id="iFxkuUc" cx="0" cy="0" r="1" gradientTransform="rotate(141.22 6.034 15.435)scale(4.29081 7.10858)" gradientUnits="userSpaceOnUse"><stop class="hcqj0acdc"/><stop offset="1" class="cbal8bcrs"/></radialGradient><radialGradient id="iB47f1p" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 -.14063 .82423 -4.48734 18.99 12.367)" gradientUnits="userSpaceOnUse"><stop class="rc_c5re_z"/><stop offset="1" class="snuy1rbbd"/></radialGradient><radialGradient id="iAn9rwX" cx="0" cy="0" r="1" gradientTransform="matrix(1.85793 .12596 -.5544 8.17728 12.825 12.592)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="b8jq6c11g"/><stop offset="1" class="t_fb--bzp"/></radialGradient><radialGradient id="i0Y8yRG" cx="0" cy="0" r="1" gradientTransform="rotate(73.753 6.956 11.453)scale(3.21441 4.84592)" gradientUnits="userSpaceOnUse"><stop class="t1hu-8bzb"/><stop offset="1" class="fw6p16k8z"/></radialGradient><radialGradient id="iNVFkue" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 -.125 1.0637 7.71184 9.146 13.429)" gradientUnits="userSpaceOnUse"><stop class="rhrvh39ao"/><stop offset="1" class="wgwc66buj"/></radialGradient><radialGradient id="iSuxied" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00074 -.47343 1.30056 -2.74911 22.786 16.32)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="pg6_0w_iu"/><stop offset="1" class="f_skm_bmo"/></radialGradient><radialGradient id="iwwu6Je" cx="0" cy="0" r="1" gradientTransform="rotate(149.088 13.127 11.354)scale(3.21012 4.30538)" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></radialGradient><radialGradient id="iC0p8vk" cx="0" cy="0" r="1" gradientTransform="rotate(124.237 11.03 9.276)scale(2.72162 3.51855)" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></radialGradient><radialGradient id="ivRuSno" cx="0" cy="0" r="1" gradientTransform="rotate(115.187 8.867 7.06)scale(3.65668 4.0446)" gradientUnits="userSpaceOnUse"><stop class="e20tfjr2m"/><stop offset="1" class="h0oicdclb"/></radialGradient><radialGradient id="itOn07c" cx="0" cy="0" r="1" gradientTransform="matrix(-.64998 2.7415 -2.6143 -.61983 12.186 4.234)" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></radialGradient><radialGradient id="iMgtoIe" cx="0" cy="0" r="1" gradientTransform="rotate(109.44 .844 6.693)scale(1.6901 1.80451)" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></radialGradient><filter id="il6smZd" width="26.723" height="28.316" x="3.898" y="1.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2875 0 0 0 0 0.161719 0 0 0 0 0.273524 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1350"/></filter><filter id="iUMgkPc" width="6.882" height="12.069" x="4.136" y="6.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".9"/></filter><filter id="igraUqd" width="6.199" height="12.268" x="9.052" y="3.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation="1"/></filter><filter id="iD0CCbd" width="6.422" height="14.453" x="14.159" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation="1"/></filter><filter id="iCQbr0b" width="6.219" height="12.656" x="19.692" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".625"/></filter><filter id="iu4xaae" width="10.125" height="9.875" x="20.505" y="13.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".75"/></filter><filter id="iqgln9d" width="3.406" height="3.61" x="6.999" y="14.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".25"/></filter><filter id="ifGgUHe" width="4.015" height="2.827" x="10.561" y="12.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".25"/></filter><filter id="iiGk74d" width="4.047" height="2.406" x="14.457" y="12.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".25"/></filter><filter id="iHkaOud" width="4.047" height="2.406" x="18.488" y="15.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1350" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-fingers-splayed-dark" /></template>
<style>
.a64o18b2b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.749 17.547c.828-.5 1.437-1.016 1.906-2.11");
}

.b3szag0eu {
  d: path("M14.951 4.124a2.415 2.415 0 1 1 4.784.666l-.92 6.613c.69-1.975 1.393-3.857 1.98-5.162c.472-1.228 1.64-2.015 3.093-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.125 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.304 2.148l-.009-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.53-3.709l-.757-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.b5to99ryy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.207 13.538c.546.644 1.63 1.135 2.547.794");
}

.b8jq6c11g {
  stop-color: var(--svg-color--190a0c, #190A0C);
}

.buzzgibur {
  fill: var(--svg-color--4d3536, #4D3536);
  d: path("M14.951 4.124a2.415 2.415 0 1 1 4.784.666l-.92 6.613c.69-1.975 1.393-3.857 1.98-5.162c.472-1.228 1.64-2.015 3.093-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.125 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.304 2.148l-.009-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.53-3.709l-.757-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.cbal8bcrs {
  stop-color: var(--svg-color--533c3d, #533C3D);
  stop-opacity: 0;
}

.cmzx9vb6f {
  stop-color: var(--svg-color--6f5552, #6F5552);
  stop-opacity: 0;
}

.cu8qy7bam {
  d: path("m22.431 16.433l-.008.004q.145-.556.309-1.128c.764-2.663 1.808-5.5 2.585-7.468q.096-.24.138-.487c.202-1.147-.419-2.33-1.567-2.706c-1.453-.422-2.621.365-3.094 1.594a44 44 0 0 0-.904 2.206c-.35.913-.714 1.921-1.076 2.954l.005-.032l-.01.042l-.599 2.03c-.184.63-.397 2.08 1.04 3c1.435.92 2.837.598 3.176 0z");
}

.cyxe9kdog {
  stroke-linecap: round;
  d: path("M28.63 15.413c-1.333.855-4.425 3.225-6.125 5.875");
}

.dbxn0ya4l {
  stop-color: var(--svg-color--5d4846, #5D4846);
}

.e20tfjr2m {
  stop-color: var(--svg-color--755754, #755754);
}

.f_skm_bmo {
  stop-color: var(--svg-color--493a38, #493A38);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fw6p16k8z {
  stop-color: var(--svg-color--4c3d3a, #4C3D3A);
  stop-opacity: 0;
}

.fxvp7ob8x {
  stop-color: var(--svg-color--3d2829, #3D2829);
}

.h-5k69ibw {
  stop-color: var(--svg-color--634e4d, #634E4D);
  stop-opacity: 0;
}

.h0oicdclb {
  stop-color: var(--svg-color--755754, #755754);
  stop-opacity: 0;
}

.h6hzpeqiq {
  stop-color: var(--svg-color--301c1a, #301C1A);
}

.hcqj0acdc {
  stop-color: var(--svg-color--533c3d, #533C3D);
}

.i1qx6fbqb {
  stop-color: var(--svg-color--231314, #231314);
}

.i5n3yo_4m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.238 16.066c.546.644 1.63 1.135 2.547.794");
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.j4vl0dbto {
  stop-color: var(--svg-color--3d2829, #3D2829);
  stop-opacity: 0;
}

.j8qvdbb-n {
  stop-color: var(--svg-color--4d3637, #4D3637);
}

.jneuh0suz {
  stop-color: var(--svg-color--271514, #271514);
}

.jsyp66b8s {
  stop-color: var(--svg-color--271514, #271514);
  stop-opacity: 0;
}

.jvjb-yvus {
  stop-color: var(--svg-color--5d4846, #5D4846);
  stop-opacity: 0;
}

.kbuu85jbe {
  stop-color: var(--svg-color--624e4c, #624E4C);
}

.kunl4sllw {
  stop-color: var(--svg-color--1f0f0f, #1F0F0F);
  stop-opacity: 0;
}

.kwbuu-bni {
  stop-color: var(--svg-color--231314, #231314);
  stop-opacity: 0;
}

.kxdho6bla {
  stroke: var(--svg-color--6f5552, #6F5552);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.802 6.32l.698 6.768");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.ln9bh8bli {
  d: path("M14.36 14.38c.31.287.72.536 1.254.69c1.613.462 2.492-1.04 2.688-1.985l.512-1.683l.92-6.612a2.415 2.415 0 1 0-4.783-.666l-.9 6.463z");
}

.lwq_tmbkn {
  stop-color: var(--svg-color--3e2623, #3E2623);
  stop-opacity: 0;
}

.nv7cu4bsu {
  d: path("m5.275 17.4l-.02-.174a25 25 0 0 0-.53-3.709l-.757-3.082a2.415 2.415 0 1 1 4.691-1.15l.656 2.676l.87 3.32c.266 1.905-2.672 3.574-4.91 2.12");
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.pg6_0w_iu {
  stop-color: var(--svg-color--452f2b, #452F2B);
}

.q59v_vbuo {
  stop-color: var(--svg-color--624e4c, #624E4C);
  stop-opacity: 0;
}

.rc_c5re_z {
  stop-color: var(--svg-color--281615, #281615);
}

.rhrvh39ao {
  stop-color: var(--svg-color--1d0a0a, #1D0A0A);
}

.rj7r7mn5o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.83 4.338l-.921 8.953");
}

.snuy1rbbd {
  stop-color: var(--svg-color--281615, #281615);
  stop-opacity: 0;
}

.t_fb--bzp {
  stop-color: var(--svg-color--190a0c, #190A0C);
  stop-opacity: 0;
}

.t00x1lb2b {
  stop-color: var(--svg-color--1f0f0f, #1F0F0F);
}

.t1hu-8bzb {
  stop-color: var(--svg-color--4c3d3a, #4C3D3A);
}

.t4587jbtf {
  stop-color: var(--svg-color--301c1a, #301C1A);
  stop-opacity: 0;
}

.usyjoccdp {
  stop-color: var(--svg-color--4d3536, #4D3536);
  stop-opacity: 0;
}

.uvbb_ob1p {
  stop-color: var(--svg-color--634e4d, #634E4D);
}

.vdljnwb7q {
  stop-color: var(--svg-color--4d3637, #4D3637);
  stop-opacity: 0;
}

.vs42d0bky {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M21.317 16.476c.355-1.25 1.47-5.256 2.97-9.406");
}

.vte6syb8p {
  stop-color: var(--svg-color--3e2623, #3E2623);
}

.vx_y1db5l {
  stop-color: var(--svg-color--271817, #271817);
  stop-opacity: 0;
}

.w-iwpvbqx {
  stop-color: var(--svg-color--6f5552, #6F5552);
}

.w1sgtxb5h {
  stroke: var(--svg-color--6c5451, #6C5451);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.686 9.313l1.781 6.968");
}

.wgwc66buj {
  stop-color: var(--svg-color--1d0a0a, #1D0A0A);
  stop-opacity: 0;
}

.x-wfh68jq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.311 14.759c.95-.185 1.699-.46 2.515-1.327");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.yaakutb3z {
  d: path("M14.38 14.632c0 .766-.422 1.828-1.766 2.047c-1.427.232-2.306-1.061-2.504-1.582l-.804-3.164l-.404-5.104a2.415 2.415 0 1 1 4.814-.388z");
}

.zthnik08w {
  stop-color: var(--svg-color--271817, #271817);
}

.zujlh0ooq {
  stop-color: var(--svg-color--4d3536, #4D3536);
}

</style>
