<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hg_xi5byk"/><path fill="url(#iUk42Kc)" class="mcm2epbwi"/><path fill="url(#itbtQzd)" class="mcm2epbwi"/><path fill="url(#iZmm8Xd)" class="mcm2epbwi"/><path fill="url(#ik6YnHb)" class="mcm2epbwi"/><path fill="url(#idva0Yd)" class="mcm2epbwi"/><path class="fxlu258xo"/><path fill="url(#imSQI2c)" class="n-6fznoqh"/><path fill="url(#i4d8iJd)" class="n-6fznoqh"/><path fill="url(#iHdaBGb)" class="n-6fznoqh"/><g filter="url(#igU51md)"><path class="ejbroxbcy"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#izXeBwc)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#i5v4GXd)" class="by194g1ei"/><path fill="url(#i43VwXd)" class="by194g1ei"/><g filter="url(#imfG7Id)"><path fill="url(#iRjyRMt)" class="zgu_--bpo"/></g><path fill="url(#iollnke)" class="jy4e3rjsw"/><path fill="url(#iOnL5De)" class="jy4e3rjsw"/><path fill="url(#i4hNkDe)" class="jy4e3rjsw"/><path fill="url(#i9bX55c)" class="h1og-2beh"/><path fill="url(#iMIg2ZO)" class="h1og-2beh"/><path fill="url(#i9Nz6Jl)" class="h1og-2beh"/><path fill="url(#i816X5R)" class="h1og-2beh"/><path fill="url(#iIipaHv)" class="h1og-2beh"/><path class="uk92h5tcg"/><path fill="url(#iLnu67h)" class="k76jtjjwr"/><path fill="url(#idlpVJd)" class="k76jtjjwr"/><path fill="url(#imdlgvc)" class="k76jtjjwr"/><path fill="url(#ira2lKd)" class="k76jtjjwr"/><path fill="url(#iB1w8Ed)" class="k76jtjjwr"/><g filter="url(#iCwcndc)"><path fill="url(#iwvUxte)" class="aj2eo5xfs"/><path fill="url(#ibkEcTd)" class="aj2eo5xfs"/></g><g filter="url(#iQaj5Db)"><path fill="url(#i9VYgXa)" class="e331fpbtp"/><path fill="url(#iVY5Ecc)" class="e331fpbtp"/><path fill="url(#iLW0nln)" class="e331fpbtp"/><path fill="url(#imEendb)" class="e331fpbtp"/><path fill="url(#irOFmTd)" class="e331fpbtp"/></g><g filter="url(#ixrluZj)"><path fill="url(#iSfw5wd)" class="yyc71qb6t"/><path fill="url(#iiIvpQb)" class="yyc71qb6t"/><path fill="url(#isUiL6c)" class="yyc71qb6t"/><path fill="url(#iPij2KA)" class="yyc71qb6t"/></g><path fill="url(#iM1R3Fc)" class="qtigmmeii"/><path fill="url(#iV7gwWd)" class="qtigmmeii"/><rect fill="url(#iGFxt3d)" class="o9e08qbdu"/><rect fill="url(#iCZvVXc)" class="o9e08qbdu"/><rect fill="url(#iT0Szpc)" class="o9e08qbdu"/><rect fill="url(#iNyUeyU)" class="o9e08qbdu"/><g filter="url(#iOKfhNb)"><circle class="bzlygpkrz"/></g><circle fill="url(#iU1hsCv)" class="c8av-0bva"/><circle fill="url(#i5Fhu0c)" class="c8av-0bva"/><g filter="url(#ieM6Lic)"><path fill="url(#irI5LDd)" clip-rule="evenodd" class="pkewzbb7b"/></g><rect fill="url(#is19MEd)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#ifDN5ie)"><path fill="url(#iu7H9kd)" class="kyv7jrdlq"/><path fill="url(#i262erJ)" class="kyv7jrdlq"/><path fill="url(#iouU5Pe)" class="kyv7jrdlq"/><path fill="url(#iBAG5rd)" class="kyv7jrdlq"/><path fill="url(#io15mxc)" class="kyv7jrdlq"/></g><g filter="url(#iUZlfxc)"><path stroke="url(#i93SocJ)" class="fkavrburz"/></g><g filter="url(#iJTRsgd)"><path stroke="url(#iCU2nPr)" class="wsj2g07-c"/></g><g filter="url(#iArPUSd)"><path stroke="url(#iigSvwc)" class="bc7i0ongh"/></g><path fill="url(#iLYfJVd)" class="x62u6rbbl"/><path fill="url(#iuecaJe)" class="pwmv9bc_x"/><path fill="url(#iPzDYxc)" class="pwmv9bc_x"/><path fill="url(#iLWqBkc)" class="pwmv9bc_x"/><g filter="url(#iXxDrwc)"><path fill="url(#iUg0IUd)" class="r99x7jora"/></g><path fill="url(#iVWmkOX)" class="r99x7jora"/><path fill="url(#if36nWc)" class="r99x7jora"/><path fill="url(#imN4G3l)" class="r99x7jora"/><path fill="url(#iED2nOc)" class="r99x7jora"/><path fill="url(#iWx9d7d)" class="r99x7jora"/><path fill="url(#iPsYWvd)" class="r99x7jora"/><path fill="url(#inhHgDe)" class="r99x7jora"/><path fill="url(#isyE6Eb)" class="r99x7jora"/><path fill="url(#iwIH3lb)" class="r99x7jora"/><g filter="url(#iCCKuRb)"><path class="lolqknbkr"/></g><g filter="url(#iZmnQOc)"><path class="d_0d9e8wo"/><path fill="url(#icH6eBe)" class="it1ywpbon"/><path fill="url(#i8zTw6Q)" class="it1ywpbon"/><path fill="url(#ie0TaRd)" class="it1ywpbon"/></g><g filter="url(#imbQYac)"><path fill="url(#iCV2dze)" class="sfn3j3blb"/></g><g filter="url(#iETVbId)"><path stroke="url(#itgJtMc)" class="qq_ijsbpi"/></g><path fill="url(#iwcfvod)" class="tjixy4bap"/><path class="xvd1hdcxc"/><path fill="url(#iWphBzY)" class="to1bhjtdn"/><path class="y_rt2lgnd"/><g filter="url(#iJKN3zl)"><path class="ws_t7ubqt"/><path fill="url(#iHFFgfe)" class="up282p8sz"/></g><g filter="url(#iA3MOyd)"><path fill="url(#iG4joAb)" class="ygg62-bdc"/></g><path class="kmvantawu"/><path fill="url(#ixpftVd)" class="ab5krjbng"/><path class="bdm6_2brf"/><g filter="url(#itpZoRd)"><path fill="url(#iLjdYkc)" class="yjhtlsg3j"/></g><g filter="url(#ieHVxFd)"><ellipse transform="rotate(-27.914 12.114 12.082)" class="ctmxvjb_b"/><ellipse fill="url(#iSBIuQd)" transform="rotate(-27.914 12.114 12.082)" class="fd42wabnp"/></g><path fill="url(#i4FfAKc)" class="a9cgrmb3b"/><path fill="url(#ibEW7cc)" class="a9cgrmb3b"/><path fill="url(#ihXb90d)" class="a9cgrmb3b"/><path fill="url(#i5p6Zkt)" class="pahb5ac_e"/><path fill="url(#i8fmy9b)" class="pahb5ac_e"/><g filter="url(#iVe90wb)"><path class="t5tjx-buh"/></g><g filter="url(#iF9OaYc)"><path class="we2_cetne"/></g><path fill="url(#iBfj5Pd)" class="raaicexie"/><path fill="url(#ieAjMmb)" class="raaicexie"/><g filter="url(#iSjKLPe)"><path fill="url(#iodu1md)" class="e8-mlobfh"/></g><path fill="url(#iQFwsnd)" class="mwv4fzbkx"/><path fill="url(#iuO87Jd)" class="mwv4fzbkx"/><path fill="url(#iUaN9Xb)" class="mwv4fzbkx"/><path fill="url(#iD4Nv7d)" class="mwv4fzbkx"/><g filter="url(#iwuuAkr)"><path fill="url(#i8gh6Fe)" class="raaicexie"/></g><defs><radialGradient id="iUk42Kc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.812)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="ik6YnHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.835 22.156)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="idva0Yd" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.415 66.252)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="i4d8iJd" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .523 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iHdaBGb" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.884)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="izXeBwc" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.544 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="i5v4GXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.468)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="i43VwXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iRjyRMt" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.654)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iollnke" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.781)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i9bX55c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.968)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="i9Nz6Jl" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.195 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="i816X5R" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.128)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iIipaHv" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.05 20.861)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iLnu67h" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.468)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="imdlgvc" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.371 20.582)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iB1w8Ed" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.701 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iwvUxte" cx="0" cy="0" r="1" gradientTransform="rotate(158.46 6.492 11.807)scale(2.80546 2.9114)" gradientUnits="userSpaceOnUse"><stop class="fcv3pabxt"/><stop offset="1" class="ehjxjubwn"/></radialGradient><radialGradient id="ibkEcTd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5045 .1671 -.03048 -.45688 14.29 19.958)" gradientUnits="userSpaceOnUse"><stop class="z-xw_ccte"/><stop offset="1" class="z5z3i6nzk"/></radialGradient><radialGradient id="iLW0nln" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.282)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="irOFmTd" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.253)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iPij2KA" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.982)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="iM1R3Fc" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.76 15.925)scale(2.55551 2.50931)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="j1n1ygxtd"/><stop offset="1" class="mdv9qbyfi"/></radialGradient><radialGradient id="iV7gwWd" cx="0" cy="0" r="1" gradientTransform="matrix(.8321 -.63357 .48552 .63766 28.001 22.853)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="jt362mrmb"/><stop offset="1" class="yfkzyxbts"/></radialGradient><radialGradient id="iT0Szpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.226)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iNyUeyU" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.265)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="is19MEd" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.118)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="i262erJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iouU5Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iBAG5rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="io15mxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iLYfJVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67981 3.94319 -4.6842 -.80756 20.941 14.077)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a5dpq-jqr"/><stop offset="1" class="kmubh8kzn"/></radialGradient><radialGradient id="iuecaJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.42117 2.99194 -1.35997 .64598 8.662 14.392)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iPzDYxc" cx="0" cy="0" r="1" gradientTransform="matrix(.20003 1.33166 -1.16814 .17547 9.556 14.164)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iLWqBkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.84041 2.83962 -1.56607 1.015 8.243 14.545)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="keuf9wi3y"/><stop offset="1" class="rp3a36fum"/></radialGradient><radialGradient id="iUg0IUd" cx="0" cy="0" r="1" gradientTransform="rotate(164.923 8.118 7.796)scale(6.00513 8.31341)" gradientUnits="userSpaceOnUse"><stop class="odixm9bgr"/><stop offset="1" class="b98_s-60t"/></radialGradient><radialGradient id="if36nWc" cx="0" cy="0" r="1" gradientTransform="scale(11.2725 13.6121)rotate(90 .437 .94)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="m-p9sabje"/><stop offset="1" class="phcdw6ach"/></radialGradient><radialGradient id="imN4G3l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.49597 1.85126 0 17.581 11.961)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iED2nOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06477 -1.231 1.33962 -.07049 12.354 11.809)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iWx9d7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.34637 0 0 6.8433 9.406 13.64)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iPsYWvd" cx="0" cy="0" r="1" gradientTransform="matrix(2.91713 -4.0765 .92333 .66073 8.322 9.863)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="inhHgDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6927 -11.42744 12.58766 -2.96609 14.68 17.754)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="isyE6Eb" cx="0" cy="0" r="1" gradientTransform="matrix(2.28136 .80407 -.48235 1.36857 17.035 7.208)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iwIH3lb" cx="0" cy="0" r="1" gradientTransform="rotate(85.755 1.552 13.195)scale(4.15758 7.57699)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="y431-xmsp"/><stop offset="1" class="r-9djmxfd"/></radialGradient><radialGradient id="ie0TaRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57813 0 0 -.3252 15.344 14.716)" gradientUnits="userSpaceOnUse"><stop class="lah1ls-tj"/><stop offset="1" class="ruqf-bc5u"/></radialGradient><radialGradient id="itgJtMc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 21.203 -3.16)scale(.79221 2.30536)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iwcfvod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.80408 3.23503 0 14.851 17.16)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iWphBzY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90514 -1.43973 0 17.286 12.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="iHFFgfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.25874 -.33342 .45904 -.35622 17.031 12.283)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixpftVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90519 -1.4398 0 12.417 12.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="iSBIuQd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.17 .262)scale(.55129 .66267)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibEW7cc" cx="0" cy="0" r="1" gradientTransform="matrix(.70123 2.50269 -2.38775 .66903 20.003 12.204)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ihXb90d" cx="0" cy="0" r="1" gradientTransform="matrix(.87888 -1.20612 1.01097 .73668 20.405 12.812)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i8fmy9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86871 -.27328 .26866 -1.83712 9.367 12.922)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iQFwsnd" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.609)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><linearGradient id="iZmm8Xd" x1="6.988" x2="7.195" y1="29.406" y2="29.406" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="imSQI2c" x1="16.932" x2="14.847" y1="28.545" y2="28.119" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="iOnL5De" x1="13.726" x2="14.226" y1="26.765" y2="26.812" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="i4hNkDe" x1="16.414" x2="15.153" y1="29.069" y2="29.122" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="iMIg2ZO" x1="11.675" x2="12.612" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="idlpVJd" x1="18.074" x2="17.138" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="i9VYgXa" x1="12.219" x2="9.392" y1="26.169" y2="26.806" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iVY5Ecc" x1="9.392" x2="11.086" y1="16.976" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="imEendb" x1="12.268" x2="12.268" y1="29.922" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="iSfw5wd" x1="18.023" x2="21.304" y1="29.125" y2="16.976" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iiIvpQb" x1="17" x2="17.152" y1="26.539" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iGFxt3d" x1="26.981" x2="24.992" y1="21.781" y2="21.781" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iCZvVXc" x1="26.336" x2="26.336" y1="25.468" y2="22.562" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="irI5LDd" x1="28.179" x2="23.367" y1="14.344" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="iu7H9kd" x1="27.914" x2="23.547" y1="27.807" y2="27.891" gradientUnits="userSpaceOnUse"><stop offset=".146" class="yrzi8mt9l"/><stop offset="1" class="rncji_bbq"/></linearGradient><linearGradient id="i93SocJ" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iCU2nPr" x1="23.614" x2="25.48" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iigSvwc" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iVWmkOX" x1="20.605" x2="15.749" y1="15.092" y2="15.092" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="icH6eBe" x1="15.898" x2="15.055" y1="14.482" y2="14.638" gradientUnits="userSpaceOnUse"><stop class="wtk4a52ny"/><stop offset="1" class="qofkq9kdy"/></linearGradient><linearGradient id="i8zTw6Q" x1="14.851" x2="14.851" y1="14.58" y2="15.531" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iCV2dze" x1="14.851" x2="14.851" y1="11.857" y2="13.475" gradientUnits="userSpaceOnUse"><stop offset=".198" class="zwjanzbmf"/><stop offset="1" class="zochtpbty"/></linearGradient><linearGradient id="iG4joAb" x1="18.154" x2="17.803" y1="12.249" y2="12.464" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLjdYkc" x1="13.247" x2="12.897" y1="12.249" y2="12.465" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4FfAKc" x1="22.032" x2="20.686" y1="12.279" y2="14.707" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="i5p6Zkt" x1="8.325" x2="9.952" y1="13.065" y2="12.922" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iuO87Jd" x1="8.554" x2="9.992" y1="6.877" y2="7.062" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iUaN9Xb" x1="15.461" x2="15.461" y1="7.929" y2="7.726" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iD4Nv7d" x1="15.507" x2="15.507" y1="5.847" y2="5.984" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="igU51md" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".25"/></filter><filter id="imfG7Id" width="3.106" height="2.966" x="13.406" y="21.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter><filter id="iCwcndc" width="4.5" height="2.352" x="12.625" y="19.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.513726 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter><filter id="iQaj5Db" width="8.299" height="13.046" x="5.292" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter><filter id="ixrluZj" width="8.299" height="13.046" x="16.153" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter><filter id="iOKfhNb" width="6.656" height="6.656" x="22.367" y="13.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".125"/></filter><filter id="ieM6Lic" width="7.206" height="7.206" x="22.067" y="13.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter><filter id="ifDN5ie" width="5.277" height="6.052" x="23.132" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.486275 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter><filter id="iUZlfxc" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iJTRsgd" width="2.262" height=".3" x="23.464" y="26.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iArPUSd" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iXxDrwc" width="12.152" height="13.969" x="9.203" y="6.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2759" result="effect2_innerShadow_4002_2759"/></filter><filter id="iCCKuRb" width="3.957" height="5.15" x="12.573" y="11.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".5"/></filter><filter id="iZmnQOc" width="2.294" height="3.435" x="13.704" y="11.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.494118 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/><feGaussianBlur result="effect2_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="imbQYac" width="2.294" height="3.435" x="13.704" y="11.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iETVbId" width="4.091" height="1.697" x="12.806" y="15.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iJKN3zl" width=".855" height=".754" x="16.478" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iA3MOyd" width=".948" height=".973" x="17.427" y="11.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".1"/></filter><filter id="itpZoRd" width="1.054" height="1.114" x="12.47" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".1"/></filter><filter id="ieHVxFd" width=".996" height=".763" x="11.617" y="11.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".05"/></filter><filter id="iVe90wb" width="1.425" height="2.597" x="8.15" y="11.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".125"/></filter><filter id="iF9OaYc" width="1.556" height="2.623" x="20.137" y="11.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2759" stdDeviation=".125"/></filter><filter id="iSjKLPe" width="19.912" height="4.003" x="4.916" y="7.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2759" result="effect2_innerShadow_4002_2759"/></filter><filter id="iwuuAkr" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2759"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:detective-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a5dpq-jqr {
  stop-color: var(--svg-color--ffd9ab, #FFD9AB);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.a9cgrmb3b {
  d: path("M20.342 14.707q.113-1.78.206-3.56a1.796 1.796 0 0 1-.206 3.56");
}

.ab5krjbng {
  d: path("M12.415 11.657a.996.996 0 0 0-.96 1.258h1.924q.034-.128.036-.262a1 1 0 0 0-1-.996");
}

.aj2eo5xfs {
  d: path("M12.625 19.547c.026.291.262.987.999 1.437c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.252-.664c.736-.45.973-1.146.999-1.437z");
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.b98_s-60t {
  stop-color: var(--svg-color--bf8979, #BF8979);
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bc7i0ongh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 28.38h1.96");
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bdm6_2brf {
  fill: var(--svg-color--000, #000);
  d: path("M12.985 12.652a.57.57 0 0 0-.57-.57a.568.568 0 0 0-.507.833h1.01a.6.6 0 0 0 .067-.263");
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
}

.bslse1b3i {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
}

.bt46k-bry {
  stop-color: var(--svg-color--810937, #810937);
}

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.bzlygpkrz {
  cx: 25.695px;
  cy: 17.093px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.c8av-0bva {
  cx: 25.695px;
  cy: 17.093px;
  r: 2.984px;
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctmxvjb_b {
  cx: 12.114px;
  cy: 12.082px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.435px;
  ry: 0.22px;
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.d_0d9e8wo {
  fill: var(--svg-color--be8a77, #BE8A77);
  d: path("m14.425 12.414l-.593 2.05c-.121.422.17.844.58.844h.878c.411 0 .702-.428.58-.843l-.592-2.051c-.127-.455-.72-.455-.853 0");
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e-5wyxbvo {
  stop-color: var(--svg-color--52342d, #52342D);
}

.e331fpbtp {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1564 1564 0 0 1-4.625-7.734c-.422-.735-.219-.907-.14-1.032s.374-.36.671-.468c.238-.088.328-.204.344-.25c.057-.068.069-.3-.344-.688c-.412-.387-1.307-1.068-1.703-1.36c-.234-.187-.651-.609-.601-.984s.65-.435.765-.43z");
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e8-mlobfh {
  d: path("M6.386 7.88c-.26-.016-.991.034-1.316.359c-.358.357-.055 1.073.508 1.652c.539.555 2.335 1.738 5.18 1.738h8.167c2.873 0 4.689-1.183 5.234-1.738c.568-.579.874-1.295.513-1.652c-.328-.325-1.067-.375-1.33-.36z");
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ehjxjubwn {
  stop-color: var(--svg-color--b57a77, #B57A77);
}

.ejbroxbcy {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.701 19.668l.69 3.215c.1.438.278.746.407.869s.325.01.407-.06l1.67-1.517l1.669 1.517c.082.07.28.183.408.06s.299-.415.4-.853l.696-3.231h-1.584l-1.59 2.116l-1.588-2.116z");
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fcv3pabxt {
  stop-color: var(--svg-color--bc907e, #BC907E);
}

.fd42wabnp {
  cx: 12.114px;
  cy: 12.082px;
  rx: 0.435px;
  ry: 0.22px;
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fk1gregde {
  stop-color: var(--svg-color--57497f, #57497F);
  stop-opacity: 0;
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fkavrburz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 25.531h1.96");
}

.foejprbbc {
  stop-color: var(--svg-color--767290, #767290);
}

.fpxhxfble {
  stop-color: var(--svg-color--5c4b6c, #5C4B6C);
}

.ft5dv1b6b {
  fill: none;
}

.fxlu258xo {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.957l3.422-1.2l4.437 1.294l-2.28 10.863z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.h1og-2beh {
  d: path("m11.972 22.726l-.806-3.758h1.851l1.867 2.489v.433l-1.96 1.782c-.097.083-.327.214-.477.07s-.357-.504-.475-1.016");
}

.hg_xi5byk {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.554 2.727 29.923");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.it1ywpbon {
  d: path("m14.425 12.414l-.593 2.05c-.121.422.17.844.58.844h.878c.411 0 .702-.428.58-.843l-.592-2.051c-.127-.455-.72-.455-.853 0");
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.j1n1ygxtd {
  stop-color: var(--svg-color--e3ac86, #E3AC86);
}

.jt362mrmb {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
}

.jy4e3rjsw {
  d: path("m13.289 29.922l.854-5.408a.1.1 0 0 1 .098-.085h1.247a.1.1 0 0 1 .099.085l.827 5.408z");
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k76jtjjwr {
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.437l1.96 1.782c.097.083.328.214.477.07c.15-.144.35-.484.467-.996");
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.keuf9wi3y {
  stop-color: var(--svg-color--ebb48c, #EBB48C);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kmubh8kzn {
  stop-color: var(--svg-color--c5987c, #C5987C);
}

.kmvantawu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.184 11.353a1.56 1.56 0 0 0-1.512 1.181c-.05.195.1.38.299.38h2.49a.257.257 0 0 0 .253-.303a1.56 1.56 0 0 0-1.53-1.258");
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.kyv7jrdlq {
  d: path("M23.132 24.82c0-.439.355-.8.793-.8h3.023c.724 0 1.31.587 1.31 1.31v3.5c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.434a.8.8 0 0 1-.444-.718");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lah1ls-tj {
  stop-color: var(--svg-color--d3a291, #D3A291);
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lolqknbkr {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.37 12.836l-.771 1.847c-.113.422.158.844.543.844h.82c.384 0 .655-.429.542-.844l-.554-2.05c-.118-.455-.455-.251-.58.203");
}

.m-p9sabje {
  stop-color: var(--svg-color--b3747d, #B3747D);
  stop-opacity: 0;
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.mcm2epbwi {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.554 2.727 29.923");
}

.mdv9qbyfi {
  stop-color: var(--svg-color--d69368, #D69368);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mwv4fzbkx {
  d: path("M8.126 7.747a.1.1 0 0 0 .095.132h13.287a.1.1 0 0 0 .094-.133l-.192-.559l-.429-1.245a.1.1 0 0 0-.094-.067H8.829a.1.1 0 0 0-.095.067c-.19.554-.38 1.12-.531 1.575z");
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n-6fznoqh {
  d: path("m13.445 29.922l-2.328-10.957l3.422-1.2l4.437 1.294l-2.28 10.863z");
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.o9e08qbdu {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.226px;
  rx: 1.286px;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odixm9bgr {
  stop-color: var(--svg-color--e5b194, #E5B194);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.pahb5ac_e {
  d: path("M9.213 11.138a1.795 1.795 0 0 0 .154 3.57a87 87 0 0 1-.154-3.57");
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.phcdw6ach {
  stop-color: var(--svg-color--a56571, #A56571);
}

.pkewzbb7b {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.157a3.578 3.578 0 0 0 0 7.157m0-.594a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.969");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.pwmv9bc_x {
  d: path("M9.428 14.606a1.83 1.83 0 0 1-1.01-.344V15.3c0 .997.594 1.884 1.497 2.253a4.6 4.6 0 0 1-.386-1.317z");
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qofkq9kdy {
  stop-color: var(--svg-color--d5a491, #D5A491);
  stop-opacity: 0;
}

.qq_ijsbpi {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.34 16.01c.437.227.957.358 1.511.358c.56 0 1.075-.13 1.511-.358h.001a.25.25 0 0 1 .292.047a.23.23 0 0 1 .025.294m-3.34-.341l3.278.3m-3.278-.3a.25.25 0 0 0-.293.05a.23.23 0 0 0-.024.291m.317-.341l-.255.3m3.595.04v.001l-.062-.042m.062.042l-.062-.042m.062.042a2.19 2.19 0 0 1-1.829.977c-.767 0-1.441-.39-1.828-.977m3.595-.042a2.11 2.11 0 0 1-1.767.944a2.11 2.11 0 0 1-1.766-.944m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.qtigmmeii {
  d: path("M27.203 22.328c.58 0 1.055.475 1.055 1.056V25.8h-2.111v-2.417a1.065 1.065 0 0 1 1.056-1.056");
}

.r-9djmxfd {
  stop-color: var(--svg-color--a8726b, #A8726B);
  stop-opacity: 0;
}

.r99x7jora {
  d: path("M9.468 16.296a4.37 4.37 0 0 0 4.336 3.8h2.104a4.37 4.37 0 0 0 4.335-3.8c.132-2.101.264-4.195.362-6.295a1.617 1.617 0 0 0-1.538-1.598h-1.563a2.7 2.7 0 0 1-2.467-1.61a.74.74 0 0 0-.687-.466h-1.42c-2.059 0-3.727 1.687-3.727 3.77c0 2.076.13 4.118.265 6.199");
}

.raaicexie {
  d: path("M8.804 5.743a.1.1 0 0 0 .094.132h11.92a.1.1 0 0 0 .094-.132a87 87 0 0 0-.639-1.79c-.468-1.25-1.636-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567l-.193.121c-.578.344-.809.398-1.278.398c-.37 0-.761-.148-1.183-.367a5 5 0 0 1-.248-.142c-.436-.26-1.078-.642-1.905-.526c-.956.135-1.66.93-2.097 1.946a29 29 0 0 0-.618 1.668");
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rncji_bbq {
  stop-color: var(--svg-color--c18880, #C18880);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rp3a36fum {
  stop-color: var(--svg-color--b5836c, #B5836C);
}

.ruqf-bc5u {
  stop-color: var(--svg-color--d3a291, #D3A291);
  stop-opacity: 0;
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sfn3j3blb {
  d: path("m14.425 12.198l-.593 2.05c-.121.423.17.845.58.845h.878c.411 0 .702-.429.58-.844l-.592-2.051c-.127-.454-.72-.454-.853 0");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.t_blaotnz {
  stop-color: var(--svg-color--67433f, #67433F);
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t5tjx-buh {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M9.232 11.875a1.066 1.066 0 0 0 .093 2.096q-.06-1.048-.093-2.096");
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
}

.tjixy4bap {
  d: path("M14.851 16.443a3.35 3.35 0 0 1-1.545-.367c-.153-.078-.317.095-.221.233a2.11 2.11 0 0 0 1.766.944c.742 0 1.393-.377 1.767-.944c.096-.144-.068-.31-.221-.233a3.34 3.34 0 0 1-1.546.367");
}

.tjiypub2l {
  width: 1.769px;
  height: 2.205px;
  x: 25.512px;
  y: 15.977px;
  rx: 0.885px;
}

.tnc_xbdtt {
  stop-color: var(--svg-color--202d61, #202D61);
}

.to1bhjtdn {
  d: path("M17.288 11.657a.996.996 0 0 1 .96 1.258h-1.924a1 1 0 0 1 .964-1.258");
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.uk92h5tcg {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.437l1.96 1.782c.097.083.328.214.477.07c.15-.144.35-.484.467-.996");
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.up282p8sz {
  d: path("M17.215 11.867c.07.095-.078.211-.246.337c-.169.126-.294.215-.365.12c-.07-.095.009-.274.177-.4c.169-.126.363-.151.434-.057");
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.we2_cetne {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.387 13.98q.064-1.06.123-2.123a1.066 1.066 0 0 1-.123 2.124");
}

.ws_t7ubqt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.215 11.867c.07.095-.078.211-.246.337c-.169.126-.294.215-.365.12c-.07-.095.009-.274.177-.4c.169-.126.363-.151.434-.057");
}

.wsj2g07-c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.955h1.962");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.wtk4a52ny {
  stop-color: var(--svg-color--d5a491, #D5A491);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x62u6rbbl {
  d: path("M20.275 14.606a1.83 1.83 0 0 0 1.009-.344V15.3c0 .997-.594 1.884-1.496 2.253q.286-.609.386-1.317z");
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xvd1hdcxc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.519 11.353c.728 0 1.344.503 1.511 1.181c.05.195-.1.38-.298.38h-2.49a.257.257 0 0 1-.253-.303a1.56 1.56 0 0 1 1.53-1.258");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y_rt2lgnd {
  fill: var(--svg-color--000, #000);
  d: path("M16.718 12.652c0-.317.253-.57.57-.57a.568.568 0 0 1 .507.832h-1.01a.5.5 0 0 1-.067-.262");
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y431-xmsp {
  stop-color: var(--svg-color--a8726b, #A8726B);
}

.yfkzyxbts {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
  stop-opacity: 0;
}

.ygg62-bdc {
  d: path("M18.175 12.52a.94.94 0 0 0-.258-.515l-.29.318l.13.254z");
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yjhtlsg3j {
  d: path("M13.324 12.535c0-.321-.261-.536-.332-.6l-.322.31l.198.404z");
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yrzi8mt9l {
  stop-color: var(--svg-color--fdc6a0, #FDC6A0);
}

.yyc71qb6t {
  d: path("m18.996 16.977l-2.743 12.945h1.797c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.219-.907.14-1.032c-.077-.125-.374-.36-.671-.468c-.237-.088-.328-.204-.344-.25c-.057-.068-.069-.3.344-.688s1.307-1.068 1.703-1.36c.234-.187.652-.609.602-.984s-.651-.435-.766-.43z");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z-xw_ccte {
  stop-color: var(--svg-color--a7696f, #A7696F);
}

.z5z3i6nzk {
  stop-color: var(--svg-color--a7696f, #A7696F);
  stop-opacity: 0;
}

.zgu_--bpo {
  d: path("m14.098 24.349l-.692-1.334l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.083h-1.284a.15.15 0 0 1-.134-.08");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zochtpbty {
  stop-color: var(--svg-color--b27c72, #B27C72);
  stop-opacity: 0;
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zwjanzbmf {
  stop-color: var(--svg-color--b27c72, #B27C72);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
