<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#infGdeb)" class="e6km55buo"/><g filter="url(#iNmlpny)"><path fill="url(#iEm75Bd)" class="e_w0s1blv"/><path fill="url(#iAs5EVc)" class="e_w0s1blv"/></g><path fill="url(#ialY06d)" class="xih839axo"/><g filter="url(#i8zICZb)"><path class="flu4fvxje"/></g><path fill="url(#iV4sZrd)" class="yifqs-83b"/><path fill="url(#ioXtFec)" class="yifqs-83b"/><path fill="url(#iESLUPi)" class="xvn07xbck"/><path fill="url(#iAsNw4b)" class="xvn07xbck"/><path fill="url(#iPKZMuh)" class="itjjclbky"/><path fill="url(#ifFa80b)" class="itjjclbky"/><path fill="url(#ikTLFjc)" class="itjjclbky"/><g filter="url(#iVSzzLb)"><path class="k86us7bhd"/></g><path fill="url(#ihcdwxb)" class="t2293ybtm"/><path fill="url(#iHDHuJe)" class="t2293ybtm"/><path fill="url(#ifwbhbC)" class="t2293ybtm"/><path fill="url(#ienBAIe)" class="ifmb1es9a"/><path fill="url(#iH1waZb)" class="ifmb1es9a"/><path fill="url(#iZhOgBb)" class="trncrh1po"/><g filter="url(#iRmxOrb)"><path stroke="url(#iyQVw8M)" class="qo6fkdb7e"/></g><g filter="url(#iq54T3f)"><path stroke="url(#ihqaBHh)" class="yl00epb_o"/></g><defs><linearGradient id="infGdeb" x1="15.935" x2="15.935" y1="2" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="bj-hoqs-l"/><stop offset="1" class="h0pvfl7_m"/></linearGradient><linearGradient id="iEm75Bd" x1="7.842" x2="18.626" y1="4.423" y2="12.765" gradientUnits="userSpaceOnUse"><stop class="ox6vr20rk"/><stop offset="1" class="vu27gfewb"/></linearGradient><linearGradient id="iAs5EVc" x1="12.188" x2="12.188" y1="13.813" y2="2.406" gradientUnits="userSpaceOnUse"><stop offset=".11" class="txvdbjbnd"/><stop offset=".214" class="ksts61-gq"/></linearGradient><linearGradient id="ialY06d" x1="3.006" x2="28.869" y1="21.214" y2="21.214" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iV4sZrd" x1="15.688" x2="18.356" y1="5.375" y2="22.28" gradientUnits="userSpaceOnUse"><stop offset=".048" class="m4nt8vber"/><stop offset=".327" class="nh2er2hfh"/><stop offset=".686" class="li7gktbmq"/></linearGradient><linearGradient id="ioXtFec" x1="13.314" x2="14.312" y1="7.699" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="vfl5npbks"/><stop offset=".467" class="dqisg1ada"/><stop offset="1" class="yp58i-bcx"/></linearGradient><linearGradient id="iESLUPi" x1="21.386" x2="24.424" y1="7.288" y2="26.241" gradientUnits="userSpaceOnUse"><stop offset=".048" class="pj-pgddud"/><stop offset=".686" class="cqbna6b9k"/></linearGradient><linearGradient id="iAsNw4b" x1="21.531" x2="22.873" y1="11.375" y2="11.549" gradientUnits="userSpaceOnUse"><stop class="xi5mqg34y"/><stop offset=".552" class="xi5mqg34y"/><stop offset="1" class="tk_33jbdg"/></linearGradient><linearGradient id="iPKZMuh" x1="17.578" x2="20.562" y1="5.893" y2="24.872" gradientUnits="userSpaceOnUse"><stop offset=".048" class="pj-pgddud"/><stop offset=".686" class="cqbna6b9k"/></linearGradient><linearGradient id="ifFa80b" x1="17.344" x2="18.715" y1="9.875" y2="10.088" gradientUnits="userSpaceOnUse"><stop class="yaosmtbxw"/><stop offset=".552" class="ak-ybobiq"/><stop offset="1" class="tk_33jbdg"/></linearGradient><linearGradient id="ihcdwxb" x1="8.654" x2="11.502" y1="6.342" y2="25.38" gradientUnits="userSpaceOnUse"><stop offset=".048" class="p08l0su3y"/><stop offset=".686" class="e7wqer7rn"/></linearGradient><linearGradient id="iHDHuJe" x1="7.031" x2="8.328" y1="10.25" y2="10.063" gradientUnits="userSpaceOnUse"><stop class="yaosmtbxw"/><stop offset=".552" class="ak-ybobiq"/><stop offset="1" class="tk_33jbdg"/></linearGradient><linearGradient id="ienBAIe" x1="12.518" x2="15.73" y1="7.302" y2="26.165" gradientUnits="userSpaceOnUse"><stop offset=".048" class="pj-pgddud"/><stop offset=".686" class="cqbna6b9k"/></linearGradient><linearGradient id="iH1waZb" x1="11.096" x2="12.348" y1="11.199" y2="11.077" gradientUnits="userSpaceOnUse"><stop class="yaosmtbxw"/><stop offset=".552" class="ak-ybobiq"/><stop offset="1" class="tk_33jbdg"/></linearGradient><linearGradient id="iZhOgBb" x1="5.313" x2="27.938" y1="22.5" y2="19.688" gradientUnits="userSpaceOnUse"><stop class="zhgfnc3kh"/><stop offset=".161" class="ah38k1own"/><stop offset=".49" class="fjvun9brv"/><stop offset="1" class="ruf-4bq0k"/></linearGradient><linearGradient id="ihqaBHh" x1="17.563" x2="26.825" y1="13.438" y2="16.737" gradientUnits="userSpaceOnUse"><stop class="fjxbc4b8r"/><stop offset=".521" class="gmx1qbbub"/><stop offset=".623" class="vfhuojt7f"/></linearGradient><filter id="iNmlpny" width="25.594" height="19.624" x="3.344" y="1.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30853" stdDeviation=".25"/></filter><filter id="i8zICZb" width="8.558" height="23.484" x="10" y="1.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30853" stdDeviation="1"/></filter><filter id="iVSzzLb" width="9.87" height="18.603" x="3.431" y="4.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30853" stdDeviation="1"/></filter><filter id="iRmxOrb" width="8.3" height="7.488" x="7.944" y="12.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30853" stdDeviation=".125"/></filter><filter id="iq54T3f" width="12.628" height="7.456" x="16.147" y="12.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30853" stdDeviation=".125"/></filter><radialGradient id="ikTLFjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 7.125 -3.65411 -.57696 20.625 19)" gradientUnits="userSpaceOnUse"><stop class="q3lyp3b3w"/><stop offset="1" class="vmlsa2bvj"/></radialGradient><radialGradient id="ifwbhbC" cx="0" cy="0" r="1" gradientTransform="rotate(82.763 -3.064 14.67)scale(9.9227 4.66075)" gradientUnits="userSpaceOnUse"><stop class="a64fmp1pd"/><stop offset="1" class="vm4t3l9rq"/></radialGradient><radialGradient id="iyQVw8M" cx="0" cy="0" r="1" gradientTransform="matrix(3 4.28125 -4.8014 3.36449 10.75 15.5)" gradientUnits="userSpaceOnUse"><stop class="j09xuzbll"/><stop offset="1" class="fjxbc4b8r"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:french-fries" /></template>
<style>
.a64fmp1pd {
  stop-color: var(--svg-color--a7650a, #A7650A);
}

.ah38k1own {
  stop-color: var(--svg-color--dd2b5d, #DD2B5D);
}

.ak-ybobiq {
  stop-color: var(--svg-color--caa92e, #CAA92E);
}

.bj-hoqs-l {
  stop-color: var(--svg-color--b22d50, #B22D50);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cqbna6b9k {
  stop-color: var(--svg-color--f7bc4a, #F7BC4A);
}

.dqisg1ada {
  stop-color: var(--svg-color--dbad29, #DBAD29);
}

.e_w0s1blv {
  d: path("M28.438 12.516c0-5.588-4.393-10.11-9.82-10.11h-4.954c-5.419 0-9.82 4.522-9.82 10.11h4.468v8.514h15.657v-8.514z");
}

.e6km55buo {
  d: path("M28.87 12.33C28.87 6.62 24.25 2 18.54 2h-5.21C7.63 2 3 6.62 3 12.33h4.7v8.7h16.47v-8.7z");
}

.e7wqer7rn {
  stop-color: var(--svg-color--d3a538, #D3A538);
}

.fjvun9brv {
  stop-color: var(--svg-color--e92f74, #E92F74);
}

.fjxbc4b8r {
  stop-color: var(--svg-color--fb5471, #FB5471);
  stop-opacity: 0;
}

.flu4fvxje {
  fill: var(--svg-color--9a1b2b, #9A1B2B);
  d: path("M12 5.062c-.005-.56 1.352-1.018 1.766-1.265c.276-.003 2.619.422 2.621.698l.17 18.25a.5.5 0 0 1-.495.504l-3.387.032a.5.5 0 0 1-.505-.496z");
}

.ft5dv1b6b {
  fill: none;
}

.gmx1qbbub {
  stop-color: var(--svg-color--de316b, #DE316B);
}

.h0pvfl7_m {
  stop-color: var(--svg-color--a7273c, #A7273C);
}

.ifmb1es9a {
  d: path("M10.68 7.932a.5.5 0 0 1 .448-.547l3.37-.336a.5.5 0 0 1 .548.449l1.805 18.16a.5.5 0 0 1-.448.547l-3.37.335a.5.5 0 0 1-.548-.448z");
}

.itjjclbky {
  d: path("M17.929 6.073a.5.5 0 0 1 .56-.432l3.36.436a.5.5 0 0 1 .431.56l-2.344 18.098a.5.5 0 0 1-.56.432l-3.36-.435a.5.5 0 0 1-.432-.56z");
}

.j09xuzbll {
  stop-color: var(--svg-color--ff6983, #FF6983);
}

.k86us7bhd {
  fill: var(--svg-color--93142a, #93142A);
  d: path("M5.433 8.797c-.054-.44 1.028-1.388 1.601-1.865a.36.36 0 0 1 .244-.09c.574.024 2.458.309 2.494.555l1.524 12.972a.5.5 0 0 1-.421.569l-3.35.5a.5.5 0 0 1-.568-.414l-.001-.007z");
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.ksts61-gq {
  stop-color: var(--svg-color--94273b, #94273B);
  stop-opacity: 0;
}

.li7gktbmq {
  stop-color: var(--svg-color--995c11, #995C11);
}

.m4nt8vber {
  stop-color: var(--svg-color--fee654, #FEE654);
}

.nh2er2hfh {
  stop-color: var(--svg-color--cb9a28, #CB9A28);
}

.ox6vr20rk {
  stop-color: var(--svg-color--b5425f, #B5425F);
}

.p08l0su3y {
  stop-color: var(--svg-color--fde252, #FDE252);
}

.pj-pgddud {
  stop-color: var(--svg-color--ffe855, #FFE855);
}

.q3lyp3b3w {
  stop-color: var(--svg-color--b96d11, #B96D11);
}

.qo6fkdb7e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M8.344 13.094c.27 2.27 2.406 6.687 7.5 6.687");
}

.ruf-4bq0k {
  stop-color: var(--svg-color--f2368c, #F2368C);
}

.t2293ybtm {
  d: path("M6.558 7.161a.5.5 0 0 1 .42-.568l3.351-.501a.5.5 0 0 1 .569.42l2.7 18.05a.5.5 0 0 1-.421.568l-3.35.5a.5.5 0 0 1-.569-.42z");
}

.tk_33jbdg {
  stop-color: var(--svg-color--cfab2b, #CFAB2B);
  stop-opacity: 0;
}

.trncrh1po {
  d: path("M24.35 12.33c-.7 0-1.28.51-1.4 1.2c-.59 3.34-3.5 5.88-7.01 5.88s-6.42-2.54-7.01-5.88c-.12-.69-.7-1.2-1.4-1.2H3.01l3.63 15.96a2.32 2.32 0 0 0 2.27 1.81h14.06c1.09 0 2.03-.75 2.27-1.81l3.63-15.96z");
}

.txvdbjbnd {
  stop-color: var(--svg-color--902438, #902438);
}

.vfhuojt7f {
  stop-color: var(--svg-color--fc5396, #FC5396);
}

.vfl5npbks {
  stop-color: var(--svg-color--d3a524, #D3A524);
}

.vm4t3l9rq {
  stop-color: var(--svg-color--a15d0a, #A15D0A);
  stop-opacity: 0;
}

.vmlsa2bvj {
  stop-color: var(--svg-color--c07617, #C07617);
  stop-opacity: 0;
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vu27gfewb {
  stop-color: var(--svg-color--b74561, #B74561);
  stop-opacity: 0;
}

.xi5mqg34y {
  stop-color: var(--svg-color--dda80e, #DDA80E);
}

.xih839axo {
  d: path("M23.06 12.33v.1c0 3.93-3.19 7.12-7.12 7.12s-7.12-3.19-7.12-7.12v-.1H3.01l3.63 15.96a2.32 2.32 0 0 0 2.27 1.81h14.06c1.09 0 2.03-.75 2.27-1.81l3.63-15.96z");
}

.xvn07xbck {
  d: path("M21.64 7.471a.5.5 0 0 1 .558-.435l3.362.41a.5.5 0 0 1 .436.557l-2.21 18.115a.5.5 0 0 1-.556.436l-3.363-.41a.5.5 0 0 1-.436-.557z");
}

.yaosmtbxw {
  stop-color: var(--svg-color--ba8f22, #BA8F22);
}

.yifqs-83b {
  d: path("M13.005 4.128a.5.5 0 0 1 .495-.504l3.387-.032a.5.5 0 0 1 .505.495l.17 18.25a.5.5 0 0 1-.495.504l-3.387.032a.5.5 0 0 1-.505-.496z");
}

.yl00epb_o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m28.375 12.938l-4.734.078c-.297 0-.42.418-.47.718c-.144.867-1.843 5.86-6.624 5.86");
}

.yp58i-bcx {
  stop-color: var(--svg-color--d1a71e, #D1A71E);
  stop-opacity: 0;
}

.zhgfnc3kh {
  stop-color: var(--svg-color--bb2c41, #BB2C41);
}

</style>
