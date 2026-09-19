<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y8ivzxb6k"/><path fill="url(#irIJkub)" class="o-61vqaqh"/><path fill="url(#iPtTk6c)" class="o-61vqaqh"/><path fill="url(#iClSPce)" class="o-61vqaqh"/><path fill="url(#ijyfssd)" class="o-61vqaqh"/><path fill="url(#iYOKwQO)" class="o-61vqaqh"/><path fill="url(#ivvWd2c)" class="o-61vqaqh"/><path fill="url(#iojVyDe)" class="o-61vqaqh"/><path fill="url(#inTB6oo)" class="o-61vqaqh"/><path fill="url(#iFNfN2b)" class="o-61vqaqh"/><path fill="url(#iMz3ZGc)" class="o-61vqaqh"/><path fill="url(#ifzDnbe)" class="o-61vqaqh"/><path fill="url(#iA39uxv)" class="vhv2grbps"/><path class="zmkj62npu"/><path fill="url(#ibIZG6c)" class="t_2bfpsnt"/><path fill="url(#icW27dq)" class="t_2bfpsnt"/><path fill="url(#iyE6pAb)" class="t_2bfpsnt"/><path fill="url(#iqhpfYd)" class="t_2bfpsnt"/><path fill="url(#ijP71Me)" class="t_2bfpsnt"/><path fill="url(#iafuBux)" class="t_2bfpsnt"/><path fill="url(#iovpIOd)" class="ovrqzubcx"/><path fill="url(#iT6JaJc)" class="ovrqzubcx"/><path fill="url(#iOFSX4b)" class="ovrqzubcx"/><path fill="url(#ipSfd6i)" class="ovrqzubcx"/><path fill="url(#i4dGUSc)" class="e7-f36zoo"/><path fill="url(#iPB0gfd)" class="e7-f36zoo"/><path fill="url(#i401yLe)" class="e7-f36zoo"/><path fill="url(#i45tV8d)" class="e7-f36zoo"/><path fill="url(#irbPsIk)" class="e7-f36zoo"/><path fill="url(#ioyd00h)" class="o2zxavsxe"/><path fill="url(#iMLl9Be)" class="o2zxavsxe"/><path fill="url(#iSppane)" class="o2zxavsxe"/><path fill="url(#iqs4e3b)" class="o2zxavsxe"/><path fill="url(#ilLdpJc)" class="o2zxavsxe"/><path fill="url(#iR6afSb)" class="zeskxvswy"/><path fill="url(#iwRg76c)" class="zeskxvswy"/><path fill="url(#i2s0U5N)" class="zeskxvswy"/><path fill="url(#ifrPpUd)" class="zeskxvswy"/><path fill="url(#iMoTg4d)" class="zeskxvswy"/><path fill="url(#ingyORn)" class="zeskxvswy"/><path class="xf52ejb-y"/><path fill="url(#icVVlhb)" class="o83sobbar"/><path fill="url(#ijHgeib)" class="o83sobbar"/><path fill="url(#ibQQ2zB)" class="o83sobbar"/><path fill="url(#i1aaH7c)" class="o83sobbar"/><path fill="url(#iYzEC2c)" class="o83sobbar"/><path fill="url(#i4rCpre)" class="o83sobbar"/><path fill="url(#iRfLcVb)" class="o83sobbar"/><path fill="url(#izHDDpd)" class="o83sobbar"/><path fill="url(#ihnZCIe)" class="y96mb_b6d"/><path fill="url(#i54ZuGY)" class="y96mb_b6d"/><path fill="url(#iU9gzVc)" class="y96mb_b6d"/><path fill="url(#i0d5eRc)" class="y96mb_b6d"/><defs><radialGradient id="iClSPce" cx="0" cy="0" r="1" gradientTransform="rotate(81.469 -3.443 20.66)scale(10.1119 24.3768)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="ivvWd2c" cx="0" cy="0" r="1" gradientTransform="matrix(.68764 6.50127 -6.0031 .63494 14.32 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="iojVyDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53853 7.97018 -6.15248 -.41571 14.9 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="inTB6oo" cx="0" cy="0" r="1" gradientTransform="rotate(147.095 12.777 12.887)scale(19.0802 24.1752)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="iFNfN2b" cx="0" cy="0" r="1" gradientTransform="matrix(7.822 5.35543 -6.78547 9.91068 15.167 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="iMz3ZGc" cx="0" cy="0" r="1" gradientTransform="rotate(161.642 15.253 12.985)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="ibIZG6c" cx="0" cy="0" r="1" gradientTransform="rotate(-138.262 12.229 10.024)scale(8.19524 7.34776)" gradientUnits="userSpaceOnUse"><stop class="mg63hybtc"/><stop offset="1" class="an7wrac-t"/></radialGradient><radialGradient id="iyE6pAb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.224 12.913 10.751)scale(8.31471 7.09704)" gradientUnits="userSpaceOnUse"><stop class="wqzn0vb7n"/><stop offset="1" class="o4xsy0b0l"/></radialGradient><radialGradient id="iqhpfYd" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 1.89063 -1.69511 .18212 7.484 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="db9rv6z2b"/><stop offset="1" class="ypyc5wbgk"/></radialGradient><radialGradient id="ijP71Me" cx="0" cy="0" r="1" gradientTransform="matrix(-.07017 1.9789 -1.77426 -.06291 9.43 12.287)" gradientUnits="userSpaceOnUse"><stop class="db9rv6z2b"/><stop offset=".501" class="db9rv6z2b"/><stop offset="1" class="ypyc5wbgk"/></radialGradient><radialGradient id="iafuBux" cx="0" cy="0" r="1" gradientTransform="rotate(56.915 -11.895 22.783)scale(4.92324 3.22008)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="e4yas3bkp"/><stop offset="1" class="jswibbcye"/></radialGradient><radialGradient id="iT6JaJc" cx="0" cy="0" r="1" gradientTransform="rotate(-99.139 11.643 4.219)scale(9.07953 6.02015)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="o6gt_ybjv"/><stop offset="1" class="rd0pze23q"/></radialGradient><radialGradient id="iOFSX4b" cx="0" cy="0" r="1" gradientTransform="rotate(93.604 -.668 9.797)scale(3.89053 .58167)" gradientUnits="userSpaceOnUse"><stop class="r-989q9jc"/><stop offset="1" class="x4-zrboyv"/></radialGradient><radialGradient id="iPB0gfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09735 -10.6667 6.36718 -.65503 11.733 15.264)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="nvd8embmm"/><stop offset="1" class="utu-fdlwf"/></radialGradient><radialGradient id="i401yLe" cx="0" cy="0" r="1" gradientTransform="rotate(-84.713 12.329 .618)scale(8.27578 3.00234)" gradientUnits="userSpaceOnUse"><stop offset=".95" class="jf44tqbyl"/><stop offset="1" class="jur4k2bfn"/></radialGradient><radialGradient id="i45tV8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.2503 4.43595 -.59456 -.03355 11.467 9.203)" gradientUnits="userSpaceOnUse"><stop class="q5601tbek"/><stop offset="1" class="k4xffvxuw"/></radialGradient><radialGradient id="iMLl9Be" cx="0" cy="0" r="1" gradientTransform="rotate(94.456 5.5 8.91)scale(2.09298)" gradientUnits="userSpaceOnUse"><stop class="h8ivm9ppt"/><stop offset="1" class="rg5e0mbyp"/></radialGradient><radialGradient id="iSppane" cx="0" cy="0" r="1" gradientTransform="matrix(-.46068 4.7966 -1.33392 -.12811 14.052 9.293)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="n1-445b5k"/><stop offset=".232" class="n1-445b5k"/><stop offset="1" class="w0ua42byy"/></radialGradient><radialGradient id="ilLdpJc" cx="0" cy="0" r="1" gradientTransform="matrix(.05462 7.9463 -4.4508 .0306 14.727 9.35)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="c5crsgbhk"/><stop offset=".944" class="r-okkxrnk"/></radialGradient><radialGradient id="iwRg76c" cx="0" cy="0" r="1" gradientTransform="matrix(-.3759 1.44996 -1.08526 -.28136 16.578 6.214)" gradientUnits="userSpaceOnUse"><stop class="gmm1vx3bh"/><stop offset="1" class="jo1hpgbfu"/></radialGradient><radialGradient id="i2s0U5N" cx="0" cy="0" r="1" gradientTransform="rotate(124.218 4.036 10.903)scale(3.56813 2.05017)" gradientUnits="userSpaceOnUse"><stop class="r4-7nqbxh"/><stop offset="1" class="i32ftmi7b"/></radialGradient><radialGradient id="iMoTg4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.4375 -2.66064 0 15.32 13.937)" gradientUnits="userSpaceOnUse"><stop class="t9bhfmbkw"/><stop offset="1" class="avgelqb-d"/></radialGradient><radialGradient id="ingyORn" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 5.897 9.19)scale(2.84289 1.38778)" gradientUnits="userSpaceOnUse"><stop class="wbn3_gbro"/><stop offset="1" class="tqo1qa7ii"/></radialGradient><radialGradient id="ijHgeib" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 8 -4.8677 -2.28175 18.375 16.5)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="f4fx21mzq"/><stop offset=".82" class="mdwjp8s0v"/></radialGradient><radialGradient id="ibQQ2zB" cx="0" cy="0" r="1" gradientTransform="rotate(115.769 5.298 12.337)scale(4.16637 3.02086)" gradientUnits="userSpaceOnUse"><stop class="j_ey73cfj"/><stop offset=".393" class="fginsybyx"/><stop offset="1" class="t5844lbnh"/></radialGradient><radialGradient id="i1aaH7c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.125 -2.75001 3.96162 -4.50181 18.062 21.125)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="lts_ivbgh"/><stop offset="1" class="qzdkjjbjx"/></radialGradient><radialGradient id="iYzEC2c" cx="0" cy="0" r="1" gradientTransform="matrix(2.8562 5.33265 -4.90861 2.62908 13.375 18.125)" gradientUnits="userSpaceOnUse"><stop class="m3tgfb3ra"/><stop offset="1" class="j1eroubtp"/></radialGradient><radialGradient id="i4rCpre" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71402 3.80039 -1.45013 -.65403 15.968 16.887)" gradientUnits="userSpaceOnUse"><stop class="fxkzh6btw"/><stop offset="1" class="g1fwqccip"/></radialGradient><radialGradient id="iRfLcVb" cx="0" cy="0" r="1" gradientTransform="rotate(114.193 4.41 13.67)scale(8.99795 5.47492)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="lvm9okbps"/><stop offset=".907" class="hm_dtj35n"/></radialGradient><radialGradient id="izHDDpd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06177 0 0 -2.47144 19.936 21.562)" gradientUnits="userSpaceOnUse"><stop class="d77bft2qq"/><stop offset="1" class="pvzthgbsa"/><stop offset="1" class="hzx_pibxs"/></radialGradient><radialGradient id="ihnZCIe" cx="0" cy="0" r="1" gradientTransform="rotate(147.212 5.531 14.62)scale(2.95308 2.71188)" gradientUnits="userSpaceOnUse"><stop class="rq3w1sb7m"/><stop offset="1" class="hski1lb-n"/></radialGradient><radialGradient id="i54ZuGY" cx="0" cy="0" r="1" gradientTransform="rotate(142.892 5.86 14.371)scale(2.8478 2.6152)" gradientUnits="userSpaceOnUse"><stop class="g4ji9vb4o"/><stop offset="1" class="a5rh5gdrv"/></radialGradient><radialGradient id="iU9gzVc" cx="0" cy="0" r="1" gradientTransform="matrix(2.60627 4.4161 -4.0554 2.3934 12.693 23.19)" gradientUnits="userSpaceOnUse"><stop class="mm7vv3bug"/><stop offset="1" class="wi4m25bid"/></radialGradient><radialGradient id="i0d5eRc" cx="0" cy="0" r="1" gradientTransform="rotate(61.132 -11.188 19.179)scale(4.51891 2.88818)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="bpr96qryy"/><stop offset="1" class="z81qkzxru"/></radialGradient><linearGradient id="irIJkub" x1="23.5" x2="22.988" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="iPtTk6c" x1="16.5" x2="19.625" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="ijyfssd" x1="32.55" x2="24.875" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iYOKwQO" x1="25.25" x2="23.437" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="ifzDnbe" x1="24.117" x2="23.274" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="iA39uxv" x1="18.128" x2="16.017" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="yhwgcqb1a"/><stop offset=".525" class="rq3w1sb7m"/><stop offset=".844" class="sqzzf85mh"/><stop offset="1" class="mjyhopb4o"/></linearGradient><linearGradient id="icW27dq" x1="5.644" x2="8.04" y1="16.939" y2="16.87" gradientUnits="userSpaceOnUse"><stop class="lm8707bep"/><stop offset="1" class="oxqq-ubgb"/></linearGradient><linearGradient id="iovpIOd" x1="6.443" x2="10.363" y1="11.856" y2="11.856" gradientUnits="userSpaceOnUse"><stop class="ziv6ydscq"/><stop offset=".109" class="t-qso0b2p"/><stop offset=".333" class="dg5bn1nef"/><stop offset=".521" class="ytu-sxmcu"/><stop offset=".661" class="i30bgv0_t"/><stop offset=".712" class="u_vzoqbyp"/></linearGradient><linearGradient id="ipSfd6i" x1="7.125" x2="8.328" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".226" class="c5crsgbhk"/><stop offset=".572" class="r-okkxrnk"/></linearGradient><linearGradient id="i4dGUSc" x1="9.07" x2="12.677" y1="10.091" y2="10.308" gradientUnits="userSpaceOnUse"><stop class="ga8r8lbgd"/><stop offset=".109" class="z816meb9s"/><stop offset=".291" class="cjyr43bnb"/><stop offset=".46" class="su7xxc_9w"/><stop offset=".571" class="ma9yo5b1o"/><stop offset=".743" class="qv0wulb9i"/></linearGradient><linearGradient id="irbPsIk" x1="9.478" x2="10.937" y1="11.166" y2="13.694" gradientUnits="userSpaceOnUse"><stop offset=".226" class="c5crsgbhk"/><stop offset=".572" class="r-okkxrnk"/></linearGradient><linearGradient id="ioyd00h" x1="11.529" x2="15.358" y1="9.002" y2="9.002" gradientUnits="userSpaceOnUse"><stop class="cdn8i9lli"/><stop offset=".255" class="mnl7ibc9p"/><stop offset=".552" class="hdsgirtov"/><stop offset=".73" class="hdsgirtov"/></linearGradient><linearGradient id="iqs4e3b" x1="12.734" x2="11.065" y1="10.703" y2="13.759" gradientUnits="userSpaceOnUse"><stop offset=".226" class="c5crsgbhk"/><stop offset=".495" class="r-okkxrnk"/></linearGradient><linearGradient id="iR6afSb" x1="13.514" x2="17.483" y1="9.649" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="npv6sxx2p"/><stop offset=".24" class="vian11bom"/><stop offset=".453" class="p6th51huv"/><stop offset=".721" class="afzmwccjq"/><stop offset="1" class="dit-rib8x"/></linearGradient><linearGradient id="ifrPpUd" x1="14.421" x2="12.31" y1="12.812" y2="14.989" gradientUnits="userSpaceOnUse"><stop offset=".226" class="c5crsgbhk"/><stop offset=".572" class="r-okkxrnk"/></linearGradient><linearGradient id="icVVlhb" x1="18.805" x2="16.525" y1="11.277" y2="20.687" gradientUnits="userSpaceOnUse"><stop class="l3v-g-bdw"/><stop offset="1" class="yy3hvv48w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-pushing-hand-medium-light" /></template>
<style>
.a5rh5gdrv {
  stop-color: var(--svg-color--e5b19a, #E5B19A);
  stop-opacity: 0;
}

.afzmwccjq {
  stop-color: var(--svg-color--eebd98, #EEBD98);
}

.ajic0q7cm {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

.an7wrac-t {
  stop-color: var(--svg-color--b16c8c, #B16C8C);
  stop-opacity: 0;
}

.avgelqb-d {
  stop-color: var(--svg-color--aa7763, #AA7763);
  stop-opacity: 0;
}

.bh-87dbgb {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

.bpr96qryy {
  stop-color: var(--svg-color--c28d7c, #C28D7C);
}

.c5crsgbhk {
  stop-color: var(--svg-color--c28d7b, #C28D7B);
  stop-opacity: 0;
}

.cdn8i9lli {
  stop-color: var(--svg-color--c8967d, #C8967D);
}

.cjyr43bnb {
  stop-color: var(--svg-color--b58572, #B58572);
}

.d77bft2qq {
  stop-color: var(--svg-color--edbba3, #EDBBA3);
}

.db9rv6z2b {
  stop-color: var(--svg-color--ca957e, #CA957E);
}

.dg5bn1nef {
  stop-color: var(--svg-color--c08c75, #C08C75);
}

.dit-rib8x {
  stop-color: var(--svg-color--edbe98, #EDBE98);
}

.e4yas3bkp {
  stop-color: var(--svg-color--bb827b, #BB827B);
}

.e7-f36zoo {
  d: path("M9.082 10.704c-.036 1.254-.216 2.174-.3 2.478c.965-.182 2.696-.41 2.587-2.715c.009-.483.072-1.822.109-2.45c.036-.63.137-2.46.255-3.39c-.255-.036-.692-.127-1.476.383c-.783.51-.829 1.34-.92 1.977c-.091.638-.21 2.15-.255 3.717");
}

.eebf5ub9j {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

.f4fx21mzq {
  stop-color: var(--svg-color--be877c, #BE877C);
  stop-opacity: 0;
}

.fginsybyx {
  stop-color: var(--svg-color--e5b594, #E5B594);
}

.ft5dv1b6b {
  fill: none;
}

.fxkzh6btw {
  stop-color: var(--svg-color--c78c8a, #C78C8A);
}

.g1fwqccip {
  stop-color: var(--svg-color--c78c8a, #C78C8A);
  stop-opacity: 0;
}

.g4ji9vb4o {
  stop-color: var(--svg-color--e5b19a, #E5B19A);
}

.ga8r8lbgd {
  stop-color: var(--svg-color--af7d63, #AF7D63);
}

.gmm1vx3bh {
  stop-color: var(--svg-color--f2c3a4, #F2C3A4);
}

.gmmht-bmp {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0;
}

.h8ivm9ppt {
  stop-color: var(--svg-color--f3caa4, #F3CAA4);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hm_dtj35n {
  stop-color: var(--svg-color--bb817b, #BB817B);
}

.hski1lb-n {
  stop-color: var(--svg-color--e7b19c, #E7B19C);
  stop-opacity: 0;
}

.hzx_pibxs {
  stop-color: var(--svg-color--fa9461, #FA9461);
  stop-opacity: 0;
}

.i-lj0-gmv {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
  stop-opacity: 0;
}

.i30bgv0_t {
  stop-color: var(--svg-color--a37062, #A37062);
}

.i32ftmi7b {
  stop-color: var(--svg-color--ad7863, #AD7863);
  stop-opacity: 0;
}

.i6o-qu9fo {
  stop-color: var(--svg-color--852dbd, #852DBD);
}

.ink3gpbzz {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

.j_ey73cfj {
  stop-color: var(--svg-color--f9cba9, #F9CBA9);
}

.j-f1eub7w {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

.j1eroubtp {
  stop-color: var(--svg-color--bb8579, #BB8579);
  stop-opacity: 0;
}

.jf44tqbyl {
  stop-color: var(--svg-color--b88f71, #B88F71);
  stop-opacity: 0;
}

.jn_5q-btc {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

.jo1hpgbfu {
  stop-color: var(--svg-color--f2c3a4, #F2C3A4);
  stop-opacity: 0;
}

.jswibbcye {
  stop-color: var(--svg-color--bb827b, #BB827B);
  stop-opacity: 0;
}

.jur4k2bfn {
  stop-color: var(--svg-color--b88f71, #B88F71);
}

.k4xffvxuw {
  stop-color: var(--svg-color--8d5342, #8D5342);
  stop-opacity: 0;
}

.k90wp6bmc {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

.l3v-g-bdw {
  stop-color: var(--svg-color--dcaf8a, #DCAF8A);
}

.lm8707bep {
  stop-color: var(--svg-color--d79d85, #D79D85);
}

.lts_ivbgh {
  stop-color: var(--svg-color--eeb99f, #EEB99F);
}

.lvm9okbps {
  stop-color: var(--svg-color--bb817b, #BB817B);
  stop-opacity: 0;
}

.m3tgfb3ra {
  stop-color: var(--svg-color--bb8579, #BB8579);
}

.m7gdckjal {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

.ma9yo5b1o {
  stop-color: var(--svg-color--a26f60, #A26F60);
}

.mdwjp8s0v {
  stop-color: var(--svg-color--be877c, #BE877C);
}

.mg63hybtc {
  stop-color: var(--svg-color--b16c8c, #B16C8C);
}

.mjyhopb4o {
  stop-color: var(--svg-color--ac6786, #AC6786);
}

.mm7vv3bug {
  stop-color: var(--svg-color--b47085, #B47085);
}

.mnl7ibc9p {
  stop-color: var(--svg-color--b78772, #B78772);
}

.n1-445b5k {
  stop-color: var(--svg-color--915847, #915847);
}

.npv6sxx2p {
  stop-color: var(--svg-color--ca967c, #CA967C);
}

.nvd8embmm {
  stop-color: var(--svg-color--b68e71, #B68E71);
  stop-opacity: 0;
}

.o-61vqaqh {
  d: path("m13.99 26.047l3.026-8.769c.059.216.94.29 1.373.3l13.598 2.352v11.553l-14.752-2.527c-2.322-.306-3.125-2.074-3.246-2.91");
}

.o2zxavsxe {
  d: path("M11.37 10.027c-.062 1.684-.267 1.689-.377 1.975c1.07 1.51 3.642.885 4.794.384V4.627c-.108-.717-.708-2.1-2.246-1.896c-1.923.256-1.88 2.214-1.958 3.316a165 165 0 0 0-.212 3.98");
}

.o4xsy0b0l {
  stop-color: var(--svg-color--b36f89, #B36F89);
  stop-opacity: 0;
}

.o6gt_ybjv {
  stop-color: var(--svg-color--b4896c, #B4896C);
  stop-opacity: 0;
}

.o83sobbar {
  d: path("M14.992 13.928c-.818 1.407-1.593 2.09-1.878 2.256c-.088.051-1.862 2.456 1.212 5.877c1.669 1.469 4.692 2.669 4.279-1.241c-.055-.518-.548-1.744-.658-2.18c-.087-.35.11-1.03.219-1.325c.234-.764.717-1.435 1.48-2.962c.765-1.528-.046-3.165-1.683-3.072c-1.637.094-1.95.887-2.971 2.647");
}

.odhggkl1x {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

.ovrqzubcx {
  d: path("m6.503 11.896l-.06 2.666c1.688-.203 2.602-1.26 2.602-2.744c.012-.255.046-.838.09-1.766c.036-.743.143-2.258.193-2.923c-.252-.083-.896-.175-1.455.123c-1.351.607-1.252 1.986-1.37 4.644");
}

.oxqq-ubgb {
  stop-color: var(--svg-color--d79d85, #D79D85);
  stop-opacity: 0;
}

.p6th51huv {
  stop-color: var(--svg-color--d29f85, #D29F85);
}

.pe70qdb4r {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

.pf1xml9sl {
  stop-color: var(--svg-color--852aab, #852AAB);
}

.pvzthgbsa {
  stop-color: var(--svg-color--edbba3, #EDBBA3);
  stop-opacity: 0;
}

.q5601tbek {
  stop-color: var(--svg-color--8d5342, #8D5342);
}

.qv0wulb9i {
  stop-color: var(--svg-color--8f5645, #8F5645);
}

.qzdkjjbjx {
  stop-color: var(--svg-color--eeb99f, #EEB99F);
  stop-opacity: 0;
}

.r-989q9jc {
  stop-color: var(--svg-color--8b503e, #8B503E);
}

.r-okkxrnk {
  stop-color: var(--svg-color--c28d7b, #C28D7B);
}

.r4-7nqbxh {
  stop-color: var(--svg-color--ad7863, #AD7863);
}

.r5htkxbvz {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

.rd0pze23q {
  stop-color: var(--svg-color--b4896c, #B4896C);
}

.rd54rdzck {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

.rg5e0mbyp {
  stop-color: var(--svg-color--f3caa4, #F3CAA4);
  stop-opacity: 0;
}

.rq3w1sb7m {
  stop-color: var(--svg-color--e7b19c, #E7B19C);
}

.s-b47gbty {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

.sqzzf85mh {
  stop-color: var(--svg-color--b37086, #B37086);
}

.su7xxc_9w {
  stop-color: var(--svg-color--a67464, #A67464);
}

.t_2bfpsnt {
  d: path("M7.91 21.687c1.05 2.271 3.919 3.744 5.222 4.196c.56.18 2.161.195 4.087-1.184c2.408-1.723 1.135-4.65 1.068-4.96s-.31-.93-.343-1.114s.1-.954.284-1.439c.144-.38.625-1.27.855-1.694l.014-.027l-2.844-3.336l-4.816-.754l-4.925.504c-.026 1.097-.137 3.453-.032 4.735c.12 1.447.118 2.233 1.43 5.072");
}

.t-qso0b2p {
  stop-color: var(--svg-color--d69f84, #D69F84);
}

.t5844lbnh {
  stop-color: var(--svg-color--e5b594, #E5B594);
  stop-opacity: 0;
}

.t9bhfmbkw {
  stop-color: var(--svg-color--aa7763, #AA7763);
}

.tqo1qa7ii {
  stop-color: var(--svg-color--925945, #925945);
  stop-opacity: 0;
}

.u_vzoqbyp {
  stop-color: var(--svg-color--8c513f, #8C513F);
}

.utu-fdlwf {
  stop-color: var(--svg-color--b68e71, #B68E71);
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

.vian11bom {
  stop-color: var(--svg-color--c08d76, #C08D76);
}

.vvyrbnhyh {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

.vy67icc3g {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

.w0ua42byy {
  stop-color: var(--svg-color--915847, #915847);
  stop-opacity: 0;
}

.wbn3_gbro {
  stop-color: var(--svg-color--925945, #925945);
}

.wi4m25bid {
  stop-color: var(--svg-color--b47085, #B47085);
  stop-opacity: 0;
}

.wqzn0vb7n {
  stop-color: var(--svg-color--b36f89, #B36F89);
}

.wz0ektb2t {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

.x4-zrboyv {
  stop-color: var(--svg-color--8b503e, #8B503E);
  stop-opacity: 0;
}

.xf52ejb-y {
  fill: var(--svg-color--c18784, #C18784);
  d: path("M14.992 13.928c-.818 1.407-1.593 2.09-1.878 2.256c-.088.051-1.862 2.456 1.212 5.877c1.669 1.469 4.692 2.669 4.279-1.241c-.055-.518-.548-1.744-.658-2.18c-.087-.35.11-1.03.219-1.325c.234-.764.717-1.435 1.48-2.962c.765-1.528-.046-3.165-1.683-3.072c-1.637.094-1.95.887-2.971 2.647");
}

.y8ivzxb6k {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m13.99 26.047l3.026-8.769c.059.216.94.29 1.373.3l13.598 2.352v11.553l-14.752-2.527c-2.322-.306-3.125-2.074-3.246-2.91");
}

.y96mb_b6d {
  d: path("m16.116 12.126l-9.636-.251c-.026 1.096-.063 3.58 0 4.739v.012c.078 1.441.121 2.228 1.43 5.06c1.05 2.272 3.919 3.745 5.222 4.197c.56.18 2.16.194 4.087-1.184c1.46-1.045 1.566-2.532 1.41-3.61a8 8 0 0 0-.024-.269c-.035-.328-.246-.94-.424-1.457c-.102-.297-.194-.563-.234-.723l-.005-.023c-.029-.197.104-.952.286-1.431c.147-.389.583-1.187.807-1.6l.082-.172c.17-.313.317-.636.53-1.061c.764-1.528-.047-3.165-1.684-3.072c-.907.052-1.407.318-1.847.845");
}

.yhwgcqb1a {
  stop-color: var(--svg-color--e4b098, #E4B098);
}

.yk1d-rbcz {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

.ypyc5wbgk {
  stop-color: var(--svg-color--ca957e, #CA957E);
  stop-opacity: 0;
}

.ytu-sxmcu {
  stop-color: var(--svg-color--b48372, #B48372);
}

.yy3hvv48w {
  stop-color: var(--svg-color--dcaf8a, #DCAF8A);
  stop-opacity: 0;
}

.z816meb9s {
  stop-color: var(--svg-color--c08f77, #C08F77);
}

.z81qkzxru {
  stop-color: var(--svg-color--c28d7c, #C28D7C);
  stop-opacity: 0;
}

.zeskxvswy {
  d: path("M13.404 10.228c-.217 1.955-.586 2.714-.744 2.85c.198 1.232.184 4.189.744 4.61c.965.726 2.704-1.725 3.446-2.077l.416-3.03c.203-1.629.627-5.024.699-5.574c.09-.687-.136-2.399-1.825-2.455S13.967 5.926 13.876 6.5l-.003.02c-.09.571-.202 1.292-.47 3.708");
}

.ziv6ydscq {
  stop-color: var(--svg-color--d6a084, #D6A084);
}

.zmkj62npu {
  fill: var(--svg-color--c28d7b, #C28D7B);
  d: path("M7.91 21.687c1.05 2.271 3.919 3.744 5.222 4.196c.56.18 2.161.195 4.087-1.184c2.408-1.723 1.135-4.65 1.068-4.96s-.31-.93-.343-1.114s.1-.954.284-1.439c.144-.38.625-1.27.855-1.694l.014-.027l-2.844-3.336l-4.816-.754l-4.925.504c-.026 1.097-.137 3.453-.032 4.735c.12 1.447.118 2.233 1.43 5.072");
}

</style>
