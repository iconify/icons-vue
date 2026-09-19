<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="zs8c4nbhp"/><path fill="url(#iXp7Ige)" class="ndt9elbwa"/><path fill="url(#ioObAdc)" class="ndt9elbwa"/><path fill="url(#iycNBtx)" class="ndt9elbwa"/><g filter="url(#iuML8Qb)"><path class="px5fkcc8a"/><path fill="url(#igyDeMb)" class="eealdrbqw"/><path class="d86jukbwy"/></g><path class="kpz3ielfb"/><path fill="url(#iwraJUO)" class="zmbzgfb5q"/><path fill="url(#iaFiXQb)" class="zmbzgfb5q"/><path fill="url(#iKlZkGS)" class="zmbzgfb5q"/><path fill="url(#i6OCire)" class="zmbzgfb5q"/><g filter="url(#i2SO43c)"><path fill="url(#i9uH7Oc)" class="teuf7pojj"/><path fill="url(#iXgyKjb)" class="teuf7pojj"/><path fill="url(#i20PV0c)" class="teuf7pojj"/></g><path class="v4fah9b_q"/><path fill="url(#igBxz7b)" class="ghj9qibnl"/><path fill="url(#ijaZXne)" class="ghj9qibnl"/><path fill="url(#in69Tqe)" class="ghj9qibnl"/><path fill="url(#iwyGTAd)" class="ghj9qibnl"/><g filter="url(#iYi3tRm)"><path fill="url(#iRCx1Vx)" class="q0fyycbku"/><path fill="url(#izTAKpe)" class="q0fyycbku"/><path fill="url(#iNQtd3c)" class="q0fyycbku"/></g><g filter="url(#i8SuiUB)"><path class="yctxbcejc"/><path fill="url(#iYvnixb)" class="b_j_6-y8y"/><path fill="url(#iVPPDdb)" class="b_j_6-y8y"/><path fill="url(#ixH9lAb)" class="b_j_6-y8y"/><path class="u2vcdnven"/></g><path class="i-52jou8n"/><path fill="url(#ixzemsd)" class="krxrk8emn"/><path fill="url(#ivbZr4A)" class="krxrk8emn"/><path fill="url(#inof6de)" class="krxrk8emn"/><path fill="url(#imxkYGb)" class="krxrk8emn"/><g filter="url(#ipUIRWq)"><path fill="url(#iIRSCwW)" class="h7shiob8z"/><path fill="url(#igMkVIc)" class="h7shiob8z"/><path fill="url(#i4gfhUk)" class="h7shiob8z"/></g><g filter="url(#iuT7kPd)"><path fill="url(#ixvNFUV)" class="c0a2k_b7v"/></g><path class="nod536ahl"/><path fill="url(#iLMZNud)" class="ltnnkpbuc"/><path fill="url(#ixhFvAz)" class="ltnnkpbuc"/><path fill="url(#il3xLuc)" class="ltnnkpbuc"/><path fill="url(#im6QQie)" class="ltnnkpbuc"/><g filter="url(#iaKfDkb)"><path fill="url(#iqSvYde)" class="r845j3bir"/><path fill="url(#iPWKJvt)" class="r845j3bir"/><path fill="url(#i3ST7re)" class="r845j3bir"/></g><path fill="url(#iaUh87c)" class="qusunknvw"/><path fill="url(#iKqWnQc)" class="qusunknvw"/><g filter="url(#iCDD4kb)"><path class="ueds4mn5o"/><path fill="url(#iHfYY4d)" class="axepu9b3o"/><path fill="url(#iWqLy0d)" class="axepu9b3o"/></g><g filter="url(#i0ndQPd)"><path class="k8p3u4b5l"/></g><path fill="url(#ii7NR9d)" class="m5i4vb55x"/><g filter="url(#iAvvfyd)"><path fill="url(#i3309Bb)" class="wyzu9ob4y"/></g><defs><linearGradient id="igyDeMb" x1="6.594" x2="5.313" y1="14.813" y2="16.094" gradientUnits="userSpaceOnUse"><stop class="xe4tjkbqn"/><stop offset=".543" class="kcyv0ibwn"/></linearGradient><linearGradient id="iwraJUO" x1="6.906" x2="5.625" y1="14.25" y2="15.531" gradientUnits="userSpaceOnUse"><stop class="xe4tjkbqn"/><stop offset=".543" class="kcyv0ibwn"/></linearGradient><linearGradient id="iaFiXQb" x1="9.555" x2="10.375" y1="11.602" y2="10.781" gradientUnits="userSpaceOnUse"><stop class="w63p16bvx"/><stop offset=".257" class="a7q9jpbeu"/><stop offset=".971" class="rubahbcei"/></linearGradient><linearGradient id="iKlZkGS" x1="5.313" x2="6.258" y1="10.563" y2="11.508" gradientUnits="userSpaceOnUse"><stop class="dz7tnnctf"/><stop offset=".198" class="lf7woi5ol"/><stop offset="1" class="lxzi81bvc"/></linearGradient><linearGradient id="i6OCire" x1="10.438" x2="9.547" y1="15.031" y2="14.141" gradientUnits="userSpaceOnUse"><stop offset=".193" class="ckevipb2p"/><stop offset=".509" class="ad8b7tw_g"/><stop offset="1" class="lgagjmn6p"/></linearGradient><linearGradient id="i9uH7Oc" x1="4.716" x2="10.695" y1="13.599" y2="13.576" gradientUnits="userSpaceOnUse"><stop class="dgezfdc2a"/><stop offset="1" class="tq11d9b0s"/></linearGradient><linearGradient id="iXgyKjb" x1="5.933" x2="9.492" y1="14.755" y2="11.262" gradientUnits="userSpaceOnUse"><stop offset=".028" class="f2ugr90db"/><stop offset=".184" class="j6kjxj5ll"/></linearGradient><linearGradient id="i20PV0c" x1="9.61" x2="6.459" y1="11.145" y2="14.297" gradientUnits="userSpaceOnUse"><stop offset=".019" class="vqghs6y2v"/><stop offset=".205" class="zzeugl1jf"/></linearGradient><linearGradient id="igBxz7b" x1="12.094" x2="10.813" y1="9.094" y2="10.375" gradientUnits="userSpaceOnUse"><stop offset=".402" class="t9gmwyb9v"/><stop offset=".866" class="gx4im9pup"/><stop offset="1" class="wwnmcgbqa"/></linearGradient><linearGradient id="ijaZXne" x1="14.656" x2="15.563" y1="6.469" y2="5.625" gradientUnits="userSpaceOnUse"><stop class="h9s711h4d"/><stop offset=".343" class="zink7d0af"/><stop offset="1" class="me6etymyl"/></linearGradient><linearGradient id="in69Tqe" x1="10.5" x2="11.445" y1="5.406" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="dz7tnnctf"/><stop offset=".198" class="lf7woi5ol"/><stop offset="1" class="lxzi81bvc"/></linearGradient><linearGradient id="iwyGTAd" x1="15.625" x2="14.734" y1="9.875" y2="8.984" gradientUnits="userSpaceOnUse"><stop offset=".193" class="ckevipb2p"/><stop offset=".509" class="ad8b7tw_g"/><stop offset="1" class="lgagjmn6p"/></linearGradient><linearGradient id="iRCx1Vx" x1="9.904" x2="15.982" y1="8.442" y2="8.518" gradientUnits="userSpaceOnUse"><stop class="ud0sbb-am"/><stop offset="1" class="xs5hwxb4y"/></linearGradient><linearGradient id="izTAKpe" x1="11.123" x2="13.856" y1="9.596" y2="6.862" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7vkfvbyx"/><stop offset=".184" class="o72bnhu_s"/></linearGradient><linearGradient id="iNQtd3c" x1="14.921" x2="12.675" y1="5.865" y2="8.006" gradientUnits="userSpaceOnUse"><stop offset=".019" class="vqghs6y2v"/><stop offset=".205" class="zzeugl1jf"/></linearGradient><linearGradient id="iYvnixb" x1="17.221" x2="15.94" y1="15.017" y2="16.299" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l84u8acvo"/><stop offset=".671" class="fbcslygpz"/><stop offset="1" class="clddo_bmg"/></linearGradient><linearGradient id="iVPPDdb" x1="19.869" x2="20.69" y1="12.369" y2="11.549" gradientUnits="userSpaceOnUse"><stop class="w63p16bvx"/><stop offset=".257" class="a7q9jpbeu"/><stop offset=".971" class="rubahbcei"/></linearGradient><linearGradient id="ixH9lAb" x1="15.627" x2="16.572" y1="11.33" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="jz9kkjboh"/><stop offset=".198" class="b1xipccrh"/><stop offset="1" class="x9dsf7blo"/></linearGradient><linearGradient id="ixzemsd" x1="17.625" x2="16.344" y1="14.563" y2="15.844" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l84u8acvo"/><stop offset=".671" class="fbcslygpz"/><stop offset="1" class="clddo_bmg"/></linearGradient><linearGradient id="ivbZr4A" x1="20.273" x2="21.094" y1="11.914" y2="11.094" gradientUnits="userSpaceOnUse"><stop class="w63p16bvx"/><stop offset=".257" class="a7q9jpbeu"/><stop offset=".971" class="rubahbcei"/></linearGradient><linearGradient id="inof6de" x1="16.031" x2="16.977" y1="10.875" y2="11.82" gradientUnits="userSpaceOnUse"><stop class="jz9kkjboh"/><stop offset=".198" class="b1xipccrh"/><stop offset="1" class="x9dsf7blo"/></linearGradient><linearGradient id="imxkYGb" x1="21.156" x2="20.266" y1="15.344" y2="14.453" gradientUnits="userSpaceOnUse"><stop offset=".193" class="ckevipb2p"/><stop offset=".509" class="ad8b7tw_g"/><stop offset="1" class="lgagjmn6p"/></linearGradient><linearGradient id="iIRSCwW" x1="15.434" x2="21.414" y1="13.912" y2="13.888" gradientUnits="userSpaceOnUse"><stop class="dgezfdc2a"/><stop offset="1" class="tq11d9b0s"/></linearGradient><linearGradient id="igMkVIc" x1="16.652" x2="20.211" y1="15.067" y2="11.574" gradientUnits="userSpaceOnUse"><stop offset=".028" class="f2ugr90db"/><stop offset=".184" class="j6kjxj5ll"/></linearGradient><linearGradient id="i4gfhUk" x1="20.329" x2="17.177" y1="11.458" y2="14.609" gradientUnits="userSpaceOnUse"><stop offset=".019" class="vqghs6y2v"/><stop offset=".205" class="zzeugl1jf"/></linearGradient><linearGradient id="ixvNFUV" x1="11.375" x2="9.219" y1="21.375" y2="19.219" gradientUnits="userSpaceOnUse"><stop class="zqrcvabqk"/><stop offset="1" class="v_k69hjso"/></linearGradient><linearGradient id="iLMZNud" x1="12.453" x2="11.172" y1="19.766" y2="21.047" gradientUnits="userSpaceOnUse"><stop class="xe4tjkbqn"/><stop offset=".543" class="kcyv0ibwn"/></linearGradient><linearGradient id="ixhFvAz" x1="15.102" x2="15.922" y1="17.117" y2="16.297" gradientUnits="userSpaceOnUse"><stop class="w63p16bvx"/><stop offset=".257" class="a7q9jpbeu"/><stop offset=".971" class="rubahbcei"/></linearGradient><linearGradient id="il3xLuc" x1="10.859" x2="11.805" y1="16.078" y2="17.023" gradientUnits="userSpaceOnUse"><stop class="jz9kkjboh"/><stop offset=".198" class="cv_55-blo"/><stop offset="1" class="fu251sb_e"/></linearGradient><linearGradient id="im6QQie" x1="15.984" x2="15.094" y1="20.547" y2="19.656" gradientUnits="userSpaceOnUse"><stop offset=".193" class="ckevipb2p"/><stop offset=".509" class="ad8b7tw_g"/><stop offset="1" class="lgagjmn6p"/></linearGradient><linearGradient id="iqSvYde" x1="10.262" x2="16.242" y1="19.115" y2="19.091" gradientUnits="userSpaceOnUse"><stop class="dgezfdc2a"/><stop offset="1" class="tq11d9b0s"/></linearGradient><linearGradient id="iPWKJvt" x1="11.48" x2="15.039" y1="20.27" y2="16.777" gradientUnits="userSpaceOnUse"><stop offset=".028" class="f2ugr90db"/><stop offset=".184" class="j6kjxj5ll"/></linearGradient><linearGradient id="i3ST7re" x1="15.157" x2="12.006" y1="16.661" y2="19.812" gradientUnits="userSpaceOnUse"><stop offset=".019" class="vqghs6y2v"/><stop offset=".205" class="zzeugl1jf"/></linearGradient><linearGradient id="iaUh87c" x1="26.938" x2="15.75" y1="16.313" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="yj4asumlz"/><stop offset="1" class="lptnsnzcw"/></linearGradient><linearGradient id="iKqWnQc" x1="25.938" x2="22.688" y1="25.125" y2="21.875" gradientUnits="userSpaceOnUse"><stop class="hw62_6bzv"/><stop offset=".933" class="kkcsbmbjy"/></linearGradient><linearGradient id="iHfYY4d" x1="25.75" x2="22.844" y1="15.125" y2="18.031" gradientUnits="userSpaceOnUse"><stop offset=".086" class="fa69-ybvy"/><stop offset=".694" class="llkbkeb7r"/></linearGradient><linearGradient id="iWqLy0d" x1="17.438" x2="18.844" y1="18.5" y2="19.531" gradientUnits="userSpaceOnUse"><stop offset=".384" class="fkdr0lbfo"/><stop offset=".767" class="dz5dn-vqd"/></linearGradient><linearGradient id="ii7NR9d" x1="23.34" x2="11.25" y1="11.472" y2="23.625" gradientUnits="userSpaceOnUse"><stop class="yi5996bix"/><stop offset=".088" class="jh0ud4bct"/><stop offset=".198" class="u1gxaobdc"/><stop offset=".758" class="plxecfbjk"/><stop offset=".879" class="o5svwr7dd"/><stop offset="1" class="ut7t-2cai"/></linearGradient><linearGradient id="i3309Bb" x1="22.25" x2="16.5" y1="10.783" y2="16.533" gradientUnits="userSpaceOnUse"><stop class="bfgha0bmy"/><stop offset="1" class="srxsy3bnz"/></linearGradient><filter id="iuML8Qb" width="10" height="10.021" x="2.373" y="8.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".5"/></filter><filter id="i2SO43c" width="7.325" height="7.325" x="4.02" y="9.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".125"/></filter><filter id="iYi3tRm" width="7.443" height="7.443" x="9.211" y="3.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".125"/></filter><filter id="i8SuiUB" width="10" height="10.021" x="13" y="8.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".5"/></filter><filter id="ipUIRWq" width="7.325" height="7.325" x="14.738" y="9.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".125"/></filter><filter id="iuT7kPd" width="10" height="10.021" x="7.873" y="13.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".5"/></filter><filter id="iaKfDkb" width="7.325" height="7.325" x="9.567" y="14.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".125"/></filter><filter id="iCDD4kb" width="18.54" height="18.335" x="11.133" y="11.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".5"/></filter><filter id="i0ndQPd" width="13.872" height="15.28" x="9.722" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".5"/></filter><filter id="iAvvfyd" width="7.375" height="8.077" x="16" y="9.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32062" stdDeviation=".25"/></filter><radialGradient id="iXp7Ige" cx="0" cy="0" r="1" gradientTransform="rotate(135 1.97 4.258)scale(12.3302 6.13734)" gradientUnits="userSpaceOnUse"><stop class="x2gz2sbzc"/><stop offset="1" class="x4cc4acpo"/></radialGradient><radialGradient id="ioObAdc" cx="0" cy="0" r="1" gradientTransform="matrix(8.17387 8.17387 -6.34375 6.34375 4.031 18.906)" gradientUnits="userSpaceOnUse"><stop class="wf1_3nbaf"/><stop offset="1" class="v0i6yy00r"/></radialGradient><radialGradient id="iycNBtx" cx="0" cy="0" r="1" gradientTransform="rotate(45 .677 24.468)scale(10.1647 3.13779)" gradientUnits="userSpaceOnUse"><stop class="n4vv0k8-r"/><stop offset="1" class="e7_6lzbxg"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chocolate-bar" /></template>
<style>
.a7q9jpbeu {
  stop-color: var(--svg-color--8e5e45, #8E5E45);
}

.ad8b7tw_g {
  stop-color: var(--svg-color--884b3f, #884B3F);
}

.axepu9b3o {
  d: path("M12.133 21.523s4.726 4.975 5.765 5.897s1.478 1.449 2.37.703c.894-.747 6.91-6.777 7.86-7.772c.952-.995.53-1.61-.305-2.444C26.99 17.072 22 12.142 22 12.142z");
}

.b_j_6-y8y {
  d: path("m17.09 9.928l.042-.037c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.348a50 50 0 0 1 1.342 1.414c.451.52.483 1.211.004 1.747l-.022.025a31 31 0 0 1-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002c-.027-.023-.83-.727-1.436-1.334a35 35 0 0 1-1.326-1.428l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.845 1.356-1.395a94 94 0 0 1 1.377-1.339");
}

.b1xipccrh {
  stop-color: var(--svg-color--773d25, #773D25);
}

.bfgha0bmy {
  stop-color: var(--svg-color--d4d1db, #D4D1DB);
}

.c0a2k_b7v {
  d: path("m11.963 15.158l.042-.038c.532-.448 1.21-.438 1.734.008l.023.021c.101.092.847.777 1.418 1.348a50 50 0 0 1 1.342 1.413c.451.52.483 1.212.004 1.747l-.022.025c-.084.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.397c-.58.461-1.223.393-1.74-.06l-.001-.002a36 36 0 0 1-1.436-1.335a35 35 0 0 1-1.327-1.427l-.001-.003c-.465-.535-.453-1.254-.01-1.755l.021-.022c.094-.098.806-.844 1.356-1.394a94 94 0 0 1 1.377-1.34");
}

.ckevipb2p {
  stop-color: var(--svg-color--7f4131, #7F4131);
}

.clddo_bmg {
  stop-color: var(--svg-color--5d2a1f, #5D2A1F);
}

.cv_55-blo {
  stop-color: var(--svg-color--783f28, #783F28);
}

.d86jukbwy {
  fill: var(--svg-color--7b3e41, #7B3E41);
  d: path("m6.463 9.723l.042-.037c.533-.448 1.21-.438 1.734.008l.023.02c.101.093.847.778 1.418 1.348a50 50 0 0 1 1.342 1.414c.451.52.483 1.211.004 1.747l-.022.025c-.084.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002c-.027-.023-.83-.727-1.436-1.334a35 35 0 0 1-1.327-1.428l-.001-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.844 1.356-1.395a94 94 0 0 1 1.377-1.339");
}

.dgezfdc2a {
  stop-color: var(--svg-color--865345, #865345);
}

.dz5dn-vqd {
  stop-color: var(--svg-color--b71550, #B71550);
  stop-opacity: 0;
}

.dz7tnnctf {
  stop-color: var(--svg-color--754a38, #754A38);
}

.e7_6lzbxg {
  stop-color: var(--svg-color--ac7a63, #AC7A63);
  stop-opacity: 0;
}

.eealdrbqw {
  d: path("m6.463 9.723l.042-.037c.533-.448 1.21-.438 1.734.008l.023.02c.101.093.847.778 1.418 1.348a50 50 0 0 1 1.342 1.414c.451.52.483 1.211.004 1.747l-.022.025c-.084.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002c-.027-.023-.83-.727-1.436-1.334a35 35 0 0 1-1.327-1.428l-.001-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.844 1.356-1.395a94 94 0 0 1 1.377-1.339");
}

.f2ugr90db {
  stop-color: var(--svg-color--7f4a40, #7F4A40);
}

.fa69-ybvy {
  stop-color: var(--svg-color--ea4b6c, #EA4B6C);
}

.fbcslygpz {
  stop-color: var(--svg-color--643026, #643026);
}

.fkdr0lbfo {
  stop-color: var(--svg-color--b3154f, #B3154F);
}

.ft5dv1b6b {
  fill: none;
}

.fu251sb_e {
  stop-color: var(--svg-color--7e4934, #7E4934);
  stop-opacity: 0;
}

.ghj9qibnl {
  d: path("m11.963 4.005l.042-.038c.532-.448 1.21-.438 1.734.008l.023.02c.101.093.847.778 1.418 1.349a50 50 0 0 1 1.342 1.413c.451.52.483 1.211.004 1.747l-.022.025c-.084.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002a36 36 0 0 1-1.436-1.334A35 35 0 0 1 9.22 8.517l-.001-.002c-.465-.536-.453-1.254-.01-1.755l.021-.022a97 97 0 0 1 1.356-1.394a95 95 0 0 1 1.377-1.34");
}

.gx4im9pup {
  stop-color: var(--svg-color--783930, #783930);
}

.h7shiob8z {
  d: path("M15.109 13.497a.48.48 0 0 1-.01-.627a24 24 0 0 1 1.42-1.561a24 24 0 0 1 1.555-1.414a.48.48 0 0 1 .625.009c.407.352 1.124.981 1.572 1.43a35 35 0 0 1 1.422 1.562a.49.49 0 0 1 .002.64c-.342.4-.941 1.085-1.406 1.55a31 31 0 0 1-1.55 1.405a.49.49 0 0 1-.64-.003c-.418-.363-1.145-1.003-1.562-1.42c-.42-.42-1.067-1.155-1.428-1.571");
}

.h9s711h4d {
  stop-color: var(--svg-color--a87760, #A87760);
  stop-opacity: 0;
}

.hw62_6bzv {
  stop-color: var(--svg-color--d61e58, #D61E58);
}

.i-52jou8n {
  fill: var(--svg-color--824534, #824534);
  d: path("m17.494 9.473l.042-.037c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.348a50 50 0 0 1 1.328 1.398l.014.016c.452.52.483 1.211.004 1.747l-.022.025c-.083.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002a36 36 0 0 1-1.436-1.334a34 34 0 0 1-1.326-1.428l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.844 1.356-1.395a95 95 0 0 1 1.377-1.339");
}

.j6kjxj5ll {
  stop-color: var(--svg-color--844a45, #844A45);
  stop-opacity: 0;
}

.jh0ud4bct {
  stop-color: var(--svg-color--adabb2, #ADABB2);
}

.jz9kkjboh {
  stop-color: var(--svg-color--733821, #733821);
}

.k8p3u4b5l {
  fill: var(--svg-color--572916, #572916);
  d: path("M22.49 12.086s-8.357 11.344-8.67 11.657s-.57.37-.997.1c-.427-.271-1.736-1.809-1.95-2.05c-.214-.243-.207-.543.075-.806c.28-.263 10.206-10.146 10.206-10.146c.16-.16.449-.119.576 0c0 0 .584.498.762.676s.09.442 0 .57");
}

.kcyv0ibwn {
  stop-color: var(--svg-color--825254, #825254);
}

.kkcsbmbjy {
  stop-color: var(--svg-color--d71d59, #D71D59);
  stop-opacity: 0;
}

.kpz3ielfb {
  fill: var(--svg-color--824534, #824534);
  d: path("m6.776 9.16l.041-.037c.533-.447 1.21-.437 1.734.008l.024.021c.1.092.846.777 1.417 1.348a50 50 0 0 1 1.342 1.413c.452.52.483 1.212.004 1.747l-.022.025c-.083.096-.647.74-1.324 1.416a55 55 0 0 1-1.456 1.397c-.58.462-1.222.394-1.739-.06l-.002-.002c-.027-.024-.829-.728-1.436-1.335a35 35 0 0 1-1.326-1.427l-.002-.002c-.465-.536-.453-1.255-.009-1.755l.02-.023c.094-.098.806-.844 1.356-1.394a94 94 0 0 1 1.378-1.34");
}

.krxrk8emn {
  d: path("m17.494 9.473l.042-.037c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.348a50 50 0 0 1 1.328 1.398l.014.016c.452.52.483 1.211.004 1.747l-.022.025c-.083.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002a36 36 0 0 1-1.436-1.334a34 34 0 0 1-1.326-1.428l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.844 1.356-1.395a95 95 0 0 1 1.377-1.339");
}

.l84u8acvo {
  stop-color: var(--svg-color--6d3f3d, #6D3F3D);
  stop-opacity: 0;
}

.lf7woi5ol {
  stop-color: var(--svg-color--764b38, #764B38);
}

.lgagjmn6p {
  stop-color: var(--svg-color--905452, #905452);
  stop-opacity: 0;
}

.llkbkeb7r {
  stop-color: var(--svg-color--ec4b6c, #EC4B6C);
  stop-opacity: 0;
}

.lptnsnzcw {
  stop-color: var(--svg-color--c41959, #C41959);
}

.ltnnkpbuc {
  d: path("m12.323 14.677l.041-.038c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.349a50 50 0 0 1 1.342 1.413c.452.52.483 1.211.004 1.747l-.022.025c-.083.096-.647.739-1.324 1.416a56 56 0 0 1-1.456 1.396c-.58.462-1.223.394-1.739-.06l-.002-.002a36 36 0 0 1-1.436-1.334A35 35 0 0 1 9.58 19.19l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022a97 97 0 0 1 1.356-1.394a94 94 0 0 1 1.377-1.34");
}

.lxzi81bvc {
  stop-color: var(--svg-color--8a5648, #8A5648);
  stop-opacity: 0;
}

.m5i4vb55x {
  d: path("M23.227 11.547s-9.508 12.906-9.852 13.25s-.625.406-1.094.11c-.469-.298-1.906-1.985-2.14-2.25c-.235-.266-.227-.596.082-.884c.308-.289 11.535-11.593 11.535-11.593c.176-.176.493-.13.633 0c0 0 .64.547.836.742s.1.485 0 .625");
}

.me6etymyl {
  stop-color: var(--svg-color--a3735a, #A3735A);
}

.n4vv0k8-r {
  stop-color: var(--svg-color--ac7a64, #AC7A64);
}

.n7vkfvbyx {
  stop-color: var(--svg-color--804643, #804643);
}

.ndt9elbwa {
  d: path("m10.984 22.625l-8.109-8.172c-1.32-1.32-.828-2.64-.25-3.219l8.563-8.515c1.023-1.024 2.187-.828 3.124.11l8.063 8z");
}

.nod536ahl {
  fill: var(--svg-color--824534, #824534);
  d: path("m12.323 14.677l.041-.038c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.349a50 50 0 0 1 1.342 1.413c.452.52.483 1.211.004 1.747l-.022.025c-.083.096-.647.739-1.324 1.416a56 56 0 0 1-1.456 1.396c-.58.462-1.223.394-1.739-.06l-.002-.002a36 36 0 0 1-1.436-1.334A35 35 0 0 1 9.58 19.19l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022a97 97 0 0 1 1.356-1.394a94 94 0 0 1 1.377-1.34");
}

.o5svwr7dd {
  stop-color: var(--svg-color--a892c1, #A892C1);
}

.o72bnhu_s {
  stop-color: var(--svg-color--874b4f, #874B4F);
  stop-opacity: 0;
}

.plxecfbjk {
  stop-color: var(--svg-color--b3a5c6, #B3A5C6);
}

.px5fkcc8a {
  fill: var(--svg-color--824534, #824534);
  d: path("m6.463 9.723l.042-.037c.533-.448 1.21-.438 1.734.008l.023.02c.101.093.847.778 1.418 1.348a50 50 0 0 1 1.342 1.414c.451.52.483 1.211.004 1.747l-.022.025c-.084.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002c-.027-.023-.83-.727-1.436-1.334a35 35 0 0 1-1.327-1.428l-.001-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.844 1.356-1.395a94 94 0 0 1 1.377-1.339");
}

.q0fyycbku {
  d: path("M9.58 8.026a.48.48 0 0 1-.007-.627c.303-.363.844-.988 1.478-1.622a25 25 0 0 1 1.614-1.471a.48.48 0 0 1 .626.007c.408.35 1.126.979 1.574 1.427a33 33 0 0 1 1.42 1.564a.49.49 0 0 1 0 .64c-.353.41-.98 1.126-1.465 1.61a33 33 0 0 1-1.609 1.464a.49.49 0 0 1-.642-.001c-.418-.362-1.147-1-1.563-1.417c-.42-.42-1.065-1.157-1.426-1.574");
}

.qusunknvw {
  d: path("M10.258 21.783s6.297 6.563 7.406 7.547c1.11.984 2.328.797 3.281 0s7.375-7.234 8.39-8.297c1.017-1.062.735-2.484-.155-3.375c-.891-.89-7.47-7.406-7.47-7.406z");
}

.r845j3bir {
  d: path("M9.937 18.7a.48.48 0 0 1-.01-.627c.295-.353.813-.954 1.42-1.561a24 24 0 0 1 1.556-1.414a.48.48 0 0 1 .624.009c.408.352 1.124.981 1.573 1.43a35 35 0 0 1 1.421 1.562a.49.49 0 0 1 .002.64c-.342.4-.941 1.085-1.406 1.55a31 31 0 0 1-1.549 1.405a.49.49 0 0 1-.641-.003c-.418-.363-1.145-1.003-1.562-1.42c-.42-.42-1.067-1.155-1.428-1.57");
}

.rubahbcei {
  stop-color: var(--svg-color--79452b, #79452B);
}

.srxsy3bnz {
  stop-color: var(--svg-color--b3a6c5, #B3A6C5);
  stop-opacity: 0;
}

.t9gmwyb9v {
  stop-color: var(--svg-color--7a3c35, #7A3C35);
  stop-opacity: 0;
}

.teuf7pojj {
  d: path("M4.39 13.185a.48.48 0 0 1-.01-.627c.295-.353.813-.954 1.42-1.562a24 24 0 0 1 1.556-1.413a.48.48 0 0 1 .625.008a35 35 0 0 1 1.572 1.43a35 35 0 0 1 1.421 1.562a.49.49 0 0 1 .002.64a31 31 0 0 1-1.406 1.55a31 31 0 0 1-1.549 1.405a.49.49 0 0 1-.641-.003a36 36 0 0 1-1.562-1.42c-.42-.42-1.067-1.154-1.428-1.57");
}

.tq11d9b0s {
  stop-color: var(--svg-color--945c4e, #945C4E);
}

.u1gxaobdc {
  stop-color: var(--svg-color--b1a4c2, #B1A4C2);
}

.u2vcdnven {
  fill: var(--svg-color--613534, #613534);
  d: path("m17.09 9.928l.042-.037c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.348a50 50 0 0 1 1.342 1.414c.451.52.483 1.211.004 1.747l-.022.025a31 31 0 0 1-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002c-.027-.023-.83-.727-1.436-1.334a35 35 0 0 1-1.326-1.428l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.845 1.356-1.395a94 94 0 0 1 1.377-1.339");
}

.ud0sbb-am {
  stop-color: var(--svg-color--8b5a4a, #8B5A4A);
}

.ueds4mn5o {
  fill: var(--svg-color--d3245a, #D3245A);
  d: path("M12.133 21.523s4.726 4.975 5.765 5.897s1.478 1.449 2.37.703c.894-.747 6.91-6.777 7.86-7.772c.952-.995.53-1.61-.305-2.444C26.99 17.072 22 12.142 22 12.142z");
}

.ut7t-2cai {
  stop-color: var(--svg-color--a485c3, #A485C3);
}

.v_k69hjso {
  stop-color: var(--svg-color--773c41, #773C41);
}

.v0i6yy00r {
  stop-color: var(--svg-color--834b4d, #834B4D);
  stop-opacity: 0;
}

.v4fah9b_q {
  fill: var(--svg-color--824534, #824534);
  d: path("m11.963 4.005l.042-.038c.532-.448 1.21-.438 1.734.008l.023.02c.101.093.847.778 1.418 1.349a50 50 0 0 1 1.342 1.413c.451.52.483 1.211.004 1.747l-.022.025c-.084.096-.647.739-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002a36 36 0 0 1-1.436-1.334A35 35 0 0 1 9.22 8.517l-.001-.002c-.465-.536-.453-1.254-.01-1.755l.021-.022a97 97 0 0 1 1.356-1.394a95 95 0 0 1 1.377-1.34");
}

.vqghs6y2v {
  stop-color: var(--svg-color--9b705c, #9B705C);
}

.w63p16bvx {
  stop-color: var(--svg-color--91634b, #91634B);
  stop-opacity: 0;
}

.wf1_3nbaf {
  stop-color: var(--svg-color--834d4f, #834D4F);
}

.wwnmcgbqa {
  stop-color: var(--svg-color--713126, #713126);
}

.wyzu9ob4y {
  d: path("M22.875 11.281c0-.453-.5-.937-.953-.781S16.5 16.281 16.5 16.281l1.578 1.266c1.584-1.896 4.797-5.805 4.797-6.266");
}

.x2gz2sbzc {
  stop-color: var(--svg-color--735040, #735040);
}

.x4cc4acpo {
  stop-color: var(--svg-color--724a3a, #724A3A);
  stop-opacity: 0;
}

.x9dsf7blo {
  stop-color: var(--svg-color--7f4b35, #7F4B35);
  stop-opacity: 0;
}

.xe4tjkbqn {
  stop-color: var(--svg-color--835355, #835355);
  stop-opacity: 0;
}

.xs5hwxb4y {
  stop-color: var(--svg-color--9b6351, #9B6351);
}

.yctxbcejc {
  fill: var(--svg-color--824534, #824534);
  d: path("m17.09 9.928l.042-.037c.533-.448 1.21-.438 1.734.008l.024.02c.1.093.846.778 1.417 1.348a50 50 0 0 1 1.342 1.414c.451.52.483 1.211.004 1.747l-.022.025a31 31 0 0 1-1.324 1.416a55 55 0 0 1-1.456 1.396c-.58.462-1.223.394-1.74-.06l-.001-.002c-.027-.023-.83-.727-1.436-1.334a35 35 0 0 1-1.326-1.428l-.002-.002c-.465-.536-.453-1.255-.01-1.755l.021-.022c.094-.098.806-.845 1.356-1.395a94 94 0 0 1 1.377-1.339");
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.yj4asumlz {
  stop-color: var(--svg-color--ed4253, #ED4253);
}

.zink7d0af {
  stop-color: var(--svg-color--a8775f, #A8775F);
}

.zmbzgfb5q {
  d: path("m6.776 9.16l.041-.037c.533-.447 1.21-.437 1.734.008l.024.021c.1.092.846.777 1.417 1.348a50 50 0 0 1 1.342 1.413c.452.52.483 1.212.004 1.747l-.022.025c-.083.096-.647.74-1.324 1.416a55 55 0 0 1-1.456 1.397c-.58.462-1.222.394-1.739-.06l-.002-.002c-.027-.024-.829-.728-1.436-1.335a35 35 0 0 1-1.326-1.427l-.002-.002c-.465-.536-.453-1.255-.009-1.755l.02-.023c.094-.098.806-.844 1.356-1.394a94 94 0 0 1 1.378-1.34");
}

.zqrcvabqk {
  stop-color: var(--svg-color--64342f, #64342F);
}

.zs8c4nbhp {
  fill: var(--svg-color--8a584c, #8A584C);
  d: path("m10.984 22.625l-8.109-8.172c-1.32-1.32-.828-2.64-.25-3.219l8.563-8.515c1.023-1.024 2.187-.828 3.124.11l8.063 8z");
}

.zzeugl1jf {
  stop-color: var(--svg-color--9b705c, #9B705C);
  stop-opacity: 0;
}

</style>
