<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#izS8k1b)"><path fill="url(#i2yxfPe)" class="uu7jkli0h"/><path fill="url(#iI1J4mc)" class="uu7jkli0h"/></g><path class="phja6i1dz"/><path fill="url(#iZ43slb)" class="xg0ysqb-q"/><path fill="url(#iNBIPAb)" class="xg0ysqb-q"/><path fill="url(#iWWBime)" class="xg0ysqb-q"/><path fill="url(#iKez1eb)" class="xg0ysqb-q"/><path fill="url(#i7KSbNc)" class="xg0ysqb-q"/><path fill="url(#iZx0rjd)" class="xg0ysqb-q"/><path fill="url(#ioACxKg)" class="tu1bpib0q"/><path fill="url(#ifFXnMb)" class="tu1bpib0q"/><path fill="url(#i1znKwb)" class="tu1bpib0q"/><path fill="url(#iMcmWfW)" class="qpgkyxdpd"/><path fill="url(#iOWGx0d)" class="qpgkyxdpd"/><path fill="url(#izikkZR)" class="w8wvz7bvo"/><path fill="url(#ibpC7Wd)" class="vvjpurbix"/><path fill="url(#iDbYR6c)" class="rue50s-3i"/><g filter="url(#iGuvZDd)"><path fill="url(#ikkObEe)" class="nq16iyigx"/></g><path fill="url(#id9ucKJ)" class="nq16iyigx"/><path fill="url(#iaZVBce)" class="nq16iyigx"/><path fill="url(#ibApknc)" class="nq16iyigx"/><path fill="url(#iBF2cbc)" class="nq16iyigx"/><path fill="url(#i1gVXBO)" class="nq16iyigx"/><path fill="url(#iTttkrd)" class="nq16iyigx"/><path fill="url(#iBuZvKb)" class="nq16iyigx"/><path fill="url(#iX2vGxT)" class="nq16iyigx"/><path fill="url(#ijx2Nje)" class="nq16iyigx"/><path fill="url(#ikJ1pvd)" class="nq16iyigx"/><g filter="url(#iJgzv6d)"><path class="lxo-2bbge"/></g><g filter="url(#i5us1Td)"><path class="xbjjz7b_r"/><path fill="url(#isr7hud)" class="spkfhwb7u"/><path fill="url(#iRT17ce)" class="spkfhwb7u"/><path fill="url(#iRR0PFe)" class="spkfhwb7u"/><path fill="url(#iVl4F1v)" class="spkfhwb7u"/><path fill="url(#iYIPTMQ)" class="spkfhwb7u"/></g><g filter="url(#iHFWQ4d)"><path stroke="url(#iDtSbZc)" class="wl_xz8hsk"/></g><path fill="url(#ie0Pwkc)" class="o9z3pit6u"/><g filter="url(#iCP6rcD)"><path class="vgmn0mx5g"/></g><g filter="url(#ixrwU3d)"><path class="j6qe09b4d"/></g><path class="iaw8ntbyf"/><path fill="url(#i5urywc)" class="fusj4wb1q"/><path class="b5gc28bwk"/><g filter="url(#ioXRrde)"><path class="y-hjaabwy"/><path fill="url(#i7wdTdw)" class="aeqimjb2i"/></g><g filter="url(#iDveGwd)"><path fill="url(#ipSRoSb)" class="vk5m556go"/></g><path fill="url(#iWLV2yc)" class="z-m1_9b5s"/><path class="gj2iqbcax"/><path class="l-bc0mb6y"/><path fill="url(#ihOCfdb)" class="ut8b-ksqo"/><path class="i5h5ctb6o"/><g filter="url(#iMMpNJe)"><path fill="url(#iIsMEkc)" class="l97lddceb"/></g><g filter="url(#iGtHQgM)"><ellipse transform="rotate(-27.914 12.167 9.707)" class="xs__yj8bq"/><ellipse fill="url(#iDbQD2J)" transform="rotate(-27.914 12.167 9.707)" class="h7typzyar"/></g><path fill="url(#iFk6wDe)" class="npru6ebxq"/><path fill="url(#iYgkDLd)" class="npru6ebxq"/><path fill="url(#io9XURd)" class="npru6ebxq"/><path fill="url(#iubLFyZ)" class="npru6ebxq"/><path fill="url(#itXjZTO)" class="ow824p6ue"/><path fill="url(#iPaOPgu)" class="ow824p6ue"/><path fill="url(#iAJMvAc)" class="d4meb8b6x"/><path fill="url(#iUIuORd)" class="d4meb8b6x"/><path fill="url(#itNu4ed)" class="d4meb8b6x"/><path fill="url(#iiFsMcd)" class="d4meb8b6x"/><path fill="url(#iP5FTJb)" class="d4meb8b6x"/><g filter="url(#imDWOCc)"><path fill="url(#iOKfzad)" class="aok-xe3rt"/></g><g filter="url(#icddxzc)"><path fill="url(#imO3jab)" class="j4f3sybvp"/></g><g filter="url(#i9mY6Gc)"><path clip-rule="evenodd" class="vg8wq_b3w"/><path fill="url(#ia5AQde)" clip-rule="evenodd" class="qmjk6vb6b"/><path fill="url(#if59vrb)" clip-rule="evenodd" class="qmjk6vb6b"/></g><g filter="url(#isqylld)"><path fill="url(#i9LZige)" class="l6k74tmui"/></g><path fill="url(#iuLiOBd)" class="l6k74tmui"/><path fill="url(#i2NKJSd)" class="l6k74tmui"/><path class="gn0aw0bof"/><path fill="url(#inJJQvc)" class="yg_hk3cro"/><path fill="url(#iImJxRb)" class="yg_hk3cro"/><path fill="url(#iW07ldW)" class="yg_hk3cro"/><path fill="url(#irguy6b)" class="yg_hk3cro"/><path fill="url(#izIp1Xc)" class="tkitgpshn"/><path fill="url(#ilAIw7A)" class="tkitgpshn"/><path fill="url(#icsa7Id)" class="tkitgpshn"/><path fill="url(#iLc3HiV)" class="tkitgpshn"/><path fill="url(#idX1eib)" class="tkitgpshn"/><path fill="url(#iKhir9d)" class="c56ws2bfy"/><path fill="url(#iRT3apc)" class="c56ws2bfy"/><path fill="url(#i1gu9Qc)" class="c56ws2bfy"/><g filter="url(#i4m8hne)"><path fill="url(#ijVChRc)" class="oynoiufkz"/><path fill="url(#iGUQueN)" class="oynoiufkz"/></g><g filter="url(#iEEWHzR)"><path fill="url(#iWTrQ0d)" class="fw3yjoqoy"/><path fill="url(#ijhitPe)" class="fw3yjoqoy"/></g><path fill="url(#imD63ec)" class="fw3yjoqoy"/><path fill="url(#iN9YvBK)" class="fw3yjoqoy"/><g filter="url(#ijbt9ic)"><path fill="url(#iFUjjad)" class="deamnec1y"/><path fill="url(#iHiBIIb)" class="deamnec1y"/><path fill="url(#iHIeVye)" class="deamnec1y"/></g><g filter="url(#i8A2JTc)"><path fill="url(#ixR7jOd)" class="c63v9v0ir"/><path fill="url(#iYZ7kWc)" class="c63v9v0ir"/><path fill="url(#ieMRlhe)" class="c63v9v0ir"/></g><g filter="url(#iG0K38n)"><path fill="url(#igH6Jfe)" class="d5p-_dbco"/></g><g filter="url(#irkKIqd)"><path stroke="url(#iH2bued)" class="dphc7m_-l"/></g><g filter="url(#iqhsVUd)"><path class="s5phn4bzq"/></g><defs><radialGradient id="iZ43slb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.62 15.88)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="iNBIPAb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.34 26.192)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iWWBime" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.684 26.067)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iKez1eb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.59 23.88)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="i7KSbNc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.34 22.66)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="iZx0rjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.059 16.198)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="ioACxKg" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.903 29.692)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="i1znKwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.645 29.91)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="iMcmWfW" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.152 23.916)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iOWGx0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.615 22.91)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="ibpC7Wd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.307 19.753)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iDbYR6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 8.563 12.15)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="ikkObEe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 17.428 10.719)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iaZVBce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 16.202 4.805)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="ibApknc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.067 9.406)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iBF2cbc" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09428 1.19083 .00428 12.32 9.453)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i1gVXBO" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 18.053 11.707)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iTttkrd" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 9.153 6.394)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iBuZvKb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.531 13.08)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iX2vGxT" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.905 7.677)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="ikJ1pvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1562 11.6537 0 14.667 16.54)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="d80o5pb2d"/><stop offset="1" class="ro1ymd9nm"/></radialGradient><radialGradient id="iRT17ce" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.086 12.08)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iVl4F1v" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 15.203 11.51)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="ie0Pwkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 14.62 14.258)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="i5urywc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 16.802 9.803)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7wdTdw" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.708 .885)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLV2yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .98438 0 9.497 8.915)" gradientUnits="userSpaceOnUse"><stop class="rl84unbtp"/><stop offset="1" class="s7ag-e23r"/></radialGradient><radialGradient id="ihOCfdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.438 9.803)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iDbQD2J" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.151 10.022)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYgkDLd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 19.238 9.817)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="io9XURd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 19.598 10.361)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iubLFyZ" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 19.712 10.534)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iPaOPgu" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .581 8.832)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iAJMvAc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.078 7.075)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="itNu4ed" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.327 7.005)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iiFsMcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.684 3.036)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="iP5FTJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.871 7.13)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="iOKfzad" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 9.705 10.461)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="ia5AQde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.196 16.005)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="if59vrb" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.229 16.005)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="i9LZige" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.817 11.68)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i2NKJSd" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 14.032 16.003)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="inJJQvc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.615 27.755)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="irguy6b" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.725 20.731)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="ilAIw7A" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.741 7.112)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="icsa7Id" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.668 8.083)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="iLc3HiV" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.715 9.067)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="idX1eib" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.059 8.973)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iRT3apc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 15 21.694)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="i1gu9Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.62 25.766)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="ijVChRc" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.486 3.455)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iGUQueN" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.965 7.223)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="ijhitPe" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .57 19.62)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="imD63ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.145 16.333)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iN9YvBK" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17969 -.05864 .27278 21.825 16.27)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="iHiBIIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.89 16.884)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="iHIeVye" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.871 19.317)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ixR7jOd" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.06 15.754)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iYZ7kWc" cx="0" cy="0" r="1" gradientTransform="rotate(-170.248 15.3 9.998)scale(4.05865 6.1655)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="ieMRlhe" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.089 12.524)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><linearGradient id="i2yxfPe" x1="14.625" x2="14.625" y1="7.911" y2="19.411" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iI1J4mc" x1="14.625" x2="14.625" y1="7.188" y2="10.781" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ifFXnMb" x1="7.645" x2="6.528" y1="26.598" y2="26.567" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="izikkZR" x1="15.692" x2="15.692" y1="14.964" y2="21.301" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="id9ucKJ" x1="19.777" x2="15.425" y1="12.404" y2="12.404" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ijx2Nje" x1="14.667" x2="14.667" y1="16.971" y2="16.331" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="isr7hud" x1="15.459" x2="14.62" y1="11.394" y2="11.429" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iRR0PFe" x1="14.62" x2="14.62" y1="12.533" y2="12.068" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iYIPTMQ" x1="14.62" x2="14.62" y1="9.578" y2="10.375" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iDtSbZc" x1="13.418" x2="13.737" y1="14.104" y2="13.27" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="ipSRoSb" x1="17.58" x2="17.266" y1="9.857" y2="10.05" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIsMEkc" x1="13.182" x2="12.868" y1="9.857" y2="10.05" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFk6wDe" x1="21.056" x2="19.849" y1="9.884" y2="12.06" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="itXjZTO" x1="8.77" x2="10.229" y1="10.588" y2="10.46" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iUIuORd" x1="10.684" x2="17.028" y1="6.661" y2="6.661" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="imO3jab" x1="20.036" x2="20.036" y1="9.502" y2="11.405" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iuLiOBd" x1="13.315" x2="13.528" y1="18.036" y2="18.036" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iImJxRb" x1="14.63" x2="14.63" y1="30.255" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iW07ldW" x1="14.63" x2="14.63" y1="26.111" y2="27.38" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="izIp1Xc" x1="14.62" x2="14.62" y1="6.911" y2="11.692" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iKhir9d" x1="14.62" x2="14.62" y1="19.544" y2="26.114" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iWTrQ0d" x1="22.059" x2="18.371" y1="16.692" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="iFUjjad" x1="20.059" x2="28.246" y1="22.13" y2="18.817" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="igH6Jfe" x1="14.496" x2="14.496" y1="4.159" y2="6.604" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iH2bued" x1="18.727" x2="20.231" y1="21.585" y2="16.395" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="izS8k1b" width="17.197" height="11.9" x="6.027" y="7.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/></filter><filter id="iGuvZDd" width="11.22" height="12.542" x="9.557" y="4.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2604" result="effect2_innerShadow_4002_2604"/></filter><filter id="iJgzv6d" width="3.747" height="4.9" x="12.605" y="8.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".5"/></filter><filter id="i5us1Td" width="2.277" height="3.3" x="13.482" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".1"/></filter><filter id="iHFWQ4d" width="3.718" height="1.573" x="12.761" y="13.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".05"/></filter><filter id="iCP6rcD" width="2.339" height="1.19" x="16.209" y="7.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/></filter><filter id="ixrwU3d" width="2.339" height="1.176" x="10.953" y="7.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/></filter><filter id="ioXRrde" width=".787" height=".696" x="16.068" y="9.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".05"/></filter><filter id="iDveGwd" width=".891" height=".913" x="16.908" y="9.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".1"/></filter><filter id="iMMpNJe" width=".986" height="1.04" x="12.465" y="9.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".1"/></filter><filter id="iGtHQgM" width=".913" height=".705" x="11.71" y="9.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".05"/></filter><filter id="imDWOCc" width="1.329" height="2.379" x="8.539" y="9.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".125"/></filter><filter id="icddxzc" width="1.947" height="2.903" x="19.063" y="9.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".25"/></filter><filter id="i9mY6Gc" width="6.88" height="3.666" x="11.195" y="15.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/></filter><filter id="isqylld" width="4.97" height="3.828" x="13.315" y="15.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/></filter><filter id="i4m8hne" width="5.52" height="4.05" x="11.865" y="2.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2604" result="effect2_innerShadow_4002_2604"/></filter><filter id="iEEWHzR" width="6.94" height="14.221" x="16.615" y="15.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2604" result="effect2_innerShadow_4002_2604"/></filter><filter id="ijbt9ic" width="11.012" height="8.855" x="17.898" y="16.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2604" result="effect2_innerShadow_4002_2604"/></filter><filter id="i8A2JTc" width="4.557" height="7.476" x="23.854" y="17.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2604"/></filter><filter id="iG0K38n" width="2.509" height="3.213" x="13.192" y="3.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2604"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2604" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2604"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2604" result="effect3_innerShadow_4002_2604"/></filter><filter id="irkKIqd" width="1.83" height="4.718" x="18.129" y="17.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".125"/></filter><filter id="iqhsVUd" width="2.769" height="7.081" x="18.434" y="23.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2604" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:firefighter-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.aeqimjb2i {
  d: path("M16.739 9.514c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.086.008-.246.159-.359s.325-.136.389-.05");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.aok-xe3rt {
  d: path("M9.535 9.52a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b5gc28bwk {
  fill: var(--svg-color--000, #000);
  d: path("M16.293 10.218c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c56ws2bfy {
  d: path("M15.205 19.544h-1.17v6.57h1.17z");
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c63v9v0ir {
  d: path("M25.687 17.949a3.5 3.5 0 0 0 .85-.172l.148-.054c.178-.062.401-.054.555.107c1.071 1.125 1.43 2.622.983 4.236s-1.732 2.764-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.085 3.203-2.53c.39-1.469-.236-3.003-1.472-3.735z");
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
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

.d4meb8b6x {
  d: path("M20.924 7.27H8.327v-.377c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.166 2.193 5.166 4.927z");
}

.d5p-_dbco {
  d: path("M13.342 4.848c0-.153.183-.231.293-.125l.155.148a.162.162 0 0 0 .274-.116v-.17c0-.345.179-.665.472-.847l.18-.112a.23.23 0 0 1 .35.195v1.195a.17.17 0 0 0 .278.132l.096-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d80o5pb2d {
  stop-color: var(--svg-color--361f27, #361F27);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.deamnec1y {
  d: path("m20.05 16.67l4.416 1.16a3.56 3.56 0 0 0 2.071-.053l.148-.054c.178-.062.401-.054.555.107c1.071 1.125 1.43 2.621.983 4.236s-1.732 2.764-2.98 3.033c-.084.02-.348.046-.505-.157l-.142-.14a3.5 3.5 0 0 0-1.745-1.111l-4.243-1.202a.61.61 0 0 1-.43-.78l1.25-4.674c.045-.22.37-.43.622-.365");
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

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dphc7m_-l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.584 17.91l-1.08 3.968");
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

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fusj4wb1q {
  d: path("M16.804 9.326a.892.892 0 0 1 .86 1.128H15.94a.896.896 0 0 1 .864-1.128");
}

.fw3yjoqoy {
  d: path("m22.674 16.075l-1.38-.368a.51.51 0 0 0-.625.358L16.865 29.91h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gj2iqbcax {
  fill: var(--svg-color--221315, #221315);
  d: path("M19.724 7.476q.046.172.049.357l-.079 1.606c.234.041.48.138.667.268V8.52c0-.31.096-.617.27-.874a1 1 0 0 0 .093-.169z");
}

.gn0aw0bof {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.615 26.11H7.645v3.8h13.97z");
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h7typzyar {
  cx: 12.167px;
  cy: 9.707px;
  rx: 0.39px;
  ry: 0.197px;
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i5h5ctb6o {
  fill: var(--svg-color--000, #000);
  d: path("M12.947 10.218a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.iaw8ntbyf {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.011 9.054c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
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

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j4f3sybvp {
  d: path("M19.563 11.405q.059-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j6qe09b4d {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.21 8.011a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.438z");
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
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

.l-bc0mb6y {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.23 9.054c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l6k74tmui {
  d: path("M13.315 16.872v1.699c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.018");
}

.l97lddceb {
  d: path("M13.251 10.114c0-.289-.234-.481-.297-.54l-.289.28l.178.36z");
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

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.lxo-2bbge {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.219 10.2l-.591 1.839c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.839c-.106-.407-.504-.407-.615 0");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.npru6ebxq {
  d: path("M19.542 12.06c.066-1.064.13-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.19");
}

.nq16iyigx {
  d: path("M9.795 13.484a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o9z3pit6u {
  d: path("M14.62 13.616c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.249-.338 1.583-.846c.087-.13-.06-.278-.197-.209a3 3 0 0 1-1.386.329");
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.ow824p6ue {
  d: path("M9.587 8.86c-.782.111-1.403.782-1.403 1.594c0 .859.673 1.56 1.52 1.606a78 78 0 0 1-.117-3.2");
}

.oynoiufkz {
  d: path("M17.285 6.91h-5.32V5.62c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.phja6i1dz {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.625 15.41c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
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

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qmjk6vb6b {
  fill-rule: evenodd;
  d: path("M11.195 16.005v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.879h-1.896c-.942 0-1.813-.33-2.496-.885");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qpgkyxdpd {
  d: path("M21.615 17.92v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rl84unbtp {
  stop-color: var(--svg-color--241a1a, #241A1A);
}

.ro1ymd9nm {
  stop-color: var(--svg-color--361f27, #361F27);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rue50s-3i {
  d: path("M9.759 11.969a1.64 1.64 0 0 1-.905-.309v.931c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
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

.s5phn4bzq {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.96 29.567c0-.2 1.145-4.104 1.718-6.031");
}

.s7ag-e23r {
  stop-color: var(--svg-color--27050c, #27050C);
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.spkfhwb7u {
  d: path("m14.238 10.004l-.532 1.839c-.108.378.152.756.521.756h.786c.37 0 .63-.384.521-.756l-.532-1.839c-.113-.407-.645-.407-.764 0");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
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

.tkitgpshn {
  d: path("M8.697 7.91h11.847c.948 0 1.988.485 1.988 2.68h.692V9.287c0-1.43-.848-2.375-2.457-2.375H8.474c-1.61 0-2.457.945-2.457 2.375v1.305h.69c0-2.196 1.04-2.68 1.99-2.68");
}

.tu1bpib0q {
  d: path("M7.645 29.91v-12a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.ut8b-ksqo {
  d: path("M12.436 9.326a.893.893 0 0 0-.86 1.127H13.3a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.uu7jkli0h {
  d: path("M22.212 7.91H7.19c-.395.32-.779 1.337-1.163 1.657v1.344c0 4.69 3.854 8.5 8.598 8.5s8.599-3.81 8.599-8.5V9.567c-.355-.42-.688-1.206-1.012-1.656");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vg8wq_b3w {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.195 16.005v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.879h-1.896c-.942 0-1.813-.33-2.496-.885");
}

.vgmn0mx5g {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.353 8.12a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 0 0 .067.55c.482-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.vk5m556go {
  d: path("M17.6 10.1a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
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

.vvjpurbix {
  d: path("M19.482 11.969c.335-.01.649-.125.904-.309v.931c0 .894-.532 1.69-1.34 2.02q.256-.546.345-1.18z");
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w8wvz7bvo {
  d: path("M13.315 15.91v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.wl_xz8hsk {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.27 13.22h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.271c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xbjjz7b_r {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.238 10.004l-.532 1.839c-.108.378.152.756.521.756h.786c.37 0 .63-.384.521-.756l-.532-1.839c-.113-.407-.645-.407-.764 0");
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xg0ysqb-q {
  d: path("M14.625 15.41c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xs__yj8bq {
  cx: 12.167px;
  cy: 9.707px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.y-hjaabwy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.739 9.514c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.086.008-.246.159-.359s.325-.136.389-.05");
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.yg_hk3cro {
  d: path("M21.615 26.11H7.645v3.8h13.97z");
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.z-m1_9b5s {
  d: path("M8.517 7.485q.038.086.095.169c.175.257.27.563.27.874v1.2c.201-.141.466-.226.72-.263l-.03-1.538q0-.225.028-.442z");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
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

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
