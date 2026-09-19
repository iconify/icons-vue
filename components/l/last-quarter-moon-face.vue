<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iaXgvte)"><path fill="url(#i8YtWOB)" class="hptittbta"/><path fill="url(#ix5MC5d)" class="hptittbta"/><path fill="url(#izJFxsl)" class="hptittbta"/><path fill="url(#i4LSJne)" class="hptittbta"/></g><path fill="url(#ir5mVjd)" class="hptittbta"/><path fill="url(#iP43SZd)" class="hptittbta"/><path fill="url(#i16iMyc)" class="hptittbta"/><path fill="url(#iMqe56d)" class="hptittbta"/><path fill="url(#iNWNWId)" class="hptittbta"/><path fill="url(#ixEDKHy)" class="hptittbta"/><path fill="url(#ilrVsmb)" class="hptittbta"/><path fill="url(#iybevyb)" class="hptittbta"/><path fill="url(#iOL43te)" class="fpr8nhbuw"/><path fill="url(#igXU2Yb)" class="fpr8nhbuw"/><path fill="url(#iPnhemb)" class="fpr8nhbuw"/><path class="y4a0dubmw"/><path fill="url(#iZcxTcb)" class="u_1bt72ak"/><path fill="url(#i1ZBwVc)" class="u_1bt72ak"/><path fill="url(#ieFj63c)" class="u_1bt72ak"/><g filter="url(#iLHgiNc)"><path stroke="url(#ikpHTId)" class="u72ajacgl"/></g><path fill="url(#iRdpnCd)" class="v8fm0acmi"/><path fill="url(#ik27Ltc)" class="v8fm0acmi"/><path fill="url(#ihD5ruc)" class="v8fm0acmi"/><g filter="url(#ityIWrb)"><path stroke="url(#iqVSj6b)" class="vge0qccst"/></g><g filter="url(#iv3Y3nb)"><path fill="url(#iAwAmqd)" class="gk1pg8bxa"/><path fill="url(#ieJi31d)" class="gk1pg8bxa"/><path fill="url(#iO5HOmd)" class="gk1pg8bxa"/></g><g filter="url(#itcgwtd)"><path fill="url(#iz8teNJ)" clip-rule="evenodd" class="p1vm3_bpj"/></g><path fill="url(#icFurke)" clip-rule="evenodd" class="n4xo_jn9r"/><g filter="url(#iteFdnc)"><path clip-rule="evenodd" class="zs9hjuc_d"/></g><g clip-rule="evenodd" filter="url(#i8nqTge)" class="d2kvgvbvc"><path class="z70vh_bns"/><path fill="url(#iOLp2Zb)" class="qd6rjpc9k"/></g><g clip-rule="evenodd" filter="url(#iJgjWrN)" class="d2kvgvbvc"><path fill="url(#iqlB7ud)" class="z9_imdb2h"/><path fill="url(#inpfAAe)" class="z9_imdb2h"/></g><path fill="url(#imPQBKd)" clip-rule="evenodd" class="fxzhumbol"/><g filter="url(#i5sj0KV)"><path stroke="url(#iHCvCib)" class="fg2m1qb3a"/></g><g filter="url(#iO6Crad)"><path stroke="url(#iPrabYc)" class="y3moj6bac"/></g><g filter="url(#igrO0Wb)"><path stroke="url(#irIwCkb)" class="b7wqn3tdq"/></g><defs><radialGradient id="i8YtWOB" cx="0" cy="0" r="1" gradientTransform="matrix(-3.85745 25.7156 -18.17427 -2.72622 19.863 5.965)" gradientUnits="userSpaceOnUse"><stop class="s6sndlb-n"/><stop offset=".772" class="n-ofh96dr"/></radialGradient><radialGradient id="ix5MC5d" cx="0" cy="0" r="1" gradientTransform="matrix(-12.79834 -5.18672 2.5913 -6.3941 23.674 28.232)" gradientUnits="userSpaceOnUse"><stop class="rs3vfqbpa"/><stop offset="1" class="r5zx3nbgo"/></radialGradient><radialGradient id="izJFxsl" cx="0" cy="0" r="1" gradientTransform="matrix(4.82577 -8.40618 11.0521 6.34472 8.829 26.237)" gradientUnits="userSpaceOnUse"><stop class="q66k5kbtk"/><stop offset="1" class="eo1ucgxrq"/></radialGradient><radialGradient id="i4LSJne" cx="0" cy="0" r="1" gradientTransform="rotate(-29.672 52.798 .528)scale(9.4691 15.9492)" gradientUnits="userSpaceOnUse"><stop class="thmzu5zgp"/><stop offset="1" class="wbubtgaki"/></radialGradient><radialGradient id="ir5mVjd" cx="0" cy="0" r="1" gradientTransform="matrix(11.46027 -4.08098 4.18188 11.74364 16.843 15.636)" gradientUnits="userSpaceOnUse"><stop class="l8by2qbsa"/><stop offset="1" class="s6l8v15dh"/></radialGradient><radialGradient id="iP43SZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.875 .95647 2.52783 8.835 16.197)" gradientUnits="userSpaceOnUse"><stop class="uajfipbim"/><stop offset="1" class="fuf0k75ce"/></radialGradient><radialGradient id="i16iMyc" cx="0" cy="0" r="1" gradientTransform="rotate(152.12 9.628 5.687)scale(13.5805 11.0884)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="izmldvjof"/><stop offset="1" class="b6cszd0sh"/></radialGradient><radialGradient id="iMqe56d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74554 4.08096 -9.32227 -8.55607 20.198 23.463)" gradientUnits="userSpaceOnUse"><stop class="dzcrlacjl"/><stop offset="1" class="cbyyemb_l"/></radialGradient><radialGradient id="iNWNWId" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12434 -.61493 .39607 -1.36826 17.99 17.928)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="a8nan7som"/><stop offset="1" class="gcz1-f7ma"/></radialGradient><radialGradient id="ixEDKHy" cx="0" cy="0" r="1" gradientTransform="rotate(163.237 11.151 3.04)scale(2.1086 1.49024)" gradientUnits="userSpaceOnUse"><stop class="grrdnac0k"/><stop offset="1" class="pfpusbc_l"/></radialGradient><radialGradient id="ilrVsmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.42173 4.13675 -1.55297 -1.28454 20.306 6.889)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="dh9d-julu"/><stop offset="1" class="t2001_s5s"/></radialGradient><radialGradient id="iybevyb" cx="0" cy="0" r="1" gradientTransform="rotate(169.099 7.759 8.069)scale(1.51783 1.71916)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="x-dohcbta"/><stop offset="1" class="lx07axr4g"/></radialGradient><radialGradient id="iOL43te" cx="0" cy="0" r="1" gradientTransform="matrix(.4472 3.55698 -13.98381 1.75814 16.006 2.016)" gradientUnits="userSpaceOnUse"><stop class="nv21zabdl"/><stop offset="1" class="u6wod_bgd"/></radialGradient><radialGradient id="igXU2Yb" cx="0" cy="0" r="1" gradientTransform="scale(5.03222 3.25171)rotate(90 1.38 2)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="v-5gyy-8r"/><stop offset="1" class="hjh07hbwz"/></radialGradient><radialGradient id="iPnhemb" cx="0" cy="0" r="1" gradientTransform="matrix(2.43111 2.09545 -3.46447 4.01944 17.012 2.016)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="l_k6zlbgk"/><stop offset="1" class="pwtg2wozy"/></radialGradient><radialGradient id="iZcxTcb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.37341 .46972 -1.14567 -8.2279 8.713 17.527)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="n96lwebvj"/><stop offset="1" class="a8w8-cchi"/></radialGradient><radialGradient id="i1ZBwVc" cx="0" cy="0" r="1" gradientTransform="matrix(3.82178 -.36296 .36402 3.8329 5.34 17.484)" gradientUnits="userSpaceOnUse"><stop offset=".892" class="laz6hcc5o"/><stop offset="1" class="ld0hbtirc"/></radialGradient><radialGradient id="ieFj63c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17777 .36295 -.427 -2.5621 9.503 16.353)" gradientUnits="userSpaceOnUse"><stop class="m4a1l3avc"/><stop offset="1" class="p1hcpxb1o"/></radialGradient><radialGradient id="ik27Ltc" cx="0" cy="0" r="1" gradientTransform="rotate(-165.353 12.04 12.787)scale(7.76791 6.69188)" gradientUnits="userSpaceOnUse"><stop offset=".758" class="m3w8qz5zs"/><stop offset=".958" class="r-0qskb3f"/></radialGradient><radialGradient id="ihD5ruc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76896 2.47669 -2.15734 5.89618 12.215 25.726)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l4xkk2k1l"/><stop offset="1" class="erui7oc9j"/></radialGradient><radialGradient id="iAwAmqd" cx="0" cy="0" r="1" gradientTransform="rotate(-11.31 39.604 -49.806)scale(3.66492)" gradientUnits="userSpaceOnUse"><stop class="l9epxg-rl"/><stop offset=".777" class="hneu2tzbv"/></radialGradient><radialGradient id="ieJi31d" cx="0" cy="0" r="1" gradientTransform="rotate(-29.275 19.251 -18.756)scale(2.36449)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="wr-fjk83a"/><stop offset="1" class="k6dxhzpoo"/></radialGradient><radialGradient id="iO5HOmd" cx="0" cy="0" r="1" gradientTransform="matrix(2.80694 -1.28127 1.57065 3.4409 10.824 7.08)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="wr-fjk83a"/><stop offset="1" class="k6dxhzpoo"/></radialGradient><radialGradient id="icFurke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32764 -1.95015 1.30654 -1.55944 14.57 21.085)" gradientUnits="userSpaceOnUse"><stop class="ctsw_g6wf"/><stop offset="1" class="ntrjtj3gf"/></radialGradient><radialGradient id="inpfAAe" cx="0" cy="0" r="1" gradientTransform="rotate(139.23 3.64 8.195)scale(3.44548 6.40211)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="njvtv6tpp"/><stop offset="1" class="jcypb8b9t"/></radialGradient><radialGradient id="imPQBKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 6.11501 0 11.574 13.369)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="yu4vrishy"/><stop offset="1" class="i3lji-b1e"/></radialGradient><filter id="iaXgvte" width="20.279" height="28.486" x="5" y="1.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.482353 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14604"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.411765 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14604" result="effect2_innerShadow_18_14604"/></filter><filter id="iLHgiNc" width="5.68" height="5.68" x="13.604" y="23.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".1"/></filter><filter id="ityIWrb" width="4.04" height="4.04" x="10.374" y="4.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".15"/></filter><filter id="iv3Y3nb" width="11.14" height="11.14" x="6.824" y="5.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14604"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14604" result="shape"/></filter><filter id="itcgwtd" width="4.236" height="4.046" x="11.291" y="17.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".25"/></filter><filter id="iteFdnc" width="4.309" height="4.54" x="6.673" y="7.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".15"/></filter><filter id="i8nqTge" width="4.13" height="4.13" x="7.154" y="7.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14604"/></filter><filter id="iJgjWrN" width="6.5" height="3.96" x="7.883" y="10.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".25"/></filter><filter id="i5sj0KV" width="3.994" height="3.963" x="7.057" y="7.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".125"/></filter><filter id="iO6Crad" width="5.325" height="2.937" x="8.86" y="11.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".2"/></filter><filter id="igrO0Wb" width="3.138" height="3.147" x="12.116" y="17.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14604" stdDeviation=".2"/></filter><linearGradient id="ikpHTId" x1="14.392" x2="18.748" y1="30.038" y2="24.744" gradientUnits="userSpaceOnUse"><stop class="fsyum4xkk"/><stop offset="1" class="dcexg2b7d"/></linearGradient><linearGradient id="iRdpnCd" x1="14.472" x2="18.983" y1="25.07" y2="28.447" gradientUnits="userSpaceOnUse"><stop offset=".272" class="x155l7bwh"/><stop offset="1" class="k8b5l02az"/></linearGradient><linearGradient id="iqVSj6b" x1="11.037" x2="14.162" y1="7.425" y2="5.925" gradientUnits="userSpaceOnUse"><stop class="ojyd0bcbr"/><stop offset="1" class="hu0wpdcnx"/></linearGradient><linearGradient id="iz8teNJ" x1="12.456" x2="15.021" y1="19.04" y2="21.365" gradientUnits="userSpaceOnUse"><stop class="zpw-s4bhu"/><stop offset="1" class="l6tjwibos"/></linearGradient><linearGradient id="iOLp2Zb" x1="11.585" x2="7.695" y1="8.055" y2="9.572" gradientUnits="userSpaceOnUse"><stop class="v_jh0qb6r"/><stop offset="1" class="yyjkh3b6t"/></linearGradient><linearGradient id="iqlB7ud" x1="11.457" x2="8.082" y1="12.55" y2="13.894" gradientUnits="userSpaceOnUse"><stop class="yqmvb6b_f"/><stop offset="1" class="vozyuwbkf"/></linearGradient><linearGradient id="iHCvCib" x1="10.882" x2="7.351" y1="8.439" y2="11.674" gradientUnits="userSpaceOnUse"><stop offset=".204" class="iotdm4jnc"/><stop offset=".52" class="h_q3w4und"/><stop offset=".801" class="i90gflbvo"/></linearGradient><linearGradient id="iPrabYc" x1="9.772" x2="11.864" y1="13.149" y2="10.879" gradientUnits="userSpaceOnUse"><stop class="y5_8fg_du"/><stop offset="1" class="kso5qihdf"/></linearGradient><linearGradient id="irIwCkb" x1="14.113" x2="12.069" y1="20.65" y2="20.031" gradientUnits="userSpaceOnUse"><stop class="b7_-o8ate"/><stop offset="1" class="q5cs4fbld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:last-quarter-moon-face" /></template>
<style>
.a8nan7som {
  stop-color: var(--svg-color--ffc145, #FFC145);
}

.a8w8-cchi {
  stop-color: var(--svg-color--a97a4e, #A97A4E);
}

.b6cszd0sh {
  stop-color: var(--svg-color--ffdf7e, #FFDF7E);
  stop-opacity: 0;
}

.b7_-o8ate {
  stop-color: var(--svg-color--554c58, #554C58);
  stop-opacity: 0;
}

.b7wqn3tdq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.716 18.475c.187 1.185 1.1 1.947 1.939 1.947");
}

.cbyyemb_l {
  stop-color: var(--svg-color--ffe790, #FFE790);
  stop-opacity: 0;
}

.ctsw_g6wf {
  stop-color: var(--svg-color--301e3a, #301E3A);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dcexg2b7d {
  stop-color: var(--svg-color--ffcf5d, #FFCF5D);
}

.dh9d-julu {
  stop-color: var(--svg-color--f3b95b, #F3B95B);
}

.dzcrlacjl {
  stop-color: var(--svg-color--ffe790, #FFE790);
}

.eo1ucgxrq {
  stop-color: var(--svg-color--ffa454, #FFA454);
  stop-opacity: 0;
}

.erui7oc9j {
  stop-color: var(--svg-color--eea752, #EEA752);
}

.fg2m1qb3a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.6 8.4c-.494-.02-1.663.383-2.179.946c-.695.632-.914 1.664-.914 2.117");
}

.fpr8nhbuw {
  d: path("M13.683 3.046a3.5 3.5 0 0 0 6.658-.961a14 14 0 0 0-6.658.96");
}

.fsyum4xkk {
  stop-color: var(--svg-color--f49d4c, #F49D4C);
}

.ft5dv1b6b {
  fill: none;
}

.fuf0k75ce {
  stop-color: var(--svg-color--ff9d5a, #FF9D5A);
  stop-opacity: 0;
}

.fxzhumbol {
  fill-rule: evenodd;
  d: path("M14.286 13a2.88 2.88 0 0 0-2.732-1.975a2.87 2.87 0 0 0-2.679 1.816a.75.75 0 0 0 1.397.548a1.37 1.37 0 0 1 1.282-.864c.607 0 1.126.394 1.307.945a.75.75 0 0 0 1.425-.47");
}

.gcz1-f7ma {
  stop-color: var(--svg-color--ffc145, #FFC145);
  stop-opacity: 0;
}

.gk1pg8bxa {
  d: path("M12.394 8.165a1.57 1.57 0 1 1 0-3.14a1.57 1.57 0 0 1 0 3.14");
}

.grrdnac0k {
  stop-color: var(--svg-color--fff8ad, #FFF8AD);
}

.h_q3w4und {
  stop-color: var(--svg-color--644f76, #644F76);
  stop-opacity: 0;
}

.hjh07hbwz {
  stop-color: var(--svg-color--ffde82, #FFDE82);
}

.hneu2tzbv {
  stop-color: var(--svg-color--f8bc5b, #F8BC5B);
}

.hptittbta {
  d: path("M16.708 18.234a.49.49 0 0 0-.13.474a13.7 13.7 0 0 0 3.516 6.127c1.27 1.28 2.74 2.26 4.31 2.94c.5.22.5.92 0 1.13c-5.35 2.25-11.8 1.04-15.93-3.63c-4.5-5.09-4.65-12.91-.32-18.15c3.51-4.25 8.85-5.84 13.73-4.8c.52.11.64.81.2 1.11c-1.29.88-2.46 1.99-3.44 3.38a14.1 14.1 0 0 0-2.476 6.603a9 9 0 0 0-.024.587c-.008.781.582 1.283 1.062 1.69c.128.109.248.211.348.31c.38.39.38 1.02-.01 1.4z");
}

.hu0wpdcnx {
  stop-color: var(--svg-color--ffca66, #FFCA66);
}

.i3lji-b1e {
  stop-color: var(--svg-color--3b302e, #3B302E);
}

.i90gflbvo {
  stop-color: var(--svg-color--644f76, #644F76);
}

.iotdm4jnc {
  stop-color: var(--svg-color--644f76, #644F76);
  stop-opacity: 0.5;
}

.izmldvjof {
  stop-color: var(--svg-color--ffdf7e, #FFDF7E);
}

.jcypb8b9t {
  stop-color: var(--svg-color--cd7f3f, #CD7F3F);
}

.k6dxhzpoo {
  stop-color: var(--svg-color--dda64b, #DDA64B);
}

.k8b5l02az {
  stop-color: var(--svg-color--ffbb67, #FFBB67);
}

.kso5qihdf {
  stop-color: var(--svg-color--5d5168, #5D5168);
}

.l_k6zlbgk {
  stop-color: var(--svg-color--ffca6e, #FFCA6E);
  stop-opacity: 0;
}

.l4xkk2k1l {
  stop-color: var(--svg-color--eea752, #EEA752);
  stop-opacity: 0;
}

.l6tjwibos {
  stop-color: var(--svg-color--ac6437, #AC6437);
}

.l8by2qbsa {
  stop-color: var(--svg-color--ffe997, #FFE997);
}

.l9epxg-rl {
  stop-color: var(--svg-color--ffec9d, #FFEC9D);
}

.laz6hcc5o {
  stop-color: var(--svg-color--d48851, #D48851);
  stop-opacity: 0;
}

.ld0hbtirc {
  stop-color: var(--svg-color--d48851, #D48851);
}

.lx07axr4g {
  stop-color: var(--svg-color--fff1a1, #FFF1A1);
  stop-opacity: 0;
}

.m3w8qz5zs {
  stop-color: var(--svg-color--ffe596, #FFE596);
  stop-opacity: 0;
}

.m4a1l3avc {
  stop-color: var(--svg-color--d87a58, #D87A58);
}

.n-ofh96dr {
  stop-color: var(--svg-color--ee8c4d, #EE8C4D);
}

.n4xo_jn9r {
  fill-rule: evenodd;
  d: path("M12.831 18.062a.75.75 0 0 0-.64.846a2.526 2.526 0 0 0 2.493 2.177a.75.75 0 1 0 0-1.5c-.502 0-.938-.38-1.007-.882a.75.75 0 0 0-.846-.64");
}

.n96lwebvj {
  stop-color: var(--svg-color--a97a4e, #A97A4E);
  stop-opacity: 0;
}

.njvtv6tpp {
  stop-color: var(--svg-color--cd7f3f, #CD7F3F);
  stop-opacity: 0;
}

.ntrjtj3gf {
  stop-color: var(--svg-color--332e2c, #332E2C);
}

.nv21zabdl {
  stop-color: var(--svg-color--ffca71, #FFCA71);
}

.ojyd0bcbr {
  stop-color: var(--svg-color--ffe07c, #FFE07C);
}

.p1hcpxb1o {
  stop-color: var(--svg-color--d87a58, #D87A58);
  stop-opacity: 0;
}

.p1vm3_bpj {
  fill-rule: evenodd;
  d: path("M12.445 18.319a.75.75 0 0 0-.648.84a2.526 2.526 0 0 0 2.474 2.199a.75.75 0 0 0 .013-1.5a1.026 1.026 0 0 1-.999-.891a.75.75 0 0 0-.84-.648");
}

.pfpusbc_l {
  stop-color: var(--svg-color--fff8ad, #FFF8AD);
  stop-opacity: 0;
}

.pwtg2wozy {
  stop-color: var(--svg-color--ffca6e, #FFCA6E);
}

.q5cs4fbld {
  stop-color: var(--svg-color--554c58, #554C58);
}

.q66k5kbtk {
  stop-color: var(--svg-color--ffa454, #FFA454);
}

.qd6rjpc9k {
  d: path("M11.134 8.555a.5.5 0 0 0-.5-.5a3.48 3.48 0 0 0-3.48 3.48a.5.5 0 0 0 1 0a2.48 2.48 0 0 1 2.48-2.48a.5.5 0 0 0 .5-.5");
}

.r-0qskb3f {
  stop-color: var(--svg-color--ffe596, #FFE596);
}

.r5zx3nbgo {
  stop-color: var(--svg-color--ffc050, #FFC050);
  stop-opacity: 0;
}

.rs3vfqbpa {
  stop-color: var(--svg-color--ffc050, #FFC050);
}

.s6l8v15dh {
  stop-color: var(--svg-color--ffe997, #FFE997);
  stop-opacity: 0;
}

.s6sndlb-n {
  stop-color: var(--svg-color--fcbd56, #FCBD56);
}

.t2001_s5s {
  stop-color: var(--svg-color--f3b95b, #F3B95B);
  stop-opacity: 0;
}

.thmzu5zgp {
  stop-color: var(--svg-color--ec8a4b, #EC8A4B);
}

.u_1bt72ak {
  d: path("M5.165 13.832a14.3 14.3 0 0 0 .667 6.969a3.5 3.5 0 1 0-.667-6.969");
}

.u6wod_bgd {
  stop-color: var(--svg-color--ffdb80, #FFDB80);
}

.u72ajacgl {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.444 29.095a2.54 2.54 0 1 1 0-5.08a2.54 2.54 0 0 1 0 5.08Z");
}

.uajfipbim {
  stop-color: var(--svg-color--ff9d5a, #FF9D5A);
}

.v_jh0qb6r {
  stop-color: var(--svg-color--3b2d31, #3B2D31);
}

.v-5gyy-8r {
  stop-color: var(--svg-color--ffde82, #FFDE82);
  stop-opacity: 0;
}

.v8fm0acmi {
  d: path("M16.444 29.095a2.54 2.54 0 1 1 0-5.08a2.54 2.54 0 0 1 0 5.08");
}

.vge0qccst {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M12.394 8.165a1.57 1.57 0 1 1 0-3.14a1.57 1.57 0 0 1 0 3.14Z");
}

.vozyuwbkf {
  stop-color: var(--svg-color--a36231, #A36231);
  stop-opacity: 0;
}

.wbubtgaki {
  stop-color: var(--svg-color--ec8a4b, #EC8A4B);
  stop-opacity: 0;
}

.wr-fjk83a {
  stop-color: var(--svg-color--dda64b, #DDA64B);
  stop-opacity: 0;
}

.x-dohcbta {
  stop-color: var(--svg-color--fff1a1, #FFF1A1);
}

.x155l7bwh {
  stop-color: var(--svg-color--ffbe6c, #FFBE6C);
}

.y3moj6bac {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.585 13.385c-.036-.526-.675-1.557-1.937-1.72c-1.263-.162-2.032.798-2.188 1.376");
}

.y4a0dubmw {
  fill: var(--svg-color--e39c53, #E39C53);
  d: path("M5.165 13.832a14.3 14.3 0 0 0 .667 6.969a3.5 3.5 0 1 0-.667-6.969");
}

.y5_8fg_du {
  stop-color: var(--svg-color--3f3445, #3F3445);
}

.yqmvb6b_f {
  stop-color: var(--svg-color--a36231, #A36231);
}

.yu4vrishy {
  stop-color: var(--svg-color--3d2a48, #3D2A48);
}

.yyjkh3b6t {
  stop-color: var(--svg-color--3b2d31, #3B2D31);
  stop-opacity: 0;
}

.z70vh_bns {
  fill: var(--svg-color--3f294d, #3F294D);
  d: path("M11.134 8.555a.5.5 0 0 0-.5-.5a3.48 3.48 0 0 0-3.48 3.48a.5.5 0 0 0 1 0a2.48 2.48 0 0 1 2.48-2.48a.5.5 0 0 0 .5-.5");
}

.z9_imdb2h {
  d: path("M13.846 13.204a2.88 2.88 0 0 0-2.732-1.976a2.87 2.87 0 0 0-2.679 1.816a.75.75 0 0 0 1.397.548a1.37 1.37 0 0 1 1.281-.864c.608 0 1.127.394 1.308.945a.75.75 0 1 0 1.425-.47");
}

.zpw-s4bhu {
  stop-color: var(--svg-color--a16132, #A16132);
}

.zs9hjuc_d {
  fill: var(--svg-color--a87c30, #A87C30);
  fill-rule: evenodd;
  d: path("M10.681 8.646a.475.475 0 0 0-.502-.446c-1.818.107-3.308 1.662-3.2 3.491a.475.475 0 1 0 .949-.056c-.077-1.302 1.011-2.41 2.307-2.486a.475.475 0 0 0 .446-.503");
}

</style>
