<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipowaId)" class="fy2jrdb-t"><path stroke="url(#iqNvrab)" class="pz3plq8nq"/><path stroke="url(#iXievfd)" class="pz3plq8nq"/></g><g filter="url(#irjpmSd)" class="zlv0v5b4v"><path stroke="url(#iVyRn4d)" class="rn786ob7f"/><path stroke="url(#ixswjbm)" class="rn786ob7f"/></g><g filter="url(#ipsWOIN)" class="fy2jrdb-t"><path class="kjl109bau"/><path stroke="url(#ibDygbU)" class="vn9_zlblu"/></g><g filter="url(#iXzqEVc)"><path stroke="url(#iWn1ADe)" class="j2a5ocbju"/></g><path fill="url(#iHrIcZb)" class="yxm8xbbpf"/><path fill="url(#iKKWFud)" class="yxm8xbbpf"/><path class="ak-eoenbz"/><path fill="url(#iDb6GWc)" class="ij9daj4gg"/><path fill="url(#iyXE5uI)" class="ij9daj4gg"/><path fill="url(#iFXsdKa)" class="lervfl-1u"/><path fill="url(#iunxoab)" class="ua62lpbps"/><path fill="url(#i6sTCfb)" class="tcl7yf21m"/><path fill="url(#iCdaeSd)" class="vphuc8b2f"/><path fill="url(#i4oZECb)" class="gvjdq3bca"/><path fill="url(#ixFOgZm)" class="kfkgu_mmc"/><path fill="url(#i9KEUyd)" class="kfkgu_mmc"/><path fill="url(#iCcGSfe)" class="kfkgu_mmc"/><path fill="url(#iwcmODe)" class="uquefjl0h"/><path fill="url(#i9tWcrU)" class="uquefjl0h"/><path fill="url(#i3Y9BQc)" class="wut-1geie"/><path fill="url(#i1YuNKc)" class="wut-1geie"/><path fill="url(#imgSfPe)" class="rml9u-9br"/><path fill="url(#ivrBP5d)" class="rml9u-9br"/><path fill="url(#icAteXg)" class="vf7ib4asj"/><path fill="url(#i3Vu2Bc)" class="vf7ib4asj"/><path fill="url(#intECXb)" class="tjv4sgboc"/><path fill="url(#iRKOCCo)" class="tjv4sgboc"/><path fill="url(#iR8qrJd)" class="ufduq6bqd"/><path fill="url(#ifwvlAe)" class="ufduq6bqd"/><path fill="url(#iztyQSd)" class="ufduq6bqd"/><g filter="url(#iLLyW4d)" class="fy2jrdb-t"><path stroke="url(#i4O6fWb)" class="n45go93ed"/><path stroke="url(#i5Z8zQc)" class="n45go93ed"/></g><g filter="url(#irhHtmb)"><path stroke="url(#i004Eid)" class="k4k83lbfm"/></g><g filter="url(#inYOYNd)"><path fill="url(#iF4nlSb)" class="un86qwbjc"/></g><g filter="url(#ijzCuqc)" class="zlv0v5b4v"><path stroke="url(#iwUlsbe)" class="sec2-kk4v"/><path stroke="url(#imFRYtb)" class="sec2-kk4v"/></g><defs><linearGradient id="iqNvrab" x1="21.649" x2="20.546" y1="3.063" y2="11.773" gradientUnits="userSpaceOnUse"><stop class="tivvd8c7q"/><stop offset="1" class="vr7bwyb6p"/></linearGradient><linearGradient id="iVyRn4d" x1="19.647" x2="19.25" y1="10.75" y2="6.438" gradientUnits="userSpaceOnUse"><stop class="f5h_q5_lv"/><stop offset="1" class="g3lpz24jc"/></linearGradient><linearGradient id="ixswjbm" x1="22.313" x2="20.938" y1="2.719" y2="4.063" gradientUnits="userSpaceOnUse"><stop offset=".294" class="f5h_q5_lv"/><stop offset="1" class="g3lpz24jc"/></linearGradient><linearGradient id="iHrIcZb" x1="24.407" x2="23.375" y1="5.469" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="grzg3rggd"/><stop offset=".341" class="rfdfqxdjw"/><stop offset=".907" class="zx1j7xbld"/></linearGradient><linearGradient id="iDb6GWc" x1="16.813" x2="17.532" y1="13" y2="12.281" gradientUnits="userSpaceOnUse"><stop offset=".054" class="efmq-9bpv"/><stop offset="1" class="j3k6fj13p"/></linearGradient><linearGradient id="iyXE5uI" x1="18.516" x2="18.047" y1="12.25" y2="12.891" gradientUnits="userSpaceOnUse"><stop offset=".139" class="f2yf-ebpb"/><stop offset="1" class="lh0zyus_j"/></linearGradient><linearGradient id="iFXsdKa" x1="16.032" x2="15" y1="14.261" y2="15.266" gradientUnits="userSpaceOnUse"><stop class="i1vchparr"/><stop offset=".366" class="z69o6hbzl"/><stop offset="1" class="d7o3b-b9m"/></linearGradient><linearGradient id="iunxoab" x1="13.805" x2="12.774" y1="16.418" y2="17.422" gradientUnits="userSpaceOnUse"><stop class="i1vchparr"/><stop offset=".366" class="z69o6hbzl"/><stop offset="1" class="d7o3b-b9m"/></linearGradient><linearGradient id="i6sTCfb" x1="9.25" x2="8.158" y1="21.344" y2="22.512" gradientUnits="userSpaceOnUse"><stop class="qckhec4ds"/><stop offset=".346" class="klw4ls7yg"/><stop offset=".849" class="jodoi-b9p"/></linearGradient><linearGradient id="iCdaeSd" x1="6.857" x2="5.79" y1="23.419" y2="24.506" gradientUnits="userSpaceOnUse"><stop class="d7s3zd3qb"/><stop offset=".362" class="klw4ls7yg"/><stop offset=".861" class="jodoi-b9p"/></linearGradient><linearGradient id="i4oZECb" x1="22.366" x2="21.446" y1="7.853" y2="8.704" gradientUnits="userSpaceOnUse"><stop class="grzg3rggd"/><stop offset=".341" class="rfdfqxdjw"/><stop offset=".907" class="zx1j7xbld"/></linearGradient><linearGradient id="ixFOgZm" x1="27.39" x2="26.342" y1="8.441" y2="9.494" gradientUnits="userSpaceOnUse"><stop class="qoyc2tbjl"/><stop offset=".341" class="pqewn0hgp"/><stop offset=".907" class="u1ht2sb5g"/></linearGradient><linearGradient id="i9KEUyd" x1="26.621" x2="26.353" y1="9.246" y2="9.486" gradientUnits="userSpaceOnUse"><stop class="otg-mxbyr"/><stop offset="1" class="yyts8d4zi"/></linearGradient><linearGradient id="iCcGSfe" x1="25.18" x2="25.657" y1="6.469" y2="6.914" gradientUnits="userSpaceOnUse"><stop offset=".434" class="srt_5kjkn"/><stop offset="1" class="rpy6_7dma"/></linearGradient><linearGradient id="iwcmODe" x1="20.172" x2="19.227" y1="14.539" y2="15.375" gradientUnits="userSpaceOnUse"><stop class="tywpdacmb"/><stop offset=".346" class="r-9mq9xbi"/><stop offset=".849" class="pjfnjt6pu"/></linearGradient><linearGradient id="i9tWcrU" x1="18.532" x2="18.719" y1="13.563" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="eqg56dr1x"/><stop offset="1" class="hsghehblj"/></linearGradient><linearGradient id="i3Y9BQc" x1="16.75" x2="15.547" y1="19.234" y2="20.406" gradientUnits="userSpaceOnUse"><stop class="tywpdacmb"/><stop offset=".346" class="r-9mq9xbi"/><stop offset=".849" class="ogqlplb_q"/></linearGradient><linearGradient id="i1YuNKc" x1="14.242" x2="14.414" y1="17.797" y2="17.969" gradientUnits="userSpaceOnUse"><stop class="eqg56dr1x"/><stop offset="1" class="hsghehblj"/></linearGradient><linearGradient id="imgSfPe" x1="18.977" x2="17.774" y1="17.078" y2="18.25" gradientUnits="userSpaceOnUse"><stop class="tywpdacmb"/><stop offset=".346" class="r-9mq9xbi"/><stop offset=".849" class="pjfnjt6pu"/></linearGradient><linearGradient id="ivrBP5d" x1="16.469" x2="16.641" y1="15.641" y2="15.813" gradientUnits="userSpaceOnUse"><stop class="eqg56dr1x"/><stop offset="1" class="hsghehblj"/></linearGradient><linearGradient id="icAteXg" x1="10.952" x2="9.94" y1="23.488" y2="24.399" gradientUnits="userSpaceOnUse"><stop class="amp48jbrn"/><stop offset=".399" class="og60x0b8i"/><stop offset="1" class="it_ryabql"/></linearGradient><linearGradient id="i3Vu2Bc" x1="9.5" x2="9.821" y1="22.325" y2="22.648" gradientUnits="userSpaceOnUse"><stop offset=".46" class="srt_5kjkn"/><stop offset=".905" class="kmylppb1i"/></linearGradient><linearGradient id="intECXb" x1="9.329" x2="8.23" y1="25.724" y2="26.894" gradientUnits="userSpaceOnUse"><stop class="amp48jbrn"/><stop offset=".399" class="og60x0b8i"/><stop offset="1" class="it_ryabql"/></linearGradient><linearGradient id="iRKOCCo" x1="7.529" x2="7.797" y1="24.471" y2="24.734" gradientUnits="userSpaceOnUse"><stop offset=".268" class="srt_5kjkn"/><stop offset=".905" class="kmylppb1i"/></linearGradient><linearGradient id="iR8qrJd" x1="24.875" x2="23.797" y1="10.141" y2="11.219" gradientUnits="userSpaceOnUse"><stop class="qoyc2tbjl"/><stop offset=".341" class="pqewn0hgp"/><stop offset=".907" class="u1ht2sb5g"/></linearGradient><linearGradient id="ifwvlAe" x1="24.152" x2="23.825" y1="10.891" y2="11.308" gradientUnits="userSpaceOnUse"><stop class="otg-mxbyr"/><stop offset="1" class="yyts8d4zi"/></linearGradient><linearGradient id="iztyQSd" x1="22.946" x2="23.352" y1="8.672" y2="9.063" gradientUnits="userSpaceOnUse"><stop offset=".46" class="srt_5kjkn"/><stop offset="1" class="rpy6_7dma"/></linearGradient><linearGradient id="i4O6fWb" x1="3.151" x2="10.608" y1="21.711" y2="9.21" gradientUnits="userSpaceOnUse"><stop class="gv968nbim"/><stop offset="1" class="hxylawz-t"/></linearGradient><linearGradient id="iF4nlSb" x1="30" x2="19.125" y1="9.75" y2="19.375" gradientUnits="userSpaceOnUse"><stop offset=".505" class="ag30b_bcd"/><stop offset="1" class="ozfhlkbae"/></linearGradient><linearGradient id="iwUlsbe" x1="29.885" x2="19.485" y1="9.712" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="wumuho9xv"/><stop offset="1" class="ybkny0oot"/></linearGradient><linearGradient id="imFRYtb" x1="12.005" x2="12.595" y1="18.377" y2="13.85" gradientUnits="userSpaceOnUse"><stop class="nadkffb-q"/><stop offset="1" class="g8_ztm4ee"/></linearGradient><filter id="ipowaId" width="4.656" height="10.771" x="18.343" y="2.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.219608 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24963"/></filter><filter id="irjpmSd" width="4.23" height="10.605" x="18.748" y="2.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24963" stdDeviation=".3"/></filter><filter id="ipsWOIN" width="5.156" height="10.771" x="9.484" y="19.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.54902 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24963"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.458824 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_24963" result="effect2_innerShadow_18_24963"/></filter><filter id="iXzqEVc" width="3.806" height="10.17" x="9.994" y="19.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24963" stdDeviation=".25"/></filter><filter id="iLLyW4d" width="20.608" height="11.724" x="2.051" y="10.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.223529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24963"/></filter><filter id="irhHtmb" width="20.108" height="11.473" x="2.516" y="11.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24963" stdDeviation=".325"/></filter><filter id="inYOYNd" width="20.433" height="9.894" x="9.975" y="9.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.419608 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24963"/></filter><filter id="ijzCuqc" width="19.833" height="9.667" x="10.373" y="9.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24963" stdDeviation=".3"/></filter><radialGradient id="iXievfd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.745 13.385 .102)scale(4.59801 1.61374)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="kvctmlblh"/><stop offset="1" class="y606j309q"/></radialGradient><radialGradient id="ibDygbU" cx="0" cy="0" r="1" gradientTransform="matrix(3.22363 2.00581 -.80881 1.29988 11.931 20.877)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="yczw4ox8m"/><stop offset="1" class="r--okunoy"/></radialGradient><radialGradient id="iWn1ADe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.1578 -.36257 .31881 -4.53532 13.765 24.582)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="h43j_so_n"/><stop offset="1" class="gf7if6bje"/></radialGradient><radialGradient id="iKKWFud" cx="0" cy="0" r="1" gradientTransform="rotate(137.911 10.579 6.236)scale(.97906 .14025)" gradientUnits="userSpaceOnUse"><stop class="i9a0reb8x"/><stop offset="1" class="aq2_1ab9j"/></radialGradient><radialGradient id="i5Z8zQc" cx="0" cy="0" r="1" gradientTransform="matrix(7.12866 4.5625 -1.3731 2.14539 21.31 13.125)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="kvctmlblh"/><stop offset="1" class="y606j309q"/></radialGradient><radialGradient id="i004Eid" cx="0" cy="0" r="1" gradientTransform="matrix(-13.49639 -5.1562 2.1291 -5.57295 21.649 19.56)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="ate4wobbv"/><stop offset="1" class="l88mdubmq"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dna" /></template>
<style>
.ag30b_bcd {
  stop-color: var(--svg-color--4fd4ff, #4FD4FF);
}

.ak-eoenbz {
  fill: var(--svg-color--53b6ff, #53B6FF);
  d: path("M15.131 11.17a2.5 2.5 0 0 1 .918-.917l2.837 2.836a.15.15 0 0 1 0 .213l-.706.705a.15.15 0 0 1-.212 0z");
}

.amp48jbrn {
  stop-color: var(--svg-color--2ba2ff, #2BA2FF);
}

.aq2_1ab9j {
  stop-color: var(--svg-color--f84770, #F84770);
  stop-opacity: 0;
}

.ate4wobbv {
  stop-color: var(--svg-color--fb527b, #FB527B);
}

.d7o3b-b9m {
  stop-color: var(--svg-color--4172e9, #4172E9);
}

.d7s3zd3qb {
  stop-color: var(--svg-color--fd3377, #FD3377);
}

.efmq-9bpv {
  stop-color: var(--svg-color--4c6de8, #4C6DE8);
}

.eqg56dr1x {
  stop-color: var(--svg-color--80215c, #80215C);
}

.f2yf-ebpb {
  stop-color: var(--svg-color--1c5fe3, #1C5FE3);
}

.f5h_q5_lv {
  stop-color: var(--svg-color--fd577a, #FD577A);
}

.ft5dv1b6b {
  fill: none;
}

.fy2jrdb-t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-2px, 2.2px);
}

.g3lpz24jc {
  stop-color: var(--svg-color--fd577a, #FD577A);
  stop-opacity: 0;
}

.g8_ztm4ee {
  stop-color: var(--svg-color--56b5ff, #56B5FF);
  stop-opacity: 0;
}

.gf7if6bje {
  stop-color: var(--svg-color--63cbff, #63CBFF);
  stop-opacity: 0;
}

.grzg3rggd {
  stop-color: var(--svg-color--f72d60, #F72D60);
}

.gv968nbim {
  stop-color: var(--svg-color--fa2e8b, #FA2E8B);
}

.gvjdq3bca {
  d: path("M20.508 7.805c-.039-.735.265-1.469.265-1.469l2.384 2.383a.15.15 0 0 1 0 .213l-.706.705a.15.15 0 0 1-.212 0z");
}

.h43j_so_n {
  stop-color: var(--svg-color--63cbff, #63CBFF);
}

.hsghehblj {
  stop-color: var(--svg-color--80215c, #80215C);
  stop-opacity: 0;
}

.hxylawz-t {
  stop-color: var(--svg-color--e91865, #E91865);
}

.i1vchparr {
  stop-color: var(--svg-color--34a9ff, #34A9FF);
}

.i9a0reb8x {
  stop-color: var(--svg-color--f84770, #F84770);
}

.ij9daj4gg {
  d: path("M15.131 11.17a2.5 2.5 0 0 1 .918-.917l2.837 2.836a.15.15 0 0 1 0 .213l-.706.705a.15.15 0 0 1-.212 0z");
}

.it_ryabql {
  stop-color: var(--svg-color--447aff, #447AFF);
}

.j2a5ocbju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M10.794 28.867c.828-.693 2.344-2.453 2.196-4.867c-.134-2.177-.781-3.36-.875-3.703");
}

.j3k6fj13p {
  stop-color: var(--svg-color--4c6de8, #4C6DE8);
  stop-opacity: 0;
}

.jodoi-b9p {
  stop-color: var(--svg-color--d23d7e, #D23D7E);
}

.k4k83lbfm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M3.491 21.614c.727-.906 2.55-2.613 5.258-2.46c3.741.21 6.946 3.34 10.531 1.163c3.257-1.976 2.513-6.18 1.529-8.226");
}

.kfkgu_mmc {
  d: path("M28.42 9.6s-.316.68-.9.931l-2.855-2.85a.15.15 0 0 1 0-.213l.706-.706a.15.15 0 0 1 .212 0z");
}

.kjl109bau {
  stroke: var(--svg-color--3ab3ff, #3AB3FF);
  d: path("M10.584 28.867c.828-.693 2.344-2.453 2.195-4.867c-.133-2.177-.78-3.36-.875-3.703");
}

.klw4ls7yg {
  stop-color: var(--svg-color--ff5590, #FF5590);
}

.kmylppb1i {
  stop-color: var(--svg-color--4b97ff, #4B97FF);
  stop-opacity: 0;
}

.kvctmlblh {
  stop-color: var(--svg-color--953853, #953853);
}

.l88mdubmq {
  stop-color: var(--svg-color--fb527b, #FB527B);
  stop-opacity: 0;
}

.lervfl-1u {
  d: path("M13 13.28c.33-.608.918-.918.918-.918l2.837 2.837a.15.15 0 0 1 0 .212l-.706.706a.15.15 0 0 1-.212 0z");
}

.lh0zyus_j {
  stop-color: var(--svg-color--1c5fe3, #1C5FE3);
  stop-opacity: 0;
}

.n45go93ed {
  d: path("M3.151 21.555c.727-.907 2.55-2.614 5.258-2.461c3.741.21 6.946 3.34 10.531 1.164c3.257-1.977 2.513-6.18 1.529-8.227");
}

.nadkffb-q {
  stop-color: var(--svg-color--56b5ff, #56B5FF);
}

.og60x0b8i {
  stop-color: var(--svg-color--51baff, #51BAFF);
}

.ogqlplb_q {
  stop-color: var(--svg-color--8f1c55, #8F1C55);
}

.otg-mxbyr {
  stop-color: var(--svg-color--4bbfff, #4BBFFF);
  stop-opacity: 0;
}

.ozfhlkbae {
  stop-color: var(--svg-color--3d97ff, #3D97FF);
}

.pjfnjt6pu {
  stop-color: var(--svg-color--aa2760, #AA2760);
}

.pqewn0hgp {
  stop-color: var(--svg-color--67f2ff, #67F2FF);
}

.pz3plq8nq {
  d: path("M21.649 3.203c-.828.693-2.344 2.453-2.196 4.867c.134 2.178.781 3.36.875 3.703");
}

.qckhec4ds {
  stop-color: var(--svg-color--c92a66, #C92A66);
}

.qoyc2tbjl {
  stop-color: var(--svg-color--53f1ff, #53F1FF);
}

.r--okunoy {
  stop-color: var(--svg-color--3196ff, #3196FF);
  stop-opacity: 0;
}

.r-9mq9xbi {
  stop-color: var(--svg-color--f73e76, #F73E76);
}

.rfdfqxdjw {
  stop-color: var(--svg-color--f1476d, #F1476D);
}

.rml9u-9br {
  d: path("M19.735 18.18s-.07.585-.699 1.105l-2.991-2.968a.15.15 0 0 1-.001-.213l.705-.705a.15.15 0 0 1 .212 0z");
}

.rn786ob7f {
  d: path("M22.078 2.969c-.828.692-2.57 2.687-2.42 5.101c.133 2.178.78 3.36.874 3.703");
}

.rpy6_7dma {
  stop-color: var(--svg-color--4fc5ff, #4FC5FF);
  stop-opacity: 0;
}

.sec2-kk4v {
  d: path("M29.305 10.253c-.726.906-2.55 2.613-5.257 2.46c-3.598-.202-6.726-3.851-10.532-1.164c-2.217 1.567-2.499 4.396-2.08 6.57");
}

.srt_5kjkn {
  stop-color: var(--svg-color--713490, #713490);
}

.tcl7yf21m {
  d: path("M6.254 20.445c.875-.441 1.516-.308 1.516-.308l2.03 2.012a.15.15 0 0 1 0 .212l-.705.706a.15.15 0 0 1-.212 0z");
}

.tivvd8c7q {
  stop-color: var(--svg-color--e32c5b, #E32C5B);
}

.tjv4sgboc {
  d: path("M10.626 27.27s-.257.4-.885.92l-2.806-2.772a.15.15 0 0 1 0-.213l.705-.705a.15.15 0 0 1 .212 0z");
}

.tywpdacmb {
  stop-color: var(--svg-color--eb2a67, #EB2A67);
}

.u1ht2sb5g {
  stop-color: var(--svg-color--42afff, #42AFFF);
}

.ua62lpbps {
  d: path("M10.773 15.436c.33-.608.918-.918.918-.918l2.837 2.837a.15.15 0 0 1 0 .212l-.706.706a.15.15 0 0 1-.212 0z");
}

.ufduq6bqd {
  d: path("M25.9 11.463s-.357.375-1.46.375l-1.992-1.99a.15.15 0 0 1 0-.212l.706-.706a.15.15 0 0 1 .212 0z");
}

.un86qwbjc {
  d: path("M29.967 11.141a1.1 1.1 0 1 0-1.717-1.376c-.633.79-2.15 2.174-4.337 2.05c-.73-.04-1.475-.26-2.297-.574c-.345-.131-.686-.274-1.044-.422l-.21-.087c-.427-.177-.876-.36-1.333-.521c-.912-.322-1.922-.58-3.005-.54c-1.106.04-2.22.39-3.339 1.18c-1.816 1.283-2.534 3.228-2.68 5.032a9.8 9.8 0 0 0 .102 2.355c.473.11.928.245 1.364.387c.364.12.725.248 1.073.372a7.8 7.8 0 0 1-.346-2.936c.111-1.376.631-2.618 1.756-3.412c.784-.554 1.488-.756 2.151-.78c.687-.026 1.397.136 2.193.417c.396.14.798.302 1.222.478l.2.084c.358.148.733.304 1.11.448c.895.343 1.89.656 2.959.716c3.227.182 5.357-1.848 6.178-2.87");
}

.uquefjl0h {
  d: path("M20.453 14.719s.36 1.023-.27 1.543l-2.005-2.042a.15.15 0 0 1 0-.212l.705-.704a.15.15 0 0 1 .214.002z");
}

.vf7ib4asj {
  d: path("M11.679 24.07s.117.852-.203 1.594l-2.382-2.383a.15.15 0 0 1 0-.212l.706-.706a.15.15 0 0 1 .212 0z");
}

.vn9_zlblu {
  d: path("M10.584 28.867c.828-.693 2.344-2.453 2.195-4.867c-.133-2.177-.78-3.36-.875-3.703");
}

.vphuc8b2f {
  d: path("M3.89 22.37c.33-.608.806-1.016.806-1.016l2.95 2.935a.15.15 0 0 1 0 .212l-.707.706a.15.15 0 0 1-.212 0z");
}

.vr7bwyb6p {
  stop-color: var(--svg-color--d31f63, #D31F63);
}

.wumuho9xv {
  stop-color: var(--svg-color--71f6ff, #71F6FF);
}

.wut-1geie {
  d: path("M17.509 20.336s-.07.586-.7 1.105l-2.991-2.968a.15.15 0 0 1 0-.213l.705-.705a.15.15 0 0 1 .212 0z");
}

.y606j309q {
  stop-color: var(--svg-color--da2562, #DA2562);
  stop-opacity: 0;
}

.ybkny0oot {
  stop-color: var(--svg-color--71f6ff, #71F6FF);
  stop-opacity: 0;
}

.yczw4ox8m {
  stop-color: var(--svg-color--2248c9, #2248C9);
}

.yxm8xbbpf {
  d: path("M21.696 4.71c.33-.607.89-.937.89-.937l2.785 2.777a.15.15 0 0 1 0 .213l-.706.705a.15.15 0 0 1-.212 0z");
}

.yyts8d4zi {
  stop-color: var(--svg-color--6491ce, #6491CE);
}

.z69o6hbzl {
  stop-color: var(--svg-color--60ceff, #60CEFF);
}

.zlv0v5b4v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
}

.zx1j7xbld {
  stop-color: var(--svg-color--a11c56, #A11C56);
}

</style>
