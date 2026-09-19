<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJ0Nzyc)" class="xzot6tb3a"/><path fill="url(#iQ3Jo1d)" class="xzot6tb3a"/><path fill="url(#iu4BL0y)" class="xzot6tb3a"/><path fill="url(#i6kQckA)" class="xzot6tb3a"/><path fill="url(#iEbtPxb)" class="h83slyb1a"/><path fill="url(#imxslwc)" class="h83slyb1a"/><path fill="url(#iAPRHYd)" class="sllpz02jo"/><path fill="url(#iegNxyc)" class="sllpz02jo"/><g filter="url(#iJdL0MO)"><path fill="url(#i6aJFZY)" class="d8wucrb-m"/><path fill="url(#izDA0dI)" class="d8wucrb-m"/></g><g filter="url(#iAlxlNd)"><path class="a7obdqv4r"/><path fill="url(#iDMsGJb)" class="e4qvstbaw"/><path fill="url(#izjH7xz)" class="e4qvstbaw"/></g><g filter="url(#ix5cxce)"><ellipse transform="rotate(-40.534 9.937 22.243)" class="si-u7d6wp"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#ioXAIBe)"><ellipse transform="scale(-1 1)rotate(-35.343 23.848 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.954 40.982)" class="tto44ccna"/><g filter="url(#iF2o4Kb)"><rect fill="url(#icTwalH)" class="qyeoy6a8h"/><rect fill="url(#iFB7LRc)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#izayU8c)" class="kav9ef57d"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iXTKVcd)"><circle class="b4n-hsbxm"/></g><g filter="url(#iP7xjwb)"><circle class="d0e6vrb_a"/></g><circle fill="url(#iOrZVKb)" class="cad66eb8i"/><circle fill="url(#itFpnJb)" class="sx6q1cbyi"/><path fill="url(#itAOAJQ)" class="hafq7pioi"/><path fill="url(#iOsGIab)" class="mx8rokbor"/><g filter="url(#i1HUw7d)"><path fill="url(#io0Poru)" class="b6q_o0ixn"/></g><path fill="url(#icJGIyT)" class="b6q_o0ixn"/><path fill="url(#ipg4vob)" class="b6q_o0ixn"/><path fill="url(#iygRhVf)" class="b6q_o0ixn"/><path fill="url(#if3T0Kd)" class="b6q_o0ixn"/><path fill="url(#iRWJ8Wd)" class="b6q_o0ixn"/><path fill="url(#ipwPG9d)" class="b6q_o0ixn"/><path fill="url(#iUo3pSc)" class="b6q_o0ixn"/><path fill="url(#iJOJOwb)" class="b6q_o0ixn"/><path fill="url(#ihVJpwd)" class="b6q_o0ixn"/><path fill="url(#ilDuwlb)" class="b6q_o0ixn"/><path fill="url(#iIofiVn)" class="b6q_o0ixn"/><g filter="url(#idEYqhe)"><path class="v916qykpj"/></g><g filter="url(#iM0HpEx)"><path class="fp5s0lujw"/><path fill="url(#i6g6JJc)" class="pwhtb9llu"/><path fill="url(#iChehBe)" class="pwhtb9llu"/><path fill="url(#iHQJ25c)" class="pwhtb9llu"/><path fill="url(#ic3GiHe)" class="pwhtb9llu"/></g><g filter="url(#iI42uTd)"><path fill="url(#iOn7lUd)" class="u4dvjyb7h"/></g><g filter="url(#i7uc15c)"><path stroke="url(#isVFAvb)" class="fdn8uihly"/></g><path fill="url(#iyWBqGe)" class="ewqn3ckje"/><path class="ujjy_q6fe"/><path fill="url(#itkf2fM)" class="quu--gryi"/><path class="vxzt2ibku"/><g filter="url(#i6rc5Ud)"><path class="kv8kf11zw"/><path fill="url(#im527Jc)" class="x-ytukbty"/></g><g filter="url(#iD1LyVb)"><path fill="url(#iMPM1de)" class="z_9p4cbfg"/></g><path class="nvfvedc9o"/><path fill="url(#i98FY4d)" class="n4q32fbof"/><path class="nnmdnfgss"/><g filter="url(#ic2sLnd)"><path fill="url(#iDVn72b)" class="u7xdy0bab"/></g><g filter="url(#iiBMWTd)"><ellipse transform="rotate(-27.914 13.487 14.41)" class="u02628t1w"/><ellipse fill="url(#ihDydyb)" transform="rotate(-27.914 13.487 14.41)" class="foz5qib1f"/></g><path fill="url(#iSc3DOc)" class="fde2r-bfw"/><path fill="url(#iStKugb)" class="fde2r-bfw"/><path fill="url(#itD94Be)" class="fde2r-bfw"/><path fill="url(#ifadlsb)" class="fde2r-bfw"/><path fill="url(#i4HhYSp)" class="rjqu8s_zy"/><path fill="url(#iywcMMe)" class="rjqu8s_zy"/><g filter="url(#i96Mcec)"><path fill="url(#ihEBJqe)" class="yfpzx5b8b"/></g><g filter="url(#iZmU2le)"><path fill="url(#ivwLz1c)" class="d1_i5hb4e"/></g><g filter="url(#iaIQeab)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#iujevtd)"><path fill="url(#iU1wwRb)" class="ygyxlcb5n"/><path fill="url(#i7n11Wc)" class="ygyxlcb5n"/><path fill="url(#iyBJvOb)" class="ygyxlcb5n"/></g><defs><radialGradient id="iJ0Nzyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.989)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="iQ3Jo1d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.145)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="iEbtPxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iAPRHYd" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.726)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="iegNxyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="iDMsGJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.145)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="icTwalH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.91)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iFB7LRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.762)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="izayU8c" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.74 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="ph3vvlbzk"/><stop offset="1" class="q7xwx5btw"/></radialGradient><radialGradient id="iOrZVKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.16)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="itFpnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.16)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="itAOAJQ" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -1.413 23.053)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iOsGIab" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.884 16.854)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="io0Poru" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.748 15.422)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="ipg4vob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 17.522 9.509)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iygRhVf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.388 14.11)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="if3T0Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.923 .233)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iRWJ8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.373 16.41)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="ipwPG9d" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.473 11.097)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iUo3pSc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.05 16.033)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iJOJOwb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.24 10.4)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="ilDuwlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.59375 -7.73227 0 15.987 14.065)" gradientUnits="userSpaceOnUse"><stop class="v9g09594t"/><stop offset="1" class="yz8k7ub6u"/></radialGradient><radialGradient id="iChehBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.407 16.783)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="ic3GiHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.523 16.213)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iyWBqGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.94 18.961)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="itkf2fM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.05917 1.68473 0 18.122 15.088)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="q4mpo4bwm"/><stop offset="1" class="m4_fmr8pb"/></radialGradient><radialGradient id="im527Jc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.52 2.913)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i98FY4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.05923 1.68482 0 13.758 15.088)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="q4mpo4bwm"/><stop offset="1" class="m4_fmr8pb"/></radialGradient><radialGradient id="ihDydyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.472 14.725)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iStKugb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.558 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="itD94Be" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.919 15.064)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="ifadlsb" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.032 15.237)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iywcMMe" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.688 11.725)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="ihEBJqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.026 15.165)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="icJGIyT" x1="21.098" x2="16.745" y1="17.108" y2="17.108" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ihVJpwd" x1="15.987" x2="15.987" y1="21.674" y2="21.034" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iIofiVn" x1="20.45" x2="20.052" y1="17.705" y2="17.713" gradientUnits="userSpaceOnUse"><stop class="qfcvipb7l"/><stop offset="1" class="yh57m78se"/></linearGradient><linearGradient id="i6g6JJc" x1="16.779" x2="15.941" y1="16.097" y2="16.132" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iHQJ25c" x1="15.941" x2="15.941" y1="17.236" y2="16.771" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iOn7lUd" x1="15.926" x2="15.926" y1="14.205" y2="15.768" gradientUnits="userSpaceOnUse"><stop offset=".13" class="qqv10wbfa"/><stop offset="1" class="a6k7uuuss"/></linearGradient><linearGradient id="isVFAvb" x1="14.739" x2="15.057" y1="18.807" y2="17.972" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iMPM1de" x1="18.9" x2="18.587" y1="14.56" y2="14.753" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDVn72b" x1="14.502" x2="14.188" y1="14.56" y2="14.753" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSc3DOc" x1="22.377" x2="21.17" y1="14.587" y2="16.763" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i4HhYSp" x1="10.091" x2="11.549" y1="15.291" y2="15.163" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="ivwLz1c" x1="21.357" x2="21.357" y1="14.205" y2="16.108" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="i7n11Wc" x1="15.94" x2="15.94" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient><filter id="iJdL0MO" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2837"/></filter><filter id="iAlxlNd" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2837"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2837" result="effect2_innerShadow_4002_2837"/></filter><filter id="ix5cxce" width="2.189" height="2.153" x="8.842" y="21.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".25"/></filter><filter id="ioXAIBe" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".125"/></filter><filter id="iF2o4Kb" width="7.744" height="9.694" x="12.072" y="14.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2837"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2837" result="effect2_innerShadow_4002_2837"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2837" result="effect3_innerShadow_4002_2837"/></filter><filter id="iXTKVcd" width="2.09" height="2.09" x="16.395" y="27.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".25"/></filter><filter id="iP7xjwb" width="2.09" height="2.09" x="16.395" y="24.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".25"/></filter><filter id="i1HUw7d" width="11.22" height="12.542" x="10.877" y="9.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2837"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2837" result="effect2_innerShadow_4002_2837"/></filter><filter id="idEYqhe" width="3.747" height="4.9" x="13.925" y="13.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".5"/></filter><filter id="iM0HpEx" width="2.277" height="3.3" x="14.802" y="14.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".1"/></filter><filter id="iI42uTd" width="2.277" height="3.3" x="14.787" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".1"/></filter><filter id="i7uc15c" width="3.718" height="1.573" x="14.081" y="17.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".05"/></filter><filter id="i6rc5Ud" width=".787" height=".696" x="17.388" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".05"/></filter><filter id="iD1LyVb" width=".891" height=".913" x="18.228" y="14.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".1"/></filter><filter id="ic2sLnd" width=".986" height="1.04" x="13.786" y="14.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".1"/></filter><filter id="iiBMWTd" width=".913" height=".705" x="13.03" y="14.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".05"/></filter><filter id="i96Mcec" width="1.329" height="2.379" x="9.86" y="13.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".125"/></filter><filter id="iZmU2le" width="1.947" height="2.903" x="20.383" y="13.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2837" stdDeviation=".25"/></filter><filter id="iaIQeab" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2837"/></filter><filter id="iujevtd" width="10.882" height="7.996" x="10.499" y="14.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2837"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:guard-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6k7uuuss {
  stop-color: var(--svg-color--362125, #362125);
  stop-opacity: 0;
}

.a7obdqv4r {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.16c1.364.419 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.65a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.858z");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b4n-hsbxm {
  cx: 17.439px;
  cy: 28.444px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.b6q_o0ixn {
  d: path("M11.116 18.187A3.916 3.916 0 0 0 15 21.593h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.884.237-3.76.325-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.116 3.69.239 5.556");
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
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

.d0e6vrb_a {
  cx: 17.439px;
  cy: 25.444px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d1_i5hb4e {
  d: path("M20.883 16.108q.059-.951.11-1.903a.956.956 0 0 1-.11 1.903");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d8wucrb-m {
  d: path("M11.926 20.16c-1.364.419-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.65a.523.523 0 0 0 .704.02a12.3 12.3 0 0 1 3.107-1.858z");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.e4qvstbaw {
  d: path("M20.046 20.16c1.364.419 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.65a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.858z");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ewqn3ckje {
  d: path("M15.94 18.319c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.329");
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fde2r-bfw {
  d: path("M20.862 16.763q.1-1.595.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.fdn8uihly {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.59 17.924h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.271c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.foz5qib1f {
  cx: 13.487px;
  cy: 14.41px;
  rx: 0.39px;
  ry: 0.197px;
}

.fp5s0lujw {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.558 14.708l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
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

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gw4u-ub3u {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.004-.008l.02-.04c.061-.121.152-.298-.02-.578c-.193-.313-.375-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.07-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.066-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.452-.58c.046-.215.132-.502.293-.663a1.06 1.06 0 0 1 .791-.3c.257.007.535-.03.752-.254c.217-.225.458-.413.699-.453s.471.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112c.098 0 .214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.484-.184.725-.144s.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.246.448.292.663c.088.417.243.491.452.58l.02.008c.219.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.117.86c.33.641.193.955 0 1.268c-.171.28-.081.457-.02.577l.02.041l.005.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.h83slyb1a {
  d: path("M9.058 29.91h-3.63a9.98 9.98 0 0 1 3.63-7.354z");
}

.hafq7pioi {
  d: path("M20.802 16.672c.335-.01.649-.124.904-.309v.931c0 .894-.532 1.69-1.34 2.02q.257-.546.345-1.18z");
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

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
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

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.kav9ef57d {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.098px;
  rx: 1.969px;
}

.kv8kf11zw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.059 14.218c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m4_fmr8pb {
  stop-color: var(--svg-color--472e28, #472E28);
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.mx8rokbor {
  d: path("M11.08 16.672a1.64 1.64 0 0 1-.905-.309v.931c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n4q32fbof {
  d: path("M13.756 14.03a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.nnmdnfgss {
  fill: var(--svg-color--000, #000);
  d: path("M14.268 14.922a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.235");
}

.nvfvedc9o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.55 13.757c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.ph3vvlbzk {
  stop-color: var(--svg-color--35161f, #35161F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pwhtb9llu {
  d: path("m15.558 14.708l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q4mpo4bwm {
  stop-color: var(--svg-color--6f4c43, #6F4C43);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q7xwx5btw {
  stop-color: var(--svg-color--462b32, #462B32);
}

.qfcvipb7l {
  stop-color: var(--svg-color--2c191f, #2C191F);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qqv10wbfa {
  stop-color: var(--svg-color--362125, #362125);
}

.quu--gryi {
  d: path("M18.125 14.03a.892.892 0 0 1 .86 1.127H17.26a.896.896 0 0 1 .864-1.128");
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rjqu8s_zy {
  d: path("M10.886 13.563a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.si-u7d6wp {
  cx: 9.937px;
  cy: 22.243px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.sllpz02jo {
  d: path("M22.942 29.91h3.63a9.98 9.98 0 0 0-3.63-7.354z");
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
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

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u02628t1w {
  cx: 13.487px;
  cy: 14.41px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.u4dvjyb7h {
  d: path("m15.544 14.51l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.766 0");
}

.u7xdy0bab {
  d: path("M14.572 14.816c0-.288-.235-.48-.298-.538l-.288.278l.177.362z");
}

.ujjy_q6fe {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.331 13.757c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v916qykpj {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.539 14.903l-.59 1.839c-.102.378.14.756.484.756h.731c.343 0 .586-.384.485-.756l-.495-1.839c-.106-.407-.504-.407-.615 0");
}

.v9g09594t {
  stop-color: var(--svg-color--301d21, #301D21);
}

.vxzt2ibku {
  fill: var(--svg-color--000, #000);
  d: path("M17.614 14.922a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.236");
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x-ytukbty {
  d: path("M18.059 14.218c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xzot6tb3a {
  d: path("M5.428 29.91h21.144c-.19-5.355-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.285-9.994 9.64");
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yfpzx5b8b {
  d: path("M10.855 14.224a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.ygyxlcb5n {
  d: path("m10.5 14.155l.12 3.518c.082 2.425 2.07 4.379 4.497 4.379h1.677c2.44 0 4.435-1.977 4.498-4.416l.09-3.481h-.909l-.12 3.48c-.049 1.898-1.662 3.487-3.56 3.487h-1.676c-1.887 0-3.489-1.597-3.553-3.483l-.09-3.484z");
}

.yh57m78se {
  stop-color: var(--svg-color--553a38, #553A38);
  stop-opacity: 0;
}

.yz8k7ub6u {
  stop-color: var(--svg-color--301d21, #301D21);
  stop-opacity: 0;
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z_9p4cbfg {
  d: path("M18.92 14.804a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
