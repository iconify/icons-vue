<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iXtXfBV)" class="jeyxs9max"/><path fill="url(#iS7CJRb)" class="jeyxs9max"/><path fill="url(#iknvCKb)" class="jeyxs9max"/><path fill="url(#isjgG1c)" class="jeyxs9max"/><path fill="url(#i6U7E1c)" class="jeyxs9max"/><path fill="url(#i4aPJ8c)" class="jeyxs9max"/><path fill="url(#iCDxuje)" class="jeyxs9max"/><path fill="url(#iJwKyiG)" class="jeyxs9max"/><path fill="url(#iHxg63d)" class="jeyxs9max"/><path fill="url(#i8SmsQe)" class="qc2znfr6m"/><g filter="url(#ir4rJ7N)" class="ljb4srbfs"><path fill="url(#i4nHYRc)" class="jlxo0n05v"/><path fill="url(#iNM5vYc)" class="jlxo0n05v"/></g><g filter="url(#inysRLX)"><path fill="url(#iJYee7b)" class="jmr_ddbsb"/></g><g filter="url(#idvsQZd)"><path fill="url(#iXnfPFT)" class="rdhzmc5-x"/></g><g filter="url(#ip2l1fc)"><path stroke="url(#iiLT4re)" class="x7gjtjbtc"/></g><g filter="url(#iNkQigd)"><path fill="url(#izK1gvc)" class="gb2k_hnkv"/></g><defs><radialGradient id="iXtXfBV" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.8283 -29.4623 0 15.77 5.633)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="br941yb6s"/><stop offset=".528" class="i799m-_6c"/><stop offset="1" class="ipny02bgt"/></radialGradient><radialGradient id="iS7CJRb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.293 33.282 3.665)scale(30.305 28.3828)" gradientUnits="userSpaceOnUse"><stop offset=".801" class="way435bra"/><stop offset="1" class="doy93llby"/></radialGradient><radialGradient id="isjgG1c" cx="0" cy="0" r="1" gradientTransform="matrix(-13.56307 11.63852 -16.66111 -19.41621 22.5 11.462)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="w1oofcewg"/><stop offset="1" class="kh_a_2bgq"/></radialGradient><radialGradient id="iCDxuje" cx="0" cy="0" r="1" gradientTransform="rotate(-154.781 12.673 5.02)scale(21.4163 18.6261)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="qzkvvtihj"/><stop offset="1" class="kh_a_2bgq"/></radialGradient><radialGradient id="iJwKyiG" cx="0" cy="0" r="1" gradientTransform="rotate(-129.075 12.839 4.904)scale(18.839 27.0981)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="h228e0bmw"/><stop offset="1" class="irhfekz4s"/></radialGradient><radialGradient id="iHxg63d" cx="0" cy="0" r="1" gradientTransform="rotate(89.633 .771 14.681)scale(17.9104 20.5242)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="g286gacdc"/><stop offset=".934" class="v9g9wjbgv"/></radialGradient><radialGradient id="iJYee7b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9375 11.18754 -4.43076 -2.35151 27.334 7.538)" gradientUnits="userSpaceOnUse"><stop class="doy93llby"/><stop offset="1" class="dt0g-isko"/></radialGradient><radialGradient id="iXnfPFT" cx="0" cy="0" r="1" gradientTransform="rotate(-126.943 12.424 4.244)scale(9.77501 4.23082)" gradientUnits="userSpaceOnUse"><stop class="doy93llby"/><stop offset="1" class="way435bra"/></radialGradient><linearGradient id="iknvCKb" x1="17.632" x2="25.645" y1="16.133" y2="25.668" gradientUnits="userSpaceOnUse"><stop offset=".74" class="g286gacdc"/><stop offset=".934" class="v9g9wjbgv"/></linearGradient><linearGradient id="i6U7E1c" x1="11.687" x2="11.687" y1="29.538" y2="21.975" gradientUnits="userSpaceOnUse"><stop class="wrlfuib6t"/><stop offset="1" class="mcajaqm6l"/></linearGradient><linearGradient id="i4aPJ8c" x1="16.639" x2="7.188" y1="16.53" y2="27.18" gradientUnits="userSpaceOnUse"><stop offset=".694" class="g286gacdc"/><stop offset=".885" class="v9g9wjbgv"/></linearGradient><linearGradient id="i8SmsQe" x1="17.125" x2="18.887" y1="7.419" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="e8eh7bkvs"/><stop offset=".68" class="h228e0bmw"/></linearGradient><linearGradient id="i4nHYRc" x1="17.312" x2="27" y1="18.913" y2="-2.087" gradientUnits="userSpaceOnUse"><stop offset=".105" class="lfxs9vaep"/><stop offset="1" class="h0_7a_bey"/></linearGradient><linearGradient id="iNM5vYc" x1="14.937" x2="19.062" y1="9.288" y2="7.726" gradientUnits="userSpaceOnUse"><stop offset=".105" class="lfxs9vaep"/><stop offset="1" class="h0_7a_bey"/></linearGradient><linearGradient id="iiLT4re" x1="7.063" x2="13.563" y1="6.321" y2="6.962" gradientUnits="userSpaceOnUse"><stop class="doy93llby"/><stop offset="1" class="way435bra"/></linearGradient><linearGradient id="izK1gvc" x1="18.563" x2="10.563" y1="30.399" y2="16.649" gradientUnits="userSpaceOnUse"><stop class="d7sq8hb3c"/><stop offset="1" class="b7umbu0lw"/></linearGradient><filter id="ir4rJ7N" width="10.436" height="15.679" x="14.687" y="4.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6120" stdDeviation="1"/></filter><filter id="inysRLX" width="14.114" height="17.881" x="16.229" y="4.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6120" stdDeviation=".75"/></filter><filter id="idvsQZd" width="12.852" height="21.845" x="5.192" y="3.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6120" stdDeviation="1.5"/></filter><filter id="ip2l1fc" width="8.649" height="5.715" x="7.316" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6120" stdDeviation=".5"/></filter><filter id="iNkQigd" width="16" height="21.875" x="1.625" y="8.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6120" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:brown-heart" /></template>
<style>
.b7umbu0lw {
  stop-color: var(--svg-color--924563, #924563);
  stop-opacity: 0;
}

.br941yb6s {
  stop-color: var(--svg-color--bc7c65, #BC7C65);
}

.d7sq8hb3c {
  stop-color: var(--svg-color--924563, #924563);
}

.doy93llby {
  stop-color: var(--svg-color--d69f8e, #D69F8E);
}

.dt0g-isko {
  stop-color: var(--svg-color--d6928e, #D6928E);
  stop-opacity: 0;
}

.e8eh7bkvs {
  stop-color: var(--svg-color--915c4e, #915C4E);
}

.ft5dv1b6b {
  fill: none;
}

.g286gacdc {
  stop-color: var(--svg-color--c172ff, #C172FF);
  stop-opacity: 0;
}

.gb2k_hnkv {
  d: path("M3.625 13.524c2.063 8.063 9.48 13.23 12 14.813c-2.9-5.25-5.562-15.542-5.625-17.875z");
}

.h0_7a_bey {
  stop-color: var(--svg-color--a55f50, #A55F50);
  stop-opacity: 0;
}

.h228e0bmw {
  stop-color: var(--svg-color--905c4e, #905C4E);
  stop-opacity: 0;
}

.i799m-_6c {
  stop-color: var(--svg-color--a55f63, #A55F63);
}

.ipny02bgt {
  stop-color: var(--svg-color--97505e, #97505E);
}

.irhfekz4s {
  stop-color: var(--svg-color--7e4f42, #7E4F42);
}

.jeyxs9max {
  d: path("M15.104 29.202a1.73 1.73 0 0 0 1.71-.023c3.584-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.025-1.897 1.542c-.238.234-.657.258-.904.034c-.69-.63-1.771-1.436-2.465-1.905c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.11 12.476");
}

.jlxo0n05v {
  d: path("M16.687 9.491v7.802c0 1.07 1.586 1.46 2.12.533c2.842-4.93 6.05-9.887 3.214-10.855c-2.428-.83-3.458.128-5.063 1.836a1 1 0 0 0-.271.684");
}

.jmr_ddbsb {
  d: path("M26.242 6.286c2.598 1.069 3.38 5.152 1.748 9.118c-1.633 3.967-5.063 6.316-7.66 5.247c-2.599-1.07-3.381-5.152-1.749-9.12c1.633-3.966 5.063-6.315 7.661-5.245");
}

.kh_a_2bgq {
  stop-color: var(--svg-color--6c384f, #6C384F);
}

.lfxs9vaep {
  stop-color: var(--svg-color--975243, #975243);
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.mcajaqm6l {
  stop-color: var(--svg-color--9f4e6e, #9F4E6E);
  stop-opacity: 0;
}

.qc2znfr6m {
  d: path("m15.219 7.806l.347.318c.954.873 2.499.63 3.365-.331c.913-1.014 2.14-2.063 3.624-2.791c-1.403.03-2.841.507-4.148 1.534q-.228.178-.475.366c-.497.38-1.027.786-1.422 1.175c-.238.234-.657.258-.904.034q-.18-.164-.389-.34z");
}

.qzkvvtihj {
  stop-color: var(--svg-color--945746, #945746);
  stop-opacity: 0;
}

.rdhzmc5-x {
  d: path("m14.84 9.18l.205 13.407C8.17 15.899 6.939 8.734 9.277 7.127c1.67-1.147 4.813.491 5.563 2.054");
}

.v9g9wjbgv {
  stop-color: var(--svg-color--c172ff, #C172FF);
}

.w1oofcewg {
  stop-color: var(--svg-color--a45843, #A45843);
  stop-opacity: 0;
}

.way435bra {
  stop-color: var(--svg-color--d69f8e, #D69F8E);
  stop-opacity: 0;
}

.wrlfuib6t {
  stop-color: var(--svg-color--9f4e6e, #9F4E6E);
}

.x7gjtjbtc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.44 6.413c1.087-.135 4.025 0 6.4 3.433");
}

</style>
