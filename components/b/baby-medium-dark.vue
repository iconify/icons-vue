<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iueZkzc)" class="aw0-ozbwv"/><path fill="url(#iw1AWQb)" class="aw0-ozbwv"/><g filter="url(#i0Gprtb)"><path fill="url(#ipnCEne)" class="wpfvvtbjo"/></g><path fill="url(#iWS1Ksd)" class="l5saph60d"/><path fill="url(#iEJBJqe)" class="l5saph60d"/><path fill="url(#io5Njub)" class="l5saph60d"/><path fill="url(#iojjjIe)" class="l5saph60d"/><g filter="url(#iceZT3c)"><path fill="url(#iASYvNA)" class="yk051b8kx"/></g><g filter="url(#iv0YUFV)"><path class="eg1wj7bgy"/><path fill="url(#imG2Ipd)" class="t7z8qfb-u"/><path fill="url(#iV10eHe)" class="t7z8qfb-u"/><path fill="url(#iVgozac)" class="t7z8qfb-u"/><path fill="url(#i8e4uae)" class="t7z8qfb-u"/></g><g filter="url(#iwjulHb)"><path class="d4v4xubmu"/></g><path stroke="url(#id1sLrd)" class="zs25280ps"/><path class="hbmt10b_q"/><path fill="url(#iGuxbKd)" class="gnsmnbsiz"/><path fill="url(#iEmtHwc)" class="itqfu5aet"/><path class="df30j9bms"/><g filter="url(#iPQiVxd)"><path class="h1a7f9vse"/></g><g filter="url(#imvqJ1c)"><path stroke="url(#ilNSZbb)" class="s8ndzosdx"/></g><g filter="url(#iCHCphd)"><path class="anvzzgqoh"/></g><g filter="url(#is1HHJc)"><path stroke="url(#iDLk02M)" class="u49b3vb3j"/></g><g filter="url(#i06AoUb)"><path fill="url(#inWDPfc)" class="zvv9qvz6c"/></g><g filter="url(#i19AtCF)"><path class="rgx6gerul"/><path fill="url(#izOtn0d)" class="nrujh8kqd"/><path fill="url(#iojbDci)" class="nrujh8kqd"/><path fill="url(#iOvBNCd)" class="nrujh8kqd"/><path fill="url(#in7WuRF)" class="nrujh8kqd"/></g><g filter="url(#ikA7fGd)"><path class="g36pyebob"/></g><g filter="url(#iB5MFvd)"><path fill="url(#ihTqdHd)" class="dzbw1fbmj"/><path fill="url(#iGCfDjc)" class="dzbw1fbmj"/></g><g filter="url(#igZZRVd)"><path class="fk3-b0ocx"/><path fill="url(#irbLrOb)" class="zwwykac4x"/></g><g filter="url(#iJWuRXc)"><path fill="url(#i9IjLOd)" class="s70ylbbla"/></g><g filter="url(#iMrvSAe)"><path fill="url(#iHk95Sb)" class="g8knucmkh"/></g><g filter="url(#iFpzSCU)"><ellipse transform="rotate(-27.914 10.689 18.71)" class="qj22awqlb"/><ellipse fill="url(#idbZ8Ab)" transform="rotate(-27.914 10.689 18.71)" class="iey7ulbyh"/></g><g filter="url(#i3mPerb)"><path fill="url(#iQDQZlc)" class="o7w_zk5zp"/></g><defs><radialGradient id="iw1AWQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 .48438 -.5037 -3.37957 6.633 19.79)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="e83j1pbzf"/><stop offset="1" class="tsnuc-o7q"/></radialGradient><radialGradient id="ipnCEne" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.578 13.211)scale(2.01965)" gradientUnits="userSpaceOnUse"><stop class="ssu63ccnp"/><stop offset="1" class="j68-af44h"/></radialGradient><radialGradient id="iEJBJqe" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 3.842 22.077)scale(4.7194 4.52281)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="q2gi06hfo"/><stop offset="1" class="di4fd-qzw"/></radialGradient><radialGradient id="io5Njub" cx="0" cy="0" r="1" gradientTransform="matrix(1.84823 -2.07813 2.05068 1.82382 25.98 19.383)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="t1bdvwm2a"/><stop offset=".883" class="uygxvob5o"/></radialGradient><radialGradient id="iojjjIe" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -3.8125 2.99389 .63804 26.172 20.68)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="kw5jt0gxx"/><stop offset="1" class="t217_nbyf"/></radialGradient><radialGradient id="iASYvNA" cx="0" cy="0" r="1" gradientTransform="rotate(8.973 -113.946 177.65)scale(1.50276 2.22165)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="kc3i_q84r"/><stop offset="1" class="h0sp3fbhr"/></radialGradient><radialGradient id="iVgozac" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 10.00001 -3.04902 .41924 5.5 19.602)" gradientUnits="userSpaceOnUse"><stop class="j8sqz220e"/><stop offset="1" class="tt6l6i3qr"/></radialGradient><radialGradient id="i8e4uae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 -13.00004 20.39882 -1.96142 10.813 29.96)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="f90e_5b5t"/><stop offset="1" class="eocuezbnh"/></radialGradient><radialGradient id="iGuxbKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 20.328 18.945)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="s28fv4bdt"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="p9hqzqn3a"/></radialGradient><radialGradient id="iEmtHwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 11.358 18.945)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="s28fv4bdt"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="p9hqzqn3a"/></radialGradient><radialGradient id="izOtn0d" cx="0" cy="0" r="1" gradientTransform="matrix(7.82168 -1.52596 1.273 6.52503 12.031 6.414)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="stsoanbmy"/><stop offset="1" class="ovwdp-bik"/></radialGradient><radialGradient id="iojbDci" cx="0" cy="0" r="1" gradientTransform="rotate(-23.69 22.573 -25.21)scale(6.68877 6.45832)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="ovwdp-bik"/><stop offset=".912" class="stsoanbmy"/></radialGradient><radialGradient id="iOvBNCd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63771 -5.65242 5.82757 -3.75043 16.76 8.232)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="aj460xbwf"/><stop offset="1" class="rfngthbki"/></radialGradient><radialGradient id="in7WuRF" cx="0" cy="0" r="1" gradientTransform="rotate(57.863 3.098 16.37)scale(5.75713 5.52963)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="yjjmn1b0t"/><stop offset=".966" class="q4ez5acay"/></radialGradient><radialGradient id="ihTqdHd" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 .04688 -.02424 .98567 15.36 21.695)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="re6r14slg"/><stop offset="1" class="bdxxkoblu"/></radialGradient><radialGradient id="iGCfDjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.79467 0 16.133 21.086)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="pv8_wtbzz"/><stop offset="1" class="qdbiq-bpb"/></radialGradient><radialGradient id="irbLrOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5717 -.73672 1.01428 -.7871 19.765 19.153)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idbZ8Ab" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.917 4.5)scale(1.21806 1.46416)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i0Gprtb" width="4.539" height="4.539" x="4.363" y="17.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".125"/></filter><filter id="iceZT3c" width="4.663" height="4.663" x="23.301" y="17.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".125"/></filter><filter id="iv0YUFV" width="23.65" height="26" x="4.753" y="3.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.333333 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24659"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.490196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24659" result="effect2_innerShadow_3987_24659"/></filter><filter id="iwjulHb" width="7" height="2.4" x="12.633" y="23.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24659"/></filter><filter id="iPQiVxd" width="3.72" height="1.592" x="9.113" y="14.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24659"/></filter><filter id="imvqJ1c" width="3.17" height=".992" x="9.317" y="14.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".1"/></filter><filter id="iCHCphd" width="3.72" height="1.592" x="18.963" y="14.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0784314 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24659"/></filter><filter id="is1HHJc" width="3.17" height=".992" x="19.363" y="14.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".1"/></filter><filter id="i06AoUb" width="7.877" height="8.718" x="12.162" y="2.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".25"/></filter><filter id="i19AtCF" width="8.1" height="8.529" x="11.931" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0313726 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24659"/></filter><filter id="ikA7fGd" width="3.638" height="2.603" x="14.181" y="20.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".25"/></filter><filter id="iB5MFvd" width="3.138" height="2.103" x="14.564" y="20.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".125"/></filter><filter id="igZZRVd" width="1.647" height="1.423" x="18.665" y="18.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".05"/></filter><filter id="iJWuRXc" width="1.611" height="1.666" x="20.881" y="18.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".1"/></filter><filter id="iMrvSAe" width="1.845" height="1.978" x="11.717" y="18.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".1"/></filter><filter id="iFpzSCU" width="1.958" height="1.444" x="9.71" y="17.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation=".05"/></filter><filter id="i3mPerb" width="13.584" height="12.368" x="14.564" y="4.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24659" stdDeviation="1.25"/></filter><linearGradient id="iueZkzc" x1="3.906" x2="6.25" y1="17.039" y2="23.039" gradientUnits="userSpaceOnUse"><stop class="jzuduyb2o"/><stop offset="1" class="y0i156btv"/></linearGradient><linearGradient id="iWS1Ksd" x1="28.516" x2="25.933" y1="18.102" y2="22.289" gradientUnits="userSpaceOnUse"><stop class="kzj9y0b0j"/><stop offset="1" class="ekonz16jg"/></linearGradient><linearGradient id="imG2Ipd" x1="16.153" x2="16.153" y1="30.539" y2="25.414" gradientUnits="userSpaceOnUse"><stop offset=".195" class="n54r9cbvw"/><stop offset="1" class="dxeyl9_7p"/></linearGradient><linearGradient id="iV10eHe" x1="6.938" x2="18.188" y1="18.039" y2="20.914" gradientUnits="userSpaceOnUse"><stop class="w39e-ubuo"/><stop offset="1" class="nvpd1fzwj"/></linearGradient><linearGradient id="id1sLrd" x1="13.797" x2="14.297" y1="25.023" y2="24.117" gradientUnits="userSpaceOnUse"><stop class="y8yymsbkp"/><stop offset="1" class="f5plm9-fv"/></linearGradient><linearGradient id="ilNSZbb" x1="12.531" x2="9.359" y1="14.617" y2="15.026" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iDLk02M" x1="22.577" x2="19.405" y1="14.565" y2="14.973" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="inWDPfc" x1="16.459" x2="15.42" y1="3.034" y2="10.528" gradientUnits="userSpaceOnUse"><stop class="w78w6v86k"/><stop offset="1" class="quv0ho30c"/></linearGradient><linearGradient id="i9IjLOd" x1="22.245" x2="21.472" y1="19.078" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHk95Sb" x1="13.191" x2="12.418" y1="19.078" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQDQZlc" x1="17.804" x2="27.5" y1="14.508" y2="8.664" gradientUnits="userSpaceOnUse"><stop class="e1m7epfuh"/><stop offset="1" class="ybfagfbdb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-medium-dark" /></template>
<style>
.aj460xbwf {
  stop-color: var(--svg-color--3e3431, #3E3431);
  stop-opacity: 0;
}

.anvzzgqoh {
  stroke: var(--svg-color--332422, #332422);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.183 15.12c-.59-.21-1.41-.36-2.47-.26");
}

.aw0-ozbwv {
  d: path("M6.633 23.04a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.bdxxkoblu {
  stop-color: var(--svg-color--98726a, #98726A);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d4v4xubmu {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.125 24.002a6.4 6.4 0 0 1-3.007-.732c-.299-.161-.617.18-.428.471a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.28-.13-.622-.428-.471a6.55 6.55 0 0 1-3.027.732");
}

.df30j9bms {
  fill: var(--svg-color--000, #000);
  d: path("M19.073 19.97c0-.7.56-1.26 1.26-1.26s1.26.56 1.26 1.26c0 .21-.05.41-.14.58h-2.23c-.1-.17-.15-.37-.15-.58m-6.46 0c0-.7-.56-1.26-1.26-1.26s-1.26.56-1.26 1.26c0 .21.05.41.14.58h2.23c.09-.17.15-.37.15-.58");
}

.di4fd-qzw {
  stop-color: var(--svg-color--794566, #794566);
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.dxeyl9_7p {
  stop-color: var(--svg-color--7d4271, #7D4271);
  stop-opacity: 0;
}

.dzbw1fbmj {
  d: path("M16.135 22.69c.51 0 .964-.282 1.225-.703c.238-.386-.011-.901-.445-.901h-1.56c-.434 0-.694.527-.444.901c.26.433.715.702 1.224.702");
}

.e1m7epfuh {
  stop-color: var(--svg-color--b08579, #B08579);
}

.e83j1pbzf {
  stop-color: var(--svg-color--825d58, #825D58);
  stop-opacity: 0;
}

.eg1wj7bgy {
  fill: var(--svg-color--9a6b5e, #9A6B5E);
  d: path("M23.362 5.751a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.112c.296 3.14 2.377 5.78 5.265 6.68c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.7-3.745-8.69");
}

.ekonz16jg {
  stop-color: var(--svg-color--7f5258, #7F5258);
}

.eocuezbnh {
  stop-color: var(--svg-color--733f59, #733F59);
  stop-opacity: 0;
}

.f5plm9-fv {
  stop-color: var(--svg-color--845b5f, #845B5F);
  stop-opacity: 0;
}

.f90e_5b5t {
  stop-color: var(--svg-color--733f59, #733F59);
}

.fk3-b0ocx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.171 18.234c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.125");
}

.ft5dv1b6b {
  fill: none;
}

.g36pyebob {
  fill: var(--svg-color--753f4c, #753F4C);
  d: path("M16.002 23.039c.51 0 .965-.28 1.225-.702c.238-.386-.011-.901-.445-.901h-1.56c-.433 0-.693.526-.444.9c.26.434.715.703 1.224.703");
}

.g8knucmkh {
  d: path("M13.363 19.71c0-.71-.578-1.184-.735-1.327l-.71.687l.437.89z");
}

.gnsmnbsiz {
  d: path("M20.333 17.77a2.2 2.2 0 0 1 2.12 2.78h-4.25c-.05-.19-.08-.38-.08-.58c0-1.21.99-2.2 2.21-2.2");
}

.h0sp3fbhr {
  stop-color: var(--svg-color--7b4941, #7B4941);
}

.h1a7f9vse {
  stroke: var(--svg-color--2d1e1d, #2D1E1D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.613 15.12c.59-.21 1.41-.36 2.47-.26");
}

.hbmt10b_q {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.843 17.1c1.61 0 2.97 1.11 3.34 2.61c.11.43-.22.84-.66.84h-5.5c-.35 0-.63-.32-.56-.67c.31-1.58 1.7-2.78 3.38-2.78m-10 0c-1.61 0-2.97 1.11-3.34 2.61c-.11.43.22.84.66.84h5.5c.35 0 .63-.32.56-.67a3.454 3.454 0 0 0-3.38-2.78");
}

.iey7ulbyh {
  cx: 10.689px;
  cy: 18.709px;
  rx: 0.96px;
  ry: 0.486px;
}

.itqfu5aet {
  d: path("M11.353 17.77a2.2 2.2 0 0 0-2.12 2.78h4.25c.05-.19.08-.38.08-.58c-.01-1.21-.99-2.2-2.21-2.2");
}

.j68-af44h {
  stop-color: var(--svg-color--5a343a, #5A343A);
}

.j8sqz220e {
  stop-color: var(--svg-color--836059, #836059);
}

.jzuduyb2o {
  stop-color: var(--svg-color--65423d, #65423D);
}

.kc3i_q84r {
  stop-color: var(--svg-color--835e58, #835E58);
}

.kw5jt0gxx {
  stop-color: var(--svg-color--8e6d5e, #8E6D5E);
  stop-opacity: 0;
}

.kzj9y0b0j {
  stop-color: var(--svg-color--997768, #997768);
}

.l5saph60d {
  d: path("M25.633 23.04a3.25 3.25 0 1 0 0-6.501a3.25 3.25 0 0 0 0 6.5");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n54r9cbvw {
  stop-color: var(--svg-color--7d4271, #7D4271);
}

.nrujh8kqd {
  d: path("M15.831 2.04a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.nvpd1fzwj {
  stop-color: var(--svg-color--734a4b, #734A4B);
  stop-opacity: 0;
}

.o7w_zk5zp {
  d: path("m18.483 9.146l4.36-2.326c2.774 2 2.899 5.615 2.774 6.594l-5.513.75a2.679 2.679 0 0 1-1.621-5.018");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovwdp-bik {
  stop-color: var(--svg-color--4b4849, #4B4849);
}

.p9hqzqn3a {
  stop-color: var(--svg-color--6d4c4a, #6D4C4A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pv8_wtbzz {
  stop-color: var(--svg-color--7c4457, #7C4457);
  stop-opacity: 0;
}

.q2gi06hfo {
  stop-color: var(--svg-color--794566, #794566);
  stop-opacity: 0;
}

.q4ez5acay {
  stop-color: var(--svg-color--1a1118, #1A1118);
}

.qdbiq-bpb {
  stop-color: var(--svg-color--7c4457, #7C4457);
}

.qj22awqlb {
  cx: 10.689px;
  cy: 18.709px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.96px;
  ry: 0.486px;
}

.quv0ho30c {
  stop-color: var(--svg-color--724139, #724139);
}

.re6r14slg {
  stop-color: var(--svg-color--8e6559, #8E6559);
}

.rfngthbki {
  stop-color: var(--svg-color--3e3431, #3E3431);
}

.rgx6gerul {
  fill: var(--svg-color--211b1d, #211B1D);
  d: path("M15.831 2.04a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.s28fv4bdt {
  stop-color: var(--svg-color--865f54, #865F54);
}

.s70ylbbla {
  d: path("M22.292 19.68a2.07 2.07 0 0 0-.57-1.14l-.64.702l.288.563z");
}

.s8ndzosdx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.668 15.026c.59-.21 1.41-.36 2.47-.26");
}

.ssu63ccnp {
  stop-color: var(--svg-color--5a2f2f, #5A2F2F);
}

.stsoanbmy {
  stop-color: var(--svg-color--4c494a, #4C494A);
  stop-opacity: 0;
}

.t1bdvwm2a {
  stop-color: var(--svg-color--7a4941, #7A4941);
}

.t217_nbyf {
  stop-color: var(--svg-color--8e6d5e, #8E6D5E);
}

.t7z8qfb-u {
  d: path("M23.362 5.751a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.112c.296 3.14 2.377 5.78 5.265 6.68c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.7-3.745-8.69");
}

.tsnuc-o7q {
  stop-color: var(--svg-color--825d58, #825D58);
}

.tt6l6i3qr {
  stop-color: var(--svg-color--836059, #836059);
  stop-opacity: 0;
}

.u49b3vb3j {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22.183 14.974c-.59-.21-1.41-.36-2.47-.26");
}

.uygxvob5o {
  stop-color: var(--svg-color--7a4941, #7A4941);
  stop-opacity: 0;
}

.w39e-ubuo {
  stop-color: var(--svg-color--734a4b, #734A4B);
}

.w78w6v86k {
  stop-color: var(--svg-color--553327, #553327);
}

.wpfvvtbjo {
  d: path("M6.633 21.809a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.y0i156btv {
  stop-color: var(--svg-color--653549, #653549);
}

.y8yymsbkp {
  stop-color: var(--svg-color--845b5f, #845B5F);
}

.ybfagfbdb {
  stop-color: var(--svg-color--b08579, #B08579);
  stop-opacity: 0;
}

.yjjmn1b0t {
  stop-color: var(--svg-color--1a1118, #1A1118);
  stop-opacity: 0;
}

.yk051b8kx {
  d: path("M25.633 21.87a2.081 2.081 0 1 0 0-4.162a2.081 2.081 0 0 0 0 4.163");
}

.zs25280ps {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.153 23.203c-.367-.197-.757.223-.526.58l.063-.042a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.28-.13-.622-.428-.471a6.55 6.55 0 0 1-3.027.732a6.4 6.4 0 0 1-3.007-.732z");
}

.zvv9qvz6c {
  d: path("M16.252 3.006c-1.473-.222-2.757-.003-3.59 1.11c1.994 0 4.463 1.673 4.325 3.843a2.97 2.97 0 0 1-.994 1.815a.492.492 0 0 0 .403.863A3.87 3.87 0 0 0 19.5 7.363c.298-2.086-1.164-4.04-3.248-4.357");
}

.zwwykac4x {
  d: path("M20.171 18.234c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.125");
}

</style>
