<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isGKhPc)" class="caio2cbjk"/><path fill="url(#i0Fvovd)" class="caio2cbjk"/><path fill="url(#iSRBmTc)" class="caio2cbjk"/><path fill="url(#i35J9ye)" class="caio2cbjk"/><path fill="url(#iZTBgce)" class="caio2cbjk"/><path fill="url(#iKvCTlH)" class="caio2cbjk"/><path fill="url(#iBsS7vb)" class="caio2cbjk"/><path fill="url(#iMJ1Nac)" class="caio2cbjk"/><path fill="url(#iFuized)" class="fyqk7jbxh"/><g filter="url(#iOxhMqc)"><path class="px3ddbb7h"/></g><g filter="url(#iFuOlDd)"><ellipse fill="url(#iCzm8Jb)" transform="rotate(-67.627 22.951 14.119)" class="xl4ycjb9i"/></g><g filter="url(#io8GWZn)"><path fill="url(#iUy7M7b)" class="szdm6y8cq"/></g><g filter="url(#iOpp08c)"><path stroke="url(#ihdoCid)" class="k52_mrb5b"/></g><g filter="url(#if9tADb)"><path class="ltm9e3rrh"/></g><defs><radialGradient id="isGKhPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 25.0559 -26.6012 0 15.77 5.66)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="gdymwj-yh"/><stop offset=".528" class="a8ug5dyvt"/><stop offset="1" class="ivp0rczth"/></radialGradient><radialGradient id="i0Fvovd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.293 33.306 3.678)scale(30.305 28.3828)" gradientUnits="userSpaceOnUse"><stop offset=".801" class="pti8wytqe"/><stop offset="1" class="t6j-hd24l"/></radialGradient><radialGradient id="i35J9ye" cx="0" cy="0" r="1" gradientTransform="matrix(0 26.6875 -33.0073 0 15.895 6.09)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="ekbezxbgs"/><stop offset=".979" class="ips0xyi5b"/></radialGradient><radialGradient id="iZTBgce" cx="0" cy="0" r="1" gradientTransform="matrix(-14.93746 11.4375 -16.3734 -21.38378 20.563 13.144)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="ekbezxbgs"/><stop offset="1" class="ips0xyi5b"/></radialGradient><radialGradient id="iBsS7vb" cx="0" cy="0" r="1" gradientTransform="rotate(-125.423 16.881 8.837)scale(31.5334 31.9949)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="ekbezxbgs"/><stop offset="1" class="ips0xyi5b"/></radialGradient><radialGradient id="iMJ1Nac" cx="0" cy="0" r="1" gradientTransform="scale(20.0528 17.499)rotate(90 -.01 .78)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="max-rhuny"/><stop offset=".934" class="d1f6q0uqp"/></radialGradient><radialGradient id="iCzm8Jb" cx="0" cy="0" r="1" gradientTransform="rotate(-173.542 16.852 6.761)scale(15.5528 7.3671)" gradientUnits="userSpaceOnUse"><stop class="ofhpa1bkc"/><stop offset="1" class="aiizt-b9r"/></radialGradient><radialGradient id="iUy7M7b" cx="0" cy="0" r="1" gradientTransform="rotate(-151.049 9.763 5.023)scale(8.77992 11.2827)" gradientUnits="userSpaceOnUse"><stop class="ofhpa1bkc"/><stop offset="1" class="aiizt-b9r"/></radialGradient><filter id="iOxhMqc" width="8.705" height="13.065" x="13.795" y="7.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6102" stdDeviation="1"/></filter><filter id="iFuOlDd" width="14.114" height="17.881" x="15.894" y="5.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6102" stdDeviation=".75"/></filter><filter id="io8GWZn" width="12.852" height="19.47" x="5.192" y="3.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6102" stdDeviation="1.5"/></filter><filter id="iOpp08c" width="8.649" height="5.715" x="7.316" y="5.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6102" stdDeviation=".5"/></filter><filter id="if9tADb" width="9.938" height="11.625" x="14.813" y="4.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6102" stdDeviation="1"/></filter><linearGradient id="iSRBmTc" x1="17.632" x2="25.645" y1="16.159" y2="25.694" gradientUnits="userSpaceOnUse"><stop offset=".694" class="wqge7ob_z"/><stop offset=".934" class="qa0xd3bfv"/></linearGradient><linearGradient id="iKvCTlH" x1="16.639" x2="7.188" y1="16.556" y2="27.206" gradientUnits="userSpaceOnUse"><stop offset=".694" class="max-rhuny"/><stop offset=".885" class="d1f6q0uqp"/></linearGradient><linearGradient id="iFuized" x1="17.125" x2="18.887" y1="7.445" y2="8.863" gradientUnits="userSpaceOnUse"><stop class="xrw8af6mm"/><stop offset=".68" class="eugh46bic"/></linearGradient><linearGradient id="ihdoCid" x1="13.069" x2="10.415" y1="8.182" y2="6.844" gradientUnits="userSpaceOnUse"><stop class="ofhpa1bkc"/><stop offset="1" class="st9ubksrd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:blue-heart" /></template>
<style>
.a8ug5dyvt {
  stop-color: var(--svg-color--396dff, #396DFF);
}

.aiizt-b9r {
  stop-color: var(--svg-color--7d9aff, #7D9AFF);
  stop-opacity: 0;
}

.caio2cbjk {
  d: path("M15.104 29.227a1.73 1.73 0 0 0 1.71-.022c3.584-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.024-1.897 1.542c-.238.234-.657.258-.904.033c-.69-.628-1.771-1.435-2.465-1.904c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.11 12.475");
}

.d1f6q0uqp {
  stop-color: var(--svg-color--b694ff, #B694FF);
}

.ekbezxbgs {
  stop-color: var(--svg-color--3156be, #3156BE);
  stop-opacity: 0;
}

.eugh46bic {
  stop-color: var(--svg-color--4a65ad, #4A65AD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyqk7jbxh {
  d: path("m15.219 7.832l.347.318c.954.873 2.499.63 3.365-.33c.913-1.014 2.14-2.064 3.624-2.792c-1.403.03-2.841.507-4.148 1.534l-.475.367c-.497.38-1.027.785-1.422 1.174c-.238.234-.657.258-.904.034q-.18-.164-.389-.34z");
}

.gdymwj-yh {
  stop-color: var(--svg-color--2a7bf7, #2A7BF7);
}

.ips0xyi5b {
  stop-color: var(--svg-color--3156be, #3156BE);
}

.ivp0rczth {
  stop-color: var(--svg-color--4a69ff, #4A69FF);
}

.k52_mrb5b {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.44 6.44c1.087-.136 4.025 0 6.4 3.432");
}

.ltm9e3rrh {
  stroke: var(--svg-color--266ff9, #266FF9);
  stroke-linecap: round;
  d: path("M22.25 6.644c-1.27.48-4.788 2.875-4.937 6.625");
}

.max-rhuny {
  stop-color: var(--svg-color--9f72ff, #9F72FF);
  stop-opacity: 0;
}

.ofhpa1bkc {
  stop-color: var(--svg-color--94b9fc, #94B9FC);
}

.pti8wytqe {
  stop-color: var(--svg-color--91b3f7, #91B3F7);
  stop-opacity: 0;
}

.px3ddbb7h {
  fill: var(--svg-color--266ff9, #266FF9);
  d: path("M15.795 10.438v7.224c0 .866 1.02 1.317 1.627.7c2.251-2.295 4.253-5.19 2.261-7.53c-.734-.862-2.152-1.41-3.293-1.209c-.377.066-.595.432-.595.815");
}

.qa0xd3bfv {
  stop-color: var(--svg-color--9f72ff, #9F72FF);
}

.st9ubksrd {
  stop-color: var(--svg-color--94b9fc, #94B9FC);
  stop-opacity: 0;
}

.szdm6y8cq {
  d: path("m14.84 9.207l.205 11.031C8.17 13.551 6.939 8.76 9.277 7.153c1.67-1.147 4.813.491 5.563 2.054");
}

.t6j-hd24l {
  stop-color: var(--svg-color--91b3f7, #91B3F7);
}

.wqge7ob_z {
  stop-color: var(--svg-color--b694ff, #B694FF);
  stop-opacity: 0;
}

.xl4ycjb9i {
  cx: 22.951px;
  cy: 14.119px;
  rx: 7.767px;
  ry: 5.087px;
}

.xrw8af6mm {
  stop-color: var(--svg-color--4a65ad, #4A65AD);
}

</style>
