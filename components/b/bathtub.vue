<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTZL77b)"><path class="pmrojcb0t"/><path fill="url(#irrp5Ed)" class="n5iugdc7e"/></g><g filter="url(#imHPhVc)"><path class="dneuw6giq"/><path fill="url(#i9HXenb)" class="ffs2b3ucu"/><path fill="url(#iqqmMPd)" class="ffs2b3ucu"/></g><g filter="url(#iRAvVFb)"><circle fill="url(#it7Hcgb)" class="l9be9cbeu"/><circle fill="url(#i1VHmBe)" class="l9be9cbeu"/></g><g filter="url(#i9Zey4b)"><path fill="url(#ios98de)" class="xu4wycc3o"/></g><rect fill="url(#ixjY1Nd)" transform="scale(-1 1)rotate(45 -41.25 -12.23)" class="ar8i_6cng"/><rect fill="url(#iTGpFUm)" transform="scale(-1 1)rotate(45 -41.25 -12.23)" class="ar8i_6cng"/><rect fill="url(#igtqYuT)" transform="scale(-1 1)rotate(45 -41.25 -12.23)" class="ar8i_6cng"/><rect transform="rotate(45 11.302 25.587)" class="x9b-ogb5r"/><rect fill="url(#i8ZlVUc)" transform="rotate(45 11.302 25.587)" class="hc7uehc1j"/><rect fill="url(#i3mZVnc)" transform="rotate(45 11.302 25.587)" class="hc7uehc1j"/><g filter="url(#iLbgJcb)"><path fill="url(#iAo6ESc)" class="wx5cr8b5e"/></g><path fill="url(#iO5uQuc)" class="wx5cr8b5e"/><path fill="url(#ir4YMwc)" class="wx5cr8b5e"/><g filter="url(#i84PNhd)"><rect fill="url(#iwPYmlD)" class="izprwoauh"/><rect fill="url(#ib6SVuc)" class="izprwoauh"/></g><rect fill="url(#iBXidhb)" class="izprwoauh"/><g filter="url(#iOaO5Wb)"><path stroke="url(#isRpzPe)" class="y95uy1mam"/></g><g filter="url(#i9sq5De)"><path stroke="url(#ip7mFSc)" class="t85a6ccea"/></g><path fill="url(#it279Hd)" class="x6vcpr0uv"/><path fill="url(#iQD1nac)" class="x6vcpr0uv"/><defs><radialGradient id="irrp5Ed" cx="0" cy="0" r="1" gradientTransform="matrix(4.82608 -4.88916 2.76518 2.7295 17.95 6.5)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="i9HXenb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8272 -2.12197 2.55378 -4.606 23.033 14.902)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="iqqmMPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28834 3.183 -1.80064 .72882 16.023 12.325)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="it7Hcgb" cx="0" cy="0" r="1" gradientTransform="rotate(-126.561 12.5 2.98)scale(3.86844 3.1722)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="i1VHmBe" cx="0" cy="0" r="1" gradientTransform="rotate(-60.751 19.578 -3.214)scale(3.25724 2.78766)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="ios98de" cx="0" cy="0" r="1" gradientTransform="matrix(-3.82673 -3.36565 2.9361 -3.33833 13.153 13.993)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iTGpFUm" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.583 1.488)scale(1.63904 1.78477)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="igtqYuT" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.48 1.993)scale(1.44735 .75237)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="i3mZVnc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.581 2.226)scale(.69503 1.07891)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="iAo6ESc" cx="0" cy="0" r="1" gradientTransform="rotate(-179.764 12.74 11.187)scale(15.6539 10.0079)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="iO5uQuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.91263 -39.3859 0 16.506 19.391)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="p1kfrabgo"/><stop offset=".941" class="mg_zulb9j"/></radialGradient><radialGradient id="iwPYmlD" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.29169 -15.4043 0 24.605 16.27)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="isRpzPe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.78172 10.28306 -7.22346 -4.7639 28.17 3.881)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="ip7mFSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.51407 -3.56436 2.72322 1.15677 18.988 6.862)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="it279Hd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.57669 0 0 -3.59203 20.106 8.92)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="iTZL77b" width="9.206" height="15.643" x="17.225" y="1.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25912"/></filter><filter id="imHPhVc" width="17.899" height="7.806" x="5.943" y="11.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.713726 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25912"/></filter><filter id="iRAvVFb" width="6.556" height="6.556" x="11.97" y="12.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25912" stdDeviation=".25"/></filter><filter id="i9Zey4b" width="7.476" height="7.651" x="6.182" y="11.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25912" stdDeviation=".25"/></filter><filter id="iLbgJcb" width="28.728" height="11.334" x="3.084" y="16.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25912"/></filter><filter id="i84PNhd" width="28.18" height="2.571" x="2.16" y="15.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25912"/></filter><filter id="iOaO5Wb" width="5.082" height="14.641" x="21.125" y="2.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25912" stdDeviation=".25"/></filter><filter id="i9sq5De" width="3.012" height="4.498" x="17.419" y="2.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25912" stdDeviation=".25"/></filter><linearGradient id="ixjY1Nd" x1="1.696" x2="-.12" y1="3.06" y2="3.277" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="i8ZlVUc" x1="10.977" x2="12.575" y1="29.206" y2="28.955" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="ir4YMwc" x1="15.949" x2="15.949" y1="17.776" y2="19.23" gradientUnits="userSpaceOnUse"><stop class="pk-xybc5s"/><stop offset="1" class="fymxclbyn"/></linearGradient><linearGradient id="ib6SVuc" x1="2.362" x2="11.558" y1="16.884" y2="16.884" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="iBXidhb" x1="17.336" x2="17.336" y1="17.825" y2="17.272" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="iQD1nac" x1="18.86" x2="18.86" y1="8.92" y2="8.408" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bathtub" /></template>
<style>
.ar8i_6cng {
  width: 1.662px;
  height: 5.303px;
  rx: 0.804px;
}

.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
}

.dneuw6giq {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M9.846 19.108a3.9 3.9 0 0 0 3.28-1.788a3.02 3.02 0 0 0 2.01.746c.8 0 1.524-.297 2.046-.777c.62.746 1.7 1.241 2.928 1.241c1.923 0 3.482-1.21 3.482-2.704c0-1.275-1.56-2.705-3.482-2.705c-.957 0-1.824.3-2.453.785a.13.13 0 0 1-.18-.022c-.525-.663-1.377-1.095-2.34-1.095c-.644 0-1.239.193-1.718.52a.13.13 0 0 1-.185-.043a3.903 3.903 0 1 0-3.388 5.842");
}

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.ffs2b3ucu {
  d: path("M9.846 19.108a3.9 3.9 0 0 0 3.28-1.788a3.02 3.02 0 0 0 2.01.746c.8 0 1.524-.297 2.046-.777c.62.746 1.7 1.241 2.928 1.241c1.923 0 3.482-1.21 3.482-2.704c0-1.275-1.56-2.705-3.482-2.705c-.957 0-1.824.3-2.453.785a.13.13 0 0 1-.18-.022c-.525-.663-1.377-1.095-2.34-1.095c-.644 0-1.239.193-1.718.52a.13.13 0 0 1-.185-.043a3.903 3.903 0 1 0-3.388 5.842");
}

.fgfvt8_za {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
}

.ft5dv1b6b {
  fill: none;
}

.fymxclbyn {
  stop-color: var(--svg-color--c6bcd1, #C6BCD1);
  stop-opacity: 0;
}

.gbuoa-pfp {
  stop-color: var(--svg-color--807d83, #807D83);
}

.go679fbfb {
  stop-color: var(--svg-color--bebac2, #BEBAC2);
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.hc7uehc1j {
  width: 1.662px;
  height: 5.303px;
  x: 11.302px;
  y: 25.587px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.izprwoauh {
  width: 27.68px;
  height: 2.321px;
  x: 2.16px;
  y: 15.504px;
  rx: 1.123px;
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.k3-gog70w {
  stop-color: var(--svg-color--8f9198, #8F9198);
  stop-opacity: 0;
}

.kb1q69u9p {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
  stop-opacity: 0;
}

.kdd3vfboh {
  stop-color: var(--svg-color--66ebff, #66EBFF);
  stop-opacity: 0;
}

.l9be9cbeu {
  cx: 15.248px;
  cy: 15.833px;
  r: 2.778px;
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n5iugdc7e {
  d: path("M24.316 6.468v11.04h1.615V6.468a4.353 4.353 0 0 0-8.706 0v1.04h1.615v-1.04a2.738 2.738 0 1 1 5.476 0");
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p1kfrabgo {
  stop-color: var(--svg-color--b49dca, #B49DCA);
  stop-opacity: 0;
}

.p53pr-blg {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
  stop-opacity: 0;
}

.pk-xybc5s {
  stop-color: var(--svg-color--9e91ad, #9E91AD);
}

.pmrojcb0t {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.316 6.468v11.04h1.615V6.468a4.353 4.353 0 0 0-8.706 0v1.04h1.615v-1.04a2.738 2.738 0 1 1 5.476 0");
}

.t7wbu9b2k {
  stop-color: var(--svg-color--887a96, #887A96);
}

.t85a6ccea {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.682 3.645c-.462.41-1.388 1.627-1.388 3.217");
}

.t9935ox4b {
  stop-color: var(--svg-color--a9a6ac, #A9A6AC);
}

.v7qdu5boj {
  stop-color: var(--svg-color--66ebff, #66EBFF);
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vngbibvro {
  stop-color: var(--svg-color--bbb2c3, #BBB2C3);
  stop-opacity: 0;
}

.vou8iltko {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
  stop-opacity: 0;
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.wx5cr8b5e {
  d: path("m4.55 22.498l-1.466-4.722h25.729l-1.486 4.743c-1.044 3.332-4.062 5.59-7.469 5.59h-7.834c-3.415 0-6.437-2.269-7.475-5.611");
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6vcpr0uv {
  d: path("M20.556 8.92c.281 0 .513-.232.46-.509c-.252-1.319-1.382-2.314-2.74-2.314c-1.357 0-2.487.995-2.74 2.314c-.052.277.18.51.461.51z");
}

.x9b-ogb5r {
  width: 1.662px;
  height: 5.303px;
  x: 11.302px;
  y: 25.587px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.xu4wycc3o {
  d: path("M13.158 13.925a2.8 2.8 0 0 0-1.026 1.974c-.037.502.06.983.26 1.408a3.325 3.325 0 1 1 .766-3.382");
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.y95uy1mam {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M21.64 2.92c1.231-.053 3.691.949 3.691 3.8v9.463");
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

</style>
