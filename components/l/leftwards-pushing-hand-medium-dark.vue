<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y8ivzxb6k"/><path fill="url(#irIJkub)" class="o-61vqaqh"/><path fill="url(#iPtTk6c)" class="o-61vqaqh"/><path fill="url(#iClSPce)" class="o-61vqaqh"/><path fill="url(#ijyfssd)" class="o-61vqaqh"/><path fill="url(#iYOKwQO)" class="o-61vqaqh"/><path fill="url(#ivvWd2c)" class="o-61vqaqh"/><path fill="url(#iojVyDe)" class="o-61vqaqh"/><path fill="url(#inTB6oo)" class="o-61vqaqh"/><path fill="url(#iFNfN2b)" class="o-61vqaqh"/><path fill="url(#iMz3ZGc)" class="o-61vqaqh"/><path fill="url(#ifzDnbe)" class="o-61vqaqh"/><path fill="url(#iaxOnFb)" class="vhv2grbps"/><path class="ektnl4b5b"/><path fill="url(#if4qgGq)" class="k8k-8p0-i"/><path fill="url(#iNp6KSd)" class="i8ssfzbtz"/><path fill="url(#i4KuX4b)" class="k8k-8p0-i"/><path fill="url(#i9IE5tc)" class="k8k-8p0-i"/><path fill="url(#iqJjwsc)" class="k8k-8p0-i"/><path fill="url(#idifKuX)" class="k8k-8p0-i"/><path fill="url(#ixipp8d)" class="k8k-8p0-i"/><path fill="url(#iWCadOe)" class="k8k-8p0-i"/><path fill="url(#iR105tk)" class="k8k-8p0-i"/><path fill="url(#ifYOgRc)" class="k8k-8p0-i"/><path fill="url(#iBY9Znc)" class="k8k-8p0-i"/><path fill="url(#iWnIUjz)" class="ovrqzubcx"/><path fill="url(#izu3rob)" class="dn13e16ka"/><path fill="url(#iblKUud)" class="ovrqzubcx"/><path fill="url(#i4kbFtc)" class="ovrqzubcx"/><path fill="url(#i62MUlb)" class="e7-f36zoo"/><path fill="url(#ivfasMd)" class="e7-f36zoo"/><path fill="url(#iBviBbC)" class="e7-f36zoo"/><path fill="url(#iTiDfVc)" class="e7-f36zoo"/><path fill="url(#iFNVnAd)" class="e7-f36zoo"/><path fill="url(#icEWOEF)" class="o2zxavsxe"/><path fill="url(#ir9Cmkc)" class="o2zxavsxe"/><path fill="url(#iw4Qg7E)" class="o2zxavsxe"/><path fill="url(#i33syrd)" class="o2zxavsxe"/><path fill="url(#iUP1C9d)" class="o2zxavsxe"/><path fill="url(#iFqhA1A)" class="zeskxvswy"/><path fill="url(#iNGXqAH)" class="zeskxvswy"/><path fill="url(#iCXTdwm)" class="zeskxvswy"/><path fill="url(#iFTyXue)" class="zeskxvswy"/><path fill="url(#iNNZ0ob)" class="zeskxvswy"/><path fill="url(#i4el7hb)" class="zeskxvswy"/><path class="kye84pb1h"/><path fill="url(#iicoHqe)" class="o83sobbar"/><path fill="url(#iRYAQYc)" class="o83sobbar"/><path fill="url(#iajv04d)" class="o83sobbar"/><path fill="url(#i0X6LNd)" class="o83sobbar"/><path fill="url(#iWCzZpd)" class="o83sobbar"/><path fill="url(#ivHQ6tc)" class="o83sobbar"/><path fill="url(#in0WM3j)" class="o83sobbar"/><path fill="url(#iCJz9De)" class="o83sobbar"/><path fill="url(#iSN7gse)" class="hsc9j6bft"/><path fill="url(#i2BXYJe)" class="hsc9j6bft"/><path fill="url(#iYb5ABf)" class="hsc9j6bft"/><path fill="url(#itu0TLb)" class="hsc9j6bft"/><path fill="url(#i0sgLod)" class="hsc9j6bft"/><path fill="url(#ibnXpbd)" class="hsc9j6bft"/><path fill="url(#irn1MOx)" class="hsc9j6bft"/><path fill="url(#iVMKnvc)" class="hsc9j6bft"/><path fill="url(#i2KYFmc)" class="hsc9j6bft"/><defs><radialGradient id="iClSPce" cx="0" cy="0" r="1" gradientTransform="rotate(81.469 -3.443 20.66)scale(10.1119 24.3768)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="ivvWd2c" cx="0" cy="0" r="1" gradientTransform="matrix(.68764 6.50127 -6.0031 .63494 14.32 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="iojVyDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53853 7.97018 -6.15248 -.41571 14.9 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="inTB6oo" cx="0" cy="0" r="1" gradientTransform="rotate(147.095 12.777 12.887)scale(19.0802 24.1752)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="iFNfN2b" cx="0" cy="0" r="1" gradientTransform="matrix(7.822 5.35543 -6.78547 9.91068 15.167 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="iMz3ZGc" cx="0" cy="0" r="1" gradientTransform="rotate(161.642 15.253 12.985)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="if4qgGq" cx="0" cy="0" r="1" gradientTransform="rotate(-138.262 12.229 10.024)scale(8.19524 7.34776)" gradientUnits="userSpaceOnUse"><stop class="nz4brjbne"/><stop offset="1" class="fd00fsb_z"/></radialGradient><radialGradient id="i4KuX4b" cx="0" cy="0" r="1" gradientTransform="rotate(-128.224 12.914 10.751)scale(8.31471 7.09704)" gradientUnits="userSpaceOnUse"><stop class="o39u29oav"/><stop offset="1" class="posf_mbnu"/></radialGradient><radialGradient id="i9IE5tc" cx="0" cy="0" r="1" gradientTransform="rotate(79.765 -6.307 17.166)scale(4.22927 3.79191)" gradientUnits="userSpaceOnUse"><stop class="z6sxc_vfa"/><stop offset="1" class="irc0o41lu"/></radialGradient><radialGradient id="iqJjwsc" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 1.89063 -1.69511 .18212 7.485 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="em6rkhrca"/><stop offset="1" class="u3oyy5beq"/></radialGradient><radialGradient id="idifKuX" cx="0" cy="0" r="1" gradientTransform="matrix(-.9643 1.34314 -1.20425 -.86458 11.944 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="em6rkhrca"/><stop offset="1" class="u3oyy5beq"/></radialGradient><radialGradient id="ixipp8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99748 1.8253 -1.63654 -1.79092 13.77 14.038)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="em6rkhrca"/><stop offset="1" class="u3oyy5beq"/></radialGradient><radialGradient id="iWCadOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45313 1.875 -1.6811 -.40627 9.813 12.39)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="ozr_mgd4a"/><stop offset="1" class="wad84kb6z"/></radialGradient><radialGradient id="iR105tk" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 4.125 -2.69798 1.75778 13.688 20.313)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="x0qznyexi"/><stop offset="1" class="w0qa1vhqw"/></radialGradient><radialGradient id="ifYOgRc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.31818 3.71842 -3.3339 -5.66481 19.082 22.25)" gradientUnits="userSpaceOnUse"><stop class="iuqfkonly"/><stop offset="1" class="zujbj7bxd"/></radialGradient><radialGradient id="iBY9Znc" cx="0" cy="0" r="1" gradientTransform="rotate(80.393 -3.291 13.08)scale(7.29006 13.501)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="fgr5ljbtv"/><stop offset="1" class="os_jlkbbi"/></radialGradient><radialGradient id="izu3rob" cx="0" cy="0" r="1" gradientTransform="rotate(-99.139 11.643 4.219)scale(9.07953 6.02015)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="jlx20wbss"/><stop offset="1" class="dgr_iccvd"/></radialGradient><radialGradient id="iblKUud" cx="0" cy="0" r="1" gradientTransform="matrix(-.29707 4.5543 -.6809 -.04441 9.12 10.408)" gradientUnits="userSpaceOnUse"><stop class="otjwecbdt"/><stop offset="1" class="qqasdabml"/></radialGradient><radialGradient id="ivfasMd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09735 -10.6667 6.36718 -.65503 11.733 15.264)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="qo203db1d"/><stop offset="1" class="akmwvhlee"/></radialGradient><radialGradient id="iBviBbC" cx="0" cy="0" r="1" gradientTransform="rotate(-84.713 12.329 .618)scale(8.27578 3.00234)" gradientUnits="userSpaceOnUse"><stop offset=".95" class="qo203db1d"/><stop offset="1" class="akmwvhlee"/></radialGradient><radialGradient id="iTiDfVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2503 4.43595 -.59456 -.03355 11.467 9.203)" gradientUnits="userSpaceOnUse"><stop class="zbwi-0bpz"/><stop offset="1" class="bsic80bbi"/></radialGradient><radialGradient id="ir9Cmkc" cx="0" cy="0" r="1" gradientTransform="rotate(90.988 5.12 9.44)scale(2.4171)" gradientUnits="userSpaceOnUse"><stop class="f0s742brh"/><stop offset="1" class="cp34s2bsp"/></radialGradient><radialGradient id="iw4Qg7E" cx="0" cy="0" r="1" gradientTransform="matrix(-.69914 4.6297 -.67506 -.10194 13.649 9.387)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o7gf38suf"/><stop offset=".232" class="o7gf38suf"/><stop offset="1" class="yfxlb5b1p"/></radialGradient><radialGradient id="i33syrd" cx="0" cy="0" r="1" gradientTransform="matrix(.05462 7.9463 -4.4508 .0306 14.727 9.35)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="o5rrv-b0r"/><stop offset=".944" class="khg19xbwl"/></radialGradient><radialGradient id="iNGXqAH" cx="0" cy="0" r="1" gradientTransform="matrix(-.3759 1.44996 -1.08526 -.28136 16.578 6.214)" gradientUnits="userSpaceOnUse"><stop class="mmsi0pvtf"/><stop offset="1" class="uz1sdv6yi"/></radialGradient><radialGradient id="iCXTdwm" cx="0" cy="0" r="1" gradientTransform="rotate(124.218 4.036 10.903)scale(3.56813 2.05017)" gradientUnits="userSpaceOnUse"><stop class="yyylqcpod"/><stop offset="1" class="naoxn1bbj"/></radialGradient><radialGradient id="iNNZ0ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.4375 -2.66064 0 15.32 13.937)" gradientUnits="userSpaceOnUse"><stop class="px3pzpb9j"/><stop offset="1" class="kvhr4-bgm"/></radialGradient><radialGradient id="i4el7hb" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 5.897 9.19)scale(2.84289 1.38778)" gradientUnits="userSpaceOnUse"><stop class="i2dm45b8e"/><stop offset="1" class="no8_v5u0s"/></radialGradient><radialGradient id="iRYAQYc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 8 -4.8677 -2.28175 18.375 16.5)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="ic_oekbrx"/><stop offset=".82" class="rla3sgb9i"/></radialGradient><radialGradient id="iajv04d" cx="0" cy="0" r="1" gradientTransform="rotate(115.769 5.298 12.337)scale(4.16637 3.02086)" gradientUnits="userSpaceOnUse"><stop class="mztcpwbis"/><stop offset=".393" class="znxffybit"/><stop offset="1" class="mp1nb-bgs"/></radialGradient><radialGradient id="i0X6LNd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.125 -2.75001 3.96162 -4.50181 18.062 21.125)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="aw01fbhnl"/><stop offset="1" class="ao7ve8erv"/></radialGradient><radialGradient id="iWCzZpd" cx="0" cy="0" r="1" gradientTransform="matrix(2.8562 5.33265 -4.90861 2.62908 13.375 18.125)" gradientUnits="userSpaceOnUse"><stop class="skpy8j1jk"/><stop offset="1" class="w_5gbwb4y"/></radialGradient><radialGradient id="ivHQ6tc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71402 3.80039 -1.45013 -.65403 15.968 16.887)" gradientUnits="userSpaceOnUse"><stop class="zupjj7rvi"/><stop offset="1" class="n5_27-qnb"/></radialGradient><radialGradient id="in0WM3j" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06177 0 0 -2.47144 19.936 21.562)" gradientUnits="userSpaceOnUse"><stop class="oq-ut2bul"/><stop offset="1" class="p1agndbko"/></radialGradient><radialGradient id="iCJz9De" cx="0" cy="0" r="1" gradientTransform="rotate(114.193 4.41 13.67)scale(8.99795 5.47492)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="zju_2hbti"/><stop offset=".907" class="jdqny-mqy"/></radialGradient><radialGradient id="iSN7gse" cx="0" cy="0" r="1" gradientTransform="rotate(147.212 5.531 14.62)scale(2.95308 2.71188)" gradientUnits="userSpaceOnUse"><stop class="fqu36q4vx"/><stop offset="1" class="dhh0mwbxp"/></radialGradient><radialGradient id="i2BXYJe" cx="0" cy="0" r="1" gradientTransform="rotate(142.892 5.86 14.371)scale(2.8478 2.6152)" gradientUnits="userSpaceOnUse"><stop class="y4au8vkif"/><stop offset="1" class="g7gvm8mbp"/></radialGradient><radialGradient id="iYb5ABf" cx="0" cy="0" r="1" gradientTransform="matrix(2.60627 4.4161 -4.0554 2.3934 12.693 23.19)" gradientUnits="userSpaceOnUse"><stop class="voyz5_blb"/><stop offset="1" class="r1v80cb3t"/></radialGradient><radialGradient id="itu0TLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0408 5.76563 -10.73371 1.93762 12.15 20.203)" gradientUnits="userSpaceOnUse"><stop class="g63gik1db"/><stop offset=".701" class="z5lrrhgst"/></radialGradient><radialGradient id="i0sgLod" cx="0" cy="0" r="1" gradientTransform="matrix(-.179 1.9355 -.59203 -.05475 9.353 12.964)" gradientUnits="userSpaceOnUse"><stop class="yl31b9krk"/><stop offset="1" class="nc1xd6bio"/></radialGradient><radialGradient id="ibnXpbd" cx="0" cy="0" r="1" gradientTransform="matrix(.14544 1.76768 -.5407 .04449 6.96 13.48)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="yl31b9krk"/><stop offset="1" class="nc1xd6bio"/></radialGradient><radialGradient id="irn1MOx" cx="0" cy="0" r="1" gradientTransform="matrix(-.7272 1.52155 -.46541 -.22244 11.233 12.596)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="yl31b9krk"/><stop offset="1" class="nc1xd6bio"/></radialGradient><radialGradient id="iVMKnvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7384 1.34254 -.41066 -.22586 13.101 13.02)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="yl31b9krk"/><stop offset="1" class="nc1xd6bio"/></radialGradient><radialGradient id="i2KYFmc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.77407 2.51145 -.43422 -.30673 14.013 14.986)" gradientUnits="userSpaceOnUse"><stop class="igzmtw34n"/><stop offset=".609" class="qe5lgx_dk"/></radialGradient><linearGradient id="irIJkub" x1="23.5" x2="22.988" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="iPtTk6c" x1="16.5" x2="19.625" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="ijyfssd" x1="32.55" x2="24.875" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iYOKwQO" x1="25.25" x2="23.437" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="ifzDnbe" x1="24.117" x2="23.274" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="iaxOnFb" x1="18.128" x2="16.017" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="yy9ap1b0c"/><stop offset=".333" class="z15t62l8q"/><stop offset=".667" class="w4mwv6wdq"/><stop offset="1" class="iig0byb3l"/></linearGradient><linearGradient id="iNp6KSd" x1="10.687" x2="12.764" y1="13.282" y2="25.968" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xv6nke6rj"/><stop offset=".159" class="zu9qgsboa"/><stop offset=".479" class="ie9xuibrm"/><stop offset=".76" class="zl-5mqcdu"/><stop offset="1" class="oe9y4qo0b"/></linearGradient><linearGradient id="iWnIUjz" x1="6.443" x2="10.363" y1="11.856" y2="11.856" gradientUnits="userSpaceOnUse"><stop class="t03t6abhg"/><stop offset=".109" class="svrcrdtnt"/><stop offset=".333" class="pjd2b0bvq"/><stop offset=".521" class="agrs0qg9j"/><stop offset=".661" class="xp4ebpb7h"/><stop offset=".922" class="nux5uy2bx"/></linearGradient><linearGradient id="i4kbFtc" x1="7.125" x2="8.328" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".226" class="wlyb77bmb"/><stop offset=".572" class="h2ug0z0zy"/></linearGradient><linearGradient id="i62MUlb" x1="8.97" x2="12.677" y1="10.02" y2="10.308" gradientUnits="userSpaceOnUse"><stop class="f6eqvfb8f"/><stop offset=".127" class="yl31b9krk"/><stop offset=".316" class="g5zxn35jf"/><stop offset=".394" class="x0re-xbhh"/><stop offset=".583" class="yba09kbmn"/><stop offset=".714" class="dsjij-pkz"/></linearGradient><linearGradient id="iFNVnAd" x1="9.478" x2="10.937" y1="11.166" y2="13.694" gradientUnits="userSpaceOnUse"><stop offset=".226" class="nifr0pbco"/><stop offset=".572" class="lfseikblh"/></linearGradient><linearGradient id="icEWOEF" x1="11.529" x2="15.358" y1="9.002" y2="9.002" gradientUnits="userSpaceOnUse"><stop class="cysg0jfku"/><stop offset=".188" class="atgwsfb5v"/><stop offset=".359" class="t9-cnpl-f"/></linearGradient><linearGradient id="iUP1C9d" x1="12.734" x2="11.065" y1="10.703" y2="13.759" gradientUnits="userSpaceOnUse"><stop offset=".226" class="p6o42styu"/><stop offset=".572" class="oor8s_bxu"/></linearGradient><linearGradient id="iFqhA1A" x1="13.514" x2="17.483" y1="9.649" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="qao2uwb2c"/><stop offset=".24" class="g78tvltgh"/><stop offset=".432" class="qhrpt4ojz"/><stop offset=".651" class="fr3wkrbai"/><stop offset="1" class="t1b2tkb5t"/></linearGradient><linearGradient id="iFTyXue" x1="14.421" x2="12.31" y1="12.812" y2="14.989" gradientUnits="userSpaceOnUse"><stop offset=".226" class="z1e7a4b3f"/><stop offset=".572" class="eaxonmbpp"/></linearGradient><linearGradient id="iicoHqe" x1="18.805" x2="16.525" y1="11.277" y2="20.687" gradientUnits="userSpaceOnUse"><stop class="jnlcrhr_s"/><stop offset="1" class="a5zypwbmi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-pushing-hand-medium-dark" /></template>
<style>
.a5zypwbmi {
  stop-color: var(--svg-color--825c50, #825C50);
  stop-opacity: 0;
}

.agrs0qg9j {
  stop-color: var(--svg-color--684746, #684746);
}

.ajic0q7cm {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

.akmwvhlee {
  stop-color: var(--svg-color--70584e, #70584E);
}

.ao7ve8erv {
  stop-color: var(--svg-color--996f71, #996F71);
  stop-opacity: 0;
}

.atgwsfb5v {
  stop-color: var(--svg-color--694744, #694744);
}

.aw01fbhnl {
  stop-color: var(--svg-color--996f71, #996F71);
}

.bh-87dbgb {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

.bsic80bbi {
  stop-color: var(--svg-color--482a2d, #482A2D);
  stop-opacity: 0;
}

.cp34s2bsp {
  stop-color: var(--svg-color--9c7d6f, #9C7D6F);
  stop-opacity: 0;
}

.cysg0jfku {
  stop-color: var(--svg-color--74524b, #74524B);
}

.dgr_iccvd {
  stop-color: var(--svg-color--6e564e, #6E564E);
}

.dhh0mwbxp {
  stop-color: var(--svg-color--8e5f66, #8E5F66);
  stop-opacity: 0;
}

.dn13e16ka {
  fill-opacity: var(--svg-fill-opacity--0-96, 0.96);
  d: path("m6.503 11.896l-.06 2.666c1.688-.203 2.602-1.26 2.602-2.744c.012-.255.046-.838.09-1.766c.036-.743.143-2.258.193-2.923c-.252-.083-.896-.175-1.455.123c-1.351.607-1.252 1.986-1.37 4.644");
}

.dsjij-pkz {
  stop-color: var(--svg-color--452828, #452828);
}

.e7-f36zoo {
  d: path("M9.082 10.704c-.036 1.254-.216 2.174-.3 2.478c.965-.182 2.696-.41 2.587-2.715c.009-.483.072-1.822.109-2.45c.036-.63.137-2.46.255-3.39c-.255-.036-.692-.127-1.476.383c-.783.51-.829 1.34-.92 1.977c-.091.638-.21 2.15-.255 3.717");
}

.eaxonmbpp {
  stop-color: var(--svg-color--76534c, #76534C);
}

.eebf5ub9j {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

.ektnl4b5b {
  fill: var(--svg-color--734157, #734157);
  d: path("M7.91 21.687c1.05 2.271 3.92 3.744 5.223 4.196c.56.18 2.16.195 4.087-1.184c2.408-1.723 1.134-4.65 1.067-4.96s-.31-.93-.343-1.114s.1-.954.285-1.439c.147-.388.63-1.311.853-1.724l-2.829-3.332l-9.69-1.099c-.026 1.097-.25 4.078-.082 5.583v.012c.078 1.442.12 2.229 1.43 5.06");
}

.em6rkhrca {
  stop-color: var(--svg-color--724e48, #724E48);
}

.f0s742brh {
  stop-color: var(--svg-color--9c7d6f, #9C7D6F);
}

.f6eqvfb8f {
  stop-color: var(--svg-color--614038, #614038);
}

.fd00fsb_z {
  stop-color: var(--svg-color--753d60, #753D60);
  stop-opacity: 0;
}

.fgr5ljbtv {
  stop-color: var(--svg-color--75514b, #75514B);
}

.fqu36q4vx {
  stop-color: var(--svg-color--8e5f66, #8E5F66);
}

.fr3wkrbai {
  stop-color: var(--svg-color--956e65, #956E65);
}

.ft5dv1b6b {
  fill: none;
}

.g5zxn35jf {
  stop-color: var(--svg-color--6f4c47, #6F4C47);
}

.g63gik1db {
  stop-color: var(--svg-color--795251, #795251);
}

.g78tvltgh {
  stop-color: var(--svg-color--724c47, #724C47);
}

.g7gvm8mbp {
  stop-color: var(--svg-color--906371, #906371);
  stop-opacity: 0;
}

.gmmht-bmp {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0;
}

.h2ug0z0zy {
  stop-color: var(--svg-color--75524a, #75524A);
}

.hsc9j6bft {
  d: path("m16.116 12.126l-9.636-.251c-.026 1.096-.063 3.58 0 4.739v.012c.078 1.441.121 2.228 1.43 5.06c1.05 2.272 3.919 3.745 5.222 4.197c.56.18 2.16.194 4.087-1.184c1.46-1.045 1.566-2.532 1.41-3.61a8 8 0 0 0-.024-.269c-.035-.328-.246-.94-.424-1.457c-.102-.297-.194-.563-.234-.723l-.005-.023c-.029-.197.104-.952.286-1.431c.147-.389.63-1.311.853-1.724l-.009-.01c.17-.314.362-.674.575-1.1c.764-1.527-.047-3.164-1.684-3.07c-.907.051-1.407.317-1.847.844");
}

.i-lj0-gmv {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
  stop-opacity: 0;
}

.i2dm45b8e {
  stop-color: var(--svg-color--573933, #573933);
}

.i6o-qu9fo {
  stop-color: var(--svg-color--852dbd, #852DBD);
}

.i8ssfzbtz {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.91 21.687c1.05 2.271 3.92 3.744 5.223 4.196c.56.18 2.16.195 4.087-1.184c2.408-1.723 1.134-4.65 1.067-4.96s-.31-.93-.343-1.114s.1-.954.285-1.439c.147-.388.63-1.311.853-1.724l-2.829-3.332l-9.69-1.099c-.026 1.097-.25 4.078-.082 5.583v.012c.078 1.442.12 2.229 1.43 5.06");
}

.ic_oekbrx {
  stop-color: var(--svg-color--784357, #784357);
  stop-opacity: 0;
}

.ie9xuibrm {
  stop-color: var(--svg-color--785251, #785251);
}

.igzmtw34n {
  stop-color: var(--svg-color--5b3b37, #5B3B37);
}

.iig0byb3l {
  stop-color: var(--svg-color--6c3760, #6C3760);
}

.ink3gpbzz {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

.irc0o41lu {
  stop-color: var(--svg-color--795153, #795153);
  stop-opacity: 0;
}

.iuqfkonly {
  stop-color: var(--svg-color--8c5d63, #8C5D63);
}

.j-f1eub7w {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

.jdqny-mqy {
  stop-color: var(--svg-color--824c64, #824C64);
}

.jlx20wbss {
  stop-color: var(--svg-color--6e564e, #6E564E);
  stop-opacity: 0;
}

.jn_5q-btc {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

.jnlcrhr_s {
  stop-color: var(--svg-color--825c50, #825C50);
}

.k8k-8p0-i {
  d: path("M7.91 21.687c1.05 2.271 3.92 3.744 5.223 4.196c.56.18 2.16.195 4.087-1.184c2.408-1.723 1.134-4.65 1.067-4.96s-.31-.93-.343-1.114s.1-.954.285-1.439c.147-.388.63-1.311.853-1.724l-2.829-3.332l-9.69-1.099c-.026 1.097-.25 4.078-.082 5.583v.012c.078 1.442.12 2.229 1.43 5.06");
}

.k90wp6bmc {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

.khg19xbwl {
  stop-color: var(--svg-color--725448, #725448);
}

.kvhr4-bgm {
  stop-color: var(--svg-color--6c4946, #6C4946);
  stop-opacity: 0;
}

.kye84pb1h {
  fill: var(--svg-color--754950, #754950);
  d: path("M14.992 13.928c-.818 1.407-1.593 2.09-1.878 2.256c-.088.051-1.862 2.456 1.212 5.877c1.669 1.469 4.692 2.669 4.279-1.241c-.055-.518-.548-1.744-.658-2.18c-.087-.35.11-1.03.219-1.325c.234-.764.717-1.435 1.48-2.962c.765-1.528-.046-3.165-1.683-3.072c-1.637.094-1.95.887-2.971 2.647");
}

.lfseikblh {
  stop-color: var(--svg-color--6c4b43, #6C4B43);
}

.m7gdckjal {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

.mmsi0pvtf {
  stop-color: var(--svg-color--9b7668, #9B7668);
}

.mp1nb-bgs {
  stop-color: var(--svg-color--825951, #825951);
  stop-opacity: 0;
}

.mztcpwbis {
  stop-color: var(--svg-color--a07c72, #A07C72);
}

.n5_27-qnb {
  stop-color: var(--svg-color--7e4c5d, #7E4C5D);
  stop-opacity: 0;
}

.naoxn1bbj {
  stop-color: var(--svg-color--5d3c3b, #5D3C3B);
  stop-opacity: 0;
}

.nc1xd6bio {
  stop-color: var(--svg-color--77554d, #77554D);
  stop-opacity: 0;
}

.nifr0pbco {
  stop-color: var(--svg-color--6c4b43, #6C4B43);
  stop-opacity: 0;
}

.no8_v5u0s {
  stop-color: var(--svg-color--573933, #573933);
  stop-opacity: 0;
}

.nux5uy2bx {
  stop-color: var(--svg-color--462728, #462728);
}

.nz4brjbne {
  stop-color: var(--svg-color--753d60, #753D60);
}

.o-61vqaqh {
  d: path("m13.99 26.047l3.026-8.769c.059.216.94.29 1.373.3l13.598 2.352v11.553l-14.752-2.527c-2.322-.306-3.125-2.074-3.246-2.91");
}

.o2zxavsxe {
  d: path("M11.37 10.027c-.062 1.684-.267 1.689-.377 1.975c1.07 1.51 3.642.885 4.794.384V4.627c-.108-.717-.708-2.1-2.246-1.896c-1.923.256-1.88 2.214-1.958 3.316a165 165 0 0 0-.212 3.98");
}

.o39u29oav {
  stop-color: var(--svg-color--753e5f, #753E5F);
}

.o5rrv-b0r {
  stop-color: var(--svg-color--725448, #725448);
  stop-opacity: 0;
}

.o7gf38suf {
  stop-color: var(--svg-color--472b2c, #472B2C);
}

.o83sobbar {
  d: path("M14.992 13.928c-.818 1.407-1.593 2.09-1.878 2.256c-.088.051-1.862 2.456 1.212 5.877c1.669 1.469 4.692 2.669 4.279-1.241c-.055-.518-.548-1.744-.658-2.18c-.087-.35.11-1.03.219-1.325c.234-.764.717-1.435 1.48-2.962c.765-1.528-.046-3.165-1.683-3.072c-1.637.094-1.95.887-2.971 2.647");
}

.odhggkl1x {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

.oe9y4qo0b {
  stop-color: var(--svg-color--7d4674, #7D4674);
}

.oor8s_bxu {
  stop-color: var(--svg-color--725049, #725049);
}

.oq-ut2bul {
  stop-color: var(--svg-color--966a67, #966A67);
}

.os_jlkbbi {
  stop-color: var(--svg-color--75514b, #75514B);
  stop-opacity: 0;
}

.otjwecbdt {
  stop-color: var(--svg-color--402221, #402221);
}

.ovrqzubcx {
  d: path("m6.503 11.896l-.06 2.666c1.688-.203 2.602-1.26 2.602-2.744c.012-.255.046-.838.09-1.766c.036-.743.143-2.258.193-2.923c-.252-.083-.896-.175-1.455.123c-1.351.607-1.252 1.986-1.37 4.644");
}

.ozr_mgd4a {
  stop-color: var(--svg-color--6d4b46, #6D4B46);
}

.p1agndbko {
  stop-color: var(--svg-color--966a67, #966A67);
  stop-opacity: 0;
}

.p6o42styu {
  stop-color: var(--svg-color--725049, #725049);
  stop-opacity: 0;
}

.pe70qdb4r {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

.pf1xml9sl {
  stop-color: var(--svg-color--852aab, #852AAB);
}

.pjd2b0bvq {
  stop-color: var(--svg-color--704c46, #704C46);
}

.posf_mbnu {
  stop-color: var(--svg-color--753e5f, #753E5F);
  stop-opacity: 0;
}

.px3pzpb9j {
  stop-color: var(--svg-color--6c4946, #6C4946);
}

.qao2uwb2c {
  stop-color: var(--svg-color--79574e, #79574E);
}

.qe5lgx_dk {
  stop-color: var(--svg-color--5b3b37, #5B3B37);
  stop-opacity: 0;
}

.qhrpt4ojz {
  stop-color: var(--svg-color--805751, #805751);
}

.qo203db1d {
  stop-color: var(--svg-color--70584e, #70584E);
  stop-opacity: 0;
}

.qqasdabml {
  stop-color: var(--svg-color--402221, #402221);
  stop-opacity: 0;
}

.r1v80cb3t {
  stop-color: var(--svg-color--734059, #734059);
  stop-opacity: 0;
}

.r5htkxbvz {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

.rd54rdzck {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

.rla3sgb9i {
  stop-color: var(--svg-color--784357, #784357);
}

.s-b47gbty {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

.skpy8j1jk {
  stop-color: var(--svg-color--72484d, #72484D);
}

.svrcrdtnt {
  stop-color: var(--svg-color--704c47, #704C47);
}

.t03t6abhg {
  stop-color: var(--svg-color--83665e, #83665E);
}

.t1b2tkb5t {
  stop-color: var(--svg-color--946e60, #946E60);
}

.t9-cnpl-f {
  stop-color: var(--svg-color--694947, #694947);
}

.u3oyy5beq {
  stop-color: var(--svg-color--724e48, #724E48);
  stop-opacity: 0;
}

.uz1sdv6yi {
  stop-color: var(--svg-color--9b7668, #9B7668);
  stop-opacity: 0;
}

.v10_5zwzh {
  stop-color: var(--svg-color--806dd1, #806DD1);
  stop-opacity: 0;
}

.v6d9zubux {
  stop-color: var(--svg-color--465eff, #465EFF);
}

.vhv2grbps {
  d: path("M14.45 26.225c-.865-.173-1.416-.37-1.584-.447c2.339-3.984 6.98-11.862 6.83-11.512c-.188.437-1.017 2-1.384 2.718c-.367.72-.36 1.602-.36 1.758s.29.68.36 1.008c.07.078.633.625.797 1.828c.131.963.099 1.622.066 1.832c-.094 1.241-.6 1.906-1.02 2.384c-.735.834-1.872.87-2.137.828c-.138-.022-.486-.182-1.568-.397");
}

.voyz5_blb {
  stop-color: var(--svg-color--734059, #734059);
}

.vvyrbnhyh {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

.vy67icc3g {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

.w_5gbwb4y {
  stop-color: var(--svg-color--72484d, #72484D);
  stop-opacity: 0;
}

.w0qa1vhqw {
  stop-color: var(--svg-color--744155, #744155);
  stop-opacity: 0;
}

.w4mwv6wdq {
  stop-color: var(--svg-color--794162, #794162);
}

.wad84kb6z {
  stop-color: var(--svg-color--6d4b46, #6D4B46);
  stop-opacity: 0;
}

.wlyb77bmb {
  stop-color: var(--svg-color--75524a, #75524A);
  stop-opacity: 0;
}

.wz0ektb2t {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

.x0qznyexi {
  stop-color: var(--svg-color--744155, #744155);
}

.x0re-xbhh {
  stop-color: var(--svg-color--6a4845, #6A4845);
}

.xp4ebpb7h {
  stop-color: var(--svg-color--624344, #624344);
}

.xv6nke6rj {
  stop-color: var(--svg-color--75534b, #75534B);
}

.y4au8vkif {
  stop-color: var(--svg-color--906371, #906371);
}

.y8ivzxb6k {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m13.99 26.047l3.026-8.769c.059.216.94.29 1.373.3l13.598 2.352v11.553l-14.752-2.527c-2.322-.306-3.125-2.074-3.246-2.91");
}

.yba09kbmn {
  stop-color: var(--svg-color--57383b, #57383B);
}

.yfxlb5b1p {
  stop-color: var(--svg-color--472b2c, #472B2C);
  stop-opacity: 0;
}

.yk1d-rbcz {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

.yl31b9krk {
  stop-color: var(--svg-color--77554d, #77554D);
}

.yy9ap1b0c {
  stop-color: var(--svg-color--8c6365, #8C6365);
}

.yyylqcpod {
  stop-color: var(--svg-color--5d3c3b, #5D3C3B);
}

.z15t62l8q {
  stop-color: var(--svg-color--916663, #916663);
}

.z1e7a4b3f {
  stop-color: var(--svg-color--76534c, #76534C);
  stop-opacity: 0;
}

.z5lrrhgst {
  stop-color: var(--svg-color--795251, #795251);
  stop-opacity: 0;
}

.z6sxc_vfa {
  stop-color: var(--svg-color--795153, #795153);
}

.zbwi-0bpz {
  stop-color: var(--svg-color--482a2d, #482A2D);
}

.zeskxvswy {
  d: path("M13.404 10.228c-.217 1.955-.586 2.714-.744 2.85c.198 1.232.184 4.189.744 4.61c.965.726 2.704-1.725 3.446-2.077l.416-3.03c.203-1.629.627-5.024.699-5.574c.09-.687-.136-2.399-1.825-2.455S13.967 5.926 13.876 6.5l-.003.02c-.09.571-.202 1.292-.47 3.708");
}

.zju_2hbti {
  stop-color: var(--svg-color--824c64, #824C64);
  stop-opacity: 0;
}

.zl-5mqcdu {
  stop-color: var(--svg-color--734356, #734356);
}

.znxffybit {
  stop-color: var(--svg-color--825951, #825951);
}

.zu9qgsboa {
  stop-color: var(--svg-color--75524b, #75524B);
}

.zujbj7bxd {
  stop-color: var(--svg-color--8c5d63, #8C5D63);
  stop-opacity: 0;
}

.zupjj7rvi {
  stop-color: var(--svg-color--7e4c5d, #7E4C5D);
}

</style>
