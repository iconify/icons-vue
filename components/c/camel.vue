<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ih0QNad)" class="iq57sr1su"/><path fill="url(#iKYHORr)" class="iq57sr1su"/><path fill="url(#iZ5W7Op)" class="iq57sr1su"/><path fill="url(#ix6N0Lc)" class="fpj6rkb8a"/><path fill="url(#iqxgOPd)" class="fpj6rkb8a"/><path fill="url(#iKJm9vb)" class="fpj6rkb8a"/><path class="i-aoncbal"/><path fill="url(#iVeT0Ed)" class="pm9o-fb_o"/><path fill="url(#imTswFc)" class="pm9o-fb_o"/><path fill="url(#ikMiUQO)" class="pm9o-fb_o"/><path fill="url(#iGXj5ZV)" class="pm9o-fb_o"/><path fill="url(#iQ1NM3c)" class="pm9o-fb_o"/><path fill="url(#icP5wei)" class="pm9o-fb_o"/><path fill="url(#idg4lUb)" class="pm9o-fb_o"/><path fill="url(#iSTeOYo)" class="pm9o-fb_o"/><path fill="url(#iWw415c)" class="m5i-l9bet"/><path fill="url(#ijGtFKM)" class="m5i-l9bet"/><path fill="url(#ibUBiuA)" class="fr05f7bgp"/><path fill="url(#iD96YCc)" class="fr05f7bgp"/><path fill="url(#iSSCXwu)" class="fr05f7bgp"/><path fill="url(#iufhNtc)" class="anp5gxc_i"/><path fill="url(#iCOc9dd)" class="pm9o-fb_o"/><path fill="url(#iOAXCJc)" class="pm9o-fb_o"/><path fill="url(#iyfFAMt)" class="pm9o-fb_o"/><path fill="url(#iL2SVwe)" class="pm9o-fb_o"/><path fill="url(#ifvGo8b)" class="x-9gjebds"/><path fill="url(#ic3BBuM)" class="m4f8c9swn"/><g filter="url(#iC8bWle)"><path fill="url(#ildGXJd)" class="v9y-u1btd"/></g><g filter="url(#iHXcCtd)"><path fill="url(#i2X90Iy)" class="ynagerbdv"/></g><g filter="url(#iyMIlIg)"><path fill="url(#iXPDdQb)" class="zzfbxbcut"/></g><g filter="url(#i3ZRdKe)"><path fill="url(#iwBl0WR)" class="fjfwlac_j"/></g><g filter="url(#iXjUWGc)"><path fill="url(#iD793TE)" class="znr2f1xhk"/></g><g filter="url(#iEbpyEb)"><path stroke="url(#i5x7Mve)" class="ls123sbsl"/></g><g filter="url(#ihGq1fc)"><path stroke="url(#i6K5xvW)" class="e0co-bjqn"/></g><g filter="url(#iejZwQb)"><path fill="url(#ien1IPX)" class="pgwbz30ux"/></g><defs><radialGradient id="ih0QNad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81248 6.875 -5.49373 -1.44833 21.054 28.688)" gradientUnits="userSpaceOnUse"><stop class="qcy41hghm"/><stop offset="1" class="gqjcrdbcp"/></radialGradient><radialGradient id="ix6N0Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25004 -10.125 9.28504 -2.06337 17.68 29.813)" gradientUnits="userSpaceOnUse"><stop class="qcy41hghm"/><stop offset="1" class="gqjcrdbcp"/></radialGradient><radialGradient id="iVeT0Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5005 7.68754 -5.76084 -4.12192 15.867 11.938)" gradientUnits="userSpaceOnUse"><stop class="hdmk6tbso"/><stop offset="1" class="ylwvzmb_c"/></radialGradient><radialGradient id="imTswFc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1406 -2.00002 .62182 -.97644 31.21 13.75)" gradientUnits="userSpaceOnUse"><stop class="ty-kgff4d"/><stop offset="1" class="hrghpkbsw"/></radialGradient><radialGradient id="ikMiUQO" cx="0" cy="0" r="1" gradientTransform="matrix(8.53122 -6.43747 2.36059 3.12835 -.852 14.688)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l6y5qb8ul"/><stop offset="1" class="zi7dalv6c"/></radialGradient><radialGradient id="iGXj5ZV" cx="0" cy="0" r="1" gradientTransform="matrix(-3.54685 -7 4.06994 -2.06221 8.992 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="l6y5qb8ul"/><stop offset="1" class="zi7dalv6c"/></radialGradient><radialGradient id="iQ1NM3c" cx="0" cy="0" r="1" gradientTransform="rotate(46.259 .121 12.891)scale(2.01132 1.1713)" gradientUnits="userSpaceOnUse"><stop class="z2i1-_8-q"/><stop offset="1" class="h0ejm_bjv"/></radialGradient><radialGradient id="icP5wei" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 2.46875 -4.49122 3.18365 2.867 4.125)" gradientUnits="userSpaceOnUse"><stop class="z2i1-_8-q"/><stop offset="1" class="h0ejm_bjv"/></radialGradient><radialGradient id="idg4lUb" cx="0" cy="0" r="1" gradientTransform="matrix(4.75 -2 7.48121 17.76783 5.367 16.75)" gradientUnits="userSpaceOnUse"><stop class="annls_lug"/><stop offset="1" class="ees1cabol"/></radialGradient><radialGradient id="iSTeOYo" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -1.5 4.57143 13.71426 7.242 17.5)" gradientUnits="userSpaceOnUse"><stop class="r43dpjbln"/><stop offset="1" class="szvft-b3t"/></radialGradient><radialGradient id="iSSCXwu" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 -4.1875 4.41159 3.88482 22.804 25.063)" gradientUnits="userSpaceOnUse"><stop class="l6y5qb8ul"/><stop offset=".79" class="zi7dalv6c"/></radialGradient><radialGradient id="iufhNtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.625 7.625 0 19.554 22.875)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="l6y5qb8ul"/><stop offset=".941" class="zi7dalv6c"/></radialGradient><radialGradient id="iCOc9dd" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -6.0625 14.37474 .1482 19.492 21.5)" gradientUnits="userSpaceOnUse"><stop class="l6y5qb8ul"/><stop offset=".452" class="zi7dalv6c"/></radialGradient><radialGradient id="iOAXCJc" cx="0" cy="0" r="1" gradientTransform="rotate(37.208 -6.476 27.126)scale(2.11879 5.53733)" gradientUnits="userSpaceOnUse"><stop class="e8gzzetif"/><stop offset="1" class="jzj_bmbdm"/></radialGradient><radialGradient id="iyfFAMt" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.0625 -4.58333 0 7.93 6.125)" gradientUnits="userSpaceOnUse"><stop class="cf97z2b0q"/><stop offset="1" class="bepcn9bgb"/></radialGradient><radialGradient id="iL2SVwe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.18749 6.56247 -7.55688 -9.42815 30.867 7.688)" gradientUnits="userSpaceOnUse"><stop class="o_4-1m5bs"/><stop offset="1" class="bwkgc05nw"/></radialGradient><radialGradient id="ifvGo8b" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 0 0 .82813 3.171 7.938)" gradientUnits="userSpaceOnUse"><stop class="lzh5sj0-n"/><stop offset="1" class="ax_-teb8n"/></radialGradient><radialGradient id="ic3BBuM" cx="0" cy="0" r="1" gradientTransform="matrix(-.29167 0 0 -1.19336 7.511 6.5)" gradientUnits="userSpaceOnUse"><stop class="mqpbk469p"/><stop offset="1" class="ldgjpwb0m"/></radialGradient><radialGradient id="iD793TE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51564 1.93749 -1.29832 -1.01564 12.32 12.14)" gradientUnits="userSpaceOnUse"><stop class="fvo03zbpu"/><stop offset="1" class="hf4_adcdi"/></radialGradient><linearGradient id="iKYHORr" x1="21.898" x2="22.594" y1="29.813" y2="25.219" gradientUnits="userSpaceOnUse"><stop class="dxr3ojbrh"/><stop offset=".497" class="cmn1rnbob"/></linearGradient><linearGradient id="iZ5W7Op" x1="24.07" x2="24.07" y1="30.618" y2="28.215" gradientUnits="userSpaceOnUse"><stop class="kcigs4btz"/><stop offset="1" class="ehcvrkpcs"/></linearGradient><linearGradient id="iqxgOPd" x1="16" x2="14.145" y1="29.813" y2="21.279" gradientUnits="userSpaceOnUse"><stop class="ixwimykau"/><stop offset="1" class="njczzlbhx"/></linearGradient><linearGradient id="iKJm9vb" x1="17.554" x2="17.554" y1="30.75" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="kcigs4btz"/><stop offset="1" class="ehcvrkpcs"/></linearGradient><linearGradient id="iWw415c" x1="7.804" x2="11.617" y1="24.938" y2="14.063" gradientUnits="userSpaceOnUse"><stop class="k8zcfkbbt"/><stop offset=".688" class="ikfrkpbsw"/></linearGradient><linearGradient id="ijGtFKM" x1="14.09" x2="14.09" y1="30.094" y2="28.145" gradientUnits="userSpaceOnUse"><stop class="kcigs4btz"/><stop offset="1" class="ehcvrkpcs"/></linearGradient><linearGradient id="ibUBiuA" x1="26.492" x2="26.492" y1="19.625" y2="30.125" gradientUnits="userSpaceOnUse"><stop class="ikfrkpbsw"/><stop offset="1" class="ty-kgff4d"/></linearGradient><linearGradient id="iD96YCc" x1="26.492" x2="26.492" y1="30.25" y2="28.688" gradientUnits="userSpaceOnUse"><stop class="nl7xj1brc"/><stop offset="1" class="a8y_9y8sc"/></linearGradient><linearGradient id="ildGXJd" x1="28.101" x2="28.101" y1="19.125" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="ebr97sbqp"/><stop offset="1" class="x_-929b7y"/></linearGradient><linearGradient id="i2X90Iy" x1="12.847" x2="12.847" y1="4.125" y2="24.563" gradientUnits="userSpaceOnUse"><stop class="ebr97sbqp"/><stop offset="1" class="x_-929b7y"/></linearGradient><linearGradient id="iXPDdQb" x1="25.82" x2="28.164" y1="11.281" y2="8.844" gradientUnits="userSpaceOnUse"><stop class="bwkgc05nw"/><stop offset="1" class="o_4-1m5bs"/></linearGradient><linearGradient id="iwBl0WR" x1="11.492" x2="14.57" y1="15.063" y2="14.269" gradientUnits="userSpaceOnUse"><stop class="hf4_adcdi"/><stop offset="1" class="fvo03zbpu"/></linearGradient><linearGradient id="i5x7Mve" x1="21.335" x2="23.437" y1="28.656" y2="19.656" gradientUnits="userSpaceOnUse"><stop class="ivc3l634m"/><stop offset="1" class="otf-idbzq"/></linearGradient><linearGradient id="i6K5xvW" x1="16.692" x2="12.804" y1="28.656" y2="12.625" gradientUnits="userSpaceOnUse"><stop class="hyatejigp"/><stop offset="1" class="w1tcor74y"/></linearGradient><linearGradient id="ien1IPX" x1="27.492" x2="23.619" y1="13.188" y2="19.105" gradientUnits="userSpaceOnUse"><stop class="bwkgc05nw"/><stop offset="1" class="o_4-1m5bs"/></linearGradient><filter id="iC8bWle" width="2.063" height="11.25" x="27.07" y="18.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".375"/></filter><filter id="iHXcCtd" width="2.063" height="11.375" x="11.816" y="18.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".375"/></filter><filter id="iyMIlIg" width="11.344" height="9.454" x="18.445" y="4.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".375"/></filter><filter id="i3ZRdKe" width="2.517" height="10.044" x="9.575" y="2.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".3"/></filter><filter id="iXjUWGc" width="4.569" height="5.062" x="9.179" y="10.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".3"/></filter><filter id="iEbpyEb" width="3.578" height="8.361" x="20.804" y="21.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".4"/></filter><filter id="ihGq1fc" width="3.829" height="9.454" x="14.89" y="20.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".4"/></filter><filter id="iejZwQb" width="7.125" height="11.438" x="22.242" y="12.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3280" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:camel" /></template>
<style>
.a8y_9y8sc {
  stop-color: var(--svg-color--bc5972, #BC5972);
  stop-opacity: 0;
}

.annls_lug {
  stop-color: var(--svg-color--d28964, #D28964);
}

.anp5gxc_i {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M29.867 11.75a.73.73 0 0 0-.21-.46c-.03-.03-5.04-5.4-5.12-5.49c-.82-.81-1.94-1.3-3.17-1.3a4.49 4.49 0 0 0-3.852 2.18q-.017.029-.037.056c-.277.401-3.608 5.211-3.68 5.322q-.002.004-.001.007l-.003.01c-.18.277-.5.465-.857.465c-.55-.01-.99-.48-.99-1.03l-.08-7.01V2.77c0-.15-.13-.27-.28-.27c-.95 0-1.72.77-1.72 1.73c0 .15-.13.27-.28.27h-4.21c-1.94 0-3.51 1.57-3.51 3.51v.37c0 .62.5 1.12 1.12 1.12h2.94c.52 0 .94.42.94.94v2.88c0 2.67 1.47 5.01 3.64 6.25c.22.12.36.35.36.61V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5v-7.5a1 1 0 0 1 1-1h7q.49-.001.952-.091c.64-.124 1.336.225 1.54.844q.216.66.528 1.287l.85 1.71c.09.16.13.35.13.53V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5V13.068c0-.293.345-.51.607-.64a.7.7 0 0 0 .393-.678");
}

.ax_-teb8n {
  stop-color: var(--svg-color--bc7748, #BC7748);
}

.bepcn9bgb {
  stop-color: var(--svg-color--e4ae7c, #E4AE7C);
  stop-opacity: 0;
}

.bwkgc05nw {
  stop-color: var(--svg-color--ffc684, #FFC684);
  stop-opacity: 0;
}

.cf97z2b0q {
  stop-color: var(--svg-color--e4ae7c, #E4AE7C);
}

.cmn1rnbob {
  stop-color: var(--svg-color--cc703f, #CC703F);
  stop-opacity: 0;
}

.dxr3ojbrh {
  stop-color: var(--svg-color--cc703f, #CC703F);
}

.e0co-bjqn {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.773 28.781L15.836 21");
}

.e8gzzetif {
  stop-color: var(--svg-color--cd8549, #CD8549);
}

.ebr97sbqp {
  stop-color: var(--svg-color--ffb684, #FFB684);
  stop-opacity: 0;
}

.ees1cabol {
  stop-color: var(--svg-color--d28964, #D28964);
  stop-opacity: 0;
}

.ehcvrkpcs {
  stop-color: var(--svg-color--d9747b, #D9747B);
  stop-opacity: 0;
}

.fjfwlac_j {
  d: path("M11.492 11.906V3.063c-.563 0-1.386 6.49-1.313 8.843z");
}

.fpj6rkb8a {
  d: path("M16.207 17.5h-3l2.57 11.61c.05.23.26.39.49.39h2.21c.2 0 .35-.18.31-.38z");
}

.fr05f7bgp {
  d: path("M28.867 19.594a2.375 2.375 0 0 0-4.75 0v.758c0 .312.144.604.241.901q.216.66.529 1.287l.85 1.71c.09.16.13.35.13.53V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5z");
}

.ft5dv1b6b {
  fill: none;
}

.fvo03zbpu {
  stop-color: var(--svg-color--ffd0a3, #FFD0A3);
}

.gqjcrdbcp {
  stop-color: var(--svg-color--7e3834, #7E3834);
}

.h0ejm_bjv {
  stop-color: var(--svg-color--e09a58, #E09A58);
  stop-opacity: 0;
}

.hdmk6tbso {
  stop-color: var(--svg-color--e19c70, #E19C70);
}

.hf4_adcdi {
  stop-color: var(--svg-color--ffd0a3, #FFD0A3);
  stop-opacity: 0;
}

.hrghpkbsw {
  stop-color: var(--svg-color--ce7549, #CE7549);
  stop-opacity: 0;
}

.hyatejigp {
  stop-color: var(--svg-color--ea9669, #EA9669);
}

.i-aoncbal {
  fill: var(--svg-color--e49e76, #E49E76);
  d: path("M29.867 11.75a.73.73 0 0 0-.21-.46c-.03-.03-5.04-5.4-5.12-5.49c-.82-.81-1.94-1.3-3.17-1.3a4.49 4.49 0 0 0-3.852 2.18q-.017.029-.037.056c-.277.401-3.608 5.211-3.68 5.322q-.002.004-.001.007l-.003.01c-.18.277-.5.465-.857.465c-.55-.01-.99-.48-.99-1.03l-.08-7.01V2.77c0-.15-.13-.27-.28-.27c-.95 0-1.72.77-1.72 1.73c0 .15-.13.27-.28.27h-4.21c-1.94 0-3.51 1.57-3.51 3.51v.37c0 .62.5 1.12 1.12 1.12h2.94c.52 0 .94.42.94.94v2.88c0 2.67 1.47 5.01 3.64 6.25c.22.12.36.35.36.61V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5v-7.5a1 1 0 0 1 1-1h7q.49-.001.952-.091c.64-.124 1.336.225 1.54.844q.216.66.528 1.287l.85 1.71c.09.16.13.35.13.53V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5V13.068c0-.293.345-.51.607-.64a.7.7 0 0 0 .393-.678");
}

.ikfrkpbsw {
  stop-color: var(--svg-color--e49e76, #E49E76);
}

.iq57sr1su {
  d: path("M22.247 18.77h3l-2.3 10.34c-.04.23-.25.39-.48.39h-2.21a.32.32 0 0 1-.31-.38z");
}

.ivc3l634m {
  stop-color: var(--svg-color--f79b78, #F79B78);
}

.ixwimykau {
  stop-color: var(--svg-color--d27d5b, #D27D5B);
}

.jzj_bmbdm {
  stop-color: var(--svg-color--cd8549, #CD8549);
  stop-opacity: 0;
}

.k8zcfkbbt {
  stop-color: var(--svg-color--d27e4d, #D27E4D);
}

.kcigs4btz {
  stop-color: var(--svg-color--d9747b, #D9747B);
}

.l6y5qb8ul {
  stop-color: var(--svg-color--b13e76, #B13E76);
}

.ldgjpwb0m {
  stop-color: var(--svg-color--3c2b34, #3C2B34);
}

.ls123sbsl {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m21.75 28.875l1.687-6.687");
}

.lzh5sj0-n {
  stop-color: var(--svg-color--c78e72, #C78E72);
}

.m4f8c9swn {
  d: path("M7.367 7.5c-.28 0-.5-.245-.5-.532v-.936c0-.298.22-.532.5-.532s.5.234.5.532v.936c0 .287-.22.532-.5.532");
}

.m5i-l9bet {
  d: path("M15.304 20.5v-1.312a1 1 0 0 0-1-1h-3.163c-.46 0-.706.611-.505 1.025c.181.374.218.684.225.879l.006.088V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5v-7.5a1 1 0 0 1 1-1z");
}

.mqpbk469p {
  stop-color: var(--svg-color--67545f, #67545F);
}

.njczzlbhx {
  stop-color: var(--svg-color--d27d5b, #D27D5B);
  stop-opacity: 0;
}

.nl7xj1brc {
  stop-color: var(--svg-color--bc5972, #BC5972);
}

.o_4-1m5bs {
  stop-color: var(--svg-color--ffc684, #FFC684);
}

.otf-idbzq {
  stop-color: var(--svg-color--f69b78, #F69B78);
  stop-opacity: 0;
}

.pgwbz30ux {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M28.367 13.188v9.437h-1.313l-3.812-9.437z");
}

.pm9o-fb_o {
  d: path("M29.867 11.75a.73.73 0 0 0-.21-.46c-.03-.03-5.04-5.4-5.12-5.49c-.82-.81-1.94-1.3-3.17-1.3a4.49 4.49 0 0 0-3.852 2.18q-.017.029-.037.056c-.277.401-3.608 5.211-3.68 5.322q-.002.004-.001.007l-.003.01c-.18.277-.5.465-.857.465c-.55-.01-.99-.48-.99-1.03l-.08-7.01V2.77c0-.15-.13-.27-.28-.27c-.95 0-1.72.77-1.72 1.73c0 .15-.13.27-.28.27h-4.21c-1.94 0-3.51 1.57-3.51 3.51v.37c0 .62.5 1.12 1.12 1.12h2.94c.52 0 .94.42.94.94v2.88c0 2.67 1.47 5.01 3.64 6.25c.22.12.36.35.36.61V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5v-7.5a1 1 0 0 1 1-1h7q.49-.001.952-.091c.64-.124 1.336.225 1.54.844q.216.66.528 1.287l.85 1.71c.09.16.13.35.13.53V29c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5V13.068c0-.293.345-.51.607-.64a.7.7 0 0 0 .393-.678");
}

.qcy41hghm {
  stop-color: var(--svg-color--c56b44, #C56B44);
}

.r43dpjbln {
  stop-color: var(--svg-color--ce8167, #CE8167);
}

.szvft-b3t {
  stop-color: var(--svg-color--ce8167, #CE8167);
  stop-opacity: 0;
}

.ty-kgff4d {
  stop-color: var(--svg-color--ce7549, #CE7549);
}

.v9y-u1btd {
  d: path("M27.82 19.125h.563v9.75h-.563z");
}

.w1tcor74y {
  stop-color: var(--svg-color--ea9669, #EA9669);
  stop-opacity: 0;
}

.x_-929b7y {
  stop-color: var(--svg-color--ffb684, #FFB684);
}

.x-9gjebds {
  d: path("M3.367 8.5c-.28 0-.5-.23-.5-.5v-.44c0-.28.22-.5.5-.5s.5.22.5.5V8c0 .27-.22.5-.5.5");
}

.ylwvzmb_c {
  stop-color: var(--svg-color--e19c70, #E19C70);
  stop-opacity: 0;
}

.ynagerbdv {
  d: path("M12.566 19h.563v9.875h-.563z");
}

.z2i1-_8-q {
  stop-color: var(--svg-color--e0a267, #E0A267);
}

.zi7dalv6c {
  stop-color: var(--svg-color--b13e76, #B13E76);
  stop-opacity: 0;
}

.znr2f1xhk {
  d: path("M13.148 13.234c-1.725-.037-1.906-1.421-1.781-2.109H9.835c-.14.781 0 1.62.22 2.313c.462 1.462 2.348 1.572 3.093 1.546z");
}

.zzfbxbcut {
  d: path("M29.039 11.594L23.952 6.18a3 3 0 0 0-2.956-.846l-1.801.479l8.125 7.375z");
}

</style>
