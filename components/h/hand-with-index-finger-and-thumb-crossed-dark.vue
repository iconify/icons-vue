<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ims70Ub)"><path fill="url(#ixpPBbe)" class="ktpq_-bdw"/><path fill="url(#iwGnVbe)" class="ktpq_-bdw"/></g><g filter="url(#iQ2hOSb)"><path fill="url(#iVWjy3S)" class="b-b1bb04h"/></g><g filter="url(#iiLSz7c)"><rect fill="url(#if5i4Yc)" transform="rotate(30 16.28 2.241)" class="wo5xxsbel"/><rect fill="url(#iUFsS5b)" transform="rotate(30 16.28 2.241)" class="wo5xxsbel"/></g><g filter="url(#ifOn3ad)"><rect fill="url(#i81tBfe)" transform="rotate(32.721 17.43 9.844)" class="h5w-8hsom"/><rect fill="url(#iuKZOil)" transform="rotate(32.721 17.43 9.844)" class="h5w-8hsom"/></g><g filter="url(#iEdY2qe)"><rect fill="url(#i5UZQPd)" transform="rotate(32.721 20.905 13.204)" class="setwy-dli"/><rect fill="url(#ibyPOOb)" transform="rotate(32.721 20.905 13.204)" class="setwy-dli"/></g><g filter="url(#itjC2jd)"><rect fill="url(#ihQQMJb)" transform="rotate(34.472 23.665 16.811)" class="g38nzwbwu"/><rect fill="url(#i4tn0QJ)" transform="rotate(34.472 23.665 16.811)" class="g38nzwbwu"/></g><g filter="url(#ieprZ2w)"><ellipse transform="rotate(36.17 14.863 12.724)" class="avj1q6uvz"/><path class="l7kmu0aot"/></g><g filter="url(#iAblTjb)"><ellipse transform="rotate(36.17 18.816 15.885)" class="r7gp7acmp"/><path class="ev7r3_odh"/></g><g filter="url(#imMk6Sq)"><ellipse transform="rotate(36.17 21.83 18.87)" class="f-_e85b4m"/><path class="w9crnkazp"/></g><defs><filter id="ims70Ub" width="6.149" height="8.616" x="8.204" y="1.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2429"/></filter><filter id="iQ2hOSb" width="22.325" height="28.931" x="4.713" y="1.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.27451 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2429"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.223529 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2429" result="effect2_innerShadow_20020_2429"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.262745 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_2429" result="effect3_innerShadow_20020_2429"/></filter><filter id="iiLSz7c" width="13.056" height="17.785" x="7.181" y="1.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".75"/></filter><filter id="ifOn3ad" width="10.27" height="12.135" x="11.207" y="9.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".75"/></filter><filter id="iEdY2qe" width="10.45" height="12.415" x="14.503" y="12.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".75"/></filter><filter id="itjC2jd" width="10.445" height="12.056" x="17.185" y="16.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".75"/></filter><filter id="ieprZ2w" width="4.824" height="5.998" x="12.451" y="9.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".2"/></filter><filter id="iAblTjb" width="4.148" height="5.069" x="16.742" y="13.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".2"/></filter><filter id="imMk6Sq" width="3.659" height="4.396" x="20.001" y="16.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2429" stdDeviation=".2"/></filter><radialGradient id="ixpPBbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.94364 4.44518 -4.2145 -.89467 12.147 3.167)" gradientUnits="userSpaceOnUse"><stop class="snmgrb76n"/><stop offset="1" class="vrfddebzm"/></radialGradient><radialGradient id="iwGnVbe" cx="0" cy="0" r="1" gradientTransform="rotate(-104.25 9.175 -1.548)scale(3.00976 1.77464)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="sav6-4bls"/><stop offset="1" class="y6hjgiviw"/></radialGradient><radialGradient id="iVWjy3S" cx="0" cy="0" r="1" gradientTransform="rotate(90.82 5.777 10.78)scale(22.645 22.0007)" gradientUnits="userSpaceOnUse"><stop class="c71-m6g0g"/><stop offset="1" class="m8m6rbexh"/></radialGradient><radialGradient id="iUFsS5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.38728 3.83665 -2.33702 -.2359 19.022 3.266)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="iuKZOil" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.67938 -2.19689 -.1482 20.415 10.472)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="ibyPOOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.83338 -2.1975 -.14352 23.89 13.853)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="i4tn0QJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.31567 4.69397 -2.19695 -.14774 26.65 17.441)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><linearGradient id="if5i4Yc" x1="18.249" x2="17.562" y1="6.878" y2="17.71" gradientUnits="userSpaceOnUse"><stop class="rx8x883-a"/><stop offset="1" class="qqhuevwyh"/></linearGradient><linearGradient id="i81tBfe" x1="19.573" x2="19.336" y1="12.685" y2="19.34" gradientUnits="userSpaceOnUse"><stop class="rx8x883-a"/><stop offset="1" class="qqhuevwyh"/></linearGradient><linearGradient id="i5UZQPd" x1="23.048" x2="22.795" y1="16.139" y2="23.012" gradientUnits="userSpaceOnUse"><stop class="rx8x883-a"/><stop offset="1" class="qqhuevwyh"/></linearGradient><linearGradient id="ihQQMJb" x1="25.809" x2="25.57" y1="19.661" y2="26.337" gradientUnits="userSpaceOnUse"><stop class="rx8x883-a"/><stop offset="1" class="qqhuevwyh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-index-finger-and-thumb-crossed-dark" /></template>
<style>
.avj1q6uvz {
  cx: 14.863px;
  cy: 12.724px;
  fill: var(--svg-color--1c0e0d, #1C0E0D);
  rx: 0.178px;
  ry: 2.721px;
}

.b-b1bb04h {
  d: path("M14.422 3.405c.783-1.29 2.514-1.844 3.803-1.062c1.29.783 1.7 2.463.918 3.752l-2.252 3.71a2.788 2.788 0 0 1 3.69 3.197a2.842 2.842 0 0 1 3.234 3.46a2.8 2.8 0 0 1 1.642.52c1.313.813 1.75 2.891.874 4.46l-2.963 4.33l-.024.036c-4.379 6.767-11.875 4.263-16.309-.982c-3-3.975-1.656-7.218-.484-9.039l4.41-6.742z");
}

.c71-m6g0g {
  stop-color: var(--svg-color--513537, #513537);
}

.ev7r3_odh {
  stroke: var(--svg-color--452d2b, #452D2B);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.433 17.777a.22.22 0 0 0 .189.034a.3.3 0 0 0 .088-.039a1 1 0 0 0 .132-.104c.09-.083.203-.205.332-.354c.26-.3.596-.725.948-1.206c.351-.481.655-.93.862-1.269c.102-.168.184-.314.236-.424a1 1 0 0 0 .06-.157a.3.3 0 0 0 .01-.096a.22.22 0 0 0-.09-.17a.22.22 0 0 0-.19-.034a.3.3 0 0 0-.088.04a1 1 0 0 0-.131.104c-.09.082-.204.204-.333.353c-.26.3-.595.725-.947 1.206s-.656.93-.862 1.27a5 5 0 0 0-.236.423a1 1 0 0 0-.06.157a.3.3 0 0 0-.01.096a.22.22 0 0 0 .09.17Z");
}

.f-_e85b4m {
  cx: 21.83px;
  cy: 18.871px;
  fill: var(--svg-color--37201e, #37201E);
  rx: 0.178px;
  ry: 1.727px;
}

.ft5dv1b6b {
  fill: none;
}

.g38nzwbwu {
  width: 3.917px;
  height: 10.15px;
  x: 23.665px;
  y: 16.811px;
  rx: 1.958px;
}

.h5w-8hsom {
  width: 3.917px;
  height: 10.119px;
  x: 17.429px;
  y: 9.844px;
  rx: 1.958px;
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.ktpq_-bdw {
  d: path("M9.586 7.405c.4 1.075.75 2.53.797 3.093l3.82-5.578c-.875-1.922-2.085-2.746-3.164-2.867c-1.25-.14-2.398.422-2.797 1.766c-.258 1.382.844 2.242 1.344 3.586");
}

.l7kmu0aot {
  stroke: var(--svg-color--412724, #412724);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.14 15.081a.22.22 0 0 0 .212.025a.4.4 0 0 0 .085-.048c.043-.031.093-.077.144-.128a7 7 0 0 0 .402-.45c.32-.383.74-.924 1.185-1.533s.834-1.173 1.101-1.595c.133-.21.24-.388.307-.52q.052-.098.079-.176a.4.4 0 0 0 .02-.095a.22.22 0 0 0-.088-.195a.22.22 0 0 0-.213-.025a.4.4 0 0 0-.085.048a1.3 1.3 0 0 0-.144.129a7 7 0 0 0-.402.45c-.32.383-.74.924-1.186 1.532a31 31 0 0 0-1.1 1.595c-.133.21-.24.388-.307.52a1.3 1.3 0 0 0-.079.176a.4.4 0 0 0-.02.095a.22.22 0 0 0 .088.195Z");
}

.m8m6rbexh {
  stop-color: var(--svg-color--472a36, #472A36);
}

.qqhuevwyh {
  stop-color: var(--svg-color--50333a, #50333A);
  stop-opacity: 0;
}

.r7gp7acmp {
  cx: 18.816px;
  cy: 15.885px;
  fill: var(--svg-color--37201e, #37201E);
  rx: 0.178px;
  ry: 2.145px;
}

.rx8x883-a {
  stop-color: var(--svg-color--50333a, #50333A);
}

.sav6-4bls {
  stop-color: var(--svg-color--2d1b18, #2D1B18);
}

.setwy-dli {
  width: 3.917px;
  height: 10.452px;
  x: 20.905px;
  y: 13.204px;
  rx: 1.958px;
}

.snmgrb76n {
  stop-color: var(--svg-color--5a4441, #5A4441);
}

.vrfddebzm {
  stop-color: var(--svg-color--47302e, #47302E);
}

.w9crnkazp {
  stroke: var(--svg-color--452d2b, #452D2B);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.693 20.426a.23.23 0 0 0 .167.04a.3.3 0 0 0 .091-.03a.7.7 0 0 0 .125-.087c.079-.066.176-.165.284-.284c.216-.24.491-.582.775-.97c.285-.39.527-.756.69-1.035c.081-.138.145-.26.185-.356a.7.7 0 0 0 .045-.145a.3.3 0 0 0 .001-.097a.23.23 0 0 0-.089-.147a.23.23 0 0 0-.167-.04a.3.3 0 0 0-.091.03a.7.7 0 0 0-.125.087a3 3 0 0 0-.284.285c-.216.24-.491.582-.775.97a13 13 0 0 0-.69 1.034a3 3 0 0 0-.185.357a.7.7 0 0 0-.045.145a.3.3 0 0 0-.001.096c.006.04.027.102.089.147Z");
}

.wo5xxsbel {
  width: 3.597px;
  height: 16.515px;
  x: 16.28px;
  y: 2.241px;
  rx: 1.799px;
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.y6hjgiviw {
  stop-color: var(--svg-color--453030, #453030);
  stop-opacity: 0;
}

</style>
