<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCIsCse)"><path class="vr62n13or"/><path fill="url(#ieGg1bd)" class="ifd54i2vx"/><path fill="url(#i9otG1c)" class="ifd54i2vx"/></g><g filter="url(#iMTZtwa)"><path class="xseafqb_d"/><path fill="url(#iPXKW4d)" class="mcbwfob-r"/><path fill="url(#iQMgS7Z)" class="mcbwfob-r"/></g><path fill="url(#ivea4Ce)" class="mcbwfob-r"/><circle fill="url(#iItWT2d)" class="m8drmgbdr"/><circle fill="url(#iVRL6pb)" class="m8drmgbdr"/><circle fill="url(#iHqGLQG)" class="gsr9e1vmr"/><circle fill="url(#ir4IIHz)" class="o3h1a_26w"/><circle fill="url(#iBKYWgx)" class="o3h1a_26w"/><circle fill="url(#iL4UAvd)" class="o3h1a_26w"/><circle fill="url(#iGqGMfl)" class="o3h1a_26w"/><g filter="url(#iCqvYIb)"><path class="lhuydcc8g"/></g><defs><linearGradient id="i9otG1c" x1="6.582" x2="8.377" y1="2.023" y2="6.493" gradientUnits="userSpaceOnUse"><stop class="ubgt9sb5d"/><stop offset="1" class="nsqonybfc"/></linearGradient><linearGradient id="iQMgS7Z" x1="25.265" x2="23.47" y1="2.023" y2="6.493" gradientUnits="userSpaceOnUse"><stop class="ubgt9sb5d"/><stop offset="1" class="nsqonybfc"/></linearGradient><linearGradient id="ivea4Ce" x1="15.749" x2="16.086" y1="7.063" y2="7.25" gradientUnits="userSpaceOnUse"><stop class="bsa9m1bnx"/><stop offset="1" class="sp9hu8pud"/></linearGradient><linearGradient id="iItWT2d" x1="23.797" x2="14.45" y1="14.938" y2="23.484" gradientUnits="userSpaceOnUse"><stop class="h4mru478r"/><stop offset="1" class="pqohq5bnu"/></linearGradient><linearGradient id="iVRL6pb" x1="12.536" x2="14.802" y1="30.668" y2="17.527" gradientUnits="userSpaceOnUse"><stop class="yjjuorbrv"/><stop offset="1" class="sv8mttj_c"/></linearGradient><linearGradient id="iHqGLQG" x1="23.963" x2="16.047" y1="18.613" y2="18.613" gradientUnits="userSpaceOnUse"><stop class="cczmrxyav"/><stop offset="1" class="hushotbag"/></linearGradient><linearGradient id="ir4IIHz" x1="11.286" x2="23.909" y1="22.103" y2="18.283" gradientUnits="userSpaceOnUse"><stop class="ignkl5a6s"/><stop offset="1" class="eocakzcqj"/></linearGradient><radialGradient id="ieGg1bd" cx="0" cy="0" r="1" gradientTransform="rotate(-123.321 9.745 2.387)scale(4.60352 17.1923)" gradientUnits="userSpaceOnUse"><stop class="lfociildi"/><stop offset="1" class="inwf30odu"/></radialGradient><radialGradient id="iPXKW4d" cx="0" cy="0" r="1" gradientTransform="rotate(-57.265 20.217 -11.245)scale(3.0487 6.68733)" gradientUnits="userSpaceOnUse"><stop class="lfociildi"/><stop offset="1" class="inwf30odu"/></radialGradient><radialGradient id="iBKYWgx" cx="0" cy="0" r="1" gradientTransform="rotate(156.644 7.501 11.447)scale(11.397 9.71148)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="jk4pe8jwr"/><stop offset="1" class="zjz6i-boe"/></radialGradient><radialGradient id="iL4UAvd" cx="0" cy="0" r="1" gradientTransform="rotate(-41.294 35.446 -9.492)scale(8.96398 8.60716)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="ob0q-1bic"/><stop offset="1" class="mbug67bel"/></radialGradient><radialGradient id="iGqGMfl" cx="0" cy="0" r="1" gradientTransform="matrix(6.65625 5.1875 -5.87867 7.54311 15.828 19.5)" gradientUnits="userSpaceOnUse"><stop offset=".926" class="rfdmtb-ae"/><stop offset="1" class="xcdla9b2s"/></radialGradient><filter id="iCIsCse" width="14.889" height="10.434" x="3.61" y="2.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1616" result="effect2_innerShadow_18_1616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.607843 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_1616" result="effect3_innerShadow_18_1616"/></filter><filter id="iMTZtwa" width="14.889" height="10.434" x="13.298" y="2.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1616" result="effect2_innerShadow_18_1616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.607843 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_1616" result="effect3_innerShadow_18_1616"/></filter><filter id="iCqvYIb" width="6.477" height="9.5" x="12.759" y="15.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.113725 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.352941 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1616" result="effect2_innerShadow_18_1616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.113725 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_1616" result="effect3_innerShadow_18_1616"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:3rd-place-medal" /></template>
<style>
.bsa9m1bnx {
  stop-color: var(--svg-color--1a6dd8, #1A6DD8);
}

.cczmrxyav {
  stop-color: var(--svg-color--cd8858, #CD8858);
}

.eocakzcqj {
  stop-color: var(--svg-color--be794e, #BE794E);
}

.ft5dv1b6b {
  fill: none;
}

.gsr9e1vmr {
  cx: 16.047px;
  cy: 20.132px;
  r: 8.688px;
}

.h4mru478r {
  stop-color: var(--svg-color--f6bc7f, #F6BC7F);
}

.hushotbag {
  stop-color: var(--svg-color--d28d59, #D28D59);
}

.ifd54i2vx {
  d: path("m14.035 3.552l4.264 7.284l-6.016 1.71C8.128 11.173 5.681 8.53 4.205 5.814c-.622-1.146-.617-3.25 1.856-3.25h6.248a2 2 0 0 1 1.726.989");
}

.ignkl5a6s {
  stop-color: var(--svg-color--d38e5f, #D38E5F);
}

.inwf30odu {
  stop-color: var(--svg-color--3669d9, #3669D9);
  stop-opacity: 0;
}

.jk4pe8jwr {
  stop-color: var(--svg-color--e5ac75, #E5AC75);
  stop-opacity: 0;
}

.lfociildi {
  stop-color: var(--svg-color--3669d9, #3669D9);
}

.lhuydcc8g {
  fill: var(--svg-color--6c3f48, #6C3F48);
  d: path("m17.46 18.675l1.046-1.81a.98.98 0 0 0 0-.976a.97.97 0 0 0-.843-.489H14.57a.976.976 0 0 0 0 1.953h.972a.25.25 0 0 1 .217.374l-.538.938a.96.96 0 0 0-.214.6c0 .539.438.976.977.976c.61 0 1.108.498 1.108 1.108s-.498 1.109-1.108 1.109a1.1 1.1 0 0 1-1.038-.732a.975.975 0 0 0-1.24-.59a.966.966 0 0 0-.59 1.24a3.06 3.06 0 0 0 2.867 2.024a3.053 3.053 0 0 0 3.051-3.05a3.07 3.07 0 0 0-1.576-2.675");
}

.m8drmgbdr {
  cx: 16.047px;
  cy: 20.132px;
  r: 10.048px;
}

.mbug67bel {
  stop-color: var(--svg-color--b36441, #B36441);
}

.mcbwfob-r {
  d: path("m17.812 3.552l-4.264 7.284l6.016 1.71c4.155-1.374 6.602-4.017 8.078-6.733c.622-1.146.617-3.25-1.856-3.25h-6.248a2 2 0 0 0-1.726.989");
}

.nsqonybfc {
  stop-color: var(--svg-color--3d89ec, #3D89EC);
  stop-opacity: 0;
}

.o3h1a_26w {
  cx: 16.047px;
  cy: 20.132px;
  r: 7.585px;
}

.ob0q-1bic {
  stop-color: var(--svg-color--b36441, #B36441);
  stop-opacity: 0;
}

.pqohq5bnu {
  stop-color: var(--svg-color--a76740, #A76740);
}

.rfdmtb-ae {
  stop-color: var(--svg-color--ab662b, #AB662B);
  stop-opacity: 0;
}

.sp9hu8pud {
  stop-color: var(--svg-color--1a6dd8, #1A6DD8);
  stop-opacity: 0;
}

.sv8mttj_c {
  stop-color: var(--svg-color--b05b5b, #B05B5B);
  stop-opacity: 0;
}

.ubgt9sb5d {
  stop-color: var(--svg-color--3d89ec, #3D89EC);
}

.vr62n13or {
  fill: var(--svg-color--4686ec, #4686EC);
  d: path("m14.035 3.552l4.264 7.284l-6.016 1.71C8.128 11.173 5.681 8.53 4.205 5.814c-.622-1.146-.617-3.25 1.856-3.25h6.248a2 2 0 0 1 1.726.989");
}

.xcdla9b2s {
  stop-color: var(--svg-color--ab662b, #AB662B);
}

.xseafqb_d {
  fill: var(--svg-color--4686ec, #4686EC);
  d: path("m17.812 3.552l-4.264 7.284l6.016 1.71c4.155-1.374 6.602-4.017 8.078-6.733c.622-1.146.617-3.25-1.856-3.25h-6.248a2 2 0 0 0-1.726.989");
}

.yjjuorbrv {
  stop-color: var(--svg-color--b05b5b, #B05B5B);
}

.zjz6i-boe {
  stop-color: var(--svg-color--e5ac75, #E5AC75);
}

</style>
