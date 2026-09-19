<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iC8aDLb)"><path fill="url(#iwY5KYb)" class="upejyjh5k"/><path fill="url(#iypE27c)" class="upejyjh5k"/><path fill="url(#i9h60Zb)" class="upejyjh5k"/></g><g filter="url(#iM3e3mb)"><path fill="url(#ircrVMr)" class="fs2y-hbgv"/></g><g filter="url(#iOi9kBc)"><rect fill="url(#ipldB4c)" transform="rotate(30 16.417 1.961)" class="r9fp8pb9z"/><rect fill="url(#ioicxEd)" transform="rotate(30 16.417 1.961)" class="r9fp8pb9z"/></g><g filter="url(#iaQzQ3m)"><rect fill="url(#irlYTDe)" transform="rotate(32.721 17.567 9.564)" class="djuruobvj"/><rect fill="url(#iB8vW8b)" transform="rotate(32.721 17.567 9.564)" class="djuruobvj"/></g><g filter="url(#iJUkybd)"><rect fill="url(#icvLm3b)" transform="rotate(32.721 21.042 12.924)" class="x0l52acyv"/><rect fill="url(#iSxTkle)" transform="rotate(32.721 21.042 12.924)" class="x0l52acyv"/></g><g filter="url(#iBju9ke)"><rect fill="url(#ibSJLce)" transform="rotate(34.472 23.802 16.531)" class="w9o3v0fbd"/><rect fill="url(#imsOtSb)" transform="rotate(34.472 23.802 16.531)" class="w9o3v0fbd"/></g><g filter="url(#i98AYJE)"><ellipse transform="rotate(36.17 15 12.444)" class="gosnnoe_j"/><path class="dmzck0b_y"/></g><g filter="url(#iaeapdb)"><ellipse transform="rotate(36.17 18.953 15.605)" class="okyh9_ljd"/><path class="unr9zmczt"/></g><g filter="url(#icwFEwc)"><ellipse transform="rotate(36.17 21.967 18.59)" class="tprkdfb_k"/><path class="ihla_dbyx"/></g><defs><filter id="iC8aDLb" width="6.149" height="8.616" x="8.341" y="1.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.509804 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2433"/></filter><filter id="iM3e3mb" width="22.325" height="28.931" x="4.85" y="1.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.533333 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2433"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.4 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2433" result="effect2_innerShadow_20020_2433"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.615686 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_2433" result="effect3_innerShadow_20020_2433"/></filter><filter id="iOi9kBc" width="13.056" height="17.785" x="7.318" y="1.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".75"/></filter><filter id="iaQzQ3m" width="10.27" height="12.135" x="11.345" y="8.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".75"/></filter><filter id="iJUkybd" width="10.45" height="12.415" x="14.64" y="12.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".75"/></filter><filter id="iBju9ke" width="10.445" height="12.056" x="17.322" y="15.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".75"/></filter><filter id="i98AYJE" width="4.824" height="5.998" x="12.588" y="9.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".2"/></filter><filter id="iaeapdb" width="4.148" height="5.069" x="16.879" y="13.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".2"/></filter><filter id="icwFEwc" width="3.659" height="4.396" x="20.138" y="16.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2433" stdDeviation=".2"/></filter><radialGradient id="iwY5KYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.94364 4.44518 -4.2145 -.89467 12.284 2.887)" gradientUnits="userSpaceOnUse"><stop class="kq6wgq_9c"/><stop offset="1" class="u0f86tyks"/></radialGradient><radialGradient id="iypE27c" cx="0" cy="0" r="1" gradientTransform="rotate(-104.25 9.135 -1.741)scale(3.00976 1.77464)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="mq0dzuwjb"/><stop offset="1" class="dxybhqb0e"/></radialGradient><radialGradient id="i9h60Zb" cx="0" cy="0" r="1" gradientTransform="matrix(.59053 2.00963 -2.74222 .8058 9.317 1.752)" gradientUnits="userSpaceOnUse"><stop class="z_tmzxw3w"/><stop offset="1" class="f_r4njbqy"/></radialGradient><radialGradient id="ircrVMr" cx="0" cy="0" r="1" gradientTransform="rotate(90.82 5.983 10.708)scale(22.645 22.0007)" gradientUnits="userSpaceOnUse"><stop class="zcvozy17t"/><stop offset="1" class="rapy9812w"/></radialGradient><radialGradient id="ioicxEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.44964 -2.10905 1.82442 1.254 19.006 3.046)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="yx6sqwlyl"/><stop offset="1" class="e20ffpbsa"/></radialGradient><radialGradient id="iB8vW8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.67938 -2.19689 -.1482 20.552 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="yljy11gdw"/><stop offset="1" class="xl8k_ojmj"/></radialGradient><radialGradient id="iSxTkle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.83338 -2.1975 -.14352 24.027 13.573)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="yljy11gdw"/><stop offset="1" class="xl8k_ojmj"/></radialGradient><radialGradient id="imsOtSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.31567 4.69397 -2.19695 -.14774 26.788 17.161)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="yljy11gdw"/><stop offset="1" class="xl8k_ojmj"/></radialGradient><linearGradient id="ipldB4c" x1="18.386" x2="17.699" y1="6.599" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="m-e9fjbtd"/><stop offset="1" class="b5qrwwbow"/></linearGradient><linearGradient id="irlYTDe" x1="19.71" x2="19.473" y1="12.405" y2="19.06" gradientUnits="userSpaceOnUse"><stop class="km_3m2b8k"/><stop offset="1" class="dp713w6rh"/></linearGradient><linearGradient id="icvLm3b" x1="23.185" x2="22.932" y1="15.859" y2="22.733" gradientUnits="userSpaceOnUse"><stop class="km_3m2b8k"/><stop offset="1" class="dp713w6rh"/></linearGradient><linearGradient id="ibSJLce" x1="25.946" x2="25.707" y1="19.381" y2="26.057" gradientUnits="userSpaceOnUse"><stop class="km_3m2b8k"/><stop offset="1" class="dp713w6rh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-index-finger-and-thumb-crossed-medium" /></template>
<style>
.b5qrwwbow {
  stop-color: var(--svg-color--ba8484, #BA8484);
  stop-opacity: 0;
}

.djuruobvj {
  width: 3.917px;
  height: 10.119px;
  x: 17.567px;
  y: 9.564px;
  rx: 1.958px;
}

.dmzck0b_y {
  stroke: var(--svg-color--a47766, #A47766);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.276 14.802c.093.068.19.033.213.024a.4.4 0 0 0 .085-.048q.066-.05.144-.128c.105-.105.242-.26.402-.45c.32-.383.74-.924 1.185-1.533s.834-1.174 1.101-1.595c.133-.21.24-.388.307-.52q.052-.097.079-.176a.4.4 0 0 0 .02-.095a.22.22 0 0 0-.088-.195a.22.22 0 0 0-.213-.025a.4.4 0 0 0-.085.048a1.3 1.3 0 0 0-.144.129c-.105.104-.242.26-.402.45c-.32.383-.74.923-1.185 1.532a31 31 0 0 0-1.101 1.595a7 7 0 0 0-.307.52a1.3 1.3 0 0 0-.079.176a.4.4 0 0 0-.02.095a.22.22 0 0 0 .088.196Z");
}

.dp713w6rh {
  stop-color: var(--svg-color--bc8684, #BC8684);
  stop-opacity: 0;
}

.dxybhqb0e {
  stop-color: var(--svg-color--967260, #967260);
  stop-opacity: 0;
}

.e20ffpbsa {
  stop-color: var(--svg-color--cda48d, #CDA48D);
  stop-opacity: 0;
}

.f_r4njbqy {
  stop-color: var(--svg-color--93755e, #93755E);
  stop-opacity: 0;
}

.fs2y-hbgv {
  d: path("M14.559 3.125c.783-1.29 2.514-1.844 3.803-1.062c1.29.783 1.7 2.463.918 3.752l-2.252 3.71a2.788 2.788 0 0 1 3.69 3.197a2.842 2.842 0 0 1 3.234 3.46a2.8 2.8 0 0 1 1.642.52c1.313.813 1.75 2.891.874 4.46l-2.963 4.33l-.024.037c-4.379 6.766-11.875 4.262-16.309-.983c-3-3.975-1.656-7.218-.484-9.039l4.41-6.742z");
}

.ft5dv1b6b {
  fill: none;
}

.gosnnoe_j {
  cx: 15px;
  cy: 12.444px;
  fill: var(--svg-color--774c41, #774C41);
  rx: 0.178px;
  ry: 2.721px;
}

.ihla_dbyx {
  stroke: var(--svg-color--a47664, #A47664);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.83 20.146a.23.23 0 0 0 .167.04a.3.3 0 0 0 .091-.03a.7.7 0 0 0 .125-.087c.079-.066.176-.165.284-.284c.216-.24.491-.582.775-.97c.285-.39.527-.756.69-1.035c.081-.138.146-.26.185-.356a.7.7 0 0 0 .045-.145a.3.3 0 0 0 .001-.097a.23.23 0 0 0-.089-.147a.23.23 0 0 0-.167-.04a.3.3 0 0 0-.091.03a.7.7 0 0 0-.125.087a3 3 0 0 0-.284.285c-.216.24-.491.582-.775.97c-.285.39-.527.755-.69 1.034a3 3 0 0 0-.185.357a.7.7 0 0 0-.045.145a.3.3 0 0 0-.001.096c.006.04.027.102.089.147Z");
}

.km_3m2b8k {
  stop-color: var(--svg-color--bc8684, #BC8684);
}

.kq6wgq_9c {
  stop-color: var(--svg-color--c29c7d, #C29C7D);
}

.m-e9fjbtd {
  stop-color: var(--svg-color--ba8484, #BA8484);
}

.mq0dzuwjb {
  stop-color: var(--svg-color--7d5b45, #7D5B45);
}

.okyh9_ljd {
  cx: 18.953px;
  cy: 15.605px;
  fill: var(--svg-color--916352, #916352);
  rx: 0.178px;
  ry: 2.145px;
}

.r9fp8pb9z {
  width: 3.597px;
  height: 16.515px;
  x: 16.417px;
  y: 1.961px;
  rx: 1.799px;
}

.rapy9812w {
  stop-color: var(--svg-color--af7680, #AF7680);
}

.tprkdfb_k {
  cx: 21.967px;
  cy: 18.591px;
  fill: var(--svg-color--916352, #916352);
  rx: 0.178px;
  ry: 1.727px;
}

.u0f86tyks {
  stop-color: var(--svg-color--a9816e, #A9816E);
}

.unr9zmczt {
  stroke: var(--svg-color--a47664, #A47664);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.57 17.497a.22.22 0 0 0 .189.034a.3.3 0 0 0 .088-.039a1 1 0 0 0 .132-.104a5 5 0 0 0 .332-.354c.26-.3.596-.725.948-1.206c.351-.481.655-.93.862-1.269c.102-.168.184-.314.236-.424a1 1 0 0 0 .06-.157a.3.3 0 0 0 .01-.096a.22.22 0 0 0-.09-.17a.22.22 0 0 0-.19-.034a.3.3 0 0 0-.088.04a1 1 0 0 0-.131.104c-.09.082-.204.204-.333.353c-.26.3-.595.725-.947 1.206s-.655.93-.862 1.27a5 5 0 0 0-.236.423a1 1 0 0 0-.06.157a.3.3 0 0 0-.01.096a.22.22 0 0 0 .09.17Z");
}

.upejyjh5k {
  d: path("M9.723 7.125c.4 1.075.75 2.53.797 3.093l3.82-5.578c-.875-1.922-2.085-2.746-3.164-2.867c-1.25-.14-2.398.422-2.797 1.766c-.258 1.383.844 2.242 1.344 3.586");
}

.w9o3v0fbd {
  width: 3.917px;
  height: 10.15px;
  x: 23.802px;
  y: 16.531px;
  rx: 1.958px;
}

.x0l52acyv {
  width: 3.917px;
  height: 10.452px;
  x: 21.042px;
  y: 12.924px;
  rx: 1.958px;
}

.xl8k_ojmj {
  stop-color: var(--svg-color--d3a990, #D3A990);
  stop-opacity: 0;
}

.yljy11gdw {
  stop-color: var(--svg-color--d3a990, #D3A990);
}

.yx6sqwlyl {
  stop-color: var(--svg-color--cda48d, #CDA48D);
}

.z_tmzxw3w {
  stop-color: var(--svg-color--93755e, #93755E);
}

.zcvozy17t {
  stop-color: var(--svg-color--b99275, #B99275);
}

</style>
