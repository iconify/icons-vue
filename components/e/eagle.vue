<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVHyeUc)"><path class="qtf8se6cv"/><path fill="url(#iMQLtFd)" class="yg6fx-dhn"/><path fill="url(#i9DRxGC)" class="yg6fx-dhn"/><path fill="url(#i60K2oc)" class="yg6fx-dhn"/><path fill="url(#iwSl8Ge)" class="yg6fx-dhn"/></g><g filter="url(#ie0YHnt)"><path class="l5v7qd0ky"/><path fill="url(#iRIA4Db)" class="l3hxsibvk"/><path fill="url(#idNmned)" class="l3hxsibvk"/><path fill="url(#ip85pFe)" class="l3hxsibvk"/><path fill="url(#i6dNPad)" class="l3hxsibvk"/></g><path fill="url(#i52NRiz)" class="i3xjn5iyy"/><path fill="url(#iCJp9Mc)" class="i3xjn5iyy"/><path fill="url(#i0OFhZd)" class="i3xjn5iyy"/><path fill="url(#i6jFYKd)" class="i3xjn5iyy"/><path fill="url(#iKQ3C9g)" class="pulmdibbu"/><path fill="url(#ijF0vnb)" class="pulmdibbu"/><path fill="url(#i3frVyb)" class="pulmdibbu"/><path fill="url(#iarDeVr)" class="r6zgp2nug"/><path fill="url(#iV78g9t)" class="r6zgp2nug"/><path fill="url(#ixSdP4c)" class="r6zgp2nug"/><path fill="url(#iVrIAWc)" class="r6zgp2nug"/><path fill="url(#iGVQvZd)" class="fx2nzjcst"/><path fill="url(#iOFlRyc)" class="fx2nzjcst"/><path fill="url(#i5Y6gcj)" class="fx2nzjcst"/><path fill="url(#iV5viIb)" class="fx2nzjcst"/><path class="c3qx02b4u"/><path fill="url(#imuc3de)" class="l0cwam9ma"/><path fill="url(#i1dgGxd)" class="l0cwam9ma"/><path fill="url(#iXENl3b)" class="u1_-hlhpq"/><path fill="url(#ivl5VNc)" class="u1_-hlhpq"/><path fill="url(#iRZ5nob)" class="u1_-hlhpq"/><path class="e8is4sr8j"/><path fill="url(#iGpP8Kd)" class="wewvs8bsq"/><path fill="url(#i3iK5kc)" class="wewvs8bsq"/><path fill="url(#ihmo3se)" class="wewvs8bsq"/><path fill="url(#iNn1uUd)" class="wewvs8bsq"/><path fill="url(#iM60Z5d)" class="wewvs8bsq"/><circle fill="url(#ijWByMd)" class="zdv0ck2zo"/><circle fill="url(#ianHJve)" class="zdv0ck2zo"/><circle fill="url(#iuwXhcz)" class="zdv0ck2zo"/><g filter="url(#iwycpkd)"><path stroke="url(#ih0yzJb)" class="a81i2bukk"/></g><g filter="url(#i1Vln5c)"><path stroke="url(#iNN0Nwc)" class="ifsafdjro"/></g><defs><linearGradient id="i9DRxGC" x1="6.212" x2="6.212" y1="18.006" y2="15.287" gradientUnits="userSpaceOnUse"><stop class="o8-efgbgc"/><stop offset="1" class="c5h6t3bns"/></linearGradient><linearGradient id="iwSl8Ge" x1="2.775" x2="4.275" y1="13.943" y2="13.943" gradientUnits="userSpaceOnUse"><stop class="o8-efgbgc"/><stop offset="1" class="c5h6t3bns"/></linearGradient><linearGradient id="iRIA4Db" x1="25.275" x2="24.931" y1="23.506" y2="23.771" gradientUnits="userSpaceOnUse"><stop class="wni6yvbjd"/><stop offset="1" class="dv73v-c6f"/></linearGradient><linearGradient id="idNmned" x1="26.337" x2="24.712" y1="22.943" y2="24.131" gradientUnits="userSpaceOnUse"><stop class="wni6yvbjd"/><stop offset="1" class="dv73v-c6f"/></linearGradient><linearGradient id="i52NRiz" x1="4.002" x2="2.998" y1="11.193" y2="18.381" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="iCJp9Mc" x1="3.275" x2=".104" y1="14.881" y2="16.397" gradientUnits="userSpaceOnUse"><stop class="zo6wqobsc"/><stop offset="1" class="nv9o9f28q"/></linearGradient><linearGradient id="i0OFhZd" x1="3.447" x2="3.775" y1="15.74" y2="16.256" gradientUnits="userSpaceOnUse"><stop offset=".262" class="zfx9uybhe"/><stop offset="1" class="abvy8cc9l"/></linearGradient><linearGradient id="iKQ3C9g" x1="20.676" x2="20.676" y1="9.881" y2="14.076" gradientUnits="userSpaceOnUse"><stop class="ms1bjddpl"/><stop offset="0" class="jf17tjoga"/><stop offset="1" class="yrciheb-f"/></linearGradient><linearGradient id="ijF0vnb" x1="20.674" x2="20.674" y1="13.068" y2="14.076" gradientUnits="userSpaceOnUse"><stop class="b7kmcsbqk"/><stop offset="1" class="t6ft7gbhk"/></linearGradient><linearGradient id="i3frVyb" x1="20.674" x2="20.674" y1="15.986" y2="14.89" gradientUnits="userSpaceOnUse"><stop class="b7kmcsbqk"/><stop offset=".857" class="t6ft7gbhk"/></linearGradient><linearGradient id="iarDeVr" x1="22.056" x2="22.059" y1="6.381" y2="12.006" gradientUnits="userSpaceOnUse"><stop class="ms1bjddpl"/><stop offset="0" class="jf17tjoga"/><stop offset="1" class="yrciheb-f"/></linearGradient><linearGradient id="iV78g9t" x1="22.056" x2="22.056" y1="10.474" y2="12.334" gradientUnits="userSpaceOnUse"><stop class="p0mcogbrs"/><stop offset="1" class="h4si79bgu"/></linearGradient><linearGradient id="ixSdP4c" x1="22.056" x2="22.056" y1="10.053" y2="11.336" gradientUnits="userSpaceOnUse"><stop class="b7kmcsbqk"/><stop offset="1" class="t6ft7gbhk"/></linearGradient><linearGradient id="iVrIAWc" x1="22.056" x2="22.056" y1="13.555" y2="12.281" gradientUnits="userSpaceOnUse"><stop class="b7kmcsbqk"/><stop offset=".857" class="t6ft7gbhk"/></linearGradient><linearGradient id="iGVQvZd" x1="23.12" x2="23.12" y1="5.738" y2="10.196" gradientUnits="userSpaceOnUse"><stop class="ms1bjddpl"/><stop offset="0" class="jf17tjoga"/><stop offset="1" class="yrciheb-f"/></linearGradient><linearGradient id="iOFlRyc" x1="23.117" x2="23.117" y1="5.037" y2="7.287" gradientUnits="userSpaceOnUse"><stop class="knsp86bsw"/><stop offset="1" class="gfvx0fzpv"/></linearGradient><linearGradient id="i5Y6gcj" x1="23.117" x2="23.117" y1="5.951" y2="6.685" gradientUnits="userSpaceOnUse"><stop class="ms1bjddpl"/><stop offset="0" class="jf17tjoga"/><stop offset="1" class="j0-n0zq4n"/></linearGradient><linearGradient id="iV5viIb" x1="23.117" x2="23.117" y1="10.724" y2="9.224" gradientUnits="userSpaceOnUse"><stop class="b7kmcsbqk"/><stop offset=".857" class="t6ft7gbhk"/></linearGradient><linearGradient id="imuc3de" x1="15.947" x2="10.681" y1="22.006" y2="22.006" gradientUnits="userSpaceOnUse"><stop class="dtq8g-but"/><stop offset=".89" class="aov_xibmj"/></linearGradient><linearGradient id="i1dgGxd" x1="9.337" x2="11.759" y1="18.99" y2="20.459" gradientUnits="userSpaceOnUse"><stop class="sujj4kbdy"/><stop offset="1" class="ot4zgac4x"/></linearGradient><linearGradient id="iXENl3b" x1="4.494" x2="11.618" y1="27.881" y2="22.006" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset=".833" class="h66atab_c"/></linearGradient><linearGradient id="iuwXhcz" x1="5.395" x2="5.051" y1="13.129" y2="12.91" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ih0yzJb" x1="19.771" x2="17.588" y1="8.221" y2="8.576" gradientUnits="userSpaceOnUse"><stop class="zm698cfoa"/><stop offset="1" class="pagryhbrq"/></linearGradient><linearGradient id="iNN0Nwc" x1="9.466" x2="8.408" y1="21.935" y2="22.326" gradientUnits="userSpaceOnUse"><stop class="kw03dgb7e"/><stop offset="1" class="mtbk1u1il"/></linearGradient><radialGradient id="iMQLtFd" cx="0" cy="0" r="1" gradientTransform="rotate(2.241 -326.695 180.455)scale(7.193 2.86392)" gradientUnits="userSpaceOnUse"><stop class="nbk57acpg"/><stop offset="1" class="p5u5jac_z"/></radialGradient><radialGradient id="i60K2oc" cx="0" cy="0" r="1" gradientTransform="rotate(-170.44 6.523 6.727)scale(3.01056 4.84979)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="o8-efgbgc"/><stop offset="1" class="c5h6t3bns"/></radialGradient><radialGradient id="ip85pFe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 3.14064 -1.78775 -2.56154 21.306 20.63)" gradientUnits="userSpaceOnUse"><stop class="eikz5h0js"/><stop offset="1" class="t8gq85g8l"/></radialGradient><radialGradient id="i6dNPad" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 1.28126 -.54203 -1.81114 21.837 20.756)" gradientUnits="userSpaceOnUse"><stop class="eikz5h0js"/><stop offset="1" class="t8gq85g8l"/></radialGradient><radialGradient id="i6jFYKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43749 3 -1.14466 -.54848 4.681 11.068)" gradientUnits="userSpaceOnUse"><stop class="w0vau80hf"/><stop offset="1" class="b4mmvi24m"/></radialGradient><radialGradient id="ivl5VNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.78907 -1.27344 2.10672 -1.3054 9.15 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="h66atab_c"/><stop offset=".789" class="kskw-5bws"/></radialGradient><radialGradient id="iRZ5nob" cx="0" cy="0" r="1" gradientTransform="rotate(-54.702 28.817 5.15)scale(5.24562 5.93331)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="zo6wqobsc"/><stop offset="1" class="nv9o9f28q"/></radialGradient><radialGradient id="iGpP8Kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3125 10.9376 0 16.868 22.88)" gradientUnits="userSpaceOnUse"><stop class="noisewb0i"/><stop offset="1" class="biicfd-ue"/></radialGradient><radialGradient id="i3iK5kc" cx="0" cy="0" r="1" gradientTransform="matrix(-7 0 0 -6.57075 20.744 11.193)" gradientUnits="userSpaceOnUse"><stop class="com-r8b4r"/><stop offset=".954" class="kem9y_b1m"/></radialGradient><radialGradient id="ihmo3se" cx="0" cy="0" r="1" gradientTransform="rotate(-147.861 14.726 6.49)scale(19.8551 13.9821)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="m8ie4d0kn"/><stop offset="1" class="izenmwf0l"/></radialGradient><radialGradient id="iNn1uUd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.52004 25.306 23.13)" gradientUnits="userSpaceOnUse"><stop class="t2i6jvb_x"/><stop offset="1" class="dxnp8lwoc"/></radialGradient><radialGradient id="iM60Z5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -1.09375 2.92293 3.92508 9.868 18.38)" gradientUnits="userSpaceOnUse"><stop class="iu6so_hge"/><stop offset=".784" class="op5twlbaa"/></radialGradient><radialGradient id="ijWByMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 5.642 13.361)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="ianHJve" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 .245 7.799)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><filter id="iVHyeUc" width="8.438" height="5.15" x="1.994" y="11.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.345098 0 0 0 0 0.431373 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4951"/></filter><filter id="ie0YHnt" width="7.735" height="4.506" x="18.312" y="21.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.627451 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4951"/></filter><filter id="iwycpkd" width=".8" height="9.628" x="18.437" y="6.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4951" stdDeviation=".15"/></filter><filter id="i1Vln5c" width="1.936" height=".609" x="8.358" y="21.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4951" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eagle" /></template>
<style>
.a81i2bukk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.837 6.412v8.828");
}

.abvy8cc9l {
  stop-color: var(--svg-color--a86717, #A86717);
}

.aov_xibmj {
  stop-color: var(--svg-color--7c3d3d, #7C3D3D);
  stop-opacity: 0;
}

.b4mmvi24m {
  stop-color: var(--svg-color--ffe768, #FFE768);
  stop-opacity: 0;
}

.b7kmcsbqk {
  stop-color: var(--svg-color--83443e, #83443E);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.biicfd-ue {
  stop-color: var(--svg-color--935166, #935166);
  stop-opacity: 0;
}

.c3qx02b4u {
  fill: var(--svg-color--85564a, #85564A);
  d: path("m8.962 22.006l3.031-5l8.25 5z");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.c5h6t3bns {
  stop-color: var(--svg-color--65586e, #65586E);
  stop-opacity: 0;
}

.com-r8b4r {
  stop-color: var(--svg-color--daa18f, #DAA18F);
}

.dtq8g-but {
  stop-color: var(--svg-color--7c3d3d, #7C3D3D);
}

.dv73v-c6f {
  stop-color: var(--svg-color--fcfbff, #FCFBFF);
  stop-opacity: 0;
}

.dxnp8lwoc {
  stop-color: var(--svg-color--a1675e, #A1675E);
  stop-opacity: 0;
}

.e8is4sr8j {
  fill: var(--svg-color--be7c6e, #BE7C6E);
  d: path("m19.305 15.615l4.742 5.985a.25.25 0 0 1-.194.406h-6.364c-5.052 0-8.489-3.578-8.489-7.99s3.43-7.99 8.489-7.99h1.816z");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.eikz5h0js {
  stop-color: var(--svg-color--9b8aa5, #9B8AA5);
}

.ft5dv1b6b {
  fill: none;
}

.fx2nzjcst {
  d: path("M26.064 10.196h-9.04c-.75 0-1.25-.79-.92-1.47l1.3-2.7h12.83c.01 2.3-1.86 4.17-4.17 4.17");
}

.gfvx0fzpv {
  stop-color: var(--svg-color--cb9c8b, #CB9C8B);
  stop-opacity: 0;
}

.h4si79bgu {
  stop-color: var(--svg-color--9e716f, #9E716F);
  stop-opacity: 0;
}

.h66atab_c {
  stop-color: var(--svg-color--f89c20, #F89C20);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i3xjn5iyy {
  d: path("M4.002 16.006s-.796.567-1.298.851c-.501.285-.71.288-.71-.851c0-2.391 1.471-3.666 1.998-4.047z");
}

.ifsafdjro {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.533 22.326c.208-.151.867-.43 1.585-.117");
}

.iu6so_hge {
  stop-color: var(--svg-color--ab8c8b, #AB8C8B);
}

.izenmwf0l {
  stop-color: var(--svg-color--cf917c, #CF917C);
}

.j0-n0zq4n {
  stop-color: var(--svg-color--c39184, #C39184);
  stop-opacity: 0;
}

.jf17tjoga {
  stop-color: var(--svg-color--c08e82, #C08E82);
}

.kem9y_b1m {
  stop-color: var(--svg-color--daa18f, #DAA18F);
  stop-opacity: 0;
}

.knsp86bsw {
  stop-color: var(--svg-color--cb9c8b, #CB9C8B);
}

.kskw-5bws {
  stop-color: var(--svg-color--f89c20, #F89C20);
  stop-opacity: 0;
}

.kw03dgb7e {
  stop-color: var(--svg-color--eaae5e, #EAAE5E);
}

.l0cwam9ma {
  d: path("m8.962 22.006l3.031-5l8.25 5z");
}

.l3hxsibvk {
  d: path("M25.9 24.49c.453.625-.208 1.484-1.078 1.484h-2.735c-2.906 0-4.093-2.359-3.703-4.292l5.266-.114z");
}

.l5v7qd0ky {
  fill: var(--svg-color--d0cbd5, #D0CBD5);
  d: path("M25.9 24.49c.453.625-.208 1.484-1.078 1.484h-2.735c-2.906 0-4.093-2.359-3.703-4.292l5.266-.114z");
}

.lr_grnbee {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
}

.m8ie4d0kn {
  stop-color: var(--svg-color--cf917c, #CF917C);
  stop-opacity: 0;
}

.ms1bjddpl {
  stop-color: var(--svg-color--c39184, #C39184);
}

.mtbk1u1il {
  stop-color: var(--svg-color--eaae5e, #EAAE5E);
  stop-opacity: 0;
}

.nbk57acpg {
  stop-color: var(--svg-color--f7f6fa, #F7F6FA);
}

.noisewb0i {
  stop-color: var(--svg-color--935166, #935166);
}

.nv9o9f28q {
  stop-color: var(--svg-color--b17a36, #B17A36);
}

.o8-efgbgc {
  stop-color: var(--svg-color--65586e, #65586E);
}

.op5twlbaa {
  stop-color: var(--svg-color--ab8c8b, #AB8C8B);
  stop-opacity: 0;
}

.ot4zgac4x {
  stop-color: var(--svg-color--93756d, #93756D);
  stop-opacity: 0;
}

.p0mcogbrs {
  stop-color: var(--svg-color--9e716f, #9E716F);
}

.p5u5jac_z {
  stop-color: var(--svg-color--f7f6fa, #F7F6FA);
  stop-opacity: 0;
}

.pagryhbrq {
  stop-color: var(--svg-color--ddaa9a, #DDAA9A);
  stop-opacity: 0;
}

.pulmdibbu {
  d: path("M22.344 15.6h-5.12c-.79 0-1.25-.784-.78-1.424l.88-1.623h7.77c0 1.906-1.679 3.046-2.75 3.046");
}

.qtf8se6cv {
  fill: var(--svg-color--b5b1bb, #B5B1BB);
  d: path("M9.154 16.006h-7.16c0-2.768 2.18-5 4.86-5h3.577v5z");
}

.r6zgp2nug {
  d: path("M24.444 13.106h-7.27c-.79 0-1.29-.86-.9-1.55l1.13-1.99h10.57c0 1.96-1.58 3.54-3.53 3.54");
}

.sujj4kbdy {
  stop-color: var(--svg-color--93756d, #93756D);
}

.t2i6jvb_x {
  stop-color: var(--svg-color--a1675e, #A1675E);
}

.t6ft7gbhk {
  stop-color: var(--svg-color--83443e, #83443E);
  stop-opacity: 0;
}

.t8gq85g8l {
  stop-color: var(--svg-color--9b8aa5, #9B8AA5);
  stop-opacity: 0;
}

.u1_-hlhpq {
  d: path("M8.634 22.584c.625-.367 1.484-.303 1.953.297c.176.225.426.04.405-.14a2 2 0 0 0-.125-.451c-.314-.747-1.026-1.273-1.832-1.284a2.01 2.01 0 0 0-2.041 2.02c0 .526.198.95.523 1.308c.126.137.401-.017.36-.196c-.118-.5.152-1.199.757-1.554");
}

.w0vau80hf {
  stop-color: var(--svg-color--ffe768, #FFE768);
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.wewvs8bsq {
  d: path("m19.305 15.615l4.742 5.985a.25.25 0 0 1-.194.406h-6.364c-5.052 0-8.489-3.578-8.489-7.99s3.43-7.99 8.489-7.99h1.816z");
}

.wni6yvbjd {
  stop-color: var(--svg-color--fcfbff, #FCFBFF);
}

.yg6fx-dhn {
  d: path("M9.154 16.006h-7.16c0-2.768 2.18-5 4.86-5h3.577v5z");
}

.yrciheb-f {
  stop-color: var(--svg-color--a16c6b, #A16C6B);
}

.zdv0ck2zo {
  cx: 5.494px;
  cy: 13.521px;
  r: 0.5px;
}

.zfx9uybhe {
  stop-color: var(--svg-color--a86717, #A86717);
  stop-opacity: 0;
}

.zm698cfoa {
  stop-color: var(--svg-color--ddaa9a, #DDAA9A);
}

.zo6wqobsc {
  stop-color: var(--svg-color--bc7824, #BC7824);
  stop-opacity: 0;
}

</style>
