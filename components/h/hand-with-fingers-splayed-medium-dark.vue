<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifw4sHg)"><path class="jx3jbvngz"/><path fill="url(#ivbEOHe)" class="napfbyb6j"/><path fill="url(#iNfeFec)" class="napfbyb6j"/></g><path fill="url(#iivpN6b)" class="iq2o_qbpb"/><path fill="url(#iRDrSIJ)" class="iq2o_qbpb"/><g filter="url(#ivCAUnd)"><path class="dqsseqr0t"/></g><path fill="url(#i8PTz5c)" class="wf7f97g9x"/><path fill="url(#i2SgWcb)" class="wf7f97g9x"/><path fill="url(#ivg1sIb)" class="wf7f97g9x"/><path fill="url(#iNh2Wud)" class="wf7f97g9x"/><path fill="url(#iB2kode)" class="wf7f97g9x"/><path fill="url(#iFBkKtd)" class="wf7f97g9x"/><path fill="url(#iNyL2Oi)" class="zjpfdh45p"/><path fill="url(#iDZ1vKd)" class="zjpfdh45p"/><path fill="url(#iaDb5ze)" class="zjpfdh45p"/><path fill="url(#i3klPub)" class="zjpfdh45p"/><path fill="url(#ic9Hgpd)" class="zjpfdh45p"/><g filter="url(#i43BYud)"><path class="rb2bz2bsd"/></g><g filter="url(#iW7Z50c)"><path stroke="url(#iCKppZc)" class="jm0zesbdo"/></g><g filter="url(#i6XazOc)"><path stroke="url(#iXcnudJ)" class="lqq7iqafp"/></g><path fill="url(#ipJEImb)" class="k3w305xui"/><path fill="url(#i5DMAEb)" class="k3w305xui"/><path fill="url(#iYTQ45P)" class="k3w305xui"/><g filter="url(#iTovbJc)"><path stroke="url(#i66kbDc)" class="ul23egxep"/></g><path fill="url(#iXcpOLP)" class="napfbyb6j"/><path fill="url(#iyCrCmc)" class="napfbyb6j"/><path fill="url(#ihJNkqe)" class="napfbyb6j"/><path fill="url(#iyRZk7y)" class="napfbyb6j"/><path fill="url(#iyWRKlz)" class="napfbyb6j"/><g filter="url(#itxztde)"><path stroke="url(#iJZupqb)" class="sm1addcji"/></g><g filter="url(#iR26oFc)"><path stroke="url(#iGIh09d)" class="yl8izo-9a"/></g><g filter="url(#iMb2bub)"><path stroke="url(#il1IU0d)" class="ocju3ln3y"/></g><g filter="url(#iOLHQ5c)"><path stroke="url(#igDOl8d)" class="mw4c-dn2n"/></g><defs><linearGradient id="iivpN6b" x1="8.962" x2="8.019" y1="12.07" y2="12.309" gradientUnits="userSpaceOnUse"><stop class="sj4ry3ocw"/><stop offset="1" class="jlzk6qbrl"/></linearGradient><linearGradient id="iRDrSIJ" x1="9.98" x2="8.29" y1="15.993" y2="14.804" gradientUnits="userSpaceOnUse"><stop class="w1asmxmqf"/><stop offset="1" class="bh_c_ktha"/></linearGradient><linearGradient id="i8PTz5c" x1="13.572" x2="15.681" y1="8.999" y2="9.195" gradientUnits="userSpaceOnUse"><stop class="pe5rnec0m"/><stop offset="1" class="adjuo3b2o"/></linearGradient><linearGradient id="i2SgWcb" x1="18.79" x2="17.744" y1="11.463" y2="11.305" gradientUnits="userSpaceOnUse"><stop class="qrh7-x26o"/><stop offset="1" class="v3_ufwbqo"/></linearGradient><linearGradient id="iFBkKtd" x1="15.321" x2="15.618" y1="14.938" y2="11.726" gradientUnits="userSpaceOnUse"><stop class="w1asmxmqf"/><stop offset="1" class="bh_c_ktha"/></linearGradient><linearGradient id="iNyL2Oi" x1="14.41" x2="13.025" y1="10.075" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="d4mbhmfan"/><stop offset="1" class="t4587jbtf"/><stop offset="1" class="fxrhuv7af"/></linearGradient><linearGradient id="iDZ1vKd" x1="8.414" x2="10.993" y1="10.825" y2="10.463" gradientUnits="userSpaceOnUse"><stop class="a0og4gblk"/><stop offset="1" class="fo__5eick"/></linearGradient><linearGradient id="i3klPub" x1="13.366" x2="12.944" y1="15.318" y2="11.97" gradientUnits="userSpaceOnUse"><stop offset=".29" class="w1asmxmqf"/><stop offset="1" class="bh_c_ktha"/></linearGradient><linearGradient id="iCKppZc" x1="17.407" x2="16.233" y1="6.821" y2="16.608" gradientUnits="userSpaceOnUse"><stop class="uyv3-kbgy"/><stop offset="1" class="o2vbi_b7o"/></linearGradient><linearGradient id="iXcnudJ" x1="21.9" x2="25.681" y1="14.726" y2="1.82" gradientUnits="userSpaceOnUse"><stop class="b0u3bcc4v"/><stop offset="1" class="lymwh_bva"/></linearGradient><linearGradient id="ipJEImb" x1="18.307" x2="21.305" y1="9.768" y2="10.775" gradientUnits="userSpaceOnUse"><stop class="c69m816mg"/><stop offset="1" class="v2qym0b5g"/></linearGradient><linearGradient id="i5DMAEb" x1="18.207" x2="19.77" y1="16.688" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="w1asmxmqf"/><stop offset="1" class="bh_c_ktha"/></linearGradient><linearGradient id="i66kbDc" x1="28.15" x2="27.653" y1="15.413" y2="21.284" gradientUnits="userSpaceOnUse"><stop class="eegxolbhf"/><stop offset="1" class="dicqufbhu"/></linearGradient><linearGradient id="iJZupqb" x1="9.137" x2="7.392" y1="16.357" y2="17.172" gradientUnits="userSpaceOnUse"><stop class="f4lbkzxzo"/><stop offset="1" class="avaukpeow"/></linearGradient><linearGradient id="iGIh09d" x1="12.994" x2="11.075" y1="14.283" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="f4lbkzxzo"/><stop offset="1" class="avaukpeow"/></linearGradient><linearGradient id="il1IU0d" x1="16.581" x2="14.918" y1="14.695" y2="13.744" gradientUnits="userSpaceOnUse"><stop class="f4lbkzxzo"/><stop offset="1" class="avaukpeow"/></linearGradient><linearGradient id="igDOl8d" x1="20.613" x2="18.95" y1="17.223" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="f4lbkzxzo"/><stop offset="1" class="avaukpeow"/></linearGradient><radialGradient id="ivbEOHe" cx="0" cy="0" r="1" gradientTransform="rotate(162.091 11.316 8.24)scale(21.5439 35.6329)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="lewvvgbgi"/><stop offset="1" class="prkeaabuo"/></radialGradient><radialGradient id="iNfeFec" cx="0" cy="0" r="1" gradientTransform="rotate(141.22 5.794 15.35)scale(4.29081 7.10858)" gradientUnits="userSpaceOnUse"><stop class="hdk36ccnl"/><stop offset="1" class="zp3t7s-zd"/></radialGradient><radialGradient id="ivg1sIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 -.14063 .82423 -4.48734 18.51 12.367)" gradientUnits="userSpaceOnUse"><stop class="f5yu43afl"/><stop offset="1" class="edhu--n7x"/></radialGradient><radialGradient id="iNh2Wud" cx="0" cy="0" r="1" gradientTransform="matrix(1.85793 .12596 -.5544 8.17728 12.345 12.592)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="f5yu43afl"/><stop offset="1" class="edhu--n7x"/></radialGradient><radialGradient id="iB2kode" cx="0" cy="0" r="1" gradientTransform="rotate(73.753 6.716 11.133)scale(3.21441 4.84592)" gradientUnits="userSpaceOnUse"><stop class="xagptkb_e"/><stop offset="1" class="potp7obeo"/></radialGradient><radialGradient id="iaDb5ze" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 -.125 1.0637 7.71184 8.665 13.429)" gradientUnits="userSpaceOnUse"><stop class="y0b-6_uim"/><stop offset="1" class="gbi70vbsu"/></radialGradient><radialGradient id="ic9Hgpd" cx="0" cy="0" r="1" gradientTransform="rotate(58.762 .78 10.152)scale(2.71164 3.33266)" gradientUnits="userSpaceOnUse"><stop class="w3gokjb6i"/><stop offset="1" class="shzcxtdzk"/></radialGradient><radialGradient id="iYTQ45P" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00074 -.47343 1.30056 -2.74911 22.306 16.32)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ylu6yuo4f"/><stop offset="1" class="jh181qqkz"/></radialGradient><radialGradient id="iXcpOLP" cx="0" cy="0" r="1" gradientTransform="rotate(149.088 12.887 11.287)scale(3.21012 4.30538)" gradientUnits="userSpaceOnUse"><stop class="e0x882b9g"/><stop offset="1" class="z0qt0scgt"/></radialGradient><radialGradient id="iyCrCmc" cx="0" cy="0" r="1" gradientTransform="rotate(124.237 10.79 9.149)scale(2.72162 3.51855)" gradientUnits="userSpaceOnUse"><stop class="e-wllnbzp"/><stop offset="1" class="dydcj5d2k"/></radialGradient><radialGradient id="ihJNkqe" cx="0" cy="0" r="1" gradientTransform="rotate(115.187 8.627 6.908)scale(3.65668 4.0446)" gradientUnits="userSpaceOnUse"><stop class="uyv3-kbgy"/><stop offset="1" class="o2vbi_b7o"/></radialGradient><radialGradient id="iyRZk7y" cx="0" cy="0" r="1" gradientTransform="matrix(-.64998 2.7415 -2.6143 -.61983 11.706 4.234)" gradientUnits="userSpaceOnUse"><stop class="qh725-jas"/><stop offset="1" class="z79i4z1bd"/></radialGradient><radialGradient id="iyWRKlz" cx="0" cy="0" r="1" gradientTransform="rotate(109.44 .604 6.523)scale(1.6901 1.80451)" gradientUnits="userSpaceOnUse"><stop class="qc1581bfp"/><stop offset="1" class="hwz-t-iyf"/></radialGradient><filter id="ifw4sHg" width="26.723" height="28.516" x="3.418" y="1.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.6"/><feGaussianBlur stdDeviation="1.125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.294118 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1366"/></filter><filter id="ivCAUnd" width="6.882" height="12.069" x="3.656" y="6.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".9"/></filter><filter id="i43BYud" width="6.199" height="12.268" x="8.571" y="3.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation="1"/></filter><filter id="iW7Z50c" width="6.422" height="14.453" x="13.678" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation="1"/></filter><filter id="i6XazOc" width="6.219" height="12.656" x="19.212" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".625"/></filter><filter id="iTovbJc" width="10.125" height="9.875" x="20.025" y="13.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".75"/></filter><filter id="itxztde" width="3.406" height="3.61" x="6.518" y="14.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".25"/></filter><filter id="iR26oFc" width="4.015" height="2.827" x="10.081" y="12.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".25"/></filter><filter id="iMb2bub" width="4.047" height="2.406" x="13.976" y="12.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".25"/></filter><filter id="iOLHQ5c" width="4.047" height="2.406" x="18.008" y="15.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1366" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-fingers-splayed-medium-dark" /></template>
<style>
.a0og4gblk {
  stop-color: var(--svg-color--59312a, #59312A);
}

.adjuo3b2o {
  stop-color: var(--svg-color--5e3730, #5E3730);
  stop-opacity: 0;
}

.avaukpeow {
  stop-color: var(--svg-color--9c7971, #9C7971);
  stop-opacity: 0;
}

.b0u3bcc4v {
  stop-color: var(--svg-color--a58174, #A58174);
}

.bh_c_ktha {
  stop-color: var(--svg-color--8c615c, #8C615C);
  stop-opacity: 0;
}

.c69m816mg {
  stop-color: var(--svg-color--5c3831, #5C3831);
}

.d4mbhmfan {
  stop-color: var(--svg-color--61443d, #61443D);
}

.dicqufbhu {
  stop-color: var(--svg-color--a37f72, #A37F72);
  stop-opacity: 0;
}

.dqsseqr0t {
  stroke: var(--svg-color--9c7a71, #9C7A71);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.206 9.313l1.781 6.968");
}

.dydcj5d2k {
  stop-color: var(--svg-color--a47f71, #A47F71);
  stop-opacity: 0;
}

.e-wllnbzp {
  stop-color: var(--svg-color--a47f71, #A47F71);
}

.e0x882b9g {
  stop-color: var(--svg-color--a58072, #A58072);
}

.edhu--n7x {
  stop-color: var(--svg-color--522a26, #522A26);
  stop-opacity: 0;
}

.eegxolbhf {
  stop-color: var(--svg-color--a37f72, #A37F72);
}

.f4lbkzxzo {
  stop-color: var(--svg-color--9c7971, #9C7971);
}

.f5yu43afl {
  stop-color: var(--svg-color--522a26, #522A26);
}

.fo__5eick {
  stop-color: var(--svg-color--59312a, #59312A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxrhuv7af {
  stop-color: var(--svg-color--61443d, #61443D);
  stop-opacity: 0;
}

.gbi70vbsu {
  stop-color: var(--svg-color--592f27, #592F27);
  stop-opacity: 0;
}

.hdk36ccnl {
  stop-color: var(--svg-color--946765, #946765);
}

.hwz-t-iyf {
  stop-color: var(--svg-color--9c796e, #9C796E);
  stop-opacity: 0;
}

.iq2o_qbpb {
  d: path("m4.795 17.4l-.02-.174a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.656 2.676l.87 3.32c.266 1.905-2.672 3.574-4.91 2.12");
}

.jh181qqkz {
  stop-color: var(--svg-color--795f56, #795F56);
  stop-opacity: 0;
}

.jlzk6qbrl {
  stop-color: var(--svg-color--6e4b42, #6E4B42);
  stop-opacity: 0;
}

.jm0zesbdo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.35 4.338l-.922 8.953");
}

.jx3jbvngz {
  fill: var(--svg-color--8c615c, #8C615C);
  d: path("M14.47 4.124a2.415 2.415 0 0 1 4.784.666l-.92 6.613c.69-1.975 1.394-3.857 1.98-5.162c.473-1.228 1.64-2.015 3.094-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.126 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.305 2.148l-.008-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.k3w305xui {
  d: path("m21.95 16.433l-.007.004q.145-.556.309-1.128c.764-2.663 1.808-5.5 2.585-7.468q.096-.24.138-.487c.201-1.147-.419-2.33-1.568-2.706c-1.453-.422-2.62.365-3.093 1.594a44 44 0 0 0-.904 2.206c-.35.913-.714 1.921-1.076 2.954l.005-.032l-.01.042l-.6 2.03c-.183.63-.396 2.08 1.04 3s2.838.598 3.177 0z");
}

.lewvvgbgi {
  stop-color: var(--svg-color--734b49, #734B49);
  stop-opacity: 0;
}

.lqq7iqafp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.837 16.476c.354-1.25 1.469-5.256 2.969-9.406");
}

.lymwh_bva {
  stop-color: var(--svg-color--a58174, #A58174);
  stop-opacity: 0;
}

.mw4c-dn2n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.758 16.066c.546.644 1.63 1.135 2.547.794");
}

.napfbyb6j {
  d: path("M14.47 4.124a2.415 2.415 0 0 1 4.784.666l-.92 6.613c.69-1.975 1.394-3.857 1.98-5.162c.473-1.228 1.64-2.015 3.094-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.126 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.305 2.148l-.008-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.o2vbi_b7o {
  stop-color: var(--svg-color--a37f73, #A37F73);
  stop-opacity: 0;
}

.ocju3ln3y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.726 13.538c.547.644 1.63 1.135 2.548.794");
}

.pe5rnec0m {
  stop-color: var(--svg-color--5e3730, #5E3730);
}

.potp7obeo {
  stop-color: var(--svg-color--7b5e53, #7B5E53);
  stop-opacity: 0;
}

.prkeaabuo {
  stop-color: var(--svg-color--734b49, #734B49);
}

.qc1581bfp {
  stop-color: var(--svg-color--9c796e, #9C796E);
}

.qh725-jas {
  stop-color: var(--svg-color--9c796d, #9C796D);
}

.qrh7-x26o {
  stop-color: var(--svg-color--5c3c36, #5C3C36);
}

.rb2bz2bsd {
  stroke: var(--svg-color--9e7b70, #9E7B70);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.321 6.32l.7 6.768");
}

.shzcxtdzk {
  stop-color: var(--svg-color--75594d, #75594D);
  stop-opacity: 0;
}

.sj4ry3ocw {
  stop-color: var(--svg-color--6e4b42, #6E4B42);
}

.sm1addcji {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.268 17.547c.829-.5 1.438-1.016 1.907-2.11");
}

.t4587jbtf {
  stop-color: var(--svg-color--301c1a, #301C1A);
  stop-opacity: 0;
}

.ul23egxep {
  stroke-linecap: round;
  d: path("M28.15 15.413c-1.334.855-4.425 3.225-6.125 5.875");
}

.uyv3-kbgy {
  stop-color: var(--svg-color--a37f73, #A37F73);
}

.v2qym0b5g {
  stop-color: var(--svg-color--5c3831, #5C3831);
  stop-opacity: 0;
}

.v3_ufwbqo {
  stop-color: var(--svg-color--5c3c36, #5C3C36);
  stop-opacity: 0;
}

.w1asmxmqf {
  stop-color: var(--svg-color--8c615c, #8C615C);
}

.w3gokjb6i {
  stop-color: var(--svg-color--75594d, #75594D);
}

.wf7f97g9x {
  d: path("M13.88 14.38c.31.287.72.536 1.254.69c1.613.462 2.492-1.04 2.688-1.985l.512-1.683l.92-6.612a2.415 2.415 0 0 0-4.783-.666l-.9 6.463z");
}

.xagptkb_e {
  stop-color: var(--svg-color--7b5e53, #7B5E53);
}

.y0b-6_uim {
  stop-color: var(--svg-color--592f27, #592F27);
}

.yl8izo-9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.831 14.759c.95-.185 1.699-.46 2.515-1.327");
}

.ylu6yuo4f {
  stop-color: var(--svg-color--795f56, #795F56);
}

.z0qt0scgt {
  stop-color: var(--svg-color--a58072, #A58072);
  stop-opacity: 0;
}

.z79i4z1bd {
  stop-color: var(--svg-color--9c796d, #9C796D);
  stop-opacity: 0;
}

.zjpfdh45p {
  d: path("M13.9 14.632c0 .766-.422 1.828-1.766 2.047c-1.428.232-2.306-1.061-2.504-1.582l-.804-3.164l-.404-5.104a2.415 2.415 0 1 1 4.814-.388z");
}

.zp3t7s-zd {
  stop-color: var(--svg-color--946765, #946765);
  stop-opacity: 0;
}

</style>
