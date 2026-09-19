<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBbmSQd)" class="nnpuiy_gl"/><path fill="url(#igk74pK)" class="nnpuiy_gl"/><g filter="url(#iBsEa8x)"><path fill="url(#iRBzcNc)" clip-rule="evenodd" class="z15facg4d"/></g><g filter="url(#i2tFeIb)"><path fill="url(#iRMow4T)" clip-rule="evenodd" class="gxisctgjz"/></g><g filter="url(#iNaB0Jb)"><path fill="url(#iIPP1Ae)" clip-rule="evenodd" class="soexfebiz"/></g><circle fill="url(#i64kXKe)" class="gb5beg0wc"/><circle fill="url(#igtzcgb)" class="gb5beg0wc"/><circle fill="url(#iz0GSDc)" class="bmv9bj2ng"/><circle fill="url(#i5ttGab)" class="bmv9bj2ng"/><circle fill="url(#i41ECyb)" class="uz9rff60a"/><circle fill="url(#iuQh9Oc)" class="uz9rff60a"/><circle fill="url(#iohbJhd)" class="xuewmnbus"/><circle fill="url(#ivmrkbb)" class="xuewmnbus"/><g filter="url(#i6o6CLd)"><path stroke="url(#imwXx6c)" class="jacryso8y"/></g><path class="ob3rz05se"/><path fill="url(#id1CETV)" class="dsx--94kg"/><path fill="url(#i9240PI)" class="dsx--94kg"/><path fill="url(#i1eNC8c)" class="dsx--94kg"/><g filter="url(#iiisosd)"><path class="vqf9fu8dc"/><path fill="url(#iNROGle)" class="k_4ljqbsp"/></g><path fill="url(#i8SMF8b)" class="k_4ljqbsp"/><path fill="url(#iNVJjOe)" class="k_4ljqbsp"/><defs><radialGradient id="i64kXKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14964 1.48087 -1.38505 -1.07525 29.308 12.463)" gradientUnits="userSpaceOnUse"><stop class="o-28vi8fk"/><stop offset="1" class="p_b3ahb5j"/></radialGradient><radialGradient id="igtzcgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.06202 -1.79752 0 28.758 12.131)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="ulmo3sbbn"/><stop offset="1" class="xm_bmgbmq"/></radialGradient><radialGradient id="iz0GSDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14964 1.48087 -1.38505 -1.07525 19.574 20.634)" gradientUnits="userSpaceOnUse"><stop class="o-28vi8fk"/><stop offset="1" class="p_b3ahb5j"/></radialGradient><radialGradient id="i5ttGab" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.06202 -1.79752 0 19.023 20.303)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="ulmo3sbbn"/><stop offset="1" class="xm_bmgbmq"/></radialGradient><radialGradient id="i41ECyb" cx="0" cy="0" r="1" gradientTransform="rotate(127.823 3.183 9.427)scale(1.80105 1.68451)" gradientUnits="userSpaceOnUse"><stop class="o-28vi8fk"/><stop offset="1" class="p_b3ahb5j"/></radialGradient><radialGradient id="iuQh9Oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.98096 -1.72686 0 12.053 12.374)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="ulmo3sbbn"/><stop offset="1" class="xm_bmgbmq"/></radialGradient><radialGradient id="iohbJhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 1.1875 -1.11066 -.86223 19.484 2.615)" gradientUnits="userSpaceOnUse"><stop class="o-28vi8fk"/><stop offset="1" class="p_b3ahb5j"/></radialGradient><radialGradient id="ivmrkbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.6535 -1.44141 0 19.043 2.35)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="ulmo3sbbn"/><stop offset="1" class="xm_bmgbmq"/></radialGradient><radialGradient id="i1eNC8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 .85938 -1.03825 -1.0005 21.797 10.115)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="aq90gabuv"/><stop offset="1" class="y4o24tb9l"/></radialGradient><radialGradient id="iNVJjOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.71455 4.79687 -4.89695 -.72946 4.277 25.896)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="jdfk0ybia"/><stop offset=".918" class="s2shjmb0g"/></radialGradient><linearGradient id="iBbmSQd" x1="19.234" x2="5.172" y1="13.021" y2="27.396" gradientUnits="userSpaceOnUse"><stop class="v-kcfi4jg"/><stop offset="1" class="oa9dfdb7h"/></linearGradient><linearGradient id="igk74pK" x1="5.5" x2="6.969" y1="24.068" y2="25.521" gradientUnits="userSpaceOnUse"><stop class="q_opjkcrr"/><stop offset="1" class="rlqgvumlf"/></linearGradient><linearGradient id="iRBzcNc" x1="28.981" x2="25.017" y1="4.112" y2="8.079" gradientUnits="userSpaceOnUse"><stop class="xl814obuq"/><stop offset="1" class="gq2besb8a"/></linearGradient><linearGradient id="iRMow4T" x1="16.848" x2="13.885" y1="4.585" y2="7.551" gradientUnits="userSpaceOnUse"><stop class="p0mlczn1q"/><stop offset="1" class="fa01rfb3k"/></linearGradient><linearGradient id="iIPP1Ae" x1="26.41" x2="23.447" y1="15.554" y2="18.52" gradientUnits="userSpaceOnUse"><stop class="p0mlczn1q"/><stop offset="1" class="fa01rfb3k"/></linearGradient><linearGradient id="imwXx6c" x1="18.547" x2="4.172" y1="13.334" y2="27.459" gradientUnits="userSpaceOnUse"><stop class="et1fa2tsb"/><stop offset="1" class="tjlz73sgx"/></linearGradient><linearGradient id="id1CETV" x1="18.847" x2="19.849" y1="11.021" y2="11.969" gradientUnits="userSpaceOnUse"><stop class="i8onsbl-t"/><stop offset="1" class="tsm2pjguw"/></linearGradient><linearGradient id="i9240PI" x1="21.422" x2="20.797" y1="12.881" y2="12.225" gradientUnits="userSpaceOnUse"><stop class="th6x1cc1n"/><stop offset="1" class="q8-8hpbzz"/></linearGradient><linearGradient id="iNROGle" x1="3.283" x2="4.277" y1="26.585" y2="27.578" gradientUnits="userSpaceOnUse"><stop class="rlvzhhvqc"/><stop offset="1" class="uwtwq6msn"/></linearGradient><linearGradient id="i8SMF8b" x1="2.609" x2="3.391" y1="29.74" y2="28.771" gradientUnits="userSpaceOnUse"><stop class="fafin7blj"/><stop offset="1" class="kfwv5stnj"/></linearGradient><filter id="iBsEa8x" width="7.104" height="8.275" x="22.983" y="1.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3440"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.823529 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3440" result="effect2_innerShadow_18_3440"/></filter><filter id="i2tFeIb" width="5.385" height="6.261" x="12.327" y="2.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3440"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.823529 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3440" result="effect2_innerShadow_18_3440"/></filter><filter id="iNaB0Jb" width="5.385" height="6.261" x="21.89" y="13.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3440"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.823529 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3440" result="effect2_innerShadow_18_3440"/></filter><filter id="i6o6CLd" width="16.511" height="16.572" x="3.495" y="11.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3440" stdDeviation=".25"/></filter><filter id="iiisosd" width="4.206" height="4.608" x="2.124" y="25.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.619608 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3440"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:magic-wand" /></template>
<style>
.aq90gabuv {
  stop-color: var(--svg-color--ece8f2, #ECE8F2);
}

.bmv9bj2ng {
  cx: 19.023px;
  cy: 21.123px;
  r: 1.242px;
}

.dsx--94kg {
  d: path("m18.2 11.789l1.722-1.731a1.414 1.414 0 1 1 2.005 1.995l-1.714 1.722z");
}

.et1fa2tsb {
  stop-color: var(--svg-color--692167, #692167);
}

.fa01rfb3k {
  stop-color: var(--svg-color--ffaf36, #FFAF36);
}

.fafin7blj {
  stop-color: var(--svg-color--968fa1, #968FA1);
}

.ft5dv1b6b {
  fill: none;
}

.gb5beg0wc {
  cx: 28.758px;
  cy: 12.951px;
  r: 1.242px;
}

.gq2besb8a {
  stop-color: var(--svg-color--ffa271, #FFA271);
}

.gxisctgjz {
  fill-rule: evenodd;
  d: path("M14.262 7.297a.74.74 0 0 0-.547-.563a5.5 5.5 0 0 1-1.007-.384a.4.4 0 0 1 0-.725c.371-.18.702-.305 1.007-.385a.74.74 0 0 0 .547-.562c.082-.417.219-.93.425-1.434a.356.356 0 0 1 .671 0c.206.503.342 1.017.425 1.434a.74.74 0 0 0 .546.562c.305.08.633.204 1.003.385a.4.4 0 0 1 0 .725a5.5 5.5 0 0 1-1.003.384a.74.74 0 0 0-.546.563c-.083.417-.219.93-.425 1.433a.356.356 0 0 1-.671 0a8 8 0 0 1-.425-1.433");
}

.i8onsbl-t {
  stop-color: var(--svg-color--c1bfc3, #C1BFC3);
}

.jacryso8y {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.328 12.24L4.172 27.46");
}

.jdfk0ybia {
  stop-color: var(--svg-color--8f6eaf, #8F6EAF);
  stop-opacity: 0;
}

.k_4ljqbsp {
  d: path("M2.638 29.425c.553.553 1.45.552 2.003-.002l1.69-1.698l-2.007-1.994l-1.688 1.697a1.414 1.414 0 0 0 .002 1.997");
}

.kfwv5stnj {
  stop-color: var(--svg-color--968fa1, #968FA1);
  stop-opacity: 0;
}

.nnpuiy_gl {
  d: path("M4.64 29.423a1.414 1.414 0 0 1-2.005-1.995l17.287-17.37a1.414 1.414 0 1 1 2.005 1.995z");
}

.o-28vi8fk {
  stop-color: var(--svg-color--ffd463, #FFD463);
}

.oa9dfdb7h {
  stop-color: var(--svg-color--54155e, #54155E);
}

.ob3rz05se {
  fill: var(--svg-color--cfc9d8, #CFC9D8);
  d: path("m18.2 11.789l1.722-1.731a1.414 1.414 0 1 1 2.005 1.995l-1.714 1.722z");
}

.p_b3ahb5j {
  stop-color: var(--svg-color--e68f2b, #E68F2B);
}

.p0mlczn1q {
  stop-color: var(--svg-color--ffd465, #FFD465);
}

.q_opjkcrr {
  stop-color: var(--svg-color--523253, #523253);
}

.q8-8hpbzz {
  stop-color: var(--svg-color--b0a1bf, #B0A1BF);
  stop-opacity: 0;
}

.rlqgvumlf {
  stop-color: var(--svg-color--523253, #523253);
  stop-opacity: 0;
}

.rlvzhhvqc {
  stop-color: var(--svg-color--a8a6ad, #A8A6AD);
}

.s2shjmb0g {
  stop-color: var(--svg-color--8f6eaf, #8F6EAF);
}

.soexfebiz {
  fill-rule: evenodd;
  d: path("M23.824 18.266a.74.74 0 0 0-.546-.563a5.5 5.5 0 0 1-1.008-.385a.4.4 0 0 1 0-.724c.372-.18.702-.305 1.008-.385a.74.74 0 0 0 .546-.563c.083-.416.22-.93.425-1.433a.356.356 0 0 1 .672 0c.206.503.342 1.017.425 1.433a.74.74 0 0 0 .546.563c.304.08.632.204 1.002.384a.4.4 0 0 1 0 .726a5.5 5.5 0 0 1-1.002.384a.74.74 0 0 0-.546.563a8 8 0 0 1-.425 1.433a.356.356 0 0 1-.672 0a8 8 0 0 1-.425-1.433");
}

.th6x1cc1n {
  stop-color: var(--svg-color--b0a1bf, #B0A1BF);
}

.tjlz73sgx {
  stop-color: var(--svg-color--5b2460, #5B2460);
}

.tsm2pjguw {
  stop-color: var(--svg-color--c1bfc3, #C1BFC3);
  stop-opacity: 0;
}

.ulmo3sbbn {
  stop-color: var(--svg-color--e37a42, #E37A42);
  stop-opacity: 0;
}

.uwtwq6msn {
  stop-color: var(--svg-color--a8a6ad, #A8A6AD);
  stop-opacity: 0;
}

.uz9rff60a {
  cx: 12.053px;
  cy: 13.162px;
  r: 1.193px;
}

.v-kcfi4jg {
  stop-color: var(--svg-color--60105f, #60105F);
}

.vqf9fu8dc {
  fill: var(--svg-color--cfc6dd, #CFC6DD);
  d: path("M2.638 29.425c.553.553 1.45.552 2.003-.002l1.69-1.698l-2.007-1.994l-1.688 1.697a1.414 1.414 0 0 0 .002 1.997");
}

.xl814obuq {
  stop-color: var(--svg-color--ffd459, #FFD459);
}

.xm_bmgbmq {
  stop-color: var(--svg-color--e37a42, #E37A42);
}

.xuewmnbus {
  cx: 19.043px;
  cy: 3.007px;
  r: 0.996px;
}

.y4o24tb9l {
  stop-color: var(--svg-color--ece8f2, #ECE8F2);
  stop-opacity: 0;
}

.z15facg4d {
  fill-rule: evenodd;
  d: path("M25.52 7.74a.99.99 0 0 0-.73-.753a7.4 7.4 0 0 1-1.348-.515a.535.535 0 0 1 0-.97a7.4 7.4 0 0 1 1.348-.514a.99.99 0 0 0 .73-.753c.112-.557.294-1.245.57-1.917a.476.476 0 0 1 .898 0c.276.672.458 1.36.569 1.917a1 1 0 0 0 .73.753c.407.107.847.273 1.342.514c.41.2.41.77 0 .97a7.3 7.3 0 0 1-1.342.515a1 1 0 0 0-.73.752a10.6 10.6 0 0 1-.57 1.918a.476.476 0 0 1-.897 0a10.7 10.7 0 0 1-.57-1.918");
}

</style>
