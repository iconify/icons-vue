<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="a5n2d0brj"/><path fill="url(#iAlKUYw)" class="l4za3cbte"/><path fill="url(#itbtQzd)" class="l4za3cbte"/><path fill="url(#iZmm8Xd)" class="l4za3cbte"/><path fill="url(#iOgfppd)" class="l4za3cbte"/><path fill="url(#iGx7x8c)" class="l4za3cbte"/><path class="t9v2librs"/><path fill="url(#iYQZt5g)" class="cej917bjj"/><path fill="url(#i4d8iJd)" class="cej917bjj"/><path fill="url(#iHdaBGb)" class="cej917bjj"/><g filter="url(#i3fTIqe)"><path class="aygyz2b1y"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#izXeBwc)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iftm7Hc)" class="by194g1ei"/><path fill="url(#i43VwXd)" class="by194g1ei"/><g filter="url(#iHyatNb)"><path fill="url(#iRjyRMt)" class="dszt5lbif"/></g><path fill="url(#iOeoa4b)" class="vi7fu79ul"/><path fill="url(#im9eHqM)" class="vi7fu79ul"/><path fill="url(#i90VaHb)" class="vi7fu79ul"/><path fill="url(#i8KloTQ)" class="c9_6a4bgu"/><path fill="url(#idhUOce)" class="c9_6a4bgu"/><path fill="url(#iEpqGnc)" class="c9_6a4bgu"/><path fill="url(#iHu3LFd)" class="c9_6a4bgu"/><path fill="url(#iP6c0ue)" class="c9_6a4bgu"/><path class="c6vmhn63l"/><path fill="url(#iY8ko2d)" class="a38uvfb5u"/><path fill="url(#iOkMYsd)" class="a38uvfb5u"/><path fill="url(#i7oZ1zb)" class="a38uvfb5u"/><path fill="url(#ira2lKd)" class="a38uvfb5u"/><path fill="url(#iknlR1o)" class="a38uvfb5u"/><g filter="url(#inDTopc)"><path fill="url(#il10nec)" class="xxcw8_bas"/><path fill="url(#ic895Kb)" class="xxcw8_bas"/></g><g filter="url(#iZWEs6d)"><path fill="url(#i9VYgXa)" class="rc34chbjr"/><path fill="url(#iVY5Ecc)" class="rc34chbjr"/><path fill="url(#iLW0nln)" class="rc34chbjr"/><path fill="url(#imEendb)" class="rc34chbjr"/><path fill="url(#irOFmTd)" class="rc34chbjr"/></g><g filter="url(#idI5I0b)"><path fill="url(#iSfw5wd)" class="vw12-pbuc"/><path fill="url(#iiIvpQb)" class="vw12-pbuc"/><path fill="url(#isUiL6c)" class="vw12-pbuc"/><path fill="url(#iPij2KA)" class="vw12-pbuc"/></g><path fill="url(#iLxtNEV)" class="gfuyog18w"/><path fill="url(#ipOFiCd)" class="gfuyog18w"/><rect fill="url(#iz2Begd)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#ij2BHIe)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#i7vlLrd)"><path fill="url(#iIrRcKb)" clip-rule="evenodd" class="fqmktcbay"/></g><rect fill="url(#is19MEd)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#iyKITMc)"><path fill="url(#i93taOc)" class="kyv7jrdlq"/><path fill="url(#ivMViyT)" class="kyv7jrdlq"/><path fill="url(#i7Ibu8c)" class="kyv7jrdlq"/><path fill="url(#iZRGmrd)" class="kyv7jrdlq"/><path fill="url(#ioCxhte)" class="kyv7jrdlq"/></g><g filter="url(#i5n1eib)"><path stroke="url(#i8Dhgpc)" class="fkavrburz"/></g><g filter="url(#ioXc0Gb)"><path stroke="url(#iM7Z3Eb)" class="wsj2g07-c"/></g><g filter="url(#ifZ0Zkb)"><path stroke="url(#ijkvTob)" class="bc7i0ongh"/></g><path fill="url(#iqZxZRc)" class="pyz2txsgl"/><path fill="url(#i8QSyxd)" class="j0gwlfbix"/><g filter="url(#irD9m1d)"><path fill="url(#iuByYyK)" class="ah1y65bnf"/><path fill="url(#iKDi3Hc)" class="ah1y65bnf"/></g><path fill="url(#i3kHT6d)" class="ah1y65bnf"/><path fill="url(#iLRoxxD)" class="ah1y65bnf"/><path fill="url(#itZ9y8c)" class="ah1y65bnf"/><path fill="url(#izW78de)" class="ah1y65bnf"/><path fill="url(#iKA7AKd)" class="ah1y65bnf"/><path fill="url(#imJ0kgd)" class="ah1y65bnf"/><path fill="url(#iF9yD4d)" class="ah1y65bnf"/><path fill="url(#iGGGiQb)" class="ah1y65bnf"/><path fill="url(#ic39NVd)" class="ah1y65bnf"/><path fill="url(#isYGO4d)" class="ah1y65bnf"/><path fill="url(#iNdJTuc)" class="ah1y65bnf"/><g filter="url(#iWy7AOc)"><path class="d84d8gawl"/></g><g filter="url(#iwl0EAc)"><path class="o872acc1u"/><path fill="url(#ikCrBfb)" class="w__zc_1bz"/><path fill="url(#iRKfLuc)" class="w__zc_1bz"/><path fill="url(#iSeUXae)" class="w__zc_1bz"/><path fill="url(#izZeSNd)" class="w__zc_1bz"/></g><g filter="url(#ixgqmre)"><path fill="url(#ij5StRb)" class="m3lt9upxo"/></g><g filter="url(#iBkZZCb)"><path stroke="url(#ii7pBVc)" class="mh3eme4ib"/></g><path fill="url(#iFlJxKd)" class="uc4cnoe_k"/><path class="c1hl4qc_a"/><path fill="url(#i1ZRrad)" class="q5f971bhv"/><path class="is2b6sbzg"/><g filter="url(#iRd2zGc)"><path class="eha30-cnn"/><path fill="url(#ihXqDkb)" class="erunfwkci"/></g><g filter="url(#iTniB8c)"><path fill="url(#iuZe4ne)" class="yobikpp-q"/></g><path class="mfwn3ipub"/><path fill="url(#iWecRxd)" class="xh75albmj"/><path class="fj1t0bcdc"/><g filter="url(#iAOecVc)"><path fill="url(#ip3YHXd)" class="lesc7vbsr"/></g><g filter="url(#iO9tzyH)"><ellipse transform="rotate(-27.914 12.131 12.082)" class="cj9wp-dju"/><ellipse fill="url(#igkWvCb)" transform="rotate(-27.914 12.131 12.082)" class="d3k1mgb6o"/></g><path fill="url(#iqCo1Qb)" class="me25wsblg"/><path fill="url(#iE3joKe)" class="me25wsblg"/><path fill="url(#itY6Yje)" class="me25wsblg"/><path fill="url(#i6uzDQb)" class="me25wsblg"/><path fill="url(#iJXxLcd)" class="lm9drebnh"/><path fill="url(#izvwTce)" class="lm9drebnh"/><g filter="url(#i1sUmEe)"><path fill="url(#i5LtGib)" class="pq7o3wbjd"/></g><g filter="url(#ifU0SIb)"><path fill="url(#iQVgode)" class="gckimk9df"/></g><path fill="url(#iBfj5Pd)" class="u7s_8-b4p"/><path fill="url(#ieAjMmb)" class="u7s_8-b4p"/><g filter="url(#iVj9jEc)"><path fill="url(#iodu1md)" class="ogy_uv7sl"/></g><path fill="url(#iQFwsnd)" class="tug1-zpqi"/><path fill="url(#iAJlZRd)" class="tug1-zpqi"/><path fill="url(#iLKj4pc)" class="tug1-zpqi"/><path fill="url(#izLYm6b)" class="tug1-zpqi"/><g filter="url(#iUSmg3E)"><path fill="url(#i8gh6Fe)" class="u7s_8-b4p"/></g><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="iOgfppd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.156)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="iGx7x8c" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.416 66.252)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="i4d8iJd" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .523 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iHdaBGb" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.884)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="izXeBwc" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.544 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iftm7Hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.469)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="i43VwXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iRjyRMt" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.654)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iOeoa4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.782)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i8KloTQ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.969)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iP6c0ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.048 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iY8ko2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.469)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="i7oZ1zb" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.372 20.583)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="il10nec" cx="0" cy="0" r="1" gradientTransform="rotate(158.46 6.492 11.807)scale(2.80546 2.9114)" gradientUnits="userSpaceOnUse"><stop class="egd9hxw0g"/><stop offset="1" class="vuz4rkbkm"/></radialGradient><radialGradient id="ic895Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5045 .1671 -.03048 -.45688 14.29 19.958)" gradientUnits="userSpaceOnUse"><stop class="b29xmhbdx"/><stop offset="1" class="bw2me1bmp"/></radialGradient><radialGradient id="iLW0nln" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.282)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="irOFmTd" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.253)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iPij2KA" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.982)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="iLxtNEV" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.76 15.925)scale(2.55551 2.50931)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="ipOFiCd" cx="0" cy="0" r="1" gradientTransform="matrix(.8321 -.63357 .48552 .63766 28.001 22.854)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="is19MEd" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.118)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="ivMViyT" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i7Ibu8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iZRGmrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ioCxhte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iqZxZRc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.163 21.627)scale(2.40298 2.85456)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="i8QSyxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.64722 .5177 -1.59711 5.08179 8.111 14.808)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iuByYyK" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24919 0 0 -9.28576 18 13.21)" gradientUnits="userSpaceOnUse"><stop class="j8rnoyurk"/><stop offset="1" class="fg9f4nbsa"/></radialGradient><radialGradient id="iKDi3Hc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.63 8.784)scale(3.75862 3.10304)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iLRoxxD" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.1996 -10.9308 0 15.492 7.274)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="heo5qmhso"/><stop offset="1" class="ipa-9-hbq"/></radialGradient><radialGradient id="itZ9y8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28116 1.58544 0 17.599 11.746)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="izW78de" cx="0" cy="0" r="1" gradientTransform="matrix(.00439 -1.22083 1.32856 .00478 12.302 11.798)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iKA7AKd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.123 7.451)scale(9.49744 24.2612)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="imJ0kgd" cx="0" cy="0" r="1" gradientTransform="matrix(3.77737 -3.25376 .9611 1.11577 7.291 10.162)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iF9yD4d" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.995 14.562)scale(2.79855 1.1187)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iGGGiQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9724 -1.86671 0 12.396 12.658)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ic39NVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37084 2.29496 0 13.126 20.096)" gradientUnits="userSpaceOnUse"><stop class="ye8y324wo"/><stop offset="1" class="hzjzh8b4d"/></radialGradient><radialGradient id="isYGO4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.88047 1.47401 0 16.814 20.096)" gradientUnits="userSpaceOnUse"><stop class="ye8y324wo"/><stop offset="1" class="hzjzh8b4d"/></radialGradient><radialGradient id="iNdJTuc" cx="0" cy="0" r="1" gradientTransform="matrix(.6968 3.6875 -9.1476 1.72857 14.92 10.43)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="tcy73gb5z"/><stop offset=".98" class="hk8v_2bpw"/></radialGradient><radialGradient id="iRKfLuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .27233 -.8559 0 15.389 14.73)" gradientUnits="userSpaceOnUse"><stop class="pamu76sks"/><stop offset="1" class="q8-wzobix"/></radialGradient><radialGradient id="izZeSNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88775 .83685 -1.34489 -3.03377 15.518 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iFlJxKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.43434 -1.1968 4.81502 9.794 14.32 17.253)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i1ZRrad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90515 -1.43974 0 17.303 12.189)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="ihXqDkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25874 -.33342 .45904 -.35622 17.048 12.284)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWecRxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9052 -1.43982 0 12.434 12.189)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="igkWvCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00863 -.55123 .6626 -.01037 12.114 12.433)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iE3joKe" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.963 19.303)scale(2.5991 2.47975)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="itY6Yje" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 22.805 -13.669)scale(1.49239 1.25092)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i6uzDQb" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 19.69 -8.374)scale(1.84955 2.47126)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="izvwTce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85004 0 0 -2.06583 9.384 12.92)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i5LtGib" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 4.142 6.861)scale(1.03743 1.06369)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iQFwsnd" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.609)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><linearGradient id="iZmm8Xd" x1="6.988" x2="7.195" y1="29.406" y2="29.406" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iYQZt5g" x1="16.932" x2="14.847" y1="28.545" y2="28.12" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="i90VaHb" x1="16.414" x2="15.153" y1="29.07" y2="29.122" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="idhUOce" x1="11.675" x2="12.612" y1="21.649" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iOkMYsd" x1="18.074" x2="17.137" y1="21.649" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="i9VYgXa" x1="12.219" x2="9.392" y1="26.169" y2="26.806" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iVY5Ecc" x1="9.392" x2="11.086" y1="16.976" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="imEendb" x1="12.268" x2="12.268" y1="29.922" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="iSfw5wd" x1="18.023" x2="21.304" y1="29.125" y2="16.976" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iiIvpQb" x1="17" x2="17.152" y1="26.539" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iz2Begd" x1="26.981" x2="24.992" y1="21.782" y2="21.782" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="iIrRcKb" x1="28.179" x2="23.367" y1="14.344" y2="19.782" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="i93taOc" x1="27.914" x2="23.132" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="a87gyab7w"/></linearGradient><linearGradient id="i8Dhgpc" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iM7Z3Eb" x1="23.614" x2="25.48" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ijkvTob" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i3kHT6d" x1="20.622" x2="17.8" y1="15.091" y2="15.091" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ikCrBfb" x1="15.803" x2="15.055" y1="13.964" y2="14" gradientUnits="userSpaceOnUse"><stop class="r90x3yjbk"/><stop offset="1" class="zmb6ni80l"/></linearGradient><linearGradient id="iSeUXae" x1="14.868" x2="14.868" y1="15.235" y2="14.716" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ij5StRb" x1="14.872" x2="15.074" y1="11.898" y2="13.208" gradientUnits="userSpaceOnUse"><stop offset=".07" class="h_0x0ebit"/><stop offset="1" class="ul6fdxbyg"/></linearGradient><linearGradient id="ii7pBVc" x1="13.528" x2="13.883" y1="16.987" y2="16.056" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iuZe4ne" x1="18.171" x2="17.821" y1="12.249" y2="12.465" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip3YHXd" x1="13.264" x2="12.914" y1="12.249" y2="12.465" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqCo1Qb" x1="22.049" x2="20.703" y1="12.279" y2="14.707" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iJXxLcd" x1="8.342" x2="9.969" y1="13.065" y2="12.922" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iQVgode" x1="20.952" x2="20.952" y1="11.934" y2="13.896" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="izLYm6b" x1="15.508" x2="15.508" y1="5.848" y2="5.985" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="i3fTIqe" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".25"/></filter><filter id="iHyatNb" width="3.106" height="2.966" x="13.406" y="21.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter><filter id="inDTopc" width="4.5" height="2.352" x="12.625" y="19.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.388235 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter><filter id="iZWEs6d" width="8.299" height="13.046" x="5.293" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter><filter id="idI5I0b" width="8.299" height="13.046" x="16.154" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter><filter id="ij2BHIe" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".125"/></filter><filter id="i7vlLrd" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter><filter id="iyKITMc" width="5.277" height="6.052" x="23.132" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter><filter id="i5n1eib" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".05"/></filter><filter id="ioXc0Gb" width="2.262" height=".3" x="23.464" y="26.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".05"/></filter><filter id="ifZ0Zkb" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".05"/></filter><filter id="irD9m1d" width="12.402" height="13.869" x="9.22" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2756" result="effect2_innerShadow_4002_2756"/></filter><filter id="iWy7AOc" width="3.949" height="5.235" x="12.735" y="11.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".5"/></filter><filter id="iwl0EAc" width="2.494" height="3.635" x="13.621" y="11.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".1"/></filter><filter id="ixgqmre" width="2.494" height="3.635" x="13.624" y="11.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".1"/></filter><filter id="iBkZZCb" width="3.991" height="1.597" x="12.873" y="15.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".05"/></filter><filter id="iRd2zGc" width=".855" height=".754" x="16.495" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".05"/></filter><filter id="iTniB8c" width=".948" height=".973" x="17.444" y="11.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".1"/></filter><filter id="iAOecVc" width="1.054" height="1.114" x="12.487" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".1"/></filter><filter id="iO9tzyH" width=".996" height=".763" x="11.633" y="11.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".05"/></filter><filter id="i1sUmEe" width="1.425" height="2.597" x="8.113" y="11.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".125"/></filter><filter id="ifU0SIb" width="1.899" height="2.961" x="20.003" y="11.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2756" stdDeviation=".25"/></filter><filter id="iVj9jEc" width="19.912" height="4.003" x="4.916" y="7.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2756" result="effect2_innerShadow_4002_2756"/></filter><filter id="iUSmg3E" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2756"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:detective-medium" /></template>
<style>
.a38uvfb5u {
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.996");
}

.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a5n2d0brj {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.555 2.727 29.923");
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.a87gyab7w {
  stop-color: var(--svg-color--a57c6f, #A57C6F);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.ah1y65bnf {
  d: path("M9.485 16.296a4.37 4.37 0 0 0 4.336 3.8h2.104a4.37 4.37 0 0 0 4.335-3.8c.132-2.102.264-4.195.362-6.295a1.617 1.617 0 0 0-1.538-1.598H17.52a2.7 2.7 0 0 1-2.467-1.61a.74.74 0 0 0-.687-.467h-1.42c-2.059 0-3.727 1.688-3.727 3.77c0 2.076.13 4.118.265 6.2");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.aygyz2b1y {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.702 19.668l.69 3.215c.1.438.277.746.406.869c.128.123.325.01.407-.06l1.67-1.517l1.669 1.517c.082.07.28.183.408.06s.299-.415.4-.853l.696-3.231h-1.584l-1.59 2.116l-1.588-2.116z");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b29xmhbdx {
  stop-color: var(--svg-color--794d53, #794D53);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
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

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
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

.bw2me1bmp {
  stop-color: var(--svg-color--794d53, #794D53);
  stop-opacity: 0;
}

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c1hl4qc_a {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.536 11.353c.729 0 1.344.503 1.511 1.181c.05.195-.1.38-.298.38h-2.49a.257.257 0 0 1-.253-.303a1.56 1.56 0 0 1 1.53-1.258");
}

.c6vmhn63l {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.996");
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.c9_6a4bgu {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.781c-.097.084-.327.214-.477.07c-.15-.143-.357-.504-.475-1.015");
}

.cej917bjj {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cj9wp-dju {
  cx: 12.131px;
  cy: 12.082px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.435px;
  ry: 0.22px;
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

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.d3k1mgb6o {
  cx: 12.131px;
  cy: 12.082px;
  rx: 0.435px;
  ry: 0.22px;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d84d8gawl {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.42 12.632l-.659 2.051c-.112.422.158.844.54.844h.817c.383 0 .653-.429.54-.844l-.551-2.051c-.118-.454-.563-.454-.687 0");
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.dszt5lbif {
  d: path("m14.098 24.35l-.692-1.334l1.453-1.352l1.453 1.352l-.662 1.33a.15.15 0 0 1-.134.084h-1.285a.15.15 0 0 1-.133-.08");
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

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.egd9hxw0g {
  stop-color: var(--svg-color--9c776e, #9C776E);
}

.eha30-cnn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.232 11.867c.07.095-.078.211-.246.337c-.169.126-.294.215-.365.12c-.07-.095.009-.274.177-.4c.169-.126.363-.151.434-.057");
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.erunfwkci {
  d: path("M17.232 11.867c.07.095-.078.211-.246.337c-.169.126-.294.215-.365.12c-.07-.095.009-.274.177-.4c.169-.126.363-.151.434-.057");
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fg9f4nbsa {
  stop-color: var(--svg-color--8e6362, #8E6362);
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fj1t0bcdc {
  fill: var(--svg-color--000, #000);
  d: path("M13.002 12.653a.57.57 0 0 0-.57-.57a.568.568 0 0 0-.507.832h1.009a.6.6 0 0 0 .068-.262");
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

.fqmktcbay {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.594a2.984 2.984 0 1 0 0-5.968a2.984 2.984 0 0 0 0 5.968");
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gckimk9df {
  d: path("M20.503 13.896q.055-.981.105-1.962c.447.06.794.475.794.977c0 .54-.402.98-.9.985");
}

.gfuyog18w {
  d: path("M27.203 22.328c.58 0 1.055.475 1.055 1.056v2.418h-2.111v-2.418c.01-.58.475-1.056 1.056-1.056");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.h_0x0ebit {
  stop-color: var(--svg-color--6e4948, #6E4948);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.heo5qmhso {
  stop-color: var(--svg-color--986072, #986072);
  stop-opacity: 0;
}

.hk8v_2bpw {
  stop-color: var(--svg-color--744a58, #744A58);
  stop-opacity: 0;
}

.hzjzh8b4d {
  stop-color: var(--svg-color--865c6b, #865C6B);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
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

.ipa-9-hbq {
  stop-color: var(--svg-color--80505f, #80505F);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.is2b6sbzg {
  fill: var(--svg-color--000, #000);
  d: path("M16.735 12.653c0-.317.253-.57.57-.57a.568.568 0 0 1 .507.832h-1.01a.5.5 0 0 1-.067-.262");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j0gwlfbix {
  d: path("M9.445 14.606a1.83 1.83 0 0 1-1.01-.344V15.3c0 .997.594 1.884 1.497 2.253a4.6 4.6 0 0 1-.386-1.317z");
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j8rnoyurk {
  stop-color: var(--svg-color--b78978, #B78978);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k7e504bil {
  cx: 25.695px;
  cy: 17.094px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.kyv7jrdlq {
  d: path("M23.132 24.82c0-.439.355-.8.793-.8h3.023c.724 0 1.31.587 1.31 1.31v3.5c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.434a.8.8 0 0 1-.444-.718");
}

.l4za3cbte {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.555 2.727 29.923");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
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

.lesc7vbsr {
  d: path("M13.342 12.535c0-.321-.262-.536-.333-.6l-.322.31l.198.404z");
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm9drebnh {
  d: path("M9.24 11.132a1.81 1.81 0 0 0-1.552 1.783c0 .958.75 1.741 1.696 1.792a87 87 0 0 1-.143-3.575");
}

.m3lt9upxo {
  d: path("m14.445 12.239l-.593 2.05c-.12.423.17.845.581.845h.877c.412 0 .702-.429.581-.844l-.593-2.051c-.127-.454-.72-.454-.853 0");
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.me25wsblg {
  d: path("M20.36 14.707q.111-1.78.205-3.56a1.796 1.796 0 0 1-.206 3.56");
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mfwn3ipub {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 11.353c-.728 0-1.343.503-1.51 1.182c-.05.194.099.38.298.38h2.49a.257.257 0 0 0 .253-.303a1.56 1.56 0 0 0-1.53-1.259");
}

.mh3eme4ib {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.868 16.443a3.35 3.35 0 0 1-1.545-.367c-.153-.078-.317.095-.221.233a2.11 2.11 0 0 0 1.766.944c.742 0 1.393-.377 1.767-.944c.096-.144-.068-.31-.221-.233a3.3 3.3 0 0 1-1.546.367Z");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.o872acc1u {
  fill: var(--svg-color--8f6361, #8F6361);
  d: path("m14.442 12.414l-.593 2.05c-.121.423.17.845.58.845h.878c.411 0 .702-.429.58-.844l-.592-2.051c-.127-.455-.72-.455-.853 0");
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ogy_uv7sl {
  d: path("M6.386 7.88c-.26-.016-.991.034-1.316.359c-.357.357-.055 1.073.508 1.652c.539.555 2.335 1.738 5.18 1.738h8.167c2.874 0 4.689-1.183 5.234-1.738c.568-.579.874-1.295.513-1.652c-.328-.325-1.067-.375-1.33-.36z");
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.pamu76sks {
  stop-color: var(--svg-color--ab867c, #AB867C);
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq7o3wbjd {
  d: path("M9.195 11.874a1.066 1.066 0 0 0 .093 2.097q-.06-1.049-.093-2.097");
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.pyz2txsgl {
  d: path("M20.292 14.606a1.83 1.83 0 0 0 1.009-.344V15.3c0 .997-.594 1.884-1.496 2.253q.286-.609.386-1.317z");
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q5f971bhv {
  d: path("M17.305 11.657a.996.996 0 0 1 .96 1.258H16.34a1 1 0 0 1 .964-1.258");
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q8-wzobix {
  stop-color: var(--svg-color--ab867c, #AB867C);
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

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r90x3yjbk {
  stop-color: var(--svg-color--aa8575, #AA8575);
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rc34chbjr {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1571 1571 0 0 1-4.625-7.734c-.422-.735-.219-.907-.14-1.032s.375-.36.671-.468c.238-.088.329-.204.344-.25c.057-.068.069-.3-.344-.688c-.412-.387-1.307-1.068-1.703-1.36c-.234-.187-.651-.609-.601-.984s.65-.435.765-.43z");
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
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

.t9v2librs {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
}

.tcy73gb5z {
  stop-color: var(--svg-color--684544, #684544);
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

.tug1-zpqi {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.131h13.287a.1.1 0 0 0 .094-.133l-.192-.559l-.429-1.245a.1.1 0 0 0-.094-.067H8.829a.1.1 0 0 0-.094.068c-.19.553-.38 1.12-.532 1.574z");
}

.u7s_8-b4p {
  d: path("M8.804 5.743a.1.1 0 0 0 .094.132h11.92a.1.1 0 0 0 .094-.132a86 86 0 0 0-.639-1.79c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567q-.103.067-.194.121c-.578.344-.808.398-1.277.398c-.37 0-.761-.148-1.183-.367a5 5 0 0 1-.248-.142c-.436-.26-1.078-.642-1.905-.526c-.956.135-1.66.93-2.097 1.946a29 29 0 0 0-.618 1.668");
}

.uc4cnoe_k {
  d: path("M14.868 16.443a3.35 3.35 0 0 1-1.545-.367c-.153-.078-.317.095-.221.233a2.11 2.11 0 0 0 1.766.944c.742 0 1.393-.377 1.767-.944c.096-.144-.068-.31-.221-.233a3.3 3.3 0 0 1-1.546.367");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ul6fdxbyg {
  stop-color: var(--svg-color--7e535d, #7E535D);
  stop-opacity: 0;
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vi7fu79ul {
  d: path("m13.289 29.922l.854-5.408a.1.1 0 0 1 .098-.084h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.vuz4rkbkm {
  stop-color: var(--svg-color--87545f, #87545F);
}

.vw12-pbuc {
  d: path("m18.996 16.977l-2.742 12.945h1.796c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.22-.907.141-1.032c-.078-.125-.375-.36-.672-.468c-.237-.088-.328-.204-.344-.25c-.057-.068-.068-.3.344-.688c.413-.387 1.307-1.068 1.703-1.36c.235-.187.652-.609.602-.984s-.651-.435-.766-.43z");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w__zc_1bz {
  d: path("m14.442 12.414l-.593 2.05c-.121.423.17.845.58.845h.878c.411 0 .702-.429.58-.844l-.592-2.051c-.127-.455-.72-.455-.853 0");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
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

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xh75albmj {
  d: path("M12.432 11.657a.996.996 0 0 0-.96 1.258h1.924q.034-.128.036-.263a1.003 1.003 0 0 0-1-.995");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xxcw8_bas {
  d: path("M12.625 19.547c.026.292.262.988.999 1.438c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.252-.664c.736-.45.973-1.146.999-1.438z");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.ye8y324wo {
  stop-color: var(--svg-color--865c6b, #865C6B);
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yobikpp-q {
  d: path("M18.192 12.521a.94.94 0 0 0-.258-.516l-.29.318l.13.255z");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.zmb6ni80l {
  stop-color: var(--svg-color--aa8575, #AA8575);
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

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
