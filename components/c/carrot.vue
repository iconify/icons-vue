<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ci_9nwbtl"/><path fill="url(#i9iYrGb)" class="ioapx3b_m"/><path fill="url(#ijzPTac)" class="ioapx3b_m"/><path fill="url(#iPUR0ae)" class="ioapx3b_m"/><path fill="url(#iVnAVwk)" class="ioapx3b_m"/><path fill="url(#is1th7d)" class="w68bqf1jy"/><path fill="url(#imYEOzb)" class="icwx2sbth"/><path fill="url(#i1x1y6v)" class="m85h4uytu"/><path class="o76asq5ro"/><path fill="url(#igrqAeX)" class="rr0zh1q2a"/><path fill="url(#iHYL3pd)" class="rr0zh1q2a"/><path class="f9yin3zub"/><path fill="url(#iYMAoyc)" class="a_kogjs7y"/><path fill="url(#iPZtlze)" class="a_kogjs7y"/><path fill="url(#icQew7d)" class="a_kogjs7y"/><path class="myl4ffbyi"/><path fill="url(#iSSqm6b)" class="l-4nhobqn"/><path fill="url(#iIrJsSb)" class="l-4nhobqn"/><defs><radialGradient id="iPUR0ae" cx="0" cy="0" r="1" gradientTransform="matrix(-5 5.75001 -11.56102 -10.05303 21.625 14.875)" gradientUnits="userSpaceOnUse"><stop class="e4vmyvu7l"/><stop offset=".53" class="unqr1kz8j"/><stop offset="1" class="y75-jhbuh"/></radialGradient><radialGradient id="iVnAVwk" cx="0" cy="0" r="1" gradientTransform="rotate(139.81 -.109 13.566)scale(22.663 22.6004)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="n92ppum2h"/><stop offset=".773" class="iwsjvevmc"/><stop offset=".849" class="gt5smhbir"/></radialGradient><radialGradient id="igrqAeX" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 1.12499 -1.05603 -1.99475 21.313 4.625)" gradientUnits="userSpaceOnUse"><stop class="uu3lxcbto"/><stop offset="1" class="plofi7jge"/></radialGradient><radialGradient id="iHYL3pd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91602 .81252 -1.14761 -6.94343 21.688 6.25)" gradientUnits="userSpaceOnUse"><stop class="lpg7lwbmu"/><stop offset=".713" class="mo-_fsboh"/><stop offset="1" class="vp6ugqbrg"/></radialGradient><radialGradient id="iYMAoyc" cx="0" cy="0" r="1" gradientTransform="rotate(139.268 12.038 11.153)scale(2.96924 2.78724)" gradientUnits="userSpaceOnUse"><stop class="uu3lxcbto"/><stop offset="1" class="plofi7jge"/></radialGradient><radialGradient id="iPZtlze" cx="0" cy="0" r="1" gradientTransform="matrix(1.03086 4.5 -11.77996 2.69856 25.782 11.563)" gradientUnits="userSpaceOnUse"><stop class="i8hpb80ol"/><stop offset="1" class="h5oil6frc"/></radialGradient><radialGradient id="iSSqm6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0336 2.55837 -1.9571 -.79068 27.545 4.857)" gradientUnits="userSpaceOnUse"><stop class="uu3lxcbto"/><stop offset="1" class="plofi7jge"/></radialGradient><radialGradient id="iIrJsSb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.87498 7.87498 -3.78308 -3.78308 27.126 5.938)" gradientUnits="userSpaceOnUse"><stop class="lpg7lwbmu"/><stop offset=".847" class="gyrapmyof"/></radialGradient><linearGradient id="i9iYrGb" x1="-2.5" x2="11.563" y1="12.5" y2="20.313" gradientUnits="userSpaceOnUse"><stop offset=".541" class="lsxv47lyi"/><stop offset=".769" class="jq-1rvb3p"/><stop offset="1" class="ap7t0j6lz"/></linearGradient><linearGradient id="ijzPTac" x1="20.5" x2="15.063" y1="32.375" y2="18.563" gradientUnits="userSpaceOnUse"><stop offset=".404" class="x-wxw8hda"/><stop offset="1" class="othpmksub"/></linearGradient><linearGradient id="is1th7d" x1="7.188" x2="12.938" y1="13.688" y2="19.125" gradientUnits="userSpaceOnUse"><stop offset=".1" class="qjf3o8t3k"/><stop offset="1" class="yvrv2d_az"/></linearGradient><linearGradient id="imYEOzb" x1="8.947" x2="11.585" y1="24.012" y2="28.797" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ifb4jchjq"/><stop offset="1" class="o07budbpv"/></linearGradient><linearGradient id="i1x1y6v" x1="17.25" x2="22.278" y1="17.688" y2="24.414" gradientUnits="userSpaceOnUse"><stop offset=".1" class="rspo13bym"/><stop offset="1" class="x-u3n6b8a"/></linearGradient><linearGradient id="icQew7d" x1="27.719" x2="27.625" y1="9.125" y2="10.688" gradientUnits="userSpaceOnUse"><stop offset=".276" class="jaboj8bmr"/><stop offset="1" class="rchab8b-n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:carrot" /></template>
<style>
.a_kogjs7y {
  d: path("M29.312 14.437c-1.51 1.757-3.546 1.22-4.296.516a1113 1113 0 0 0-3.328-3.422c-.25-.387-.194-.66-.141-.89c.039-.172.175-.324.39-.446c.18-.101 2.683-.35 5.266-.523c1.927-.13 3.828 2.765 2.11 4.765");
}

.ap7t0j6lz {
  stop-color: var(--svg-color--fd9434, #FD9434);
}

.ci_9nwbtl {
  fill: var(--svg-color--ff8c4c, #FF8C4C);
  d: path("m4.691 29.774l16.51-4.886c4.729-1.398 6.318-7.41 2.924-10.982l-5.269-5.544c-3.394-3.572-9.382-2.177-11.02 2.463L2.119 27.066c-.572 1.619.927 3.197 2.573 2.708");
}

.e4vmyvu7l {
  stop-color: var(--svg-color--ffd769, #FFD769);
}

.f9yin3zub {
  fill: var(--svg-color--aad248, #AAD248);
  d: path("M29.312 14.437c-1.51 1.757-3.546 1.22-4.296.516a1113 1113 0 0 0-3.328-3.422c-.25-.387-.194-.66-.141-.89c.039-.172.175-.324.39-.446c.18-.101 2.683-.35 5.266-.523c1.927-.13 3.828 2.765 2.11 4.765");
}

.ft5dv1b6b {
  fill: none;
}

.gt5smhbir {
  stop-color: var(--svg-color--cb751f, #CB751F);
}

.gyrapmyof {
  stop-color: var(--svg-color--6fb909, #6FB909);
}

.h5oil6frc {
  stop-color: var(--svg-color--b3ba74, #B3BA74);
}

.i8hpb80ol {
  stop-color: var(--svg-color--a7d029, #A7D029);
  stop-opacity: 0;
}

.icwx2sbth {
  d: path("M8.955 23.713a1.31 1.31 0 0 0-.047 1.851l2.199 2.314l2.81-.834l-3.121-3.284a1.3 1.3 0 0 0-1.84-.047");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ifb4jchjq {
  stop-color: var(--svg-color--9e5044, #9E5044);
}

.ioapx3b_m {
  d: path("m4.691 29.774l16.51-4.886c4.729-1.398 6.318-7.41 2.924-10.982l-5.269-5.544c-3.394-3.572-9.382-2.177-11.02 2.463L2.119 27.066c-.572 1.619.927 3.197 2.573 2.708");
}

.iwsjvevmc {
  stop-color: var(--svg-color--f28b3a, #F28B3A);
  stop-opacity: 0;
}

.jaboj8bmr {
  stop-color: var(--svg-color--8ace17, #8ACE17);
}

.jq-1rvb3p {
  stop-color: var(--svg-color--ea842a, #EA842A);
}

.l-4nhobqn {
  d: path("M28.094 3.766c2.533 1.856 1.218 5.5-.891 5.906c-1.505.29-5.07.437-5.07.437s.288-3.583.695-4.797c.984-2.937 3.688-2.703 5.266-1.546");
}

.lpg7lwbmu {
  stop-color: var(--svg-color--afdc52, #AFDC52);
  stop-opacity: 0;
}

.lsxv47lyi {
  stop-color: var(--svg-color--b3734c, #B3734C);
}

.m85h4uytu {
  d: path("M17.098 16.887a1.31 1.31 0 0 0-.047 1.851l5.38 5.662a6.45 6.45 0 0 0 2.02-1.666l-5.502-5.79a1.303 1.303 0 0 0-1.85-.057");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mo-_fsboh {
  stop-color: var(--svg-color--8bc028, #8BC028);
}

.myl4ffbyi {
  fill: var(--svg-color--aad248, #AAD248);
  d: path("M28.094 3.766c2.533 1.856 1.218 5.5-.891 5.906c-1.505.29-5.07.437-5.07.437s.288-3.583.695-4.797c.984-2.937 3.688-2.703 5.266-1.546");
}

.n92ppum2h {
  stop-color: var(--svg-color--ff9243, #FF9243);
  stop-opacity: 0;
}

.o07budbpv {
  stop-color: var(--svg-color--c95d82, #C95D82);
}

.o76asq5ro {
  fill: var(--svg-color--aad248, #AAD248);
  d: path("M18.132 3.02c-1.792 1.468-1.301 3.516-.616 4.283a518 518 0 0 0 3.75 3.744c.381.26.655.208.887.161c.172-.035.327-.168.454-.38c.106-.177.006-3.01.24-5.589c.175-1.923-2.675-3.891-4.715-2.22");
}

.othpmksub {
  stop-color: var(--svg-color--ff717b, #FF717B);
  stop-opacity: 0;
}

.plofi7jge {
  stop-color: var(--svg-color--bcef62, #BCEF62);
  stop-opacity: 0;
}

.qjf3o8t3k {
  stop-color: var(--svg-color--6e482a, #6E482A);
}

.rchab8b-n {
  stop-color: var(--svg-color--91d212, #91D212);
  stop-opacity: 0;
}

.rr0zh1q2a {
  d: path("M18.132 3.02c-1.792 1.468-1.301 3.516-.616 4.283a518 518 0 0 0 3.75 3.744c.381.26.655.208.887.161c.172-.035.327-.168.454-.38c.106-.177.006-3.01.24-5.589c.175-1.923-2.675-3.891-4.715-2.22");
}

.rspo13bym {
  stop-color: var(--svg-color--aa6147, #AA6147);
}

.unqr1kz8j {
  stop-color: var(--svg-color--ffa427, #FFA427);
}

.uu3lxcbto {
  stop-color: var(--svg-color--c1f26b, #C1F26B);
}

.vp6ugqbrg {
  stop-color: var(--svg-color--81aa56, #81AA56);
}

.w68bqf1jy {
  d: path("M13.006 19.082a1.31 1.31 0 0 0 .047-1.85L7.6 11.496l-.975 2.763l4.53 4.766a1.303 1.303 0 0 0 1.85.057");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x-u3n6b8a {
  stop-color: var(--svg-color--cb747c, #CB747C);
}

.x-wxw8hda {
  stop-color: var(--svg-color--ff7cb4, #FF7CB4);
}

.y75-jhbuh {
  stop-color: var(--svg-color--fca328, #FCA328);
  stop-opacity: 0;
}

.yvrv2d_az {
  stop-color: var(--svg-color--ac5e3b, #AC5E3B);
}

</style>
