<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iESmfnb)"><path fill="url(#ikupwOd)" class="b-nuk-b4s"/><path fill="url(#ih1rDlc)" class="b-nuk-b4s"/></g><path class="svwri4bju"/><path fill="url(#iPxRisO)" class="xm4_27y7v"/><path fill="url(#i6tBdvc)" class="xm4_27y7v"/><path fill="url(#iTlLgRd)" class="xm4_27y7v"/><path fill="url(#iFxueid)" class="xm4_27y7v"/><path fill="url(#igTw5cd)" class="xm4_27y7v"/><path fill="url(#iaLDK8d)" class="xm4_27y7v"/><path fill="url(#iU6eLke)" class="lvn_s4bba"/><path fill="url(#iowSXBb)" class="lvn_s4bba"/><path fill="url(#i50WmTF)" class="lvn_s4bba"/><path fill="url(#iKFlild)" class="nghft9a4i"/><path fill="url(#iuCEThe)" class="nghft9a4i"/><path fill="url(#iV28Exe)" class="o_7k65e3p"/><path fill="url(#i8YYYJu)" class="q35ut-bwv"/><path fill="url(#itNvxQe)" class="q35ut-bwv"/><path fill="url(#ix7ZVpd)" class="kai7pcohn"/><path fill="url(#irIq7pc)" class="kai7pcohn"/><g filter="url(#ijvFMae)"><path fill="url(#iRaaZeA)" class="nsj3wyb5q"/></g><path fill="url(#iA1wXpe)" class="nsj3wyb5q"/><path fill="url(#iJ3CVBe)" class="nsj3wyb5q"/><path fill="url(#iWO0S7b)" class="nsj3wyb5q"/><path fill="url(#itUscLd)" class="nsj3wyb5q"/><path fill="url(#iwoPiHc)" class="nsj3wyb5q"/><g filter="url(#i8lfR1c)"><path class="k6m39dbtj"/></g><g filter="url(#ihHV3hc)"><path fill="url(#iNUoqGA)" class="euxlq7kmv"/><path fill="url(#i5jiNlb)" class="euxlq7kmv"/><path fill="url(#i3Ilmpg)" class="euxlq7kmv"/><path fill="url(#iPnnCac)" class="euxlq7kmv"/></g><g filter="url(#iVR37od)"><path stroke="url(#iXQqULU)" class="yj4tzhngs"/></g><path fill="url(#iI7fxcc)" class="ej09pim5p"/><path fill="url(#iusWzBc)" class="glmstv1nt"/><path fill="url(#ihd0Xoc)" class="glmstv1nt"/><path fill="url(#iw3j4fe)" class="by2-gdfnq"/><path fill="url(#ifMLGcc)" class="by2-gdfnq"/><path class="oh9mkbc-a"/><path fill="url(#irWok4b)" class="liay-b9hr"/><path fill="url(#iFiX7hc)" class="ywmafqbdi"/><path fill="url(#i1EmSdd)" class="ekjwvnbys"/><path class="evb2u87xr"/><g filter="url(#icMPWjb)"><path class="fd1qr3beh"/><path fill="url(#iAC76Je)" class="clihpib0k"/></g><g filter="url(#ilMa0jb)"><path fill="url(#iHMxxDc)" class="ci42hkhvf"/></g><path class="dkiiyacnb"/><path fill="url(#iANwL6b)" class="fjuiv8bxv"/><path class="n_v10_fli"/><g filter="url(#iiIfoyb)"><path fill="url(#iz8V9Kd)" class="te46mqb8e"/></g><g filter="url(#ie58ZeX)"><ellipse transform="rotate(-27.914 12.144 9.984)" class="rxeocmybz"/><ellipse fill="url(#ie0H9RH)" transform="rotate(-27.914 12.144 9.984)" class="gur8f5bqz"/></g><path fill="url(#imq9psb)" class="nmbyngbmi"/><path fill="url(#iw8eqqz)" class="nmbyngbmi"/><path fill="url(#iPJa05b)" class="nmbyngbmi"/><path fill="url(#iPrGNcb)" class="sv2ymebuc"/><path fill="url(#idCMYac)" class="sv2ymebuc"/><g filter="url(#iJIl12a)"><path class="a0ule7mja"/></g><g filter="url(#iDnHMFd)"><path class="q0s6-rbwf"/></g><g filter="url(#i0aNsod)"><path clip-rule="evenodd" class="wkzfombmd"/><path fill="url(#iwtBYlc)" clip-rule="evenodd" class="j7-uaxb4o"/><path fill="url(#iAjupwy)" clip-rule="evenodd" class="j7-uaxb4o"/></g><g filter="url(#iT77VQb)"><path fill="url(#itxLVJe)" class="lgc814y9z"/></g><path fill="url(#ixqjZmd)" class="hiks6xx6r"/><path fill="url(#izt1K2d)" class="hiks6xx6r"/><path fill="url(#i4wrYSc)" class="hiks6xx6r"/><path fill="url(#iybEFpb)" class="hiks6xx6r"/><path fill="url(#i1VkjOb)" class="hiks6xx6r"/><path fill="url(#iy9R3Xb)" class="lgc814y9z"/><path fill="url(#iRJ0Ojc)" class="lgc814y9z"/><path class="kvv0bkfgg"/><path fill="url(#iAOIRoe)" class="xc3k34bqk"/><path fill="url(#iIzyKec)" class="xc3k34bqk"/><path fill="url(#iU8R47c)" class="xc3k34bqk"/><path fill="url(#iqteKep)" class="xc3k34bqk"/><path fill="url(#iex7lod)" class="o7my5lz5f"/><path fill="url(#imsSkkc)" class="o7my5lz5f"/><path fill="url(#iVJUBCd)" class="o7my5lz5f"/><path fill="url(#ifHPhbb)" class="o7my5lz5f"/><path fill="url(#icusSDe)" class="o7my5lz5f"/><path fill="url(#ihIEj1E)" class="ztyt6bqgs"/><path fill="url(#imx5Uze)" class="ztyt6bqgs"/><path fill="url(#ixdP5Nb)" class="ztyt6bqgs"/><g filter="url(#iYL73ld)"><path fill="url(#iFzZ3ye)" class="x011atbqx"/><path fill="url(#ibf5jGb)" class="x011atbqx"/></g><g filter="url(#iPdC2qe)"><path fill="url(#iYk35zc)" class="lokx7ip3c"/><path fill="url(#iWBNNZa)" class="lokx7ip3c"/></g><path fill="url(#iirHiRl)" class="lokx7ip3c"/><path fill="url(#ipcKpHb)" class="lokx7ip3c"/><g filter="url(#iG5pgBe)"><path fill="url(#ilTal9b)" class="ueekzybdq"/><path fill="url(#iZ12zQd)" class="ueekzybdq"/><path fill="url(#ipQPqPG)" class="ueekzybdq"/></g><g filter="url(#i1yJMCc)"><path fill="url(#i6WNq9b)" class="nsfh4jb7l"/><path fill="url(#iDbM6jd)" class="nsfh4jb7l"/><path fill="url(#i0YdLSb)" class="nsfh4jb7l"/></g><g filter="url(#iWJArZd)"><path fill="url(#ieAJ7Hd)" class="th3_co_2p"/></g><g filter="url(#iyDIQhc)"><path stroke="url(#iTmg54d)" class="fpjjveb4m"/></g><g filter="url(#isb80eb)"><path class="p1bjzvexn"/></g><defs><radialGradient id="iPxRisO" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i6tBdvc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.281)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iTlLgRd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.156)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iFxueid" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.969)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="igTw5cd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.75)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="iaLDK8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.288)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iU6eLke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.865 29.781)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="i50WmTF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 30)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="iKFlild" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 24.005)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iuCEThe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 23)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="i8YYYJu" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 5.414 13.863)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="itNvxQe" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -2.118 25.086)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ix7ZVpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 9.05 11.867)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="irIq7pc" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -3.262 12.577)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iRaaZeA" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25492 0 0 -9.24801 17.419 10.808)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iA1wXpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.38582 13.2394 0 14.402 17.144)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iJ3CVBe" cx="0" cy="0" r="1" gradientTransform="rotate(93.794 4.941 14.544)scale(6.11532 2.25979)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iWO0S7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.71103 0 12.495 9.628)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="itUscLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 2.00156 0 17.098 9.216)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iwoPiHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.75 15.5018 0 14.644 15.031)" gradientUnits="userSpaceOnUse"><stop offset=".601" class="pid70_n0k"/><stop offset=".927" class="c94gsvpbd"/></radialGradient><radialGradient id="iXQqULU" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 18.912 -4.36)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iI7fxcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 14.597 14.52)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ihd0Xoc" cx="0" cy="0" r="1" gradientTransform="rotate(-149.036 10.303 1.655)scale(.31888 .54799)" gradientUnits="userSpaceOnUse"><stop class="edd2b3bzd"/><stop offset="1" class="mh0vkptms"/></radialGradient><radialGradient id="ifMLGcc" cx="0" cy="0" r="1" gradientTransform="rotate(-149.414 7.631 2.407)scale(.31763 .54196)" gradientUnits="userSpaceOnUse"><stop class="edd2b3bzd"/><stop offset="1" class="mh0vkptms"/></radialGradient><radialGradient id="irWok4b" cx="0" cy="0" r="1" gradientTransform="matrix(.33203 1.03515 -.45428 .14571 9.361 8.12)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="maq9lkm0q"/><stop offset="1" class="rn4f8hb8p"/></radialGradient><radialGradient id="iFiX7hc" cx="0" cy="0" r="1" gradientTransform="rotate(68.786 3.89 18.39)scale(1.37116 .78458)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="r6la93_zm"/><stop offset="1" class="p657lmvmk"/></radialGradient><radialGradient id="i1EmSdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.779 10.08)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iAC76Je" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.764 1.029)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iANwL6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.415 10.08)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ie0H9RH" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.128 10.3)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iw8eqqz" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 19.215 10.086)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iPJa05b" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 19.575 10.631)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="idCMYac" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .46 8.957)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iwtBYlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.094)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iAjupwy" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.095)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="itxLVJe" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.78 11.718)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="ixqjZmd" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.032 7.107)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="i4wrYSc" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.094)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iybEFpb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.125)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="i1VkjOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.219)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="iRJ0Ojc" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.994 16.092)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iAOIRoe" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.844)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iqteKep" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.778 20.761)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="imsSkkc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.202)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iVJUBCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.172)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ifHPhbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.156)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="icusSDe" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.063)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="imx5Uze" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.783)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ixdP5Nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.855)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iFzZ3ye" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.462 3.498)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="ibf5jGb" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.313)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iWBNNZa" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .515 19.65)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iirHiRl" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.422)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="ipcKpHb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17969 -.05864 .27278 21.786 16.36)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="iZ12zQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.974)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ipQPqPG" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.406)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="i6WNq9b" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.022 15.79)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iDbM6jd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.531)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="i0YdLSb" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.06 12.565)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><linearGradient id="ikupwOd" x1="14.587" x2="14.587" y1="8" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="ih1rDlc" x1="14.587" x2="14.587" y1="7.277" y2="10.87" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="iowSXBb" x1="7.607" x2="6.49" y1="26.688" y2="26.656" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iV28Exe" x1="15.654" x2="15.654" y1="15.053" y2="21.39" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iNUoqGA" x1="14.458" x2="15.3" y1="11.814" y2="11.814" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i5jiNlb" x1="13.402" x2="14.46" y1="11.664" y2="11.724" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="i3Ilmpg" x1="14.458" x2="14.458" y1="12.199" y2="13.021" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iPnnCac" x1="14.458" x2="14.458" y1="10.03" y2="10.844" gradientUnits="userSpaceOnUse"><stop class="mm3zuyb1y"/><stop offset="1" class="qa978sv2p"/></linearGradient><linearGradient id="iusWzBc" x1="18.333" x2="16.153" y1="8.437" y2="8.437" gradientUnits="userSpaceOnUse"><stop class="qnlqy2bep"/><stop offset="1" class="xtwlcdb6y"/></linearGradient><linearGradient id="iw3j4fe" x1="13.023" x2="10.842" y1="8.425" y2="8.425" gradientUnits="userSpaceOnUse"><stop class="qnlqy2bep"/><stop offset="1" class="xtwlcdb6y"/></linearGradient><linearGradient id="iHMxxDc" x1="17.557" x2="17.243" y1="10.133" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz8V9Kd" x1="13.159" x2="12.845" y1="10.133" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imq9psb" x1="21.033" x2="19.826" y1="10.154" y2="12.33" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iPrGNcb" x1="8.747" x2="10.206" y1="10.858" y2="10.73" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="izt1K2d" x1="10.646" x2="16.99" y1="6.75" y2="6.75" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iy9R3Xb" x1="13.277" x2="13.489" y1="18.125" y2="18.125" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iIzyKec" x1="14.592" x2="14.592" y1="30.344" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iU8R47c" x1="14.592" x2="14.592" y1="26.2" y2="27.469" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="iex7lod" x1="14.582" x2="14.582" y1="7" y2="11.781" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="ihIEj1E" x1="14.582" x2="14.582" y1="19.633" y2="26.203" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iYk35zc" x1="22.021" x2="18.333" y1="16.781" y2="30" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="ilTal9b" x1="20.021" x2="28.208" y1="22.219" y2="18.906" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="ieAJ7Hd" x1="14.458" x2="14.458" y1="4.248" y2="6.693" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iTmg54d" x1="18.689" x2="20.193" y1="21.674" y2="16.485" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="iESmfnb" width="17.197" height="11.9" x="5.989" y="7.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/></filter><filter id="ijvFMae" width="10.773" height="12.542" x="9.507" y="4.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2601" result="effect2_innerShadow_4002_2601"/></filter><filter id="i8lfR1c" width="3.877" height="4.9" x="12.304" y="9.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".5"/></filter><filter id="ihHV3hc" width="2.049" height="2.998" x="13.434" y="9.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".05"/></filter><filter id="iVR37od" width="3.718" height="1.573" x="12.738" y="13.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".05"/></filter><filter id="icMPWjb" width=".787" height=".696" x="16.045" y="9.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".05"/></filter><filter id="ilMa0jb" width=".891" height=".913" x="16.885" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".1"/></filter><filter id="iiIfoyb" width=".986" height="1.04" x="12.442" y="9.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".1"/></filter><filter id="ie58ZeX" width=".913" height=".705" x="11.687" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".05"/></filter><filter id="iJIl12a" width="1.329" height="2.379" x="8.564" y="9.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".125"/></filter><filter id="iDnHMFd" width="1.447" height="2.403" x="19.309" y="9.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".125"/></filter><filter id="i0aNsod" width="6.88" height="3.666" x="11.157" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/></filter><filter id="iT77VQb" width="4.97" height="3.828" x="13.277" y="15.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/></filter><filter id="iYL73ld" width="5.52" height="4.05" x="11.827" y="3.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2601" result="effect2_innerShadow_4002_2601"/></filter><filter id="iPdC2qe" width="6.94" height="14.221" x="16.577" y="15.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2601" result="effect2_innerShadow_4002_2601"/></filter><filter id="iG5pgBe" width="11.012" height="8.855" x="17.86" y="16.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2601" result="effect2_innerShadow_4002_2601"/></filter><filter id="i1yJMCc" width="4.557" height="7.476" x="23.816" y="17.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2601"/></filter><filter id="iWJArZd" width="2.509" height="3.213" x="13.154" y="3.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2601"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2601" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2601"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2601" result="effect3_innerShadow_4002_2601"/></filter><filter id="iyDIQhc" width="1.83" height="4.718" x="18.091" y="17.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".125"/></filter><filter id="isb80eb" width="2.769" height="7.081" x="18.396" y="23.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2601" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:firefighter" /></template>
<style>
.a0ule7mja {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M9.56 9.791a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.b-nuk-b4s {
  d: path("M22.174 8H7.152c-.395.32-.779 1.336-1.163 1.656V11c0 4.69 3.854 8.5 8.598 8.5s8.599-3.81 8.599-8.5V9.656c-.355-.42-.688-1.206-1.012-1.656");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by2-gdfnq {
  d: path("M11.099 7.954a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.552a2.22 2.22 0 0 0-1.386.284a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c94gsvpbd {
  stop-color: var(--svg-color--d5752a, #D5752A);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.ci42hkhvf {
  d: path("M17.576 10.378a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clihpib0k {
  d: path("M16.716 9.791c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
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

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dkiiyacnb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.206 9.33c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
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

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.edd2b3bzd {
  stop-color: var(--svg-color--923b32, #923B32);
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ej09pim5p {
  d: path("M14.597 13.877c-.508 0-.984-.12-1.385-.329c-.137-.07-.285.085-.198.21c.335.507.918.845 1.583.845s1.248-.338 1.583-.846c.087-.13-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.ekjwvnbys {
  d: path("M16.781 9.603a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.euxlq7kmv {
  d: path("m14.082 10.325l-.524 1.774c-.107.364.15.73.513.73h.774c.364 0 .62-.371.513-.73l-.523-1.774a.388.388 0 0 0-.753 0");
}

.evb2u87xr {
  fill: var(--svg-color--000, #000);
  d: path("M16.27 10.495c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.fd1qr3beh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.716 9.791c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fjuiv8bxv {
  d: path("M12.413 9.602a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.fpjjveb4m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 18l-1.08 3.968");
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glmstv1nt {
  d: path("M18.296 8.078a1.85 1.85 0 0 0-.687-.411c-.304-.096-.685-.122-1.213-.057a.277.277 0 0 0 .068.55c.48-.059.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.gur8f5bqz {
  cx: 12.144px;
  cy: 9.984px;
  rx: 0.39px;
  ry: 0.197px;
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hiks6xx6r {
  d: path("M20.886 7.36H8.289v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.166 2.193 5.166 4.927z");
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
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

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j7-uaxb4o {
  fill-rule: evenodd;
  d: path("M11.157 16.094v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98V16.1a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k6m39dbtj {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m13.964 10.407l-.635 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.407-.542-.407-.661 0");
}

.kai7pcohn {
  d: path("M9.736 12.058a1.64 1.64 0 0 1-.905-.309v.931c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
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

.kvv0bkfgg {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.2H7.607V30h13.97z");
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lgc814y9z {
  d: path("M13.277 16.962v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.017");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.liay-b9hr {
  d: path("M8.48 7.574q.037.087.094.169c.175.257.27.563.27.874v1.2c.201-.141.466-.226.72-.263l-.03-1.538q0-.225.028-.442z");
}

.lokx7ip3c {
  d: path("m22.636 16.164l-1.38-.368a.51.51 0 0 0-.625.358L16.827 30h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lvn_s4bba {
  d: path("M7.607 30V17.998a10.98 10.98 0 0 0-4.02 8.502V30z");
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.maq9lkm0q {
  stop-color: var(--svg-color--a7580e, #A7580E);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mh0vkptms {
  stop-color: var(--svg-color--923b32, #923B32);
  stop-opacity: 0;
}

.mm3zuyb1y {
  stop-color: var(--svg-color--ffad36, #FFAD36);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n_v10_fli {
  fill: var(--svg-color--000, #000);
  d: path("M12.924 10.495a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nghft9a4i {
  d: path("M21.577 18.01V30h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nmbyngbmi {
  d: path("M19.519 12.33c.066-1.064.118-2.11.174-3.174c.755.132 1.34.774 1.34 1.567a1.61 1.61 0 0 1-1.514 1.607");
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nsfh4jb7l {
  d: path("M25.649 18.038q.435-.032.85-.171l.148-.055c.179-.062.401-.054.555.107c1.071 1.125 1.43 2.622.983 4.236c-.447 1.615-1.732 2.764-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.003-1.472-3.735z");
}

.nsj3wyb5q {
  d: path("M9.747 13.573a3.93 3.93 0 0 0 3.906 3.406h1.896a3.93 3.93 0 0 0 3.906-3.406c.118-1.883.238-3.76.326-5.642a1.453 1.453 0 0 0-1.386-1.432h-1.408c-.96 0-1.829-.564-2.223-1.443a.67.67 0 0 0-.618-.419h-1.28c-1.855 0-3.359 1.513-3.359 3.38c0 1.86.117 3.69.24 5.556");
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o_7k65e3p {
  d: path("M13.277 16v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98V16z");
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o7my5lz5f {
  d: path("M8.659 8h11.847c.948 0 1.988.484 1.988 2.68h.692V9.375c0-1.43-.848-2.375-2.457-2.375H8.436c-1.61 0-2.457.945-2.457 2.375v1.305h.69C6.67 8.484 7.71 8 8.66 8");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9mkbc-a {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.988 9.33c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
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

.p1bjzvexn {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.656c0-.2 1.146-4.104 1.719-6.031");
}

.p657lmvmk {
  stop-color: var(--svg-color--a24808, #A24808);
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

.pid70_n0k {
  stop-color: var(--svg-color--d5752a, #D5752A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q0s6-rbwf {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M19.559 11.679q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.q35ut-bwv {
  d: path("M19.458 12.058c.336-.01.65-.124.905-.309v.931c0 .894-.532 1.69-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.qa978sv2p {
  stop-color: var(--svg-color--ffad36, #FFAD36);
  stop-opacity: 0;
}

.qnlqy2bep {
  stop-color: var(--svg-color--8d2c29, #8D2C29);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r6la93_zm {
  stop-color: var(--svg-color--af5911, #AF5911);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rn4f8hb8p {
  stop-color: var(--svg-color--9e490c, #9E490C);
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rxeocmybz {
  cx: 12.144px;
  cy: 9.984px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sv2ymebuc {
  d: path("M9.556 9.129a1.62 1.62 0 0 0-1.395 1.595c0 .858.673 1.56 1.52 1.606a78 78 0 0 1-.125-3.201");
}

.svwri4bju {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
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

.te46mqb8e {
  d: path("M13.228 10.39c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.th3_co_2p {
  d: path("M13.304 4.937c0-.153.183-.23.293-.125l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.179-.665.472-.847l.18-.112a.23.23 0 0 1 .35.195v1.195a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ueekzybdq {
  d: path("m20.012 16.76l4.416 1.16a3.56 3.56 0 0 0 2.071-.054l.148-.054c.179-.062.401-.054.555.107c1.071 1.125 1.43 2.622.983 4.236s-1.732 2.764-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-1.745-1.111l-4.243-1.202a.61.61 0 0 1-.43-.78l1.25-4.674c.045-.22.37-.43.622-.365");
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
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

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wkzfombmd {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.157 16.094v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98V16.1a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x011atbqx {
  d: path("M17.247 7h-5.32V5.71c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xc3k34bqk {
  d: path("M21.577 26.2H7.607V30h13.97z");
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xm4_27y7v {
  d: path("M14.587 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xtwlcdb6y {
  stop-color: var(--svg-color--90331e, #90331E);
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yj4tzhngs {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.246 13.482c.39.203.855.32 1.351.32c.5 0 .96-.117 1.35-.32h.001a.23.23 0 0 1 .271.044a.214.214 0 0 1 .024.273m-2.997-.317l2.934.275m-2.934-.275a.23.23 0 0 0-.271.046a.21.21 0 0 0-.024.271m.295-.317l-.232.275m3.229.042l-.063-.042m.063.042l-.063-.042m.063.042a1.97 1.97 0 0 1-1.646.88a1.97 1.97 0 0 1-1.646-.88m3.23-.042a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042v.001l.062-.043m-.062.042h-.001l.063-.042");
}

.ywmafqbdi {
  d: path("M19.705 7.574q.045.172.05.357l-.08 1.606c.234.041.48.138.668.268V8.617c0-.311.095-.617.27-.874a1 1 0 0 0 .092-.169z");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
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

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.ztyt6bqgs {
  d: path("M15.167 19.633h-1.17v6.57h1.17z");
}

</style>
