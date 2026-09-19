<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ij8h9iM)" class="qib_kju9v"/><g filter="url(#i1l8PfA)"><rect fill="url(#idrtP2d)" class="t9y6duqwc"/><rect fill="url(#iDSDsnd)" class="t9y6duqwc"/></g><rect fill="url(#i0ybjce)" class="t9y6duqwc"/><rect fill="url(#i0ybjce)" class="t9y6duqwc"/><g filter="url(#iTZ0dNb)"><rect fill="url(#ib877Fb)" class="afu192brx"/><rect fill="url(#iaX6Xve)" class="afu192brx"/></g><rect fill="url(#iO0kEjc)" class="afu192brx"/><g filter="url(#i6Oxatd)"><rect fill="url(#iCdzUIr)" class="vaihbrbnx"/></g><rect fill="url(#i2lnZLc)" class="vaihbrbnx"/><path fill="url(#ixD8aDe)" class="xj11ui05d"/><path fill="url(#ihGQVbd)" class="xj11ui05d"/><path fill="url(#ipMm0Nd)" class="xj11ui05d"/><g filter="url(#iSyCt2E)"><path fill="url(#iWY27rb)" clip-rule="evenodd" class="n7qiucb0w"/></g><g filter="url(#iJOrKor)"><path fill="url(#iPXRRrd)" class="q-trlro6l"/></g><g filter="url(#iEGurba)"><path fill="url(#i1EDNtc)" class="qtdaplb_w"/></g><g filter="url(#ijReJRc)"><path fill="url(#iEhlxwe)" class="eyb7d9bvi"/></g><g filter="url(#iTxErfd)"><path fill="url(#iSxmMFj)" class="ir60586ti"/></g><rect fill="url(#iLuFLkc)" class="atb7wha4u"/><defs><linearGradient id="ij8h9iM" x1="16" x2="16" y1="6.422" y2="16.984" gradientUnits="userSpaceOnUse"><stop class="turye-btt"/><stop offset="1" class="ehuuqhzwn"/></linearGradient><linearGradient id="idrtP2d" x1="16" x2="16" y1="5.063" y2="8.619" gradientUnits="userSpaceOnUse"><stop class="e601fdi6v"/><stop offset="1" class="qylweibpb"/></linearGradient><linearGradient id="iDSDsnd" x1="16" x2="16" y1="8.689" y2="6.676" gradientUnits="userSpaceOnUse"><stop class="l6wajubyh"/><stop offset="1" class="zc3mrfpjl"/></linearGradient><linearGradient id="ib877Fb" x1="16" x2="16" y1="9.063" y2="22.474" gradientUnits="userSpaceOnUse"><stop class="prc8g6bxc"/><stop offset="1" class="fu2p9cciz"/></linearGradient><linearGradient id="iaX6Xve" x1="16" x2="16" y1="13.383" y2="10.641" gradientUnits="userSpaceOnUse"><stop class="l6wajubyh"/><stop offset="1" class="zc3mrfpjl"/></linearGradient><linearGradient id="iCdzUIr" x1="16" x2="16" y1="12.938" y2="26.349" gradientUnits="userSpaceOnUse"><stop class="prc8g6bxc"/><stop offset="1" class="fu2p9cciz"/></linearGradient><linearGradient id="ixD8aDe" x1="15.906" x2="15.906" y1="16.094" y2="29.875" gradientUnits="userSpaceOnUse"><stop class="nrnu9j57l"/><stop offset="1" class="x1n7boq7y"/></linearGradient><linearGradient id="ihGQVbd" x1="30.031" x2="27.344" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".547" class="az_9ucbvs"/><stop offset="1" class="l7tq1l2rt"/></linearGradient><linearGradient id="ipMm0Nd" x1="1.969" x2="4.5" y1="25.188" y2="25.188" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="iWY27rb" x1="15.91" x2="15.91" y1="21.016" y2="26.953" gradientUnits="userSpaceOnUse"><stop class="pvv9lqo2b"/><stop offset="1" class="eibd44bbj"/></linearGradient><linearGradient id="iPXRRrd" x1="15.906" x2="15.906" y1="5.063" y2="14.969" gradientUnits="userSpaceOnUse"><stop class="p0-lobcyl"/><stop offset="1" class="ld0e_netw"/></linearGradient><linearGradient id="i1EDNtc" x1="12.219" x2="10.961" y1="10.938" y2="12.938" gradientUnits="userSpaceOnUse"><stop class="e1dzkq1ma"/><stop offset="1" class="zn6ew-7at"/></linearGradient><linearGradient id="iEhlxwe" x1="16.625" x2="15.906" y1="7.063" y2="9.063" gradientUnits="userSpaceOnUse"><stop class="uqljsjyyy"/><stop offset="1" class="cy-ezwg6m"/></linearGradient><linearGradient id="iSxmMFj" x1="21.563" x2="20.867" y1="2.719" y2="5.063" gradientUnits="userSpaceOnUse"><stop class="hefji0bsz"/><stop offset="1" class="ehal60bxd"/></linearGradient><linearGradient id="iLuFLkc" x1="18.406" x2="14.906" y1="22.344" y2="25.992" gradientUnits="userSpaceOnUse"><stop class="k11r6vb3l"/><stop offset="1" class="u63cp8bec"/></linearGradient><filter id="i1l8PfA" width="22.3" height="13.812" x="4.7" y="5.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.890196 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.792157 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><filter id="iTZ0dNb" width="22.3" height="14.212" x="4.7" y="8.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.6 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.890196 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><filter id="i6Oxatd" width="22.3" height="14.212" x="4.7" y="12.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.6 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.945098 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><filter id="iSyCt2E" width="8.777" height="6.838" x="11.422" y="20.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.2 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_23356"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_23356" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.294118 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.486275 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23356" result="effect3_innerShadow_18_23356"/></filter><filter id="iJOrKor" width="28.075" height="13.481" x="1.869" y="4.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.427451 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.333333 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><filter id="iEGurba" width="6.223" height="2.1" x="7.849" y="10.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.25098 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><filter id="ijReJRc" width="6.223" height="2.1" x="12.794" y="7.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.611765 0 0 0 0 0.85098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.501961 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><filter id="iTxErfd" width="6.223" height="2.1" x="17.756" y="3.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.905882 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23356"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.713726 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23356" result="effect2_innerShadow_18_23356"/></filter><radialGradient id="i0ybjce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25801 1.28097 -2.16672 -2.12789 27 5.422)" gradientUnits="userSpaceOnUse"><stop class="axnqlt9zy"/><stop offset="1" class="yta38ub3w"/></radialGradient><radialGradient id="iO0kEjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25801 1.28097 -2.16672 -2.12789 27 9.422)" gradientUnits="userSpaceOnUse"><stop class="axnqlt9zy"/><stop offset="1" class="yta38ub3w"/></radialGradient><radialGradient id="i2lnZLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25801 1.28097 -2.16672 -2.12789 27 13.297)" gradientUnits="userSpaceOnUse"><stop class="axnqlt9zy"/><stop offset="1" class="yta38ub3w"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:card-file-box" /></template>
<style>
.afu192brx {
  width: 22px;
  height: 13.412px;
  x: 5px;
  y: 9.063px;
  rx: 2.5px;
}

.atb7wha4u {
  width: 6.023px;
  height: 4.016px;
  x: 12.898px;
  y: 21.977px;
  rx: 0.4px;
}

.axnqlt9zy {
  stop-color: var(--svg-color--ffe857, #FFE857);
}

.az_9ucbvs {
  stop-color: var(--svg-color--5d5468, #5D5468);
}

.cy-ezwg6m {
  stop-color: var(--svg-color--4482ca, #4482CA);
}

.e1dzkq1ma {
  stop-color: var(--svg-color--ff416d, #FF416D);
}

.e601fdi6v {
  stop-color: var(--svg-color--ffd650, #FFD650);
}

.ehal60bxd {
  stop-color: var(--svg-color--54c877, #54C877);
}

.ehuuqhzwn {
  stop-color: var(--svg-color--321143, #321143);
}

.eibd44bbj {
  stop-color: var(--svg-color--8466be, #8466BE);
}

.eyb7d9bvi {
  d: path("M12.895 8.063a1 1 0 0 1 1-1h4.023a1 1 0 0 1 1 1v1h-6.023z");
}

.ft5dv1b6b {
  fill: none;
}

.fu2p9cciz {
  stop-color: var(--svg-color--ffba59, #FFBA59);
}

.hefji0bsz {
  stop-color: var(--svg-color--4edc8e, #4EDC8E);
}

.ifgzk3ibd {
  stop-color: var(--svg-color--564f5e, #564F5E);
}

.ir60586ti {
  d: path("M17.856 4.063a1 1 0 0 1 1-1h4.023a1 1 0 0 1 1 1v1h-6.024z");
}

.k11r6vb3l {
  stop-color: var(--svg-color--decbf4, #DECBF4);
}

.l6wajubyh {
  stop-color: var(--svg-color--ffba48, #FFBA48);
}

.l7tq1l2rt {
  stop-color: var(--svg-color--5b5069, #5B5069);
  stop-opacity: 0;
}

.ld0e_netw {
  stop-color: var(--svg-color--6c6695, #6C6695);
}

.n7qiucb0w {
  fill-rule: evenodd;
  d: path("M13.322 21.016a1.4 1.4 0 0 0-1.4 1.4v3.137a1.4 1.4 0 0 0 1.4 1.4h5.176a1.4 1.4 0 0 0 1.4-1.4v-3.137a1.4 1.4 0 0 0-1.4-1.4zm-.023.96a.4.4 0 0 0-.4.4v3.216a.4.4 0 0 0 .4.4h5.223a.4.4 0 0 0 .4-.4v-3.215a.4.4 0 0 0-.4-.4z");
}

.nrnu9j57l {
  stop-color: var(--svg-color--5d4a72, #5D4A72);
}

.p0-lobcyl {
  stop-color: var(--svg-color--63567e, #63567E);
}

.prc8g6bxc {
  stop-color: var(--svg-color--ffda53, #FFDA53);
}

.pvv9lqo2b {
  stop-color: var(--svg-color--8b6dc5, #8B6DC5);
}

.q-trlro6l {
  d: path("M1.969 7.313a2.25 2.25 0 0 1 2.25-2.25H7.5a2.5 2.5 0 0 0-2.225 1.359h-1.04a.75.75 0 0 0-.75.75v9.062c0 .415.335.75.75.75h23.53a.75.75 0 0 0 .75-.75V7.172a.75.75 0 0 0-.75-.75h-1.04a2.5 2.5 0 0 0-2.225-1.36h3.094a2.25 2.25 0 0 1 2.25 2.25v8.782a2.25 2.25 0 0 1-2.25 2.25H4.219a2.25 2.25 0 0 1-2.25-2.25z");
}

.qib_kju9v {
  width: 25.031px;
  height: 10.563px;
  x: 3.484px;
  y: 6.422px;
  rx: 0.75px;
}

.qtdaplb_w {
  d: path("M7.95 11.938a1 1 0 0 1 1-1h4.023a1 1 0 0 1 1 1v1H7.949z");
}

.qylweibpb {
  stop-color: var(--svg-color--ffcd4a, #FFCD4A);
}

.t9y6duqwc {
  width: 22px;
  height: 13.412px;
  x: 5px;
  y: 5.063px;
  rx: 2.5px;
}

.turye-btt {
  stop-color: var(--svg-color--4b3d53, #4B3D53);
}

.u63cp8bec {
  stop-color: var(--svg-color--ccbfdc, #CCBFDC);
}

.uqljsjyyy {
  stop-color: var(--svg-color--4794d7, #4794D7);
}

.vaihbrbnx {
  width: 22px;
  height: 13.412px;
  x: 5px;
  y: 12.938px;
  rx: 2.5px;
}

.x1n7boq7y {
  stop-color: var(--svg-color--544862, #544862);
}

.xj11ui05d {
  d: path("M1.969 16.094v11.531a2.25 2.25 0 0 0 2.25 2.25h23.375a2.25 2.25 0 0 0 2.25-2.25V16.094a2.25 2.25 0 0 1-2.25 2.25H4.219a2.25 2.25 0 0 1-2.25-2.25");
}

.yta38ub3w {
  stop-color: var(--svg-color--ffe857, #FFE857);
  stop-opacity: 0;
}

.zc3mrfpjl {
  stop-color: var(--svg-color--ffba48, #FFBA48);
  stop-opacity: 0;
}

.zn6ew-7at {
  stop-color: var(--svg-color--ff3a66, #FF3A66);
}

.zxrl_acpg {
  stop-color: var(--svg-color--564f5e, #564F5E);
  stop-opacity: 0;
}

</style>
