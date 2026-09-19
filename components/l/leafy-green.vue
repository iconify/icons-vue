<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i1LDQEc)" class="s7z3_l7lr"/><g filter="url(#i17WcIc)"><path fill="url(#ivISSCO)" class="rxitn2bps"/></g><g filter="url(#ig5iymb)"><path stroke="url(#imEJyHb)" class="z36yqmwmp"/></g><path class="scnhv7jta"/><g filter="url(#ic4w0Wd)"><path fill="url(#iiZVT0b)" class="p51y6wbuz"/></g><g filter="url(#iuG9Kre)"><path fill="url(#iMNgJvd)" class="kmhtwlfey"/></g><g filter="url(#iPNnhEd)"><path stroke="url(#i4ba3QI)" class="svmo5gb-x"/></g><g filter="url(#inZVquc)"><path class="k3fwu6b1j"/></g><path fill="url(#i6JGroe)" class="t8_io6bgb"/><g filter="url(#iFJznYb)"><path fill="url(#i1CmBpH)" class="od-oeebis"/></g><path fill="url(#iaHiLJe)" clip-rule="evenodd" class="e6n69f_4l"/><path fill="url(#iNbixwe)" clip-rule="evenodd" class="e6n69f_4l"/><g filter="url(#iOpdlGc)"><path stroke="url(#iD5OVkd)" class="ge246evqy"/></g><g filter="url(#ipGJmPd)"><path stroke="url(#i8LLnPe)" class="oi1_rcc5l"/></g><g filter="url(#i74iEMd)"><path stroke="url(#iaXFWVd)" class="m0m_twb4k"/></g><g filter="url(#isV1yzc)"><path stroke="url(#iho6tHJ)" class="aael4dxnm"/></g><g filter="url(#iWaqW5b)"><path stroke="url(#i62dS3b)" class="dk4yvib2i"/></g><g filter="url(#iVLAvFe)"><path class="ve5b42g-i"/></g><g filter="url(#icMKVnc)"><path fill="url(#iG2wJse)" class="b8lp_7fww"/></g><g filter="url(#icMKVnc)"><path fill="url(#iG2wJse)" class="b8lp_7fww"/></g><g filter="url(#iwvqPIe)"><path fill="url(#ioA3qdc)" class="y_8w_u_ox"/></g><g filter="url(#iwvqPIe)"><path fill="url(#ioA3qdc)" class="y_8w_u_ox"/></g><g filter="url(#ipdRamb)"><path fill="url(#iCmvehd)" class="h29p6hbkc"/></g><g filter="url(#iUVcNab)"><path fill="url(#iUcKKyh)" class="p141de_wh"/></g><g filter="url(#iDuev8x)"><path stroke="url(#iNUwJPb)" class="ob_-uybif"/></g><g filter="url(#iILwtfe)"><path stroke="url(#iMe8jId)" class="kmop9mb3i"/></g><g filter="url(#iB0CYRb)"><path stroke="url(#iRUVztb)" class="s6o76obsk"/></g><g filter="url(#i10XGNe)"><path stroke="url(#ieOuice)" class="ke9q1lbav"/></g><g filter="url(#i1uGcib)"><path stroke="url(#iht85zc)" class="k6meft38q"/></g><g filter="url(#izzmi0G)"><path stroke="url(#iDeOkjc)" class="nuaemsbmm"/></g><g filter="url(#iLa7Vsb)"><path fill="url(#irxSdVd)" class="az1ldbcds"/></g><g filter="url(#i4AmntZ)"><path fill="url(#iFlWwBd)" class="c9hhehb_i"/></g><g filter="url(#iqFGfzd)"><path fill="url(#ipmveoc)" class="lnsiddcio"/></g><defs><linearGradient id="i1LDQEc" x1="28.25" x2="10.875" y1="14.188" y2="29" gradientUnits="userSpaceOnUse"><stop class="wc227pb-g"/><stop offset=".165" class="daj6j3bgo"/><stop offset=".243" class="qu7c_sb4g"/><stop offset=".464" class="cnk02mbnf"/><stop offset=".575" class="x-u1z7btn"/><stop offset="1" class="lvqhg20vj"/></linearGradient><linearGradient id="ivISSCO" x1="26.063" x2="12.25" y1="11" y2="28.375" gradientUnits="userSpaceOnUse"><stop class="fv02bpbry"/><stop offset=".72" class="pjuho6b_f"/><stop offset="1" class="f0yuaqbum"/></linearGradient><linearGradient id="imEJyHb" x1="25.839" x2="28.773" y1="11.52" y2="17.779" gradientUnits="userSpaceOnUse"><stop class="zg-81zhsg"/><stop offset=".51" class="dl46f-bzz"/><stop offset="1" class="chwwjjb3j"/></linearGradient><linearGradient id="iiZVT0b" x1="16.813" x2="2.875" y1="4.563" y2="19.938" gradientUnits="userSpaceOnUse"><stop class="tug9drbkd"/><stop offset=".364" class="xg93qcbgh"/><stop offset=".578" class="azvg7uisn"/><stop offset="1" class="p8cs4iifv"/></linearGradient><linearGradient id="iMNgJvd" x1="14.613" x2="16.063" y1="7.563" y2="29.132" gradientUnits="userSpaceOnUse"><stop class="vr7v5bbsy"/><stop offset=".514" class="n-gd1o41e"/><stop offset=".907" class="k77b33bpq"/></linearGradient><linearGradient id="i4ba3QI" x1="20.406" x2="13.688" y1="5.25" y2="3.624" gradientUnits="userSpaceOnUse"><stop class="zg-81zhsg"/><stop offset=".51" class="dl46f-bzz"/><stop offset="1" class="chwwjjb3j"/></linearGradient><linearGradient id="i6JGroe" x1="4.063" x2="23" y1="26.375" y2="7.438" gradientUnits="userSpaceOnUse"><stop class="m813zbbnu"/><stop offset=".419" class="bnbfkb7gv"/><stop offset=".536" class="duvalnbsx"/><stop offset=".779" class="hde5inb9r"/><stop offset="1" class="hhjbegbnn"/></linearGradient><linearGradient id="i1CmBpH" x1="3.75" x2="24.125" y1="26.688" y2="8.125" gradientUnits="userSpaceOnUse"><stop class="p4cxhvtqn"/><stop offset=".169" class="krnrn83bs"/><stop offset=".358" class="ryud-9b9o"/><stop offset=".535" class="wrphdrbul"/><stop offset=".712" class="yiymzhb8z"/><stop offset=".884" class="xftcmlllh"/><stop offset="1" class="yq4whtevm"/></linearGradient><linearGradient id="iaHiLJe" x1="10.938" x2="16.344" y1="13.719" y2="21.375" gradientUnits="userSpaceOnUse"><stop class="s0ufmobmg"/><stop offset="1" class="pmbyii_df"/></linearGradient><linearGradient id="iD5OVkd" x1="19.844" x2="15.563" y1="11.969" y2="16.25" gradientUnits="userSpaceOnUse"><stop offset=".311" class="hdye0xv1w"/><stop offset="1" class="ew49b9bhq"/></linearGradient><linearGradient id="i8LLnPe" x1="20.309" x2="15.696" y1="17.885" y2="16.425" gradientUnits="userSpaceOnUse"><stop offset=".434" class="pk_1fqbru"/><stop offset="1" class="ae2crlj8c"/></linearGradient><linearGradient id="iaXFWVd" x1="9.076" x2="10.512" y1="18.304" y2="22.926" gradientUnits="userSpaceOnUse"><stop offset=".597" class="py9g-_brl"/><stop offset="1" class="jm7jmtber"/></linearGradient><linearGradient id="iho6tHJ" x1="14.068" x2="9.439" y1="23.096" y2="21.685" gradientUnits="userSpaceOnUse"><stop offset=".597" class="py9g-_brl"/><stop offset="1" class="jm7jmtber"/></linearGradient><linearGradient id="i62dS3b" x1="8.281" x2="15.876" y1="24.094" y2="16.501" gradientUnits="userSpaceOnUse"><stop offset=".689" class="py9g-_brl"/><stop offset="1" class="ew49b9bhq"/></linearGradient><linearGradient id="iG2wJse" x1="23.344" x2="24.063" y1="14.722" y2="20.344" gradientUnits="userSpaceOnUse"><stop class="lgtypvbey"/><stop offset=".233" class="u32nl9bvp"/><stop offset="1" class="htg9h9bzs"/></linearGradient><linearGradient id="ioA3qdc" x1="17.537" x2="11.99" y1="8.719" y2="7.558" gradientUnits="userSpaceOnUse"><stop class="lgtypvbey"/><stop offset=".233" class="u32nl9bvp"/><stop offset="1" class="htg9h9bzs"/></linearGradient><linearGradient id="iCmvehd" x1="9.086" x2="11.279" y1="13.259" y2="8.04" gradientUnits="userSpaceOnUse"><stop class="vu6oxdadk"/><stop offset=".233" class="dryzcqbka"/><stop offset="1" class="b2x3tek9f"/></linearGradient><linearGradient id="iUcKKyh" x1="19.579" x2="24.788" y1="22.942" y2="20.708" gradientUnits="userSpaceOnUse"><stop offset=".58" class="xxbol21rf"/><stop offset="1" class="evwpdjb-w"/></linearGradient><linearGradient id="iNUwJPb" x1="6.219" x2="1.406" y1="16.25" y2="25.344" gradientUnits="userSpaceOnUse"><stop class="chwwjjb3j"/><stop offset=".289" class="mlzaofnxw"/><stop offset=".708" class="gavngwr3z"/><stop offset="1" class="chwwjjb3j"/></linearGradient><linearGradient id="iRUVztb" x1="9.461" x2="9.867" y1="19.07" y2="18.922" gradientUnits="userSpaceOnUse"><stop class="xz_9sjb5w"/><stop offset="1" class="vy99bgqia"/></linearGradient><linearGradient id="ieOuice" x1="14" x2="14.516" y1="12.984" y2="12.836" gradientUnits="userSpaceOnUse"><stop class="ait6n2wjf"/><stop offset="1" class="x1v8q0buv"/></linearGradient><linearGradient id="iht85zc" x1="19.302" x2="19.456" y1="18.273" y2="17.759" gradientUnits="userSpaceOnUse"><stop class="ait6n2wjf"/><stop offset="1" class="x1v8q0buv"/></linearGradient><linearGradient id="iDeOkjc" x1="13.211" x2="13.361" y1="22.822" y2="22.416" gradientUnits="userSpaceOnUse"><stop class="xz_9sjb5w"/><stop offset="1" class="vy99bgqia"/></linearGradient><linearGradient id="irxSdVd" x1="11.594" x2="7.688" y1="5.762" y2="5.969" gradientUnits="userSpaceOnUse"><stop class="pe899xbqf"/><stop offset="1" class="bz6ng9kxa"/></linearGradient><linearGradient id="iFlWwBd" x1="26.031" x2="25.902" y1="20.639" y2="24.548" gradientUnits="userSpaceOnUse"><stop class="pe899xbqf"/><stop offset="1" class="bz6ng9kxa"/></linearGradient><linearGradient id="ipmveoc" x1="5.044" x2="5.156" y1="12.032" y2="8.031" gradientUnits="userSpaceOnUse"><stop offset=".5" class="g0m34obtg"/><stop offset="1" class="bz6ng9kxa"/></linearGradient><filter id="i17WcIc" width="27.085" height="20.384" x="2.449" y="9.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="ig5iymb" width="7.133" height="9.605" x="23.373" y="10.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".5"/></filter><filter id="ic4w0Wd" width="20.25" height="27.352" x="2.375" y="2.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iuG9Kre" width="23.377" height="24.445" x="2.924" y="5.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".5"/></filter><filter id="iPNnhEd" width="10.023" height="6.316" x="11.774" y="1.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".5"/></filter><filter id="inZVquc" width="2.421" height="10.563" x="2.001" y="14.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iFJznYb" width="22.373" height="22.652" x="3.135" y="6.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".125"/></filter><filter id="iOpdlGc" width="5.156" height="5.172" x="15.813" y="11.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".125"/></filter><filter id="ipGJmPd" width="6.444" height="3.053" x="14.691" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".125"/></filter><filter id="i74iEMd" width="2.387" height="4.939" x="8.722" y="17.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".125"/></filter><filter id="isV1yzc" width="4.945" height="2.367" x="10.027" y="21.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".125"/></filter><filter id="iWaqW5b" width="9.203" height="9.109" x="7.422" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".125"/></filter><filter id="iVLAvFe" width="5.752" height="5.267" x="20.282" y="5.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="icMKVnc" width="2.599" height="6.871" x="22.39" y="13.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iwvqPIe" width="6.773" height="2.906" x="11.508" y="6.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="ipdRamb" width="3.33" height="6.591" x="8.337" y="7.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iUVcNab" width="5.804" height="3.481" x="18.665" y="20.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iDuev8x" width="5.805" height="14.467" x="2.369" y="15.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iILwtfe" width="1.209" height="1.21" x="7.66" y="23.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".05"/></filter><filter id="iB0CYRb" width="1.83" height="3.988" x="8.951" y="17.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".05"/></filter><filter id="i10XGNe" width="2.24" height="5.127" x="13.517" y="11.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".05"/></filter><filter id="i1uGcib" width="5.116" height="2.285" x="15.699" y="16.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".05"/></filter><filter id="izzmi0G" width="3.986" height="1.84" x="10.778" y="21.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".05"/></filter><filter id="iLa7Vsb" width="6.531" height="2.097" x="6.25" y="4.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="i4AmntZ" width="2.149" height="6.53" x="25.061" y="19.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><filter id="iqFGfzd" width="1.955" height="5.811" x="3.981" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30123" stdDeviation=".25"/></filter><radialGradient id="iNbixwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06251 5.5625 -5.56664 -1.0633 14.875 16.938)" gradientUnits="userSpaceOnUse"><stop class="hojululat"/><stop offset="1" class="msd32wbcf"/></radialGradient><radialGradient id="iMe8jId" cx="0" cy="0" r="1" gradientTransform="matrix(.4297 -.52343 .40848 .33533 7.96 24.351)" gradientUnits="userSpaceOnUse"><stop class="zg-81zhsg"/><stop offset="1" class="chwwjjb3j"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leafy-green" /></template>
<style>
.aael4dxnm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.347 22.823l-3.694-1.117");
}

.ae2crlj8c {
  stop-color: var(--svg-color--4d6d3c, #4D6D3C);
  stop-opacity: 0;
}

.ait6n2wjf {
  stop-color: var(--svg-color--597843, #597843);
}

.az1ldbcds {
  d: path("m12.281 6.219l-.219-.75C8 4.375 6.75 6.219 6.75 6.219c2.688-.75 4.313-.281 5.531 0");
}

.azvg7uisn {
  stop-color: var(--svg-color--5d8541, #5D8541);
}

.b2x3tek9f {
  stop-color: var(--svg-color--abd46f, #ABD46F);
  stop-opacity: 0;
}

.b8lp_7fww {
  d: path("M24.297 20.344s.734-3.75-.672-5.782c-.437-.218-.93-.008-.656.297c1.578 1.766 1.328 5.485 1.328 5.485");
}

.bnbfkb7gv {
  stop-color: var(--svg-color--70a124, #70A124);
}

.bz6ng9kxa {
  stop-color: var(--svg-color--77a458, #77A458);
  stop-opacity: 0;
}

.c9hhehb_i {
  d: path("m25.56 19.96l.755.204c1.174 4.04-.644 5.327-.644 5.327c.696-2.702.195-4.317-.11-5.53");
}

.chwwjjb3j {
  stop-color: var(--svg-color--8bb34f, #8BB34F);
  stop-opacity: 0;
}

.cnk02mbnf {
  stop-color: var(--svg-color--524c55, #524C55);
}

.daj6j3bgo {
  stop-color: var(--svg-color--4c4954, #4C4954);
}

.dk4yvib2i {
  stroke-linecap: round;
  d: path("m8.172 24.11l7.703-7.61");
}

.dl46f-bzz {
  stop-color: var(--svg-color--84b05d, #84B05D);
}

.dryzcqbka {
  stop-color: var(--svg-color--94c155, #94C155);
}

.duvalnbsx {
  stop-color: var(--svg-color--71a520, #71A520);
  stop-opacity: 0.798;
}

.e6n69f_4l {
  fill-rule: evenodd;
  d: path("M13.827 11.362c.33-.103.68.082.782.411l1.193 3.842l4.098-4.098a.625.625 0 1 1 .884.883l-4.097 4.098l3.85 1.194a.625.625 0 1 1-.37 1.194l-4.48-1.389l-3.86 3.861l2.65.824a.625.625 0 0 1-.37 1.193l-3.28-1.018l-2.173 2.174a.625.625 0 1 1-.884-.884l2.173-2.173l-1.018-3.28a.625.625 0 0 1 1.194-.37l.823 2.65l3.861-3.86l-1.388-4.47a.625.625 0 0 1 .412-.782");
}

.evwpdjb-w {
  stop-color: var(--svg-color--819252, #819252);
  stop-opacity: 0;
}

.ew49b9bhq {
  stop-color: var(--svg-color--5c8142, #5C8142);
  stop-opacity: 0;
}

.f0yuaqbum {
  stop-color: var(--svg-color--51534b, #51534B);
}

.ft5dv1b6b {
  fill: none;
}

.fv02bpbry {
  stop-color: var(--svg-color--5a853f, #5A853F);
}

.g0m34obtg {
  stop-color: var(--svg-color--688e4f, #688E4F);
}

.gavngwr3z {
  stop-color: var(--svg-color--94be55, #94BE55);
}

.ge246evqy {
  stroke-linecap: round;
  d: path("m20.219 12.078l-3.657 3.672");
}

.h29p6hbkc {
  d: path("M11.167 7.96s-2.436 2.81-2.326 5.233c.244.398.657.504.573.114c-.534-2.465 1.753-5.347 1.753-5.347");
}

.hde5inb9r {
  stop-color: var(--svg-color--89bf21, #89BF21);
}

.hdye0xv1w {
  stop-color: var(--svg-color--5c8141, #5C8141);
}

.hhjbegbnn {
  stop-color: var(--svg-color--89c031, #89C031);
}

.hojululat {
  stop-color: var(--svg-color--3e5d2e, #3E5D2E);
}

.htg9h9bzs {
  stop-color: var(--svg-color--b2dd74, #B2DD74);
  stop-opacity: 0;
}

.jm7jmtber {
  stop-color: var(--svg-color--4c6d3a, #4C6D3A);
  stop-opacity: 0;
}

.k3fwu6b1j {
  fill: var(--svg-color--688555, #688555);
  d: path("M2.844 18.234c-.65-1.875-.235-2.593.094-3.172c-.13 1.063-.207 1.463.125 2.829c.228.943.859 2.327.859 3.828c0 1.36-1.281 2.906-1.281 2.906s.578-1.016.937-2.906c-.016-1.085-.432-2.613-.734-3.485");
}

.k6meft38q {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m16.47 16.63l3.976 1.309a.34.34 0 0 1 .205.416c-.081.328-.378.27-.502.237c-.1-.026-3.287-1.028-4.335-1.368");
}

.k77b33bpq {
  stop-color: var(--svg-color--374a2a, #374A2A);
}

.ke9q1lbav {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m15.61 15.836l-1.262-3.991a.34.34 0 0 0-.414-.211c-.328.078-.274.375-.243.5c.025.1.989 3.298 1.317 4.35");
}

.kmhtwlfey {
  d: path("M23.758 22.714c1.848-1.864 1.988-4.797.68-6.994a1.217 1.217 0 0 1 .355-1.65c.126-.088.24-.186.332-.299c.688-3.021-3.937-7.334-6.861-6.572l-.065.07c-.444.5-1.18.645-1.75.3c-2.183-1.322-5.106-1.202-6.952.66c-1.076 1.086-1.632 2.614-1.652 4.081c-.008.613-.435 1.188-.983 1.454c-.663.322-1.245.831-1.725 1.315c-1.14 1.14-1.377 2.547-1.118 4.022c2.91 16.786-2.597 6.939 9.383 9.04c1.131.199 2.727-.102 3.857-1.242c.47-.473.912-1.022 1.212-1.608c.264-.517.808-.895 1.383-.9c1.416-.012 2.812-.576 3.904-1.677");
}

.kmop9mb3i {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.14 23.586c-.16.14-.527.481-.195.797c.313.297.563 0 .79-.219");
}

.krnrn83bs {
  stop-color: var(--svg-color--86aa3c, #86AA3C);
}

.lgtypvbey {
  stop-color: var(--svg-color--b2de74, #B2DE74);
  stop-opacity: 0;
}

.lnsiddcio {
  d: path("M5.435 12.592h-.62c-.987-3.34.529-4.81.529-4.81c-.933 1.438-.28 3.906.091 4.81");
}

.lvqhg20vj {
  stop-color: var(--svg-color--574d55, #574D55);
}

.m0m_twb4k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m9.348 18.024l1.136 3.688");
}

.m813zbbnu {
  stop-color: var(--svg-color--88ad37, #88AD37);
}

.mlzaofnxw {
  stop-color: var(--svg-color--94c051, #94C051);
}

.msd32wbcf {
  stop-color: var(--svg-color--40602f, #40602F);
  stop-opacity: 0;
}

.n-gd1o41e {
  stop-color: var(--svg-color--436c30, #436C30);
}

.nuaemsbmm {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m11.567 21.644l2.825.862a.34.34 0 0 1 .21.415c-.08.327-.377.272-.502.24c-.1-.025-2.156-.68-3.207-1.012");
}

.ob_-uybif {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M5.781 16.063c-.375 1-.178 2.293 0 3.562c.25 1.781-.916 3.052-1.406 3.75c-.76.854-1.997 3.203-.672 4.828s3.318.839 3.828.485");
}

.od-oeebis {
  d: path("M23.182 21.689c1.66-1.66 1.774-4.42.6-6.376c-.488-.812.018-1.262.463-1.797c1.332-1.593 1.37-3.726 0-5.29c-1.545-1.765-3.978-2.049-5.636-.195c-.398.446-1.479.48-1.991.173c-1.96-1.176-4.413-1.174-6.071.484c-.967.966-1.482 2.553-1.5 3.859c-.008.546-.392 1.058-.883 1.295c-.595.287-1.275.618-1.706 1.05c-1.024 1.015-1.16 2.295-.927 3.608c.298 1.705.283 3.552-.937 4.781c-1.313 1.547-1.81 3.253-.188 4.875c1.379 1.379 3.063.703 4.64-.593c1.23-1.23 3.122-1.34 4.836-1.042c1.016.177 2.448-.09 3.464-1.106c.42-.421.736-1.045 1.005-1.567c.237-.46.726-.797 1.243-.801c1.271-.01 2.608-.378 3.588-1.358");
}

.oi1_rcc5l {
  stroke-linecap: round;
  d: path("m20.385 18.269l-4.943-1.553");
}

.p141de_wh {
  d: path("M23.969 20.813s-1.734 2.786-4.384 2.453c-.41-.266-.6-.79-.194-.844c2.468-.328 4.578-1.61 4.578-1.61");
}

.p4cxhvtqn {
  stop-color: var(--svg-color--8fb541, #8FB541);
}

.p51y6wbuz {
  d: path("M5.462 7.86c1.246-2.26 4.057-2.793 6.38-1.892c.652.252.812-.495 1.165-.984c1.48-2.055 3.388-2.675 5.283-1.765c2.271 1.089 3.178 4.052 1.977 6.23a4 4 0 0 1-.629.862c2.356 1.411 3.19 4.47 1.84 6.905a5.07 5.07 0 0 1-3.97 2.605a4.37 4.37 0 0 1-.516 2.586a4.28 4.28 0 0 1-3.304 2.197c-1.736.19-3.294 1.175-4.148 2.719a3.54 3.54 0 0 1-4.842 1.383c-1.718-.966-2.328-3.154-1.37-4.888c.854-1.534.863-3.39.112-4.982a4.36 4.36 0 0 1 .122-3.997c.365-.66.926-1.058 1.5-1.433c.223-.145.656-.718.563-.969c-.51-1.366-.922-3.197-.163-4.578");
}

.p8cs4iifv {
  stop-color: var(--svg-color--4c6e39, #4C6E39);
}

.pe899xbqf {
  stop-color: var(--svg-color--77a458, #77A458);
}

.pjuho6b_f {
  stop-color: var(--svg-color--5b7444, #5B7444);
}

.pk_1fqbru {
  stop-color: var(--svg-color--4d6e3c, #4D6E3C);
}

.pmbyii_df {
  stop-color: var(--svg-color--46772a, #46772A);
}

.py9g-_brl {
  stop-color: var(--svg-color--5c8142, #5C8142);
}

.qu7c_sb4g {
  stop-color: var(--svg-color--4c771d, #4C771D);
}

.rxitn2bps {
  d: path("M23.808 26.439c2.254-1.255 3.181-3.966 2.282-6.306c-.108-.282-.042-.743.236-.859a4.2 4.2 0 0 0 .768-.415c1.748-1.19 2.45-3.373 1.543-5.282a4.324 4.324 0 0 0-6.88-1.294a5.11 5.11 0 0 0-6.89-1.852a5.11 5.11 0 0 0-2.598 3.997a4.33 4.33 0 0 0-2.58.52a4.31 4.31 0 0 0-2.192 3.326c-.19 1.748-1.172 3.317-2.712 4.177a3.582 3.582 0 1 0 3.496 6.256c1.53-.86 3.383-.87 4.97-.114a4.32 4.32 0 0 0 3.989-.122a4.27 4.27 0 0 0 1.564-1.497a.56.56 0 0 1 .678-.232a5.1 5.1 0 0 0 4.326-.303");
}

.ryud-9b9o {
  stop-color: var(--svg-color--8db93f, #8DB93F);
}

.s0ufmobmg {
  stop-color: var(--svg-color--457328, #457328);
}

.s6o76obsk {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.633 20.719L9.78 17.89a.34.34 0 0 0-.414-.211c-.328.078-.273.375-.242.5c.025.1.672 2.159 1 3.21");
}

.s7z3_l7lr {
  d: path("M24.462 27.129c2.386-1.328 3.367-4.197 2.416-6.674a.607.607 0 0 1 .332-.767q.422-.174.812-.44a4.58 4.58 0 0 0 1.55-5.73a4.575 4.575 0 0 0-7.28-1.37a5.407 5.407 0 0 0-7.29-1.96c-1.62.9-2.59 2.52-2.75 4.23c-.91-.1-1.87.07-2.73.55a4.56 4.56 0 0 0-2.32 3.52c-.2 1.85-1.24 3.51-2.87 4.42a3.79 3.79 0 0 0-1.46 5.16a3.79 3.79 0 0 0 5.16 1.46c1.62-.91 3.58-.92 5.26-.12c1.3.62 2.87.63 4.22-.13c.7-.39 1.261-.94 1.656-1.584a.595.595 0 0 1 .716-.245c1.444.562 3.12.49 4.578-.32");
}

.scnhv7jta {
  fill: var(--svg-color--457420, #457420);
  d: path("M4.882 7.549C6.21 5.163 9.08 4.182 11.556 5.133a.607.607 0 0 0 .767-.332q.174-.422.44-.812a4.58 4.58 0 0 1 5.73-1.55a4.575 4.575 0 0 1 1.37 7.28a5.407 5.407 0 0 1 1.96 7.29a5.4 5.4 0 0 1-4.23 2.75c.1.91-.07 1.87-.55 2.73a4.56 4.56 0 0 1-3.52 2.32c-1.85.2-3.51 1.24-4.42 2.87a3.79 3.79 0 0 1-5.16 1.46a3.79 3.79 0 0 1-1.46-5.16c.91-1.62.92-3.58.12-5.26a4.57 4.57 0 0 1 .13-4.22c.388-.697.859-1.26 1.47-1.655a.614.614 0 0 0 .245-.724c-.542-1.442-.375-3.114.434-4.571");
}

.svmo5gb-x {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.406 6.625c.172-1.406-1.125-3.219-2.812-3.75c-1.256-.395-3.15-.075-4.5 2.125");
}

.t8_io6bgb {
  d: path("M23.844 21.969c1.781-1.782 1.917-4.585.656-6.685a1.16 1.16 0 0 1 .342-1.577c.121-.084.231-.178.32-.285c1.43-1.71 1.292-4.226-.178-5.906c-1.76-2.01-4.577-2.235-6.437-.375l-.063.066c-.427.478-1.137.616-1.687.286c-2.105-1.263-4.924-1.148-6.703.632c-1.038 1.037-1.573 2.498-1.593 3.9c-.007.586-.42 1.136-.948 1.39c-.638.308-1.2.794-1.662 1.257c-1.1 1.09-1.329 2.434-1.079 3.844c.32 1.83-.143 3.648-1.453 4.968c-1.48 1.48-1.638 3.623.103 5.365c1.48 1.48 3.792 1.334 5.272-.146c1.32-1.32 3.285-1.867 5.125-1.547c1.091.19 2.63-.097 3.72-1.187c.451-.452.878-.977 1.167-1.538c.255-.493.78-.855 1.334-.86c1.365-.01 2.712-.55 3.764-1.602");
}

.tug9drbkd {
  stop-color: var(--svg-color--5a873e, #5A873E);
}

.u32nl9bvp {
  stop-color: var(--svg-color--b2de74, #B2DE74);
}

.ve5b42g-i {
  fill: var(--svg-color--bfee84, #BFEE84);
  d: path("M20.782 6.47c2.75-.625 5.125 1.126 4.703 4.141c-.543-2.803-1.825-3.881-4.703-4.14");
}

.vr7v5bbsy {
  stop-color: var(--svg-color--2d5b18, #2D5B18);
}

.vu6oxdadk {
  stop-color: var(--svg-color--8cb750, #8CB750);
}

.vy99bgqia {
  stop-color: var(--svg-color--436c2f, #436C2F);
}

.wc227pb-g {
  stop-color: var(--svg-color--4b7916, #4B7916);
}

.wrphdrbul {
  stop-color: var(--svg-color--81a738, #81A738);
}

.x-u1z7btn {
  stop-color: var(--svg-color--605a62, #605A62);
}

.x1v8q0buv {
  stop-color: var(--svg-color--456d31, #456D31);
}

.xftcmlllh {
  stop-color: var(--svg-color--82b42e, #82B42E);
}

.xg93qcbgh {
  stop-color: var(--svg-color--528034, #528034);
}

.xxbol21rf {
  stop-color: var(--svg-color--96aa61, #96AA61);
}

.xz_9sjb5w {
  stop-color: var(--svg-color--6e9253, #6E9253);
}

.y_8w_u_ox {
  d: path("M12.008 7.324s3.797-.435 5.71 1.127c.184.454-.064.928-.348.631c-1.635-1.713-5.362-1.758-5.362-1.758");
}

.yiymzhb8z {
  stop-color: var(--svg-color--8cbc3d, #8CBC3D);
}

.yq4whtevm {
  stop-color: var(--svg-color--83b835, #83B835);
}

.z36yqmwmp {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.492 11.795c1.343-.45 3.378.46 4.235 2.007c.638 1.151.703 3.072-1.184 4.834");
}

.zg-81zhsg {
  stop-color: var(--svg-color--80ae64, #80AE64);
}

</style>
