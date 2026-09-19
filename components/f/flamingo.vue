<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="eei63za0i"/><path fill="url(#isdOIBc)" class="ldcf9eg3f"/><path fill="url(#imtJ0jc)" class="ldcf9eg3f"/><path fill="url(#i3UfUJd)" class="ldcf9eg3f"/><g filter="url(#i0j1NQd)"><path stroke="url(#i2Lm3me)" class="nkf8idbzm"/></g><path fill="url(#iBh22mc)" class="lt9z-q_zf"/><path fill="url(#inz2qNc)" class="lt9z-q_zf"/><path fill="url(#iaFTzNd)" class="lt9z-q_zf"/><path fill="url(#i5EznSd)" class="qzn7pty-t"/><path fill="url(#iF3Qqpb)" class="qzn7pty-t"/><path fill="url(#iQDdQGb)" class="qzn7pty-t"/><path fill="url(#iDhxQcb)" class="qzn7pty-t"/><path fill="url(#iu3fGQb)" class="qzn7pty-t"/><path fill="url(#issAmtb)" class="qzn7pty-t"/><g filter="url(#ijF3Atb)"><path fill="url(#i5K4PzG)" class="shwoz5eeu"/><path fill="url(#iGEXNNc)" class="dcksmjbjs"/></g><path fill="url(#iA7Cxke)" class="sbjgjh8je"/><path fill="url(#iv7KDHH)" class="sbjgjh8je"/><path fill="url(#iCa8ubJ)" class="sbjgjh8je"/><path fill="url(#iIyAyed)" class="sbjgjh8je"/><path fill="url(#ipSRx6b)" class="ojtbjtt4e"/><path fill="url(#iO9Pwvb)" class="ojtbjtt4e"/><g filter="url(#iidz1vc)"><path fill="url(#iyQIwGe)" class="elqgrdbtw"/></g><path fill="url(#iEp3X2c)" class="kvnxpybqb"/><path fill="url(#iDvdgCP)" class="kvnxpybqb"/><path fill="url(#iNvwZxe)" class="kvnxpybqb"/><path fill="url(#i6BsDhe)" class="lp83_ccwv"/><g filter="url(#igUquMb)"><path stroke="url(#iMAWHJc)" class="woz8p6buf"/></g><g filter="url(#icTgoEe)"><path stroke="url(#iqvfuFd)" class="mkf5xbygz"/></g><g filter="url(#itPDAgp)"><path stroke="url(#iQbEGRd)" class="yu_y3hb1z"/></g><g filter="url(#iq9lKdc)"><path stroke="url(#i7khKdK)" class="a5ea9zb1a"/></g><defs><linearGradient id="isdOIBc" x1="15.888" x2="15.888" y1="18.688" y2="26.219" gradientUnits="userSpaceOnUse"><stop class="jeys61f5c"/><stop offset="1" class="xpnn-p5ul"/></linearGradient><linearGradient id="imtJ0jc" x1="15.794" x2="15.794" y1="30.125" y2="29.586" gradientUnits="userSpaceOnUse"><stop class="phdj8nb9i"/><stop offset="1" class="ml-xt8bjv"/></linearGradient><linearGradient id="i2Lm3me" x1="16.45" x2="19.514" y1="18.531" y2="19.518" gradientUnits="userSpaceOnUse"><stop class="dgh9rabfa"/><stop offset="1" class="r3f_1qtju"/></linearGradient><linearGradient id="iBh22mc" x1="12.794" x2="21.325" y1="23.219" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="mo8s5gznp"/><stop offset="1" class="z0msjc-gh"/></linearGradient><linearGradient id="iaFTzNd" x1="14.95" x2="14.95" y1="24.969" y2="24.344" gradientUnits="userSpaceOnUse"><stop class="ngjk72oaq"/><stop offset="1" class="lh593x5yh"/></linearGradient><linearGradient id="i5EznSd" x1="20.763" x2="9.075" y1="22.875" y2="8.813" gradientUnits="userSpaceOnUse"><stop class="y_rrxd12w"/><stop offset="1" class="k1mlv5qsu"/></linearGradient><linearGradient id="iF3Qqpb" x1="16" x2="16" y1="19.75" y2="15.25" gradientUnits="userSpaceOnUse"><stop class="bznm6rbst"/><stop offset="1" class="faq6zbbof"/></linearGradient><linearGradient id="i5K4PzG" x1="15.606" x2="19.481" y1="9.937" y2="17.156" gradientUnits="userSpaceOnUse"><stop class="wc8spo37w"/><stop offset="1" class="l_ddebamj"/></linearGradient><linearGradient id="iGEXNNc" x1="11.669" x2="18.427" y1="13.604" y2="13.604" gradientUnits="userSpaceOnUse"><stop class="lf1q0ab2s"/><stop offset="1" class="no7qj6zjo"/></linearGradient><linearGradient id="iA7Cxke" x1="23.513" x2="11.075" y1="16" y2="10.688" gradientUnits="userSpaceOnUse"><stop class="a51qohq4n"/><stop offset="1" class="j3gss9bub"/></linearGradient><linearGradient id="ipSRx6b" x1="8.013" x2="8.013" y1="1.578" y2="3.172" gradientUnits="userSpaceOnUse"><stop class="orogzxyau"/><stop offset="1" class="wbw-5rbhd"/></linearGradient><linearGradient id="iyQIwGe" x1="6.372" x2="12.31" y1="3.266" y2="3.266" gradientUnits="userSpaceOnUse"><stop class="prr06vn9p"/><stop offset="1" class="s58ehl94k"/></linearGradient><linearGradient id="iNvwZxe" x1="11.384" x2="11.041" y1="3.107" y2="2.889" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="i6BsDhe" x1="9.513" x2="9.513" y1="2.344" y2="5" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="kgv50-ecn"/></linearGradient><linearGradient id="iMAWHJc" x1="4.856" x2="11.888" y1="11.078" y2="3.984" gradientUnits="userSpaceOnUse"><stop class="dgh9rabfa"/><stop offset=".534" class="r3f_1qtju"/><stop offset="1" class="dgh9rabfa"/></linearGradient><linearGradient id="iqvfuFd" x1="13.763" x2="9.494" y1="13.563" y2="16.53" gradientUnits="userSpaceOnUse"><stop class="dgh9rabfa"/><stop offset="1" class="r3f_1qtju"/></linearGradient><linearGradient id="iQbEGRd" x1="18.794" x2="21.966" y1="20.328" y2="21.526" gradientUnits="userSpaceOnUse"><stop class="b67etybhs"/><stop offset="1" class="xdfta7kgs"/></linearGradient><linearGradient id="i7khKdK" x1=".513" x2="5.608" y1="23.688" y2="29.672" gradientUnits="userSpaceOnUse"><stop class="b67etybhs"/><stop offset="1" class="xdfta7kgs"/></linearGradient><radialGradient id="i3UfUJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.88281 0 0 .59375 14.435 29.047)" gradientUnits="userSpaceOnUse"><stop class="q7ukxorza"/><stop offset="1" class="wiay7zb2f"/></radialGradient><radialGradient id="inz2qNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -2.158 1.78805 18.966 19.047)" gradientUnits="userSpaceOnUse"><stop class="n1-nrtpjs"/><stop offset="1" class="hpgzikbxj"/></radialGradient><radialGradient id="iQDdQGb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18748 2.25002 -5.68805 -8.05794 25.138 12.625)" gradientUnits="userSpaceOnUse"><stop class="b5fom9bjv"/><stop offset="1" class="uhzva39kr"/></radialGradient><radialGradient id="iDhxQcb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34374 1.875 -2.39783 -2.99727 13.669 2.922)" gradientUnits="userSpaceOnUse"><stop class="e10e8j4em"/><stop offset="1" class="xvqd2wbxp"/></radialGradient><radialGradient id="iu3fGQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 0 0 2.10937 9.825 2.984)" gradientUnits="userSpaceOnUse"><stop class="e10e8j4em"/><stop offset="1" class="xvqd2wbxp"/></radialGradient><radialGradient id="issAmtb" cx="0" cy="0" r="1" gradientTransform="rotate(135.44 3.899 6.98)scale(8.64022 1.89996)" gradientUnits="userSpaceOnUse"><stop class="xcxzx2bsk"/><stop offset="1" class="ph9qtnbmj"/></radialGradient><radialGradient id="iv7KDHH" cx="0" cy="0" r="1" gradientTransform="rotate(140.179 9.457 8.85)scale(10.4974 12.1392)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="oeuqzpyuy"/><stop offset="1" class="chqjjfb5a"/></radialGradient><radialGradient id="iCa8ubJ" cx="0" cy="0" r="1" gradientTransform="matrix(-12.93755 12.59749 -9.13502 -9.38162 22.388 9.59)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="m1w9l824e"/><stop offset="1" class="nbbzxxbtq"/></radialGradient><radialGradient id="iIyAyed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.63706 2.375 -6.1597 -4.2458 24.775 15.688)" gradientUnits="userSpaceOnUse"><stop class="mx65styut"/><stop offset="1" class="j3_nw90-v"/></radialGradient><radialGradient id="iO9Pwvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 -.85156 1.91058 -.59596 7.755 5.383)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="s9wis0bdq"/><stop offset="1" class="ul1nowbjb"/></radialGradient><radialGradient id="iEp3X2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 11.631 3.339)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iDvdgCP" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 5.18 3.948)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><filter id="i0j1NQd" width="1.5" height="11.656" x="15.7" y="18.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".3"/></filter><filter id="ijF3Atb" width="13.211" height="10.028" x="11.821" y="8.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".5"/></filter><filter id="iidz1vc" width="4.516" height="4.547" x="5.528" y="1.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".375"/></filter><filter id="igUquMb" width="6.641" height="8.781" x="5.294" y="4.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".25"/></filter><filter id="icTgoEe" width="9.189" height="6.391" x="5.496" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".5"/></filter><filter id="itPDAgp" width="6.988" height="4.706" x="15.175" y="18.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".25"/></filter><filter id="iq9lKdc" width="9.903" height="2.037" x="10.772" y="22.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5165" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flamingo" /></template>
<style>
.a51qohq4n {
  stop-color: var(--svg-color--ffa9b9, #FFA9B9);
}

.a5ea9zb1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.075 22.875H12.31a.937.937 0 0 0-.938.938v0");
}

.b5fom9bjv {
  stop-color: var(--svg-color--ff94d3, #FF94D3);
}

.b67etybhs {
  stop-color: var(--svg-color--ff9fb4, #FF9FB4);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bznm6rbst {
  stop-color: var(--svg-color--d947aa, #D947AA);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.chqjjfb5a {
  stop-color: var(--svg-color--e874a0, #E874A0);
}

.dcksmjbjs {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M24.03 16.9c-.33-4.097-3.434-7.31-7.404-7.31c-2.102 0-3.805 1.797-3.805 4.014s1.703 4.014 3.805 4.014l6.772-.01c.37.01.661-.318.632-.708");
}

.dgh9rabfa {
  stop-color: var(--svg-color--ff91a9, #FF91A9);
  stop-opacity: 0;
}

.e10e8j4em {
  stop-color: var(--svg-color--ff9bb0, #FF9BB0);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.eei63za0i {
  fill: var(--svg-color--e06593, #E06593);
  d: path("M15.953 30.01h-1.19a.749.749 0 1 1 0-1.5h.75V19c0-.41.34-.75.75-.75s.75.34.75.76v9.95c0 .58-.48 1.05-1.06 1.05");
}

.elqgrdbtw {
  d: path("m6.37 4.143l-.092 1.2l.227-.862a1 1 0 0 1 .967-.747h1.822V2.297h-.93a2 2 0 0 0-1.993 1.846");
}

.faq6zbbof {
  stop-color: var(--svg-color--d947aa, #D947AA);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hpgzikbxj {
  stop-color: var(--svg-color--d04b86, #D04B86);
  stop-opacity: 0;
}

.j3_nw90-v {
  stop-color: var(--svg-color--ffc9c5, #FFC9C5);
  stop-opacity: 0;
}

.j3gss9bub {
  stop-color: var(--svg-color--ff9eb7, #FF9EB7);
}

.jeys61f5c {
  stop-color: var(--svg-color--a72574, #A72574);
}

.k1mlv5qsu {
  stop-color: var(--svg-color--ef6a8e, #EF6A8E);
}

.kgv50-ecn {
  stop-color: var(--svg-color--d3b9d9, #D3B9D9);
}

.kvnxpybqb {
  d: path("M11.483 4a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.l_ddebamj {
  stop-color: var(--svg-color--d445a2, #D445A2);
}

.ldcf9eg3f {
  d: path("M15.953 30.01h-1.19a.749.749 0 1 1 0-1.5h.75V19c0-.41.34-.75.75-.75s.75.34.75.76v9.95c0 .58-.48 1.05-1.06 1.05");
}

.lf1q0ab2s {
  stop-color: var(--svg-color--bb3c69, #BB3C69);
}

.lh593x5yh {
  stop-color: var(--svg-color--e155c5, #E155C5);
  stop-opacity: 0;
}

.lp83_ccwv {
  d: path("M10.013 2h-1v3h1z");
}

.lt9z-q_zf {
  d: path("M11.263 24.5c-.41 0-.75-.34-.75-.75v-.37c0-.76.62-1.38 1.38-1.38h8.44c.1 0 .15-.06.17-.11s.04-.12-.02-.2l-3.92-5.02l1.18-.92l3.92 5.02c.4.51.47 1.19.19 1.77c-.28.59-.9.96-1.56.96h-8.28v.24c0 .43-.34.76-.75.76");
}

.m1w9l824e {
  stop-color: var(--svg-color--cc4c8f, #CC4C8F);
  stop-opacity: 0;
}

.mkf5xbygz {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  d: path("M7.052 11.836c-.172.726.048 1.61.648 2.023c.868.597 1.957.286 2.563-.203c.325-.262 2.067-1.974 2.922-2.86");
}

.ml-xt8bjv {
  stop-color: var(--svg-color--d952a0, #D952A0);
  stop-opacity: 0;
}

.mo8s5gznp {
  stop-color: var(--svg-color--ea64ba, #EA64BA);
}

.mx65styut {
  stop-color: var(--svg-color--ffc9c5, #FFC9C5);
}

.n1-nrtpjs {
  stop-color: var(--svg-color--d04b86, #D04B86);
}

.nbbzxxbtq {
  stop-color: var(--svg-color--cc4c8f, #CC4C8F);
}

.ngjk72oaq {
  stop-color: var(--svg-color--e155c5, #E155C5);
}

.nkf8idbzm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.45 29.031V18.875");
}

.no7qj6zjo {
  stop-color: var(--svg-color--e25688, #E25688);
  stop-opacity: 0;
}

.oeuqzpyuy {
  stop-color: var(--svg-color--e874a0, #E874A0);
  stop-opacity: 0;
}

.ojtbjtt4e {
  d: path("M8.203 2c-1.21 0-2.19.98-2.19 2.19v1.15c0 .28.32.45.55.3l.6-.39c.24-.16.53-.25.82-.25h2.03V2z");
}

.orogzxyau {
  stop-color: var(--svg-color--8e8e8f, #8E8E8F);
}

.ph9qtnbmj {
  stop-color: var(--svg-color--d15c74, #D15C74);
  stop-opacity: 0;
}

.phdj8nb9i {
  stop-color: var(--svg-color--d952a0, #D952A0);
}

.prr06vn9p {
  stop-color: var(--svg-color--9a999b, #9A999B);
}

.q7ukxorza {
  stop-color: var(--svg-color--f581a8, #F581A8);
}

.qzn7pty-t {
  d: path("M16.413 8h-.14c-1.47 0-3.11.74-3.99 1.71l-2.99 2.98c-.29.29-.77.29-1.06 0a.754.754 0 0 1 0-1.06l4.98-4.98A2.723 2.723 0 0 0 11.293 2h-3.09c-1.21 0-2.19.98-2.19 2.19v1.15c0 .28.32.45.55.3l.6-.39c.24-.16.53-.25.82-.25h2.78l-4.16 4.35a5.702 5.702 0 0 0 4.12 9.65h15.13c.66 0 1.19-.56 1.13-1.23c-.43-5.41-5.06-9.7-10.57-9.77");
}

.r3f_1qtju {
  stop-color: var(--svg-color--ff91a9, #FF91A9);
}

.s58ehl94k {
  stop-color: var(--svg-color--9a999b, #9A999B);
  stop-opacity: 0;
}

.s9wis0bdq {
  stop-color: var(--svg-color--634a65, #634A65);
}

.sbjgjh8je {
  d: path("M24.773 16.71c-.34-3.99-3.53-7.12-7.61-7.12a3.91 3.91 0 1 0 0 7.82l6.96-.01c.38.01.68-.31.65-.69");
}

.shwoz5eeu {
  d: path("M24.03 16.9c-.33-4.097-3.434-7.31-7.404-7.31c-2.102 0-3.805 1.797-3.805 4.014s1.703 4.014 3.805 4.014l6.772-.01c.37.01.661-.318.632-.708");
}

.uhzva39kr {
  stop-color: var(--svg-color--ff94d3, #FF94D3);
  stop-opacity: 0;
}

.ul1nowbjb {
  stop-color: var(--svg-color--634a65, #634A65);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wbw-5rbhd {
  stop-color: var(--svg-color--6e6576, #6E6576);
}

.wc8spo37w {
  stop-color: var(--svg-color--e16081, #E16081);
}

.wiay7zb2f {
  stop-color: var(--svg-color--f581a8, #F581A8);
  stop-opacity: 0;
}

.woz8p6buf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.31 5.266L7.122 9.625c-.734.734-1.203 1.875-1.203 3.172");
}

.xcxzx2bsk {
  stop-color: var(--svg-color--d15c74, #D15C74);
}

.xdfta7kgs {
  stop-color: var(--svg-color--ff9fb4, #FF9FB4);
}

.xpnn-p5ul {
  stop-color: var(--svg-color--a72574, #A72574);
  stop-opacity: 0;
}

.xvqd2wbxp {
  stop-color: var(--svg-color--ff9bb0, #FF9BB0);
  stop-opacity: 0;
}

.y_rrxd12w {
  stop-color: var(--svg-color--ed5ec4, #ED5EC4);
}

.yu_y3hb1z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m19.919 19.469l1.357 1.676c.153.19.237.425.237.668v0c0 .587-.476 1.062-1.062 1.062h-4.626");
}

.z0msjc-gh {
  stop-color: var(--svg-color--e66793, #E66793);
}

</style>
