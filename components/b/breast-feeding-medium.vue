<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iQM0LXc)" class="d2kvgvbvc"><path fill="url(#iyho0Ee)" class="yfvjw8b3h"/><path fill="url(#i5vBcxc)" class="yfvjw8b3h"/><path fill="url(#i5CyTec)" class="yfvjw8b3h"/><path fill="url(#iAgu0SP)" class="yfvjw8b3h"/><path fill="url(#inQMYcb)" class="yfvjw8b3h"/><path fill="url(#ibNSNpb)" class="yfvjw8b3h"/><path fill="url(#i0YPmsb)" class="yfvjw8b3h"/><path fill="url(#igOJL3Z)" class="yfvjw8b3h"/><path fill="url(#imTWAmc)" class="yfvjw8b3h"/><path fill="url(#iPEZUwe)" class="yfvjw8b3h"/><path fill="url(#iqHKCzc)" class="yfvjw8b3h"/><path fill="url(#i7CZyfb)" class="yfvjw8b3h"/></g><path class="qlgfsfb2d"/><path fill="url(#inT0juc)" class="fimw5lrwi"/><path fill="url(#iWd4zKx)" class="nc2l1ubcn"/><path fill="url(#iMUMVBb)" class="nc2l1ubcn"/><path fill="url(#ihAqQZb)" class="nc2l1ubcn"/><path fill="url(#ixs8xad)" class="nc2l1ubcn"/><path fill="url(#i05FtMc)" class="rflawqjsp"/><path fill="url(#i84iPBc)" class="rflawqjsp"/><path fill="url(#iLPvRSc)" class="rflawqjsp"/><g filter="url(#iaD0V2d)"><path fill="url(#iQOT0sb)" class="doqtch_8f"/><path fill="url(#idKf9je)" class="doqtch_8f"/><path fill="url(#i3qVvAd)" class="doqtch_8f"/><path fill="url(#iqgKQHd)" class="doqtch_8f"/></g><g filter="url(#iyB0ssc)"><path fill="url(#i3DtQFe)" class="fbwetlb3l"/></g><g filter="url(#iZHS5eu)"><path stroke="url(#iwvdgkb)" class="cjbp-tbil"/></g><g filter="url(#iBqJSGe)"><path fill="url(#iLPB5yc)" class="y3i4g-bee"/></g><g filter="url(#iU02qCb)"><path stroke="url(#iEDV3hd)" class="bz3ncuban"/></g><g filter="url(#iw8npSe)"><path fill="url(#iLq1j3d)" class="q_rjf54ai"/><path fill="url(#i7oWc2c)" class="q_rjf54ai"/></g><g filter="url(#iKi4VDb)"><path class="yf_lw100d"/><path fill="url(#i3Zoegc)" class="zts9dnb_c"/><path fill="url(#iXz8cJe)" class="zts9dnb_c"/><path fill="url(#iwMPDnc)" class="zts9dnb_c"/><path fill="url(#ihMIuLv)" class="zts9dnb_c"/></g><path fill="url(#iTJuZ6I)" class="aiaew87yw"/><path fill="url(#i2IqXye)" class="aiaew87yw"/><path fill="url(#iZSK6iW)" class="t34-m913i"/><path fill="url(#iV6pyVc)" class="t34-m913i"/><g filter="url(#iTzJP8d)"><path fill="url(#iJvoJBe)" class="fry0q78oh"/></g><g filter="url(#iTzJP8d)"><path fill="url(#iJvoJBe)" class="fry0q78oh"/><path fill="url(#iYxEfxb)" class="fry0q78oh"/><path fill="url(#ipzFdmb)" class="fry0q78oh"/><path fill="url(#ibU0Yze)" class="fry0q78oh"/><path fill="url(#idQO2uz)" class="fry0q78oh"/></g><path fill="url(#iSb7RLY)" class="fry0q78oh"/><g filter="url(#iINMu0c)"><path fill="url(#id9ovJc)" class="cs-jscxvs"/></g><g filter="url(#ieLbXCd)"><path stroke="url(#iVBSA8P)" class="f_-cokbml"/></g><g filter="url(#iyBf64d)"><path stroke="url(#ilbpWdb)" class="qd-vegb5y"/></g><g filter="url(#i9daYPM)"><path stroke="url(#iE4pyQe)" class="vyojtk_xf"/></g><g filter="url(#iqDPG9d)"><path stroke="url(#iQZMQle)" class="kzj-gwbkm"/></g><g filter="url(#iArJ4Lj)"><path stroke="url(#i1yZ5Yd)" class="i4dibacwt"/></g><g filter="url(#ik1MNxb)"><path stroke="url(#iysO5xd)" class="xi960zbzc"/></g><g filter="url(#iKUXMhN)"><path fill="url(#iVI7JFe)" class="x9_lkhbgw"/></g><path fill="url(#iFjiwwJ)" class="x9_lkhbgw"/><g filter="url(#iPa45Nb)"><path fill="url(#i9WOvOc)" class="gjutkou6f"/><path fill="url(#iyzOY4b)" class="gjutkou6f"/></g><g filter="url(#itLAjwe)"><path class="feugx5i3r"/><path fill="url(#ivJ0LRx)" class="qe03co1lx"/></g><g filter="url(#i0jzQze)"><path class="qpwbhgbyy"/><path fill="url(#i7CZ6kc)" class="md1t93b9l"/></g><g filter="url(#ihEJmjc)"><path fill="url(#iqq7S1d)" class="pcy-27bbq"/><path fill="url(#iDN8LBe)" class="pcy-27bbq"/><path fill="url(#iixjAbq)" class="pcy-27bbq"/><path fill="url(#iJKhWXb)" class="pcy-27bbq"/><path fill="url(#iMASd8k)" class="pcy-27bbq"/><path fill="url(#i872Elb)" class="pcy-27bbq"/></g><path fill="url(#i8r1Tdc)" class="pcy-27bbq"/><g filter="url(#ij9d6vb)"><path class="t1s5t0bbn"/></g><g filter="url(#i3DC2gc)"><path class="y5wj0cb9b"/><path fill="url(#ihFx4Yd)" class="yjxrkgq7v"/><path fill="url(#iAEc6fb)" class="yjxrkgq7v"/><path fill="url(#i4Xhbmc)" class="yjxrkgq7v"/><path fill="url(#i68qXHc)" class="yjxrkgq7v"/></g><g filter="url(#iGXN2Fc)"><path stroke="url(#iRU52kc)" class="i0xvywvie"/></g><path class="fft2fx5po"/><g filter="url(#iYLtYZd)"><path class="l1bz-r8iw"/><path fill="url(#i48pffb)" class="mdxlbkffu"/><path fill="url(#iLjx0sd)" class="mdxlbkffu"/></g><g filter="url(#i2tFsBd)"><path class="re_ifjj0z"/><path fill="url(#iTvB3tY)" class="ps9fj4bvg"/><path fill="url(#i6jPIxe)" class="ps9fj4bvg"/></g><g filter="url(#iU3cyJd)"><path stroke="url(#igBQsye)" class="qit_6iqhw"/></g><g filter="url(#iTIAvzc)"><path class="u6mu-v3yl"/></g><g filter="url(#igiy2Vb)"><path fill="url(#ip5TfGb)" class="boy37thuw"/></g><g filter="url(#iit1wtb)"><path fill="url(#ih0xTlg)" class="wvf_psbmu"/></g><path fill="url(#iIvAz0d)" class="b8_m1dbzs"/><path fill="url(#i8TS9Le)" class="g8eqos3yo"/><g filter="url(#itfrbTc)" class="tryqaac1t"><path stroke="url(#ib9CIKn)" class="chcol9b3r"/><path stroke="url(#iHFg07c)" class="chcol9b3r"/></g><g filter="url(#ilneWBe)" class="tryqaac1t"><path stroke="url(#iIWuN9d)" class="vt94b84mi"/><path stroke="url(#ixio8Ub)" class="vt94b84mi"/></g><g filter="url(#iVt7p6d)"><path clip-rule="evenodd" class="klfo-1b4q"/></g><g filter="url(#iR4D6lc)"><path class="lo8r7sbbw"/></g><g filter="url(#i83lCJe)"><path class="p9lf13b1j"/></g><g filter="url(#itABkqc)"><path class="nsuzlkbcm"/></g><defs><radialGradient id="i5vBcxc" cx="0" cy="0" r="1" gradientTransform="matrix(.29287 4.89336 -6.11281 .36586 16.211 13.975)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="i5CyTec" cx="0" cy="0" r="1" gradientTransform="rotate(135.04 3.592 10.169)scale(3.70671 4.87033)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iAgu0SP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02155 2.0542 -1.57734 -.7844 10.996 12.51)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="inQMYcb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92244 2.47178 -1.74115 -.64978 11.058 10.296)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="ibNSNpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.96846 2.45767 -3.41162 2.73252 10.703 3.576)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i0YPmsb" cx="0" cy="0" r="1" gradientTransform="rotate(124.034 9.432 7.483)scale(2.17293 3.03664)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="igOJL3Z" cx="0" cy="0" r="1" gradientTransform="rotate(152.815 10.779 7.307)scale(2.04673 4.26829)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="imTWAmc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.804 1.30759 -1.66567 -3.57188 23.767 12.583)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iPEZUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48384 -2.59009 2.04861 -1.17363 20.306 6.899)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iqHKCzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60581 -.13982 .22656 2.6019 9.413 11.613)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="i7CZyfb" cx="0" cy="0" r="1" gradientTransform="rotate(-113.713 13.353 -2.55)scale(4.04834 1.46113)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="inT0juc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 1.9893 19.511 29.938)" gradientUnits="userSpaceOnUse"><stop class="n2a634bwb"/><stop offset="1" class="y9owwpbix"/></radialGradient><radialGradient id="iWd4zKx" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50378 0 0 -5.6875 21.761 19.162)" gradientUnits="userSpaceOnUse"><stop class="ufx-nyb4s"/><stop offset="1" class="s6rfugboe"/></radialGradient><radialGradient id="iMUMVBb" cx="0" cy="0" r="1" gradientTransform="rotate(-154.983 12.467 9.024)scale(2.5864 3.5607)" gradientUnits="userSpaceOnUse"><stop class="blqrnab2q"/><stop offset="1" class="ybai0acxr"/></radialGradient><radialGradient id="ihAqQZb" cx="0" cy="0" r="1" gradientTransform="matrix(.6438 1.98845 -3.91086 1.2662 16.59 16.398)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="iobnj4b7a"/><stop offset="1" class="y3p2-pbto"/></radialGradient><radialGradient id="ixs8xad" cx="0" cy="0" r="1" gradientTransform="matrix(2.21876 -7 9.86052 3.12544 19.268 23.153)" gradientUnits="userSpaceOnUse"><stop offset=".783" class="j-e6rp1-z"/><stop offset="1" class="k3_w4brwn"/></radialGradient><radialGradient id="i84iPBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.79688 2.04686 -1.95763 2.67496 23.418 27.38)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tkcxzncwj"/><stop offset="1" class="mqicc-u0l"/></radialGradient><radialGradient id="iLPvRSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.3125 -2.12008 2.12008 22.011 27.818)" gradientUnits="userSpaceOnUse"><stop class="c14jvicyx"/><stop offset="1" class="i8x7p37cq"/></radialGradient><radialGradient id="idKf9je" cx="0" cy="0" r="1" gradientTransform="rotate(126.08 3.12 12.131)scale(4.98797 9.68383)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7fe64b-m"/><stop offset="1" class="o3yqmrbrg"/></radialGradient><radialGradient id="i3qVvAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45313 -.6875 0 13.87 28.317)" gradientUnits="userSpaceOnUse"><stop class="la4e9obft"/><stop offset="1" class="sq95r4vix"/></radialGradient><radialGradient id="iqgKQHd" cx="0" cy="0" r="1" gradientTransform="rotate(-117.519 14.64 7.173)scale(1.35267 2.95016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="kc6luf8ah"/><stop offset="1" class="yit44gm3t"/></radialGradient><radialGradient id="i3DtQFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 -1.6057 .88152 .74629 11.761 25.739)" gradientUnits="userSpaceOnUse"><stop class="c_e6lvb0e"/><stop offset="1" class="bzrv_p78g"/></radialGradient><radialGradient id="iwvdgkb" cx="0" cy="0" r="1" gradientTransform="rotate(-162.16 15.544 12.068)scale(.71402 1.53504)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></radialGradient><radialGradient id="i7oWc2c" cx="0" cy="0" r="1" gradientTransform="rotate(163.67 9.088 15.5)scale(5.1125 7.55864)" gradientUnits="userSpaceOnUse"><stop class="khg6a5-nz"/><stop offset="1" class="jyzijgb5l"/></radialGradient><radialGradient id="iXz8cJe" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 -1.0625 .82137 1.8964 14.8 30.736)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="y_genvbtz"/><stop offset="1" class="dyjetvbhh"/></radialGradient><radialGradient id="iwMPDnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .36719 -.26111 -.32778 16.792 26.346)" gradientUnits="userSpaceOnUse"><stop class="oqa602b9h"/><stop offset="1" class="tm8i9nrvx"/></radialGradient><radialGradient id="ihMIuLv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 0 0 -.59662 16.175 28.216)" gradientUnits="userSpaceOnUse"><stop class="h5ifffbxa"/><stop offset="1" class="ny1a5-4af"/></radialGradient><radialGradient id="iTJuZ6I" cx="0" cy="0" r="1" gradientTransform="rotate(154.496 10.792 13.812)scale(3.77401 4.40797)" gradientUnits="userSpaceOnUse"><stop class="w-wd4mb8i"/><stop offset="1" class="jswq_j2dq"/></radialGradient><radialGradient id="i2IqXye" cx="0" cy="0" r="1" gradientTransform="rotate(42.983 -16.002 40.634)scale(5.22527)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="i54m18vgp"/><stop offset=".995" class="nybv-x_bu"/></radialGradient><radialGradient id="iV6pyVc" cx="0" cy="0" r="1" gradientTransform="matrix(.39062 -3.01563 4.79304 .62086 19.418 24.41)" gradientUnits="userSpaceOnUse"><stop class="l99uylilx"/><stop offset="1" class="xjvfic_gd"/></radialGradient><radialGradient id="iJvoJBe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.355 27.817)" gradientUnits="userSpaceOnUse"><stop class="rq4-grb6j"/><stop offset="1" class="w6mxzsbgv"/></radialGradient><radialGradient id="iYxEfxb" cx="0" cy="0" r="1" gradientTransform="rotate(34.714 -27.668 42.785)scale(3.03183 .43734)" gradientUnits="userSpaceOnUse"><stop class="a4385nb5a"/><stop offset="1" class="wx449kb5h"/></radialGradient><radialGradient id="ipzFdmb" cx="0" cy="0" r="1" gradientTransform="matrix(1.89062 2.04687 -.34125 .3152 20.784 22.544)" gradientUnits="userSpaceOnUse"><stop class="a4385nb5a"/><stop offset="1" class="wx449kb5h"/></radialGradient><radialGradient id="ibU0Yze" cx="0" cy="0" r="1" gradientTransform="matrix(1.90624 1.26564 -.211 .3178 19.721 25.184)" gradientUnits="userSpaceOnUse"><stop class="a4385nb5a"/><stop offset="1" class="wx449kb5h"/></radialGradient><radialGradient id="idQO2uz" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 2.11719 -.35298 .03386 23.69 22.38)" gradientUnits="userSpaceOnUse"><stop class="uddy23wrg"/><stop offset="1" class="u5jw2ubor"/></radialGradient><radialGradient id="iFjiwwJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.9279 -1.12668 1.27667 -1.05144 11.031 14.01)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i9WOvOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.37494 -1.68834 2.06139 2.89969 20.336 10.937)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iyzOY4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.2627 -.24463 .10533 .54366 20.848 8.509)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ivJ0LRx" cx="0" cy="0" r="1" gradientTransform="rotate(-15.219 49.705 -71.98)scale(1.61362 1.2614)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i7CZ6kc" cx="0" cy="0" r="1" gradientTransform="rotate(169.035 5.015 6.652)scale(1.12539)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iqq7S1d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.19794 4.45695 -5.96558 -8.29587 18.902 10.153)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iDN8LBe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08712 1.44605 -1.007 -1.45343 18.146 11.227)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iixjAbq" cx="0" cy="0" r="1" gradientTransform="rotate(-82.797 17.682 .502)scale(4.40715 5.59185)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iJKhWXb" cx="0" cy="0" r="1" gradientTransform="matrix(.15047 7.97644 -9.97045 .18808 16.896 10.09)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iMASd8k" cx="0" cy="0" r="1" gradientTransform="rotate(157.932 7.89 7.859)scale(7.5015 12.9153)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="i872Elb" cx="0" cy="0" r="1" gradientTransform="rotate(94.127 4.87 11.613)scale(3.56242 2.85052)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="i8r1Tdc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34504 .2606 -1.30686 -6.74522 21.46 10.819)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="ihFx4Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-.89095 -2.0463 .63065 -.27458 17.095 12.454)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="i68qXHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81548 .158 -.04417 -.22799 16.887 12.724)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="i48pffb" cx="0" cy="0" r="1" gradientTransform="matrix(.76191 -3.13882 1.60574 .38978 9.547 9.599)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iLjx0sd" cx="0" cy="0" r="1" gradientTransform="matrix(.80235 -2.2997 1.23462 .43075 11.135 8.227)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iTvB3tY" cx="0" cy="0" r="1" gradientTransform="rotate(104.719 7.197 7.637)scale(5.19427 8.49232)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i6jPIxe" cx="0" cy="0" r="1" gradientTransform="matrix(.05708 1.4734 -3.16994 .1228 14.707 3.347)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iHFg07c" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 19.144 10.43)" gradientUnits="userSpaceOnUse"><stop class="lql_2ab8k"/><stop offset="1" class="ea15stbaq"/></radialGradient><radialGradient id="ixio8Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 14.677 11.182)" gradientUnits="userSpaceOnUse"><stop class="lql_2ab8k"/><stop offset="1" class="ea15stbaq"/></radialGradient><filter id="iQM0LXc" width="16.762" height="17.464" x="8.093" y="1.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iaD0V2d" width="12.107" height="12.935" x="4.292" y="17.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iyB0ssc" width="3.547" height="2.605" x="10.246" y="23.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".25"/></filter><filter id="iZHS5eu" width="1.338" height="3.484" x="25.65" y="26.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".05"/></filter><filter id="iBqJSGe" width="8.034" height="4.188" x="6.668" y="26.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".5"/></filter><filter id="iU02qCb" width="1.907" height="4.376" x="11.205" y="20.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".125"/></filter><filter id="iw8npSe" width="10.856" height="8.359" x="11.765" y="21.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iKi4VDb" width="6.652" height="4.473" x="14.118" y="25.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.431373 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iTzJP8d" width="6.654" height="7.23" x="19.111" y="21.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.337255 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iINMu0c" width="5.813" height="5.503" x="7.73" y="21.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".5"/></filter><filter id="ieLbXCd" width="3.309" height="3.341" x="20.88" y="21.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".2"/></filter><filter id="iyBf64d" width="2.013" height="4.911" x="23.891" y="22.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".2"/></filter><filter id="i9daYPM" width="3.294" height="2.926" x="19.598" y="22.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".2"/></filter><filter id="iqDPG9d" width="3.106" height="2.411" x="19.224" y="23.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".2"/></filter><filter id="iArJ4Lj" width="3.043" height="2.122" x="19.208" y="25.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".2"/></filter><filter id="ik1MNxb" width="5.798" height=".972" x="14.85" y="28.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".15"/></filter><filter id="iKUXMhN" width="3.58" height="3.431" x="9.401" y="10.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iPa45Nb" width="3.43" height="3.681" x="19.356" y="8.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="itLAjwe" width="3.29" height="3.29" x="19.426" y="8.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".25"/></filter><filter id="i0jzQze" width="2.99" height="2.99" x="9.641" y="10.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".175"/></filter><filter id="ihEJmjc" width="11.27" height="11.207" x="10.28" y="6.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="ij9d6vb" width="2.984" height="3.917" x="14.69" y="10.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".25"/></filter><filter id="i3DC2gc" width="2.484" height="3.405" x="15.081" y="10.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".125"/></filter><filter id="iGXN2Fc" width="3.86" height="1.922" x="14.637" y="13.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".05"/></filter><filter id="iYLtYZd" width="4.234" height="5.344" x="8.568" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/><feGaussianBlur result="effect2_foregroundBlur_4002_3507" stdDeviation=".2"/></filter><filter id="i2tFsBd" width="9.95" height="4.934" x="11.399" y="3.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/><feGaussianBlur result="effect2_foregroundBlur_4002_3507" stdDeviation=".125"/></filter><filter id="iU3cyJd" width="1.517" height="2.278" x="11.367" y="4.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".1"/></filter><filter id="iTIAvzc" width="6.909" height="3.466" x="14.501" y="4.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".375"/></filter><filter id="igiy2Vb" width="3.872" height="3.001" x="11.525" y="9.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".3"/></filter><filter id="iit1wtb" width="3.682" height="2.915" x="16.395" y="8.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".3"/></filter><filter id="itfrbTc" width="2.582" height="1.236" x="16.902" y="10.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".075"/></filter><filter id="ilneWBe" width="2.582" height="1.236" x="12.435" y="10.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".075"/></filter><filter id="iVt7p6d" width="2.633" height=".931" x="16.932" y="7.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="iR4D6lc" width="2.408" height=".779" x="16.974" y="8.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".1"/></filter><filter id="i83lCJe" width="2.502" height="1.456" x="11.623" y="8.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3507"/></filter><filter id="itABkqc" width="2.268" height="1.298" x="11.633" y="8.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3507" stdDeviation=".1"/></filter><linearGradient id="iyho0Ee" x1="19.522" x2="15.284" y1="3.069" y2="15.574" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="i05FtMc" x1="26.793" x2="24.491" y1="25.099" y2="29.938" gradientUnits="userSpaceOnUse"><stop class="up7b_htug"/><stop offset="1" class="bvctw1bkc"/></linearGradient><linearGradient id="iQOT0sb" x1="15.261" x2="6.793" y1="19.255" y2="29.937" gradientUnits="userSpaceOnUse"><stop class="eoa632ltp"/><stop offset="1" class="rlw3b4b7i"/></linearGradient><linearGradient id="iLPB5yc" x1="13.48" x2="7.928" y1="28.942" y2="28.918" gradientUnits="userSpaceOnUse"><stop class="lzdnytbwv"/><stop offset="1" class="yasfqbb-e"/></linearGradient><linearGradient id="iEDV3hd" x1="13.155" x2="13.104" y1="24.331" y2="21.381" gradientUnits="userSpaceOnUse"><stop class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></linearGradient><linearGradient id="iLq1j3d" x1="21.355" x2="14.293" y1="27.662" y2="27.224" gradientUnits="userSpaceOnUse"><stop class="vrjrrpcnz"/><stop offset="1" class="qarzv5b-l"/></linearGradient><linearGradient id="i3Zoegc" x1="18.565" x2="18.55" y1="30.091" y2="29.278" gradientUnits="userSpaceOnUse"><stop offset=".204" class="r3kdhjbzd"/><stop offset="1" class="sz9ifbfqc"/></linearGradient><linearGradient id="iZSK6iW" x1="21.668" x2="20.168" y1="18.658" y2="23.255" gradientUnits="userSpaceOnUse"><stop class="rm6lemo-n"/><stop offset=".635" class="uny69rbro"/></linearGradient><linearGradient id="iSb7RLY" x1="25.558" x2="24.87" y1="25.274" y2="25.424" gradientUnits="userSpaceOnUse"><stop offset=".049" class="khirl1bud"/><stop offset="1" class="m-nxtsi5k"/></linearGradient><linearGradient id="id9ovJc" x1="10.636" x2="13.293" y1="25.665" y2="22.418" gradientUnits="userSpaceOnUse"><stop class="lk8w5cclk"/><stop offset="1" class="qrasocbfu"/></linearGradient><linearGradient id="iVBSA8P" x1="22.142" x2="23.757" y1="22.832" y2="24.211" gradientUnits="userSpaceOnUse"><stop offset=".076" class="rfocsjb8y"/><stop offset="1" class="ynj51cbvd"/></linearGradient><linearGradient id="ilbpWdb" x1="24.746" x2="25.784" y1="23.628" y2="23.825" gradientUnits="userSpaceOnUse"><stop offset=".076" class="rfocsjb8y"/><stop offset="1" class="ynj51cbvd"/></linearGradient><linearGradient id="iE4pyQe" x1="20.855" x2="22.461" y1="23.453" y2="25.186" gradientUnits="userSpaceOnUse"><stop offset=".076" class="rfocsjb8y"/><stop offset="1" class="ynj51cbvd"/></linearGradient><linearGradient id="iQZMQle" x1="20.422" x2="21.715" y1="24.622" y2="26.405" gradientUnits="userSpaceOnUse"><stop offset=".076" class="rfocsjb8y"/><stop offset="1" class="ynj51cbvd"/></linearGradient><linearGradient id="i1yZ5Yd" x1="20.386" x2="21.186" y1="26.08" y2="27.486" gradientUnits="userSpaceOnUse"><stop offset=".076" class="rfocsjb8y"/><stop offset="1" class="ynj51cbvd"/></linearGradient><linearGradient id="iysO5xd" x1="19.922" x2="15.689" y1="29.04" y2="28.983" gradientUnits="userSpaceOnUse"><stop class="yddo6xgmq"/><stop offset="1" class="z2-7n818b"/></linearGradient><linearGradient id="iVI7JFe" x1="9.45" x2="11.393" y1="12.664" y2="12.287" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iAEc6fb" x1="15.307" x2="16.29" y1="12.879" y2="12.689" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i4Xhbmc" x1="16.433" x2="16.306" y1="13.429" y2="12.773" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iRU52kc" x1="15.623" x2="15.961" y1="15.217" y2="14.378" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="igBQsye" x1="11.356" x2="12.125" y1="4.651" y2="5.876" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="ip5TfGb" x1="14.352" x2="11.665" y1="10.586" y2="10.294" gradientUnits="userSpaceOnUse"><stop class="s_1mgzhbo"/><stop offset="1" class="t-u7o5ykp"/></linearGradient><linearGradient id="ih0xTlg" x1="19.092" x2="15.618" y1="10.055" y2="8.901" gradientUnits="userSpaceOnUse"><stop offset=".394" class="aqne2ebmr"/><stop offset="1" class="zufjkvb9h"/></linearGradient><linearGradient id="iIvAz0d" x1="19.035" x2="17.472" y1="10.791" y2="11.616" gradientUnits="userSpaceOnUse"><stop offset=".558" class="vg8k7bbhe"/><stop offset="1" class="w-7avbcrn"/></linearGradient><linearGradient id="i8TS9Le" x1="14.536" x2="12.969" y1="11.55" y2="12.371" gradientUnits="userSpaceOnUse"><stop offset=".558" class="vg8k7bbhe"/><stop offset="1" class="w-7avbcrn"/></linearGradient><linearGradient id="ib9CIKn" x1="17.004" x2="19.332" y1="10.89" y2="11.052" gradientUnits="userSpaceOnUse"><stop class="hcvz7rbkn"/><stop offset="1" class="dq4m0ybwq"/></linearGradient><linearGradient id="iIWuN9d" x1="12.536" x2="14.865" y1="11.642" y2="11.804" gradientUnits="userSpaceOnUse"><stop class="hcvz7rbkn"/><stop offset="1" class="dq4m0ybwq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:breast-feeding-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a4385nb5a {
  stop-color: var(--svg-color--92626a, #92626A);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.aiaew87yw {
  d: path("M23.408 27.099a4.3 4.3 0 1 0 0-8.6c-2.375 0-3.553 1.925-3.553 4.3s1.178 4.3 3.553 4.3");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.aqne2ebmr {
  stop-color: var(--svg-color--b48474, #B48474);
}

.b8_m1dbzs {
  d: path("M19.106 10.2c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51s-.63-.03-.86-.23a.3.3 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.39");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.blqrnab2q {
  stop-color: var(--svg-color--826a56, #826A56);
}

.boy37thuw {
  d: path("M12.125 9.727c1.375-.263 2.39.359 2.672 1.125c-1.413.208-2.038.38-2.476.614z");
}

.bvctw1bkc {
  stop-color: var(--svg-color--9c69f1, #9C69F1);
}

.bz3ncuban {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.631 21.1c.344.634 1.031 2.28 1.031 3.78");
}

.bzrv_p78g {
  stop-color: var(--svg-color--44327f, #44327F);
  stop-opacity: 0;
}

.c_e6lvb0e {
  stop-color: var(--svg-color--44327f, #44327F);
}

.c14jvicyx {
  stop-color: var(--svg-color--603eb7, #603EB7);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.chcol9b3r {
  d: path("M17.152 10.8c.13.122.518.353 1.022.298s.947-.543 1.06-.727");
}

.cjbp-tbil {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.613 26.498c.273.906.367 2.164-.797 3.18");
}

.cs-jscxvs {
  d: path("M8.73 25.665h2.453c.425-.689 1.037-1.514 1.36-1.84a7 7 0 0 0-.532-1.663c-1.125.974-2.656 2.741-3.28 3.503");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.doqtch_8f {
  d: path("M13.57 17.002c-3.353 1.353-6.48 5.4-8.312 7.957c-.71.853-1.718 2.661-.086 4.978h9.18c.104-.703.154-1.981-.053-3.129c-.11-.612-.72-.996-1.342-.996h-1.196c.102-.265.73-1.357 1.801-1.936c.505-.274.854-.564 1.413-.887l.495-.287l.73-.42a6.03 6.03 0 0 1-.942-3.245v-1.452a5.2 5.2 0 0 1-1.689-.583");
}

.dq4m0ybwq {
  stop-color: var(--svg-color--533f3d, #533F3D);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dyjetvbhh {
  stop-color: var(--svg-color--b98c86, #B98C86);
  stop-opacity: 0;
}

.ea15stbaq {
  stop-color: var(--svg-color--594543, #594543);
  stop-opacity: 0;
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eoa632ltp {
  stop-color: var(--svg-color--9165d0, #9165D0);
}

.f_-cokbml {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m21.48 22.334l2.11 2.14");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fbwetlb3l {
  d: path("M10.746 25.739h1.57l.977-1.594c-1.675-.139-2.396 1.005-2.547 1.594");
}

.feugx5i3r {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M21.289 11.442a1.145 1.145 0 1 0-.436-2.248a1.145 1.145 0 0 0 .436 2.248");
}

.fft2fx5po {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.61 14.344a3.2 3.2 0 0 1-1.558-.073c-.162-.048-.287.152-.168.271a2.06 2.06 0 0 0 3.4-.659c.065-.16-.124-.293-.257-.188a3.2 3.2 0 0 1-1.417.649");
}

.fimw5lrwi {
  d: path("M25.578 29.938c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.fry0q78oh {
  d: path("M20.935 22.042a.64.64 0 0 1 .913.018a93 93 0 0 0 1.82 1.887a.05.05 0 0 0 .085-.04l-.089-.926a.67.67 0 0 1 1.32-.21l.692 3.103q.088.294.089.615c0 1.065-.766 1.95-1.777 2.136c-.697.2-1.485-.121-1.794-.308l-2.78-1.689a.632.632 0 0 1 .626-1.098l-.596-.428a.621.621 0 1 1 .737-1l.186.141l-.656-.52a.648.648 0 1 1 .837-.988l1.156 1.045l-.79-.853a.636.636 0 0 1 .02-.886");
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g8eqos3yo {
  d: path("M14.607 10.953c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51c-.31.06-.62-.03-.86-.22a.25.25 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.4");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gjutkou6f {
  d: path("M21.397 12.001a1.715 1.715 0 1 0-.652-3.367a1.715 1.715 0 0 0 .652 3.367");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h5ifffbxa {
  stop-color: var(--svg-color--bc9586, #BC9586);
}

.hcvz7rbkn {
  stop-color: var(--svg-color--533f3d, #533F3D);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i0xvywvie {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.61 14.344a3.2 3.2 0 0 1-1.558-.073c-.162-.048-.287.152-.168.271a2.06 2.06 0 0 0 3.4-.659c.065-.16-.124-.293-.257-.188a3.2 3.2 0 0 1-1.417.649Z");
}

.i4dibacwt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.808 25.865l1.843.922");
}

.i54m18vgp {
  stop-color: var(--svg-color--51e398, #51E398);
  stop-opacity: 0;
}

.i8x7p37cq {
  stop-color: var(--svg-color--603eb7, #603EB7);
  stop-opacity: 0;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iobnj4b7a {
  stop-color: var(--svg-color--5d372f, #5D372F);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-e6rp1-z {
  stop-color: var(--svg-color--896a51, #896A51);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jswq_j2dq {
  stop-color: var(--svg-color--34e38b, #34E38B);
}

.jyzijgb5l {
  stop-color: var(--svg-color--248571, #248571);
  stop-opacity: 0;
}

.k3_w4brwn {
  stop-color: var(--svg-color--896a51, #896A51);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kc6luf8ah {
  stop-color: var(--svg-color--7556b0, #7556B0);
}

.khg6a5-nz {
  stop-color: var(--svg-color--248571, #248571);
}

.khirl1bud {
  stop-color: var(--svg-color--caa28b, #CAA28B);
}

.klfo-1b4q {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.177 8.342l-.098.268za.286.286 0 0 1-.195.537l-.006-.002a1 1 0 0 0-.13-.038a3 3 0 0 0-.385-.072a2.4 2.4 0 0 0-1.14.121a.286.286 0 0 1-.205-.533a3 3 0 0 1 1.412-.155a3.5 3.5 0 0 1 .632.136l.011.004h.004z");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kzj-gwbkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.824 24.34l1.906 1.211");
}

.l1bz-r8iw {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M9.5 6.057c.47-.741 1.59-.96 2.126-.966l.676 1.27c-.272.01-.31.058-.47.29c.077 1.171-1.084 2.117-2.575 2.884c-.458-1.53-.369-2.512.243-3.478");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l99uylilx {
  stop-color: var(--svg-color--309972, #309972);
}

.la4e9obft {
  stop-color: var(--svg-color--ac7ff8, #AC7FF8);
}

.lk8w5cclk {
  stop-color: var(--svg-color--a176df, #A176DF);
}

.lo8r7sbbw {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.274 8.56c.322-.147 1.169-.268 1.807.024");
}

.lql_2ab8k {
  stop-color: var(--svg-color--594543, #594543);
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lzdnytbwv {
  stop-color: var(--svg-color--a673ff, #A673FF);
}

.m-nxtsi5k {
  stop-color: var(--svg-color--b6877d, #B6877D);
  stop-opacity: 0;
}

.md1t93b9l {
  d: path("M11.354 13.366a1.145 1.145 0 1 0-.436-2.247a1.145 1.145 0 0 0 .436 2.247");
}

.mdxlbkffu {
  d: path("M9.5 6.057c.47-.741 1.59-.96 2.126-.966l.676 1.27c-.272.01-.31.058-.47.29c.077 1.171-1.084 2.117-2.575 2.884c-.458-1.53-.369-2.512.243-3.478");
}

.mqicc-u0l {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
  stop-opacity: 0;
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n2a634bwb {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
}

.n7fe64b-m {
  stop-color: var(--svg-color--6a428c, #6A428C);
}

.nc2l1ubcn {
  d: path("M17.348 16.398c-.72 0-1.42.08-2.09.22v2.42c0 3.48 2.93 6.25 6.41 6.06l5.58-.31c-.7-4.74-4.86-8.39-9.9-8.39");
}

.nsuzlkbcm {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.601 9.189c-.353-.017-1.184.187-1.668.697");
}

.ny1a5-4af {
  stop-color: var(--svg-color--b0837c, #B0837C);
  stop-opacity: 0;
}

.nybv-x_bu {
  stop-color: var(--svg-color--51e398, #51E398);
}

.o3yqmrbrg {
  stop-color: var(--svg-color--885ebc, #885EBC);
  stop-opacity: 0;
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.oqa602b9h {
  stop-color: var(--svg-color--b58e83, #B58E83);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p9lf13b1j {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.104 10.124l-.004.004a.286.286 0 0 1-.382-.426h.001l.003-.003l.009-.008a2 2 0 0 1 .14-.11c.093-.07.228-.16.396-.253a3 3 0 0 1 1.367-.383a.286.286 0 0 1 .01.571a2.4 2.4 0 0 0-1.103.314a3 3 0 0 0-.437.294");
}

.pcy-27bbq {
  d: path("m10.44 11.006l.012-.003l-.064-.275l-.073-.319c-.171-.997.334-1.493.556-1.67l.05-.031q.026-.018.05-.032c.508-.364.871-.9.994-1.533l.046-.22a.281.281 0 0 1 .473-.146A4.12 4.12 0 0 0 16.16 7.88l3.37-.653c.188-.036 1.15-.128 1.458 1.164l.499 3.24c.439 2.958-1.47 5.371-4.265 5.913s-5.468-.984-6.165-3.892z");
}

.ps9fj4bvg {
  d: path("M13.808 3.266c-1.236-.032-2.071 1.356-2.11 1.819C13.519 8.58 16.265 7.839 18.955 7c1.61-.502 1.934.213 2.145.549c-.798-4.116-4.447-4.21-7.26-4.283z");
}

.q_rjf54ai {
  d: path("m13.45 23.852l.07-.038c.504-.273.896-.5 1.455-.824l.495-.287l.04-.023l.69-.397l-.005-.006c1.997-1.01 4.472-.3 5.603 1.672c1.18 2.04.48 4.64-1.56 5.8l-.3.18h-5.585c.103-.705.152-1.977-.054-3.12c-.11-.613-.72-.996-1.341-.996h-1.193q.071-.168.156-.33c.159-.287.425-.694.8-1.066q.326-.316.73-.565");
}

.qarzv5b-l {
  stop-color: var(--svg-color--37ba71, #37BA71);
}

.qd-vegb5y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m24.49 22.763l.813 3.711");
}

.qe03co1lx {
  d: path("M21.289 11.442a1.145 1.145 0 1 0-.436-2.248a1.145 1.145 0 0 0 .436 2.248");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qit_6iqhw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.667 5.037c.074.25.48 1.162.917 1.678");
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qlgfsfb2d {
  fill: var(--svg-color--642fc5, #642FC5);
  d: path("M25.578 29.938c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.qpwbhgbyy {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.354 13.366a1.145 1.145 0 1 0-.436-2.247a1.145 1.145 0 0 0 .436 2.247");
}

.qrasocbfu {
  stop-color: var(--svg-color--a176df, #A176DF);
  stop-opacity: 0;
}

.qtbzeirls {
  stop-color: var(--svg-color--a980f3, #A980F3);
}

.r3kdhjbzd {
  stop-color: var(--svg-color--9d5e7c, #9D5E7C);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.re_ifjj0z {
  fill: var(--svg-color--553836, #553836);
  d: path("M13.808 3.266c-1.236-.032-2.071 1.356-2.11 1.819C13.519 8.58 16.265 7.839 18.955 7c1.61-.502 1.934.213 2.145.549c-.798-4.116-4.447-4.21-7.26-4.283z");
}

.rflawqjsp {
  d: path("M27.515 27.443c-.013-.405-.165-2.417-.222-3.117l-2.825.18l-3.008 3.324c0 1.263.513 1.95.805 2.108h4.39c.97-.963.868-2.21.86-2.495");
}

.rfocsjb8y {
  stop-color: var(--svg-color--b69381, #B69381);
}

.rlw3b4b7i {
  stop-color: var(--svg-color--9565e9, #9565E9);
}

.rm6lemo-n {
  stop-color: var(--svg-color--3db155, #3DB155);
}

.rq4-grb6j {
  stop-color: var(--svg-color--b1817b, #B1817B);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s_1mgzhbo {
  stop-color: var(--svg-color--8d5d63, #8D5D63);
}

.s6rfugboe {
  stop-color: var(--svg-color--a8806b, #A8806B);
}

.sq95r4vix {
  stop-color: var(--svg-color--a476f3, #A476F3);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sz9ifbfqc {
  stop-color: var(--svg-color--9d5e7c, #9D5E7C);
  stop-opacity: 0;
}

.t-u7o5ykp {
  stop-color: var(--svg-color--8d5d63, #8D5D63);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t1s5t0bbn {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.564 11.143l-.37 1.917c-.044.388.3.7.686.626l.822-.16a.576.576 0 0 0 .403-.837l-.9-1.67c-.196-.371-.593-.295-.641.124");
}

.t34-m913i {
  d: path("M21.538 23.878a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tce23o4qc {
  stop-color: var(--svg-color--a980f3, #A980F3);
  stop-opacity: 0;
}

.tkcxzncwj {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
}

.tm8i9nrvx {
  stop-color: var(--svg-color--b58e83, #B58E83);
  stop-opacity: 0;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u5jw2ubor {
  stop-color: var(--svg-color--8a6557, #8A6557);
  stop-opacity: 0;
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u6mu-v3yl {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.69 6.433l-1.438.563a.733.733 0 1 1-.408-1.402l2.45-.475c1.448-.28 2.21 1.086 2.366 1.574a3.35 3.35 0 0 0-2.97-.26");
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uddy23wrg {
  stop-color: var(--svg-color--8a6557, #8A6557);
}

.ufx-nyb4s {
  stop-color: var(--svg-color--bd9678, #BD9678);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uny69rbro {
  stop-color: var(--svg-color--38aa6f, #38AA6F);
}

.up7b_htug {
  stop-color: var(--svg-color--ab84ee, #AB84EE);
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vg8k7bbhe {
  stop-color: var(--svg-color--3a2522, #3A2522);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vrjrrpcnz {
  stop-color: var(--svg-color--349373, #349373);
}

.vt94b84mi {
  d: path("M12.685 11.552c.13.122.518.353 1.021.298c.505-.054.947-.543 1.06-.727");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vyojtk_xf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m20.198 23.05l2.093 1.727");
}

.w-7avbcrn {
  stop-color: var(--svg-color--38221e, #38221E);
}

.w-wd4mb8i {
  stop-color: var(--svg-color--53ffa2, #53FFA2);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wvf_psbmu {
  d: path("M17.077 8.778c1.041-.327 2.4.235 2.4 1.624c-.671-.374-2.007-.518-2.482-.374z");
}

.wx449kb5h {
  stop-color: var(--svg-color--92626a, #92626A);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x9_lkhbgw {
  d: path("M11.442 13.93a1.715 1.715 0 1 0-.652-3.367a1.715 1.715 0 0 0 .652 3.367");
}

.xi960zbzc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.3 29.04c.886.054 3.107.13 4.898 0");
}

.xjvfic_gd {
  stop-color: var(--svg-color--309972, #309972);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y_genvbtz {
  stop-color: var(--svg-color--b28280, #B28280);
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y3i4g-bee {
  d: path("M7.668 27.098h6.034v2.188H7.668z");
}

.y3p2-pbto {
  stop-color: var(--svg-color--79513f, #79513F);
  stop-opacity: 0;
}

.y5wj0cb9b {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.546 10.996l-.211 1.886c-.043.388.3.701.686.626l.823-.159a.577.577 0 0 0 .403-.837l-.9-1.671c-.196-.371-.752-.263-.8.155");
}

.y9owwpbix {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
  stop-opacity: 0;
}

.yasfqbb-e {
  stop-color: var(--svg-color--a673ff, #A673FF);
  stop-opacity: 0;
}

.ybai0acxr {
  stop-color: var(--svg-color--826a56, #826A56);
  stop-opacity: 0;
}

.yddo6xgmq {
  stop-color: var(--svg-color--ad827e, #AD827E);
}

.yf_lw100d {
  fill: var(--svg-color--a87d73, #A87D73);
  d: path("M14.318 29.937h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.yfvjw8b3h {
  d: path("M23.825 11.315c.134-.499.152-1.03.05-1.56a3.5 3.5 0 0 0-.546-1.31l.005-.002a3.4 3.4 0 0 0-.398-.48l-.003-.003a3.45 3.45 0 0 1-.91-1.746l-.002-.01a3.517 3.517 0 0 0-4.12-2.785a.57.57 0 0 1-.525-.15a3.52 3.52 0 0 0-3.085-.897a3.52 3.52 0 0 0-2.528 1.984a.6.6 0 0 1-.43.336l-.088.018A3.517 3.517 0 0 0 8.55 8.813l.002.01c.128.657.062 1.34-.191 1.96l-.002.005a3.52 3.52 0 0 0 .427 3.44a.55.55 0 0 1 .093.477a3.5 3.5 0 0 0-.054 1.538a3.425 3.425 0 0 0 4.02 2.715l8.981-1.74a3.425 3.425 0 0 0 2.715-4.02a3.5 3.5 0 0 0-.624-1.407a.55.55 0 0 1-.092-.476m-13.372-.311l-.013.002l1.732 2.222c.697 2.908 1.274-.246 4.07-.788c2.795-.542 4.647 2.487 4.207-.471l.54-3.576c-.308-1.292-1.27-1.2-1.458-1.164l-3.37.653a4.12 4.12 0 0 1-3.676-1.105a.281.281 0 0 0-.473.147l-.047.22a2.46 2.46 0 0 1-.994 1.533q-.023.013-.05.032q-.026.018-.05.031c-.221.176-.726.673-.555 1.67l.072.318z");
}

.yit44gm3t {
  stop-color: var(--svg-color--9165d2, #9165D2);
  stop-opacity: 0;
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yjxrkgq7v {
  d: path("m15.546 10.996l-.211 1.886c-.043.388.3.701.686.626l.823-.159a.577.577 0 0 0 .403-.837l-.9-1.671c-.196-.371-.752-.263-.8.155");
}

.ynj51cbvd {
  stop-color: var(--svg-color--b69381, #B69381);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z2-7n818b {
  stop-color: var(--svg-color--ad827e, #AD827E);
  stop-opacity: 0;
}

.zts9dnb_c {
  d: path("M14.318 29.937h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.zufjkvb9h {
  stop-color: var(--svg-color--b48474, #B48474);
  stop-opacity: 0;
}

</style>
