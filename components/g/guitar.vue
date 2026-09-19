<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#io2v7pZ)"><path fill="url(#iA5K0Jl)" class="qej5c71gf"/></g><path fill="url(#ifQ9jgb)" class="idr4rubel"/><g filter="url(#ijmb7Rb)"><path fill="url(#iKKA0gc)" class="b539q0btg"/><path fill="url(#ibr44pb)" class="b539q0btg"/></g><g filter="url(#iemsJzd)"><path class="uw7hsybgc"/><path fill="url(#i6vhKcc)" class="hi8o82far"/></g><g filter="url(#im4o51d)"><path fill="url(#im5JGSd)" class="kcr_r64sl"/></g><g filter="url(#izsCLmb)"><path fill="url(#iRuQfbe)" class="eo913fbiv"/></g><g filter="url(#ihsroYd)"><path fill="url(#ib7eGOb)" class="tsa185bnz"/><path fill="url(#iAFQNNe)" class="tsa185bnz"/></g><circle fill="url(#iAjnDAd)" class="i4ztv7bpj"/><circle fill="url(#iNYBrwe)" class="t4jp5bc9j"/><circle fill="url(#ix45uDb)" class="jr7-89btg"/><defs><linearGradient id="iA5K0Jl" x1="9.562" x2="20.563" y1="24.5" y2="23.625" gradientUnits="userSpaceOnUse"><stop class="oy815o_yu"/><stop offset="1" class="nwckpg90j"/></linearGradient><linearGradient id="ifQ9jgb" x1="5.844" x2="12.5" y1="19.094" y2="21.438" gradientUnits="userSpaceOnUse"><stop class="k8g1h8bxz"/><stop offset="1" class="h5xwibcad"/></linearGradient><linearGradient id="iKKA0gc" x1="24.344" x2="14.219" y1="8.063" y2="17.938" gradientUnits="userSpaceOnUse"><stop class="h3xctvtjl"/><stop offset="1" class="j2jwy3bwu"/></linearGradient><linearGradient id="ibr44pb" x1="24.984" x2="24.453" y1="8.016" y2="8.531" gradientUnits="userSpaceOnUse"><stop offset=".22" class="h85zkb1bt"/><stop offset="1" class="jg6dxqq6u"/></linearGradient><linearGradient id="im5JGSd" x1="11.899" x2="13.844" y1="18.484" y2="20.391" gradientUnits="userSpaceOnUse"><stop class="uvja22blw"/><stop offset="1" class="z2d2abbcb"/></linearGradient><linearGradient id="iRuQfbe" x1="9.836" x2="11.781" y1="20.547" y2="22.453" gradientUnits="userSpaceOnUse"><stop class="uvja22blw"/><stop offset="1" class="z2d2abbcb"/></linearGradient><linearGradient id="ib7eGOb" x1="8.687" x2="7.125" y1="23.688" y2="25.344" gradientUnits="userSpaceOnUse"><stop class="cg2f_rbot"/><stop offset="1" class="ca315unat"/></linearGradient><linearGradient id="iAFQNNe" x1="8.516" x2="8.156" y1="23.578" y2="23.969" gradientUnits="userSpaceOnUse"><stop class="jsaq6xupo"/><stop offset="1" class="f-hbunq2q"/></linearGradient><filter id="io2v7pZ" width="20.021" height="21.133" x="2.098" y="9.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.368627 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18660"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18660" result="effect2_innerShadow_18_18660"/></filter><filter id="ijmb7Rb" width="12.411" height="11.911" x="13.455" y="6.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.258824 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18660"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.309804 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18660" result="effect2_innerShadow_18_18660"/></filter><filter id="iemsJzd" width="7.09" height="5.594" x="23.436" y="3.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.196078 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18660"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.196078 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18660" result="effect2_innerShadow_18_18660"/></filter><filter id="im4o51d" width="2.728" height="2.746" x="11.656" y="17.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.517647 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18660"/></filter><filter id="izsCLmb" width="2.728" height="2.746" x="9.594" y="20.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.517647 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18660"/></filter><filter id="ihsroYd" width="4.306" height="4.322" x="5.52" y="22.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.141176 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18660"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18660" result="shape"/></filter><radialGradient id="i6vhKcc" cx="0" cy="0" r="1" gradientTransform="matrix(4.60938 -1.58826 .95915 2.78361 25.656 6.37)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="rkgf48bjh"/><stop offset="1" class="ef2puou3i"/></radialGradient><radialGradient id="iAjnDAd" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 11.905 4.907)scale(.56731)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="eceudwb9v"/><stop offset="1" class="dp4re-zzc"/></radialGradient><radialGradient id="iNYBrwe" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 12.823 4.725)scale(.56731)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="eceudwb9v"/><stop offset="1" class="dp4re-zzc"/></radialGradient><radialGradient id="ix45uDb" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 13.792 4.534)scale(.56731)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="eceudwb9v"/><stop offset="1" class="dp4re-zzc"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:guitar" /></template>
<style>
.b539q0btg {
  d: path("m23.764 6.752l1.851 1.852l-9.942 9.941a.4.4 0 0 1-.565 0l-1.286-1.286a.4.4 0 0 1 0-.565z");
}

.ca315unat {
  stop-color: var(--svg-color--9178a2, #9178A2);
}

.cg2f_rbot {
  stop-color: var(--svg-color--a394b1, #A394B1);
}

.dp4re-zzc {
  stop-color: var(--svg-color--b7a7c0, #B7A7C0);
}

.eceudwb9v {
  stop-color: var(--svg-color--c3b9c9, #C3B9C9);
}

.ef2puou3i {
  stop-color: var(--svg-color--e663a0, #E663A0);
}

.eo913fbiv {
  d: path("M9.747 20.254a.514.514 0 0 1 .727.004l1.6 1.617a.515.515 0 0 1-.732.724l-1.6-1.617a.514.514 0 0 1 .005-.728");
}

.f-hbunq2q {
  stop-color: var(--svg-color--ad9fb8, #AD9FB8);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h3xctvtjl {
  stop-color: var(--svg-color--635c95, #635C95);
}

.h5xwibcad {
  stop-color: var(--svg-color--ffe8ff, #FFE8FF);
}

.h85zkb1bt {
  stop-color: var(--svg-color--57337d, #57337D);
}

.hi8o82far {
  d: path("M28.922 6.742c.803 0 1.455-.76 1.455-1.564a1.455 1.455 0 0 0-2.108-1.3l-4.062 1.666a1 1 0 0 0-.332 1.627l1.576 1.598c.356.361.986.327 1.258-.102c.262-.412.57-.99.858-1.81c.064-.185.288-.274.476-.224c.293.078.641.11.879.11");
}

.i4ztv7bpj {
  cx: 24.41px;
  cy: 4.945px;
  r: 0.574px;
}

.idr4rubel {
  d: path("M7.203 18.188c.943-1.29 2.92-1.594 3.858-1.555a.21.21 0 0 0 .19-.102c.442-.742.897-1.215 1.452-1.312c.383-.036 1.038-.047 1.5.828c.463.875 1.182 1.74 1.484 2.062c1.523.636 2.62.46 3.4.251a.625.625 0 0 1 .773.448c.097.384-.18.768-.564.863a5.7 5.7 0 0 0-2.53 1.376c-1.594 1.5-.86 3.25-2.125 5.031c-.764 1.075-2.907 3.094-4.235 2c-.631-.52-.554-1.76-.283-2.656c.128-.423.074-.907-.23-1.228l-2.487-2.616c-.458-.578-1.19-2.04-.203-3.39");
}

.j2jwy3bwu {
  stop-color: var(--svg-color--605193, #605193);
}

.jg6dxqq6u {
  stop-color: var(--svg-color--645d97, #645D97);
  stop-opacity: 0;
}

.jr7-89btg {
  cx: 27.895px;
  cy: 3.5px;
  r: 0.574px;
}

.jsaq6xupo {
  stop-color: var(--svg-color--ad9fb8, #AD9FB8);
}

.k8g1h8bxz {
  stop-color: var(--svg-color--ffebff, #FFEBFF);
}

.kcr_r64sl {
  d: path("M11.81 18.192a.514.514 0 0 1 .727.004l1.599 1.617a.515.515 0 0 1-.732.723l-1.599-1.617a.515.515 0 0 1 .004-.727");
}

.nwckpg90j {
  stop-color: var(--svg-color--d83391, #D83391);
}

.oy815o_yu {
  stop-color: var(--svg-color--d53556, #D53556);
}

.qej5c71gf {
  d: path("M11.688 13.063c.259-1.495 1.297-2.782 2.356-3.63c.456-.365 1.1-.307 1.549.068c.787.658.623 2.003-.073 2.756q-.228.245-.442.54c-1.375 1.906.281 3.812 1.5 4.375c.953.586 2.235.328 2.735.203s2.156-.562 2.437.625s-.312 2.188-1.625 2.438s-2.562.093-3.094 2.812c-.531 2.719-1.718 5.125-4.468 6.188s-5.907.75-8.25-1.594c-1.844-1.969-2.844-5.907-.938-9.032C5.5 15.72 8.156 15.5 9.031 15.345s2.203-.125 2.656-2.281");
}

.rkgf48bjh {
  stop-color: var(--svg-color--e663a0, #E663A0);
  stop-opacity: 0;
}

.t4jp5bc9j {
  cx: 26.105px;
  cy: 4.242px;
  r: 0.574px;
}

.tsa185bnz {
  d: path("M6.799 22.784a.5.5 0 0 1 .707.004l2.026 2.05a.5.5 0 0 1-.004.706l-.68.673a.5.5 0 0 1-.706-.004l-2.027-2.05a.5.5 0 0 1 .004-.707z");
}

.uvja22blw {
  stop-color: var(--svg-color--9c8baa, #9C8BAA);
}

.uw7hsybgc {
  fill: var(--svg-color--cd338b, #CD338B);
  d: path("M28.922 6.742c.803 0 1.455-.76 1.455-1.564a1.455 1.455 0 0 0-2.108-1.3l-4.062 1.666a1 1 0 0 0-.332 1.627l1.576 1.598c.356.361.986.327 1.258-.102c.262-.412.57-.99.858-1.81c.064-.185.288-.274.476-.224c.293.078.641.11.879.11");
}

.z2d2abbcb {
  stop-color: var(--svg-color--a08eaf, #A08EAF);
}

</style>
