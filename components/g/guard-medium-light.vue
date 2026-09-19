<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#if3sSqg)"><path fill="url(#i6aJFZY)" class="ocwvddb0y"/><path fill="url(#izDA0dI)" class="ocwvddb0y"/></g><g filter="url(#iQHcNhc)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#i0xbmid)"><ellipse transform="rotate(-40.534 9.937 22.244)" class="a_d5m7-5r"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#iO95lGb)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.955 40.983)" class="tto44ccna"/><g filter="url(#irJw48c)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#izUZwzd)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iu5GgeJ)"><circle class="a1tpsrb8u"/></g><g filter="url(#is08aib)"><circle class="wfn54lnxd"/></g><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><path fill="url(#izgyXxd)" class="f2_5aiobj"/><path fill="url(#iNIzFLb)" class="iombfubgt"/><path fill="url(#iOCa0Cb)" class="iombfubgt"/><path fill="url(#iNIzFLb)" class="iombfubgt"/><path fill="url(#iOCa0Cb)" class="iombfubgt"/><g filter="url(#iuIWILb)"><path fill="url(#iliCGhP)" class="je8jsvbiu"/></g><path fill="url(#iVGLBLb)" class="je8jsvbiu"/><path fill="url(#itTEYnc)" class="je8jsvbiu"/><path fill="url(#itQ2dmb)" class="je8jsvbiu"/><path fill="url(#iFKHubt)" class="je8jsvbiu"/><path fill="url(#iY1Vuze)" class="je8jsvbiu"/><path fill="url(#i0jheTS)" class="je8jsvbiu"/><path fill="url(#ijZYM1c)" class="je8jsvbiu"/><path fill="url(#iDlxwib)" class="je8jsvbiu"/><g filter="url(#iRaiREd)"><path class="t6hf35bkm"/></g><g filter="url(#izuMuVd)"><path fill="url(#ixVWILb)" class="hkt6a0b4z"/><path fill="url(#i1FZVOe)" class="hkt6a0b4z"/><path fill="url(#i4TmQTb)" class="hkt6a0b4z"/><path fill="url(#ixobZnr)" class="hkt6a0b4z"/></g><g filter="url(#i7pYB3d)"><path fill="url(#i46Lkvd)" class="r7n45nzkd"/></g><g filter="url(#iZjG5oc)"><path stroke="url(#iSleiPd)" class="o951qub_k"/></g><path fill="url(#iQDhfqc)" class="lo3c_c3rn"/><path class="pm0ju79np"/><path fill="url(#ixtmNSZ)" class="dsfubwivk"/><path class="mnt76gbuu"/><g filter="url(#i5w1Ike)"><path class="pz4gwobln"/><path fill="url(#iCyKHwd)" class="ufu317btt"/></g><g filter="url(#i73i8hc)"><path fill="url(#i03Xhde)" class="zt5w_yl0e"/></g><path class="ltlts4b9o"/><path fill="url(#iAw0Ewd)" class="b23j3xbne"/><path class="ab60rebbp"/><g filter="url(#i2n5WNa)"><path fill="url(#iDCz6ob)" class="cw6o2h-7t"/></g><g filter="url(#iAaJUUc)"><ellipse transform="rotate(-27.914 13.487 14.41)" class="u02628t1w"/><ellipse fill="url(#iBnZegc)" transform="rotate(-27.914 13.487 14.41)" class="foz5qib1f"/></g><path fill="url(#iRtvenO)" class="fde2r-bfw"/><path fill="url(#iqIKfRc)" class="fde2r-bfw"/><path fill="url(#iVN5ugb)" class="fde2r-bfw"/><path fill="url(#ijcKpAd)" class="rjqu8s_zy"/><path fill="url(#iil9WCc)" class="rjqu8s_zy"/><g filter="url(#ih6AhbG)"><path class="hn_-2ibbr"/></g><g filter="url(#iOow1Jb)"><path class="p4-deokyb"/></g><g filter="url(#iTY3yRd)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#iGqlkEe)"><path fill="url(#iU1wwRb)" class="u17l1bw1n"/><path fill="url(#i7n11Wc)" class="u17l1bw1n"/><path fill="url(#iyBJvOb)" class="u17l1bw1n"/></g><defs><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="izUZwzd" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="i2cbmcbeb"/><stop offset="1" class="dhvpgd73i"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="izgyXxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.4 16.198)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iNIzFLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.393 16.48)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iOCa0Cb" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -3.855 14.638)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iliCGhP" cx="0" cy="0" r="1" gradientTransform="rotate(-174.554 10.188 7.535)scale(6.12174 10.8293)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="ptyk3-ibl"/></radialGradient><radialGradient id="iVGLBLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14299 12.963 -10.73495 -.94653 17.522 9.508)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="itTEYnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.388 14.301)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="itQ2dmb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 13.57 .582)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iFKHubt" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.06 15.806)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iY1Vuze" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.088 12.42)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i0jheTS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.786 19.494)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="ijZYM1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.898 10.04)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iSleiPd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 23.374 -3.286)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="agis4eb7s"/><stop offset="1" class="rbv7crf7o"/></radialGradient><radialGradient id="iQDhfqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.94 18.96)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ixtmNSZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17408 1.6093 0 18.122 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="tcnu-pxmv"/><stop offset=".887" class="kg92xobxe"/></radialGradient><radialGradient id="iCyKHwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.894 14.59)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAw0Ewd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17414 1.60939 0 13.758 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="tcnu-pxmv"/><stop offset=".887" class="kg92xobxe"/></radialGradient><radialGradient id="iBnZegc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.472 14.725)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqIKfRc" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.559 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iVN5ugb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.919 15.064)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iil9WCc" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 6.064 7.18)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iDlxwib" x1="15.988" x2="15.988" y1="14.002" y2="14.877" gradientUnits="userSpaceOnUse"><stop offset=".035" class="a-m662bug"/><stop offset="1" class="ijh84dm9y"/></linearGradient><linearGradient id="ixVWILb" x1="15.941" x2="16.795" y1="16.25" y2="16.25" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="i1FZVOe" x1="14.868" x2="15.942" y1="16.095" y2="16.154" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i4TmQTb" x1="15.941" x2="15.941" y1="16.649" y2="17.501" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="ixobZnr" x1="15.941" x2="15.941" y1="14.402" y2="14.821" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="i46Lkvd" x1="15.926" x2="15.99" y1="14.277" y2="15.464" gradientUnits="userSpaceOnUse"><stop class="o7c2glclr"/><stop offset="1" class="d2xpdab_y"/></linearGradient><linearGradient id="i03Xhde" x1="18.9" x2="18.587" y1="14.559" y2="14.753" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDCz6ob" x1="14.502" x2="14.188" y1="14.559" y2="14.752" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRtvenO" x1="22.377" x2="21.17" y1="14.587" y2="16.763" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ijcKpAd" x1="10.091" x2="11.549" y1="15.291" y2="15.163" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="i7n11Wc" x1="15.94" x2="15.94" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient><filter id="if3sSqg" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2846"/></filter><filter id="iQHcNhc" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2846" result="effect2_innerShadow_4002_2846"/></filter><filter id="i0xbmid" width="2.189" height="2.153" x="8.842" y="21.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".25"/></filter><filter id="iO95lGb" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".125"/></filter><filter id="irJw48c" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2846" result="effect2_innerShadow_4002_2846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2846" result="effect3_innerShadow_4002_2846"/></filter><filter id="iu5GgeJ" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".25"/></filter><filter id="is08aib" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".25"/></filter><filter id="iuIWILb" width="11.47" height="12.792" x="10.377" y="9.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2846" result="effect2_innerShadow_4002_2846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.454902 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2846" result="effect3_innerShadow_4002_2846"/></filter><filter id="iRaiREd" width="3.754" height="4.824" x="13.795" y="13.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".5"/></filter><filter id="izuMuVd" width="2.077" height="3.1" x="14.902" y="14.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".05"/></filter><filter id="i7pYB3d" width="2.077" height="3.1" x="14.887" y="14.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".05"/></filter><filter id="iZjG5oc" width="3.718" height="1.573" x="14.081" y="17.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".05"/></filter><filter id="i5w1Ike" width=".787" height=".696" x="17.388" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".05"/></filter><filter id="i73i8hc" width=".891" height=".913" x="18.228" y="14.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".1"/></filter><filter id="i2n5WNa" width=".986" height="1.04" x="13.786" y="14.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".1"/></filter><filter id="iAaJUUc" width=".913" height=".705" x="13.031" y="14.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".05"/></filter><filter id="ih6AhbG" width="1.329" height="2.379" x="9.908" y="13.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".125"/></filter><filter id="iOow1Jb" width="1.447" height="2.403" x="20.652" y="13.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2846" stdDeviation=".125"/></filter><filter id="iTY3yRd" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2846"/></filter><filter id="iGqlkEe" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2846"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:guard-medium-light" /></template>
<style>
.a_d5m7-5r {
  cx: 9.937px;
  cy: 22.244px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.a-m662bug {
  stop-color: var(--svg-color--bf7872, #BF7872);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.ab60rebbp {
  fill: var(--svg-color--000, #000);
  d: path("M14.268 14.921a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.agis4eb7s {
  stop-color: var(--svg-color--e1a99d, #E1A99D);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b23j3xbne {
  d: path("M13.756 14.029a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
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

.cw6o2h-7t {
  d: path("M14.572 14.816c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d2xpdab_y {
  stop-color: var(--svg-color--c8847a, #C8847A);
  stop-opacity: 0;
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.dhvpgd73i {
  stop-color: var(--svg-color--d4968b, #D4968B);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dsfubwivk {
  d: path("M18.125 14.029a.892.892 0 0 1 .86 1.127H17.26a.896.896 0 0 1 .864-1.128");
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f2_5aiobj {
  d: path("M20.802 16.672a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019q.257-.546.345-1.18z");
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fde2r-bfw {
  d: path("M20.862 16.763q.1-1.595.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.foz5qib1f {
  cx: 13.487px;
  cy: 14.41px;
  rx: 0.39px;
  ry: 0.197px;
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

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
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

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkt6a0b4z {
  d: path("m15.558 14.707l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hn_-2ibbr {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.903 14.224a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
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

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.i2cbmcbeb {
  stop-color: var(--svg-color--c47480, #C47480);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.ijh84dm9y {
  stop-color: var(--svg-color--bf7872, #BF7872);
  stop-opacity: 0;
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iombfubgt {
  d: path("M11.08 16.672a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.je8jsvbiu {
  d: path("M11.116 18.187A3.916 3.916 0 0 0 15 21.592h1.887a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.116 3.691.239 5.556");
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.kg92xobxe {
  stop-color: var(--svg-color--4a2d33, #4A2D33);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo3c_c3rn {
  d: path("M15.94 18.318c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.ltlts4b9o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.55 13.757c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mnt76gbuu {
  fill: var(--svg-color--000, #000);
  d: path("M17.613 14.921a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o7c2glclr {
  stop-color: var(--svg-color--c8847a, #C8847A);
}

.o951qub_k {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.59 17.923a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.272a.23.23 0 0 0-.271-.045c-.39.203-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.ocwvddb0y {
  d: path("M11.926 20.161c-1.364.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .704.02a12.3 12.3 0 0 1 3.107-1.857z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.p4-deokyb {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.902 16.112q.059-.953.111-1.904a.956.956 0 0 1-.11 1.904");
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm0ju79np {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.331 13.757c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.ptyk3-ibl {
  stop-color: var(--svg-color--c68981, #C68981);
}

.pz4gwobln {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.059 14.217c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r7n45nzkd {
  d: path("m15.543 14.583l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.rbv7crf7o {
  stop-color: var(--svg-color--e1a99d, #E1A99D);
  stop-opacity: 0;
}

.rjqu8s_zy {
  d: path("M10.886 13.563a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
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

.t6hf35bkm {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.51 15.086l-.692 1.655c-.102.378.142.757.486.757h.735c.345 0 .588-.384.487-.757l-.497-1.838c-.106-.407-.408-.225-.52.183");
}

.tcnu-pxmv {
  stop-color: var(--svg-color--734b48, #734B48);
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
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

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u02628t1w {
  cx: 13.487px;
  cy: 14.41px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.ufu317btt {
  d: path("M18.059 14.217c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
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

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zt5w_yl0e {
  d: path("M18.92 14.803a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
}

</style>
