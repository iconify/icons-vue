<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="j_dulcbnt"/><path fill="url(#iAlKUYw)" class="ng-28zxwb"/><path fill="url(#itbtQzd)" class="ng-28zxwb"/><path fill="url(#iOhOn5b)" class="ng-28zxwb"/><path fill="url(#i8ngfnv)" class="ng-28zxwb"/><path fill="url(#iWXDRFe)" class="ng-28zxwb"/><path class="em148031i"/><path fill="url(#iAomAlC)" class="tnef9wrdf"/><path fill="url(#ig9e68k)" class="tnef9wrdf"/><path fill="url(#iB0vApd)" class="tnef9wrdf"/><g filter="url(#ifp1Fud)"><path class="qk9vqlbuc"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#im8Vkvd)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iWKZSod)" class="by194g1ei"/><path fill="url(#idsRMlc)" class="by194g1ei"/><g filter="url(#ieHv9nc)"><path fill="url(#iV17Npc)" class="gemgotgww"/></g><path fill="url(#iOeoa4b)" class="zswbabceh"/><path fill="url(#im9eHqM)" class="zswbabceh"/><path fill="url(#iTudamq)" class="zswbabceh"/><path fill="url(#iEbPnCK)" class="wibdzhbon"/><path fill="url(#itSm4AK)" class="wibdzhbon"/><path fill="url(#iEpqGnc)" class="wibdzhbon"/><path fill="url(#iHu3LFd)" class="wibdzhbon"/><path fill="url(#iP6c0ue)" class="wibdzhbon"/><path class="yyxxh9qfh"/><path fill="url(#iyKMIle)" class="s0-op-jbm"/><path fill="url(#iC6TSsc)" class="s0-op-jbm"/><path fill="url(#i7oZ1zb)" class="s0-op-jbm"/><path fill="url(#ira2lKd)" class="s0-op-jbm"/><path fill="url(#iknlR1o)" class="s0-op-jbm"/><g filter="url(#i91O7Vc)"><path fill="url(#ioyeKve)" class="xxcw8_bas"/><path fill="url(#iitK3EU)" class="xxcw8_bas"/></g><g filter="url(#iPazqiH)"><path fill="url(#iimzjsu)" class="irpqnktdz"/><path fill="url(#iv8hTQc)" class="irpqnktdz"/><path fill="url(#iMAGDRc)" class="irpqnktdz"/><path fill="url(#i2jMWwb)" class="irpqnktdz"/><path fill="url(#irOFmTd)" class="irpqnktdz"/></g><g filter="url(#iADX9Cc)"><path fill="url(#i1VflDU)" class="my_84zz7a"/><path fill="url(#iEAfnnc)" class="my_84zz7a"/><path fill="url(#isUiL6c)" class="my_84zz7a"/><path fill="url(#iVjF54c)" class="my_84zz7a"/></g><path fill="url(#ivSwZae)" class="rhxl5gb9p"/><path fill="url(#iax88fe)" class="rhxl5gb9p"/><rect fill="url(#iz2Begd)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#iScb2Mb)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#iJfkz9d)"><path fill="url(#iIrRcKb)" clip-rule="evenodd" class="nhkngdbxa"/></g><rect fill="url(#ihSbEiX)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#iAtbPFj)"><path fill="url(#iwT1FQb)" class="gen1zebho"/><path fill="url(#i6It0Mc)" class="gen1zebho"/><path fill="url(#iRDJC0b)" class="gen1zebho"/><path fill="url(#isG2Jnb)" class="gen1zebho"/><path fill="url(#iptqFYb)" class="gen1zebho"/></g><path fill="url(#i5J2GDd)" class="gen1zebho"/><g filter="url(#iYV4Mod)"><path stroke="url(#iep2WYd)" class="fkavrburz"/></g><g filter="url(#iFmbtlB)"><path stroke="url(#i0UPD0b)" class="tnviirb6b"/></g><g filter="url(#ic4J9xb)"><path stroke="url(#iaOTrJt)" class="bc7i0ongh"/></g><path fill="url(#i0QHFPd)" class="x62u6rbbl"/><path fill="url(#iIB3GWd)" class="pwmv9bc_x"/><g filter="url(#iipSjWd)"><path fill="url(#ikzgTDd)" class="j_tdxuvbh"/></g><path fill="url(#iExxXcd)" class="j_tdxuvbh"/><path fill="url(#ilrccee)" class="j_tdxuvbh"/><path fill="url(#ii145hW)" class="j_tdxuvbh"/><path fill="url(#i7AzMIP)" class="j_tdxuvbh"/><path fill="url(#ijF2MIb)" class="j_tdxuvbh"/><path fill="url(#iUaJrJc)" class="j_tdxuvbh"/><path fill="url(#irLdrMb)" class="j_tdxuvbh"/><path fill="url(#i1K2Koe)" class="j_tdxuvbh"/><g filter="url(#iE3BN4m)"><path class="m2ipc1ljc"/></g><g filter="url(#i55tyzb)"><path class="m9m0e1btb"/><path fill="url(#iE09j2b)" class="lpown5iec"/><path fill="url(#iHe6Z9b)" class="lpown5iec"/><path fill="url(#ixiKTMc)" class="lpown5iec"/><path fill="url(#i8p7Qmd)" class="lpown5iec"/></g><g filter="url(#iVU4ljg)"><path fill="url(#iJHO8Tc)" class="s373i_baj"/></g><g filter="url(#i2ML98S)"><path stroke="url(#iw6NBIc)" class="shl7c6jiw"/></g><path fill="url(#iZGLUYb)" class="zx0jjr-cz"/><path class="l3_hdyrbm"/><path fill="url(#iS7Emcc)" class="to1bhjtdn"/><path class="gs8utbrbr"/><g filter="url(#iLQUBuc)"><path class="ok6g0xb6f"/><path fill="url(#iEfcDzd)" class="wtpc7f2sj"/></g><g filter="url(#iq0oMLc)"><path fill="url(#i2FO93c)" class="i7gh54b0a"/></g><path class="hbm_ekbec"/><path fill="url(#i7eRVfS)" class="mx43wwh9a"/><path class="jz_gcmb9c"/><g filter="url(#ivfIJGE)"><path fill="url(#iLjdYkc)" class="ffsvqobcl"/></g><g filter="url(#iRgPKdd)"><ellipse transform="rotate(-27.914 12.114 12.082)" class="ctmxvjb_b"/><ellipse fill="url(#iHPnSQb)" transform="rotate(-27.914 12.114 12.082)" class="fd42wabnp"/></g><path fill="url(#iDaio9b)" class="a9cgrmb3b"/><path fill="url(#iOoZwbc)" class="a9cgrmb3b"/><path fill="url(#i9LImkG)" class="a9cgrmb3b"/><path fill="url(#iSLaGie)" class="a9cgrmb3b"/><path fill="url(#iJm7aAb)" class="isisf50au"/><path fill="url(#iStyMec)" class="isisf50au"/><g filter="url(#i1kG6IC)"><path fill="url(#iCq36Ac)" class="snlr3-apx"/></g><g filter="url(#iSmu0vL)"><path fill="url(#i3qIEOb)" class="g8qsq388j"/></g><path fill="url(#iBfj5Pd)" class="u29lq70aj"/><path fill="url(#ieAjMmb)" class="u29lq70aj"/><g filter="url(#i0aelmd)"><path fill="url(#iodu1md)" class="jsq1u4rsj"/></g><path fill="url(#iTUCPGc)" class="mf9pttgpg"/><path fill="url(#iAJlZRd)" class="mf9pttgpg"/><path fill="url(#iLKj4pc)" class="mf9pttgpg"/><path fill="url(#izLYm6b)" class="mf9pttgpg"/><g filter="url(#iwvxLlb)"><path fill="url(#i8gh6Fe)" class="u29lq70aj"/></g><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="i8ngfnv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.157)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="iWXDRFe" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.417 66.252)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="ig9e68k" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .522 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iB0vApd" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.885)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="im8Vkvd" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.545 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iWKZSod" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.47)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="idsRMlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.921)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iV17Npc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.655)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iOeoa4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.782)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="iEbPnCK" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.97)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iP6c0ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.048 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iyKMIle" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.47)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="i7oZ1zb" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.372 20.583)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="ioyeKve" cx="0" cy="0" r="1" gradientTransform="rotate(158.46 6.492 11.808)scale(2.80546 2.9114)" gradientUnits="userSpaceOnUse"><stop class="fcv3pabxt"/><stop offset="1" class="ehjxjubwn"/></radialGradient><radialGradient id="iitK3EU" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5045 .1671 -.03048 -.45688 14.29 19.959)" gradientUnits="userSpaceOnUse"><stop class="z-xw_ccte"/><stop offset="1" class="z5z3i6nzk"/></radialGradient><radialGradient id="iMAGDRc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.283)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="irOFmTd" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.253)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iVjF54c" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.983)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="ivSwZae" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 11.774 14.943)scale(2.5843 2.53551)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="fwxdqq60h"/><stop offset="1" class="sn5q5zbjv"/></radialGradient><radialGradient id="iax88fe" cx="0" cy="0" r="1" gradientTransform="matrix(.88698 -.597 .4575 .67972 28.125 22.694)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wa3u08nda"/><stop offset="1" class="aszpk2bre"/><stop offset="1" class="f-jevn7df"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="ihSbEiX" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.119)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="i6It0Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.797)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iRDJC0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="isG2Jnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iptqFYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i0QHFPd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.172 21.615)scale(2.40294 2.85451)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iIB3GWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6472 .51769 -1.5971 5.0817 8.094 14.809)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="ikzgTDd" cx="0" cy="0" r="1" gradientTransform="rotate(163.27 7.948 8.28)scale(6.13441 5.94046)" gradientUnits="userSpaceOnUse"><stop class="t-4zdpbuy"/><stop offset=".951" class="j5q_9nbdn"/></radialGradient><radialGradient id="ilrccee" cx="0" cy="0" r="1" gradientTransform="rotate(95.44 5.234 10.716)scale(13.8436 17.3036)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="z_8rtmb_y"/><stop offset=".994" class="nzt6epbxo"/></radialGradient><radialGradient id="ii145hW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28114 1.58541 0 17.581 11.747)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="i7AzMIP" cx="0" cy="0" r="1" gradientTransform="matrix(.00439 -1.22081 1.32853 .00477 12.285 11.799)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="ijF2MIb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.47842 .59832 -1.52842 -24.2126 18.681 14.314)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iUaJrJc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.611 14.11 -5.965)scale(5.03198 1.84206)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="irLdrMb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.62 8.78)scale(3.75856 3.10299)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="i1K2Koe" cx="0" cy="0" r="1" gradientTransform="rotate(80.461 .734 13.895)scale(3.55371 9.35909)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="hxowi5i8i"/><stop offset="1" class="qprdntb3r"/></radialGradient><radialGradient id="iHe6Z9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .27233 -.8559 0 15.371 14.73)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="tvpehoh0i"/><stop offset="1" class="o8vvrqzqj"/></radialGradient><radialGradient id="i8p7Qmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69704 .77808 -1.25043 -2.72729 15.501 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iZGLUYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.80408 3.23502 0 14.851 17.16)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iS7Emcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90514 -1.43972 0 17.286 12.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iEfcDzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25873 -.33341 .45904 -.35622 17.03 12.283)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7eRVfS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90518 -1.43979 0 12.417 12.189)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iHPnSQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00863 -.55122 .66259 -.01037 12.098 12.434)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOoZwbc" cx="0" cy="0" r="1" gradientTransform="matrix(.70123 2.50268 -2.38775 .66903 20.003 12.205)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="i9LImkG" cx="0" cy="0" r="1" gradientTransform="matrix(.87888 -1.20612 1.01097 .73668 20.405 12.812)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iSLaGie" cx="0" cy="0" r="1" gradientTransform="matrix(.65487 -1.7297 2.31112 .875 20.532 13.005)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iStyMec" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.077 6.176)scale(1.81309 1.94627)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iCq36Ac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02246 .1755 -.21536 -1.25461 9.369 12.923)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iTUCPGc" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.61)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><linearGradient id="iOhOn5b" x1="6.988" x2="7.195" y1="29.407" y2="29.407" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iAomAlC" x1="16.932" x2="14.847" y1="28.546" y2="28.12" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="iTudamq" x1="16.414" x2="15.153" y1="29.07" y2="29.123" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="itSm4AK" x1="11.675" x2="12.612" y1="21.65" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iC6TSsc" x1="18.074" x2="17.137" y1="21.65" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iimzjsu" x1="12.219" x2="9.392" y1="26.17" y2="26.807" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iv8hTQc" x1="9.392" x2="11.086" y1="16.977" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="i2jMWwb" x1="12.268" x2="12.268" y1="29.922" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="i1VflDU" x1="18.023" x2="21.304" y1="29.125" y2="16.977" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iEAfnnc" x1="17" x2="17.152" y1="26.539" y2="26.571" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iz2Begd" x1="26.981" x2="24.992" y1="21.782" y2="21.782" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="iIrRcKb" x1="28.179" x2="23.367" y1="14.344" y2="19.782" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="iwT1FQb" x1="27.914" x2="23.132" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop offset=".146" class="g5msifdtf"/><stop offset=".861" class="s1a3ngbhp"/></linearGradient><linearGradient id="i5J2GDd" x1="28.654" x2="26.027" y1="28.118" y2="28.118" gradientUnits="userSpaceOnUse"><stop class="x0n4s-bkb"/><stop offset="1" class="runotir-h"/></linearGradient><linearGradient id="iep2WYd" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i0UPD0b" x1="23.614" x2="25.48" y1="27.034" y2="27.034" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iaOTrJt" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iExxXcd" x1="20.605" x2="15.749" y1="15.092" y2="15.092" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iE09j2b" x1="15.641" x2="14.992" y1="13.943" y2="13.982" gradientUnits="userSpaceOnUse"><stop class="v5h3xspgo"/><stop offset="1" class="oyglz-bkk"/></linearGradient><linearGradient id="ixiKTMc" x1="14.851" x2="14.851" y1="15.235" y2="14.716" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iJHO8Tc" x1="14.637" x2="14.851" y1="12.107" y2="13.579" gradientUnits="userSpaceOnUse"><stop class="otu1-6baj"/><stop offset=".871" class="xo0ziebaz"/></linearGradient><linearGradient id="iw6NBIc" x1="13.511" x2="13.866" y1="16.988" y2="16.057" gradientUnits="userSpaceOnUse"><stop class="f8yp1suiv"/><stop offset="1" class="urft54bsg"/></linearGradient><linearGradient id="i2FO93c" x1="18.154" x2="17.804" y1="12.249" y2="12.465" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLjdYkc" x1="13.247" x2="12.897" y1="12.249" y2="12.465" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDaio9b" x1="22.032" x2="20.686" y1="12.279" y2="14.707" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iJm7aAb" x1="8.325" x2="9.952" y1="13.065" y2="12.923" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="i3qIEOb" x1="20.964" x2="20.964" y1="11.865" y2="13.989" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="izLYm6b" x1="15.508" x2="15.508" y1="5.848" y2="5.985" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="ifp1Fud" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".25"/></filter><filter id="ieHv9nc" width="3.106" height="2.966" x="13.406" y="21.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter><filter id="i91O7Vc" width="4.5" height="2.352" x="12.625" y="19.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.513726 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter><filter id="iPazqiH" width="8.299" height="13.046" x="5.293" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter><filter id="iADX9Cc" width="8.299" height="13.046" x="16.154" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter><filter id="iScb2Mb" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".125"/></filter><filter id="iJfkz9d" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter><filter id="iAtbPFj" width="5.327" height="6.052" x="23.132" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.52549 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter><filter id="iYV4Mod" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".05"/></filter><filter id="iFmbtlB" width="2.262" height=".3" x="23.464" y="26.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".05"/></filter><filter id="ic4J9xb" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".05"/></filter><filter id="iipSjWd" width="12.402" height="13.969" x="9.203" y="6.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2762" result="effect2_innerShadow_4002_2762"/></filter><filter id="iE3BN4m" width="3.949" height="5.235" x="12.719" y="11.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".5"/></filter><filter id="i55tyzb" width="2.494" height="3.635" x="13.604" y="11.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.560784 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/><feGaussianBlur result="effect2_foregroundBlur_4002_2762" stdDeviation=".1"/></filter><filter id="iVU4ljg" width="2.494" height="3.635" x="13.604" y="11.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".1"/></filter><filter id="i2ML98S" width="3.99" height="1.597" x="12.856" y="15.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".05"/></filter><filter id="iLQUBuc" width=".855" height=".754" x="16.478" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".05"/></filter><filter id="iq0oMLc" width=".948" height=".973" x="17.427" y="11.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".1"/></filter><filter id="ivfIJGE" width="1.054" height="1.114" x="12.47" y="11.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".1"/></filter><filter id="iRgPKdd" width=".996" height=".763" x="11.617" y="11.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".05"/></filter><filter id="i1kG6IC" width="1.425" height="2.597" x="8.096" y="11.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".125"/></filter><filter id="iSmu0vL" width="2.056" height="3.123" x="19.936" y="11.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2762" stdDeviation=".25"/></filter><filter id="i0aelmd" width="19.912" height="4.003" x="4.916" y="7.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2762" result="effect2_innerShadow_4002_2762"/></filter><filter id="iwvxLlb" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2762"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:detective-light" /></template>
<style>
.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.a9cgrmb3b {
  d: path("M20.342 14.707q.113-1.78.206-3.56a1.796 1.796 0 0 1-.206 3.56");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
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

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
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

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
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

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.ehjxjubwn {
  stop-color: var(--svg-color--b57a77, #B57A77);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.em148031i {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.294l-2.281 10.862z");
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.f-jevn7df {
  stop-color: var(--svg-color--ffdfc5, #FFDFC5);
  stop-opacity: 0;
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.f8yp1suiv {
  stop-color: var(--svg-color--dba8a1, #DBA8A1);
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

.ffsvqobcl {
  d: path("M13.324 12.536c0-.322-.261-.537-.332-.601l-.322.31l.198.404z");
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

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
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

.fwxdqq60h {
  stop-color: var(--svg-color--fbc4a9, #FBC4A9);
}

.g5msifdtf {
  stop-color: var(--svg-color--ffdec2, #FFDEC2);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.g8qsq388j {
  d: path("M20.436 13.989q.064-1.062.123-2.124a1.066 1.066 0 0 1-.123 2.124");
}

.gemgotgww {
  d: path("m14.098 24.35l-.692-1.334l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.083h-1.285a.15.15 0 0 1-.133-.08");
}

.gen1zebho {
  d: path("M23.132 24.82c0-.439.355-.8.793-.8h3.023c.724 0 1.31.587 1.31 1.31v3.5a1.09 1.09 0 0 1-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.434a.8.8 0 0 1-.444-.718");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gs8utbrbr {
  fill: var(--svg-color--000, #000);
  d: path("M16.718 12.653c0-.317.253-.57.57-.57a.568.568 0 0 1 .507.832h-1.01a.5.5 0 0 1-.067-.262");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hbm_ekbec {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.184 11.354c-.729 0-1.344.502-1.512 1.18c-.05.195.1.381.299.381h2.49a.257.257 0 0 0 .253-.303a1.56 1.56 0 0 0-1.53-1.258");
}

.hxowi5i8i {
  stop-color: var(--svg-color--b6817f, #B6817F);
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.i7gh54b0a {
  d: path("M18.175 12.522a.94.94 0 0 0-.258-.517l-.29.319l.13.254z");
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.irpqnktdz {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1566 1566 0 0 1-4.625-7.734c-.422-.735-.219-.906-.14-1.031s.375-.36.671-.47c.238-.087.329-.202.344-.25c.057-.067.069-.3-.344-.687c-.412-.387-1.307-1.067-1.703-1.36c-.234-.187-.651-.608-.601-.983s.65-.435.765-.43z");
}

.isisf50au {
  d: path("M9.224 11.137a1.806 1.806 0 0 0-1.553 1.778c0 .959.75 1.742 1.696 1.793a87 87 0 0 1-.143-3.57");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j_dulcbnt {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.j_tdxuvbh {
  d: path("M9.469 16.296a4.37 4.37 0 0 0 4.335 3.8h2.104a4.37 4.37 0 0 0 4.335-3.8c.132-2.101.264-4.194.362-6.295a1.617 1.617 0 0 0-1.538-1.597h-1.563a2.7 2.7 0 0 1-2.467-1.61a.74.74 0 0 0-.686-.467h-1.42c-2.06 0-3.728 1.688-3.728 3.77c0 2.076.13 4.118.266 6.2");
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.j5q_9nbdn {
  stop-color: var(--svg-color--cc9990, #CC9990);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jsq1u4rsj {
  d: path("M6.386 7.879c-.26-.016-.991.034-1.316.36c-.357.357-.055 1.073.508 1.652c.539.554 2.335 1.738 5.18 1.738h8.167c2.874 0 4.689-1.184 5.234-1.738c.568-.58.874-1.295.513-1.653c-.328-.325-1.067-.375-1.33-.359z");
}

.jz_gcmb9c {
  fill: var(--svg-color--000, #000);
  d: path("M12.985 12.653a.57.57 0 0 0-.57-.57a.568.568 0 0 0-.507.832h1.01a.6.6 0 0 0 .067-.262");
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

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l3_hdyrbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.519 11.354c.728 0 1.344.502 1.511 1.181c.05.195-.1.38-.298.38h-2.49a.257.257 0 0 1-.253-.303a1.56 1.56 0 0 1 1.53-1.258");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
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

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lpown5iec {
  d: path("m14.425 12.414l-.593 2.05c-.121.423.17.845.58.845h.878c.411 0 .702-.429.58-.844l-.592-2.051c-.127-.454-.72-.454-.853 0");
}

.m2ipc1ljc {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.404 12.627l-.66 2.05c-.112.423.158.845.54.845h.817c.383 0 .653-.429.54-.844l-.551-2.051c-.118-.454-.563-.454-.687 0");
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.m9m0e1btb {
  fill: var(--svg-color--d8a298, #D8A298);
  d: path("m14.425 12.414l-.593 2.05c-.121.423.17.845.58.845h.878c.411 0 .702-.429.58-.844l-.592-2.051c-.127-.454-.72-.454-.853 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf9pttgpg {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.131h13.287a.1.1 0 0 0 .094-.132l-.192-.56l-.429-1.244a.1.1 0 0 0-.094-.068H8.829a.1.1 0 0 0-.094.068c-.19.554-.38 1.12-.532 1.575z");
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mx43wwh9a {
  d: path("M12.415 11.657a.996.996 0 0 0-.96 1.258h1.924q.034-.128.036-.263a1 1 0 0 0-1-.995");
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.my_84zz7a {
  d: path("m18.996 16.977l-2.742 12.945h1.796c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.22-.906.141-1.031c-.078-.125-.375-.36-.672-.47c-.237-.087-.328-.202-.344-.25c-.057-.067-.068-.3.344-.687c.413-.387 1.307-1.067 1.703-1.36c.235-.187.652-.608.602-.983s-.651-.435-.766-.43z");
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.ng-28zxwb {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.nhkngdbxa {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.593a2.984 2.984 0 1 0 0-5.97a2.984 2.984 0 0 0 0 5.97");
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.nzt6epbxo {
  stop-color: var(--svg-color--ad727e, #AD727E);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.o8vvrqzqj {
  stop-color: var(--svg-color--e1b2a7, #E1B2A7);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ok6g0xb6f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.215 11.868c.07.095-.078.21-.246.336c-.169.126-.294.215-.365.12c-.07-.095.008-.274.177-.4s.363-.151.434-.056");
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.otu1-6baj {
  stop-color: var(--svg-color--bd8884, #BD8884);
}

.oyglz-bkk {
  stop-color: var(--svg-color--e4b5a8, #E4B5A8);
  stop-opacity: 0;
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
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

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qk9vqlbuc {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.702 19.668l.69 3.215c.1.438.277.746.406.869c.128.123.325.011.407-.06l1.67-1.517l1.669 1.517c.082.071.28.183.408.06s.299-.415.4-.852l.696-3.232h-1.584l-1.59 2.116l-1.588-2.116z");
}

.qprdntb3r {
  stop-color: var(--svg-color--b6817f, #B6817F);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rhxl5gb9p {
  d: path("M27.203 22.329c.58 0 1.055.475 1.055 1.055v2.418h-2.111v-2.418c.01-.58.475-1.055 1.056-1.055");
}

.runotir-h {
  stop-color: var(--svg-color--ffdfbf, #FFDFBF);
  stop-opacity: 0;
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.s0-op-jbm {
  d: path("m17.77 22.747l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.995");
}

.s1a3ngbhp {
  stop-color: var(--svg-color--eeb6a5, #EEB6A5);
}

.s373i_baj {
  d: path("m14.425 12.215l-.593 2.051c-.121.422.17.844.58.844h.878c.411 0 .702-.428.58-.844l-.592-2.05c-.127-.455-.72-.455-.853 0");
}

.shl7c6jiw {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.851 16.443a3.35 3.35 0 0 1-1.545-.367c-.153-.077-.317.095-.221.234a2.11 2.11 0 0 0 1.766.943c.742 0 1.393-.377 1.767-.943c.096-.145-.068-.311-.221-.234a3.34 3.34 0 0 1-1.546.367Z");
}

.sn5q5zbjv {
  stop-color: var(--svg-color--eda886, #EDA886);
}

.snlr3-apx {
  d: path("M9.178 11.875a1.066 1.066 0 0 0 .093 2.096q-.06-1.049-.093-2.097");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.t-4zdpbuy {
  stop-color: var(--svg-color--f9c8b5, #F9C8B5);
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
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

.tnef9wrdf {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.294l-2.281 10.862z");
}

.tnviirb6b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.956h1.962");
}

.to1bhjtdn {
  d: path("M17.288 11.657a.996.996 0 0 1 .96 1.258h-1.924a1 1 0 0 1 .964-1.258");
}

.tvpehoh0i {
  stop-color: var(--svg-color--e1b2a7, #E1B2A7);
}

.u29lq70aj {
  d: path("M8.804 5.743a.1.1 0 0 0 .094.132h11.92a.1.1 0 0 0 .094-.133a86 86 0 0 0-.639-1.789c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567q-.103.067-.194.12c-.578.344-.808.4-1.277.4c-.37 0-.761-.15-1.183-.368a5 5 0 0 1-.248-.142c-.436-.26-1.078-.642-1.905-.526c-.956.134-1.66.93-2.097 1.945a29 29 0 0 0-.618 1.669");
}

.urft54bsg {
  stop-color: var(--svg-color--dba8a1, #DBA8A1);
  stop-opacity: 0;
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5h3xspgo {
  stop-color: var(--svg-color--e4b5a8, #E4B5A8);
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wa3u08nda {
  stop-color: var(--svg-color--ffdfc5, #FFDFC5);
}

.wibdzhbon {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.781c-.097.084-.327.214-.477.07c-.15-.143-.357-.503-.475-1.015");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.wtpc7f2sj {
  d: path("M17.215 11.868c.07.095-.078.21-.246.336c-.169.126-.294.215-.365.12c-.07-.095.008-.274.177-.4s.363-.151.434-.056");
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x0n4s-bkb {
  stop-color: var(--svg-color--ffdfbf, #FFDFBF);
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

.xo0ziebaz {
  stop-color: var(--svg-color--bd8884, #BD8884);
  stop-opacity: 0;
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xxcw8_bas {
  d: path("M12.625 19.547c.026.292.262.988.999 1.438c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.252-.664c.736-.45.973-1.146.999-1.438z");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yyxxh9qfh {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.747l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.995");
}

.z_8rtmb_y {
  stop-color: var(--svg-color--c48b92, #C48B92);
  stop-opacity: 0;
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.z-xw_ccte {
  stop-color: var(--svg-color--a7696f, #A7696F);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z5z3i6nzk {
  stop-color: var(--svg-color--a7696f, #A7696F);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zswbabceh {
  d: path("m13.289 29.922l.854-5.407a.1.1 0 0 1 .098-.085h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zx0jjr-cz {
  d: path("M14.851 16.443a3.35 3.35 0 0 1-1.545-.367c-.153-.077-.317.095-.221.234a2.11 2.11 0 0 0 1.766.943c.742 0 1.393-.377 1.767-.943c.096-.145-.068-.311-.221-.234a3.34 3.34 0 0 1-1.546.367");
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
