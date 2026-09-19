<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p0sep6u6h"/><path stroke="url(#ilcR2Vc)" class="dsrq2pbor"/><path stroke="url(#iKdmkpd)" class="dsrq2pbor"/><path stroke="url(#iqGN1qe)" class="dsrq2pbor"/><g filter="url(#iN4yszb)"><path class="k_bmtxxec"/></g><g filter="url(#iDzT4sc)"><path fill="url(#i9CDzCb)" class="vj64ivb0i"/><path fill="url(#icYaJHc)" class="vj64ivb0i"/><path fill="url(#i1kmfBb)" class="vj64ivb0i"/><path fill="url(#iGWxWtC)" class="vj64ivb0i"/></g><path stroke="url(#iU2pFee)" class="e0zbunbis"/><path stroke="url(#i0e9cpb)" class="e0zbunbis"/><path stroke="url(#i69vMHc)" class="nsj-fhbtz"/><path stroke="url(#iPierKd)" class="nsj-fhbtz"/><rect fill="url(#iC3UpFT)" transform="rotate(30 14.683 18.683)" class="ngi0bnbvt"/><rect fill="url(#iVnxQkc)" transform="rotate(30 14.683 18.683)" class="ngi0bnbvt"/><rect fill="url(#ixZAt9d)" transform="rotate(30 14.683 18.683)" class="ngi0bnbvt"/><defs><radialGradient id="iKdmkpd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13812 2.44623 -3.62306 -3.16673 27.796 2.05)" gradientUnits="userSpaceOnUse"><stop class="vp29wje1f"/><stop offset="1" class="cmm1obbdg"/></radialGradient><radialGradient id="iqGN1qe" cx="0" cy="0" r="1" gradientTransform="matrix(1.1152 -.47965 .29802 .6929 26.656 2.985)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="r6vm17glm"/><stop offset="1" class="egmgd1bvg"/></radialGradient><radialGradient id="icYaJHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.84376 -3.04093 -1.85546 16.157 22.344)" gradientUnits="userSpaceOnUse"><stop class="iu6uwtgpd"/><stop offset="1" class="li8lebbyx"/></radialGradient><radialGradient id="iGWxWtC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71873 2.71876 -3.47064 -2.19405 13.72 25.813)" gradientUnits="userSpaceOnUse"><stop class="omk47cbmy"/><stop offset="1" class="hd_oipbcl"/></radialGradient><radialGradient id="i0e9cpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09855 .18342 -2.59954 -1.39673 15.096 23.524)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="nh4ulhbew"/><stop offset="1" class="rpw-a_hmo"/></radialGradient><radialGradient id="iPierKd" cx="0" cy="0" r="1" gradientTransform="rotate(117.408 -.366 16.929)scale(.23761 3.30054)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="nh4ulhbew"/><stop offset="1" class="rpw-a_hmo"/></radialGradient><radialGradient id="iVnxQkc" cx="0" cy="0" r="1" gradientTransform="rotate(164.846 7.64 10.512)scale(3.29759 2.01065)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="j9mkg_zxh"/><stop offset=".966" class="hr9u17b3b"/></radialGradient><radialGradient id="ixZAt9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.00351 .65017 -1.93386 -.01044 17.438 18.85)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="eh8uh-poj"/><stop offset="1" class="dt1u0gy4o"/></radialGradient><linearGradient id="ilcR2Vc" x1="15.439" x2="17.782" y1="18.063" y2="19.438" gradientUnits="userSpaceOnUse"><stop offset=".142" class="t95r3ob6z"/><stop offset="1" class="oijl4q39g"/></linearGradient><linearGradient id="i9CDzCb" x1="7.439" x2="15.876" y1="29.063" y2="21.25" gradientUnits="userSpaceOnUse"><stop class="aksihkbhf"/><stop offset="1" class="ibw8ai5aw"/></linearGradient><linearGradient id="i1kmfBb" x1="6.439" x2="10.626" y1="29.125" y2="26.75" gradientUnits="userSpaceOnUse"><stop class="ungwku9vn"/><stop offset="1" class="kg-f78xpv"/></linearGradient><linearGradient id="iU2pFee" x1="15.314" x2="10.486" y1="24.125" y2="21.472" gradientUnits="userSpaceOnUse"><stop class="ktyrvxvta"/><stop offset=".718" class="e045c-bps"/><stop offset="1" class="m5e5sgbwy"/></linearGradient><linearGradient id="i69vMHc" x1="14.735" x2="9.29" y1="25.738" y2="22.851" gradientUnits="userSpaceOnUse"><stop class="ktyrvxvta"/><stop offset=".718" class="e045c-bps"/><stop offset="1" class="m5e5sgbwy"/></linearGradient><linearGradient id="iC3UpFT" x1="16.584" x2="16.611" y1="18.683" y2="19.885" gradientUnits="userSpaceOnUse"><stop class="rwrz_ebce"/><stop offset="1" class="jftpjsb6t"/></linearGradient><filter id="iN4yszb" width="12.835" height="20.588" x="14.023" y="2.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26124" stdDeviation=".375"/></filter><filter id="iDzT4sc" width="14.242" height="10.062" x="4.267" y="19.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.517647 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26124"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.427451 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26124" result="effect2_innerShadow_18_26124"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:broom" /></template>
<style>
.aksihkbhf {
  stop-color: var(--svg-color--f58c43, #F58C43);
}

.cmm1obbdg {
  stop-color: var(--svg-color--a57667, #A57667);
  stop-opacity: 0;
}

.dsrq2pbor {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M25.658 3.5L14.86 22.234");
}

.dt1u0gy4o {
  stop-color: var(--svg-color--c3b6d4, #C3B6D4);
  stop-opacity: 0;
}

.e045c-bps {
  stop-color: var(--svg-color--dc1e43, #DC1E43);
}

.e0zbunbis {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m11.267 21.547l6.047 3.281");
}

.egmgd1bvg {
  stop-color: var(--svg-color--bb8b86, #BB8B86);
  stop-opacity: 0;
}

.eh8uh-poj {
  stop-color: var(--svg-color--c3b6d4, #C3B6D4);
}

.ft5dv1b6b {
  fill: none;
}

.hd_oipbcl {
  stop-color: var(--svg-color--ffa565, #FFA565);
  stop-opacity: 0;
}

.hr9u17b3b {
  stop-color: var(--svg-color--7e7785, #7E7785);
}

.ibw8ai5aw {
  stop-color: var(--svg-color--fdad47, #FDAD47);
}

.iu6uwtgpd {
  stop-color: var(--svg-color--ffd46f, #FFD46F);
}

.j9mkg_zxh {
  stop-color: var(--svg-color--9b8dac, #9B8DAC);
  stop-opacity: 0;
}

.jftpjsb6t {
  stop-color: var(--svg-color--b69bcc, #B69BCC);
}

.k_bmtxxec {
  stroke: var(--svg-color--96596b, #96596B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M25.733 3.896L15.148 22.234");
}

.kg-f78xpv {
  stop-color: var(--svg-color--ff8655, #FF8655);
  stop-opacity: 0;
}

.ktyrvxvta {
  stop-color: var(--svg-color--ff1951, #FF1951);
}

.li8lebbyx {
  stop-color: var(--svg-color--ffd46f, #FFD46F);
  stop-opacity: 0;
}

.m5e5sgbwy {
  stop-color: var(--svg-color--b2424f, #B2424F);
}

.ngi0bnbvt {
  width: 3.803px;
  height: 1.319px;
  x: 14.683px;
  y: 18.683px;
  rx: 0.659px;
}

.nh4ulhbew {
  stop-color: var(--svg-color--ff516d, #FF516D);
}

.nsj-fhbtz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m10.243 22.773l6.711 3.774");
}

.oijl4q39g {
  stop-color: var(--svg-color--834953, #834953);
  stop-opacity: 0;
}

.omk47cbmy {
  stop-color: var(--svg-color--ffa565, #FFA565);
}

.p0sep6u6h {
  stroke: var(--svg-color--9f6261, #9F6261);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M25.658 3.5L14.86 22.234");
}

.r6vm17glm {
  stop-color: var(--svg-color--bb8b86, #BB8B86);
}

.rpw-a_hmo {
  stop-color: var(--svg-color--ff516d, #FF516D);
  stop-opacity: 0;
}

.rwrz_ebce {
  stop-color: var(--svg-color--aa9fb9, #AA9FB9);
}

.t95r3ob6z {
  stop-color: var(--svg-color--6e4240, #6E4240);
}

.ungwku9vn {
  stop-color: var(--svg-color--ff8655, #FF8655);
}

.vj64ivb0i {
  d: path("m9.704 23.328l-5.14 4.805c-.594.601-.228 1.476.5 1.476h7.515c2.43-.117 3.774-1.195 4.27-2.98l.543-2.09c.398-1.93-.24-3.241-1.586-4.016c-1.433-.824-3.21-.567-4.286.687z");
}

.vp29wje1f {
  stop-color: var(--svg-color--a57667, #A57667);
}

</style>
