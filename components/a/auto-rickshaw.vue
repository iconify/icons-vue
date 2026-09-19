<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGzNQTd)"><path class="j2006_2dc"/></g><g filter="url(#iDrGyCc)"><path class="r3kwxz3cz"/><path fill="url(#iz6ECvd)" class="ms89-obzj"/></g><g filter="url(#iF8q9fc)"><path fill="url(#i2f5pSd)" class="ko4gwiunp"/></g><g filter="url(#iVS4wtc)"><path fill="url(#i74YAJc)" class="mh2peudve"/><path fill="url(#in4mZrb)" class="mh2peudve"/><path fill="url(#i1hw5Zb)" class="mh2peudve"/></g><g filter="url(#i0DZpJd)"><path fill="url(#i1AyKle)" class="plomc0ecs"/></g><path class="a7ptiibgp"/><path fill="url(#iZZmZrv)" class="zir617bwz"/><path fill="url(#iwIS1fd)" class="zir617bwz"/><path fill="url(#iOpOynJ)" class="zir617bwz"/><path fill="url(#iGDWZdd)" class="zir617bwz"/><g filter="url(#iIiCUuc)"><path class="maumwhb8g"/><path fill="url(#i4AbY6c)" class="hqp0jmb2e"/></g><g filter="url(#imwlvhv)"><path class="y-z_56bqr"/></g><path fill="url(#iE7yE1d)" class="gk964dbzt"/><path class="pmilfnron"/><path fill="url(#ijJpGfb)" class="iwvo8ejep"/><g filter="url(#ilDjhZc)"><path fill="url(#iBQm5Rd)" class="snvfy8-ue"/></g><path class="ztc8i-b_a"/><path fill="url(#iOhsmrc)" class="aq8l87b0o"/><path fill="url(#i62phQx)" class="aq8l87b0o"/><g filter="url(#ic2S3wd)"><path fill="url(#i9kqjje)" class="romknsu6g"/></g><g filter="url(#idZ82zb)"><path fill="url(#ica9uzd)" class="ozfzm9vsy"/></g><path fill="url(#iryzpZb)" class="u2q6f-7-k"/><path fill="url(#i2T1tTd)" class="u2q6f-7-k"/><path fill="url(#iKknA1d)" class="u2q6f-7-k"/><path class="h9xh5u5ux"/><path class="c2asm9bob"/><path fill="url(#iYUcNQd)" class="f7-_s8byw"/><path fill="url(#iZzJF2d)" class="f7-_s8byw"/><defs><linearGradient id="iz6ECvd" x1="8.295" x2="10.17" y1="6.025" y2="7.201" gradientUnits="userSpaceOnUse"><stop class="epot3ybtp"/><stop offset="1" class="ev95u638s"/></linearGradient><linearGradient id="i2f5pSd" x1="21.24" x2="24.21" y1="21.53" y2="21.53" gradientUnits="userSpaceOnUse"><stop class="m9lq6qb6l"/><stop offset="1" class="u7svee36f"/></linearGradient><linearGradient id="i74YAJc" x1="3.905" x2="10.908" y1="26.503" y2="26.503" gradientUnits="userSpaceOnUse"><stop class="yzjmohqfk"/><stop offset="1" class="ut9kief7h"/></linearGradient><linearGradient id="in4mZrb" x1="7.404" x2="7.404" y1="25.494" y2="26.869" gradientUnits="userSpaceOnUse"><stop class="coubj68aq"/><stop offset="1" class="hxc4nnn7k"/></linearGradient><linearGradient id="i1hw5Zb" x1="10.644" x2="9.863" y1="25.932" y2="26.498" gradientUnits="userSpaceOnUse"><stop class="coubj68aq"/><stop offset="1" class="hxc4nnn7k"/></linearGradient><linearGradient id="i1AyKle" x1="7.676" x2="7.676" y1="25.682" y2="27.525" gradientUnits="userSpaceOnUse"><stop class="pdr15mbgs"/><stop offset="1" class="dw50o5llj"/></linearGradient><linearGradient id="iwIS1fd" x1="9.566" x2="8.676" y1="23.885" y2="24.322" gradientUnits="userSpaceOnUse"><stop offset=".153" class="m1ddx1bps"/><stop offset="1" class="jm-srab5d"/></linearGradient><linearGradient id="iGDWZdd" x1="7.488" x2="7.488" y1="26.025" y2="25.791" gradientUnits="userSpaceOnUse"><stop class="ovhi2f9-q"/><stop offset="1" class="ia0lkkb3o"/></linearGradient><linearGradient id="iE7yE1d" x1="24.482" x2="24.256" y1="15.924" y2="16.369" gradientUnits="userSpaceOnUse"><stop class="mqemyz4up"/><stop offset="1" class="lthf7gbdk"/></linearGradient><linearGradient id="ijJpGfb" x1="12.978" x2="12.795" y1="12.025" y2="12.025" gradientUnits="userSpaceOnUse"><stop offset=".23" class="zz7609b3z"/><stop offset="1" class="vsn-9vbzx"/></linearGradient><linearGradient id="iBQm5Rd" x1="14.988" x2="17.988" y1="21.53" y2="21.53" gradientUnits="userSpaceOnUse"><stop class="phxlfrhwq"/><stop offset="1" class="blidzrzjx"/></linearGradient><linearGradient id="iOhsmrc" x1="17.988" x2="18.146" y1="16.713" y2="16.713" gradientUnits="userSpaceOnUse"><stop class="nhztq064q"/><stop offset="1" class="z5omlnbpz"/></linearGradient><linearGradient id="i62phQx" x1="18.951" x2="18.826" y1="17.119" y2="17.119" gradientUnits="userSpaceOnUse"><stop class="zqlmvdbxq"/><stop offset="1" class="p61y8yjpa"/></linearGradient><linearGradient id="i9kqjje" x1="22.988" x2="29.992" y1="26.503" y2="26.503" gradientUnits="userSpaceOnUse"><stop class="yzjmohqfk"/><stop offset="1" class="ut9kief7h"/></linearGradient><linearGradient id="ica9uzd" x1="25.234" x2="27.742" y1="26.503" y2="26.503" gradientUnits="userSpaceOnUse"><stop class="tl8mgb9om"/><stop offset="1" class="b8q6rac6p"/></linearGradient><linearGradient id="iryzpZb" x1="8.66" x2="8.66" y1="20.588" y2="22.713" gradientUnits="userSpaceOnUse"><stop class="qwzaymxpx"/><stop offset="1" class="mw2rblbad"/></linearGradient><linearGradient id="i2T1tTd" x1="8.66" x2="8.66" y1="23.4" y2="22.432" gradientUnits="userSpaceOnUse"><stop class="icz4b8h8z"/><stop offset="1" class="o2sh3ibul"/></linearGradient><linearGradient id="iKknA1d" x1="10.566" x2="9.16" y1="21.713" y2="21.713" gradientUnits="userSpaceOnUse"><stop class="i9hm-tbzd"/><stop offset="1" class="nzz3qbbwe"/></linearGradient><linearGradient id="iYUcNQd" x1="7.904" x2="10.342" y1="11.53" y2="11.53" gradientUnits="userSpaceOnUse"><stop class="w0azssy_d"/><stop offset="1" class="s7lc65b7y"/></linearGradient><linearGradient id="iZzJF2d" x1="11.373" x2="10.217" y1="12.244" y2="12.244" gradientUnits="userSpaceOnUse"><stop class="x8wnfgb4t"/><stop offset="1" class="wre9wh39u"/></linearGradient><filter id="iGzNQTd" width="1.2" height="11.344" x="17.888" y="7.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.592157 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.843137 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11343" result="effect2_innerShadow_18_11343"/></filter><filter id="iDrGyCc" width="22.85" height="13.35" x="6.228" y="5.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.976471 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11343" result="effect2_innerShadow_18_11343"/></filter><filter id="iF8q9fc" width="3.25" height="5.25" x="20.988" y="19.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0980392 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/></filter><filter id="iVS4wtc" width="7.404" height="7.204" x="3.702" y="22.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.113725 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.176471 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11343" result="effect2_innerShadow_18_11343"/></filter><filter id="i0DZpJd" width="2.908" height="2.908" x="5.85" y="25.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.0901961 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_11343"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_11343" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.356863 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_11343"/></filter><filter id="iIiCUuc" width="23.674" height="11.5" x="5.814" y="15.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.647059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.435294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11343" result="effect2_innerShadow_18_11343"/></filter><filter id="imwlvhv" width="4.886" height="8" x="21.587" y="16.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.419608 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/></filter><filter id="ilDjhZc" width="3.25" height="5.25" x="14.988" y="19.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0980392 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/></filter><filter id="ic2S3wd" width="7.404" height="7.404" x="22.786" y="22.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.0941176 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11343"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.0941176 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11343" result="effect2_innerShadow_18_11343"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.294118 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11343" result="effect3_innerShadow_18_11343"/></filter><filter id="idZ82zb" width="4.508" height="4.508" x="24.084" y="24.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.105882 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_11343"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_11343" result="shape"/></filter><radialGradient id="iZZmZrv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5625 0 0 -1.9 9.082 23.12)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="m1ddx1bps"/><stop offset="1" class="jm-srab5d"/></radialGradient><radialGradient id="iOpOynJ" cx="0" cy="0" r="1" gradientTransform="rotate(-131.607 10.091 11.106)scale(5.60039 6.33463)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="taicn02ea"/><stop offset="1" class="fii_gm0lk"/></radialGradient><radialGradient id="i4AbY6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .6953 -.6167 -.8315 8.982 22.549)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="ukr2ipjec"/><stop offset="1" class="retx5o2ls"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:auto-rickshaw" /></template>
<style>
.a7ptiibgp {
  fill: var(--svg-color--3b8676, #3B8676);
  d: path("M11.818 26.025c.09 0 .17-.08.17-.17a4.507 4.507 0 0 0-4.5-4.33a4.5 4.5 0 0 0-4.5 4.33c0 .09.07.17.17.17z");
}

.aq8l87b0o {
  d: path("M18.988 16.025h-1v8h1z");
}

.b8q6rac6p {
  stop-color: var(--svg-color--f2f2f2, #F2F2F2);
}

.blidzrzjx {
  stop-color: var(--svg-color--1f162d, #1F162D);
}

.c2asm9bob {
  fill: var(--svg-color--ee3124, #EE3124);
  d: path("M28.988 23.025c-.55 0-1-.45-1-1v-1.69c0-.17.14-.31.31-.31h.69z");
}

.coubj68aq {
  stop-color: var(--svg-color--0c0c32, #0C0C32);
}

.dw50o5llj {
  stop-color: var(--svg-color--90799f, #90799F);
}

.epot3ybtp {
  stop-color: var(--svg-color--ccae62, #CCAE62);
}

.ev95u638s {
  stop-color: var(--svg-color--ccae62, #CCAE62);
  stop-opacity: 0;
}

.f7-_s8byw {
  d: path("m9.658 8.025l-2.33 7h1.34c1.29 0 2.33-1.04 2.33-2.33v-4.67z");
}

.fii_gm0lk {
  stop-color: var(--svg-color--347a60, #347A60);
}

.ft5dv1b6b {
  fill: none;
}

.gk964dbzt {
  d: path("m26.373 24.025l-1.453-8h-.932v5.6a5.5 5.5 0 0 0-2.401 2.4z");
}

.h9xh5u5ux {
  fill: var(--svg-color--ffb521, #FFB521);
  d: path("M7.15 23.045v-3.01c-.55 0-1 .45-1 1v1.01c0 .55.45 1 1 1");
}

.hqp0jmb2e {
  d: path("M12.988 24.025v-8h-6l-.3.9c-.45 1.34-.34 2.81.29 4.08l2.503 5.017h.926l.47 1.003h18.111v-11h-5v5.6a5.5 5.5 0 0 0-2.401 2.4z");
}

.hxc4nnn7k {
  stop-color: var(--svg-color--0c0c32, #0C0C32);
  stop-opacity: 0;
}

.i9hm-tbzd {
  stop-color: var(--svg-color--67fca3, #67FCA3);
}

.ia0lkkb3o {
  stop-color: var(--svg-color--395268, #395268);
  stop-opacity: 0;
}

.icz4b8h8z {
  stop-color: var(--svg-color--316e65, #316E65);
}

.iwvo8ejep {
  d: path("M12.978 8.025h-3.33l-2.67 8h6z");
}

.j2006_2dc {
  fill: var(--svg-color--d0c5d4, #D0C5D4);
  d: path("M18.988 7.682h-1v11.343h1z");
}

.jm-srab5d {
  stop-color: var(--svg-color--265a52, #265A52);
  stop-opacity: 0;
}

.ko4gwiunp {
  d: path("M23.988 19.025h-1.53c-.81 0-1.47.66-1.47 1.47v3.53h3z");
}

.lthf7gbdk {
  stop-color: var(--svg-color--3d8f7a, #3D8F7A);
  stop-opacity: 0;
}

.m1ddx1bps {
  stop-color: var(--svg-color--265a52, #265A52);
}

.m9lq6qb6l {
  stop-color: var(--svg-color--322a58, #322A58);
}

.maumwhb8g {
  fill: var(--svg-color--3d8f7a, #3D8F7A);
  d: path("M12.988 24.025v-8h-6l-.3.9c-.45 1.34-.34 2.81.29 4.08l2.503 5.017h.926l.47 1.003h18.111v-11h-5v5.6a5.5 5.5 0 0 0-2.401 2.4z");
}

.mh2peudve {
  d: path("M7.404 30a3.502 3.502 0 1 0 0-7.004a3.502 3.502 0 0 0 0 7.004");
}

.mqemyz4up {
  stop-color: var(--svg-color--3d8f7a, #3D8F7A);
}

.ms89-obzj {
  d: path("M24.058 6.025H9.918c-1.15 0-2.18.74-2.54 1.83c-.03.08.03.17.12.17h2.15l-2.67 8h6v-8h11v11h5v-8.07c.01-2.72-2.2-4.93-4.92-4.93");
}

.mw2rblbad {
  stop-color: var(--svg-color--40a37c, #40A37C);
}

.nhztq064q {
  stop-color: var(--svg-color--306d56, #306D56);
}

.nzz3qbbwe {
  stop-color: var(--svg-color--67fca3, #67FCA3);
  stop-opacity: 0;
}

.o2sh3ibul {
  stop-color: var(--svg-color--316e65, #316E65);
  stop-opacity: 0;
}

.ovhi2f9-q {
  stop-color: var(--svg-color--395268, #395268);
}

.ozfzm9vsy {
  d: path("M26.488 27.752a1.254 1.254 0 1 0 0-2.508a1.254 1.254 0 0 0 0 2.508");
}

.p61y8yjpa {
  stop-color: var(--svg-color--479982, #479982);
  stop-opacity: 0;
}

.pdr15mbgs {
  stop-color: var(--svg-color--655774, #655774);
}

.phxlfrhwq {
  stop-color: var(--svg-color--382452, #382452);
}

.plomc0ecs {
  d: path("M7.404 27.752a1.254 1.254 0 1 0 0-2.508a1.254 1.254 0 0 0 0 2.508");
}

.pmilfnron {
  fill: var(--svg-color--fac947, #FAC947);
  d: path("M12.978 8.025h-3.33l-2.67 8h6z");
}

.qwzaymxpx {
  stop-color: var(--svg-color--5bea97, #5BEA97);
}

.r3kwxz3cz {
  fill: var(--svg-color--f6c547, #F6C547);
  d: path("M24.058 6.025H9.918c-1.15 0-2.18.74-2.54 1.83c-.03.08.03.17.12.17h2.15l-2.67 8h6v-8h11v11h5v-8.07c.01-2.72-2.2-4.93-4.92-4.93");
}

.retx5o2ls {
  stop-color: var(--svg-color--275353, #275353);
  stop-opacity: 0;
}

.romknsu6g {
  d: path("M26.488 30a3.502 3.502 0 1 0 0-7.004a3.502 3.502 0 0 0 0 7.004");
}

.s7lc65b7y {
  stop-color: var(--svg-color--3e9ddd, #3E9DDD);
}

.snvfy8-ue {
  d: path("M17.988 19.025h-1.53c-.81 0-1.47.66-1.47 1.47v3.53h3z");
}

.taicn02ea {
  stop-color: var(--svg-color--347a60, #347A60);
  stop-opacity: 0;
}

.tl8mgb9om {
  stop-color: var(--svg-color--d8d8d8, #D8D8D8);
}

.u2q6f-7-k {
  d: path("M8.66 23.045H7.15v-3.01h1.51c.83 0 1.51.67 1.51 1.51c-.01.82-.68 1.5-1.51 1.5");
}

.u7svee36f {
  stop-color: var(--svg-color--1e1b3d, #1E1B3D);
}

.ukr2ipjec {
  stop-color: var(--svg-color--275353, #275353);
}

.ut9kief7h {
  stop-color: var(--svg-color--2a2453, #2A2453);
}

.vsn-9vbzx {
  stop-color: var(--svg-color--fd5, #FD5);
  stop-opacity: 0;
}

.w0azssy_d {
  stop-color: var(--svg-color--4ed1fd, #4ED1FD);
}

.wre9wh39u {
  stop-color: var(--svg-color--4fb7e7, #4FB7E7);
  stop-opacity: 0;
}

.x8wnfgb4t {
  stop-color: var(--svg-color--4fb7e7, #4FB7E7);
}

.y-z_56bqr {
  fill: var(--svg-color--3d8f7a, #3D8F7A);
  d: path("m26.373 24.025l-1.453-8h-.932v5.6a5.5 5.5 0 0 0-2.401 2.4z");
}

.yzjmohqfk {
  stop-color: var(--svg-color--421d46, #421D46);
}

.z5omlnbpz {
  stop-color: var(--svg-color--306d56, #306D56);
  stop-opacity: 0;
}

.zir617bwz {
  d: path("M11.818 26.025c.09 0 .17-.08.17-.17a4.507 4.507 0 0 0-4.5-4.33a4.5 4.5 0 0 0-4.5 4.33c0 .09.07.17.17.17z");
}

.zqlmvdbxq {
  stop-color: var(--svg-color--479982, #479982);
}

.ztc8i-b_a {
  fill: var(--svg-color--3d8f7a, #3D8F7A);
  d: path("M18.988 16.025h-1v8h1z");
}

.zz7609b3z {
  stop-color: var(--svg-color--fd5, #FD5);
}

</style>
