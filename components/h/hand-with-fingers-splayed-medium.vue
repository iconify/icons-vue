<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iq6mpBL)"><path class="c0li_bcty"/><path fill="url(#iofgDKd)" class="napfbyb6j"/><path fill="url(#iTGVP8b)" class="napfbyb6j"/></g><path fill="url(#icD37Ic)" class="iq2o_qbpb"/><path fill="url(#iGyIoXb)" class="iq2o_qbpb"/><g filter="url(#ichp5FA)"><path class="o71i0wywp"/></g><path fill="url(#iqAoEKe)" class="lvf4egbzb"/><path fill="url(#irm4vhn)" class="lvf4egbzb"/><path fill="url(#is87s5L)" class="lvf4egbzb"/><path fill="url(#i7UKZEd)" class="lvf4egbzb"/><path fill="url(#iUM0GOc)" class="lvf4egbzb"/><g filter="url(#i9YA0Ib)"><path class="evrq-rdbb"/></g><path fill="url(#iFSSwWd)" class="wf7f97g9x"/><path fill="url(#iF9qccO)" class="wf7f97g9x"/><path fill="url(#iNU60Cb)" class="wf7f97g9x"/><path fill="url(#iKU9xrd)" class="wf7f97g9x"/><path fill="url(#iT4aqRb)" class="wf7f97g9x"/><path fill="url(#iybByoe)" class="wf7f97g9x"/><g filter="url(#ipGhDss)"><path stroke="url(#ixgAwYd)" class="jm0zesbdo"/></g><path fill="url(#ie1C0gc)" class="cob7-sk7q"/><path fill="url(#ieKMv9d)" class="cob7-sk7q"/><path fill="url(#iAgutfc)" class="cob7-sk7q"/><g filter="url(#iGGBPLd)"><path stroke="url(#irxhMDd)" class="lqq7iqafp"/></g><g filter="url(#iKkRPzf)"><path stroke="url(#igb5g9b)" class="e6krpwbyv"/></g><path fill="url(#i4zfRSd)" class="napfbyb6j"/><path fill="url(#ipIKHWe)" class="napfbyb6j"/><path fill="url(#igFhB2d)" class="napfbyb6j"/><path fill="url(#iLK5zcv)" class="napfbyb6j"/><path fill="url(#iUg6cOe)" class="napfbyb6j"/><g filter="url(#iaDSoZb)"><path stroke="url(#iCXUHPb)" class="sm1addcji"/></g><g filter="url(#igPNKnJ)"><path stroke="url(#iw2Lw1c)" class="yl8izo-9a"/></g><g filter="url(#i0KWbjd)"><path stroke="url(#iAM9Jve)" class="ocju3ln3y"/></g><g filter="url(#iwnFJ9d)"><path stroke="url(#i1P6y0C)" class="mw4c-dn2n"/></g><defs><linearGradient id="icD37Ic" x1="8.962" x2="8.019" y1="12.07" y2="12.309" gradientUnits="userSpaceOnUse"><stop class="tuv3wmjtl"/><stop offset="1" class="wfbs8lbbx"/></linearGradient><linearGradient id="iGyIoXb" x1="9.98" x2="8.29" y1="15.993" y2="14.804" gradientUnits="userSpaceOnUse"><stop class="eq4-5yxww"/><stop offset="1" class="jyjd2fb4v"/></linearGradient><linearGradient id="iqAoEKe" x1="14.41" x2="13.025" y1="10.075" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="q3oz1fkff"/><stop offset="1" class="t4587jbtf"/><stop offset="1" class="o490qhwdb"/></linearGradient><linearGradient id="irm4vhn" x1="8.414" x2="10.993" y1="10.825" y2="10.463" gradientUnits="userSpaceOnUse"><stop class="w0efsqw6k"/><stop offset="1" class="n5s68wbua"/></linearGradient><linearGradient id="i7UKZEd" x1="13.366" x2="12.944" y1="15.318" y2="11.97" gradientUnits="userSpaceOnUse"><stop offset=".29" class="eq4-5yxww"/><stop offset="1" class="jyjd2fb4v"/></linearGradient><linearGradient id="iFSSwWd" x1="13.572" x2="15.681" y1="8.999" y2="9.195" gradientUnits="userSpaceOnUse"><stop class="y591ksmyk"/><stop offset="1" class="qoerfg7mw"/></linearGradient><linearGradient id="iF9qccO" x1="18.79" x2="17.744" y1="11.463" y2="11.305" gradientUnits="userSpaceOnUse"><stop class="a3lw79b7z"/><stop offset="1" class="q4_a51zzm"/></linearGradient><linearGradient id="iybByoe" x1="15.321" x2="15.618" y1="14.938" y2="11.726" gradientUnits="userSpaceOnUse"><stop class="eq4-5yxww"/><stop offset="1" class="jyjd2fb4v"/></linearGradient><linearGradient id="ixgAwYd" x1="17.407" x2="16.233" y1="6.821" y2="16.608" gradientUnits="userSpaceOnUse"><stop class="qjhm2stkm"/><stop offset="1" class="s5bj0abyc"/></linearGradient><linearGradient id="ie1C0gc" x1="18.307" x2="21.305" y1="9.768" y2="10.775" gradientUnits="userSpaceOnUse"><stop class="y4-6_vq6r"/><stop offset="1" class="pqr0p4b0j"/></linearGradient><linearGradient id="ieKMv9d" x1="18.207" x2="19.77" y1="16.688" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="eq4-5yxww"/><stop offset="1" class="jyjd2fb4v"/></linearGradient><linearGradient id="irxhMDd" x1="21.9" x2="25.681" y1="14.726" y2="1.82" gradientUnits="userSpaceOnUse"><stop class="zf2v4j4cy"/><stop offset="1" class="yq54gjb-q"/></linearGradient><linearGradient id="igb5g9b" x1="28.15" x2="27.653" y1="15.414" y2="21.285" gradientUnits="userSpaceOnUse"><stop class="yr7usdr1u"/><stop offset="1" class="c4hzoxbwx"/></linearGradient><linearGradient id="iCXUHPb" x1="9.137" x2="7.392" y1="16.357" y2="17.172" gradientUnits="userSpaceOnUse"><stop class="k7t9l9bda"/><stop offset="1" class="z9xoncbqq"/></linearGradient><linearGradient id="iw2Lw1c" x1="12.994" x2="11.075" y1="14.283" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="k7t9l9bda"/><stop offset="1" class="z9xoncbqq"/></linearGradient><linearGradient id="iAM9Jve" x1="16.581" x2="14.918" y1="14.695" y2="13.744" gradientUnits="userSpaceOnUse"><stop class="k7t9l9bda"/><stop offset="1" class="z9xoncbqq"/></linearGradient><linearGradient id="i1P6y0C" x1="20.613" x2="18.95" y1="17.223" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="k7t9l9bda"/><stop offset="1" class="z9xoncbqq"/></linearGradient><radialGradient id="iofgDKd" cx="0" cy="0" r="1" gradientTransform="rotate(162.091 11.316 8.24)scale(21.5439 35.6329)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="zi73fml0u"/><stop offset="1" class="qysi05bhg"/></radialGradient><radialGradient id="iTGVP8b" cx="0" cy="0" r="1" gradientTransform="rotate(141.22 5.794 15.35)scale(4.29081 7.10858)" gradientUnits="userSpaceOnUse"><stop class="lesu3ebfc"/><stop offset="1" class="vrp5279ag"/></radialGradient><radialGradient id="is87s5L" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 -.125 1.0637 7.71184 8.665 13.43)" gradientUnits="userSpaceOnUse"><stop class="a6j0qhb4g"/><stop offset="1" class="m8a0b8oay"/></radialGradient><radialGradient id="iUM0GOc" cx="0" cy="0" r="1" gradientTransform="rotate(58.762 .78 10.152)scale(2.71164 3.33266)" gradientUnits="userSpaceOnUse"><stop class="u-s9hqb1d"/><stop offset="1" class="l2k7r6clf"/></radialGradient><radialGradient id="iNU60Cb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 -.14063 .82423 -4.48734 18.51 12.367)" gradientUnits="userSpaceOnUse"><stop class="ommaqbylo"/><stop offset="1" class="v1dstq94l"/></radialGradient><radialGradient id="iKU9xrd" cx="0" cy="0" r="1" gradientTransform="matrix(1.85793 .12596 -.5544 8.17728 12.345 12.592)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="m_7u7lbsj"/><stop offset="1" class="mg2q5fmsa"/></radialGradient><radialGradient id="iT4aqRb" cx="0" cy="0" r="1" gradientTransform="rotate(73.753 6.716 11.133)scale(3.21441 4.84592)" gradientUnits="userSpaceOnUse"><stop class="zr0okx6cw"/><stop offset="1" class="i575q2bns"/></radialGradient><radialGradient id="iAgutfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00074 -.47343 1.30056 -2.74911 22.306 16.32)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="mi1ga_b9w"/><stop offset="1" class="m7nzayi_r"/></radialGradient><radialGradient id="i4zfRSd" cx="0" cy="0" r="1" gradientTransform="rotate(147.308 13.696 11.401)scale(6.01516 1.81793)" gradientUnits="userSpaceOnUse"><stop class="u65ms5b3b"/><stop offset="1" class="iykmbgn4a"/></radialGradient><radialGradient id="ipIKHWe" cx="0" cy="0" r="1" gradientTransform="matrix(1.62446 -.94445 .93393 1.60636 24.24 5.967)" gradientUnits="userSpaceOnUse"><stop class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></radialGradient><radialGradient id="igFhB2d" cx="0" cy="0" r="1" gradientTransform="rotate(-41.606 13.756 -22.063)scale(2.29883 1.9829)" gradientUnits="userSpaceOnUse"><stop class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></radialGradient><radialGradient id="iLK5zcv" cx="0" cy="0" r="1" gradientTransform="rotate(-49.514 11.774 -9.702)scale(2.03652 1.66399)" gradientUnits="userSpaceOnUse"><stop class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></radialGradient><radialGradient id="iUg6cOe" cx="0" cy="0" r="1" gradientTransform="matrix(.68001 -1.2278 1.3352 .7395 6.9 9.14)" gradientUnits="userSpaceOnUse"><stop class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></radialGradient><filter id="iq6mpBL" width="26.723" height="28.516" x="3.418" y="1.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.6"/><feGaussianBlur stdDeviation="1.125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.360784 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1382"/></filter><filter id="ichp5FA" width="6.882" height="12.069" x="3.656" y="6.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".9"/></filter><filter id="i9YA0Ib" width="6.199" height="12.268" x="8.571" y="3.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation="1"/></filter><filter id="ipGhDss" width="6.422" height="14.453" x="13.678" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation="1"/></filter><filter id="iGGBPLd" width="6.219" height="12.656" x="19.212" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".625"/></filter><filter id="iKkRPzf" width="10.125" height="9.875" x="20.025" y="13.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".75"/></filter><filter id="iaDSoZb" width="3.406" height="3.61" x="6.518" y="14.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".25"/></filter><filter id="igPNKnJ" width="4.015" height="2.827" x="10.081" y="12.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".25"/></filter><filter id="i0KWbjd" width="4.047" height="2.406" x="13.976" y="12.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".25"/></filter><filter id="iwnFJ9d" width="4.047" height="2.406" x="18.008" y="15.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1382" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-fingers-splayed-medium" /></template>
<style>
.a3lw79b7z {
  stop-color: var(--svg-color--7c5d50, #7C5D50);
}

.a6j0qhb4g {
  stop-color: var(--svg-color--643d33, #643D33);
}

.c0li_bcty {
  fill: var(--svg-color--b3867a, #B3867A);
  d: path("M14.47 4.124a2.415 2.415 0 0 1 4.784.666l-.92 6.613c.69-1.975 1.394-3.857 1.98-5.162c.473-1.228 1.64-2.015 3.094-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.126 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.305 2.148l-.008-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.c4hzoxbwx {
  stop-color: var(--svg-color--cea68f, #CEA68F);
  stop-opacity: 0;
}

.cob7-sk7q {
  d: path("m21.95 16.434l-.007.003q.145-.556.309-1.128c.764-2.663 1.808-5.5 2.585-7.468q.096-.24.138-.487c.201-1.146-.419-2.33-1.568-2.706c-1.453-.422-2.62.365-3.093 1.594a44 44 0 0 0-.904 2.206c-.35.913-.714 1.921-1.076 2.955l.005-.033l-.01.042l-.6 2.03c-.183.63-.396 2.08 1.04 3s2.838.599 3.177 0z");
}

.e6krpwbyv {
  stroke-linecap: round;
  d: path("M28.15 15.414c-1.334.854-4.425 3.225-6.125 5.874");
}

.eq4-5yxww {
  stop-color: var(--svg-color--b3867a, #B3867A);
}

.evrq-rdbb {
  stroke: var(--svg-color--c8a089, #C8A089);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.321 6.32l.7 6.768");
}

.ft5dv1b6b {
  fill: none;
}

.i575q2bns {
  stop-color: var(--svg-color--91745f, #91745F);
  stop-opacity: 0;
}

.iq2o_qbpb {
  d: path("m4.795 17.4l-.02-.174a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.656 2.676l.87 3.32c.266 1.905-2.672 3.574-4.91 2.12");
}

.iykmbgn4a {
  stop-color: var(--svg-color--d1a890, #D1A890);
  stop-opacity: 0;
}

.jm0zesbdo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.35 4.338l-.922 8.953");
}

.jyjd2fb4v {
  stop-color: var(--svg-color--b3867a, #B3867A);
  stop-opacity: 0;
}

.k7t9l9bda {
  stop-color: var(--svg-color--cea58d, #CEA58D);
}

.l2k7r6clf {
  stop-color: var(--svg-color--917460, #917460);
  stop-opacity: 0;
}

.lesu3ebfc {
  stop-color: var(--svg-color--bb8c81, #BB8C81);
}

.lqq7iqafp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.837 16.476c.354-1.25 1.469-5.256 2.969-9.406");
}

.lvf4egbzb {
  d: path("M13.9 14.632c0 .766-.422 1.828-1.766 2.047c-1.428.233-2.306-1.061-2.504-1.582l-.804-3.164l-.404-5.104a2.415 2.415 0 1 1 4.814-.388z");
}

.m_7u7lbsj {
  stop-color: var(--svg-color--6e4437, #6E4437);
}

.m7nzayi_r {
  stop-color: var(--svg-color--9b7c68, #9B7C68);
  stop-opacity: 0;
}

.m8a0b8oay {
  stop-color: var(--svg-color--643d33, #643D33);
  stop-opacity: 0;
}

.mg2q5fmsa {
  stop-color: var(--svg-color--6e4437, #6E4437);
  stop-opacity: 0;
}

.mi1ga_b9w {
  stop-color: var(--svg-color--9b7c68, #9B7C68);
}

.mw4c-dn2n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.758 16.066c.546.644 1.63 1.135 2.547.794");
}

.n5s68wbua {
  stop-color: var(--svg-color--875a51, #875A51);
  stop-opacity: 0;
}

.napfbyb6j {
  d: path("M14.47 4.124a2.415 2.415 0 0 1 4.784.666l-.92 6.613c.69-1.975 1.394-3.857 1.98-5.162c.473-1.228 1.64-2.015 3.094-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.126 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.305 2.148l-.008-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.o490qhwdb {
  stop-color: var(--svg-color--7b5b4c, #7B5B4C);
  stop-opacity: 0;
}

.o71i0wywp {
  stroke: var(--svg-color--c9a18b, #C9A18B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.206 9.313l1.781 6.968");
}

.ocju3ln3y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.726 13.538c.547.644 1.63 1.135 2.548.794");
}

.ommaqbylo {
  stop-color: var(--svg-color--5c3d30, #5C3D30);
}

.pqr0p4b0j {
  stop-color: var(--svg-color--764f40, #764F40);
  stop-opacity: 0;
}

.q3oz1fkff {
  stop-color: var(--svg-color--7b5b4c, #7B5B4C);
}

.q4_a51zzm {
  stop-color: var(--svg-color--7c5d50, #7C5D50);
  stop-opacity: 0;
}

.qjhm2stkm {
  stop-color: var(--svg-color--cca38d, #CCA38D);
}

.qoerfg7mw {
  stop-color: var(--svg-color--7f5549, #7F5549);
  stop-opacity: 0;
}

.qysi05bhg {
  stop-color: var(--svg-color--926664, #926664);
}

.s5bj0abyc {
  stop-color: var(--svg-color--cca38d, #CCA38D);
  stop-opacity: 0;
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

.tuv3wmjtl {
  stop-color: var(--svg-color--926e59, #926E59);
}

.u-s9hqb1d {
  stop-color: var(--svg-color--917460, #917460);
}

.u65ms5b3b {
  stop-color: var(--svg-color--d1a890, #D1A890);
}

.v1dstq94l {
  stop-color: var(--svg-color--5c3d30, #5C3D30);
  stop-opacity: 0;
}

.vrp5279ag {
  stop-color: var(--svg-color--bb8c81, #BB8C81);
  stop-opacity: 0;
}

.w0efsqw6k {
  stop-color: var(--svg-color--875a51, #875A51);
}

.wf7f97g9x {
  d: path("M13.88 14.38c.31.287.72.536 1.254.69c1.613.462 2.492-1.04 2.688-1.985l.512-1.683l.92-6.612a2.415 2.415 0 0 0-4.783-.666l-.9 6.463z");
}

.wfbs8lbbx {
  stop-color: var(--svg-color--926e59, #926E59);
  stop-opacity: 0;
}

.xd1qixbwn {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
}

.xp3m0tmzy {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
  stop-opacity: 0;
}

.y4-6_vq6r {
  stop-color: var(--svg-color--764f40, #764F40);
}

.y591ksmyk {
  stop-color: var(--svg-color--7f5549, #7F5549);
}

.yl8izo-9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.831 14.759c.95-.185 1.699-.46 2.515-1.327");
}

.yq54gjb-q {
  stop-color: var(--svg-color--caa18c, #CAA18C);
  stop-opacity: 0;
}

.yr7usdr1u {
  stop-color: var(--svg-color--cea68f, #CEA68F);
}

.z9xoncbqq {
  stop-color: var(--svg-color--cea58d, #CEA58D);
  stop-opacity: 0;
}

.zf2v4j4cy {
  stop-color: var(--svg-color--caa18c, #CAA18C);
}

.zi73fml0u {
  stop-color: var(--svg-color--926664, #926664);
  stop-opacity: 0;
}

.zr0okx6cw {
  stop-color: var(--svg-color--91745f, #91745F);
}

</style>
