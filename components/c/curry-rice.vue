<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#id0WPnc)" class="vnreirbsb"/><path fill="url(#iz0TAod)" class="vnreirbsb"/><path fill="url(#iLydfHe)" class="uar96jblh"/><path fill="url(#iiEJRpc)" class="uar96jblh"/><path fill="url(#izSsHkL)" class="uar96jblh"/><path fill="url(#imDx3EV)" class="uar96jblh"/><path fill="url(#iGVzKLc)" class="uar96jblh"/><path fill="url(#iFE9Kmb)" class="h-i1urrjx"/><path fill="url(#iEtLhOZ)" class="h-i1urrjx"/><g filter="url(#i86Kqxd)"><path fill="url(#iA8uIHc)" class="c2zb_d_eg"/></g><path class="b7l6-xzne"/><path fill="url(#iWvm0rb)" class="o1kz-86cr"/><path fill="url(#iEfMM7d)" class="o1kz-86cr"/><path fill="url(#iN2hmGb)" class="o1kz-86cr"/><path fill="url(#iUrBpsd)" class="o1kz-86cr"/><g filter="url(#iFvjAuc)"><path class="dhezvujwu"/></g><g filter="url(#i4VdANe)"><path class="cljo5mb0a"/></g><g filter="url(#i05bSVc)"><path class="pqvqzqb1y"/></g><path fill="url(#ive5Oie)" class="y3gebxxdx"/><path fill="url(#i2cbOne)" class="cyb_7rb5l"/><g filter="url(#iYRZMPc)"><path class="da9dkk03a"/></g><g filter="url(#idDGjAc)"><path class="mkbl3bigu"/></g><path fill="url(#iPrn5Kb)" class="f3ixxllmn"/><path fill="url(#iCcCGRb)" class="cmlk5cben"/><path fill="url(#i1mOGZo)" class="cmlk5cben"/><path fill="url(#iSQQmXh)" class="cmlk5cben"/><path fill="url(#il3QnWd)" class="vfsndizjy"/><path fill="url(#iY4Cx3b)" class="vfsndizjy"/><path fill="url(#iDJ7X6d)" class="vfsndizjy"/><g filter="url(#izuBW5d)"><path class="i_c_j-b7t"/></g><path fill="url(#iE9RJcd)" class="rltbnaclt"/><path fill="url(#iDa4zFc)" class="rltbnaclt"/><path fill="url(#isPAqww)" class="rltbnaclt"/><path class="g4fwbxb7i"/><path class="o-kl78s5m"/><path class="oa50k2c2e"/><path class="qqam5l_kw"/><path class="e-k6srb9z"/><path class="y3j_kccjt"/><path class="dfh_v6a8w"/><path class="x2u9k0jhs"/><path class="u8nm-ac6e"/><g filter="url(#ipsx9Xc)"><path fill="url(#iSLuapw)" class="g0vn_pbar"/></g><g filter="url(#iM9ihfc)"><path fill="url(#i1PYN0b)" class="v4yghqbwv"/></g><g filter="url(#iYG1yKc)"><path fill="url(#i0CEySc)" class="sl7xtk4zx"/></g><g filter="url(#iR6rijc)"><path fill="url(#iYWizfZ)" class="c998vdiar"/><path fill="url(#igRDhxe)" class="c998vdiar"/></g><defs><radialGradient id="iz0TAod" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.12496 -12.75 0 18.5 24.875)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="idjqppgpe"/><stop offset=".758" class="i17-dv7xk"/></radialGradient><radialGradient id="iiEJRpc" cx="0" cy="0" r="1" gradientTransform="matrix(.18746 11.43746 -17.46695 .28629 19.437 18.062)" gradientUnits="userSpaceOnUse"><stop offset=".916" class="uh8vtd1av"/><stop offset="1" class="w323bgbvu"/></radialGradient><radialGradient id="izSsHkL" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 7.6875 -8.3465 -.13572 9.188 8.125)" gradientUnits="userSpaceOnUse"><stop class="itq_0gyjr"/><stop offset="1" class="a326vbc-q"/></radialGradient><radialGradient id="imDx3EV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 6.875 -8.08315 -1.7636 21.813 18.25)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="khxyk7bdo"/><stop offset=".839" class="gtd4bnyov"/><stop offset=".94" class="ijsxj-cof"/></radialGradient><radialGradient id="iGVzKLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 3.75 -11.7142 -.97617 7.563 28.188)" gradientUnits="userSpaceOnUse"><stop class="k_gs12hln"/><stop offset=".865" class="n7np1h20q"/></radialGradient><radialGradient id="iEtLhOZ" cx="0" cy="0" r="1" gradientTransform="matrix(.125 9.23247 -13.52726 .18315 14.938 19.08)" gradientUnits="userSpaceOnUse"><stop offset=".907" class="z642czbbn"/><stop offset=".954" class="v15c70bsy"/></radialGradient><radialGradient id="iWvm0rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.875 -11.3526 0 13.307 16.813)" gradientUnits="userSpaceOnUse"><stop class="qhrf4gszc"/><stop offset="1" class="k21v0s6rc"/></radialGradient><radialGradient id="iEfMM7d" cx="0" cy="0" r="1" gradientTransform="rotate(90.536 -1.197 16.678)scale(3.3439 17.5244)" gradientUnits="userSpaceOnUse"><stop class="u3f5r0h8m"/><stop offset=".774" class="n15fh3b3y"/></radialGradient><radialGradient id="iN2hmGb" cx="0" cy="0" r="1" gradientTransform="matrix(-17.68748 8.875 -7.52378 -14.99456 15.063 18.625)" gradientUnits="userSpaceOnUse"><stop offset=".477" class="o4nv0nbzo"/><stop offset=".574" class="m7gntabkn"/></radialGradient><radialGradient id="iUrBpsd" cx="0" cy="0" r="1" gradientTransform="rotate(114.759 4.98 13.005)scale(4.32782 9.48491)" gradientUnits="userSpaceOnUse"><stop class="mclm89b3c"/><stop offset=".637" class="awpaddbmz"/></radialGradient><radialGradient id="ive5Oie" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 -2.085 12.173)scale(1.13934 1.29585)" gradientUnits="userSpaceOnUse"><stop class="wphwi-l8v"/><stop offset=".453" class="veqfi41nu"/><stop offset=".809" class="m5ovbtcga"/></radialGradient><radialGradient id="i2cbOne" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 .192 14.233)scale(1.13934 1.29585)" gradientUnits="userSpaceOnUse"><stop class="wphwi-l8v"/><stop offset=".453" class="veqfi41nu"/><stop offset=".809" class="m5ovbtcga"/></radialGradient><radialGradient id="iPrn5Kb" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 -2.25 14.436)scale(1.13934 1.29585)" gradientUnits="userSpaceOnUse"><stop class="wphwi-l8v"/><stop offset=".453" class="veqfi41nu"/><stop offset=".809" class="m5ovbtcga"/></radialGradient><radialGradient id="i1mOGZo" cx="0" cy="0" r="1" gradientTransform="matrix(-.03124 .91014 -2.85842 -.09812 24.375 18.737)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="xrtg8ibpj"/><stop offset="1" class="ayw3kybsq"/></radialGradient><radialGradient id="iSQQmXh" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 .91406 -7.04644 5.54078 20.844 17.648)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="i9b8xkb-a"/><stop offset="1" class="oe350oahz"/></radialGradient><radialGradient id="iY4Cx3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 .88679 -2.85825 -.10072 23.813 22.968)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="xrtg8ibpj"/><stop offset="1" class="ayw3kybsq"/></radialGradient><radialGradient id="iDJ7X6d" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 .89061 -6.90565 5.57307 20.281 21.906)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="i9b8xkb-a"/><stop offset="1" class="oe350oahz"/></radialGradient><radialGradient id="iDa4zFc" cx="0" cy="0" r="1" gradientTransform="rotate(91.975 -.553 19.646)scale(.90679 2.8601)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="xrtg8ibpj"/><stop offset="1" class="ayw3kybsq"/></radialGradient><radialGradient id="isPAqww" cx="0" cy="0" r="1" gradientTransform="rotate(51.702 -12.657 25.923)scale(1.15974 8.94926)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="i9b8xkb-a"/><stop offset="1" class="oe350oahz"/></radialGradient><radialGradient id="iYWizfZ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31253 8.0156 -9.08093 -4.8857 29.125 19.297)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="d0h02dbav"/></radialGradient><radialGradient id="igRDhxe" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 9.1 16.112)scale(5.44324 3.911)" gradientUnits="userSpaceOnUse"><stop class="tqvi83b3b"/><stop offset="1" class="deq6bg32u"/></radialGradient><filter id="i86Kqxd" width="17.188" height="7.52" x="4" y="11.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".5"/></filter><filter id="iFvjAuc" width="2.422" height="2" x="6.219" y="18.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><filter id="i4VdANe" width="2.422" height="2" x="8.06" y="21.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><filter id="i05bSVc" width="2.422" height="2" x="11.341" y="19.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><filter id="iYRZMPc" width="4.86" height="2.013" x="21.125" y="16.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".125"/></filter><filter id="idDGjAc" width="4.86" height="2.013" x="20.497" y="21.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".125"/></filter><filter id="izuBW5d" width="4.86" height="2.013" x="15.75" y="18.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".125"/></filter><filter id="ipsx9Xc" width="3.235" height="1.844" x="17.765" y="19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><filter id="iM9ihfc" width="3.235" height="1.844" x="23.155" y="16.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><filter id="iYG1yKc" width="3.235" height="1.844" x="22.592" y="20.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><filter id="iR6rijc" width="11.234" height="13.941" x="19.094" y="12.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31370" stdDeviation=".25"/></filter><linearGradient id="id0WPnc" x1="5.188" x2="27.5" y1="26.25" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="spfyce2lg"/><stop offset=".218" class="rvlh4n2ye"/><stop offset=".529" class="mujqfi9pk"/><stop offset="1" class="p_4r8qbfu"/></linearGradient><linearGradient id="iLydfHe" x1="16.02" x2="16.02" y1="11.06" y2="27.1" gradientUnits="userSpaceOnUse"><stop class="ect33ei5c"/><stop offset=".016" class="m-z7iyb1r"/><stop offset=".651" class="u-7zlhbup"/><stop offset=".912" class="tpqrf5bzb"/><stop offset=".959" class="ijn9aubeg"/><stop offset="1" class="jh7izxthi"/></linearGradient><linearGradient id="iFE9Kmb" x1="4.22" x2="28.875" y1="19.688" y2="16.438" gradientUnits="userSpaceOnUse"><stop class="ni656pv8f"/><stop offset="1" class="ynlnkmbzw"/></linearGradient><linearGradient id="iA8uIHc" x1="9.438" x2="9.438" y1="18.094" y2="12.813" gradientUnits="userSpaceOnUse"><stop offset=".314" class="zq3seebvn"/><stop offset=".763" class="czxm44fuf"/></linearGradient><linearGradient id="iCcCGRb" x1="21.563" x2="26.06" y1="18.563" y2="18.563" gradientUnits="userSpaceOnUse"><stop class="vy8-abbvv"/><stop offset=".514" class="fgh-vhavg"/><stop offset="1" class="hq0_h_g3s"/></linearGradient><linearGradient id="il3QnWd" x1="21" x2="25.497" y1="22.797" y2="22.797" gradientUnits="userSpaceOnUse"><stop class="vy8-abbvv"/><stop offset=".514" class="fgh-vhavg"/><stop offset="1" class="hq0_h_g3s"/></linearGradient><linearGradient id="iE9RJcd" x1="16.25" x2="20.747" y1="20.7" y2="20.7" gradientUnits="userSpaceOnUse"><stop class="vy8-abbvv"/><stop offset=".514" class="fgh-vhavg"/><stop offset="1" class="hq0_h_g3s"/></linearGradient><linearGradient id="iSLuapw" x1="20.406" x2="18.125" y1="20.016" y2="19.5" gradientUnits="userSpaceOnUse"><stop offset=".603" class="w32njgoab"/><stop offset="1" class="dy8zy5bjz"/></linearGradient><linearGradient id="i1PYN0b" x1="25.796" x2="23.515" y1="17.742" y2="17.227" gradientUnits="userSpaceOnUse"><stop offset=".603" class="w32njgoab"/><stop offset="1" class="dy8zy5bjz"/></linearGradient><linearGradient id="i0CEySc" x1="25.233" x2="22.952" y1="22" y2="21.484" gradientUnits="userSpaceOnUse"><stop offset=".603" class="w32njgoab"/><stop offset="1" class="dy8zy5bjz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:curry-rice" /></template>
<style>
.a326vbc-q {
  stop-color: var(--svg-color--a39fa2, #A39FA2);
  stop-opacity: 0;
}

.awpaddbmz {
  stop-color: var(--svg-color--fcfbfc, #FCFBFC);
  stop-opacity: 0;
}

.ayw3kybsq {
  stop-color: var(--svg-color--ff8826, #FF8826);
  stop-opacity: 0;
}

.b7l6-xzne {
  fill: var(--svg-color--efebf4, #EFEBF4);
  d: path("M13.31 10c-3.54 0-6.53 2.33-7.52 5.54c-.35 1.16.53 2.32 1.74 2.32h11.55c1.21 0 2.1-1.17 1.74-2.32A7.86 7.86 0 0 0 13.31 10");
}

.c2zb_d_eg {
  d: path("M5.088 15.54c-.353 1.16.392 2.32 1.613 2.32h11.65c1.221 0 2.119-1.17 1.756-2.32c0 0-12.78-7.2-15.02 0");
}

.c998vdiar {
  d: path("M29.047 19.25c0-2.187-.656-4.937-2.563-6.219c1.641.422 3.344 2.813 3.344 6.094c0 4.963-3.344 7.156-10.234 6.813c9-.813 9.453-4.5 9.453-6.688");
}

.cljo5mb0a {
  fill: var(--svg-color--bf462a, #BF462A);
  d: path("M9.27 23.477c.394 0 .712-.166.712-.432c0-.314-.318-.568-.711-.568s-.711.254-.711.568c0 .278.318.432.71.432");
}

.cmlk5cben {
  d: path("M23.734 16.734c-1.021 0-2.019.858-2.159 1.4c-.04.154-.02.428.589.428h3.36c.336 0 .574-.107.53-.36c-.137-.798-1.298-1.468-2.32-1.468");
}

.cyb_7rb5l {
  d: path("M12.89 20.977c.43 0 .78-.227.78-.592a.78.78 0 1 0-1.56 0c0 .38.349.592.78.592");
}

.czxm44fuf {
  stop-color: var(--svg-color--6b605d, #6B605D);
}

.d0h02dbav {
  stop-color: var(--svg-color--fdfbfe, #FDFBFE);
  stop-opacity: 0;
}

.da9dkk03a {
  fill: var(--svg-color--e35a2f, #E35A2F);
  d: path("M23.583 17.05c-.99 0-2.06.616-2.196 1.117c-.039.142-.019.395.571.395h3.258c.325 0 .557-.099.514-.333c-.133-.736-1.156-1.18-2.147-1.18");
}

.deq6bg32u {
  stop-color: var(--svg-color--fbf9ff, #FBF9FF);
  stop-opacity: 0;
}

.dfh_v6a8w {
  fill: var(--svg-color--cdbbc5, #CDBBC5);
  d: path("M10.2 15.4a.286.286 0 0 1 .394-.088l.734.471a.286.286 0 0 1-.308.482l-.733-.47a.286.286 0 0 1-.088-.396");
}

.dhezvujwu {
  fill: var(--svg-color--bf462a, #BF462A);
  d: path("M7.43 20c.392 0 .71-.165.71-.431c0-.314-.318-.569-.71-.569c-.393 0-.711.255-.711.569c0 .277.318.431.71.431");
}

.dy8zy5bjz {
  stop-color: var(--svg-color--fff16e, #FFF16E);
  stop-opacity: 0;
}

.e-k6srb9z {
  fill: var(--svg-color--c0abb3, #C0ABB3);
  d: path("M15.033 15.857a.286.286 0 0 1-.16.372l-.81.32a.286.286 0 0 1-.212-.53l.81-.321a.286.286 0 0 1 .372.16");
}

.ect33ei5c {
  stop-color: var(--svg-color--b4b3b3, #B4B3B3);
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.f3ixxllmn {
  d: path("M9.593 23.477c.43 0 .78-.227.78-.592a.78.78 0 1 0-1.56 0c0 .38.349.592.78.592");
}

.fgh-vhavg {
  stop-color: var(--svg-color--ffd43c, #FFD43C);
}

.ft5dv1b6b {
  fill: none;
}

.g0vn_pbar {
  d: path("M18.594 20c.412-.012 1.463.177 1.906.344c-.4-.55-1.469-.844-2.016-.844c-.312 0-.303.512.11.5");
}

.g4fwbxb7i {
  fill: var(--svg-color--dcdadd, #DCDADD);
  d: path("M12.146 10.918a.286.286 0 0 1 .395.083l.413.632a.286.286 0 0 1-.479.313l-.413-.632a.286.286 0 0 1 .084-.396");
}

.gtd4bnyov {
  stop-color: var(--svg-color--c1bec1, #C1BEC1);
}

.h-i1urrjx {
  d: path("M22.02 13.28c3.2 0 5.8 2.6 5.8 5.8s-2.6 5.8-5.8 5.8h-12c-3.2 0-5.8-2.6-5.8-5.8s2.6-5.8 5.8-5.8z");
}

.hq0_h_g3s {
  stop-color: var(--svg-color--fff353, #FFF353);
}

.i_c_j-b7t {
  fill: var(--svg-color--e35a2f, #E35A2F);
  d: path("M18.208 19.188c-.99 0-2.06.616-2.196 1.116c-.039.143-.019.396.571.396h3.258c.325 0 .557-.099.514-.333c-.133-.736-1.156-1.18-2.147-1.18");
}

.i17-dv7xk {
  stop-color: var(--svg-color--8e7aaa, #8E7AAA);
  stop-opacity: 0;
}

.i9b8xkb-a {
  stop-color: var(--svg-color--c68b33, #C68B33);
}

.idjqppgpe {
  stop-color: var(--svg-color--8d79a9, #8D79A9);
}

.ijn9aubeg {
  stop-color: var(--svg-color--c9beda, #C9BEDA);
}

.ijsxj-cof {
  stop-color: var(--svg-color--d0cfd1, #D0CFD1);
  stop-opacity: 0;
}

.itq_0gyjr {
  stop-color: var(--svg-color--847e80, #847E80);
}

.jh7izxthi {
  stop-color: var(--svg-color--a28fbe, #A28FBE);
}

.k_gs12hln {
  stop-color: var(--svg-color--a59ab7, #A59AB7);
}

.k21v0s6rc {
  stop-color: var(--svg-color--e8e0ec, #E8E0EC);
  stop-opacity: 0;
}

.khxyk7bdo {
  stop-color: var(--svg-color--a69490, #A69490);
}

.m-z7iyb1r {
  stop-color: var(--svg-color--d3d1d2, #D3D1D2);
}

.m5ovbtcga {
  stop-color: var(--svg-color--4d9237, #4D9237);
}

.m7gntabkn {
  stop-color: var(--svg-color--b3b1b2, #B3B1B2);
}

.mclm89b3c {
  stop-color: var(--svg-color--fcfbfc, #FCFBFC);
}

.mkbl3bigu {
  fill: var(--svg-color--e35a2f, #E35A2F);
  d: path("M22.956 21.278c-.99 0-2.06.617-2.196 1.117c-.04.143-.02.396.57.396h3.259c.325 0 .556-.1.514-.334c-.133-.736-1.157-1.179-2.147-1.179");
}

.mujqfi9pk {
  stop-color: var(--svg-color--8d7ea3, #8D7EA3);
}

.n15fh3b3y {
  stop-color: var(--svg-color--c38680, #C38680);
  stop-opacity: 0;
}

.n7np1h20q {
  stop-color: var(--svg-color--a396b6, #A396B6);
  stop-opacity: 0;
}

.ni656pv8f {
  stop-color: var(--svg-color--f66b25, #F66B25);
}

.o-kl78s5m {
  fill: var(--svg-color--e3e1e4, #E3E1E4);
  d: path("M15.25 11.53a.286.286 0 0 1 .396-.08l.749.477a.286.286 0 0 1-.314.478l-.75-.478a.286.286 0 0 1-.081-.396");
}

.o1kz-86cr {
  d: path("M13.31 10c-3.54 0-6.53 2.33-7.52 5.54c-.35 1.16.53 2.32 1.74 2.32h11.55c1.21 0 2.1-1.17 1.74-2.32A7.86 7.86 0 0 0 13.31 10");
}

.o4nv0nbzo {
  stop-color: var(--svg-color--cbc9cb, #CBC9CB);
  stop-opacity: 0;
}

.oa50k2c2e {
  fill: var(--svg-color--dbd5df, #DBD5DF);
  d: path("M12.719 13.281a.286.286 0 0 1 .393.095l.436.693a.286.286 0 0 1-.488.298l-.437-.693a.286.286 0 0 1 .096-.393");
}

.oe350oahz {
  stop-color: var(--svg-color--c78d34, #C78D34);
  stop-opacity: 0;
}

.p_4r8qbfu {
  stop-color: var(--svg-color--c4bbd1, #C4BBD1);
}

.pqvqzqb1y {
  fill: var(--svg-color--bf462a, #BF462A);
  d: path("M12.552 20.898c.393 0 .71-.165.71-.43c0-.315-.317-.57-.71-.57s-.71.255-.71.57c0 .277.317.43.71.43");
}

.qhrf4gszc {
  stop-color: var(--svg-color--e7ddea, #E7DDEA);
}

.qqam5l_kw {
  fill: var(--svg-color--d7d1da, #D7D1DA);
  d: path("M16.227 13.758a.286.286 0 0 1 .19.357l-.257.833a.286.286 0 1 1-.547-.167l.257-.833a.286.286 0 0 1 .357-.19");
}

.rltbnaclt {
  d: path("M18.528 18.88c-1.022 0-2.125.862-2.265 1.397c-.04.152-.02.423.588.423h3.361c.335 0 .574-.106.53-.356c-.137-.788-1.193-1.464-2.214-1.464");
}

.rvlh4n2ye {
  stop-color: var(--svg-color--726681, #726681);
}

.sl7xtk4zx {
  d: path("M23.42 21.984c.413-.012 1.464.177 1.907.344c-.4-.55-1.469-.844-2.016-.844c-.312 0-.303.513.11.5");
}

.spfyce2lg {
  stop-color: var(--svg-color--6f6a72, #6F6A72);
}

.tpqrf5bzb {
  stop-color: var(--svg-color--d8d3df, #D8D3DF);
}

.tqvi83b3b {
  stop-color: var(--svg-color--fdfbff, #FDFBFF);
}

.u-7zlhbup {
  stop-color: var(--svg-color--dddbdd, #DDDBDD);
}

.u3f5r0h8m {
  stop-color: var(--svg-color--c3867e, #C3867E);
}

.u8nm-ac6e {
  fill: var(--svg-color--c3bec8, #C3BEC8);
  d: path("M8.722 14.286a.286.286 0 0 1-.151.375l-.804.338a.286.286 0 1 1-.223-.526l.803-.339a.286.286 0 0 1 .375.152");
}

.uar96jblh {
  d: path("M22.02 11.06h-12A8.02 8.02 0 0 0 2 19.08a8.02 8.02 0 0 0 8.02 8.02h12a8.02 8.02 0 0 0 8.02-8.02a8.02 8.02 0 0 0-8.02-8.02");
}

.uh8vtd1av {
  stop-color: var(--svg-color--888786, #888786);
  stop-opacity: 0;
}

.v15c70bsy {
  stop-color: var(--svg-color--cc562e, #CC562E);
}

.v4yghqbwv {
  d: path("M23.983 17.727c.413-.013 1.464.177 1.907.343c-.4-.55-1.47-.843-2.016-.843c-.312 0-.303.512.11.5");
}

.veqfi41nu {
  stop-color: var(--svg-color--3fb848, #3FB848);
}

.vfsndizjy {
  d: path("M23.219 21.016c-1.022 0-2.066.822-2.206 1.357c-.04.153-.02.424.588.424h3.361c.335 0 .574-.106.53-.357c-.137-.787-1.252-1.424-2.273-1.424");
}

.vnreirbsb {
  d: path("M20.74 29.96h-9.28c-4.02 0-7.29-3.26-7.29-7.29v-2.88h23.85v2.88a7.27 7.27 0 0 1-7.28 7.29");
}

.vy8-abbvv {
  stop-color: var(--svg-color--d59935, #D59935);
}

.w323bgbvu {
  stop-color: var(--svg-color--8e8c8d, #8E8C8D);
}

.w32njgoab {
  stop-color: var(--svg-color--fff872, #FFF872);
}

.wphwi-l8v {
  stop-color: var(--svg-color--84f08b, #84F08B);
}

.x2u9k0jhs {
  fill: var(--svg-color--d6d2d9, #D6D2D9);
  d: path("M10.492 12.2a.286.286 0 0 1 .219.34l-.186.852a.286.286 0 0 1-.559-.12l.186-.852a.286.286 0 0 1 .34-.22");
}

.xrtg8ibpj {
  stop-color: var(--svg-color--ff9027, #FF9027);
}

.y3gebxxdx {
  d: path("M7.78 20.102c.43 0 .78-.227.78-.592a.78.78 0 1 0-1.56 0c0 .38.35.592.78.592");
}

.y3j_kccjt {
  fill: var(--svg-color--d0c5ca, #D0C5CA);
  d: path("M18.352 14.933a.286.286 0 0 1 .296.275l.03.872a.286.286 0 0 1-.57.021l-.031-.871a.286.286 0 0 1 .275-.297");
}

.ynlnkmbzw {
  stop-color: var(--svg-color--ff8e36, #FF8E36);
}

.z642czbbn {
  stop-color: var(--svg-color--c54f2d, #C54F2D);
  stop-opacity: 0;
}

.zq3seebvn {
  stop-color: var(--svg-color--863b1f, #863B1F);
}

</style>
