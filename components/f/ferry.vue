<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVsjikd)"><path fill="url(#iZB19Ae)" class="lkuvvtbww"/><path fill="url(#iztJsse)" class="lkuvvtbww"/><path fill="url(#iCqThjd)" class="lkuvvtbww"/></g><path class="d6j5-mb6o"/><path fill="url(#is47Nuc)" class="dq-560q2x"/><path fill="url(#iIZ8vad)" class="dq-560q2x"/><path fill="url(#ijSZIWA)" class="dq-560q2x"/><g filter="url(#itiU5zQ)"><path fill="url(#im71QWb)" class="x1ndktiuy"/><path fill="url(#iAqKoLe)" class="x1ndktiuy"/></g><g filter="url(#ikucEiF)"><path class="vrmi-rbnh"/></g><path fill="url(#ikypK9d)" class="z_qll6b_f"/><path class="hnzp6rn9x"/><path fill="url(#iLS7Q2d)" class="shcu1hbhf"/><path fill="url(#iKhGqzL)" class="shcu1hbhf"/><path fill="url(#iqn1zgc)" class="cu2pqbcyf"/><g filter="url(#iKPp7Xc)"><path class="hgjwqhb5f"/></g><path fill="url(#iq7zmib)" class="z194ji7ai"/><g filter="url(#iOB5xfh)"><path class="r-n5g0sls"/></g><g filter="url(#iO4rRub)"><path class="vz91e7oxt"/></g><g filter="url(#iu2jI8d)"><path class="zhgzp08wq"/></g><g filter="url(#ihIo6Wc)"><path class="owul4bbcr"/></g><g filter="url(#igndNGc)"><path class="ovel-wb7f"/></g><g filter="url(#iGdGFxe)"><path class="r-p_tlrfy"/></g><g filter="url(#iZuBfac)"><path fill="url(#iK8rU8d)" class="r6o1hqp2s"/><path fill="url(#iiegXcK)" class="r6o1hqp2s"/></g><g filter="url(#i9U52gF)"><path fill="url(#iHaAcnc)" class="mu6452b2z"/></g><path fill="url(#iNzyj7j)" class="uwps5tb1y"/><g filter="url(#imBWCac)"><path class="zku1x9b3m"/></g><g filter="url(#ifeWGae)"><path fill="url(#inSd6qe)" class="e2wqwcbkn"/></g><path fill="url(#ibDxU1h)" class="a3t6md5as"/><path fill="url(#iVfmJie)" class="a3t6md5as"/><path fill="url(#iR4WxAd)" class="a3t6md5as"/><path fill="url(#ixaacSS)" class="esyyu3blg"/><path fill="url(#igy0Uad)" class="esyyu3blg"/><g filter="url(#iKs3Vme)"><path fill="url(#ivxM1Ic)" class="nkokkkb0d"/></g><path fill="url(#iydAwsw)" class="nkokkkb0d"/><defs><linearGradient id="iZB19Ae" x1="30" x2="7.006" y1="16.969" y2="16.957" gradientUnits="userSpaceOnUse"><stop offset=".602" class="uy_s_2bll"/><stop offset="1" class="x_qqkhbyx"/></linearGradient><linearGradient id="iztJsse" x1="18.5" x2="18.5" y1="13.614" y2="16.077" gradientUnits="userSpaceOnUse"><stop class="aj3p7obuh"/><stop offset="1" class="l5wgfbc7v"/></linearGradient><linearGradient id="is47Nuc" x1="11.214" x2="11.655" y1="11.223" y2="10.929" gradientUnits="userSpaceOnUse"><stop class="xu1z22ycc"/><stop offset="1" class="nxbgi_bfe"/></linearGradient><linearGradient id="iIZ8vad" x1="20.125" x2="17.313" y1="10.969" y2="10.969" gradientUnits="userSpaceOnUse"><stop class="no84gb42a"/><stop offset="1" class="ff-pgacww"/></linearGradient><linearGradient id="iAqKoLe" x1="20.183" x2="19.176" y1="7.969" y2="7.969" gradientUnits="userSpaceOnUse"><stop class="ec9ukdcet"/><stop offset="1" class="u_m4_krjo"/></linearGradient><linearGradient id="ikypK9d" x1="25" x2="25" y1="5.969" y2="6.85" gradientUnits="userSpaceOnUse"><stop class="j2y629jcu"/><stop offset="1" class="mingiebps"/></linearGradient><linearGradient id="iLS7Q2d" x1="25.5" x2="25.5" y1="7.969" y2="10.969" gradientUnits="userSpaceOnUse"><stop class="qfhnbkb8y"/><stop offset="1" class="oiqymqgyf"/></linearGradient><linearGradient id="iqn1zgc" x1="9.67" x2="15.006" y1="9.957" y2="9.957" gradientUnits="userSpaceOnUse"><stop class="vkh_zubet"/><stop offset="1" class="cp65m-qgt"/></linearGradient><linearGradient id="iq7zmib" x1="15.061" x2="10.704" y1="5.242" y2="21.501" gradientUnits="userSpaceOnUse"><stop class="vkh_zubet"/><stop offset="1" class="cp65m-qgt"/></linearGradient><linearGradient id="iK8rU8d" x1="19.125" x2="15.625" y1="6.156" y2="5" gradientUnits="userSpaceOnUse"><stop offset=".02" class="au39h8ber"/><stop offset="1" class="jkuvr251v"/></linearGradient><linearGradient id="iiegXcK" x1="16.985" x2="16.985" y1="3.969" y2="4.203" gradientUnits="userSpaceOnUse"><stop class="l5hizv2vz"/><stop offset="1" class="x8atl7abl"/></linearGradient><linearGradient id="iHaAcnc" x1="4.595" x2="30.006" y1="24.457" y2="24.457" gradientUnits="userSpaceOnUse"><stop class="g07zuyb2l"/><stop offset="1" class="d2q4y9bqf"/></linearGradient><linearGradient id="iNzyj7j" x1="19.001" x2="19.001" y1="23.933" y2="24.982" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".849" class="dk8d3t44m"/></linearGradient><linearGradient id="ibDxU1h" x1="30.02" x2="5.02" y1="19.456" y2="19.456" gradientUnits="userSpaceOnUse"><stop class="adqyfefge"/><stop offset="1" class="t66pidb5y"/></linearGradient><linearGradient id="iVfmJie" x1="17.5" x2="17.5" y1="18.969" y2="19.469" gradientUnits="userSpaceOnUse"><stop class="nrtcnq5mo"/><stop offset="1" class="eo0pxgbio"/></linearGradient><linearGradient id="iR4WxAd" x1="5.254" x2="5.984" y1="19.969" y2="19.969" gradientUnits="userSpaceOnUse"><stop class="og6p-ubbu"/><stop offset="1" class="x-_daqara"/></linearGradient><linearGradient id="ixaacSS" x1="30.012" x2="15.012" y1="12.456" y2="12.456" gradientUnits="userSpaceOnUse"><stop class="gind88bhl"/><stop offset="1" class="ulmyjacsn"/></linearGradient><linearGradient id="igy0Uad" x1="22.5" x2="22.5" y1="11.969" y2="12.469" gradientUnits="userSpaceOnUse"><stop class="nrtcnq5mo"/><stop offset="1" class="eo0pxgbio"/></linearGradient><linearGradient id="ivxM1Ic" x1="30" x2="2" y1="24.969" y2="24.969" gradientUnits="userSpaceOnUse"><stop offset=".419" class="ps-2j5qtf"/><stop offset="1" class="u9zq41b2n"/><stop offset="1" class="mzo_t8bcf"/></linearGradient><linearGradient id="iydAwsw" x1="16" x2="16" y1="19.619" y2="21.032" gradientUnits="userSpaceOnUse"><stop class="sqdmhscld"/><stop offset="1" class="mo0gtmb-n"/></linearGradient><filter id="iVsjikd" width="23.25" height="6" x="7" y="13.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.596078 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="itiU5zQ" width="12.15" height="1.1" x="8.1" y="6.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.388235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="ikucEiF" width="10.25" height="6" x="20" y="5.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.713726 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iKPp7Xc" width="5.928" height="2.4" x="9.072" y="8.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.74902 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iOB5xfh" width="5.25" height="3.25" x="8.75" y="14.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25" dy="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.745098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iO4rRub" width="2.5" height="2.5" x="14.5" y="14.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.745098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iu2jI8d" width="2.5" height="2.5" x="17.5" y="14.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.745098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="ihIo6Wc" width="2.5" height="2.5" x="20.5" y="14.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.745098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="igndNGc" width="2.5" height="2.5" x="23.5" y="14.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.745098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iGdGFxe" width="2.5" height="2.5" x="26.5" y="14.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.745098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iZuBfac" width="6.069" height="3" x="14" y="3.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.686275 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="i9U52gF" width="28.5" height="9" x="2" y="19.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.584314 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="imBWCac" width="28.569" height="3.65" x="1.47" y="26.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.67451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12336" result="effect2_innerShadow_18_12336"/></filter><filter id="ifeWGae" width="19.25" height="1.1" x="11" y="12.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.423529 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><filter id="iKs3Vme" width="28.5" height="5.25" x="2" y="19.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.34902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12336"/></filter><radialGradient id="iCqThjd" cx="0" cy="0" r="1" gradientTransform="rotate(134.361 12.427 13.59)scale(4.03908 1.08434)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="ukkvs2b8x"/><stop offset="1" class="fgtd8tqbf"/></radialGradient><radialGradient id="ijSZIWA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12693 1.10011 -.84655 -.8672 15.168 13.152)" gradientUnits="userSpaceOnUse"><stop class="k2l7mfbws"/><stop offset="1" class="ui0gxfbqi"/></radialGradient><radialGradient id="im71QWb" cx="0" cy="0" r="1" gradientTransform="matrix(10.8968 0 0 .5 13.71 7.469)" gradientUnits="userSpaceOnUse"><stop class="f-_1t3bdz"/><stop offset="1" class="xkjfq9ryx"/></radialGradient><radialGradient id="iKhGqzL" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4062 5.18754 -1.16987 -.99367 31.719 7.75)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="mg8rkdabj"/><stop offset="1" class="qo6asmh5n"/></radialGradient><radialGradient id="inSd6qe" cx="0" cy="0" r="1" gradientTransform="matrix(17.3602 0 0 .4989 19.945 13.152)" gradientUnits="userSpaceOnUse"><stop class="l2epqnbmd"/><stop offset="1" class="dtcc6vumf"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ferry" /></template>
<style>
.a3t6md5as {
  d: path("M30 19.969H5v-.4c0-.4.3-.6.6-.6H30z");
}

.adqyfefge {
  stop-color: var(--svg-color--685486, #685486);
}

.aj3p7obuh {
  stop-color: var(--svg-color--807c9a, #807C9A);
}

.au39h8ber {
  stop-color: var(--svg-color--d0cad5, #D0CAD5);
}

.cp65m-qgt {
  stop-color: var(--svg-color--4cf0f8, #4CF0F8);
}

.cu2pqbcyf {
  d: path("M15 10.369v-.8c0-.3-.3-.6-.6-.6H9.7l1.3 2h3.4c.3 0 .6-.3.6-.6");
  opacity: var(--svg-opacity--0-48, 0.48);
}

.d2q4y9bqf {
  stop-color: var(--svg-color--dbdced, #DBDCED);
}

.d6j5-mb6o {
  fill: var(--svg-color--ded5dd, #DED5DD);
  d: path("m9 7.969l3.3 4.9c.2.3.3.7.2 1.1H30v-6z");
}

.dk8d3t44m {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.1;
}

.dq-560q2x {
  d: path("m9 7.969l3.3 4.9c.2.3.3.7.2 1.1H30v-6z");
}

.dtcc6vumf {
  stop-color: var(--svg-color--4fa8ff, #4FA8FF);
}

.e2wqwcbkn {
  d: path("M30 13.969H11.5c-.3 0-.5-.2-.5-.5s.2-.5.5-.5H30z");
}

.ec9ukdcet {
  stop-color: var(--svg-color--2f78ba, #2F78BA);
}

.eo0pxgbio {
  stop-color: var(--svg-color--544a60, #544A60);
  stop-opacity: 0;
}

.esyyu3blg {
  d: path("M30 12.969H15v-.4c0-.4.3-.6.6-.6H30z");
}

.f-_1t3bdz {
  stop-color: var(--svg-color--47afff, #47AFFF);
}

.ff-pgacww {
  stop-color: var(--svg-color--a3969d, #A3969D);
  stop-opacity: 0;
}

.fgtd8tqbf {
  stop-color: var(--svg-color--dedbf2, #DEDBF2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g07zuyb2l {
  stop-color: var(--svg-color--d1cedc, #D1CEDC);
}

.gind88bhl {
  stop-color: var(--svg-color--584e64, #584E64);
}

.hgjwqhb5f {
  fill: var(--svg-color--56f5ff, #56F5FF);
  d: path("M15 10.369v-.8c0-.3-.3-.6-.6-.6H9.672l1.344 2H14.4c.3 0 .6-.3.6-.6");
}

.hnzp6rn9x {
  fill: var(--svg-color--49e8ff, #49E8FF);
  d: path("M21.6 10.969H30v-3h-8.4c-.3 0-.6.3-.6.6v1.7c0 .4.3.7.6.7");
}

.j2y629jcu {
  stop-color: var(--svg-color--f5f0f6, #F5F0F6);
}

.jkuvr251v {
  stop-color: var(--svg-color--d5cdd9, #D5CDD9);
}

.k2l7mfbws {
  stop-color: var(--svg-color--86848f, #86848F);
}

.l2epqnbmd {
  stop-color: var(--svg-color--3ebbff, #3EBBFF);
}

.l5hizv2vz {
  stop-color: var(--svg-color--edebee, #EDEBEE);
}

.l5wgfbc7v {
  stop-color: var(--svg-color--807c9a, #807C9A);
  stop-opacity: 0;
}

.lkuvvtbww {
  d: path("m12.1 14.869l-5.1 5.1h23v-6H12.5c0 .3-.1.6-.4.9");
}

.mg8rkdabj {
  stop-color: var(--svg-color--48e6ff, #48E6FF);
}

.mingiebps {
  stop-color: var(--svg-color--f5f0f6, #F5F0F6);
  stop-opacity: 0;
}

.mo0gtmb-n {
  stop-color: var(--svg-color--35b8ff, #35B8FF);
  stop-opacity: 0;
}

.mu6452b2z {
  d: path("M3 19.969c-.5 0-1 .4-1 1v1c0 1.4.9 2.5 2.2 2.9c.5.1.8.5.8 1v.1c0 1.7 1.3 3 3 3h22v-9z");
}

.mzo_t8bcf {
  stop-color: var(--svg-color--488fea, #488FEA);
}

.nkokkkb0d {
  d: path("M30 24.969v-5H3c-.5 0-1 .4-1 1v1c0 1.4.9 2.5 2.2 2.9q.157.031.286.1z");
}

.no84gb42a {
  stop-color: var(--svg-color--a3969d, #A3969D);
}

.nrtcnq5mo {
  stop-color: var(--svg-color--544a60, #544A60);
}

.nxbgi_bfe {
  stop-color: var(--svg-color--a39ea8, #A39EA8);
  stop-opacity: 0;
}

.og6p-ubbu {
  stop-color: var(--svg-color--3e3e49, #3E3E49);
}

.oiqymqgyf {
  stop-color: var(--svg-color--2094f4, #2094F4);
  stop-opacity: 0;
}

.ovel-wb7f {
  fill: var(--svg-color--52fbff, #52FBFF);
  d: path("M25 16.969c-.6 0-1-.4-1-1s.4-1 1-1s1 .4 1 1c0 .5-.4 1-1 1");
}

.owul4bbcr {
  fill: var(--svg-color--52fbff, #52FBFF);
  d: path("M22 16.969c-.6 0-1-.4-1-1s.4-1 1-1s1 .4 1 1c0 .5-.4 1-1 1");
}

.ps-2j5qtf {
  stop-color: var(--svg-color--3fb6ff, #3FB6FF);
}

.qfhnbkb8y {
  stop-color: var(--svg-color--2094f4, #2094F4);
}

.qo6asmh5n {
  stop-color: var(--svg-color--48e6ff, #48E6FF);
  stop-opacity: 0;
}

.r-n5g0sls {
  fill: var(--svg-color--52fbff, #52FBFF);
  d: path("M14 16.269v-.6c0-.4-.3-.7-.7-.7H12l-2 2h3.3c.4 0 .7-.3.7-.7");
}

.r-p_tlrfy {
  fill: var(--svg-color--52fbff, #52FBFF);
  d: path("M28 16.969c-.6 0-1-.4-1-1s.4-1 1-1s1 .4 1 1c0 .5-.4 1-1 1");
}

.r6o1hqp2s {
  d: path("M19.8 3.969h-2.503c-.1 0-.188 0-.297.1l-3 2.9h4.2l1.7-2.7c.108-.136.1-.3-.1-.3");
}

.shcu1hbhf {
  d: path("M21.6 10.969H30v-3h-8.4c-.3 0-.6.3-.6.6v1.7c0 .4.3.7.6.7");
}

.sqdmhscld {
  stop-color: var(--svg-color--35b8ff, #35B8FF);
}

.t66pidb5y {
  stop-color: var(--svg-color--504a54, #504A54);
}

.u_m4_krjo {
  stop-color: var(--svg-color--2f78ba, #2F78BA);
  stop-opacity: 0;
}

.u9zq41b2n {
  stop-color: var(--svg-color--1876c4, #1876C4);
}

.ui0gxfbqi {
  stop-color: var(--svg-color--86848f, #86848F);
  stop-opacity: 0;
}

.ukkvs2b8x {
  stop-color: var(--svg-color--dedbf2, #DEDBF2);
}

.ulmyjacsn {
  stop-color: var(--svg-color--6b5587, #6B5587);
}

.uwps5tb1y {
  d: path("M30 24.969H8.5c-.3 0-.5-.2-.5-.5s.2-.5.5-.5H30z");
}

.uy_s_2bll {
  stop-color: var(--svg-color--e7e4f3, #E7E4F3);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vkh_zubet {
  stop-color: var(--svg-color--c0fffe, #C0FFFE);
}

.vrmi-rbnh {
  fill: var(--svg-color--ebe3f0, #EBE3F0);
  d: path("M30 11.969H20v-5c0-.6.4-1 1-1h9z");
}

.vz91e7oxt {
  fill: var(--svg-color--52fbff, #52FBFF);
  d: path("M16 16.969c-.6 0-1-.4-1-1s.4-1 1-1s1 .4 1 1c0 .5-.4 1-1 1");
}

.x_qqkhbyx {
  stop-color: var(--svg-color--e3dce6, #E3DCE6);
}

.x-_daqara {
  stop-color: var(--svg-color--3e3e49, #3E3E49);
  stop-opacity: 0;
}

.x1ndktiuy {
  d: path("M20 7.969H8.6c-.3 0-.5-.2-.5-.5s.2-.5.5-.5H20z");
}

.x8atl7abl {
  stop-color: var(--svg-color--edebee, #EDEBEE);
  stop-opacity: 0;
}

.xkjfq9ryx {
  stop-color: var(--svg-color--2b87dc, #2B87DC);
}

.xu1z22ycc {
  stop-color: var(--svg-color--a39ea8, #A39EA8);
}

.z_qll6b_f {
  d: path("M30 11.969H20v-5c0-.6.4-1 1-1h9z");
}

.z194ji7ai {
  d: path("M14 16.269v-.6c0-.4-.3-.7-.7-.7H12l-2 2h3.3c.4 0 .7-.3.7-.7");
}

.zhgzp08wq {
  fill: var(--svg-color--52fbff, #52FBFF);
  d: path("M19 16.969c-.6 0-1-.4-1-1s.4-1 1-1s1 .4 1 1c0 .5-.4 1-1 1");
}

.zku1x9b3m {
  fill: var(--svg-color--4f95f5, #4F95F5);
  d: path("M30.04 27.023c-.923 0-1.83 1.008-3.243 1.008c-1.414 0-1.88-1.07-3.578-1.07c-1.798 0-1.98 1.089-3.696 1.089c-1.316 0-2.085-1.066-3.476-1.066c-1.798 0-2.445 1.066-3.727 1.066c-1.422 0-1.952-1.1-3.75-1.1c-1.203 0-2.172 1.1-3.468 1.1c-1.063 0-1.657-.534-3.032-1.1V30h27.97z");
}

</style>
