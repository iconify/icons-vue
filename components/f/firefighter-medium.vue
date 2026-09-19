<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1YMzrd)"><path fill="url(#inJe27K)" class="op4oknb0c"/><path fill="url(#iYYvkzd)" class="op4oknb0c"/></g><path class="vfvu-le0l"/><path fill="url(#iKtSVPc)" class="zghvajbfn"/><path fill="url(#iZlNfJc)" class="zghvajbfn"/><path fill="url(#iPAI1pb)" class="zghvajbfn"/><path fill="url(#i60FNGr)" class="zghvajbfn"/><path fill="url(#iBfklUS)" class="zghvajbfn"/><path fill="url(#id9v4Ec)" class="zghvajbfn"/><path fill="url(#iY2SHOe)" class="k9tgvabpk"/><path fill="url(#ivE93ZN)" class="k9tgvabpk"/><path fill="url(#i3fdVsc)" class="k9tgvabpk"/><path fill="url(#iGtkYWd)" class="h5w-dr7bj"/><path fill="url(#i90IRAe)" class="h5w-dr7bj"/><path fill="url(#iwaqO1c)" class="x7a2cjbak"/><path fill="url(#ia1fsJd)" class="x_y99ccua"/><path fill="url(#ioADucd)" class="ninkwub7p"/><g filter="url(#iA0XaFb)"><path fill="url(#iAo3gLA)" class="l2min6bvj"/><path fill="url(#i9dVGQb)" class="l2min6bvj"/></g><path fill="url(#iBi3Rme)" class="l2min6bvj"/><path fill="url(#iihM1ge)" class="l2min6bvj"/><path fill="url(#ixJcYIX)" class="l2min6bvj"/><path fill="url(#igvGIih)" class="l2min6bvj"/><path fill="url(#iJquCGb)" class="l2min6bvj"/><path fill="url(#i825pyd)" class="l2min6bvj"/><path fill="url(#iC45SMb)" class="l2min6bvj"/><path fill="url(#iO1w2qe)" class="l2min6bvj"/><path fill="url(#isE6vne)" class="l2min6bvj"/><g filter="url(#iMpRjsy)"><path class="gzez8-r_z"/></g><g filter="url(#ieiHP1b)"><path class="lyes1-b2r"/><path fill="url(#ivE8kbb)" class="zuwiytbpl"/><path fill="url(#iEfAdCb)" class="zuwiytbpl"/><path fill="url(#iEVnzfd)" class="zuwiytbpl"/><path fill="url(#iGt2vte)" class="zuwiytbpl"/><path fill="url(#i0wPLwe)" class="zuwiytbpl"/><path fill="url(#iVcTs2b)" class="zuwiytbpl"/></g><g filter="url(#ijuLB4c)"><path stroke="url(#i5KL0be)" class="ne6ofv0yo"/></g><path fill="url(#iKjUdkd)" class="njcnwtbjp"/><g filter="url(#ieWCulb)"><path class="vr66bfydu"/></g><g filter="url(#iQKTrhd)"><path class="v6ipadbav"/></g><path class="inzus9lrp"/><path fill="url(#ioO9VCb)" class="hpb8-pbyx"/><path class="r5ppebcga"/><path fill="url(#iMeCvCE)" class="cagc7ntof"/><path class="z-p3un40t"/><g filter="url(#iLYvYBd)"><path class="j4gxujbel"/><path fill="url(#ijA6Eab)" class="j59mrrqhy"/></g><g filter="url(#iGZ9tpf)"><path fill="url(#isS8Lvc)" class="gr7v7ac4m"/></g><path class="ha6zkwoci"/><path fill="url(#ieQqZQI)" class="j6hfaoyix"/><path class="eelddfbvt"/><g filter="url(#iYy7qkd)"><path fill="url(#iPREcgd)" class="m73lm3z0d"/></g><g filter="url(#iIbVocb)"><ellipse transform="rotate(-27.914 12.094 9.768)" class="v_qjdacjf"/><ellipse fill="url(#idZvtSc)" transform="rotate(-27.914 12.094 9.768)" class="e8z2bfy5o"/></g><path fill="url(#iGMdKQd)" class="nzhk5hb2k"/><path fill="url(#i97mL0b)" class="nzhk5hb2k"/><path fill="url(#iHFkupe)" class="nzhk5hb2k"/><path fill="url(#iARQ5ub)" class="nzhk5hb2k"/><path fill="url(#iGRZ3Pd)" class="nzhk5hb2k"/><path fill="url(#iD4Lx2c)" class="vex-1jhir"/><path fill="url(#iZeUaGe)" class="vex-1jhir"/><path fill="url(#idJssge)" class="vex-1jhir"/><g filter="url(#ilETbCd)"><path fill="url(#iT4PWrb)" class="uvo-73bqb"/></g><g filter="url(#i7T6Zsb)"><path fill="url(#ieT91OX)" class="d-18wfb1e"/></g><path fill="url(#iSepCpe)" class="bnj4awb7x"/><path fill="url(#iRHxkne)" class="bnj4awb7x"/><path fill="url(#iIrphQc)" class="bnj4awb7x"/><path fill="url(#itGm0Tc)" class="bnj4awb7x"/><path fill="url(#ijcV2Td)" class="bnj4awb7x"/><g filter="url(#inwCqLe)"><path clip-rule="evenodd" class="t02u5pbdh"/><path fill="url(#i09LEGc)" clip-rule="evenodd" class="dboz2gdul"/><path fill="url(#iZIfEBc)" clip-rule="evenodd" class="dboz2gdul"/></g><g filter="url(#iAjhYib)"><path fill="url(#iyadHgd)" class="efdg3b1ld"/></g><path fill="url(#iX1GUQc)" class="efdg3b1ld"/><path fill="url(#ioHes2c)" class="efdg3b1ld"/><path class="epmte165c"/><path fill="url(#iVvmsXd)" class="sj-oksqer"/><path fill="url(#iBit0Tc)" class="sj-oksqer"/><path fill="url(#in0mW6b)" class="sj-oksqer"/><path fill="url(#iQ6b6oZ)" class="sj-oksqer"/><path fill="url(#i5buLed)" class="e8fyeibbk"/><path fill="url(#iS0y7sb)" class="e8fyeibbk"/><path fill="url(#iOYwQgd)" class="e8fyeibbk"/><path fill="url(#iyNhGvt)" class="e8fyeibbk"/><path fill="url(#i1uMwWc)" class="e8fyeibbk"/><path fill="url(#iioOKUb)" class="xafkzg5qh"/><path fill="url(#iMFO0xd)" class="xafkzg5qh"/><path fill="url(#ivE558b)" class="xafkzg5qh"/><g filter="url(#iUnSVub)"><path fill="url(#iRgarjc)" class="hqpihdano"/><path fill="url(#iRUKT1c)" class="hqpihdano"/></g><g filter="url(#i6dUWyc)"><path fill="url(#inCW8Yd)" class="hk__utvhv"/><path fill="url(#iEPFVje)" class="hk__utvhv"/></g><path fill="url(#i5bGLze)" class="hk__utvhv"/><path fill="url(#iLTi7qd)" class="hk__utvhv"/><g filter="url(#iTCxRid)"><path fill="url(#ia0Vpsd)" class="jlg55n4fa"/><path fill="url(#igZtNoe)" class="jlg55n4fa"/><path fill="url(#i6AK64f)" class="jlg55n4fa"/></g><g filter="url(#idRvGTQ)"><path fill="url(#i0F2JCb)" class="i5wcispyy"/><path fill="url(#iZDKXWb)" class="i5wcispyy"/><path fill="url(#iJzqmFc)" class="i5wcispyy"/></g><g filter="url(#iAJneHc)"><path fill="url(#iq66wKe)" class="bwfp-7bqq"/></g><g filter="url(#iJIQWvb)"><path stroke="url(#ii0P1oe)" class="p5b-6qbnd"/></g><g filter="url(#iEmOkfc)"><path class="j-aqwlflj"/></g><defs><radialGradient id="iKtSVPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.542 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="iZlNfJc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.262 26.253)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iPAI1pb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.606 26.128)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="i60FNGr" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.512 23.94)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iBfklUS" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.262 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="id9v4Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 18.98 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iY2SHOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.824 29.753)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="i3fdVsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.567 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="iGtkYWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.074 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="i90IRAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.537 22.972)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="ia1fsJd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.227 19.73)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="ioADucd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 8.49 12.211)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iAo3gLA" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 17.355 10.78)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i9dVGQb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.851 7.687)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iihM1ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.8347 -11.206 0 15.106 4.609)" gradientUnits="userSpaceOnUse"><stop offset=".779" class="x1sq6wblk"/><stop offset="1" class="qif6ck0um"/></radialGradient><radialGradient id="ixJcYIX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 16.994 9.467)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="igvGIih" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 10.897 -1.389)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iJquCGb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.804 6.167)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i825pyd" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 7.755 8.047)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iC45SMb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.467 13.077)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iO1w2qe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 12.331 10.284)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="isE6vne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.77076 13.6288 0 14.594 15.743)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="c331hvvlc"/><stop offset=".91" class="pkfxeebzf"/></radialGradient><radialGradient id="iEfAdCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.72705 0 14.989 12.14)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iGt2vte" cx="0" cy="0" r="1" gradientTransform="rotate(154.931 6.263 7.464)scale(1.77031 2.94716)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iKjUdkd" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 14.056 14.403)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ioO9VCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .96814 0 9.402 8.976)" gradientUnits="userSpaceOnUse"><stop class="rl84unbtp"/><stop offset="1" class="s7ag-e23r"/></radialGradient><radialGradient id="iMeCvCE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.729 9.864)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ijA6Eab" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.686 .933)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieQqZQI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.365 9.864)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="idZvtSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.078 10.082)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i97mL0b" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 19.165 9.877)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iHFkupe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 19.525 10.422)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iARQ5ub" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 19.639 10.595)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iGRZ3Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 3 -4.22407 -.088 19.778 8.727)" gradientUnits="userSpaceOnUse"><stop class="gy5cnrbed"/><stop offset="1" class="zskft4b9n"/></radialGradient><radialGradient id="iZeUaGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 9.631 10.519)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="idJssge" cx="0" cy="0" r="1" gradientTransform="rotate(77.826 -.748 10.192)scale(1.2308 2.98368)" gradientUnits="userSpaceOnUse"><stop class="q27cizbur"/><stop offset="1" class="vt_76z49v"/></radialGradient><radialGradient id="iT4PWrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 9.632 10.52)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iSepCpe" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.02 7.08)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="iIrphQc" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.249 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="itGm0Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.606 3.097)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ijcV2Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.793 7.19)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="i09LEGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.117 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iZIfEBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.15 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iyadHgd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15119 3 -3.33004 -3.49787 18.007 16.19)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="ioHes2c" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.953 16.064)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iVvmsXd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.537 27.815)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iQ6b6oZ" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.787 20.731)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="iS0y7sb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.663 7.173)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iOYwQgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.59 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="iyNhGvt" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.637 9.128)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i1uMwWc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 21.98 9.034)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iMFO0xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.921 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ivE558b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.542 25.83)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iRgarjc" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.443 3.481)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iRUKT1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.887 7.284)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iEPFVje" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .507 19.618)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="i5bGLze" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.067 16.393)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iLTi7qd" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17969 -.05864 .27278 21.746 16.33)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="igZtNoe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.813 16.945)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="i6AK64f" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.793 19.378)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="i0F2JCb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.008 15.768)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iZDKXWb" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.606 22.503)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJzqmFc" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.043 12.546)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><linearGradient id="inJe27K" x1="14.547" x2="14.547" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iYYvkzd" x1="14.547" x2="14.547" y1="7.248" y2="10.842" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ivE93ZN" x1="7.567" x2="6.449" y1="26.659" y2="26.628" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iwaqO1c" x1="15.614" x2="15.614" y1="15.025" y2="21.361" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iBi3Rme" x1="19.704" x2="17.175" y1="12.465" y2="12.465" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ivE8kbb" x1="15.341" x2="14.547" y1="11.455" y2="11.486" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iEVnzfd" x1="14.547" x2="14.547" y1="12.594" y2="12.129" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i0wPLwe" x1="14.547" x2="14.547" y1="9.889" y2="10.435" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iVcTs2b" x1="13.463" x2="14.547" y1="12.042" y2="12.095" gradientUnits="userSpaceOnUse"><stop offset=".233" class="xutladcis"/><stop offset="1" class="hcruwac-m"/></linearGradient><linearGradient id="i5KL0be" x1="13.345" x2="13.664" y1="14.165" y2="13.33" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="isS8Lvc" x1="17.507" x2="17.193" y1="9.917" y2="10.111" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPREcgd" x1="13.109" x2="12.795" y1="9.917" y2="10.111" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGMdKQd" x1="20.983" x2="19.776" y1="9.944" y2="12.121" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iD4Lx2c" x1="8.697" x2="10.155" y1="10.649" y2="10.521" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ieT91OX" x1="20" x2="20" y1="9.635" y2="11.393" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iRHxkne" x1="10.606" x2="16.949" y1="6.722" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iX1GUQc" x1="13.237" x2="13.449" y1="18.096" y2="18.096" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iBit0Tc" x1="14.552" x2="14.552" y1="30.315" y2="28.721" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="in0mW6b" x1="14.552" x2="14.552" y1="26.171" y2="27.44" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i5buLed" x1="14.542" x2="14.542" y1="6.972" y2="11.753" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iioOKUb" x1="14.542" x2="14.542" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="inCW8Yd" x1="21.981" x2="18.293" y1="16.753" y2="29.971" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="ia0Vpsd" x1="19.981" x2="28.168" y1="22.19" y2="18.878" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="iq66wKe" x1="14.418" x2="14.418" y1="4.22" y2="6.665" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="ii0P1oe" x1="18.649" x2="20.152" y1="21.646" y2="16.456" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="i1YMzrd" width="17.197" height="11.9" x="5.948" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/></filter><filter id="iA0XaFb" width="11.22" height="12.442" x="9.484" y="4.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2610" result="effect2_innerShadow_4002_2610"/></filter><filter id="iMpRjsy" width="3.735" height="4.88" x="12.334" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".5"/></filter><filter id="ieiHP1b" width="2.179" height="3.3" x="13.457" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".1"/></filter><filter id="ijuLB4c" width="3.718" height="1.573" x="12.688" y="13.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".05"/></filter><filter id="ieWCulb" width="2.339" height="1.19" x="16.136" y="7.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/></filter><filter id="iQKTrhd" width="2.339" height="1.176" x="10.88" y="7.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/></filter><filter id="iLYvYBd" width=".787" height=".696" x="15.995" y="9.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".05"/></filter><filter id="iGZ9tpf" width=".891" height=".913" x="16.835" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".1"/></filter><filter id="iYy7qkd" width=".986" height="1.04" x="12.392" y="9.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".1"/></filter><filter id="iIbVocb" width=".913" height=".705" x="11.637" y="9.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".05"/></filter><filter id="ilETbCd" width="1.329" height="2.379" x="8.466" y="9.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".125"/></filter><filter id="i7T6Zsb" width="1.806" height="2.758" x="19.097" y="9.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".25"/></filter><filter id="inwCqLe" width="6.88" height="3.666" x="11.117" y="15.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/></filter><filter id="iAjhYib" width="4.97" height="3.828" x="13.237" y="15.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/></filter><filter id="iUnSVub" width="5.52" height="4.05" x="11.787" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2610" result="effect2_innerShadow_4002_2610"/></filter><filter id="i6dUWyc" width="6.94" height="14.221" x="16.537" y="15.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2610" result="effect2_innerShadow_4002_2610"/></filter><filter id="iTCxRid" width="11.012" height="8.855" x="17.82" y="16.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2610" result="effect2_innerShadow_4002_2610"/></filter><filter id="idRvGTQ" width="4.557" height="7.476" x="23.776" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2610"/></filter><filter id="iAJneHc" width="2.509" height="3.213" x="13.114" y="3.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2610"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2610" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2610" result="effect3_innerShadow_4002_2610"/></filter><filter id="iJIQWvb" width="1.83" height="4.718" x="18.051" y="17.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".125"/></filter><filter id="iEmOkfc" width="2.769" height="7.081" x="18.356" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2610" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:firefighter-medium" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bnj4awb7x {
  d: path("M20.845 7.332H8.25v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.bwfp-7bqq {
  d: path("M13.264 4.909c0-.153.183-.231.293-.125l.154.148a.162.162 0 0 0 .275-.117v-.17c0-.344.178-.665.471-.846l.18-.112a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .28.133l.095-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c331hvvlc {
  stop-color: var(--svg-color--864e59, #864E59);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cagc7ntof {
  d: path("M16.731 9.387a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.d-18wfb1e {
  d: path("M19.597 11.393q.05-.879.094-1.758c.402.055.712.426.712.876c0 .484-.36.878-.806.882");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.dboz2gdul {
  fill-rule: evenodd;
  d: path("M11.117 16.065v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8fyeibbk {
  d: path("M8.618 7.972h11.847c.95 0 1.99.484 1.99 2.68h.69V9.347c0-1.43-.847-2.375-2.456-2.375H8.395c-1.609 0-2.457.945-2.457 2.375v1.305h.692c0-2.196 1.04-2.68 1.988-2.68");
}

.e8z2bfy5o {
  cx: 12.094px;
  cy: 9.768px;
  rx: 0.39px;
  ry: 0.197px;
}

.eelddfbvt {
  fill: var(--svg-color--000, #000);
  d: path("M12.874 10.28a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.efdg3b1ld {
  d: path("M13.237 16.933v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.888h-1.896q-.19 0-.376-.018");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.epmte165c {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.537 26.171H7.567v3.8h13.97z");
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gr7v7ac4m {
  d: path("M17.526 10.161a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gy5cnrbed {
  stop-color: var(--svg-color--74483c, #74483C);
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.gzez8-r_z {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m13.943 10.247l-.587 1.825c-.1.376.14.751.482.751h.726c.34 0 .581-.381.481-.75l-.49-1.826c-.106-.405-.502-.405-.612 0");
}

.h5w-dr7bj {
  d: path("M21.537 17.981v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.ha6zkwoci {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.156 9.115c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34H13.3a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hcruwac-m {
  stop-color: var(--svg-color--916557, #916557);
  stop-opacity: 0;
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hk__utvhv {
  d: path("m22.596 16.136l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.624");
}

.hpb8-pbyx {
  d: path("M8.439 7.546q.037.086.093.168c.172.258.266.564.266.875v1.2c.198-.141.459-.226.708-.264l-.03-1.537q0-.225.028-.442z");
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.hqpihdano {
  d: path("M17.207 6.971h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.i5wcispyy {
  d: path("M25.609 18.01a3.5 3.5 0 0 0 .85-.172l.148-.055c.178-.062.4-.053.554.108c1.072 1.125 1.43 2.621.984 4.236c-.448 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.142-.14a3.5 3.5 0 0 0-.641-.589c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.734z");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.inzus9lrp {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.938 9.115c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j-aqwlflj {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.881 29.628c0-.2 1.146-4.104 1.719-6.031");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j4gxujbel {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.665 9.575c.064.085-.069.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.007-.246.159-.359c.15-.113.325-.136.388-.05");
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j59mrrqhy {
  d: path("M16.665 9.575c.064.085-.069.19-.22.302c-.151.113-.263.193-.327.108c-.063-.085.007-.246.159-.359c.15-.113.325-.136.388-.05");
}

.j6hfaoyix {
  d: path("M12.363 9.387a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jlg55n4fa {
  d: path("m19.972 16.73l4.416 1.161a3.56 3.56 0 0 0 2.071-.053l.148-.054c.178-.063.4-.054.554.107c1.072 1.125 1.43 2.621.984 4.236c-.448 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.141-.14a3.5 3.5 0 0 0-1.745-1.111l-4.243-1.203a.61.61 0 0 1-.431-.779l1.252-4.674c.044-.22.37-.43.621-.365");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k9tgvabpk {
  d: path("M7.567 29.972V17.97a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kmg6h4b5x {
  stop-color: var(--svg-color--bd585d, #BD585D);
  stop-opacity: 0;
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l2min6bvj {
  d: path("M9.722 13.545a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.lyes1-b2r {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m14.185 10.065l-.504 1.838c-.103.379.144.757.493.757h.745c.35 0 .597-.384.494-.757l-.504-1.838c-.108-.407-.611-.407-.725 0");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m73lm3z0d {
  d: path("M13.178 10.174c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.ne6ofv0yo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.196 13.281a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.ninkwub7p {
  d: path("M9.686 12.03a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.njcnwtbjp {
  d: path("M14.547 13.676c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.334.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nzhk5hb2k {
  d: path("M19.469 12.12c.066-1.063.12-2.126.176-3.19c.756.132 1.338.79 1.338 1.584a1.61 1.61 0 0 1-1.514 1.607");
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.op4oknb0c {
  d: path("M22.134 7.972H7.112c-.395.32-.78 1.336-1.164 1.656v1.344c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.628c-.354-.42-.687-1.206-1.011-1.656");
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.p5b-6qbnd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.506 17.971l-1.08 3.968");
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pkfxeebzf {
  stop-color: var(--svg-color--864e59, #864E59);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q27cizbur {
  stop-color: var(--svg-color--5b302c, #5B302C);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qif6ck0um {
  stop-color: var(--svg-color--934a5a, #934A5A);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r5ppebcga {
  fill: var(--svg-color--221315, #221315);
  d: path("M19.645 7.537q.046.172.05.356L19.616 9.5c.233.041.48.138.667.268V8.58c0-.311.096-.617.27-.874a1 1 0 0 0 .093-.169z");
}

.rl84unbtp {
  stop-color: var(--svg-color--241a1a, #241A1A);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rz-l4sb2t {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
}

.rzbfz4btw {
  stop-color: var(--svg-color--b3576b, #B3576B);
  stop-opacity: 0;
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s7ag-e23r {
  stop-color: var(--svg-color--27050c, #27050C);
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sj-oksqer {
  d: path("M21.537 26.171H7.567v3.8h13.97z");
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.t02u5pbdh {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.117 16.065v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.tbz0q_48a {
  stop-color: var(--svg-color--dd365e, #DD365E);
  stop-opacity: 0;
}

.tc4y5tbfa {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
}

.tcape2laf {
  stop-color: var(--svg-color--edb63d, #EDB63D);
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.uvo-73bqb {
  d: path("M9.461 9.582a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v_qjdacjf {
  cx: 12.094px;
  cy: 9.768px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v6ipadbav {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M11.136 7.91a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.552a2.22 2.22 0 0 0-1.386.284a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.vex-1jhir {
  d: path("M9.503 8.917a1.62 1.62 0 0 0-1.392 1.598c0 .859.673 1.56 1.52 1.606a78 78 0 0 1-.128-3.205");
}

.vfvu-le0l {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.547 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vr66bfydu {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M18.28 8.02a1.85 1.85 0 0 0-.688-.412c-.304-.096-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.028.979.036c.198.063.332.164.49.3a.277.277 0 1 0 .364-.417");
}

.vt_76z49v {
  stop-color: var(--svg-color--5b302c, #5B302C);
  stop-opacity: 0;
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x_y99ccua {
  d: path("M19.408 12.03c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.02q.256-.547.346-1.18z");
}

.x1sq6wblk {
  stop-color: var(--svg-color--a06772, #A06772);
  stop-opacity: 0;
}

.x7a2cjbak {
  d: path("M13.237 15.972v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xafkzg5qh {
  d: path("M15.127 19.605h-1.17v6.57h1.17z");
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xutladcis {
  stop-color: var(--svg-color--916557, #916557);
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.z-p3un40t {
  fill: var(--svg-color--000, #000);
  d: path("M16.22 10.28c0-.285.227-.512.511-.512a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zghvajbfn {
  d: path("M14.547 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.zskft4b9n {
  stop-color: var(--svg-color--74483c, #74483C);
  stop-opacity: 0;
}

.zuwiytbpl {
  d: path("m14.185 10.065l-.504 1.838c-.103.379.144.757.493.757h.745c.35 0 .597-.384.494-.757l-.504-1.838c-.108-.407-.611-.407-.725 0");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
