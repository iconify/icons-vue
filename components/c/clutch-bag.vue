<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKbS0sb)"><path fill="url(#ibgCm5H)" clip-rule="evenodd" class="ltsrxdbio"/><path fill="url(#ioVfJ6c)" clip-rule="evenodd" class="ltsrxdbio"/></g><g filter="url(#iQM6QDe)"><path fill="url(#i3hPFZd)" class="j9klqccxm"/><path fill="url(#iF38Tjc)" class="j9klqccxm"/></g><g filter="url(#iMFYMpd)"><path fill="url(#iE02Edd)" class="jkmk6johg"/><path fill="url(#i19r18w)" class="jkmk6johg"/></g><path fill="url(#inZs3Je)" class="jkmk6johg"/><path fill="url(#iaJFlkd)" class="jkmk6johg"/><g filter="url(#ics6mGd)"><rect fill="url(#iKGIyEc)" transform="rotate(-7.131 24.623 12.051)" class="uy0-01bsy"/><rect fill="url(#iv76qcc)" transform="rotate(-7.131 24.623 12.051)" class="uy0-01bsy"/></g><defs><linearGradient id="ibgCm5H" x1="5.796" x2="3.358" y1="10.594" y2="7.656" gradientUnits="userSpaceOnUse"><stop class="hhhm45baq"/><stop offset="1" class="jtw8ysxll"/></linearGradient><linearGradient id="i3hPFZd" x1="16" x2="16" y1="9.605" y2="16.313" gradientUnits="userSpaceOnUse"><stop offset=".214" class="yv1h-kp6e"/><stop offset="1" class="j6moi1_8m"/></linearGradient><linearGradient id="iF38Tjc" x1="2.265" x2="7.015" y1="20.25" y2="20.75" gradientUnits="userSpaceOnUse"><stop offset=".201" class="p7apxebux"/><stop offset="1" class="sf9kcnbcv"/></linearGradient><linearGradient id="iE02Edd" x1="16" x2="16" y1="21.815" y2="29.638" gradientUnits="userSpaceOnUse"><stop offset=".335" class="rncwomckg"/><stop offset="1" class="suq885v0i"/></linearGradient><linearGradient id="i19r18w" x1="2.39" x2="7.64" y1="25.727" y2="25.727" gradientUnits="userSpaceOnUse"><stop offset=".316" class="r5etz3bte"/><stop offset="1" class="dgetnlblh"/></linearGradient><linearGradient id="iaJFlkd" x1="17.39" x2="17.39" y1="30" y2="28.125" gradientUnits="userSpaceOnUse"><stop class="suq885v0i"/><stop offset="1" class="l99bh6j4v"/></linearGradient><linearGradient id="iKGIyEc" x1="26.154" x2="26.154" y1="12.051" y2="25.491" gradientUnits="userSpaceOnUse"><stop class="fwk6qnv6h"/><stop offset="1" class="zoq-6ibgq"/></linearGradient><linearGradient id="iv76qcc" x1="26.962" x2="26.647" y1="25.61" y2="21.221" gradientUnits="userSpaceOnUse"><stop offset=".25" class="v6sswpbqk"/><stop offset="1" class="rthee-bkr"/></linearGradient><filter id="iKbS0sb" width="4.674" height="4.879" x="1.764" y="6.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.866667 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17080"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.764706 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17080" result="effect2_innerShadow_18_17080"/></filter><filter id="iQM6QDe" width="28.872" height="20.034" x="1.864" y="9.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.72549 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17080"/></filter><filter id="iMFYMpd" width="28.872" height="7.823" x="1.864" y="21.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.72549 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17080"/></filter><filter id="ics6mGd" width="8.351" height="17.36" x="22.801" y="9.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17080" stdDeviation="1"/></filter><radialGradient id="ioVfJ6c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8378 -.7958 .83127 -2.9643 4.702 8.483)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="tvosnutmo"/><stop offset=".942" class="u2mv3nbpp"/></radialGradient><radialGradient id="inZs3Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.0625 -13.0167 0 16 20.938)" gradientUnits="userSpaceOnUse"><stop offset=".485" class="rncwomckg"/><stop offset="1" class="gd6e2z2kv"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clutch-bag" /></template>
<style>
.dgetnlblh {
  stop-color: var(--svg-color--d8929a, #D8929A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwk6qnv6h {
  stop-color: var(--svg-color--ffc4b7, #FFC4B7);
}

.gd6e2z2kv {
  stop-color: var(--svg-color--f7a7b8, #F7A7B8);
  stop-opacity: 0;
}

.hhhm45baq {
  stop-color: var(--svg-color--ffc432, #FFC432);
}

.j6moi1_8m {
  stop-color: var(--svg-color--f091a0, #F091A0);
}

.j9klqccxm {
  d: path("M2.921 14.452a5.5 5.5 0 0 1 5.461-4.847h15.2a5.5 5.5 0 0 1 5.458 4.823l1.05 8.472a6 6 0 0 1-5.955 6.738H7.865a6 6 0 0 1-5.957-6.712z");
}

.jkmk6johg {
  d: path("m29.955 21.815l.134 1.085a6 6 0 0 1-5.954 6.738H7.865a6 6 0 0 1-5.957-6.712l.132-1.11z");
}

.jtw8ysxll {
  stop-color: var(--svg-color--ffcc47, #FFCC47);
}

.l99bh6j4v {
  stop-color: var(--svg-color--e277d3, #E277D3);
  stop-opacity: 0;
}

.ltsrxdbio {
  fill-rule: evenodd;
  d: path("M2.182 7.22a.8.8 0 0 0-.057 1.229l2.27 2.07a1.16 1.16 0 0 0 1.761-1.482l-1.61-2.523a.8.8 0 0 0-1.157-.208zm2.99 3.013a.57.57 0 1 0 0-1.14a.57.57 0 0 0 0 1.14");
}

.p7apxebux {
  stop-color: var(--svg-color--d37e7e, #D37E7E);
}

.r5etz3bte {
  stop-color: var(--svg-color--d8929a, #D8929A);
}

.rncwomckg {
  stop-color: var(--svg-color--f7a7b8, #F7A7B8);
}

.rthee-bkr {
  stop-color: var(--svg-color--ffc8c8, #FFC8C8);
  stop-opacity: 0;
}

.sf9kcnbcv {
  stop-color: var(--svg-color--db7f8a, #DB7F8A);
  stop-opacity: 0;
}

.suq885v0i {
  stop-color: var(--svg-color--e277d3, #E277D3);
}

.tvosnutmo {
  stop-color: var(--svg-color--ffdd29, #FFDD29);
  stop-opacity: 0;
}

.u2mv3nbpp {
  stop-color: var(--svg-color--ffdd29, #FFDD29);
}

.uy0-01bsy {
  width: 3.063px;
  height: 13.44px;
  x: 24.623px;
  y: 12.051px;
  rx: 1.531px;
}

.v6sswpbqk {
  stop-color: var(--svg-color--ffc8c8, #FFC8C8);
}

.yv1h-kp6e {
  stop-color: var(--svg-color--ee9d8c, #EE9D8C);
}

.zoq-6ibgq {
  stop-color: var(--svg-color--ffc4b7, #FFC4B7);
  stop-opacity: 0;
}

</style>
