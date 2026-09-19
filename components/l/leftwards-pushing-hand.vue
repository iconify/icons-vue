<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y8ivzxb6k"/><path fill="url(#irIJkub)" class="o-61vqaqh"/><path fill="url(#iPtTk6c)" class="o-61vqaqh"/><path fill="url(#iClSPce)" class="o-61vqaqh"/><path fill="url(#ijyfssd)" class="o-61vqaqh"/><path fill="url(#iYOKwQO)" class="o-61vqaqh"/><path fill="url(#ivvWd2c)" class="o-61vqaqh"/><path fill="url(#iojVyDe)" class="o-61vqaqh"/><path fill="url(#inTB6oo)" class="o-61vqaqh"/><path fill="url(#iFNfN2b)" class="o-61vqaqh"/><path fill="url(#iMz3ZGc)" class="o-61vqaqh"/><path fill="url(#ifzDnbe)" class="o-61vqaqh"/><path fill="url(#ivs3xcc)" class="vhv2grbps"/><path class="f6m366smq"/><path fill="url(#islFfMe)" class="cur7ilbwx"/><path fill="url(#i1C3jKc)" class="p3mtaj3rz"/><path fill="url(#isRd5oc)" class="cur7ilbwx"/><path fill="url(#iW3d4Be)" class="cur7ilbwx"/><path fill="url(#iCmoARb)" class="cur7ilbwx"/><path fill="url(#icWnSZc)" class="cur7ilbwx"/><path fill="url(#iV7ptoe)" class="cur7ilbwx"/><path fill="url(#iX2WMNd)" class="cur7ilbwx"/><path fill="url(#i7nlEkb)" class="cur7ilbwx"/><path fill="url(#igC9jBb)" class="cur7ilbwx"/><path fill="url(#i5JJeId)" class="ovrqzubcx"/><path fill="url(#iD3ZIec)" class="ovrqzubcx"/><path fill="url(#iad7ERc)" class="ovrqzubcx"/><path fill="url(#ioN2LHr)" class="ovrqzubcx"/><path fill="url(#iys2VVG)" class="ovrqzubcx"/><path fill="url(#iczgjNe)" class="e7-f36zoo"/><path fill="url(#ivFtkCu)" class="e7-f36zoo"/><path fill="url(#i1Jlwxe)" class="e7-f36zoo"/><path fill="url(#iwiDq1c)" class="e7-f36zoo"/><path fill="url(#io5nlFe)" class="e7-f36zoo"/><path fill="url(#irGtxgc)" class="e7-f36zoo"/><path fill="url(#iBp9Cwd)" class="o2zxavsxe"/><path fill="url(#imNQJdc)" class="o2zxavsxe"/><path fill="url(#iDiIR6f)" class="o2zxavsxe"/><path fill="url(#ix0nGpM)" class="o2zxavsxe"/><path fill="url(#iEzzDKe)" class="zeskxvswy"/><path fill="url(#iKyxtFb)" class="zeskxvswy"/><path fill="url(#iTNPMic)" class="zeskxvswy"/><path fill="url(#io1GRqd)" class="zeskxvswy"/><path fill="url(#iqzuyqT)" class="zeskxvswy"/><path fill="url(#iuuofoe)" class="zeskxvswy"/><path class="igr1z4b_e"/><path fill="url(#iBUzWWi)" class="o83sobbar"/><path fill="url(#i9tSohc)" class="o83sobbar"/><path fill="url(#izKNVAb)" class="o83sobbar"/><path fill="url(#isA5Ywd)" class="o83sobbar"/><path fill="url(#iIdGCHd)" class="o83sobbar"/><path fill="url(#iJLZm1d)" class="o83sobbar"/><path fill="url(#ik8ddti)" class="o83sobbar"/><path fill="url(#iZtEj7w)" class="o83sobbar"/><path fill="url(#i6yzYKd)" class="hsc9j6bft"/><path fill="url(#iqcBdGd)" class="hsc9j6bft"/><path fill="url(#iUR2hhL)" class="hsc9j6bft"/><defs><radialGradient id="iClSPce" cx="0" cy="0" r="1" gradientTransform="rotate(81.469 -3.443 20.66)scale(10.1119 24.3768)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="ivvWd2c" cx="0" cy="0" r="1" gradientTransform="matrix(.68764 6.50127 -6.0031 .63494 14.32 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="iojVyDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53853 7.97018 -6.15248 -.41571 14.9 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="inTB6oo" cx="0" cy="0" r="1" gradientTransform="rotate(147.095 12.777 12.887)scale(19.0802 24.1752)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="iFNfN2b" cx="0" cy="0" r="1" gradientTransform="matrix(7.822 5.35543 -6.78547 9.91068 15.167 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="iMz3ZGc" cx="0" cy="0" r="1" gradientTransform="rotate(161.642 15.253 12.985)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="islFfMe" cx="0" cy="0" r="1" gradientTransform="rotate(-138.262 12.229 10.025)scale(8.19524 7.34776)" gradientUnits="userSpaceOnUse"><stop class="a4mkhz4kt"/><stop offset="1" class="der68rb5o"/></radialGradient><radialGradient id="iW3d4Be" cx="0" cy="0" r="1" gradientTransform="matrix(.2058 10.0847 -9.04179 .18452 14.81 16.185)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="x1ob3cbbz"/><stop offset="1" class="ihbs0wphk"/></radialGradient><radialGradient id="iCmoARb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.224 12.913 10.751)scale(8.31471 7.09704)" gradientUnits="userSpaceOnUse"><stop class="o_5n5wgtf"/><stop offset="1" class="kmjznhzms"/></radialGradient><radialGradient id="icWnSZc" cx="0" cy="0" r="1" gradientTransform="rotate(79.765 -6.308 17.165)scale(4.22927 3.79191)" gradientUnits="userSpaceOnUse"><stop class="jjt_f1b4b"/><stop offset="1" class="urw491b2f"/></radialGradient><radialGradient id="iV7ptoe" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 1.89063 -1.69511 .18212 7.484 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="i5qzygb_i"/><stop offset="1" class="joq42sboe"/></radialGradient><radialGradient id="iX2WMNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.45313 1.875 -1.6811 -.40627 9.812 12.39)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="m9lg_cbcu"/><stop offset="1" class="joq42sboe"/></radialGradient><radialGradient id="i7nlEkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 4.125 -2.69798 1.75778 13.687 20.313)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="aix_4gzkl"/><stop offset="1" class="epudzbdem"/></radialGradient><radialGradient id="igC9jBb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.31818 3.71842 -3.3339 -5.66481 19.081 22.25)" gradientUnits="userSpaceOnUse"><stop class="gj1jxdboc"/><stop offset="1" class="r5znjwblf"/></radialGradient><radialGradient id="iD3ZIec" cx="0" cy="0" r="1" gradientTransform="rotate(-99.139 11.643 4.219)scale(9.07953 6.02015)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="lvxnl7_2g"/><stop offset="1" class="e_rci6btq"/></radialGradient><radialGradient id="iad7ERc" cx="0" cy="0" r="1" gradientTransform="rotate(128.157 2.588 5.99)scale(1.08814 .41767)" gradientUnits="userSpaceOnUse"><stop class="tul337ogz"/><stop offset="1" class="e1zr_oxer"/></radialGradient><radialGradient id="ioN2LHr" cx="0" cy="0" r="1" gradientTransform="rotate(93.604 -.668 9.797)scale(3.89053 .58167)" gradientUnits="userSpaceOnUse"><stop class="dle7c82hk"/><stop offset="1" class="rp7ma24gd"/></radialGradient><radialGradient id="ivFtkCu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09735 -10.6667 6.36718 -.65503 11.733 15.264)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="gwwf19bus"/><stop offset="1" class="u9094pbuo"/></radialGradient><radialGradient id="i1Jlwxe" cx="0" cy="0" r="1" gradientTransform="rotate(125.139 4.273 5.577)scale(1.19535 .44453)" gradientUnits="userSpaceOnUse"><stop class="tul337ogz"/><stop offset="1" class="e1zr_oxer"/></radialGradient><radialGradient id="iwiDq1c" cx="0" cy="0" r="1" gradientTransform="rotate(-84.713 12.329 .618)scale(8.27578 3.00234)" gradientUnits="userSpaceOnUse"><stop offset=".95" class="kdwv2rbxg"/><stop offset="1" class="g-9v2b8iu"/></radialGradient><radialGradient id="io5nlFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2503 4.43595 -.59456 -.03355 11.467 9.203)" gradientUnits="userSpaceOnUse"><stop class="dle7c82hk"/><stop offset="1" class="rp7ma24gd"/></radialGradient><radialGradient id="imNQJdc" cx="0" cy="0" r="1" gradientTransform="rotate(90.988 5.12 9.44)scale(2.4171)" gradientUnits="userSpaceOnUse"><stop class="twzrd6b1c"/><stop offset="1" class="devnblbfb"/></radialGradient><radialGradient id="iDiIR6f" cx="0" cy="0" r="1" gradientTransform="matrix(-.69914 4.6297 -.67506 -.10194 13.649 9.387)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="dle7c82hk"/><stop offset=".232" class="dle7c82hk"/><stop offset="1" class="rp7ma24gd"/></radialGradient><radialGradient id="iKyxtFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3759 1.44996 -1.08526 -.28136 16.578 6.214)" gradientUnits="userSpaceOnUse"><stop class="imarrnb8d"/><stop offset="1" class="i4-cjgbpi"/></radialGradient><radialGradient id="iTNPMic" cx="0" cy="0" r="1" gradientTransform="rotate(124.218 4.036 10.903)scale(3.56813 2.05017)" gradientUnits="userSpaceOnUse"><stop class="p_itlhbut"/><stop offset="1" class="snzfxsbzi"/></radialGradient><radialGradient id="iqzuyqT" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.4375 -2.66064 0 15.32 13.937)" gradientUnits="userSpaceOnUse"><stop class="s5530qsym"/><stop offset="1" class="bherg6shj"/></radialGradient><radialGradient id="iuuofoe" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 5.897 9.19)scale(2.84289 1.38778)" gradientUnits="userSpaceOnUse"><stop class="fwxucb51f"/><stop offset="1" class="pmgphlkow"/></radialGradient><radialGradient id="i9tSohc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 8 -4.8677 -2.28175 18.375 16.5)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="o0c8v-ibv"/><stop offset=".82" class="jy08abv0g"/></radialGradient><radialGradient id="izKNVAb" cx="0" cy="0" r="1" gradientTransform="rotate(115.769 5.298 12.337)scale(4.16637 3.02086)" gradientUnits="userSpaceOnUse"><stop class="ij70x3i2d"/><stop offset=".393" class="uoak8zblu"/><stop offset="1" class="weabqemkb"/></radialGradient><radialGradient id="isA5Ywd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.125 -2.75001 3.96162 -4.50181 18.062 21.125)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="mszj1mbis"/><stop offset="1" class="slk_cbm0c"/></radialGradient><radialGradient id="iIdGCHd" cx="0" cy="0" r="1" gradientTransform="matrix(2.8562 5.33265 -4.90861 2.62908 13.375 18.125)" gradientUnits="userSpaceOnUse"><stop class="guruu5bjb"/><stop offset="1" class="rc8f71m5a"/></radialGradient><radialGradient id="iJLZm1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71402 3.80039 -1.45013 -.65403 15.968 16.887)" gradientUnits="userSpaceOnUse"><stop class="j7frvrb4h"/><stop offset="1" class="las-2wb6w"/></radialGradient><radialGradient id="ik8ddti" cx="0" cy="0" r="1" gradientTransform="rotate(114.193 4.41 13.67)scale(8.99795 5.47492)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="yt4vnqb2q"/><stop offset=".907" class="easyj86_k"/></radialGradient><radialGradient id="iZtEj7w" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06177 0 0 -2.47144 19.936 21.562)" gradientUnits="userSpaceOnUse"><stop class="bm86kwbdk"/><stop offset="1" class="hzx_pibxs"/></radialGradient><radialGradient id="i6yzYKd" cx="0" cy="0" r="1" gradientTransform="rotate(147.212 5.531 14.62)scale(2.95308 2.71188)" gradientUnits="userSpaceOnUse"><stop class="qyhdwdvsp"/><stop offset="1" class="fku5ojbpz"/></radialGradient><radialGradient id="iqcBdGd" cx="0" cy="0" r="1" gradientTransform="rotate(142.892 5.86 14.371)scale(2.8478 2.6152)" gradientUnits="userSpaceOnUse"><stop class="duelji-8g"/><stop offset="1" class="xs104cbsx"/></radialGradient><radialGradient id="iUR2hhL" cx="0" cy="0" r="1" gradientTransform="matrix(2.60627 4.4161 -4.0554 2.3934 12.693 23.19)" gradientUnits="userSpaceOnUse"><stop class="h8doqu99b"/><stop offset="1" class="mla-37b5r"/></radialGradient><linearGradient id="irIJkub" x1="23.5" x2="22.988" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="iPtTk6c" x1="16.5" x2="19.625" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="ijyfssd" x1="32.55" x2="24.875" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iYOKwQO" x1="25.25" x2="23.437" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="ifzDnbe" x1="24.117" x2="23.274" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="ivs3xcc" x1="18.128" x2="16.017" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="tmnj_nbbn"/><stop offset=".525" class="nrj4mib6h"/><stop offset=".844" class="tpgn14bna"/><stop offset="1" class="zk_6ful_m"/></linearGradient><linearGradient id="i1C3jKc" x1="10.686" x2="12.763" y1="13.282" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".027" class="w3s7mab_t"/><stop offset=".159" class="gc-6hkbfu"/><stop offset=".479" class="uijcl4b2k"/><stop offset=".76" class="y45y4lb2l"/><stop offset="1" class="hpcczrb7p"/></linearGradient><linearGradient id="isRd5oc" x1="5.643" x2="8.04" y1="16.939" y2="16.87" gradientUnits="userSpaceOnUse"><stop class="i-sw-uobh"/><stop offset="1" class="mq8ibdcao"/></linearGradient><linearGradient id="i5JJeId" x1="6.443" x2="10.363" y1="11.856" y2="11.856" gradientUnits="userSpaceOnUse"><stop class="i8j1zcpue"/><stop offset=".109" class="wtcdkybph"/><stop offset=".333" class="ak7stn86d"/><stop offset=".521" class="sn2zkpfnc"/><stop offset=".661" class="snrtysb5g"/><stop offset=".712" class="y1n2ifkam"/></linearGradient><linearGradient id="iys2VVG" x1="7.125" x2="8.328" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".226" class="joq42sboe"/><stop offset=".572" class="i5qzygb_i"/></linearGradient><linearGradient id="iczgjNe" x1="9.07" x2="12.677" y1="10.091" y2="10.308" gradientUnits="userSpaceOnUse"><stop class="e1brbqbxg"/><stop offset=".109" class="zo-hfdcdg"/><stop offset=".291" class="n9ut6_bfd"/><stop offset=".385" class="tlrc_dthv"/><stop offset=".46" class="xppti3bbg"/><stop offset=".544" class="utno-6uzt"/><stop offset=".62" class="itwjdg74c"/></linearGradient><linearGradient id="irGtxgc" x1="9.478" x2="10.937" y1="11.166" y2="13.694" gradientUnits="userSpaceOnUse"><stop offset=".226" class="joq42sboe"/><stop offset=".572" class="i5qzygb_i"/></linearGradient><linearGradient id="iBp9Cwd" x1="11.529" x2="15.358" y1="9.002" y2="9.002" gradientUnits="userSpaceOnUse"><stop class="og5h_3b9x"/><stop offset=".188" class="xd4zpcbyb"/><stop offset=".359" class="orq_kgbmw"/></linearGradient><linearGradient id="ix0nGpM" x1="12.734" x2="11.065" y1="10.703" y2="13.759" gradientUnits="userSpaceOnUse"><stop offset=".226" class="joq42sboe"/><stop offset=".572" class="i5qzygb_i"/></linearGradient><linearGradient id="iEzzDKe" x1="13.514" x2="17.483" y1="9.649" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="iny3xttze"/><stop offset=".24" class="i0wfq-btk"/><stop offset=".542" class="n6wevhbtd"/><stop offset=".776" class="y134bvbit"/><stop offset="1" class="xjsjecgfp"/></linearGradient><linearGradient id="io1GRqd" x1="14.421" x2="12.31" y1="12.812" y2="14.989" gradientUnits="userSpaceOnUse"><stop offset=".226" class="nqchf4bsq"/><stop offset=".572" class="x_s37fcmt"/></linearGradient><linearGradient id="iBUzWWi" x1="18.805" x2="16.525" y1="11.277" y2="20.687" gradientUnits="userSpaceOnUse"><stop class="cx951t_jp"/><stop offset="1" class="hk7ii5w0a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-pushing-hand" /></template>
<style>
.a4mkhz4kt {
  stop-color: var(--svg-color--e57a67, #E57A67);
}

.aix_4gzkl {
  stop-color: var(--svg-color--e78150, #E78150);
}

.ajic0q7cm {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

.ak7stn86d {
  stop-color: var(--svg-color--f09430, #F09430);
}

.bh-87dbgb {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

.bherg6shj {
  stop-color: var(--svg-color--f0a13b, #F0A13B);
  stop-opacity: 0;
}

.bm86kwbdk {
  stop-color: var(--svg-color--fa9461, #FA9461);
}

.cur7ilbwx {
  d: path("M7.91 21.687c1.05 2.271 3.919 3.744 5.222 4.196c.56.18 2.16.195 4.087-1.184c2.408-1.723 1.134-4.65 1.067-4.96s-.31-.93-.343-1.113c-.033-.184.1-.954.285-1.44c.147-.388.63-1.311.853-1.724l-2.829-3.332l-9.772-.255c-.026 1.097-.063 3.58 0 4.74v.011c.078 1.442.121 2.229 1.43 5.06");
}

.cx951t_jp {
  stop-color: var(--svg-color--f7c22e, #F7C22E);
}

.der68rb5o {
  stop-color: var(--svg-color--e57a67, #E57A67);
  stop-opacity: 0;
}

.devnblbfb {
  stop-color: var(--svg-color--ffdd69, #FFDD69);
  stop-opacity: 0;
}

.dle7c82hk {
  stop-color: var(--svg-color--b93813, #B93813);
}

.duelji-8g {
  stop-color: var(--svg-color--fdc251, #FDC251);
}

.e_rci6btq {
  stop-color: var(--svg-color--dd9535, #DD9535);
}

.e1brbqbxg {
  stop-color: var(--svg-color--cf6918, #CF6918);
}

.e1zr_oxer {
  stop-color: var(--svg-color--e1934b, #E1934B);
  stop-opacity: 0;
}

.e7-f36zoo {
  d: path("M9.082 10.704c-.036 1.254-.216 2.174-.3 2.478c.965-.182 2.696-.41 2.587-2.715c.009-.483.072-1.822.109-2.45c.036-.63.137-2.46.255-3.39c-.255-.036-.692-.127-1.476.383c-.783.51-.829 1.34-.92 1.977c-.091.638-.21 2.15-.255 3.717");
}

.easyj86_k {
  stop-color: var(--svg-color--e78345, #E78345);
}

.eebf5ub9j {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

.epudzbdem {
  stop-color: var(--svg-color--e78150, #E78150);
  stop-opacity: 0;
}

.f6m366smq {
  fill: var(--svg-color--e2812a, #E2812A);
  d: path("M7.91 21.687c1.05 2.271 3.919 3.744 5.222 4.196c.56.18 2.16.195 4.087-1.184c2.408-1.723 1.134-4.65 1.067-4.96s-.31-.93-.343-1.113c-.033-.184.1-.954.285-1.44c.147-.388.63-1.311.853-1.724l-2.829-3.332l-9.772-.255c-.026 1.097-.063 3.58 0 4.74v.011c.078 1.442.121 2.229 1.43 5.06");
}

.fku5ojbpz {
  stop-color: var(--svg-color--ffba4d, #FFBA4D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwxucb51f {
  stop-color: var(--svg-color--b85227, #B85227);
}

.g-9v2b8iu {
  stop-color: var(--svg-color--e8b298, #E8B298);
}

.gc-6hkbfu {
  stop-color: var(--svg-color--e78528, #E78528);
}

.gj1jxdboc {
  stop-color: var(--svg-color--f99365, #F99365);
}

.gmmht-bmp {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0;
}

.guruu5bjb {
  stop-color: var(--svg-color--e98b33, #E98B33);
}

.gwwf19bus {
  stop-color: var(--svg-color--d69330, #D69330);
  stop-opacity: 0;
}

.h8doqu99b {
  stop-color: var(--svg-color--e97c64, #E97C64);
}

.hk7ii5w0a {
  stop-color: var(--svg-color--f7c22e, #F7C22E);
  stop-opacity: 0;
}

.hpcczrb7p {
  stop-color: var(--svg-color--e67775, #E67775);
}

.hsc9j6bft {
  d: path("m16.116 12.126l-9.636-.251c-.026 1.096-.063 3.58 0 4.739v.012c.078 1.441.121 2.228 1.43 5.06c1.05 2.272 3.919 3.745 5.222 4.197c.56.18 2.16.194 4.087-1.184c1.46-1.045 1.566-2.532 1.41-3.61a8 8 0 0 0-.024-.269c-.035-.328-.246-.94-.424-1.457c-.102-.297-.194-.563-.234-.723l-.005-.023c-.029-.197.104-.952.286-1.431c.147-.389.63-1.311.853-1.724l-.009-.01c.17-.314.362-.674.575-1.1c.764-1.527-.047-3.164-1.684-3.07c-.907.051-1.407.317-1.847.844");
}

.hzx_pibxs {
  stop-color: var(--svg-color--fa9461, #FA9461);
  stop-opacity: 0;
}

.i-lj0-gmv {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
  stop-opacity: 0;
}

.i-sw-uobh {
  stop-color: var(--svg-color--d4802f, #D4802F);
}

.i0wfq-btk {
  stop-color: var(--svg-color--ec9730, #EC9730);
}

.i4-cjgbpi {
  stop-color: var(--svg-color--ffea68, #FFEA68);
  stop-opacity: 0;
}

.i5qzygb_i {
  stop-color: var(--svg-color--e28a2f, #E28A2F);
}

.i6o-qu9fo {
  stop-color: var(--svg-color--852dbd, #852DBD);
}

.i8j1zcpue {
  stop-color: var(--svg-color--e1976b, #E1976B);
}

.igr1z4b_e {
  fill: var(--svg-color--e58932, #E58932);
  d: path("M14.992 13.928c-.818 1.407-1.593 2.09-1.878 2.256c-.088.051-1.862 2.456 1.212 5.877c1.669 1.469 4.692 2.669 4.279-1.241c-.055-.518-.548-1.744-.658-2.18c-.087-.35.11-1.03.219-1.325c.234-.764.717-1.435 1.48-2.962c.765-1.528-.046-3.165-1.683-3.072c-1.637.094-1.95.887-2.971 2.647");
}

.ihbs0wphk {
  stop-color: var(--svg-color--e2a789, #E2A789);
}

.ij70x3i2d {
  stop-color: var(--svg-color--ffea69, #FFEA69);
}

.imarrnb8d {
  stop-color: var(--svg-color--ffea68, #FFEA68);
}

.ink3gpbzz {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

.iny3xttze {
  stop-color: var(--svg-color--ce7b2b, #CE7B2B);
}

.itwjdg74c {
  stop-color: var(--svg-color--bc4620, #BC4620);
}

.j-f1eub7w {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

.j7frvrb4h {
  stop-color: var(--svg-color--f49854, #F49854);
}

.jjt_f1b4b {
  stop-color: var(--svg-color--e1802f, #E1802F);
}

.jn_5q-btc {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

.joq42sboe {
  stop-color: var(--svg-color--e28a2f, #E28A2F);
  stop-opacity: 0;
}

.jy08abv0g {
  stop-color: var(--svg-color--d6912c, #D6912C);
}

.k90wp6bmc {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

.kdwv2rbxg {
  stop-color: var(--svg-color--e8b298, #E8B298);
  stop-opacity: 0;
}

.kmjznhzms {
  stop-color: var(--svg-color--ea8497, #EA8497);
  stop-opacity: 0;
}

.las-2wb6w {
  stop-color: var(--svg-color--f49854, #F49854);
  stop-opacity: 0;
}

.lvxnl7_2g {
  stop-color: var(--svg-color--dd9535, #DD9535);
  stop-opacity: 0;
}

.m7gdckjal {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

.m9lg_cbcu {
  stop-color: var(--svg-color--ea872c, #EA872C);
}

.mla-37b5r {
  stop-color: var(--svg-color--e97c64, #E97C64);
  stop-opacity: 0;
}

.mq8ibdcao {
  stop-color: var(--svg-color--d4802f, #D4802F);
  stop-opacity: 0;
}

.mszj1mbis {
  stop-color: var(--svg-color--ffc744, #FFC744);
}

.n6wevhbtd {
  stop-color: var(--svg-color--ffc955, #FFC955);
}

.n9ut6_bfd {
  stop-color: var(--svg-color--f38e2f, #F38E2F);
}

.nqchf4bsq {
  stop-color: var(--svg-color--e3822a, #E3822A);
  stop-opacity: 0;
}

.nrj4mib6h {
  stop-color: var(--svg-color--ffbf47, #FFBF47);
}

.o_5n5wgtf {
  stop-color: var(--svg-color--ea8497, #EA8497);
}

.o-61vqaqh {
  d: path("m13.99 26.047l3.026-8.769c.059.216.94.29 1.373.3l13.598 2.352v11.553l-14.752-2.527c-2.322-.306-3.125-2.074-3.246-2.91");
}

.o0c8v-ibv {
  stop-color: var(--svg-color--d6912c, #D6912C);
  stop-opacity: 0;
}

.o2zxavsxe {
  d: path("M11.37 10.027c-.062 1.684-.267 1.689-.377 1.975c1.07 1.51 3.642.885 4.794.384V4.627c-.108-.717-.708-2.1-2.246-1.896c-1.923.256-1.88 2.214-1.958 3.316a165 165 0 0 0-.212 3.98");
}

.o83sobbar {
  d: path("M14.992 13.928c-.818 1.407-1.593 2.09-1.878 2.256c-.088.051-1.862 2.456 1.212 5.877c1.669 1.469 4.692 2.669 4.279-1.241c-.055-.518-.548-1.744-.658-2.18c-.087-.35.11-1.03.219-1.325c.234-.764.717-1.435 1.48-2.962c.765-1.528-.046-3.165-1.683-3.072c-1.637.094-1.95.887-2.971 2.647");
}

.odhggkl1x {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

.og5h_3b9x {
  stop-color: var(--svg-color--cf731f, #CF731F);
}

.orq_kgbmw {
  stop-color: var(--svg-color--e88c25, #E88C25);
}

.ovrqzubcx {
  d: path("m6.503 11.896l-.06 2.666c1.688-.203 2.602-1.26 2.602-2.744c.012-.255.046-.838.09-1.766c.036-.743.143-2.258.193-2.923c-.252-.083-.896-.175-1.455.123c-1.351.607-1.252 1.986-1.37 4.644");
}

.p_itlhbut {
  stop-color: var(--svg-color--e5872f, #E5872F);
}

.p3mtaj3rz {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.91 21.687c1.05 2.271 3.919 3.744 5.222 4.196c.56.18 2.16.195 4.087-1.184c2.408-1.723 1.134-4.65 1.067-4.96s-.31-.93-.343-1.113c-.033-.184.1-.954.285-1.44c.147-.388.63-1.311.853-1.724l-2.829-3.332l-9.772-.255c-.026 1.097-.063 3.58 0 4.74v.011c.078 1.442.121 2.229 1.43 5.06");
}

.pe70qdb4r {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

.pf1xml9sl {
  stop-color: var(--svg-color--852aab, #852AAB);
}

.pmgphlkow {
  stop-color: var(--svg-color--b85227, #B85227);
  stop-opacity: 0;
}

.qyhdwdvsp {
  stop-color: var(--svg-color--ffba4d, #FFBA4D);
}

.r5htkxbvz {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

.r5znjwblf {
  stop-color: var(--svg-color--f99365, #F99365);
  stop-opacity: 0;
}

.rc8f71m5a {
  stop-color: var(--svg-color--e98b33, #E98B33);
  stop-opacity: 0;
}

.rd54rdzck {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

.rp7ma24gd {
  stop-color: var(--svg-color--b93813, #B93813);
  stop-opacity: 0;
}

.s-b47gbty {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

.s5530qsym {
  stop-color: var(--svg-color--f0a13b, #F0A13B);
}

.slk_cbm0c {
  stop-color: var(--svg-color--ffc744, #FFC744);
  stop-opacity: 0;
}

.sn2zkpfnc {
  stop-color: var(--svg-color--f38d4a, #F38D4A);
}

.snrtysb5g {
  stop-color: var(--svg-color--ed763a, #ED763A);
}

.snzfxsbzi {
  stop-color: var(--svg-color--e5872f, #E5872F);
  stop-opacity: 0;
}

.tlrc_dthv {
  stop-color: var(--svg-color--f08e27, #F08E27);
}

.tmnj_nbbn {
  stop-color: var(--svg-color--fbc354, #FBC354);
}

.tpgn14bna {
  stop-color: var(--svg-color--ed8076, #ED8076);
}

.tul337ogz {
  stop-color: var(--svg-color--e1934b, #E1934B);
}

.twzrd6b1c {
  stop-color: var(--svg-color--ffde69, #FFDE69);
}

.u9094pbuo {
  stop-color: var(--svg-color--d69330, #D69330);
}

.uijcl4b2k {
  stop-color: var(--svg-color--e07f2c, #E07F2C);
}

.uoak8zblu {
  stop-color: var(--svg-color--fec836, #FEC836);
}

.urw491b2f {
  stop-color: var(--svg-color--e1802f, #E1802F);
  stop-opacity: 0;
}

.utno-6uzt {
  stop-color: var(--svg-color--e3722f, #E3722F);
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

.vvyrbnhyh {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

.vy67icc3g {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

.w3s7mab_t {
  stop-color: var(--svg-color--ed8827, #ED8827);
}

.weabqemkb {
  stop-color: var(--svg-color--fec836, #FEC836);
  stop-opacity: 0;
}

.wtcdkybph {
  stop-color: var(--svg-color--d9842d, #D9842D);
}

.wz0ektb2t {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

.x_s37fcmt {
  stop-color: var(--svg-color--e3822a, #E3822A);
}

.x1ob3cbbz {
  stop-color: var(--svg-color--e2a789, #E2A789);
  stop-opacity: 0;
}

.xd4zpcbyb {
  stop-color: var(--svg-color--d17c2b, #D17C2B);
}

.xjsjecgfp {
  stop-color: var(--svg-color--fbce61, #FBCE61);
}

.xppti3bbg {
  stop-color: var(--svg-color--ed822f, #ED822F);
}

.xs104cbsx {
  stop-color: var(--svg-color--fdc251, #FDC251);
  stop-opacity: 0;
}

.y134bvbit {
  stop-color: var(--svg-color--ffd944, #FFD944);
}

.y1n2ifkam {
  stop-color: var(--svg-color--c0421b, #C0421B);
}

.y45y4lb2l {
  stop-color: var(--svg-color--e17d48, #E17D48);
}

.y8ivzxb6k {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m13.99 26.047l3.026-8.769c.059.216.94.29 1.373.3l13.598 2.352v11.553l-14.752-2.527c-2.322-.306-3.125-2.074-3.246-2.91");
}

.yk1d-rbcz {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

.yt4vnqb2q {
  stop-color: var(--svg-color--e78345, #E78345);
  stop-opacity: 0;
}

.zeskxvswy {
  d: path("M13.404 10.228c-.217 1.955-.586 2.714-.744 2.85c.198 1.232.184 4.189.744 4.61c.965.726 2.704-1.725 3.446-2.077l.416-3.03c.203-1.629.627-5.024.699-5.574c.09-.687-.136-2.399-1.825-2.455S13.967 5.926 13.876 6.5l-.003.02c-.09.571-.202 1.292-.47 3.708");
}

.zk_6ful_m {
  stop-color: var(--svg-color--d56e81, #D56E81);
}

.zo-hfdcdg {
  stop-color: var(--svg-color--e08029, #E08029);
}

</style>
