<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ikMY1Tc)"><path fill="url(#iYCpHTd)" class="nm3_j9wvt"/><path fill="url(#iCyHxTd)" class="nm3_j9wvt"/></g><path class="xb44u-blz"/><path fill="url(#izAQigd)" class="ovvejmbph"/><path fill="url(#ier2Dub)" class="ovvejmbph"/><path fill="url(#iWcCFWT)" class="ovvejmbph"/><path fill="url(#iuJXEQd)" class="ovvejmbph"/><path fill="url(#i5aczCc)" class="ovvejmbph"/><path fill="url(#iqjlpOb)" class="ovvejmbph"/><path fill="url(#iWVZUYb)" class="srf37nb-e"/><path fill="url(#inu3QVd)" class="srf37nb-e"/><path fill="url(#irsdH4c)" class="srf37nb-e"/><path fill="url(#i7GV5Ed)" class="vdne8-75y"/><path fill="url(#iOIvIXc)" class="vdne8-75y"/><path fill="url(#iGVok1g)" class="n3-1ri2jm"/><path fill="url(#i3cpPXb)" class="lca308gqi"/><path fill="url(#iY3dete)" class="svtl-z3-k"/><g filter="url(#iYn2GGd)"><path fill="url(#i7NBKPe)" class="byahc9cfq"/><path fill="url(#it9WTxL)" class="byahc9cfq"/></g><path fill="url(#i3jeOEz)" class="byahc9cfq"/><path fill="url(#iETSqme)" class="byahc9cfq"/><path fill="url(#iYhUQEe)" class="byahc9cfq"/><path fill="url(#ikeJtIc)" class="byahc9cfq"/><path fill="url(#iRjoXcc)" class="byahc9cfq"/><path fill="url(#i8B4L3d)" class="byahc9cfq"/><path fill="url(#i118Tod)" class="byahc9cfq"/><path fill="url(#iiT5ivc)" class="byahc9cfq"/><g filter="url(#i0r3afb)"><path class="iu50muwro"/></g><g filter="url(#iRzfoRc)"><path class="ix9hjsb2b"/><path fill="url(#i5vKplc)" class="fm8u67bql"/><path fill="url(#ipEWbzb)" class="fm8u67bql"/><path fill="url(#iIyAO1d)" class="fm8u67bql"/><path fill="url(#iUOgOKe)" class="fm8u67bql"/><path fill="url(#iBYd7Zb)" class="fm8u67bql"/></g><g filter="url(#i9aS9Kb)"><path stroke="url(#iyosSXd)" class="mxki9ud2p"/></g><path fill="url(#ifirate)" class="fx8gmyb8r"/><path fill="url(#imlxOoe)" class="lsnc20b-o"/><path class="xq7s1574r"/><g filter="url(#iI1bVxz)"><path class="mzl8dcg-h"/></g><g filter="url(#iseC5Wc)"><path class="aggwxjksf"/></g><path class="bn4kkbczz"/><path fill="url(#iS0hB5c)" class="rftw2rbuv"/><path class="ezt8k_b3n"/><g filter="url(#imeXgLt)"><path class="gpnw08y-s"/><path fill="url(#iK4lfNe)" class="ui2z9jbuj"/></g><g filter="url(#iC0toMd)"><path fill="url(#iaWAqBd)" class="es6fcfbby"/></g><path class="h5x965v8n"/><path fill="url(#ioIqa9d)" class="z6byr7vui"/><path class="sn1anc6hu"/><g filter="url(#iIlz7Qb)"><path fill="url(#i8bDFFb)" class="tztu7rbfe"/></g><g filter="url(#i2okVYc)"><ellipse transform="rotate(-27.914 12.089 9.712)" class="tlgdncc4h"/><ellipse fill="url(#idYFyzc)" transform="rotate(-27.914 12.089 9.712)" class="cdjhb1jfy"/></g><path fill="url(#iYCSvse)" class="oji17rbqg"/><path fill="url(#igA4FFb)" class="oji17rbqg"/><path fill="url(#iQiDOHd)" class="oji17rbqg"/><path fill="url(#iIDcHRb)" class="oji17rbqg"/><path fill="url(#i9zU4Bd)" class="o26w0nbbn"/><path fill="url(#i1eJzad)" class="o26w0nbbn"/><g filter="url(#i4w2INc)"><path fill="url(#i5BeZnb)" class="ah26hbetv"/></g><g filter="url(#iVLM76b)"><path fill="url(#iCUJZ2d)" class="c07875jis"/></g><path fill="url(#iOFXqzn)" class="x4wbw5p_v"/><path fill="url(#igefvab)" class="x4wbw5p_v"/><path fill="url(#is8uV0d)" class="x4wbw5p_v"/><path fill="url(#i3xY9sb)" class="x4wbw5p_v"/><path fill="url(#iB3KyNe)" class="x4wbw5p_v"/><g filter="url(#iYsw6Mb)"><path clip-rule="evenodd" class="y-_y6_bwk"/><path fill="url(#ikNBAqp)" clip-rule="evenodd" class="byer7fp6t"/><path fill="url(#iD3TShe)" clip-rule="evenodd" class="byer7fp6t"/></g><g filter="url(#iXYtADc)"><path fill="url(#iVjUSQd)" class="yduze7bxv"/></g><path fill="url(#i51x3qc)" class="yduze7bxv"/><path fill="url(#igSQ2tc)" class="yduze7bxv"/><path class="ywt6vob0u"/><path fill="url(#i07Wiee)" class="nbwi6nb0x"/><path fill="url(#iKSxXmc)" class="nbwi6nb0x"/><path fill="url(#ixb0ayc)" class="nbwi6nb0x"/><path fill="url(#iHE3opb)" class="nbwi6nb0x"/><path fill="url(#ieHEBub)" class="unx234bdc"/><path fill="url(#iehuA3b)" class="unx234bdc"/><path fill="url(#iY3ki8b)" class="unx234bdc"/><path fill="url(#i7uF0Qb)" class="unx234bdc"/><path fill="url(#iCoxO5b)" class="unx234bdc"/><path fill="url(#iVx7sqe)" class="xyzz31b7b"/><path fill="url(#iWroHgc)" class="xyzz31b7b"/><path fill="url(#ionKy5b)" class="xyzz31b7b"/><g filter="url(#iIt3cHc)"><path fill="url(#ir2Mdsi)" class="tdust5bqt"/><path fill="url(#iAfITpd)" class="tdust5bqt"/></g><g filter="url(#iVrt2ht)"><path fill="url(#ijde7ue)" class="a0dieccro"/><path fill="url(#ikOTUTc)" class="a0dieccro"/></g><path fill="url(#iERrMhc)" class="a0dieccro"/><path fill="url(#iyPOrgb)" class="a0dieccro"/><g filter="url(#iXUAvTb)"><path fill="url(#i2DZTHc)" class="jyem0l38y"/><path fill="url(#igrPQfY)" class="jyem0l38y"/><path fill="url(#izWgADd)" class="jyem0l38y"/></g><g filter="url(#i7gFmWl)"><path fill="url(#inKN1Md)" class="lrw1tsb1o"/><path fill="url(#ivR4DRo)" class="lrw1tsb1o"/><path fill="url(#i1X9QIb)" class="lrw1tsb1o"/></g><g filter="url(#iWZ3GQq)"><path fill="url(#iY8WQPd)" class="z1g2odbcn"/></g><g filter="url(#iImgLnd)"><path stroke="url(#iLLyQSd)" class="o3i__byxt"/></g><g filter="url(#iNDTsJd)"><path class="zn7hribqr"/></g><defs><radialGradient id="izAQigd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.542 15.885)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="ier2Dub" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.262 26.197)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iWcCFWT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.606 26.072)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iuJXEQd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.512 23.884)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="i5aczCc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.262 22.666)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="iqjlpOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 18.98 16.203)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iWVZUYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.824 29.697)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="irsdH4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.567 29.916)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="i7GV5Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.074 23.92)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iOIvIXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.537 22.916)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="i3cpPXb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.265 19.699)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iY3dete" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 8.485 12.155)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="i7NBKPe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 17.35 10.724)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="it9WTxL" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.865 7.657)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iETSqme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.84375 12.3628 0 14.524 17.5)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".444" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iYhUQEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 16.989 9.41)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="ikeJtIc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 10.867 -1.414)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iRjoXcc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 17.975 11.712)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="i8B4L3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 7.75 7.99)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="i118Tod" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.49 13.047)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iiT5ivc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.125 11.908 0 14.589 16.156)" gradientUnits="userSpaceOnUse"><stop offset=".695" class="wxaqq2b7n"/><stop offset="1" class="lf9xrjbpf"/></radialGradient><radialGradient id="ipEWbzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.008 12.084)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iUOgOKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 15.124 11.515)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ifirate" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 14.05 14.347)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="imlxOoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .98438 0 9.419 8.92)" gradientUnits="userSpaceOnUse"><stop class="rl84unbtp"/><stop offset="1" class="s7ag-e23r"/></radialGradient><radialGradient id="iS0hB5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 16.724 9.808)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iK4lfNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.496 9.892)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioIqa9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.36 9.808)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="idYFyzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 12.074 10.026)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igA4FFb" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 19.16 9.822)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iQiDOHd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 19.52 10.366)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iIDcHRb" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 19.634 10.539)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i1eJzad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 9.626 10.463)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="i5BeZnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 9.628 10.466)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iOFXqzn" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.037 7.053)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="is8uV0d" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.249 7.01)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="i3xY9sb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.606 3.04)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="iB3KyNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.793 7.134)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="ikNBAqp" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.117 16.009)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iD3TShe" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94025 -.49362 1.26336 12.15 16.01)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iVjUSQd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.777 11.668)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="igSQ2tc" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.953 16.008)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="i07Wiee" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.537 27.76)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iHE3opb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.766 20.703)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="iehuA3b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.663 7.117)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iY3ki8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.59 8.087)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="i7uF0Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.637 9.072)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="iCoxO5b" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 21.98 8.978)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iWroHgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.921 21.698)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ionKy5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.542 25.77)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="ir2Mdsi" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.446 3.453)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iAfITpd" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.887 7.228)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="ikOTUTc" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .53 19.59)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iERrMhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.067 16.338)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iyPOrgb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.746 16.275)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="igrPQfY" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.812 16.889)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="izWgADd" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.793 19.322)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="inKN1Md" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.019 15.74)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="ivR4DRo" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.606 22.447)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="i1X9QIb" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.05 12.518)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><linearGradient id="iYCpHTd" x1="14.547" x2="14.547" y1="7.916" y2="19.416" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iCyHxTd" x1="14.547" x2="14.547" y1="7.192" y2="10.786" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="inu3QVd" x1="7.567" x2="6.449" y1="26.603" y2="26.572" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iGVok1g" x1="15.614" x2="15.614" y1="14.969" y2="21.305" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="i3jeOEz" x1="19.699" x2="17.17" y1="12.409" y2="12.409" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i5vKplc" x1="15.38" x2="14.542" y1="11.399" y2="11.433" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iIyAO1d" x1="14.542" x2="14.542" y1="12.538" y2="12.073" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iBYd7Zb" x1="14.542" x2="14.542" y1="9.833" y2="10.379" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iyosSXd" x1="13.34" x2="13.659" y1="14.109" y2="13.274" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iaWAqBd" x1="17.502" x2="17.188" y1="9.861" y2="10.055" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8bDFFb" x1="13.104" x2="12.79" y1="9.861" y2="10.055" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYCSvse" x1="20.978" x2="19.771" y1="9.888" y2="12.065" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i9zU4Bd" x1="8.692" x2="10.15" y1="10.592" y2="10.465" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iCUJZ2d" x1="19.958" x2="19.958" y1="9.507" y2="11.41" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="igefvab" x1="10.606" x2="16.949" y1="6.666" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i51x3qc" x1="13.237" x2="13.449" y1="18.041" y2="18.041" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iKSxXmc" x1="14.552" x2="14.552" y1="30.259" y2="28.666" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="ixb0ayc" x1="14.552" x2="14.552" y1="26.116" y2="27.384" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="ieHEBub" x1="14.542" x2="14.542" y1="6.916" y2="11.697" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iVx7sqe" x1="14.542" x2="14.542" y1="19.548" y2="26.119" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="ijde7ue" x1="21.981" x2="18.293" y1="16.697" y2="29.916" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i2DZTHc" x1="19.981" x2="28.168" y1="22.134" y2="18.822" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="iY8WQPd" x1="14.418" x2="14.418" y1="4.164" y2="6.609" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iLLyQSd" x1="18.649" x2="20.152" y1="21.59" y2="16.4" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="ikMY1Tc" width="17.197" height="11.9" x="5.948" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/></filter><filter id="iYn2GGd" width="11.22" height="12.542" x="9.479" y="4.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2607" result="effect2_innerShadow_4002_2607"/></filter><filter id="i0r3afb" width="3.747" height="4.9" x="12.527" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".5"/></filter><filter id="iRzfoRc" width="2.277" height="3.3" x="13.403" y="9.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".1"/></filter><filter id="i9aS9Kb" width="3.718" height="1.573" x="12.683" y="13.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".05"/></filter><filter id="iI1bVxz" width="2.339" height="1.19" x="16.098" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/></filter><filter id="iseC5Wc" width="2.339" height="1.176" x="10.841" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/></filter><filter id="imeXgLt" width=".787" height=".696" x="15.99" y="9.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".05"/></filter><filter id="iC0toMd" width=".891" height=".913" x="16.829" y="9.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".1"/></filter><filter id="iIlz7Qb" width=".986" height="1.04" x="12.387" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".1"/></filter><filter id="i2okVYc" width=".913" height=".705" x="11.632" y="9.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".05"/></filter><filter id="i4w2INc" width="1.329" height="2.379" x="8.461" y="9.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".125"/></filter><filter id="iVLM76b" width="1.947" height="2.903" x="18.985" y="9.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".25"/></filter><filter id="iYsw6Mb" width="6.88" height="3.666" x="11.117" y="15.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/></filter><filter id="iXYtADc" width="4.97" height="3.828" x="13.237" y="15.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/></filter><filter id="iIt3cHc" width="5.52" height="4.05" x="11.787" y="2.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2607" result="effect2_innerShadow_4002_2607"/></filter><filter id="iVrt2ht" width="6.94" height="14.221" x="16.537" y="15.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2607" result="effect2_innerShadow_4002_2607"/></filter><filter id="iXUAvTb" width="11.012" height="8.855" x="17.82" y="16.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2607" result="effect2_innerShadow_4002_2607"/></filter><filter id="i7gFmWl" width="4.557" height="7.476" x="23.776" y="17.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2607"/></filter><filter id="iWZ3GQq" width="2.509" height="3.213" x="13.114" y="3.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2607"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2607" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2607" result="effect3_innerShadow_4002_2607"/></filter><filter id="iImgLnd" width="1.83" height="4.718" x="18.051" y="17.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".125"/></filter><filter id="iNDTsJd" width="2.769" height="7.081" x="18.356" y="23.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2607" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:firefighter-medium-dark" /></template>
<style>
.a0dieccro {
  d: path("m22.596 16.08l-1.38-.368a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.aggwxjksf {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M11.098 7.876a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ah26hbetv {
  d: path("M9.456 9.525a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bn4kkbczz {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.933 9.059c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.byahc9cfq {
  d: path("M9.717 13.489a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418H12.82c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.byer7fp6t {
  fill-rule: evenodd;
  d: path("M11.117 16.01v1.585c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c07875jis {
  d: path("M19.485 11.41q.058-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cdjhb1jfy {
  cx: 12.089px;
  cy: 9.712px;
  rx: 0.39px;
  ry: 0.197px;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
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

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
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

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.es6fcfbby {
  d: path("M17.52 10.106a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.ezt8k_b3n {
  fill: var(--svg-color--000, #000);
  d: path("M16.215 10.223c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fm8u67bql {
  d: path("m14.16 10.009l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fx8gmyb8r {
  d: path("M14.542 13.62c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.085-.197.209c.334.508.918.846 1.583.846s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gpnw08y-s {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.66 9.52c.064.084-.069.188-.22.3c-.151.114-.263.193-.327.108c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h5x965v8n {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.151 9.059c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu50muwro {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.14 10.205l-.59 1.838c-.101.378.14.757.484.757h.732c.343 0 .585-.385.484-.757l-.494-1.838c-.106-.407-.505-.407-.616 0");
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.ix9hjsb2b {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m14.16 10.009l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jyem0l38y {
  d: path("m19.972 16.675l4.416 1.16a3.56 3.56 0 0 0 2.071-.053l.148-.055c.178-.062.4-.053.554.108c1.072 1.125 1.43 2.621.984 4.235c-.448 1.615-1.733 2.765-2.98 3.034c-.084.02-.348.046-.506-.157l-.141-.14a3.5 3.5 0 0 0-1.745-1.112l-4.243-1.202a.61.61 0 0 1-.431-.779l1.252-4.674c.044-.22.37-.43.621-.365");
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
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

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lca308gqi {
  d: path("M19.403 11.974c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lf9xrjbpf {
  stop-color: var(--svg-color--6b3844, #6B3844);
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

.lrw1tsb1o {
  d: path("M25.609 17.954c.288-.022.575-.079.85-.172l.148-.054c.178-.062.4-.054.554.107c1.072 1.125 1.43 2.621.984 4.236c-.448 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.142-.14a3.5 3.5 0 0 0-.641-.588c1.567-.053 2.817-1.085 3.203-2.53c.39-1.469-.236-3.003-1.472-3.735z");
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lsnc20b-o {
  d: path("M8.439 7.49q.039.086.095.169c.175.257.27.563.27.874v1.2c.2-.141.466-.226.72-.264l-.03-1.537q0-.225.028-.442z");
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mxki9ud2p {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.191 13.225a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.mzl8dcg-h {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M18.241 7.985a1.85 1.85 0 0 0-.687-.411c-.304-.096-.686-.122-1.213-.057a.277.277 0 1 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.n3-1ri2jm {
  d: path("M13.237 15.916v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nbwi6nb0x {
  d: path("M21.537 26.116H7.567v3.8h13.97z");
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nm3_j9wvt {
  d: path("M22.134 7.916H7.112c-.395.32-.78 1.336-1.164 1.656v1.344c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.572c-.354-.42-.687-1.206-1.011-1.656");
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o26w0nbbn {
  d: path("M9.508 8.863c-.78.11-1.403.784-1.403 1.595c0 .86.674 1.561 1.521 1.607a78 78 0 0 1-.118-3.202");
}

.o3i__byxt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.506 17.915l-1.08 3.968");
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.oji17rbqg {
  d: path("M19.464 12.065q.1-1.597.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.ovvejmbph {
  d: path("M14.547 15.416c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
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

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.rftw2rbuv {
  d: path("M16.726 9.33a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.rl84unbtp {
  stop-color: var(--svg-color--241a1a, #241A1A);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
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

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sn1anc6hu {
  fill: var(--svg-color--000, #000);
  d: path("M12.869 10.223a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.srf37nb-e {
  d: path("M7.567 29.916V17.914a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.svtl-z3-k {
  d: path("M9.68 11.974a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
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

.tdust5bqt {
  d: path("M17.207 6.916h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.tlgdncc4h {
  cx: 12.089px;
  cy: 9.712px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tztu7rbfe {
  d: path("M13.173 10.118c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.ui2z9jbuj {
  d: path("M16.66 9.52c.064.084-.069.188-.22.3c-.151.114-.263.193-.327.108c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.unx234bdc {
  d: path("M8.618 7.916h11.847c.95 0 1.99.484 1.99 2.68h.69V9.29c0-1.43-.847-2.375-2.456-2.375H8.395c-1.609 0-2.457.945-2.457 2.375v1.304h.692c0-2.195 1.04-2.68 1.988-2.68");
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vdne8-75y {
  d: path("M21.537 17.925v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
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

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wxaqq2b7n {
  stop-color: var(--svg-color--6b3844, #6B3844);
  stop-opacity: 0;
}

.x4wbw5p_v {
  d: path("M20.845 7.276H8.25v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xb44u-blz {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.547 15.416c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xq7s1574r {
  fill: var(--svg-color--221315, #221315);
  d: path("M19.645 7.481q.046.171.05.356l-.079 1.607c.233.041.48.138.667.268V8.524c0-.311.096-.617.27-.874a1 1 0 0 0 .093-.169z");
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xyzz31b7b {
  d: path("M15.127 19.548h-1.17v6.57h1.17z");
}

.y-_y6_bwk {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.117 16.01v1.585c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.yduze7bxv {
  d: path("M13.237 16.877v1.699c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.018");
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.ywt6vob0u {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.537 26.116H7.567v3.8h13.97z");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z1g2odbcn {
  d: path("M13.264 4.852c0-.152.183-.23.293-.124l.154.148a.162.162 0 0 0 .275-.117v-.17c0-.344.178-.665.471-.847l.18-.111a.23.23 0 0 1 .35.195V5.02a.17.17 0 0 0 .28.132l.095-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.z6byr7vui {
  d: path("M12.358 9.33a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zn7hribqr {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.881 29.572c0-.2 1.146-4.104 1.719-6.031");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

</style>
