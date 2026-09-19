<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="si2ie7bds"/><g filter="url(#ihKlgqe)"><path fill="url(#iWLDP1b)" class="y05o10b-f"/></g><path fill="url(#inGcnmb)" class="og7p8ef6j"/><path fill="url(#ivn8azd)" class="brtjrcemb"/><path fill="url(#iEeMCRc)" class="brtjrcemb"/><path fill="url(#iw7jfXc)" class="brtjrcemb"/><path fill="url(#iXlZtkd)" class="brtjrcemb"/><path fill="url(#iUIwKEc)" class="brtjrcemb"/><path fill="url(#iqg4uwb)" class="brtjrcemb"/><path fill="url(#iUMXumc)" class="brtjrcemb"/><path fill="url(#iSlfCQd)" class="brtjrcemb"/><path fill="url(#ic7VgBe)" class="brtjrcemb"/><path fill="url(#iRQH3Wp)" class="brtjrcemb"/><path fill="url(#imJuSld)" class="brtjrcemb"/><path fill="url(#iF23t0d)" class="z8_r1dbvt"/><path fill="url(#iUiePme)" class="z8_r1dbvt"/><g filter="url(#i8ZbxQX)"><path fill="url(#iFYLjgc)" class="vg81_iboq"/><path fill="url(#iSWg0be)" class="vg81_iboq"/></g><g filter="url(#iiG4Acc)"><path fill="url(#iVTv6jZ)" class="f2_k7nbxo"/><path fill="url(#ibdHYtc)" class="f2_k7nbxo"/><path fill="url(#iLHiTBd)" class="f2_k7nbxo"/></g><g filter="url(#iApnX6d)"><path stroke="url(#iRow4Qb)" class="y95j8-byn"/></g><g filter="url(#io2g4Zc)"><path fill="url(#isFLAsc)" class="rut7llftq"/><path fill="url(#ipsidEe)" class="rut7llftq"/><path fill="url(#iWpj04c)" class="rut7llftq"/><path fill="url(#i0cv5sq)" class="rut7llftq"/><path fill="url(#iH9XDkY)" class="rut7llftq"/><path fill="url(#izgxhUd)" class="rut7llftq"/><path fill="url(#i3Fv7eX)" class="rut7llftq"/><path fill="url(#i1kSkme)" class="rut7llftq"/><path fill="url(#iHPqnmd)" class="rut7llftq"/><path fill="url(#iywoHEb)" class="rut7llftq"/></g><path fill="url(#i0qQule)" class="b_mbj3b4z"/><path fill="url(#igUsvpH)" class="b_mbj3b4z"/><circle fill="url(#ipCqljM)" class="oi9vfw7gk"/><circle fill="url(#iKebrle)" class="oi9vfw7gk"/><circle fill="url(#izitaDd)" class="oi9vfw7gk"/><g filter="url(#ipcDAeb)"><path fill="url(#iBhidFd)" class="shbsq5bim"/></g><g filter="url(#ih8L95c)"><path fill="url(#iL6xPbc)" class="dpylg1bqq"/></g><g filter="url(#i7qPdhX)"><path fill="url(#i5aEHuc)" class="q6v5oeb9e"/></g><g filter="url(#ic6rOub)"><path stroke="url(#inlAjJd)" class="sgzkgjjcl"/></g><g filter="url(#i5hZZHc)"><path fill="url(#iHdvENb)" class="e4_fetbdy"/></g><g filter="url(#iHLEdhe)"><path stroke="url(#id6IWfc)" class="vnuwbqb6z"/></g><g filter="url(#iMgCUFb)"><path stroke="url(#iMycAob)" class="lg1x92b1x"/></g><g filter="url(#iTYYZTc)"><path class="hc4l7feqf"/></g><defs><radialGradient id="iWLDP1b" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 1.32812 -1.34623 2.34402 26.612 9.485)" gradientUnits="userSpaceOnUse"><stop class="y28nttbhx"/><stop offset="1" class="g_sgy9b-w"/></radialGradient><radialGradient id="ivn8azd" cx="0" cy="0" r="1" gradientTransform="rotate(145.981 7.886 6.189)scale(3.88535 7.30852)" gradientUnits="userSpaceOnUse"><stop class="i_7zxhbsi"/><stop offset="1" class="gzh6kscpy"/></radialGradient><radialGradient id="iEeMCRc" cx="0" cy="0" r="1" gradientTransform="rotate(66.125 3.5 9.84)scale(10.4232 11.078)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="mwhyxzyic"/><stop offset="1" class="b7v57abyz"/></radialGradient><radialGradient id="iXlZtkd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51143 1.89659 -1.12444 -.89608 13.64 4.308)" gradientUnits="userSpaceOnUse"><stop class="g2wc55b_k"/><stop offset="1" class="natse864u"/></radialGradient><radialGradient id="iUIwKEc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52564 2.11911 -.89939 -1.07193 16.028 7.1)" gradientUnits="userSpaceOnUse"><stop class="g2wc55b_k"/><stop offset="1" class="natse864u"/></radialGradient><radialGradient id="iqg4uwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34375 1.64062 -.26724 -.38178 17.956 7.892)" gradientUnits="userSpaceOnUse"><stop offset=".031" class="g2wc55b_k"/><stop offset=".893" class="natse864u"/></radialGradient><radialGradient id="iUMXumc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3281 2.53127 -.41232 -.37923 14.08 2.798)" gradientUnits="userSpaceOnUse"><stop class="g2wc55b_k"/><stop offset="1" class="natse864u"/></radialGradient><radialGradient id="iSlfCQd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.16972 .91894 -.40706 -.96112 14.794 4.895)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="ic7VgBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8234 .76563 -.34493 -.37095 13.448 4.728)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="iRQH3Wp" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35937 1.21875 -.54907 -1.06294 16.44 7.876)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="imJuSld" cx="0" cy="0" r="1" gradientTransform="rotate(134.683 6.157 6.901)scale(1.99982 .95664)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="iF23t0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.89151 -1.62856 .98904 1.14873 3.905 4.63)" gradientUnits="userSpaceOnUse"><stop class="v0lxwrw8c"/><stop offset="1" class="qvruwibmg"/></radialGradient><radialGradient id="iUiePme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8601 -.8015 .96609 -2.24205 5.685 5.009)" gradientUnits="userSpaceOnUse"><stop offset=".84" class="ul8ntc5jf"/><stop offset="1" class="gyskztbxs"/></radialGradient><radialGradient id="iSWg0be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.85156 2.14227 0 18 28.142)" gradientUnits="userSpaceOnUse"><stop class="esdhshb7o"/><stop offset="1" class="zk7_jm-pn"/></radialGradient><radialGradient id="ibdHYtc" cx="0" cy="0" r="1" gradientTransform="rotate(-135 7.47 10.452)scale(1.01647 2.0084)" gradientUnits="userSpaceOnUse"><stop class="ufjhytbyb"/><stop offset="1" class="zk7_jm-pn"/></radialGradient><radialGradient id="iLHiTBd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5703 -1.52344 1.11774 -1.15213 6.815 18.782)" gradientUnits="userSpaceOnUse"><stop class="lhxz0tb6k"/><stop offset="1" class="t7se8-bri"/></radialGradient><radialGradient id="ipsidEe" cx="0" cy="0" r="1" gradientTransform="rotate(-106.39 14.455 9.463)scale(6.64502 8.99011)" gradientUnits="userSpaceOnUse"><stop class="cqi1m2bxr"/><stop offset="1" class="wb8annbpt"/></radialGradient><radialGradient id="iWpj04c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.875 6.53125 0 16.3 21.251)" gradientUnits="userSpaceOnUse"><stop class="k_uo2lb7f"/><stop offset="1" class="wm54im16m"/></radialGradient><radialGradient id="i0cv5sq" cx="0" cy="0" r="1" gradientTransform="rotate(-62.418 29.36 -6.385)scale(2.36222 5.41084)" gradientUnits="userSpaceOnUse"><stop class="k_uo2lb7f"/><stop offset="1" class="wm54im16m"/></radialGradient><radialGradient id="iH9XDkY" cx="0" cy="0" r="1" gradientTransform="rotate(-16.631 49.987 -13.285)scale(5.0226 10.8354)" gradientUnits="userSpaceOnUse"><stop class="r7nt8bqar"/><stop offset="1" class="n0earqbbn"/></radialGradient><radialGradient id="izgxhUd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -1.51562 .69875 1.1958 4.987 8.767)" gradientUnits="userSpaceOnUse"><stop class="q92bisbnd"/><stop offset="1" class="j1hbibbxu"/></radialGradient><radialGradient id="i3Fv7eX" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .4297 -1.30184 2.03554 6.019 2.79)" gradientUnits="userSpaceOnUse"><stop class="zbcn3kg0t"/><stop offset="1" class="nz41ibb3u"/></radialGradient><radialGradient id="i1kSkme" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -1.42187 6.45399 2.62414 9.753 25.83)" gradientUnits="userSpaceOnUse"><stop class="i73baob2a"/><stop offset="1" class="ziz970b6i"/></radialGradient><radialGradient id="iHPqnmd" cx="0" cy="0" r="1" gradientTransform="rotate(121.088 -1.252 14.946)scale(.62034 2.32909)" gradientUnits="userSpaceOnUse"><stop class="i7kwnsbtw"/><stop offset="1" class="ozl41i9iy"/></radialGradient><radialGradient id="iywoHEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.67188 .2791 .44138 8.284 19.407)" gradientUnits="userSpaceOnUse"><stop class="w0qioubuo"/><stop offset="1" class="b89-4bbfl"/></radialGradient><radialGradient id="igUsvpH" cx="0" cy="0" r="1" gradientTransform="matrix(1.4422 -.80985 .22471 .40017 2.424 8.524)" gradientUnits="userSpaceOnUse"><stop class="lagn3cb8q"/><stop offset="1" class="r8bvzmz9u"/></radialGradient><radialGradient id="ipCqljM" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.162 5.851)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iKebrle" cx="0" cy="0" r="1" gradientTransform="rotate(137.926 1.968 4.136)scale(.3074 .27043)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><linearGradient id="inGcnmb" x1="1.761" x2="6.085" y1="9.535" y2="6.044" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ixz6v2bhs"/><stop offset="1" class="e2a7rcbkj"/></linearGradient><linearGradient id="iw7jfXc" x1="14.403" x2="11.524" y1="7.53" y2="9.241" gradientUnits="userSpaceOnUse"><stop offset=".516" class="mwhyxzyic"/><stop offset="1" class="b7v57abyz"/></linearGradient><linearGradient id="iFYLjgc" x1="20.925" x2="15.689" y1="19.439" y2="21.539" gradientUnits="userSpaceOnUse"><stop class="kedgnpb4s"/><stop offset="1" class="j3lv25bwc"/></linearGradient><linearGradient id="iVTv6jZ" x1="8.009" x2="3.012" y1="16.97" y2="22.001" gradientUnits="userSpaceOnUse"><stop class="j5i0bcbpv"/><stop offset="1" class="j3lv25bwc"/></linearGradient><linearGradient id="iRow4Qb" x1="4.763" x2="8.326" y1="19.765" y2="17.437" gradientUnits="userSpaceOnUse"><stop class="bd746ob-n"/><stop offset="1" class="aj7oio2ey"/></linearGradient><linearGradient id="isFLAsc" x1="8.576" x2="21.264" y1="1.982" y2="26.371" gradientUnits="userSpaceOnUse"><stop class="cx4s4tnso"/><stop offset="1" class="xmaeumynr"/></linearGradient><linearGradient id="i0qQule" x1="2.909" x2="3.501" y1="8.048" y2="9.58" gradientUnits="userSpaceOnUse"><stop offset=".006" class="sa3b_fvpu"/><stop offset="1" class="z8p8hpqah"/></linearGradient><linearGradient id="izitaDd" x1="5.915" x2="5.571" y1="5.62" y2="5.401" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iBhidFd" x1="18.168" x2="21.567" y1="27.032" y2="21.675" gradientUnits="userSpaceOnUse"><stop class="a8w_-db0v"/><stop offset="1" class="c0836bb1j"/></linearGradient><linearGradient id="iL6xPbc" x1="7.919" x2="14.25" y1="3.631" y2="13.97" gradientUnits="userSpaceOnUse"><stop class="l6asi_bad"/><stop offset="1" class="caccqtb0a"/></linearGradient><linearGradient id="i5aEHuc" x1="28.956" x2="25.737" y1="12.749" y2="24.782" gradientUnits="userSpaceOnUse"><stop class="s2jmff1mi"/><stop offset="1" class="g-w90zbbh"/></linearGradient><linearGradient id="inlAjJd" x1="27.518" x2="21.3" y1="19.189" y2="33.063" gradientUnits="userSpaceOnUse"><stop class="g-w90zbbh"/><stop offset=".239" class="s2jmff1mi"/><stop offset="1" class="g-w90zbbh"/></linearGradient><linearGradient id="iHdvENb" x1="7.393" x2="8.909" y1="2.751" y2="5.626" gradientUnits="userSpaceOnUse"><stop class="t5ng6m5ia"/><stop offset="1" class="neuu31bdt"/></linearGradient><linearGradient id="id6IWfc" x1="9.393" x2="10.175" y1="24.22" y2="17.782" gradientUnits="userSpaceOnUse"><stop class="wi-b97b3f"/><stop offset="1" class="vsm9a27iv"/></linearGradient><linearGradient id="iMycAob" x1="7.034" x2="8.03" y1="21.845" y2="21.984" gradientUnits="userSpaceOnUse"><stop class="wi-b97b3f"/><stop offset="1" class="vsm9a27iv"/></linearGradient><filter id="ihKlgqe" width="6.656" height="9.594" x="23.831" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".5"/></filter><filter id="i8ZbxQX" width="6.296" height="12.775" x="16.997" y="15.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.415686 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2478"/></filter><filter id="iiG4Acc" width="10.145" height="7.53" x="3.012" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.415686 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2478"/></filter><filter id="iApnX6d" width="4.888" height="6.419" x="3.569" y="16.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".2"/></filter><filter id="io2g4Zc" width="25.963" height="28.25" x="2.018" y="2.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.262745 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2478"/></filter><filter id="ipcDAeb" width="5.609" height="7.813" x="17.003" y="20.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".5"/></filter><filter id="ih8L95c" width="8.632" height="13.516" x="5.909" y="1.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".5"/></filter><filter id="i7qPdhX" width="9.063" height="15.783" x="20.143" y="10.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation="1"/></filter><filter id="ic6rOub" width="5.635" height="14.06" x="22.509" y="16.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".5"/></filter><filter id="i5hZZHc" width="2.594" height="3.469" x="6.565" y="2.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".125"/></filter><filter id="iHLEdhe" width="4.564" height="6.385" x="7.454" y="19.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".25"/></filter><filter id="iMgCUFb" width="1.13" height="3.282" x="6.977" y="20.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".125"/></filter><filter id="iTYYZTc" width="5.031" height="13.344" x="5.909" y="6.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2478" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:horse" /></template>
<style>
.a8w_-db0v {
  stop-color: var(--svg-color--82585e, #82585E);
}

.aj7oio2ey {
  stop-color: var(--svg-color--876363, #876363);
  stop-opacity: 0;
}

.b_mbj3b4z {
  d: path("m4.215 9.115l-1.259-2.13l-.654.71a1.07 1.07 0 0 0-.262.939c.14.687.82 1.028 1.47.765z");
}

.b7v57abyz {
  stop-color: var(--svg-color--1e1818, #1E1818);
}

.b89-4bbfl {
  stop-color: var(--svg-color--97716c, #97716C);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bd746ob-n {
  stop-color: var(--svg-color--876363, #876363);
}

.bf8pxkoqd {
  stop-color: var(--svg-color--343435, #343435);
}

.brtjrcemb {
  d: path("M7.615 5.142c0 .083.067.15.15.15h1.09a.15.15 0 0 1 .15.15v2.922c0 .083.067.15.15.15h1.699a.15.15 0 0 1 .15.15v3.615c0 .083.067.15.15.15h2.475a4.01 4.01 0 0 0 4.006-4.012a.41.41 0 0 0-.412-.413h-2.085c-.149 0-.216-.206-.107-.307a3.07 3.07 0 0 0 .986-2.258a.436.436 0 0 0-.436-.436h-2.152c-.15 0-.224-.22-.124-.333a1.86 1.86 0 0 0 .473-1.242a.427.427 0 0 0-.426-.427H7.765a.15.15 0 0 0-.15.15z");
}

.c0836bb1j {
  stop-color: var(--svg-color--82585e, #82585E);
  stop-opacity: 0;
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.caccqtb0a {
  stop-color: var(--svg-color--ab8073, #AB8073);
  stop-opacity: 0;
}

.cqi1m2bxr {
  stop-color: var(--svg-color--6a433b, #6A433B);
}

.cx4s4tnso {
  stop-color: var(--svg-color--936554, #936554);
}

.dpylg1bqq {
  d: path("M11.393 13.97L6.91 2.454l2.474 2.53a3 3 0 0 1 .532.742l3.626 7.162z");
}

.e2a7rcbkj {
  stop-color: var(--svg-color--ffdea7, #FFDEA7);
}

.e4_fetbdy {
  d: path("M8.003 5.423L6.815 2.454L8.91 4.235z");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.esdhshb7o {
  stop-color: var(--svg-color--794562, #794562);
}

.f2_k7nbxo {
  d: path("M4.771 23.418a.38.38 0 0 1-.538 0l-.392-.392a2.82 2.82 0 0 1-.83-2.005v-2.358A2.66 2.66 0 0 1 5.672 16h7.336v2H5.67a.66.66 0 0 0-.661.663v2.358c0 .221.088.434.244.59l.391.393a.38.38 0 0 1 0 .538z");
}

.ft5dv1b6b {
  fill: none;
}

.g_sgy9b-w {
  stop-color: var(--svg-color--535254, #535254);
}

.g-w90zbbh {
  stop-color: var(--svg-color--a47c71, #A47C71);
  stop-opacity: 0;
}

.g2wc55b_k {
  stop-color: var(--svg-color--5a5a5b, #5A5A5B);
}

.gyskztbxs {
  stop-color: var(--svg-color--4a494a, #4A494A);
}

.gzh6kscpy {
  stop-color: var(--svg-color--363335, #363335);
}

.hc4l7feqf {
  fill: var(--svg-color--966d67, #966D67);
  d: path("m8.003 15.985l-1.094-7.75l.844-.938c.146 1.156.725 4.575 1 6.875s.781 3.156 1.187 3.875l-.875.594c-.525-.725-.927-2.073-1.062-2.656");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i_7zxhbsi {
  stop-color: var(--svg-color--535253, #535253);
}

.i73baob2a {
  stop-color: var(--svg-color--633456, #633456);
}

.i7kwnsbtw {
  stop-color: var(--svg-color--6a463f, #6A463F);
}

.ixz6v2bhs {
  stop-color: var(--svg-color--dc872a, #DC872A);
}

.j1hbibbxu {
  stop-color: var(--svg-color--6f3e55, #6F3E55);
  stop-opacity: 0;
}

.j3lv25bwc {
  stop-color: var(--svg-color--805655, #805655);
}

.j5i0bcbpv {
  stop-color: var(--svg-color--5a3933, #5A3933);
}

.k_uo2lb7f {
  stop-color: var(--svg-color--733b61, #733B61);
}

.kedgnpb4s {
  stop-color: var(--svg-color--522a34, #522A34);
}

.l6asi_bad {
  stop-color: var(--svg-color--ab8073, #AB8073);
}

.lagn3cb8q {
  stop-color: var(--svg-color--d7aa87, #D7AA87);
}

.lg1x92b1x {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.753 20.673c-.302.464-.725 1.64 0 2.64");
}

.lhxz0tb6k {
  stop-color: var(--svg-color--5f3553, #5F3553);
}

.mwhyxzyic {
  stop-color: var(--svg-color--1e1818, #1E1818);
  stop-opacity: 0;
}

.n0earqbbn {
  stop-color: var(--svg-color--855f53, #855F53);
  stop-opacity: 0;
}

.natse864u {
  stop-color: var(--svg-color--5a5a5b, #5A5A5B);
  stop-opacity: 0;
}

.neuu31bdt {
  stop-color: var(--svg-color--9f7667, #9F7667);
  stop-opacity: 0;
}

.nz41ibb3u {
  stop-color: var(--svg-color--926c60, #926C60);
  stop-opacity: 0;
}

.og7p8ef6j {
  d: path("M3.017 6.92c-.337.362-.74.778-.74.778a1.08 1.08 0 0 0-.23.946c.154.675.838 1.008 1.48.75l.768-.311z");
}

.oi9vfw7gk {
  cx: 6.013px;
  cy: 6.013px;
  r: 0.5px;
}

.ozl41i9iy {
  stop-color: var(--svg-color--6a463f, #6A463F);
  stop-opacity: 0;
}

.q6v5oeb9e {
  d: path("M27.206 16.876c0-3.156-2.234-4.516-5.063-4.031v.781l1.05.651a3 3 0 0 1 1.42 2.55v4.987l2.593 2.718z");
}

.q92bisbnd {
  stop-color: var(--svg-color--6f3e55, #6F3E55);
}

.qvruwibmg {
  stop-color: var(--svg-color--1f1818, #1F1818);
}

.r7nt8bqar {
  stop-color: var(--svg-color--855f53, #855F53);
}

.r8bvzmz9u {
  stop-color: var(--svg-color--d7aa87, #D7AA87);
  stop-opacity: 0;
}

.rut7llftq {
  d: path("M23.069 12.001h-7.04a3.44 3.44 0 0 1-3.012-1.775L9.979 4.75c-.273-.492-.645-.828-1.112-1.195l-2.016-1.51a.27.27 0 0 0-.414.227v.83a.28.28 0 0 1-.076.195L2.302 7.694a1.07 1.07 0 0 0-.262.94c.14.687.82 1.028 1.47.765l2.394-.966a.297.297 0 0 1 .405.235l1.11 8.044a4.95 4.95 0 0 0 1.031 2.414a.26.26 0 0 1-.018.348l-.642.643a2.65 2.65 0 0 0-.779 1.887a2.73 2.73 0 0 0 .811 1.911l1.246 1.256a2.8 2.8 0 0 0 2.002.83h.456a.48.48 0 0 0 .478-.479V24.48a.48.48 0 0 0-.478-.479h-.456a.84.84 0 0 1-.59-.244l-1.263-1.274a.66.66 0 0 1-.016-.952l.88-.88a.26.26 0 0 1 .287-.056c.605.262 1.27.406 1.965.406h8.004c.425 0 .838.138 1.177.393l2.513 1.887a2.4 2.4 0 0 1 .48 3.36l-2.24 2.989a.232.232 0 0 0 .186.371h1.217c.2 0 .39-.091.515-.248l3.234-4.048a2.57 2.57 0 0 0 .563-1.604v-7.18c0-2.717-2.2-4.92-4.913-4.92");
}

.s2jmff1mi {
  stop-color: var(--svg-color--a47c71, #A47C71);
}

.sa3b_fvpu {
  stop-color: var(--svg-color--cfa576, #CFA576);
}

.sgzkgjjcl {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.706 29.189l2.555-3.281a3 3 0 0 0 .632-1.843v-6.783");
}

.shbsq5bim {
  d: path("M18.003 26.623v.816h.38v-.82a1 1 0 0 1 .312-.726l2.917-2.767l-1.937-1.5v1.472a2 2 0 0 1-.42 1.225l-.833 1.075a2 2 0 0 0-.42 1.225");
}

.si2ie7bds {
  fill: var(--svg-color--292727, #292727);
  d: path("M28.02 6.649V5.486c0-.268.218-.485.486-.485c.835 0 1.512.678 1.512 1.514v1.989c0 1.38-1.118 2.5-2.496 2.5h-1.154a.356.356 0 0 0-.356.356v4.641h-1.997V9.505c0-1.38 1.117-2.5 2.496-2.5h1.154c.197 0 .356-.16.356-.356");
}

.t5ng6m5ia {
  stop-color: var(--svg-color--9f7667, #9F7667);
}

.t7se8-bri {
  stop-color: var(--svg-color--5f3553, #5F3553);
  stop-opacity: 0;
}

.ufjhytbyb {
  stop-color: var(--svg-color--784d65, #784D65);
}

.ul8ntc5jf {
  stop-color: var(--svg-color--4a494a, #4A494A);
  stop-opacity: 0;
}

.v-z8ul8_r {
  stop-color: var(--svg-color--343435, #343435);
  stop-opacity: 0;
}

.v0lxwrw8c {
  stop-color: var(--svg-color--2b292d, #2B292D);
}

.vg81_iboq {
  d: path("M18.994 15.388v7.788a.96.96 0 0 1-.28.676l-.883.878a2.84 2.84 0 0 0-.834 2.017v.938c0 .174.141.316.316.316h1.366a.316.316 0 0 0 .316-.316v-.937c0-.227.09-.444.25-.604l3.874-3.88l.024-.009v-7.029z");
}

.vnuwbqb6z {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m9.58 19.89l-.995 1.115a1.5 1.5 0 0 0 .073 2.075l1.538 1.495a1 1 0 0 0 .697.284h.625");
}

.vsm9a27iv {
  stop-color: var(--svg-color--8b6c67, #8B6C67);
  stop-opacity: 0;
}

.w0qioubuo {
  stop-color: var(--svg-color--97716c, #97716C);
}

.wb8annbpt {
  stop-color: var(--svg-color--6a433b, #6A433B);
  stop-opacity: 0;
}

.wi-b97b3f {
  stop-color: var(--svg-color--8b6c67, #8B6C67);
}

.wm54im16m {
  stop-color: var(--svg-color--643655, #643655);
  stop-opacity: 0;
}

.xmaeumynr {
  stop-color: var(--svg-color--764a4c, #764A4C);
}

.y05o10b-f {
  d: path("M28.737 5.689v1.875h-1.906a2 2 0 0 0-2 2v3.718h.61v-2.937h2.046a2 2 0 0 0 2-2V6.814c0-.492-.296-.936-.75-1.125");
}

.y28nttbhx {
  stop-color: var(--svg-color--535254, #535254);
  stop-opacity: 0;
}

.y95j8-byn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m4.92 22.374l-.195-.202a2 2 0 0 1-.556-1.384v-2.383c0-.69.56-1.25 1.25-1.25h2.438");
}

.z8_r1dbvt {
  d: path("M5.717 3.001c-1.011 0-1.848.75-1.985 1.725a.246.246 0 0 0 .241.283H5.48A2.006 2.006 0 0 0 7.485 3z");
}

.z8p8hpqah {
  stop-color: var(--svg-color--bb8185, #BB8185);
}

.zbcn3kg0t {
  stop-color: var(--svg-color--926c60, #926C60);
}

.ziz970b6i {
  stop-color: var(--svg-color--633456, #633456);
  stop-opacity: 0;
}

.zk7_jm-pn {
  stop-color: var(--svg-color--784d65, #784D65);
  stop-opacity: 0;
}

</style>
