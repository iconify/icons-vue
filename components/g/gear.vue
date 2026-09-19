<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVY7Nub)" clip-rule="evenodd" class="d_obcez9o"/><g filter="url(#iCOouPc)"><path fill="url(#iVY7Nub)" clip-rule="evenodd" class="d_obcez9o"/></g><g clip-rule="evenodd" filter="url(#io73F4d)" class="d2kvgvbvc"><path fill="url(#iaIuSLe)" class="unfte5bjb"/><path fill="url(#ib2jF0b)" class="unfte5bjb"/></g><g filter="url(#iwo5CBc)"><path fill="url(#iBMWJ5c)" clip-rule="evenodd" class="udcu52bsg"/></g><g filter="url(#iEDNAwe)"><path fill="url(#iw1K3Eb)" clip-rule="evenodd" class="ztzf-kb_x"/></g><path fill="url(#icKvKCe)" clip-rule="evenodd" class="h4ogyobzt"/><path fill="url(#iFhj3Wc)" clip-rule="evenodd" class="h4ogyobzt"/><path fill="url(#iJUe0Cd)" clip-rule="evenodd" class="c__hqcbfq"/><path fill="url(#iqjQ2qb)" clip-rule="evenodd" class="c__hqcbfq"/><path fill="url(#iBqY10b)" clip-rule="evenodd" class="c__hqcbfq"/><g filter="url(#i3CNVse)"><path stroke="url(#i5cH72Y)" clip-rule="evenodd" class="j0t9qfc1n"/></g><defs><radialGradient id="ib2jF0b" cx="0" cy="0" r="1" gradientTransform="rotate(26.764 -19.776 25.385)scale(4.02495 11.1436)" gradientUnits="userSpaceOnUse"><stop class="lm6lfbb5h"/><stop offset="1" class="khixgbbyc"/></radialGradient><radialGradient id="iBMWJ5c" cx="0" cy="0" r="1" gradientTransform="rotate(133.81 8.106 10.049)scale(14.8967 19.4343)" gradientUnits="userSpaceOnUse"><stop offset=".033" class="xqw4a_bvl"/><stop offset="1" class="zxzyy0bjc"/></radialGradient><radialGradient id="icKvKCe" cx="0" cy="0" r="1" gradientTransform="rotate(128.71 7.15 11.297)scale(11.1432)" gradientUnits="userSpaceOnUse"><stop class="jc1qqjj7q"/><stop offset="1" class="jvpel3vfy"/></radialGradient><radialGradient id="iFhj3Wc" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 2.875 -5.7957 9.07155 11.188 12.969)" gradientUnits="userSpaceOnUse"><stop class="x31hgxn9z"/><stop offset="1" class="r5cane1gn"/></radialGradient><radialGradient id="iJUe0Cd" cx="0" cy="0" r="1" gradientTransform="rotate(136.338 7.205 10.393)scale(9.46013 9.40439)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="v-nhmib3d"/><stop offset="1" class="dill2nbgb"/></radialGradient><radialGradient id="iqjQ2qb" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 -3.5 5.56387 5.46451 12.063 19.688)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="p_4m9dopq"/><stop offset="1" class="plwplwbzk"/></radialGradient><radialGradient id="iBqY10b" cx="0" cy="0" r="1" gradientTransform="matrix(2.71874 3.15625 -5.60325 4.82653 12.78 11.656)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="w4nz4jbem"/><stop offset="1" class="ftk3pbb7a"/></radialGradient><radialGradient id="i5cH72Y" cx="0" cy="0" r="1" gradientTransform="rotate(152.789 8.673 10.312)scale(6.85944 6.79772)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="ybun_acyk"/><stop offset="1" class="mybj23g1z"/></radialGradient><filter id="iCOouPc" width="28.064" height="27.994" x="1.968" y="2.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.533333 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24453"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.941176 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_24453" result="effect2_innerShadow_18_24453"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.6 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_24453" result="effect3_innerShadow_18_24453"/></filter><filter id="io73F4d" width="17.281" height="17.281" x="7.359" y="7.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24453" stdDeviation=".25"/></filter><filter id="iwo5CBc" width="16.039" height="16.039" x="8.105" y="7.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.521569 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24453"/></filter><filter id="iEDNAwe" width="11.216" height="11.216" x="10.392" y="10.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24453" stdDeviation=".05"/></filter><filter id="i3CNVse" width="10.175" height="10.175" x="10.912" y="10.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24453" stdDeviation=".05"/></filter><linearGradient id="iVY7Nub" x1="25.813" x2="6.125" y1="6.063" y2="25.688" gradientUnits="userSpaceOnUse"><stop class="kb8ta3r1w"/><stop offset="1" class="ncea8rfjm"/></linearGradient><linearGradient id="iaIuSLe" x1="21" x2="13.594" y1="9.445" y2="23.938" gradientUnits="userSpaceOnUse"><stop class="rk92qc38n"/><stop offset=".837" class="uf670fl3f"/></linearGradient><linearGradient id="iw1K3Eb" x1="18.906" x2="16" y1="11" y2="21.516" gradientUnits="userSpaceOnUse"><stop class="t13r1n5ec"/><stop offset="1" class="a5iyz47ze"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:gear" /></template>
<style>
.a5iyz47ze {
  stop-color: var(--svg-color--9888ac, #9888AC);
}

.c__hqcbfq {
  fill-rule: evenodd;
  d: path("M16 20.945a4.938 4.938 0 1 0 0-9.875a4.938 4.938 0 0 0 0 9.875m4.328-4.937a4.328 4.328 0 1 1-8.656 0a4.328 4.328 0 0 1 8.656 0");
}

.d_obcez9o {
  fill-rule: evenodd;
  d: path("M12.874 6.62c-.054.634-.82.952-1.307.54c-.636-.54-1.311-1.067-1.813-1.348c-1.362-.765-2.179-.915-3.497.37l-.035.036l-.02.02l-.016.016C4.902 7.572 5.05 8.388 5.816 9.75c.284.508.82 1.192 1.366 1.835c.413.486.095 1.255-.541 1.307c-.84.069-1.702.174-2.262.33c-1.504.423-2.187.895-2.211 2.735v.102c.024 1.84.707 2.312 2.21 2.734c.552.155 1.398.259 2.226.328c.635.053.953.82.541 1.306c-.532.63-1.051 1.296-1.33 1.791c-.765 1.362-.913 2.179.371 3.497l.016.017l.02.02l.035.035c1.318 1.284 2.135 1.135 3.497.37c.508-.285 1.194-.823 1.838-1.37c.487-.412 1.255-.094 1.307.542c.07.84.174 1.704.332 2.265c.422 1.504.894 2.187 2.734 2.21h.101c1.84-.024 2.313-.706 2.735-2.21c.153-.546.256-1.379.325-2.198c.054-.635.82-.952 1.307-.54c.636.539 1.311 1.066 1.813 1.348c1.362.765 2.178.914 3.497-.37l.035-.036l.012-.012l.008-.008l.016-.016c1.284-1.318 1.136-2.135.37-3.497c-.284-.507-.82-1.192-1.366-1.834c-.413-.487-.095-1.255.541-1.307c.84-.07 1.702-.174 2.262-.331c1.504-.422 2.187-.894 2.211-2.734v-.102c-.024-1.84-.707-2.312-2.21-2.734c-.552-.155-1.398-.259-2.226-.328c-.635-.053-.953-.82-.541-1.306c.532-.63 1.051-1.296 1.33-1.792c.765-1.362.913-2.178-.371-3.496l-.016-.017l-.02-.02l-.035-.035c-1.319-1.285-2.135-1.136-3.497-.37c-.508.285-1.194.823-1.838 1.37c-.487.412-1.255.094-1.308-.542c-.069-.84-.173-1.705-.33-2.265c-.422-1.504-.895-2.187-2.735-2.211h-.101c-1.84.024-2.313.707-2.735 2.21c-.153.546-.256 1.38-.325 2.198m3.122 14.794a5.406 5.406 0 1 0 0-10.812a5.406 5.406 0 0 0 0 10.812");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dill2nbgb {
  stop-color: var(--svg-color--ada4bb, #ADA4BB);
}

.ft5dv1b6b {
  fill: none;
}

.ftk3pbb7a {
  stop-color: var(--svg-color--a294b3, #A294B3);
  stop-opacity: 0;
}

.h4ogyobzt {
  fill-rule: evenodd;
  d: path("M16 21.477a5.469 5.469 0 1 0 0-10.938a5.469 5.469 0 0 0 0 10.938m0-1.141a4.328 4.328 0 1 0 0-8.656a4.328 4.328 0 0 0 0 8.656");
}

.j0t9qfc1n {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16 20.945a4.938 4.938 0 1 0 0-9.875a4.938 4.938 0 0 0 0 9.875Z");
}

.jc1qqjj7q {
  stop-color: var(--svg-color--e6e0f1, #E6E0F1);
}

.jvpel3vfy {
  stop-color: var(--svg-color--a89aba, #A89ABA);
}

.kb8ta3r1w {
  stop-color: var(--svg-color--ded7eb, #DED7EB);
}

.khixgbbyc {
  stop-color: var(--svg-color--908b9a, #908B9A);
  stop-opacity: 0;
}

.lm6lfbb5h {
  stop-color: var(--svg-color--908b9a, #908B9A);
}

.mybj23g1z {
  stop-color: var(--svg-color--a197af, #A197AF);
}

.ncea8rfjm {
  stop-color: var(--svg-color--c1b4d6, #C1B4D6);
}

.p_4m9dopq {
  stop-color: var(--svg-color--bcb6c4, #BCB6C4);
}

.plwplwbzk {
  stop-color: var(--svg-color--bcb6c4, #BCB6C4);
  stop-opacity: 0;
}

.r5cane1gn {
  stop-color: var(--svg-color--90899a, #90899A);
  stop-opacity: 0;
}

.rk92qc38n {
  stop-color: var(--svg-color--d0ccd9, #D0CCD9);
}

.t13r1n5ec {
  stop-color: var(--svg-color--aea9b7, #AEA9B7);
}

.udcu52bsg {
  fill-rule: evenodd;
  d: path("M16 23.902a7.895 7.895 0 1 0 0-15.789a7.895 7.895 0 0 0 0 15.79m0-3.043a4.852 4.852 0 1 0 0-9.703a4.852 4.852 0 0 0 0 9.703");
}

.uf670fl3f {
  stop-color: var(--svg-color--a38ebe, #A38EBE);
}

.unfte5bjb {
  d: path("M16 24.148a8.14 8.14 0 1 0 0-16.28a8.14 8.14 0 0 0 0 16.28m0-3.137a5.003 5.003 0 1 0 0-10.006a5.003 5.003 0 0 0 0 10.006");
}

.v-nhmib3d {
  stop-color: var(--svg-color--c9bfd7, #C9BFD7);
}

.w4nz4jbem {
  stop-color: var(--svg-color--a294b3, #A294B3);
}

.x31hgxn9z {
  stop-color: var(--svg-color--90899a, #90899A);
}

.xqw4a_bvl {
  stop-color: var(--svg-color--e5dff0, #E5DFF0);
}

.ybun_acyk {
  stop-color: var(--svg-color--ccc3da, #CCC3DA);
}

.ztzf-kb_x {
  fill-rule: evenodd;
  d: path("M16 21.516A5.508 5.508 0 1 0 16 10.5a5.508 5.508 0 0 0 0 11.016m4.852-5.508a4.852 4.852 0 1 1-9.704 0a4.852 4.852 0 0 1 9.704 0");
}

.zxzyy0bjc {
  stop-color: var(--svg-color--9b8bae, #9B8BAE);
}

</style>
