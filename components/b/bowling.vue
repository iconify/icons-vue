<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXD6FBc)"><path class="ma3e1iyzp"/><path fill="url(#i3OEdDn)" class="b4sowlbzh"/><path fill="url(#iJf9O3b)" class="b4sowlbzh"/></g><path fill="url(#iJWdOVd)" class="b4sowlbzh"/><path fill="url(#iFdNqqc)" class="b4sowlbzh"/><path fill="url(#iEAzbYc)" class="b4sowlbzh"/><path fill="url(#iVCY9Db)" class="b4sowlbzh"/><path fill="url(#inR3Efd)" class="b4sowlbzh"/><path fill="url(#iwx4Ems)" class="zqble0b2e"/><path fill="url(#izCnTSb)" class="fw7kk8k9j"/><g filter="url(#iXX1qGe)"><path class="iwszehbou"/><path fill="url(#iVOq9Zb)" class="locmnobvg"/><path fill="url(#i6Fbgue)" class="locmnobvg"/></g><path fill="url(#i0ajdGb)" class="locmnobvg"/><path fill="url(#i3dxDPc)" class="locmnobvg"/><path fill="url(#iI0vefc)" class="locmnobvg"/><path fill="url(#iUNQVKc)" class="locmnobvg"/><path fill="url(#iX3YV6d)" class="nrj95vkkn"/><path fill="url(#i3fo8Qd)" class="xmnswlg_w"/><g filter="url(#iWIBhVc)"><path fill="url(#iL6qVqc)" class="e75djgbrj"/></g><path fill="url(#iOQOkIb)" class="lcb-6-tfx"/><path fill="url(#iyc6dIx)" class="rrrfxe9na"/><path fill="url(#iDvSrHI)" class="arman2bei"/><defs><radialGradient id="i3OEdDn" cx="0" cy="0" r="1" gradientTransform="matrix(-4.8297 2.67495 -2.18172 -3.93917 27.872 7.594)" gradientUnits="userSpaceOnUse"><stop class="o80-2vw4x"/><stop offset="1" class="yrlphybth"/></radialGradient><radialGradient id="iJf9O3b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.70836 1.48606 -2.00439 -7.69937 30.015 20.448)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="o80-2vw4x"/><stop offset="1" class="yrlphybth"/></radialGradient><radialGradient id="iJWdOVd" cx="0" cy="0" r="1" gradientTransform="rotate(-27.646 72.018 -23.556)scale(9.22897 9.40675)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="oqby6fb5l"/><stop offset="1" class="e-wjrtbzv"/></radialGradient><radialGradient id="iEAzbYc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66592 -1.62206 1.15135 -2.60209 26.808 13.209)" gradientUnits="userSpaceOnUse"><stop class="knkdr4bvk"/><stop offset="1" class="mf4vk811c"/></radialGradient><radialGradient id="iVCY9Db" cx="0" cy="0" r="1" gradientTransform="matrix(2.94727 .70176 -1.04256 4.37856 19.624 26.17)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="v2_93zb5t"/><stop offset="1" class="mpnn1o7kz"/></radialGradient><radialGradient id="inR3Efd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.36963 2.45603 -2.00317 -3.56393 28.676 6.872)" gradientUnits="userSpaceOnUse"><stop class="o80-2vw4x"/><stop offset="1" class="yrlphybth"/></radialGradient><radialGradient id="iVOq9Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.8297 2.67495 -2.18172 -3.93917 19.942 7.594)" gradientUnits="userSpaceOnUse"><stop class="o80-2vw4x"/><stop offset="1" class="yrlphybth"/></radialGradient><radialGradient id="i6Fbgue" cx="0" cy="0" r="1" gradientTransform="matrix(-5.70836 1.48606 -2.00439 -7.69937 22.085 20.448)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="o80-2vw4x"/><stop offset="1" class="yrlphybth"/></radialGradient><radialGradient id="i0ajdGb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.646 68.053 -7.441)scale(9.22897 9.40675)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="rpap3hbmq"/><stop offset="1" class="hx7ywfi8e"/></radialGradient><radialGradient id="iI0vefc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66592 -1.62206 1.15135 -2.60209 18.878 13.209)" gradientUnits="userSpaceOnUse"><stop class="knkdr4bvk"/><stop offset="1" class="mf4vk811c"/></radialGradient><radialGradient id="iUNQVKc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.36963 2.45603 -2.00317 -3.56393 20.746 6.872)" gradientUnits="userSpaceOnUse"><stop class="o80-2vw4x"/><stop offset="1" class="yrlphybth"/></radialGradient><radialGradient id="iL6qVqc" cx="0" cy="0" r="1" gradientTransform="rotate(129.245 2.09 12.507)scale(12.8668)" gradientUnits="userSpaceOnUse"><stop class="q19m4_bri"/><stop offset="1" class="gin_2_b9c"/></radialGradient><radialGradient id="iOQOkIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.58379 -1.30223 1.2219 1.4861 6.436 22.308)" gradientUnits="userSpaceOnUse"><stop class="uo5firszl"/><stop offset="1" class="pxf92hbxs"/></radialGradient><radialGradient id="iyc6dIx" cx="0" cy="0" r="1" gradientTransform="matrix(1.58379 -1.30223 1.2219 1.4861 10.116 22.308)" gradientUnits="userSpaceOnUse"><stop class="xlccmrbpf"/><stop offset="1" class="knzx8cces"/></radialGradient><radialGradient id="iDvSrHI" cx="0" cy="0" r="1" gradientTransform="matrix(1.58379 -1.30223 1.2219 1.4861 8.366 19.478)" gradientUnits="userSpaceOnUse"><stop class="gjalreb4s"/><stop offset="1" class="m3u7cm_5c"/></radialGradient><linearGradient id="iFdNqqc" x1="24.804" x2="24.804" y1="30.035" y2="29.634" gradientUnits="userSpaceOnUse"><stop class="m3zb_4bzs"/><stop offset="1" class="grlhm974x"/></linearGradient><linearGradient id="iwx4Ems" x1="23.01" x2="26.095" y1="14.379" y2="14.379" gradientUnits="userSpaceOnUse"><stop class="cj5tdpauj"/><stop offset="1" class="fmco0db_a"/></linearGradient><linearGradient id="izCnTSb" x1="23.052" x2="26" y1="16.829" y2="16.829" gradientUnits="userSpaceOnUse"><stop class="vzmpgbbqp"/><stop offset="1" class="fmco0db_a"/></linearGradient><linearGradient id="i3dxDPc" x1="16.874" x2="16.874" y1="30.035" y2="29.634" gradientUnits="userSpaceOnUse"><stop class="m3zb_4bzs"/><stop offset="1" class="grlhm974x"/></linearGradient><linearGradient id="iX3YV6d" x1="14.431" x2="18.571" y1="13.709" y2="13.709" gradientUnits="userSpaceOnUse"><stop class="l242ebbpo"/><stop offset="1" class="vew34rm3z"/></linearGradient><linearGradient id="i3fo8Qd" x1="15.133" x2="18.08" y1="16.829" y2="16.829" gradientUnits="userSpaceOnUse"><stop class="gru5mvbsa"/><stop offset="1" class="fmco0db_a"/></linearGradient><filter id="iXD6FBc" width="12.417" height="23.969" x="18.598" y="5.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.686275 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2431"/></filter><filter id="iXX1qGe" width="12.417" height="23.969" x="10.668" y="5.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.686275 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2431"/></filter><filter id="iWIBhVc" width="14.54" height="14.29" x="1.735" y="15.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2431"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.215686 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2431" result="effect2_innerShadow_18_2431"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bowling" /></template>
<style>
.arman2bei {
  d: path("M9.095 19.82a1.13 1.13 0 1 0 0-2.26a1.13 1.13 0 0 0 0 2.26");
}

.b4sowlbzh {
  d: path("M26.545 15.7c0-1.63.39-3.24 1.04-4.73a3.588 3.588 0 0 0-3.55-5.01a3.6 3.6 0 0 0-3.33 3.35c-.04.61.08 1.19.31 1.71c.64 1.41 1.02 2.93 1.02 4.48v.2c0 .92-.38 1.8-1.04 2.44l-.29.28c-2.78 2.66-2.81 7.09-.08 9.8l1.51 1.49c.13.13.32.21.51.21h3.32c.19 0 .37-.07.51-.21l1.51-1.5a6.835 6.835 0 0 0-.08-9.8l-.3-.28a3.27 3.27 0 0 1-1.06-2.43");
}

.cj5tdpauj {
  stop-color: var(--svg-color--d72b4d, #D72B4D);
}

.e-wjrtbzv {
  stop-color: var(--svg-color--b07ed9, #B07ED9);
  stop-opacity: 0;
}

.e75djgbrj {
  d: path("M9.005 29.97a7.02 7.02 0 1 0 0-14.04a7.02 7.02 0 0 0 0 14.04");
}

.fmco0db_a {
  stop-color: var(--svg-color--ff5694, #FF5694);
}

.ft5dv1b6b {
  fill: none;
}

.fw7kk8k9j {
  d: path("M26.755 16.83a3.3 3.3 0 0 1-.21-1.14c0-.07.01-.13.01-.2h-4.53v.2c0 .39-.08.77-.21 1.14z");
}

.gin_2_b9c {
  stop-color: var(--svg-color--492d6c, #492D6C);
}

.gjalreb4s {
  stop-color: var(--svg-color--3a224c, #3A224C);
}

.grlhm974x {
  stop-color: var(--svg-color--aa7dd2, #AA7DD2);
  stop-opacity: 0;
}

.gru5mvbsa {
  stop-color: var(--svg-color--cc314c, #CC314C);
}

.hx7ywfi8e {
  stop-color: var(--svg-color--a87ad0, #A87AD0);
  stop-opacity: 0;
}

.iwszehbou {
  fill: var(--svg-color--dad4e3, #DAD4E3);
  d: path("M18.615 15.7c0-1.63.39-3.24 1.04-4.73a3.588 3.588 0 0 0-3.55-5.01a3.6 3.6 0 0 0-3.33 3.35c-.04.61.08 1.19.31 1.71c.64 1.41 1.02 2.93 1.02 4.48v.2c0 .92-.38 1.8-1.04 2.44l-.29.28c-2.78 2.66-2.81 7.09-.08 9.8l1.51 1.49c.13.13.32.21.51.21h3.32c.19 0 .37-.07.51-.21l1.51-1.5a6.835 6.835 0 0 0-.08-9.8l-.3-.28a3.3 3.3 0 0 1-1.06-2.43");
}

.knkdr4bvk {
  stop-color: var(--svg-color--ddd1eb, #DDD1EB);
}

.knzx8cces {
  stop-color: var(--svg-color--311644, #311644);
}

.l242ebbpo {
  stop-color: var(--svg-color--bc3246, #BC3246);
}

.lcb-6-tfx {
  d: path("M7.165 22.65a1.13 1.13 0 1 0 0-2.26a1.13 1.13 0 0 0 0 2.26");
}

.locmnobvg {
  d: path("M18.615 15.7c0-1.63.39-3.24 1.04-4.73a3.588 3.588 0 0 0-3.55-5.01a3.6 3.6 0 0 0-3.33 3.35c-.04.61.08 1.19.31 1.71c.64 1.41 1.02 2.93 1.02 4.48v.2c0 .92-.38 1.8-1.04 2.44l-.29.28c-2.78 2.66-2.81 7.09-.08 9.8l1.51 1.49c.13.13.32.21.51.21h3.32c.19 0 .37-.07.51-.21l1.51-1.5a6.835 6.835 0 0 0-.08-9.8l-.3-.28a3.3 3.3 0 0 1-1.06-2.43");
}

.m3u7cm_5c {
  stop-color: var(--svg-color--25112e, #25112E);
}

.m3zb_4bzs {
  stop-color: var(--svg-color--aa7dd2, #AA7DD2);
}

.ma3e1iyzp {
  fill: var(--svg-color--dad4e3, #DAD4E3);
  d: path("M26.545 15.7c0-1.63.39-3.24 1.04-4.73a3.588 3.588 0 0 0-3.55-5.01a3.6 3.6 0 0 0-3.33 3.35c-.04.61.08 1.19.31 1.71c.64 1.41 1.02 2.93 1.02 4.48v.2c0 .92-.38 1.8-1.04 2.44l-.29.28c-2.78 2.66-2.81 7.09-.08 9.8l1.51 1.49c.13.13.32.21.51.21h3.32c.19 0 .37-.07.51-.21l1.51-1.5a6.835 6.835 0 0 0-.08-9.8l-.3-.28a3.27 3.27 0 0 1-1.06-2.43");
}

.mf4vk811c {
  stop-color: var(--svg-color--ddd1eb, #DDD1EB);
  stop-opacity: 0;
}

.mpnn1o7kz {
  stop-color: var(--svg-color--b192cd, #B192CD);
  stop-opacity: 0;
}

.nrj95vkkn {
  d: path("M18.955 13.04h-5.17c.11.44.2.89.25 1.34h4.67c.06-.45.14-.89.25-1.34");
}

.o80-2vw4x {
  stop-color: var(--svg-color--faf9fd, #FAF9FD);
}

.oqby6fb5l {
  stop-color: var(--svg-color--b07ed9, #B07ED9);
}

.pxf92hbxs {
  stop-color: var(--svg-color--291737, #291737);
}

.q19m4_bri {
  stop-color: var(--svg-color--7d79c2, #7D79C2);
}

.rpap3hbmq {
  stop-color: var(--svg-color--a87ad0, #A87AD0);
}

.rrrfxe9na {
  d: path("M10.845 22.65a1.13 1.13 0 1 0 0-2.26a1.13 1.13 0 0 0 0 2.26");
}

.uo5firszl {
  stop-color: var(--svg-color--3f2b52, #3F2B52);
}

.v2_93zb5t {
  stop-color: var(--svg-color--b192cd, #B192CD);
}

.vew34rm3z {
  stop-color: var(--svg-color--fe3a86, #FE3A86);
}

.vzmpgbbqp {
  stop-color: var(--svg-color--d8324d, #D8324D);
}

.xlccmrbpf {
  stop-color: var(--svg-color--52336e, #52336E);
}

.xmnswlg_w {
  d: path("M18.835 16.83a3.3 3.3 0 0 1-.21-1.14c0-.07.01-.13.01-.2h-4.53v.2c0 .39-.08.77-.21 1.14z");
}

.yrlphybth {
  stop-color: var(--svg-color--faf9fd, #FAF9FD);
  stop-opacity: 0;
}

.zqble0b2e {
  d: path("M26.885 13.04h-5.17c.11.44.2.89.25 1.34h4.67c.05-.45.14-.89.25-1.34");
}

</style>
