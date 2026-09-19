<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#imFnRXd)"><path fill="url(#i6aJFZY)" class="ocwvddb0y"/><path fill="url(#izDA0dI)" class="ocwvddb0y"/></g><g filter="url(#ipJEzPV)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#i2atLEe)"><ellipse transform="rotate(-40.534 9.937 22.243)" class="si-u7d6wp"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#i63CpBd)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.954 40.982)" class="tto44ccna"/><g filter="url(#iqZfAId)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#ifOw8lB)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iGZL3eg)"><circle class="a1tpsrb8u"/></g><g filter="url(#ivUVhHv)"><circle class="wfn54lnxd"/></g><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><path fill="url(#i6IEJCb)" class="d_xkqubif"/><path fill="url(#iRiKzGN)" class="qif-q1dzp"/><g filter="url(#iAq3jwi)"><path fill="url(#icFhbId)" class="v2ie1cchc"/><path fill="url(#i1g9CND)" class="v2ie1cchc"/></g><path fill="url(#iV806Lc)" class="v2ie1cchc"/><path fill="url(#iynf6Mc)" class="v2ie1cchc"/><path fill="url(#iNV2Cdc)" class="v2ie1cchc"/><path fill="url(#iG7tzfb)" class="v2ie1cchc"/><path fill="url(#ienixOd)" class="v2ie1cchc"/><path fill="url(#i4thmld)" class="v2ie1cchc"/><path fill="url(#irmDolc)" class="v2ie1cchc"/><path fill="url(#iB4rnbe)" class="v2ie1cchc"/><path fill="url(#ifT8mkh)" class="v2ie1cchc"/><g filter="url(#iudXAyb)"><path class="mrpi1bbbs"/></g><g filter="url(#iLTSiWT)"><path class="zjs87k7dw"/><path fill="url(#ipJI4jc)" class="ni1jufo3h"/><path fill="url(#iIyWTqb)" class="ni1jufo3h"/><path fill="url(#iq768Qb)" class="ni1jufo3h"/><path fill="url(#ikF0FQc)" class="ni1jufo3h"/></g><g filter="url(#i73SpCb)"><path fill="url(#idRxpOi)" class="tl2tq_b9s"/></g><g filter="url(#iu7kpiA)"><path stroke="url(#i4tYcCx)" class="jhifxobna"/></g><path fill="url(#ic2Yt8d)" class="up8ej4b0f"/><path class="jzcion38k"/><path fill="url(#irYzvXd)" class="tvvcl4hsp"/><path class="lxvq6gbjj"/><g filter="url(#itzEr2d)"><path class="rlelt4bjj"/><path fill="url(#iazN0Qc)" class="x1514rzpa"/></g><g filter="url(#i9egzye)"><path fill="url(#i3kfbof)" class="qy3_sgb1v"/></g><path class="ey8qzh7kr"/><path fill="url(#i57zPye)" class="bw9ww8b8y"/><path class="tyejhgbno"/><g filter="url(#iEL2q7c)"><path fill="url(#itekzle)" class="x7tv69v-d"/></g><g filter="url(#ilrzJEX)"><ellipse transform="rotate(-27.914 13.547 14.41)" class="q73ebkbcg"/><ellipse fill="url(#iZRTFcd)" transform="rotate(-27.914 13.547 14.41)" class="qo0nrbcrw"/></g><path fill="url(#iPtT6Pb)" class="lzb2gvb3g"/><path fill="url(#ive4VzB)" class="lzb2gvb3g"/><path fill="url(#iLrTwQc)" class="lzb2gvb3g"/><path fill="url(#iHkPrIc)" class="lzb2gvb3g"/><path fill="url(#iawOBze)" class="y2-plxkkc"/><path fill="url(#iUcihMb)" class="y2-plxkkc"/><g filter="url(#iste1te)"><path fill="url(#iVYhc6i)" class="yea85ieen"/></g><g filter="url(#ixxCvwb)"><path fill="url(#ilbC3oc)" class="ws67ph6op"/></g><g filter="url(#iF5zhfo)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#ioAZBKb)"><path fill="url(#iU1wwRb)" class="u17l1bw1n"/><path fill="url(#i7n11Wc)" class="u17l1bw1n"/><path fill="url(#iyBJvOb)" class="u17l1bw1n"/></g><defs><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="ifOw8lB" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="ujpokubdf"/><stop offset="1" class="op1k02bbd"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="i6IEJCb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -1.383 23.096)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iRiKzGN" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.943 16.853)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="icFhbId" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.808 15.422)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i1g9CND" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.269 10.417)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iynf6Mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 17.581 9.508)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="iNV2Cdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.447 14.109)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iG7tzfb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.953 .203)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="ienixOd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.458 8.511)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i4thmld" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.208 12.689)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="irmDolc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.08 16.06)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iB4rnbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.784 14.926)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iIyWTqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.466 16.782)" gradientUnits="userSpaceOnUse"><stop class="y3t_2qtwt"/><stop offset="1" class="wt5y_6nqn"/></radialGradient><radialGradient id="ikF0FQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.582 16.213)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="ic2Yt8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.509 19.045)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="irYzvXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17408 1.6093 0 18.182 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="tcnu-pxmv"/><stop offset=".887" class="kg92xobxe"/></radialGradient><radialGradient id="iazN0Qc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.55 2.898)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i57zPye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17414 1.60939 0 13.818 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="tcnu-pxmv"/><stop offset=".887" class="kg92xobxe"/></radialGradient><radialGradient id="iZRTFcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.531 14.725)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ive4VzB" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.618 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iLrTwQc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.978 15.064)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iHkPrIc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.092 15.236)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iUcihMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.085 15.16)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iVYhc6i" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.086 15.164)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iV806Lc" x1="21.157" x2="18.628" y1="17.107" y2="17.107" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ifT8mkh" x1="16.047" x2="16.047" y1="14.091" y2="15.216" gradientUnits="userSpaceOnUse"><stop class="f_s43_06n"/><stop offset="1" class="gaie_kbxo"/></linearGradient><linearGradient id="ipJI4jc" x1="16.838" x2="16" y1="16.096" y2="16.169" gradientUnits="userSpaceOnUse"><stop class="y3t_2qtwt"/><stop offset="1" class="wt5y_6nqn"/></linearGradient><linearGradient id="iq768Qb" x1="16" x2="16" y1="17.236" y2="16.771" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="idRxpOi" x1="16" x2="16.279" y1="14.277" y2="15.888" gradientUnits="userSpaceOnUse"><stop class="rq8hgj5ew"/><stop offset="1" class="s92fwlbtn"/></linearGradient><linearGradient id="i4tYcCx" x1="14.798" x2="15.117" y1="18.806" y2="17.972" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="i3kfbof" x1="18.96" x2="18.646" y1="14.559" y2="14.753" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itekzle" x1="14.562" x2="14.248" y1="14.559" y2="14.752" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPtT6Pb" x1="22.436" x2="21.23" y1="14.586" y2="16.762" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iawOBze" x1="10.15" x2="11.608" y1="15.29" y2="15.163" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ilbC3oc" x1="21.453" x2="21.453" y1="14.277" y2="16.035" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="i7n11Wc" x1="15.94" x2="15.94" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient><filter id="imFnRXd" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2843"/></filter><filter id="ipJEzPV" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2843" result="effect2_innerShadow_4002_2843"/></filter><filter id="i2atLEe" width="2.189" height="2.153" x="8.842" y="21.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".25"/></filter><filter id="i63CpBd" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".125"/></filter><filter id="iqZfAId" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2843" result="effect2_innerShadow_4002_2843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2843" result="effect3_innerShadow_4002_2843"/></filter><filter id="iGZL3eg" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".25"/></filter><filter id="ivUVhHv" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".25"/></filter><filter id="iAq3jwi" width="11.62" height="12.842" x="10.537" y="8.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2843" result="effect2_innerShadow_4002_2843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy="-.5"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.278431 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2843" result="effect3_innerShadow_4002_2843"/></filter><filter id="iudXAyb" width="3.747" height="4.9" x="13.985" y="13.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".5"/></filter><filter id="iLTSiWT" width="2.277" height="3.3" x="14.861" y="14.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".1"/></filter><filter id="i73SpCb" width="2.277" height="3.3" x="14.861" y="14.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".1"/></filter><filter id="iu7kpiA" width="3.718" height="1.573" x="14.141" y="17.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".05"/></filter><filter id="itzEr2d" width=".787" height=".696" x="17.448" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".05"/></filter><filter id="i9egzye" width=".891" height=".913" x="18.288" y="14.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".1"/></filter><filter id="iEL2q7c" width=".986" height="1.04" x="13.845" y="14.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".1"/></filter><filter id="ilrzJEX" width=".913" height=".705" x="13.09" y="14.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".05"/></filter><filter id="iste1te" width="1.329" height="2.379" x="9.919" y="13.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".125"/></filter><filter id="ixxCvwb" width="1.806" height="2.758" x="20.55" y="13.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2843" stdDeviation=".25"/></filter><filter id="iF5zhfo" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2843"/></filter><filter id="ioAZBKb" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2843"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:guard-medium" /></template>
<style>
.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.bw9ww8b8y {
  d: path("M13.816 14.029a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.d_xkqubif {
  d: path("M20.861 16.672c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.ey8qzh7kr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.61 13.757c-.654 0-1.206.45-1.356 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.f_s43_06n {
  stop-color: var(--svg-color--814d56, #814D56);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.gaie_kbxo {
  stop-color: var(--svg-color--956a63, #956A63);
  stop-opacity: 0;
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gw4u-ub3u {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.004-.008l.02-.04c.061-.121.152-.298-.02-.578c-.193-.313-.375-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.07-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.066-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.452-.58c.046-.215.132-.502.293-.663a1.06 1.06 0 0 1 .791-.3c.257.007.535-.03.752-.254c.217-.225.458-.413.699-.453s.471.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112c.098 0 .214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.484-.184.725-.144s.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.246.448.292.663c.088.417.243.491.452.58l.02.008c.219.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.117.86c.33.641.193.955 0 1.268c-.171.28-.081.457-.02.577l.02.041l.005.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.gx_0zqbtq {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.099px;
  rx: 1.969px;
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jhifxobna {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.65 17.923h-.002a.23.23 0 0 0-.27.047a.21.21 0 0 0-.024.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.203-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.jzcion38k {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.39 13.757c.654 0 1.206.45 1.356 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.kg92xobxe {
  stop-color: var(--svg-color--4a2d33, #4A2D33);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lxvq6gbjj {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 14.921c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.lzb2gvb3g {
  d: path("M20.922 16.762q.101-1.596.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mrpi1bbbs {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.599 14.903l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.407-.504-.407-.615 0");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.ni1jufo3h {
  d: path("m15.618 14.707l-.532 1.838c-.108.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ocwvddb0y {
  d: path("M11.926 20.161c-1.364.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .704.02a12.3 12.3 0 0 1 3.107-1.857z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.op1k02bbd {
  stop-color: var(--svg-color--ac7879, #AC7879);
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q73ebkbcg {
  cx: 13.547px;
  cy: 14.41px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qif-q1dzp {
  d: path("M11.139 16.672a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qo0nrbcrw {
  cx: 13.547px;
  cy: 14.41px;
  rx: 0.39px;
  ry: 0.197px;
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qy3_sgb1v {
  d: path("M18.979 14.803a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rlelt4bjj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 14.217c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.rq8hgj5ew {
  stop-color: var(--svg-color--87545a, #87545A);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.s92fwlbtn {
  stop-color: var(--svg-color--87545a, #87545A);
  stop-opacity: 0;
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.si-u7d6wp {
  cx: 9.937px;
  cy: 22.243px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.sy7gbya4q {
  d: path("M22.942 29.911h3.63a9.98 9.98 0 0 0-3.63-7.355z");
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.tcnu-pxmv {
  stop-color: var(--svg-color--734b48, #734B48);
}

.tl2tq_b9s {
  d: path("m15.618 14.583l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.765 0");
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvvcl4hsp {
  d: path("M18.184 14.029a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.twe7w31pl {
  stop-color: var(--svg-color--c9b0d8, #C9B0D8);
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.tyejhgbno {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 14.921a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.u17l1bw1n {
  d: path("m10.5 14.156l.12 3.518c.082 2.424 2.07 4.378 4.497 4.378h1.677c2.44 0 4.435-1.976 4.498-4.416l.09-3.48h-.909l-.12 3.48c-.049 1.898-1.662 3.486-3.56 3.486h-1.676c-1.887 0-3.489-1.597-3.553-3.482l-.09-3.485z");
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ujpokubdf {
  stop-color: var(--svg-color--955268, #955268);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.up8ej4b0f {
  d: path("M16 18.318c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v2ie1cchc {
  d: path("M11.175 18.187a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.556");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wfn54lnxd {
  cx: 17.439px;
  cy: 25.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.ws67ph6op {
  d: path("M21.05 16.035q.05-.879.095-1.758c.4.054.711.426.711.876c0 .484-.36.878-.806.882");
}

.wt5y_6nqn {
  stop-color: var(--svg-color--bd957f, #BD957F);
  stop-opacity: 0;
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x1514rzpa {
  d: path("M18.118 14.217c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.x7tv69v-d {
  d: path("M14.631 14.816c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y2-plxkkc {
  d: path("M10.956 13.558a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.y3t_2qtwt {
  stop-color: var(--svg-color--bd957f, #BD957F);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yea85ieen {
  d: path("M10.915 14.223a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.zjs87k7dw {
  fill: var(--svg-color--946763, #946763);
  d: path("m15.618 14.707l-.532 1.838c-.108.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
