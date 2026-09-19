<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hg_xi5byk"/><path fill="url(#iUk42Kc)" class="mcm2epbwi"/><path fill="url(#itbtQzd)" class="mcm2epbwi"/><path fill="url(#iZmm8Xd)" class="mcm2epbwi"/><path fill="url(#ik6YnHb)" class="mcm2epbwi"/><path fill="url(#idva0Yd)" class="mcm2epbwi"/><path class="fxlu258xo"/><path fill="url(#imSQI2c)" class="n-6fznoqh"/><path fill="url(#i4d8iJd)" class="n-6fznoqh"/><path fill="url(#iHdaBGb)" class="n-6fznoqh"/><g filter="url(#irqx6Pi)"><path class="ejbroxbcy"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#izXeBwc)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#i5v4GXd)" class="by194g1ei"/><path fill="url(#i43VwXd)" class="by194g1ei"/><g filter="url(#i5Ckt3c)"><path fill="url(#iRjyRMt)" class="zgu_--bpo"/></g><path fill="url(#iollnke)" class="jy4e3rjsw"/><path fill="url(#iOnL5De)" class="jy4e3rjsw"/><path fill="url(#i4hNkDe)" class="jy4e3rjsw"/><path fill="url(#i9bX55c)" class="h1og-2beh"/><path fill="url(#iMIg2ZO)" class="h1og-2beh"/><path fill="url(#i9Nz6Jl)" class="h1og-2beh"/><path fill="url(#i816X5R)" class="h1og-2beh"/><path fill="url(#iIipaHv)" class="h1og-2beh"/><path class="uk92h5tcg"/><path fill="url(#iLnu67h)" class="k76jtjjwr"/><path fill="url(#idlpVJd)" class="k76jtjjwr"/><path fill="url(#imdlgvc)" class="k76jtjjwr"/><path fill="url(#ira2lKd)" class="k76jtjjwr"/><path fill="url(#iB1w8Ed)" class="k76jtjjwr"/><g filter="url(#iOy4F4c)"><path fill="url(#ilVNUUb)" class="aj2eo5xfs"/><path fill="url(#ivtRrhc)" class="aj2eo5xfs"/></g><g filter="url(#izHr5Dd)"><path fill="url(#i9VYgXa)" class="e331fpbtp"/><path fill="url(#iVY5Ecc)" class="e331fpbtp"/><path fill="url(#iLW0nln)" class="e331fpbtp"/><path fill="url(#imEendb)" class="e331fpbtp"/><path fill="url(#irOFmTd)" class="e331fpbtp"/></g><g filter="url(#ifFLLjE)"><path fill="url(#iSfw5wd)" class="yyc71qb6t"/><path fill="url(#iiIvpQb)" class="yyc71qb6t"/><path fill="url(#isUiL6c)" class="yyc71qb6t"/><path fill="url(#iPij2KA)" class="yyc71qb6t"/></g><path fill="url(#i4Ttz3O)" class="qtigmmeii"/><path fill="url(#iepmPae)" class="qtigmmeii"/><rect fill="url(#iGFxt3d)" class="o9e08qbdu"/><rect fill="url(#iCZvVXc)" class="o9e08qbdu"/><rect fill="url(#iT0Szpc)" class="o9e08qbdu"/><rect fill="url(#iNyUeyU)" class="o9e08qbdu"/><g filter="url(#iX9v5Zb)"><circle class="bzlygpkrz"/></g><circle fill="url(#iU1hsCv)" class="c8av-0bva"/><circle fill="url(#i5Fhu0c)" class="c8av-0bva"/><g filter="url(#iH2PVpc)"><path fill="url(#irI5LDd)" clip-rule="evenodd" class="pkewzbb7b"/></g><rect fill="url(#is19MEd)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#i508Jhe)"><path fill="url(#iyCZoxd)" class="kyv7jrdlq"/><path fill="url(#izGehDb)" class="kyv7jrdlq"/><path fill="url(#idC83od)" class="kyv7jrdlq"/><path fill="url(#iPk3fyb)" class="kyv7jrdlq"/><path fill="url(#iQVl2Wc)" class="kyv7jrdlq"/></g><g filter="url(#iXhCo8c)"><path stroke="url(#iNPO7Ld)" class="fkavrburz"/></g><g filter="url(#iIZtO7b)"><path stroke="url(#is1zmgb)" class="wsj2g07-c"/></g><g filter="url(#ica0WCb)"><path stroke="url(#ilpKa8b)" class="bc7i0ongh"/></g><path fill="url(#i06GRCe)" class="ipt1bfbah"/><path fill="url(#igauvgc)" class="t82f7j6vo"/><g filter="url(#iChBXbc)"><path fill="url(#iI0C8Vb)" class="v30rs0boi"/><path fill="url(#iLpjqrb)" class="v30rs0boi"/></g><path fill="url(#iztzFMM)" class="v30rs0boi"/><path fill="url(#icuty8b)" class="v30rs0boi"/><path fill="url(#i2npjgH)" class="v30rs0boi"/><path fill="url(#i4o5mOr)" class="v30rs0boi"/><path fill="url(#iTQD5mc)" class="v30rs0boi"/><path fill="url(#iPsldSo)" class="v30rs0boi"/><path fill="url(#iCInpMc)" class="v30rs0boi"/><path fill="url(#iVxBsKe)" class="v30rs0boi"/><path fill="url(#ix6qsLe)" class="v30rs0boi"/><path fill="url(#iQrpKUd)" class="v30rs0boi"/><g filter="url(#iOLbWjc)"><path class="orv1t_kej"/></g><g filter="url(#iKQGUyc)"><path class="e2bn6fzum"/><path fill="url(#i96Qqoj)" class="t-w3kccor"/><path fill="url(#iTK5ZxO)" class="t-w3kccor"/><path fill="url(#in9hqHb)" class="t-w3kccor"/><path fill="url(#iKlfTzc)" class="t-w3kccor"/></g><g filter="url(#iMiirRd)"><path fill="url(#ie7yhIb)" class="p86wpqbvb"/></g><g filter="url(#imCMcGT)"><path stroke="url(#iyiQn1d)" class="i9yk9g3ti"/></g><path fill="url(#i8LIDsd)" class="jul696bez"/><path class="xvpleobpk"/><path fill="url(#iD122Jd)" class="tptatk8az"/><path class="mdns0tbcw"/><g filter="url(#ic2tecd)"><path class="es2q2uslr"/><path fill="url(#infeRDd)" class="xedeyobfo"/></g><g filter="url(#iUWbLpe)"><path fill="url(#ivyJg6d)" class="n077pnbic"/></g><path class="onh17wupt"/><path fill="url(#iV2jBec)" class="ypl05wbbw"/><path class="ci01wqxer"/><g filter="url(#iQpR1le)"><path fill="url(#iFRVdcf)" class="z9q4-zbzu"/></g><g filter="url(#i9rIyRd)"><ellipse transform="rotate(-27.914 12.135 12.103)" class="s_1fh7b1a"/><ellipse fill="url(#ivAsrtc)" transform="rotate(-27.914 12.135 12.103)" class="ox8iaisdf"/></g><path fill="url(#isk41je)" class="a6vj1vxht"/><path fill="url(#i0tr6Pe)" class="a6vj1vxht"/><path fill="url(#i2EmXxd)" class="a6vj1vxht"/><path fill="url(#icSeDmb)" class="a6vj1vxht"/><path fill="url(#i1jjxqc)" class="o5l1a0btf"/><path fill="url(#i3L2cGe)" class="o5l1a0btf"/><g filter="url(#iq0x4Md)"><path fill="url(#i4Elfiz)" class="s2eg5fbxb"/></g><g filter="url(#iUcMJvc)"><path fill="url(#i2nKuNc)" class="gyu37tnpy"/></g><g filter="url(#iVporvd)"><path fill="url(#i8gh6Fe)" class="raaicexie"/></g><path fill="url(#iBfj5Pd)" class="raaicexie"/><path fill="url(#ieAjMmb)" class="raaicexie"/><g filter="url(#i18qbbb)"><path fill="url(#iodu1md)" class="e8-mlobfh"/></g><path fill="url(#iQFwsnd)" class="mwv4fzbkx"/><path fill="url(#iuO87Jd)" class="mwv4fzbkx"/><path fill="url(#iUaN9Xb)" class="mwv4fzbkx"/><path fill="url(#iD4Nv7d)" class="mwv4fzbkx"/><defs><radialGradient id="iUk42Kc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.812)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="ik6YnHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.835 22.156)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="idva0Yd" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.415 66.252)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="i4d8iJd" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .523 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iHdaBGb" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.884)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="izXeBwc" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.544 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="i5v4GXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.468)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="i43VwXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iRjyRMt" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.654)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iollnke" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.781)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i9bX55c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.968)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="i9Nz6Jl" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.195 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="i816X5R" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.128)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iIipaHv" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.05 20.861)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iLnu67h" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.468)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="imdlgvc" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.371 20.582)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iB1w8Ed" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.701 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="ilVNUUb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.78888 2.28145 -.95395 -1.58425 17.864 19.767)" gradientUnits="userSpaceOnUse"><stop class="xpue650cw"/><stop offset="1" class="noz9vkbxt"/></radialGradient><radialGradient id="ivtRrhc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5045 .1671 -.03048 -.45688 14.29 19.958)" gradientUnits="userSpaceOnUse"><stop class="hoqjl1bek"/><stop offset="1" class="olj659buj"/></radialGradient><radialGradient id="iLW0nln" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.282)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="irOFmTd" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.253)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iPij2KA" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.982)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="i4Ttz3O" cx="0" cy="0" r="1" gradientTransform="rotate(140.585 10.006 16.57)scale(2.25799 2.21834)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="iepmPae" cx="0" cy="0" r="1" gradientTransform="matrix(.81959 -.51212 .26744 .42801 28.014 22.732)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iT0Szpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.226)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iNyUeyU" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.265)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="is19MEd" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.118)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="izGehDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="idC83od" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iPk3fyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iQVl2Wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i06GRCe" cx="0" cy="0" r="1" gradientTransform="matrix(.8314 2.24236 -2.66375 .98763 20.137 14.271)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="igauvgc" cx="0" cy="0" r="1" gradientTransform="matrix(1.63936 .51522 -1.5895 5.05756 8.134 14.815)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iI0C8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.80466 0 0 -10.2684 17.976 13.226)" gradientUnits="userSpaceOnUse"><stop class="m6i64ob9s"/><stop offset=".8" class="hhi9hubjb"/><stop offset="1" class="w3m41_b3u"/></radialGradient><radialGradient id="iLpjqrb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.606 8.799)scale(3.7407 3.08825)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="icuty8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.36625 17.0808 0 14.839 20.078)" gradientUnits="userSpaceOnUse"><stop class="plth6ctui"/><stop offset="1" class="dwutbj-od"/></radialGradient><radialGradient id="i2npjgH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.27505 1.57788 0 17.576 11.769)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i4o5mOr" cx="0" cy="0" r="1" gradientTransform="matrix(.00436 -1.21501 1.32222 .00475 12.305 11.82)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iTQD5mc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.43338 .59548 -1.52116 -24.09754 18.67 14.323)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iPsldSo" cx="0" cy="0" r="1" gradientTransform="matrix(3.75935 -3.23826 .95653 1.11045 7.318 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iCInpMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26055 2.77299 -1.10848 -.10415 21.015 9.987)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iVxBsKe" cx="0" cy="0" r="1" gradientTransform="matrix(.10938 -.80423 2.55387 .34734 12.992 20.078)" gradientUnits="userSpaceOnUse"><stop class="yykzn00ws"/><stop offset="1" class="ykx7psb2s"/></radialGradient><radialGradient id="ix6qsLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 -1.03125 3.27484 -1.09162 16.836 20.32)" gradientUnits="userSpaceOnUse"><stop class="yykzn00ws"/><stop offset="1" class="ykx7psb2s"/></radialGradient><radialGradient id="iQrpKUd" cx="0" cy="0" r="1" gradientTransform="matrix(.79365 4.375 -8.29268 1.50434 14.117 10.883)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="h9hedgb-i"/><stop offset="1" class="mk7wtccvn"/></radialGradient><radialGradient id="iTK5ZxO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .27104 -.85183 0 15.377 14.737)" gradientUnits="userSpaceOnUse"><stop class="rpxfseb7a"/><stop offset="1" class="rxtxp2xvj"/></radialGradient><radialGradient id="iKlfTzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68898 .77438 -1.2445 -2.71432 15.506 14.104)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="i8LIDsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.42273 -1.19108 4.79201 9.74725 14.314 17.25)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iD122Jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90084 -1.43288 0 17.282 12.21)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="infeRDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2575 -.33183 .45685 -.35452 17.029 12.303)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iV2jBec" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90088 -1.43295 0 12.436 12.21)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="ivAsrtc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.189 .261)scale(.54866 .65952)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0tr6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(.6979 2.49078 -2.3764 .66585 19.986 12.224)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="i2EmXxd" cx="0" cy="0" r="1" gradientTransform="matrix(.8747 -1.20039 1.00616 .73317 20.386 12.83)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="icSeDmb" cx="0" cy="0" r="1" gradientTransform="matrix(.65176 -1.72149 2.30015 .87085 20.513 13.02)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i3L2cGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84121 0 0 -2.05598 9.401 12.936)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="i4Elfiz" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 4.15 6.87)scale(1.03248 1.05862)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iQFwsnd" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.609)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><linearGradient id="iZmm8Xd" x1="6.988" x2="7.195" y1="29.406" y2="29.406" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="imSQI2c" x1="16.932" x2="14.847" y1="28.545" y2="28.119" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="iOnL5De" x1="13.726" x2="14.226" y1="26.765" y2="26.812" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="i4hNkDe" x1="16.414" x2="15.153" y1="29.069" y2="29.122" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="iMIg2ZO" x1="11.675" x2="12.612" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="idlpVJd" x1="18.074" x2="17.138" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="i9VYgXa" x1="12.219" x2="9.392" y1="26.169" y2="26.806" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iVY5Ecc" x1="9.392" x2="11.086" y1="16.976" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="imEendb" x1="12.268" x2="12.268" y1="29.922" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="iSfw5wd" x1="18.023" x2="21.304" y1="29.125" y2="16.976" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iiIvpQb" x1="17" x2="17.152" y1="26.539" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iGFxt3d" x1="26.981" x2="24.992" y1="21.781" y2="21.781" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iCZvVXc" x1="26.336" x2="26.336" y1="25.468" y2="22.562" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="irI5LDd" x1="28.179" x2="23.367" y1="14.344" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="iyCZoxd" x1="27.914" x2="23.132" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iNPO7Ld" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="is1zmgb" x1="23.614" x2="25.48" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ilpKa8b" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iztzFMM" x1="20.585" x2="17.777" y1="15.098" y2="15.098" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i96Qqoj" x1="15.79" x2="15.094" y1="13.975" y2="13.992" gradientUnits="userSpaceOnUse"><stop class="myj-9sdud"/><stop offset="1" class="dt9g2qbwa"/></linearGradient><linearGradient id="in9hqHb" x1="14.859" x2="14.859" y1="15.24" y2="14.724" gradientUnits="userSpaceOnUse"><stop class="x0w_b5ndh"/><stop offset="1" class="vmstrxb4d"/></linearGradient><linearGradient id="ie7yhIb" x1="14.859" x2="14.859" y1="11.896" y2="13.295" gradientUnits="userSpaceOnUse"><stop class="rbz0-dbrz"/><stop offset="1" class="io_yrnb9q"/></linearGradient><linearGradient id="iyiQn1d" x1="13.525" x2="13.878" y1="16.985" y2="16.058" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ivyJg6d" x1="18.146" x2="17.797" y1="12.269" y2="12.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFRVdcf" x1="13.262" x2="12.914" y1="12.269" y2="12.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isk41je" x1="22.006" x2="20.666" y1="12.299" y2="14.715" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i1jjxqc" x1="8.364" x2="9.983" y1="13.08" y2="12.939" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="i2nKuNc" x1="20.873" x2="20.873" y1="11.875" y2="13.988" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iuO87Jd" x1="8.554" x2="9.992" y1="6.877" y2="7.062" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iUaN9Xb" x1="15.461" x2="15.461" y1="7.929" y2="7.726" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iD4Nv7d" x1="15.507" x2="15.507" y1="5.847" y2="5.984" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="irqx6Pi" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".25"/></filter><filter id="i5Ckt3c" width="3.106" height="2.966" x="13.406" y="21.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="iOy4F4c" width="4.5" height="2.352" x="12.625" y="19.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="izHr5Dd" width="8.299" height="13.046" x="5.292" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="ifFLLjE" width="8.299" height="13.046" x="16.153" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="iX9v5Zb" width="6.656" height="6.656" x="22.367" y="13.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".125"/></filter><filter id="iH2PVpc" width="7.206" height="7.206" x="22.067" y="13.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="i508Jhe" width="5.277" height="6.052" x="23.132" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="iXhCo8c" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".05"/></filter><filter id="iIZtO7b" width="2.262" height=".3" x="23.464" y="26.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".05"/></filter><filter id="ica0WCb" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".05"/></filter><filter id="iChBXbc" width="12.348" height="13.903" x="9.237" y="6.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2753" result="effect2_innerShadow_4002_2753"/></filter><filter id="iOLbWjc" width="3.939" height="5.22" x="12.732" y="11.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".5"/></filter><filter id="iKQGUyc" width="2.484" height="3.62" x="13.617" y="11.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".1"/></filter><filter id="iMiirRd" width="2.484" height="3.62" x="13.617" y="11.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".1"/></filter><filter id="imCMcGT" width="4.074" height="1.691" x="12.822" y="15.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".05"/></filter><filter id="ic2tecd" width=".852" height=".751" x="16.478" y="11.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".05"/></filter><filter id="iUWbLpe" width=".945" height=".97" x="17.421" y="11.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".1"/></filter><filter id="iQpR1le" width="1.051" height="1.111" x="12.489" y="11.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".1"/></filter><filter id="i9rIyRd" width=".992" height=".76" x="11.639" y="11.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".05"/></filter><filter id="iq0x4Md" width="1.42" height="2.587" x="8.135" y="11.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".125"/></filter><filter id="iUcMJvc" width="2.051" height="3.113" x="19.847" y="11.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2753" stdDeviation=".25"/></filter><filter id="iVporvd" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/></filter><filter id="i18qbbb" width="19.912" height="4.003" x="4.916" y="7.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2753"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2753" result="effect2_innerShadow_4002_2753"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:detective-medium-dark" /></template>
<style>
.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6vj1vxht {
  d: path("M20.324 14.715q.11-1.772.205-3.543a1.787 1.787 0 0 1-.205 3.543");
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.aj2eo5xfs {
  d: path("M12.625 19.547c.026.291.262.987.999 1.437c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.252-.664c.736-.45.973-1.146.999-1.437z");
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
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

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
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

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.ci01wqxer {
  fill: var(--svg-color--000, #000);
  d: path("M13.002 12.67a.565.565 0 0 0-.568-.567a.565.565 0 0 0-.504.83h1.004a.56.56 0 0 0 .068-.262");
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
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

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dt9g2qbwa {
  stop-color: var(--svg-color--846360, #846360);
  stop-opacity: 0;
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.dwutbj-od {
  stop-color: var(--svg-color--734354, #734354);
  stop-opacity: 0;
}

.e-5wyxbvo {
  stop-color: var(--svg-color--52342d, #52342D);
}

.e2bn6fzum {
  fill: var(--svg-color--623b3b, #623B3B);
  d: path("m14.435 12.433l-.59 2.04c-.121.42.168.84.577.84h.874c.41 0 .698-.426.578-.84l-.59-2.04c-.127-.453-.717-.453-.85 0");
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

.ejbroxbcy {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.701 19.668l.69 3.215c.1.438.278.746.407.869s.325.01.407-.06l1.67-1.517l1.669 1.517c.082.07.28.183.408.06s.299-.415.4-.853l.696-3.231h-1.584l-1.59 2.116l-1.588-2.116z");
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.es2q2uslr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.211 11.89c.07.094-.077.209-.244.334c-.168.126-.293.214-.363.12c-.07-.095.008-.273.176-.399c.167-.125.36-.15.431-.056");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
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

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fxlu258xo {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.957l3.422-1.2l4.437 1.294l-2.28 10.863z");
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

.gyu37tnpy {
  d: path("M20.347 13.988q.065-1.056.123-2.113a1.06 1.06 0 0 1-.123 2.113");
}

.h1og-2beh {
  d: path("m11.972 22.726l-.806-3.758h1.851l1.867 2.489v.433l-1.96 1.782c-.097.083-.327.214-.477.07s-.357-.504-.475-1.016");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h9hedgb-i {
  stop-color: var(--svg-color--5d3a3f, #5D3A3F);
}

.hg_xi5byk {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.554 2.727 29.923");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hoqjl1bek {
  stop-color: var(--svg-color--613540, #613540);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.i9yk9g3ti {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.355 16.012a3.26 3.26 0 0 0 1.504.356c.557 0 1.07-.13 1.504-.356a.245.245 0 0 1 .291.047a.23.23 0 0 1 .026.293l-.063-.042c-.372.564-1.02.94-1.758.94a2.1 2.1 0 0 1-1.758-.94zm0 0a.245.245 0 0 0-.292.05a.23.23 0 0 0-.024.29z");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.io_yrnb9q {
  stop-color: var(--svg-color--5f3b40, #5F3B40);
  stop-opacity: 0;
}

.ipt1bfbah {
  d: path("M20.257 14.614a1.8 1.8 0 0 0 1.004-.343v1.034a2.41 2.41 0 0 1-1.489 2.242a4.5 4.5 0 0 0 .384-1.31z");
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.jul696bez {
  d: path("M14.859 16.443a3.34 3.34 0 0 1-1.538-.365c-.153-.077-.316.094-.22.232c.372.564 1.02.94 1.758.94s1.386-.376 1.758-.94c.096-.143-.068-.31-.22-.232a3.3 3.3 0 0 1-1.538.365");
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

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
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

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.m6i64ob9s {
  stop-color: var(--svg-color--8e6259, #8E6259);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mcm2epbwi {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.554 2.727 29.923");
}

.mdns0tbcw {
  fill: var(--svg-color--000, #000);
  d: path("M16.717 12.67c0-.315.252-.567.567-.567a.565.565 0 0 1 .505.829h-1.005a.5.5 0 0 1-.067-.261");
}

.mk7wtccvn {
  stop-color: var(--svg-color--5b3340, #5B3340);
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

.myj-9sdud {
  stop-color: var(--svg-color--846360, #846360);
}

.n-6fznoqh {
  d: path("m13.445 29.922l-2.328-10.957l3.422-1.2l4.437 1.294l-2.28 10.863z");
}

.n077pnbic {
  d: path("M18.167 12.54a.93.93 0 0 0-.257-.514l-.289.317l.13.253z");
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
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

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.noz9vkbxt {
  stop-color: var(--svg-color--693a46, #693A46);
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

.o5l1a0btf {
  d: path("M9.258 11.157a1.8 1.8 0 0 0-1.545 1.774c0 .954.747 1.733 1.688 1.784a87 87 0 0 1-.143-3.558");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
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

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.olj659buj {
  stop-color: var(--svg-color--613540, #613540);
  stop-opacity: 0;
}

.onh17wupt {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.204 11.378c-.725 0-1.338.5-1.504 1.175a.304.304 0 0 0 .297.379h2.478a.256.256 0 0 0 .252-.302a1.556 1.556 0 0 0-1.523-1.252");
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.orv1t_kej {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.413 12.65l-.656 2.042c-.112.42.157.84.538.84h.813c.38 0 .65-.427.537-.84l-.549-2.042c-.117-.452-.56-.452-.683 0");
}

.ox8iaisdf {
  cx: 12.135px;
  cy: 12.103px;
  rx: 0.433px;
  ry: 0.219px;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p86wpqbvb {
  d: path("m14.435 12.235l-.59 2.042c-.121.42.168.84.577.84h.874c.41 0 .698-.427.578-.84l-.59-2.042c-.127-.452-.717-.452-.85 0");
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pkewzbb7b {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.157a3.578 3.578 0 0 0 0 7.157m0-.594a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.969");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.plth6ctui {
  stop-color: var(--svg-color--623748, #623748);
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
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

.qtigmmeii {
  d: path("M27.203 22.328c.58 0 1.055.475 1.055 1.056V25.8h-2.111v-2.417a1.065 1.065 0 0 1 1.056-1.056");
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.raaicexie {
  d: path("M8.804 5.743a.1.1 0 0 0 .094.132h11.92a.1.1 0 0 0 .094-.132a87 87 0 0 0-.639-1.79c-.468-1.25-1.636-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567l-.193.121c-.578.344-.809.398-1.278.398c-.37 0-.761-.148-1.183-.367a5 5 0 0 1-.248-.142c-.436-.26-1.078-.642-1.905-.526c-.956.135-1.66.93-2.097 1.946a29 29 0 0 0-.618 1.668");
}

.rbz0-dbrz {
  stop-color: var(--svg-color--5f3b40, #5F3B40);
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rpxfseb7a {
  stop-color: var(--svg-color--846461, #846461);
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.rxtxp2xvj {
  stop-color: var(--svg-color--846461, #846461);
  stop-opacity: 0;
}

.s_1fh7b1a {
  cx: 12.135px;
  cy: 12.103px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.433px;
  ry: 0.219px;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.s2eg5fbxb {
  d: path("M9.212 11.896a1.061 1.061 0 0 0 .093 2.087a87 87 0 0 1-.093-2.087");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_blaotnz {
  stop-color: var(--svg-color--67433f, #67433F);
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t-w3kccor {
  d: path("m14.435 12.433l-.59 2.04c-.121.42.168.84.577.84h.874c.41 0 .698-.426.578-.84l-.59-2.04c-.127-.453-.717-.453-.85 0");
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t82f7j6vo {
  d: path("M9.461 14.614a1.8 1.8 0 0 1-1.004-.343v1.034c0 .992.59 1.875 1.489 2.242a4.5 4.5 0 0 1-.384-1.31z");
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
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

.tptatk8az {
  d: path("M17.284 11.68a.99.99 0 0 1 .955 1.252h-1.914a.995.995 0 0 1 .96-1.252");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.uk92h5tcg {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.437l1.96 1.782c.097.083.328.214.477.07c.15-.144.35-.484.467-.996");
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.v30rs0boi {
  d: path("M9.502 16.297a4.35 4.35 0 0 0 4.314 3.781h2.095a4.35 4.35 0 0 0 4.314-3.781c.131-2.092.263-4.175.36-6.266a1.61 1.61 0 0 0-1.531-1.59h-1.555a2.69 2.69 0 0 1-2.455-1.602a.74.74 0 0 0-.684-.464h-1.413c-2.05 0-3.71 1.68-3.71 3.752c0 2.066.13 4.098.265 6.17");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vmstrxb4d {
  stop-color: var(--svg-color--713e4a, #713E4A);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w3m41_b3u {
  stop-color: var(--svg-color--6d4649, #6D4649);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wsj2g07-c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.955h1.962");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x0w_b5ndh {
  stop-color: var(--svg-color--713e4a, #713E4A);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xedeyobfo {
  d: path("M17.211 11.89c.07.094-.077.209-.244.334c-.168.126-.293.214-.363.12c-.07-.095.008-.273.176-.399c.167-.125.36-.15.431-.056");
}

.xpue650cw {
  stop-color: var(--svg-color--765553, #765553);
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xvpleobpk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.514 11.378c.725 0 1.338.5 1.504 1.175a.304.304 0 0 1-.297.379h-2.477a.256.256 0 0 1-.253-.302a1.55 1.55 0 0 1 1.523-1.252");
}

.ykx7psb2s {
  stop-color: var(--svg-color--6e4d59, #6E4D59);
  stop-opacity: 0;
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.ypl05wbbw {
  d: path("M12.434 11.68a.99.99 0 0 0-.955 1.252h1.915q.035-.127.036-.262a1 1 0 0 0-.996-.99");
}

.yyc71qb6t {
  d: path("m18.996 16.977l-2.743 12.945h1.797c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.219-.907.14-1.032c-.077-.125-.374-.36-.671-.468c-.237-.088-.328-.204-.344-.25c-.057-.068-.069-.3.344-.688s1.307-1.068 1.703-1.36c.234-.187.652-.609.602-.984s-.651-.435-.766-.43z");
}

.yykzn00ws {
  stop-color: var(--svg-color--6e4d59, #6E4D59);
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z9q4-zbzu {
  d: path("M13.34 12.554c0-.32-.26-.534-.331-.598l-.32.31l.197.4z");
}

.zgu_--bpo {
  d: path("m14.098 24.349l-.692-1.334l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.083h-1.284a.15.15 0 0 1-.134-.08");
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
