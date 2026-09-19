<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iCVKUfb)" class="d2kvgvbvc"><path fill="url(#iomrQNd)" class="ti5ns9bti"/><path fill="url(#igkvsOa)" class="ti5ns9bti"/><path fill="url(#i46OKDb)" class="ti5ns9bti"/><path fill="url(#ioZYkud)" class="ti5ns9bti"/><path fill="url(#i68Ztwd)" class="ti5ns9bti"/><path fill="url(#iVYhJFY)" class="ti5ns9bti"/><path fill="url(#ibN0ucc)" class="ti5ns9bti"/><path fill="url(#iyPbCqc)" class="ti5ns9bti"/><path fill="url(#ijk4jRb)" class="ti5ns9bti"/><path fill="url(#i4CWZdd)" class="ti5ns9bti"/><path fill="url(#iOZ0Kvc)" class="ti5ns9bti"/></g><path class="fe9o-1b2z"/><path fill="url(#ihXqP6d)" class="n7msnz5sl"/><path fill="url(#iFUbMCd)" class="r4flqbcjd"/><path fill="url(#iG3Eifc)" class="r4flqbcjd"/><path fill="url(#irvpIqb)" class="r4flqbcjd"/><path fill="url(#icOp5Bb)" class="r4flqbcjd"/><path fill="url(#iP4QOlc)" class="i_pl4ibxb"/><path fill="url(#ii8nzKe)" class="i_pl4ibxb"/><path fill="url(#iKF1tOH)" class="i_pl4ibxb"/><g filter="url(#iX61rGb)"><path fill="url(#iZD9j1c)" class="pyrigobmp"/><path fill="url(#ibhVwgM)" class="pyrigobmp"/><path fill="url(#iDbA9Db)" class="pyrigobmp"/><path fill="url(#iwlo8ne)" class="pyrigobmp"/></g><g filter="url(#icxYJ7l)"><path fill="url(#i496HOb)" class="hg-ee5v6z"/></g><g filter="url(#ijJJTxd)"><path stroke="url(#i5rlBse)" class="qbagijrnw"/></g><g filter="url(#iLhk9Vc)"><path fill="url(#i0pyKxd)" class="i8omvjbjm"/></g><g filter="url(#iXGXyPd)"><path stroke="url(#iP4SV8d)" class="t25c-kbzs"/></g><g filter="url(#iNbjcob)"><path fill="url(#idBvuGd)" class="jbyb7zbsw"/><path fill="url(#i91dnRm)" class="jbyb7zbsw"/></g><g filter="url(#iGuBQQc)"><path class="sh3vt1bfc"/><path fill="url(#i4m5ute)" class="ip6ihtb0n"/><path fill="url(#iUaHhjc)" class="ip6ihtb0n"/><path fill="url(#iWy3znc)" class="ip6ihtb0n"/><path fill="url(#ivrRD6b)" class="ip6ihtb0n"/></g><path fill="url(#ibRS7ga)" class="ud_lf2bqt"/><path fill="url(#iPqDY4W)" class="ud_lf2bqt"/><path fill="url(#iDGyZKb)" class="cjvt5sh_p"/><path fill="url(#iKtRRtb)" class="cjvt5sh_p"/><g filter="url(#inM02gP)"><path fill="url(#ihhzwte)" class="y3st6e2hh"/><path fill="url(#iKfvXSd)" class="y3st6e2hh"/><path fill="url(#iC7TjFc)" class="y3st6e2hh"/><path fill="url(#ipfjlhS)" class="y3st6e2hh"/><path fill="url(#ie6eoTb)" class="y3st6e2hh"/></g><path fill="url(#iyWh8Zb)" class="y3st6e2hh"/><g filter="url(#iAB619c)"><path fill="url(#ioNJkOb)" class="lxai1jb9h"/></g><g filter="url(#ihddUKe)"><path stroke="url(#i4I43ac)" class="iul9049lf"/></g><g filter="url(#ibTTqLd)"><path stroke="url(#ixFk5le)" class="ag592_bob"/></g><g filter="url(#iuVdXTc)"><path stroke="url(#ic99YXb)" class="j1-shybhj"/></g><g filter="url(#iA1WRxb)"><path stroke="url(#i3ZKl3d)" class="x9l2kpb_x"/></g><g filter="url(#iEp0nFz)"><path stroke="url(#iUOebAe)" class="hp07t2bmv"/></g><g filter="url(#itgtHle)"><path stroke="url(#ioMNgob)" class="gnlgf5bza"/></g><g filter="url(#i8fQjHd)"><path fill="url(#iFuUrae)" class="ogwyqlrze"/></g><g filter="url(#iPSaldc)"><path fill="url(#iWhmLid)" class="v8goawbnm"/><path fill="url(#i4s9EAe)" class="v8goawbnm"/></g><g filter="url(#iWenCKc)"><path class="o6qx60bff"/><path fill="url(#i6MyUPe)" class="eww29tbma"/></g><g filter="url(#iNfeNsZ)"><path class="ia_qwfb7r"/><path fill="url(#idjchAc)" class="wcgqkbbxt"/></g><g filter="url(#iBq1fbe)"><path fill="url(#ihYbfod)" class="jcl0g0bfl"/><path fill="url(#iLEiKCc)" class="jcl0g0bfl"/><path fill="url(#i3zIXdc)" class="jcl0g0bfl"/><path fill="url(#ilkjnHd)" class="jcl0g0bfl"/><path fill="url(#ixORvbc)" class="jcl0g0bfl"/></g><path fill="url(#iDlH57b)" class="jcl0g0bfl"/><path fill="url(#iwLWxre)" class="jcl0g0bfl"/><g filter="url(#itDx22c)"><path class="iehphloax"/></g><g filter="url(#ifovyjw)"><path class="vy8gdf6bj"/><path fill="url(#iwOgshe)" class="gnlbl7n9s"/><path fill="url(#ihorMCe)" class="gnlbl7n9s"/><path fill="url(#i2sDYLe)" class="gnlbl7n9s"/><path fill="url(#iSzUwVc)" class="gnlbl7n9s"/></g><g filter="url(#iLs7J1s)"><path fill="url(#ixJdiuc)" class="thhcukb0j"/></g><g filter="url(#iGSxkOe)"><path stroke="url(#icmS7fe)" class="rq62sfb9x"/></g><path class="d-2-zzrvn"/><g filter="url(#is2sRYc)"><path class="hfsix9bri"/><path fill="url(#iPJtZIe)" class="w9ixeebma"/></g><g filter="url(#i5qyk1b)"><path class="c93k2wdbi"/><path fill="url(#iw304ne)" class="mm2ngwx_x"/><path fill="url(#iCfR41b)" class="mm2ngwx_x"/></g><g filter="url(#i41CEln)"><path stroke="url(#ibCpORn)" class="acbhe55so"/></g><g filter="url(#iQBcbVd)"><path class="dhxck6bve"/></g><g filter="url(#iVhwwPb)"><path fill="url(#izBn8dd)" class="jaxnvvbws"/></g><g filter="url(#i36eT5c)"><path fill="url(#iOcT51d)" class="ddy80qbfp"/></g><path fill="url(#irZPnCb)" class="yn-qmdb0b"/><path fill="url(#irLDmwe)" class="eckg1-bse"/><g filter="url(#iGtM87d)" class="tryqaac1t"><path stroke="url(#iPaTTsc)" class="a3-qrac0v"/><path stroke="url(#iGghrzd)" class="a3-qrac0v"/></g><g filter="url(#imeJqYc)" class="tryqaac1t"><path stroke="url(#iEWXXyV)" class="cywo8acqu"/><path stroke="url(#iGLzCfc)" class="cywo8acqu"/></g><g filter="url(#i6Ljh3c)"><path class="cj2ro8btx"/></g><g filter="url(#iqDc1YF)"><path clip-rule="evenodd" class="op1ihkbup"/></g><g filter="url(#i6KZcbc)"><path class="j5b5asq6d"/></g><g filter="url(#iBJ9kee)"><path class="xgm21db5v"/></g><defs><radialGradient id="igkvsOa" cx="0" cy="0" r="1" gradientTransform="rotate(87.25 .703 15.395)scale(4.8934 6.11286)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i46OKDb" cx="0" cy="0" r="1" gradientTransform="rotate(135.715 3.57 10.06)scale(3.70012 4.86167)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ioZYkud" cx="0" cy="0" r="1" gradientTransform="rotate(117.116 1.629 9.535)scale(2.2901 1.75848)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i68Ztwd" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.97 8.862)scale(2.6336 1.85514)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iVYhJFY" cx="0" cy="0" r="1" gradientTransform="rotate(51.982 1.735 12.698)scale(3.1432 4.36324)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ibN0ucc" cx="0" cy="0" r="1" gradientTransform="rotate(124.709 9.405 7.417)scale(2.16906 3.03123)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iyPbCqc" cx="0" cy="0" r="1" gradientTransform="rotate(153.49 10.738 7.258)scale(2.04309 4.2607)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ijk4jRb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8142 1.2722 -1.62059 -3.58487 23.605 12.655)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i4CWZdd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.132 12.147 -2.469)scale(2.97971 2.35678)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iOZ0Kvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.6045 -.12067 .19553 2.59975 9.288 11.517)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ihXqP6d" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 1.9893 19.511 29.919)" gradientUnits="userSpaceOnUse"><stop class="n2a634bwb"/><stop offset="1" class="y9owwpbix"/></radialGradient><radialGradient id="iFUbMCd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50378 0 0 -5.6875 21.761 19.143)" gradientUnits="userSpaceOnUse"><stop class="kqmp-xbxk"/><stop offset="1" class="vx8r8sbmx"/></radialGradient><radialGradient id="iG3Eifc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.983 12.465 9.015)scale(2.5864 3.5607)" gradientUnits="userSpaceOnUse"><stop class="bm5kr2bhy"/><stop offset="1" class="dl9ionbqq"/></radialGradient><radialGradient id="irvpIqb" cx="0" cy="0" r="1" gradientTransform="rotate(64.824 -4.749 21.026)scale(2.19716 4.32137)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="mdzncccgv"/><stop offset="1" class="c6jtw0hjs"/></radialGradient><radialGradient id="icOp5Bb" cx="0" cy="0" r="1" gradientTransform="matrix(2.21876 -7 9.86052 3.12544 19.268 23.134)" gradientUnits="userSpaceOnUse"><stop offset=".783" class="gl09nnb4p"/><stop offset="1" class="uqpfdhbxh"/></radialGradient><radialGradient id="ii8nzKe" cx="0" cy="0" r="1" gradientTransform="matrix(2.79688 2.04686 -1.95763 2.67496 23.418 27.362)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tkcxzncwj"/><stop offset="1" class="mqicc-u0l"/></radialGradient><radialGradient id="iKF1tOH" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.3125 -2.12008 2.12008 22.012 27.799)" gradientUnits="userSpaceOnUse"><stop class="c14jvicyx"/><stop offset="1" class="i8x7p37cq"/></radialGradient><radialGradient id="ibhVwgM" cx="0" cy="0" r="1" gradientTransform="rotate(126.08 3.125 12.122)scale(4.98797 9.68383)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7fe64b-m"/><stop offset="1" class="o3yqmrbrg"/></radialGradient><radialGradient id="iDbA9Db" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45313 -.6875 0 13.87 28.298)" gradientUnits="userSpaceOnUse"><stop class="la4e9obft"/><stop offset="1" class="sq95r4vix"/></radialGradient><radialGradient id="iwlo8ne" cx="0" cy="0" r="1" gradientTransform="rotate(-117.519 14.634 7.163)scale(1.35267 2.95016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="kc6luf8ah"/><stop offset="1" class="yit44gm3t"/></radialGradient><radialGradient id="i496HOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 -1.6057 .88152 .74629 11.761 25.72)" gradientUnits="userSpaceOnUse"><stop class="c_e6lvb0e"/><stop offset="1" class="bzrv_p78g"/></radialGradient><radialGradient id="i5rlBse" cx="0" cy="0" r="1" gradientTransform="rotate(-162.16 15.543 12.058)scale(.71402 1.53504)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></radialGradient><radialGradient id="i91dnRm" cx="0" cy="0" r="1" gradientTransform="rotate(163.67 9.09 15.49)scale(5.1125 7.55864)" gradientUnits="userSpaceOnUse"><stop class="khg6a5-nz"/><stop offset="1" class="jyzijgb5l"/></radialGradient><radialGradient id="iUaHhjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 -1.0625 .82137 1.8964 14.8 30.717)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="x79fyur6x"/><stop offset="1" class="w7g29ccgc"/><stop offset="1" class="pkg2022aq"/></radialGradient><radialGradient id="iWy3znc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .36719 -.26111 -.32778 16.792 26.327)" gradientUnits="userSpaceOnUse"><stop class="mn_1abcya"/><stop offset="1" class="g_yd9fbim"/></radialGradient><radialGradient id="ivrRD6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 0 0 -.59662 16.175 28.197)" gradientUnits="userSpaceOnUse"><stop class="tcaw_fkkx"/><stop offset="1" class="oyi32_b2v"/></radialGradient><radialGradient id="ibRS7ga" cx="0" cy="0" r="1" gradientTransform="rotate(154.496 10.795 13.802)scale(3.77401 4.40797)" gradientUnits="userSpaceOnUse"><stop class="w-wd4mb8i"/><stop offset="1" class="jswq_j2dq"/></radialGradient><radialGradient id="iPqDY4W" cx="0" cy="0" r="1" gradientTransform="rotate(42.983 -15.978 40.624)scale(5.22527)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="i54m18vgp"/><stop offset=".995" class="nybv-x_bu"/></radialGradient><radialGradient id="iKtRRtb" cx="0" cy="0" r="1" gradientTransform="matrix(.39062 -3.01563 4.79304 .62086 19.418 24.392)" gradientUnits="userSpaceOnUse"><stop class="l99uylilx"/><stop offset="1" class="xjvfic_gd"/></radialGradient><radialGradient id="ihhzwte" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.355 27.799)" gradientUnits="userSpaceOnUse"><stop class="ilmgd4m9e"/><stop offset="1" class="u75zz_obl"/></radialGradient><radialGradient id="iKfvXSd" cx="0" cy="0" r="1" gradientTransform="rotate(34.714 -27.637 42.775)scale(3.03183 .43734)" gradientUnits="userSpaceOnUse"><stop class="uamj4xkkk"/><stop offset="1" class="moyus9lkj"/></radialGradient><radialGradient id="iC7TjFc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89062 2.04687 -.34125 .3152 20.784 22.524)" gradientUnits="userSpaceOnUse"><stop class="uamj4xkkk"/><stop offset="1" class="moyus9lkj"/></radialGradient><radialGradient id="ipfjlhS" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 1.26562 -.211 .3178 19.721 25.165)" gradientUnits="userSpaceOnUse"><stop class="uamj4xkkk"/><stop offset="1" class="moyus9lkj"/></radialGradient><radialGradient id="ie6eoTb" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 2.11719 -.35298 .03386 23.69 22.36)" gradientUnits="userSpaceOnUse"><stop class="uamj4xkkk"/><stop offset="1" class="moyus9lkj"/></radialGradient><radialGradient id="iWhmLid" cx="0" cy="0" r="1" gradientTransform="rotate(-58.393 20.635 -12.883)scale(2.91115 3.55438)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="i4s9EAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.5177 .52205 -.14759 .42908 20.876 8.555)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i6MyUPe" cx="0" cy="0" r="1" gradientTransform="matrix(1.55942 -.40455 .31625 1.21904 20.506 10.561)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="idjchAc" cx="0" cy="0" r="1" gradientTransform="rotate(169.711 4.988 6.575)scale(1.28411 1.01301)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="ihYbfod" cx="0" cy="0" r="1" gradientTransform="rotate(144.955 7.783 8.05)scale(7.62048 10.1999)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iLEiKCc" cx="0" cy="0" r="1" gradientTransform="rotate(162.284 8.826 7.277)scale(3.71401 4.09961)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i3zIXdc" cx="0" cy="0" r="1" gradientTransform="matrix(.6488 -4.21435 5.34723 .8232 14.686 18.841)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ilkjnHd" cx="0" cy="0" r="1" gradientTransform="rotate(101.627 3.391 12.614)scale(6.44311 11.7243)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="ixORvbc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.97227 2.73128 -4.70242 -12.0041 18.009 12.184)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iDlH57b" cx="0" cy="0" r="1" gradientTransform="rotate(169.711 10.172 6.393)scale(1.36761 6.85843)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iwLWxre" cx="0" cy="0" r="1" gradientTransform="matrix(2.13434 3.93831 -6.86102 3.71829 12.357 4.85)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iwOgshe" cx="0" cy="0" r="1" gradientTransform="rotate(-112.853 12.604 .6)scale(2.2283 .68674)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iSzUwVc" cx="0" cy="0" r="1" gradientTransform="rotate(169.713 7.796 7.11)scale(.82932 .23186)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iPJtZIe" cx="0" cy="0" r="1" gradientTransform="matrix(.79758 -3.12463 1.59849 .40802 9.447 9.509)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iw304ne" cx="0" cy="0" r="1" gradientTransform="rotate(105.394 7.193 7.55)scale(5.18503 8.47722)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iCfR41b" cx="0" cy="0" r="1" gradientTransform="matrix(.03964 1.47136 -3.16553 .08528 14.67 3.328)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iGghrzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 19.144 10.411)" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ql2-nbc9p"/><stop offset="1" class="ns3cxsbdp"/></radialGradient><radialGradient id="iGLzCfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 14.677 11.163)" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ql2-nbc9p"/><stop offset="1" class="ns3cxsbdp"/></radialGradient><filter id="iCVKUfb" width="16.711" height="17.401" x="7.965" y="1.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="iX61rGb" width="12.107" height="12.935" x="4.292" y="16.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="icxYJ7l" width="3.547" height="2.605" x="10.246" y="23.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".25"/></filter><filter id="ijJJTxd" width="1.338" height="3.484" x="25.65" y="26.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".05"/></filter><filter id="iLhk9Vc" width="8.034" height="4.188" x="6.668" y="26.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".5"/></filter><filter id="iXGXyPd" width="1.907" height="4.376" x="11.205" y="20.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".125"/></filter><filter id="iNbjcob" width="10.856" height="8.359" x="11.765" y="21.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="iGuBQQc" width="6.652" height="4.473" x="14.118" y="25.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.556863 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="inM02gP" width="6.654" height="7.23" x="19.111" y="21.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.513726 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="iAB619c" width="5.813" height="5.503" x="7.73" y="21.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".5"/></filter><filter id="ihddUKe" width="3.309" height="3.341" x="20.88" y="21.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".2"/></filter><filter id="ibTTqLd" width="2.013" height="4.911" x="23.891" y="22.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".2"/></filter><filter id="iuVdXTc" width="3.294" height="2.926" x="19.598" y="22.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".2"/></filter><filter id="iA1WRxb" width="3.106" height="2.411" x="19.224" y="23.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".2"/></filter><filter id="iEp0nFz" width="3.043" height="2.122" x="19.208" y="25.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".2"/></filter><filter id="itgtHle" width="5.798" height=".972" x="14.85" y="28.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".15"/></filter><filter id="i8fQjHd" width="3.575" height="3.425" x="9.269" y="10.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="iPSaldc" width="3.425" height="3.675" x="19.228" y="8.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="iWenCKc" width="3.286" height="3.286" x="19.297" y="8.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".25"/></filter><filter id="iNfeNsZ" width="3.086" height="3.086" x="9.458" y="10.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".2"/></filter><filter id="iBq1fbe" width="11.221" height="11.381" x="10.174" y="6.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="itDx22c" width="2.983" height="3.911" x="14.537" y="10.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".25"/></filter><filter id="ifovyjw" width="2.483" height="3.4" x="14.93" y="10.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".125"/></filter><filter id="iLs7J1s" width="2.483" height="3.4" x="14.872" y="10.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".125"/></filter><filter id="iGSxkOe" width="3.862" height="1.899" x="14.47" y="13.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".05"/></filter><filter id="is2sRYc" width="4.146" height="5.208" x="8.589" y="4.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/><feGaussianBlur result="effect2_foregroundBlur_4002_3509" stdDeviation=".15"/></filter><filter id="i5qyk1b" width="9.903" height="4.947" x="11.348" y="2.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/><feGaussianBlur result="effect2_foregroundBlur_4002_3509" stdDeviation=".125"/></filter><filter id="i41CEln" width="1.495" height="2.287" x="11.316" y="4.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".1"/></filter><filter id="iQBcbVd" width="6.895" height="3.431" x="14.428" y="4.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".375"/></filter><filter id="iVhwwPb" width="3.89" height="2.988" x="11.525" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".3"/></filter><filter id="i36eT5c" width="3.682" height="2.915" x="16.395" y="8.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".3"/></filter><filter id="iGtM87d" width="2.582" height="1.236" x="16.902" y="10.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".075"/></filter><filter id="imeJqYc" width="2.582" height="1.236" x="12.435" y="10.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".075"/></filter><filter id="i6Ljh3c" width="2.506" height="1.433" x="11.514" y="8.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="iqDc1YF" width="2.629" height=".931" x="16.802" y="7.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3509"/></filter><filter id="i6KZcbc" width="2.404" height=".79" x="16.844" y="8.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".1"/></filter><filter id="iBJ9kee" width="2.273" height="1.277" x="11.524" y="8.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3509" stdDeviation=".1"/></filter><linearGradient id="iomrQNd" x1="19.479" x2="14.75" y1="3.108" y2="17.597" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iP4QOlc" x1="26.793" x2="24.491" y1="25.08" y2="29.919" gradientUnits="userSpaceOnUse"><stop class="up7b_htug"/><stop offset="1" class="bvctw1bkc"/></linearGradient><linearGradient id="iZD9j1c" x1="15.261" x2="6.793" y1="19.235" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="eoa632ltp"/><stop offset="1" class="rlw3b4b7i"/></linearGradient><linearGradient id="i0pyKxd" x1="13.48" x2="7.929" y1="28.923" y2="28.899" gradientUnits="userSpaceOnUse"><stop class="lzdnytbwv"/><stop offset="1" class="yasfqbb-e"/></linearGradient><linearGradient id="iP4SV8d" x1="13.155" x2="13.105" y1="24.311" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></linearGradient><linearGradient id="idBvuGd" x1="21.355" x2="14.293" y1="27.643" y2="27.205" gradientUnits="userSpaceOnUse"><stop class="vrjrrpcnz"/><stop offset="1" class="qarzv5b-l"/></linearGradient><linearGradient id="i4m5ute" x1="18.565" x2="18.55" y1="30.072" y2="29.259" gradientUnits="userSpaceOnUse"><stop offset=".204" class="q1m6mtlky"/><stop offset="1" class="vbtyscd-k"/></linearGradient><linearGradient id="iDGyZKb" x1="21.668" x2="20.168" y1="18.639" y2="23.235" gradientUnits="userSpaceOnUse"><stop class="rm6lemo-n"/><stop offset=".635" class="uny69rbro"/></linearGradient><linearGradient id="iyWh8Zb" x1="25.558" x2="24.87" y1="25.255" y2="25.405" gradientUnits="userSpaceOnUse"><stop offset=".049" class="qcigj0wzj"/><stop offset="1" class="cw7wini3d"/></linearGradient><linearGradient id="ioNJkOb" x1="10.636" x2="13.293" y1="25.646" y2="22.399" gradientUnits="userSpaceOnUse"><stop class="lk8w5cclk"/><stop offset="1" class="qrasocbfu"/></linearGradient><linearGradient id="i4I43ac" x1="22.142" x2="24.279" y1="22.813" y2="24.668" gradientUnits="userSpaceOnUse"><stop offset=".076" class="vrywjrb0z"/><stop offset="1" class="a-ksimo1j"/></linearGradient><linearGradient id="ixFk5le" x1="24.746" x2="26.137" y1="23.609" y2="23.877" gradientUnits="userSpaceOnUse"><stop offset=".076" class="vrywjrb0z"/><stop offset="1" class="a-ksimo1j"/></linearGradient><linearGradient id="ic99YXb" x1="20.855" x2="22.592" y1="23.433" y2="25.288" gradientUnits="userSpaceOnUse"><stop offset=".076" class="vrywjrb0z"/><stop offset="1" class="a-ksimo1j"/></linearGradient><linearGradient id="i3ZKl3d" x1="20.422" x2="21.581" y1="24.604" y2="26.21" gradientUnits="userSpaceOnUse"><stop offset=".076" class="vrywjrb0z"/><stop offset="1" class="a-ksimo1j"/></linearGradient><linearGradient id="iUOebAe" x1="20.387" x2="21.186" y1="26.061" y2="27.467" gradientUnits="userSpaceOnUse"><stop offset=".076" class="vrywjrb0z"/><stop offset="1" class="a-ksimo1j"/></linearGradient><linearGradient id="ioMNgob" x1="19.922" x2="15.689" y1="29.02" y2="28.964" gradientUnits="userSpaceOnUse"><stop class="rug17304c"/><stop offset="1" class="baxddibyt"/></linearGradient><linearGradient id="iFuUrae" x1="9.313" x2="12.411" y1="12.566" y2="12.004" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ihorMCe" x1="15.157" x2="16.14" y1="12.851" y2="12.672" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i2sDYLe" x1="16.292" x2="16.176" y1="13.509" y2="12.87" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ixJdiuc" x1="15.706" x2="15.961" y1="10.508" y2="11.871" gradientUnits="userSpaceOnUse"><stop class="xaulv1bog"/><stop offset="1" class="th144cwik"/></linearGradient><linearGradient id="icmS7fe" x1="15.445" x2="15.793" y1="15.187" y2="14.353" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="ibCpORn" x1="11.682" x2="12.494" y1="5.338" y2="6.568" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="izBn8dd" x1="14.352" x2="11.665" y1="10.566" y2="10.275" gradientUnits="userSpaceOnUse"><stop class="gbf1_y03d"/><stop offset="1" class="bmyc5db9w"/></linearGradient><linearGradient id="iOcT51d" x1="19.092" x2="15.618" y1="10.036" y2="8.882" gradientUnits="userSpaceOnUse"><stop offset=".394" class="xpf_69b1t"/><stop offset="1" class="rf88abbhx"/><stop offset="1" class="sjjdjlu1h"/></linearGradient><linearGradient id="irZPnCb" x1="17.784" x2="19.315" y1="11.515" y2="10.39" gradientUnits="userSpaceOnUse"><stop offset=".048" class="kpx6jhb5u"/><stop offset="1" class="wpapq1b-u"/></linearGradient><linearGradient id="irLDmwe" x1="13.286" x2="14.824" y1="12.279" y2="11.156" gradientUnits="userSpaceOnUse"><stop offset=".048" class="kpx6jhb5u"/><stop offset="1" class="wpapq1b-u"/></linearGradient><linearGradient id="iPaTTsc" x1="17.003" x2="19.332" y1="10.871" y2="11.033" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iEWXXyV" x1="12.536" x2="14.865" y1="11.623" y2="11.785" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:breast-feeding-light" /></template>
<style>
.a-ksimo1j {
  stop-color: var(--svg-color--f1caba, #F1CABA);
  stop-opacity: 0;
}

.a3-qrac0v {
  d: path("M17.152 10.781c.13.122.518.353 1.022.298s.947-.543 1.06-.727");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.acbhe55so {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.617 4.979c.07.25.465 1.166.895 1.686");
}

.ag592_bob {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m24.49 22.744l.813 3.711");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.baxddibyt {
  stop-color: var(--svg-color--e9bfb9, #E9BFB9);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bm5kr2bhy {
  stop-color: var(--svg-color--ceab8b, #CEAB8B);
}

.bmyc5db9w {
  stop-color: var(--svg-color--d59c8f, #D59C8F);
  stop-opacity: 0;
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bvctw1bkc {
  stop-color: var(--svg-color--9c69f1, #9C69F1);
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

.c6jtw0hjs {
  stop-color: var(--svg-color--d29379, #D29379);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c93k2wdbi {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M13.774 3.236c-1.233-.046-2.083 1.33-2.126 1.791c1.775 3.512 4.524 2.803 7.219 1.998c1.613-.482 1.928.236 2.134.573c-.748-4.117-4.389-4.255-7.196-4.36z");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj2ro8btx {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.992 10.063l-.004.004a.285.285 0 0 1-.377-.43h.002l.003-.003l.009-.008a2 2 0 0 1 .14-.108c.095-.068.23-.158.399-.248a3 3 0 0 1 1.37-.366a.285.285 0 0 1 .003.57a2.4 2.4 0 0 0-1.105.3a3 3 0 0 0-.42.272z");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cjvt5sh_p {
  d: path("M21.538 23.859a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cw7wini3d {
  stop-color: var(--svg-color--efc1b2, #EFC1B2);
  stop-opacity: 0;
}

.cywo8acqu {
  d: path("M12.685 11.533c.13.122.517.353 1.021.298s.947-.543 1.06-.727");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d-2-zzrvn {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.44 14.326a3.2 3.2 0 0 1-1.554-.09c-.16-.05-.288.148-.17.268a2.056 2.056 0 0 0 3.401-.618c.067-.159-.12-.294-.254-.19a3.2 3.2 0 0 1-1.423.63");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.ddy80qbfp {
  d: path("M17.077 8.759c1.041-.327 2.4.235 2.4 1.624c-.672-.374-2.007-.518-2.482-.374z");
}

.dhxck6bve {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.612 6.444l-1.443.545a.732.732 0 1 1-.39-1.405l2.45-.445c1.45-.263 2.195 1.11 2.344 1.6a3.35 3.35 0 0 0-2.962-.295");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dl9ionbqq {
  stop-color: var(--svg-color--ceab8b, #CEAB8B);
  stop-opacity: 0;
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.eckg1-bse {
  d: path("M14.607 10.934c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51c-.31.06-.62-.03-.86-.22a.25.25 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.4");
}

.eoa632ltp {
  stop-color: var(--svg-color--9165d0, #9165D0);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eww29tbma {
  d: path("M21.145 11.485a1.143 1.143 0 1 0-.408-2.249a1.143 1.143 0 0 0 .408 2.25");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.fe9o-1b2z {
  fill: var(--svg-color--642fc5, #642FC5);
  d: path("M25.578 29.919c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g_yd9fbim {
  stop-color: var(--svg-color--e9bcaf, #E9BCAF);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gbf1_y03d {
  stop-color: var(--svg-color--d59c8f, #D59C8F);
}

.gl09nnb4p {
  stop-color: var(--svg-color--e4b89b, #E4B89B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gnlbl7n9s {
  d: path("m15.418 10.973l-.233 1.881a.574.574 0 0 0 .678.633l.823-.15a.576.576 0 0 0 .412-.83l-.88-1.68c-.19-.372-.747-.27-.8.146");
}

.gnlgf5bza {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.3 29.02c.886.055 3.107.13 4.898 0");
}

.hfsix9bri {
  fill: var(--svg-color--232121, #232121);
  d: path("M9.442 5.973c.478-.735 1.599-.94 2.133-.94l.66 1.276c-.272.007-.491.143-.654.373c-.23 1.404-1.712 2.425-2.423 2.76c-.44-1.534-.339-2.513.284-3.47");
}

.hg-ee5v6z {
  d: path("M10.746 25.72h1.57l.977-1.594c-1.675-.139-2.396 1.005-2.547 1.594");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hp07t2bmv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.808 25.846l1.843.922");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_pl4ibxb {
  d: path("M27.515 27.424c-.013-.405-.165-2.417-.222-3.117l-2.825.18l-3.008 3.324c0 1.263.513 1.95.805 2.108h4.39c.969-.963.868-2.21.86-2.495");
}

.i54m18vgp {
  stop-color: var(--svg-color--51e398, #51E398);
  stop-opacity: 0;
}

.i8omvjbjm {
  d: path("M7.668 27.079h6.034v2.188H7.668z");
}

.i8x7p37cq {
  stop-color: var(--svg-color--603eb7, #603EB7);
  stop-opacity: 0;
}

.ia_qwfb7r {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.205 13.29a1.143 1.143 0 1 0-.408-2.249a1.143 1.143 0 0 0 .408 2.249");
}

.iehphloax {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.434 11.12l-.393 1.91a.574.574 0 0 0 .678.633l.823-.15a.576.576 0 0 0 .412-.83l-.88-1.68c-.19-.372-.587-.3-.64.117");
}

.ilmgd4m9e {
  stop-color: var(--svg-color--eabaaf, #EABAAF);
}

.ip6ihtb0n {
  d: path("M14.318 29.918h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067c-.046-.002-.064-.06-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.iul9049lf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m21.48 22.315l2.11 2.14");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j1-shybhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m20.198 23.03l2.093 1.727");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j5b5asq6d {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.144 8.499c.323-.144 1.17-.255 1.804.045");
}

.jaxnvvbws {
  d: path("M12.125 9.707c1.375-.262 2.41.604 2.69 1.37c-1.413.208-2.056.135-2.494.37z");
}

.jbyb7zbsw {
  d: path("m13.45 23.833l.07-.038c.504-.273.896-.5 1.455-.824l.495-.287l.04-.023l.69-.397l-.005-.006c1.997-1.01 4.472-.3 5.603 1.672c1.18 2.04.48 4.64-1.56 5.8l-.3.18h-5.585c.103-.705.152-1.978-.054-3.12c-.11-.613-.72-.996-1.341-.996h-1.193q.071-.168.156-.33a4.8 4.8 0 0 1 .8-1.066q.327-.316.73-.565");
}

.jcl0g0bfl {
  d: path("m10.32 10.923l.014-.002l-.061-.276l-.07-.319c-.158-.997.352-1.487.575-1.66l.05-.03l.05-.032a2.45 2.45 0 0 0 1.01-1.519l.05-.218a.28.28 0 0 1 .473-.141a4.11 4.11 0 0 0 3.657 1.146l3.371-.612c.189-.035 1.15-.115 1.443 1.178l.46 3.24c.403 2.958-1.53 5.344-4.327 5.852c-2.797.507-5.446-1.047-6.108-3.958z");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jswq_j2dq {
  stop-color: var(--svg-color--34e38b, #34E38B);
}

.jyzijgb5l {
  stop-color: var(--svg-color--248571, #248571);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.ka236wzgl {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc6luf8ah {
  stop-color: var(--svg-color--7556b0, #7556B0);
}

.khg6a5-nz {
  stop-color: var(--svg-color--248571, #248571);
}

.kpx6jhb5u {
  stop-color: var(--svg-color--161312, #161312);
}

.kqmp-xbxk {
  stop-color: var(--svg-color--ffd9b8, #FFD9B8);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l99uylilx {
  stop-color: var(--svg-color--309972, #309972);
}

.la4e9obft {
  stop-color: var(--svg-color--ac7ff8, #AC7FF8);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lk8w5cclk {
  stop-color: var(--svg-color--a176df, #A176DF);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lxai1jb9h {
  d: path("M8.73 25.646h2.453c.425-.689 1.037-1.514 1.36-1.84a7 7 0 0 0-.531-1.663c-1.126.973-2.657 2.741-3.282 3.503");
}

.lzdnytbwv {
  stop-color: var(--svg-color--a673ff, #A673FF);
}

.m-leh6bjs {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
}

.mdzncccgv {
  stop-color: var(--svg-color--c0806b, #C0806B);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mm2ngwx_x {
  d: path("M13.774 3.236c-1.233-.046-2.083 1.33-2.126 1.791c1.775 3.512 4.524 2.803 7.219 1.998c1.613-.482 1.928.236 2.134.573c-.748-4.117-4.389-4.255-7.196-4.36z");
}

.mn_1abcya {
  stop-color: var(--svg-color--e9bcaf, #E9BCAF);
}

.moyus9lkj {
  stop-color: var(--svg-color--d6a592, #D6A592);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqicc-u0l {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n2a634bwb {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
}

.n7fe64b-m {
  stop-color: var(--svg-color--6a428c, #6A428C);
}

.n7msnz5sl {
  d: path("M25.578 29.919c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.nybv-x_bu {
  stop-color: var(--svg-color--51e398, #51E398);
}

.o3yqmrbrg {
  stop-color: var(--svg-color--885ebc, #885EBC);
  stop-opacity: 0;
}

.o6qx60bff {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M21.145 11.485a1.143 1.143 0 1 0-.408-2.249a1.143 1.143 0 0 0 .408 2.25");
}

.ogwyqlrze {
  d: path("M11.287 13.854a1.712 1.712 0 1 0-.612-3.37a1.712 1.712 0 0 0 .612 3.37");
}

.op1ihkbup {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.046 8.302l-.1.267za.286.286 0 0 1-.2.534h-.001l-.005-.002a1 1 0 0 0-.13-.04a3 3 0 0 0-.384-.076a2.4 2.4 0 0 0-1.14.108a.285.285 0 1 1-.198-.536a3 3 0 0 1 1.412-.138a3.5 3.5 0 0 1 .63.144l.01.004l.004.001z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oyi32_b2v {
  stop-color: var(--svg-color--eebaaf, #EEBAAF);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkg2022aq {
  stop-color: var(--svg-color--ecb2b2, #ECB2B2);
  stop-opacity: 0;
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pyrigobmp {
  d: path("M13.57 16.983c-3.353 1.353-6.48 5.4-8.312 7.956c-.71.854-1.718 2.662-.086 4.98h9.18c.104-.704.154-1.983-.053-3.13c-.11-.612-.72-.996-1.341-.996H11.76c.102-.265.73-1.357 1.801-1.936c.505-.273.854-.563 1.413-.887l1.224-.707a6.03 6.03 0 0 1-.941-3.245v-1.452a5.2 5.2 0 0 1-1.689-.583");
}

.q1m6mtlky {
  stop-color: var(--svg-color--c48b99, #C48B99);
}

.qarzv5b-l {
  stop-color: var(--svg-color--37ba71, #37BA71);
}

.qbagijrnw {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.613 26.479c.274.906.367 2.164-.797 3.18");
}

.qcigj0wzj {
  stop-color: var(--svg-color--ffd8c3, #FFD8C3);
}

.ql2-nbc9p {
  stop-color: var(--svg-color--9a6b40, #9A6B40);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qrasocbfu {
  stop-color: var(--svg-color--a176df, #A176DF);
  stop-opacity: 0;
}

.qtbzeirls {
  stop-color: var(--svg-color--a980f3, #A980F3);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r4flqbcjd {
  d: path("M17.348 16.379c-.72 0-1.42.08-2.09.22v2.42c0 3.48 2.93 6.25 6.41 6.06l5.58-.31c-.7-4.74-4.86-8.39-9.9-8.39");
}

.rf88abbhx {
  stop-color: var(--svg-color--f1b493, #F1B493);
  stop-opacity: 0;
}

.rlw3b4b7i {
  stop-color: var(--svg-color--9565e9, #9565E9);
}

.rm6lemo-n {
  stop-color: var(--svg-color--3db155, #3DB155);
}

.rq62sfb9x {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.44 14.326a3.2 3.2 0 0 1-1.554-.09c-.16-.05-.288.148-.17.268a2.056 2.056 0 0 0 3.401-.618c.067-.159-.12-.294-.254-.19a3.2 3.2 0 0 1-1.423.63Z");
}

.rug17304c {
  stop-color: var(--svg-color--e9bfb9, #E9BFB9);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sh3vt1bfc {
  fill: var(--svg-color--e8b6a7, #E8B6A7);
  d: path("M14.318 29.918h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067c-.046-.002-.064-.06-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sjjdjlu1h {
  stop-color: var(--svg-color--ffc9b1, #FFC9B1);
  stop-opacity: 0;
}

.sq95r4vix {
  stop-color: var(--svg-color--a476f3, #A476F3);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t25c-kbzs {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.631 21.08c.344.636 1.032 2.281 1.032 3.781");
}

.tcaw_fkkx {
  stop-color: var(--svg-color--f5c2b6, #F5C2B6);
}

.tce23o4qc {
  stop-color: var(--svg-color--a980f3, #A980F3);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.th144cwik {
  stop-color: var(--svg-color--eec1af, #EEC1AF);
  stop-opacity: 0;
}

.thhcukb0j {
  d: path("m15.36 10.877l-.234 1.88a.574.574 0 0 0 .678.634l.823-.15a.576.576 0 0 0 .413-.831l-.88-1.679c-.19-.373-.747-.271-.8.146");
}

.ti5ns9bti {
  d: path("M23.677 11.389a3.45 3.45 0 0 0 .068-1.556a3.5 3.5 0 0 0-.53-1.315l.006-.001a3.4 3.4 0 0 0-.392-.484l-.002-.003a3.45 3.45 0 0 1-.888-1.754l-.002-.01a3.51 3.51 0 0 0-4.08-2.827a.57.57 0 0 1-.522-.158a3.52 3.52 0 0 0-3.07-.93A3.52 3.52 0 0 0 11.72 4.3a.6.6 0 0 1-.433.33l-.089.017A3.51 3.51 0 0 0 8.46 8.712l.002.01c.12.658.046 1.338-.214 1.955l-.002.004a3.51 3.51 0 0 0 .386 3.44a.55.55 0 0 1 .087.476a3.5 3.5 0 0 0-.072 1.534a3.42 3.42 0 0 0 3.98 2.758l8.986-1.631a3.42 3.42 0 0 0 2.757-3.981a3.5 3.5 0 0 0-.606-1.411a.55.55 0 0 1-.087-.477m-13.343-.468l-.013.003l1.702 2.238c.662 2.91 1.274-.231 4.071-.74c2.797-.507 4.61 2.537 4.206-.42l.582-3.563c-.293-1.293-1.254-1.213-1.443-1.179l-3.37.612a4.11 4.11 0 0 1-3.658-1.146a.28.28 0 0 0-.473.141l-.05.219a2.45 2.45 0 0 1-1.01 1.519l-.05.03l-.05.032c-.223.173-.733.663-.575 1.66l.07.319z");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tkcxzncwj {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.u75zz_obl {
  stop-color: var(--svg-color--dcada1, #DCADA1);
}

.uamj4xkkk {
  stop-color: var(--svg-color--d6a592, #D6A592);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ud_lf2bqt {
  d: path("M23.408 27.08a4.3 4.3 0 0 0 0-8.6c-2.375 0-3.553 1.925-3.553 4.3s1.178 4.3 3.553 4.3");
}

.uny69rbro {
  stop-color: var(--svg-color--38aa6f, #38AA6F);
}

.up7b_htug {
  stop-color: var(--svg-color--ab84ee, #AB84EE);
}

.uqpfdhbxh {
  stop-color: var(--svg-color--e4b89b, #E4B89B);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v8goawbnm {
  d: path("M21.247 12.046a1.712 1.712 0 1 0-.612-3.37a1.712 1.712 0 0 0 .611 3.37");
}

.vbtyscd-k {
  stop-color: var(--svg-color--c48b99, #C48B99);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vrjrrpcnz {
  stop-color: var(--svg-color--349373, #349373);
}

.vrywjrb0z {
  stop-color: var(--svg-color--f1caba, #F1CABA);
}

.vx8r8sbmx {
  stop-color: var(--svg-color--f2c3a9, #F2C3A9);
}

.vy8gdf6bj {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.418 10.973l-.233 1.881a.574.574 0 0 0 .678.633l.823-.15a.576.576 0 0 0 .412-.83l-.88-1.68c-.19-.372-.747-.27-.8.146");
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w-wd4mb8i {
  stop-color: var(--svg-color--53ffa2, #53FFA2);
}

.w7g29ccgc {
  stop-color: var(--svg-color--e3af9a, #E3AF9A);
  stop-opacity: 0;
}

.w9ixeebma {
  d: path("M9.442 5.973c.478-.735 1.599-.94 2.133-.94l.66 1.276c-.272.007-.491.143-.654.373c-.23 1.404-1.712 2.425-2.423 2.76c-.44-1.534-.339-2.513.284-3.47");
}

.wcgqkbbxt {
  d: path("M11.205 13.29a1.143 1.143 0 1 0-.408-2.249a1.143 1.143 0 0 0 .408 2.249");
}

.wpapq1b-u {
  stop-color: var(--svg-color--161716, #161716);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x79fyur6x {
  stop-color: var(--svg-color--ecb2b2, #ECB2B2);
}

.x9l2kpb_x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.824 24.321l1.906 1.211");
}

.xaulv1bog {
  stop-color: var(--svg-color--eec1af, #EEC1AF);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xgm21db5v {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.498 9.146c-.353-.02-1.185.173-1.674.676");
}

.xjvfic_gd {
  stop-color: var(--svg-color--309972, #309972);
  stop-opacity: 0;
}

.xpf_69b1t {
  stop-color: var(--svg-color--ffc9b1, #FFC9B1);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y3st6e2hh {
  d: path("M20.935 22.023a.64.64 0 0 1 .913.018c.447.475 1.16 1.226 1.82 1.887a.05.05 0 0 0 .085-.04l-.089-.926a.67.67 0 0 1 1.32-.21l.692 3.103q.088.294.089.615c0 1.065-.766 1.95-1.777 2.136c-.697.2-1.485-.121-1.794-.308l-2.78-1.689a.632.632 0 0 1 .626-1.098l-.596-.428a.62.62 0 1 1 .737-1l.186.141l-.656-.52a.648.648 0 1 1 .837-.988l1.156 1.045l-.79-.853a.636.636 0 0 1 .02-.886");
}

.y9owwpbix {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
  stop-opacity: 0;
}

.yasfqbb-e {
  stop-color: var(--svg-color--a673ff, #A673FF);
  stop-opacity: 0;
}

.yit44gm3t {
  stop-color: var(--svg-color--9165d2, #9165D2);
  stop-opacity: 0;
}

.yn-qmdb0b {
  d: path("M19.106 10.181c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51s-.63-.03-.86-.23a.3.3 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.39");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

</style>
