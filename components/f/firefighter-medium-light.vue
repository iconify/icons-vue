<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWrwUXl)"><path fill="url(#icFSX4d)" class="xdpeznbmk"/><path fill="url(#iY6ajVd)" class="xdpeznbmk"/></g><path class="xtob7mb0f"/><path fill="url(#i5XxABb)" class="i-vys5vjv"/><path fill="url(#iTqVWRc)" class="i-vys5vjv"/><path fill="url(#iwYYfzk)" class="i-vys5vjv"/><path fill="url(#irvaKOc)" class="i-vys5vjv"/><path fill="url(#iEzvdkd)" class="i-vys5vjv"/><path fill="url(#iJefplb)" class="i-vys5vjv"/><path fill="url(#itaTVgb)" class="dqwyzhw7l"/><path fill="url(#ihjOAre)" class="dqwyzhw7l"/><path fill="url(#idckKib)" class="dqwyzhw7l"/><path fill="url(#i8hks0c)" class="jrzio0bwr"/><path fill="url(#ipx3ORd)" class="jrzio0bwr"/><path fill="url(#i8ABIJc)" class="yv1wrjbcb"/><g filter="url(#ije14ae)"><path fill="url(#ioYI98F)" class="kwzpxaciw"/><path fill="url(#i6ZaNJc)" class="kwzpxaciw"/></g><path fill="url(#iVcjSHe)" class="u4vma9bug"/><path fill="url(#iifKQde)" class="uk-_dobib"/><path fill="url(#iKiZOyb)" class="uk-_dobib"/><path fill="url(#iBjKXpd)" class="uk-_dobib"/><path fill="url(#iKiZOyb)" class="uk-_dobib"/><g filter="url(#iUIgHZl)"><path fill="url(#iaGuGFe)" class="jq4unsb0q"/></g><path fill="url(#i7ZuSFd)" class="jq4unsb0q"/><path fill="url(#is8MVOc)" class="jq4unsb0q"/><path fill="url(#iGsuGjb)" class="jq4unsb0q"/><path fill="url(#if9U41w)" class="jq4unsb0q"/><path fill="url(#iqVxoqb)" class="jq4unsb0q"/><path fill="url(#ipXtFoc)" class="jq4unsb0q"/><path fill="url(#iV2zozd)" class="jq4unsb0q"/><path fill="url(#is2h5co)" class="jq4unsb0q"/><path fill="url(#iBtvTmc)" class="jq4unsb0q"/><path fill="url(#iucMxad)" class="jq4unsb0q"/><g filter="url(#iMEdaPd)"><path class="tdeyyz51e"/></g><g filter="url(#ipzkq1c)"><path fill="url(#i1sQLTc)" class="h2j74rp_e"/><path fill="url(#iJDJPEb)" class="h2j74rp_e"/><path fill="url(#iwUXzkc)" class="h2j74rp_e"/><path fill="url(#iOBcRod)" class="h2j74rp_e"/></g><g filter="url(#iFi7dzc)"><path stroke="url(#ieTk1Qb)" class="hqsxlwb0l"/></g><path fill="url(#ieroGhb)" class="pwea_2rka"/><g filter="url(#iU1XDHb)"><path class="om452db7q"/></g><g filter="url(#iQnBTje)"><path class="gckl5bbdk"/></g><path class="homw601_q"/><path fill="url(#i1AxDpd)" class="c1zlw1bna"/><path class="dhr8kcbtz"/><g filter="url(#im0S2Mf)"><path class="cgekyxbkd"/><path fill="url(#i1KeePd)" class="ngb0izbwy"/></g><g filter="url(#iGyD80b)"><path fill="url(#ifDBt0d)" class="o9vjlcb2u"/></g><path fill="url(#iuksN4c)" class="rcozcsb6t"/><path fill="url(#iUKlnJb)" class="opi_ovbwb"/><path class="dsis1eyuj"/><path fill="url(#inIeGqd)" class="b_qfexbys"/><path class="m5zl3fy4l"/><g filter="url(#iI0qm7A)"><path fill="url(#i0cAjFD)" class="w7tknbcto"/></g><g filter="url(#ibuluTb)"><ellipse transform="rotate(-27.914 12.089 9.742)" class="kkndqfb5c"/><ellipse fill="url(#iqAnHuc)" transform="rotate(-27.914 12.089 9.742)" class="o2hcjzb3o"/></g><path fill="url(#iF1x7dJ)" class="j4jr2cc4k"/><path fill="url(#iGcD2Zy)" class="j4jr2cc4k"/><path fill="url(#iorvBZc)" class="j4jr2cc4k"/><path fill="url(#ihoKWLe)" class="j4jr2cc4k"/><path fill="url(#iki54Le)" class="arvc0y9uw"/><path fill="url(#i9p647b)" class="arvc0y9uw"/><path fill="url(#ioQtflb)" class="arvc0y9uw"/><g filter="url(#iEoQSrj)"><path class="h69uknbpq"/></g><g filter="url(#iMMenYb)"><path fill="url(#iCiBwne)" class="swd336bml"/></g><path fill="url(#iqCH6Ed)" class="gngqkccyp"/><path fill="url(#iuZCJ3d)" class="gngqkccyp"/><path fill="url(#ihrUnoC)" class="gngqkccyp"/><path fill="url(#iRcNyJn)" class="gngqkccyp"/><path fill="url(#i8CiOTc)" class="gngqkccyp"/><g filter="url(#iRBdwyb)"><path clip-rule="evenodd" class="z2dz3ccft"/><path fill="url(#itmimsb)" clip-rule="evenodd" class="s12_7xc-l"/><path fill="url(#iCoV1BQ)" clip-rule="evenodd" class="s12_7xc-l"/></g><g filter="url(#iWiVoXy)"><path fill="url(#i3z1wvd)" class="a8_8ctbdn"/></g><path fill="url(#izZmBlc)" class="a8_8ctbdn"/><path fill="url(#i8IfEiI)" class="a8_8ctbdn"/><path class="eo66f_b5r"/><path fill="url(#iw3N5Jc)" class="u1pnl7bal"/><path fill="url(#i7rwFPl)" class="u1pnl7bal"/><path fill="url(#icO71Oe)" class="u1pnl7bal"/><path fill="url(#iWC8gHe)" class="u1pnl7bal"/><path fill="url(#il65nke)" class="ktui8gb8v"/><path fill="url(#ilBmaie)" class="ktui8gb8v"/><path fill="url(#iag7pFd)" class="ktui8gb8v"/><path fill="url(#i3gaJsD)" class="ktui8gb8v"/><path fill="url(#i0cTBJd)" class="ktui8gb8v"/><path fill="url(#iT1EBab)" class="x8ohsgb6n"/><path fill="url(#iRC0Dwc)" class="x8ohsgb6n"/><path fill="url(#i2LptYd)" class="x8ohsgb6n"/><g filter="url(#ijdXRLe)"><path fill="url(#iOXpCFZ)" class="mn178ybew"/><path fill="url(#iB7VzId)" class="mn178ybew"/></g><g filter="url(#iZkiEoe)"><path fill="url(#iwwSfLc)" class="c2dvdhrzz"/><path fill="url(#isp5ZVu)" class="c2dvdhrzz"/></g><path fill="url(#izKYvEd)" class="c2dvdhrzz"/><path fill="url(#ipcOQEb)" class="c2dvdhrzz"/><g filter="url(#iMir0Td)"><path fill="url(#itUlJFe)" class="mycr6f5xw"/><path fill="url(#i11AMPr)" class="mycr6f5xw"/><path fill="url(#iudjTOe)" class="mycr6f5xw"/></g><g filter="url(#i5HsA0S)"><path fill="url(#iIqCbKe)" class="yo8g-xb4j"/><path fill="url(#i4kA9ue)" class="yo8g-xb4j"/><path fill="url(#i6GG1kb)" class="yo8g-xb4j"/></g><g filter="url(#iOE0X9d)"><path fill="url(#iBnYHyc)" class="m05ju8soj"/></g><g filter="url(#irBE08d)"><path stroke="url(#iKoDLRc)" class="z-5icob1t"/></g><g filter="url(#igHItAc)"><path class="fqpzz1bqg"/></g><defs><radialGradient id="i5XxABb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.542 15.915)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="iTqVWRc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.262 26.226)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iwYYfzk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.606 26.101)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="irvaKOc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.512 23.914)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iEzvdkd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.262 22.695)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="iJefplb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 18.98 16.233)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="itaTVgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.824 29.726)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="idckKib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.567 29.945)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="i8hks0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.074 23.95)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="ipx3ORd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.537 22.945)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="ioYI98F" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 17.355 10.753)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i6ZaNJc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.859 7.673)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iVcjSHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 20 11.528)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="u44sxcbtw"/><stop offset="1" class="rhksyobfb"/></radialGradient><radialGradient id="iifKQde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 8.993 11.812)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iKiZOyb" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.843 11.492)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iBjKXpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 8.993 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="bykkhcb0n"/><stop offset="1" class="qmt1lfg1g"/></radialGradient><radialGradient id="iaGuGFe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 17.35 10.753)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="is8MVOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.5769 -10.3109 0 14.59 4.59)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="p93hnxttz"/><stop offset=".988" class="yj5rken3l"/></radialGradient><radialGradient id="iGsuGjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.452 -13.983 0 14.589 4.582)" gradientUnits="userSpaceOnUse"><stop offset=".961" class="zs8s-9phz"/><stop offset="1" class="oxsr71-dz"/></radialGradient><radialGradient id="if9U41w" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 16.99 9.633)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iqVxoqb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 10.656 -1.089)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="ipXtFoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 9.661 11.138)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iV2zozd" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 8.689 7.752)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="is2h5co" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 14.388 14.825)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iBtvTmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 16.5 5.372)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iucMxad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.25 10.2829 0 14.589 15.972)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="fbhpt0iyz"/><stop offset=".902" class="j2fvg2bzr"/></radialGradient><radialGradient id="ieTk1Qb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 18.691 -4.427)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="gl9j5ld5z"/><stop offset="1" class="b3ziilbku"/></radialGradient><radialGradient id="ieroGhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 14.542 14.293)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i1AxDpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 16.724 9.837)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i1KeePd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 16.496 9.921)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuksN4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.6328 .64063 -.82937 -.81924 9.434 8.19)" gradientUnits="userSpaceOnUse"><stop class="solc8wbap"/><stop offset="1" class="k5sc15tyi"/></radialGradient><radialGradient id="iUKlnJb" cx="0" cy="0" r="1" gradientTransform="matrix(.72458 .08596 -.14246 1.20076 19.622 8.35)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="uokpokbkf"/><stop offset=".715" class="tq1-3z4lm"/></radialGradient><radialGradient id="inIeGqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.36 9.837)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iqAnHuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 12.074 10.056)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGcD2Zy" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 19.16 9.85)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iorvBZc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 19.52 10.396)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ihoKWLe" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 -2.64062 2.41203 .38536 19.684 11.628)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="osv8xjxbj"/><stop offset="1" class="twozr_ehz"/></radialGradient><radialGradient id="i9p647b" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.195 4.897)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="ioQtflb" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -2.69922 3.32696 .03852 9.278 11.597)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="cerichy6k"/><stop offset="1" class="ido4-abht"/></radialGradient><radialGradient id="iqCH6Ed" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.028 7.068)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="ihrUnoC" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.249 7.039)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iRcNyJn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.606 3.07)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="i8CiOTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.793 7.164)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="itmimsb" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.117 16.039)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iCoV1BQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.15 16.04)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="i3z1wvd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.771 11.682)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i8IfEiI" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.953 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iw3N5Jc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.537 27.79)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iWC8gHe" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.777 20.718)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="ilBmaie" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.663 7.147)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iag7pFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.59 8.117)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="i3gaJsD" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.637 9.101)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i0cTBJd" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 21.98 9.008)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iRC0Dwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.921 21.728)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="i2LptYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.542 25.8)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iOXpCFZ" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.445 3.468)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iB7VzId" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.887 7.258)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="isp5ZVu" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .517 19.605)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="izKYvEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.067 16.367)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="ipcOQEb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.746 16.304)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="i11AMPr" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.813 16.92)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="iudjTOe" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.793 19.351)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="iIqCbKe" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.013 15.755)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="i4kA9ue" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.606 22.476)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="i6GG1kb" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.046 12.533)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><linearGradient id="icFSX4d" x1="14.547" x2="14.547" y1="7.945" y2="19.445" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iY6ajVd" x1="14.547" x2="14.547" y1="7.222" y2="10.816" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ihjOAre" x1="7.567" x2="6.449" y1="26.633" y2="26.601" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="i8ABIJc" x1="15.614" x2="15.614" y1="14.998" y2="21.335" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="i7ZuSFd" x1="19.699" x2="15.347" y1="12.439" y2="12.439" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i1sQLTc" x1="14.542" x2="15.397" y1="11.582" y2="11.582" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iJDJPEb" x1="13.469" x2="14.543" y1="11.426" y2="11.486" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iwUXzkc" x1="14.542" x2="14.542" y1="11.981" y2="12.833" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iOBcRod" x1="14.542" x2="14.542" y1="9.733" y2="10.152" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ifDBt0d" x1="17.502" x2="17.188" y1="9.891" y2="10.084" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0cAjFD" x1="13.104" x2="12.79" y1="9.891" y2="10.085" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iF1x7dJ" x1="20.978" x2="19.771" y1="9.918" y2="12.094" gradientUnits="userSpaceOnUse"><stop class="wswqs7s-z"/><stop offset="1" class="cv8rlkbra"/></linearGradient><linearGradient id="iki54Le" x1="8.692" x2="10.15" y1="10.622" y2="10.495" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iCiBwne" x1="19.977" x2="19.544" y1="9.54" y2="11.253" gradientUnits="userSpaceOnUse"><stop class="nfjey8cvn"/><stop offset="1" class="xw_yjab3v"/></linearGradient><linearGradient id="iuZCJ3d" x1="10.606" x2="16.949" y1="6.695" y2="6.695" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="izZmBlc" x1="13.237" x2="13.449" y1="18.07" y2="18.07" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="i7rwFPl" x1="14.552" x2="14.552" y1="30.289" y2="28.695" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="icO71Oe" x1="14.552" x2="14.552" y1="26.145" y2="27.414" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="il65nke" x1="14.542" x2="14.542" y1="6.945" y2="11.726" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iT1EBab" x1="14.542" x2="14.542" y1="19.578" y2="26.148" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iwwSfLc" x1="21.981" x2="18.293" y1="16.727" y2="29.945" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="itUlJFe" x1="19.981" x2="28.168" y1="22.164" y2="18.851" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="iBnYHyc" x1="14.418" x2="14.418" y1="4.193" y2="6.639" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iKoDLRc" x1="18.649" x2="20.152" y1="21.619" y2="16.43" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="iWrwUXl" width="17.197" height="11.9" x="5.948" y="7.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/></filter><filter id="ije14ae" width="11.22" height="12.442" x="9.484" y="4.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2613" result="effect2_innerShadow_4002_2613"/></filter><filter id="iUIgHZl" width="10.97" height="12.542" x="9.479" y="4.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2613" result="effect2_innerShadow_4002_2613"/></filter><filter id="iMEdaPd" width="3.754" height="4.824" x="12.396" y="9.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".5"/></filter><filter id="ipzkq1c" width="2.077" height="3.1" x="13.503" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".05"/></filter><filter id="iFi7dzc" width="3.718" height="1.573" x="12.683" y="13.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".05"/></filter><filter id="iU1XDHb" width="2.339" height="1.19" x="16.131" y="7.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/></filter><filter id="iQnBTje" width="2.339" height="1.176" x="10.875" y="7.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/></filter><filter id="im0S2Mf" width=".787" height=".696" x="15.99" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".05"/></filter><filter id="iGyD80b" width=".891" height=".913" x="16.83" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".1"/></filter><filter id="iI0qm7A" width=".986" height="1.04" x="12.387" y="9.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".1"/></filter><filter id="ibuluTb" width=".913" height=".705" x="11.632" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".05"/></filter><filter id="iEoQSrj" width="1.329" height="2.379" x="8.509" y="9.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".125"/></filter><filter id="iMMenYb" width="1.447" height="2.403" x="19.254" y="9.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".125"/></filter><filter id="iRBdwyb" width="6.88" height="3.666" x="11.117" y="15.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/></filter><filter id="iWiVoXy" width="4.97" height="3.828" x="13.237" y="15.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/></filter><filter id="ijdXRLe" width="5.52" height="4.05" x="11.787" y="2.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2613" result="effect2_innerShadow_4002_2613"/></filter><filter id="iZkiEoe" width="6.94" height="14.221" x="16.537" y="15.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2613" result="effect2_innerShadow_4002_2613"/></filter><filter id="iMir0Td" width="11.012" height="8.855" x="17.82" y="16.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2613" result="effect2_innerShadow_4002_2613"/></filter><filter id="i5HsA0S" width="4.557" height="7.476" x="23.776" y="17.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2613"/></filter><filter id="iOE0X9d" width="2.509" height="3.213" x="13.114" y="3.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2613"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2613" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2613" result="effect3_innerShadow_4002_2613"/></filter><filter id="irBE08d" width="1.83" height="4.718" x="18.051" y="17.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".125"/></filter><filter id="igHItAc" width="2.769" height="7.081" x="18.356" y="23.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2613" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:firefighter-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.a8_8ctbdn {
  d: path("M13.237 16.907v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.017");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.arvc0y9uw {
  d: path("M9.497 8.898a1.614 1.614 0 0 0-1.392 1.59c0 .859.674 1.56 1.521 1.607a78 78 0 0 1-.13-3.197");
}

.b_qfexbys {
  d: path("M12.358 9.36a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.b3ziilbku {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
  stop-opacity: 0;
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.bykkhcb0n {
  stop-color: var(--svg-color--edb388, #EDB388);
}

.c1zlw1bna {
  d: path("M16.726 9.36a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.c2dvdhrzz {
  d: path("m22.596 16.11l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.625");
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cerichy6k {
  stop-color: var(--svg-color--a55f48, #A55F48);
  stop-opacity: 0;
}

.cgekyxbkd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.66 9.549c.064.085-.069.189-.22.301c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cv8rlkbra {
  stop-color: var(--svg-color--dc967b, #DC967B);
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

.dhr8kcbtz {
  fill: var(--svg-color--000, #000);
  d: path("M16.215 10.253a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .454.747h-.904a.46.46 0 0 1-.061-.235");
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqwyzhw7l {
  d: path("M7.567 29.945V17.943a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.dsis1eyuj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.151 9.088c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eo66f_b5r {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.537 26.145H7.567v3.8h13.97z");
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fbhpt0iyz {
  stop-color: var(--svg-color--bb7871, #BB7871);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fqpzz1bqg {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.881 29.601c0-.2 1.146-4.104 1.719-6.03");
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gckl5bbdk {
  fill: var(--svg-color--6c3421, #6C3421);
  d: path("M11.131 7.914a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gl9j5ld5z {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
}

.gngqkccyp {
  d: path("M20.845 7.305H8.25v-.378C8.25 4.193 10.26 2 13.27 2h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h2j74rp_e {
  d: path("m14.16 10.039l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.765 0");
}

.h69uknbpq {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M9.505 9.555a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.homw601_q {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.933 9.088c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.hqsxlwb0l {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.191 13.255a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.203-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.i-vys5vjv {
  d: path("M14.547 15.445c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
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

.ido4-abht {
  stop-color: var(--svg-color--a55f48, #A55F48);
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
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

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j2fvg2bzr {
  stop-color: var(--svg-color--b66751, #B66751);
}

.j4jr2cc4k {
  d: path("M19.464 12.094c.066-1.064.118-2.124.174-3.188c.755.132 1.34.788 1.34 1.582a1.61 1.61 0 0 1-1.514 1.606");
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jq4unsb0q {
  d: path("M9.717 13.518a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.433h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419H12.82c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.jrzio0bwr {
  d: path("M21.537 17.955v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k5sc15tyi {
  stop-color: var(--svg-color--ac7653, #AC7653);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kkndqfb5c {
  cx: 12.089px;
  cy: 9.742px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.ktui8gb8v {
  d: path("M8.618 7.945h11.847c.95 0 1.99.484 1.99 2.68h.69V9.32c0-1.43-.847-2.375-2.456-2.375H8.395c-1.609 0-2.457.945-2.457 2.375v1.305h.692c0-2.196 1.04-2.68 1.988-2.68");
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kwzpxaciw {
  d: path("M9.722 13.518a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.433h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
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

.m05ju8soj {
  d: path("M13.264 4.882c0-.153.183-.23.293-.125l.154.149a.162.162 0 0 0 .275-.117v-.17c0-.345.178-.665.471-.847l.18-.111a.23.23 0 0 1 .35.195V5.05a.17.17 0 0 0 .28.132l.095-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m5zl3fy4l {
  fill: var(--svg-color--000, #000);
  d: path("M12.869 10.253a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mn178ybew {
  d: path("M17.207 6.945h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mycr6f5xw {
  d: path("m19.972 16.704l4.416 1.16a3.57 3.57 0 0 0 2.071-.052l.148-.055c.178-.062.4-.054.554.107c1.072 1.125 1.43 2.622.984 4.236c-.448 1.615-1.733 2.764-2.98 3.034c-.084.02-.348.045-.506-.158l-.141-.14a3.5 3.5 0 0 0-1.745-1.111l-4.243-1.202a.61.61 0 0 1-.431-.78l1.252-4.674c.044-.22.37-.43.621-.365");
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

.nfjey8cvn {
  stop-color: var(--svg-color--ca8a72, #CA8A72);
}

.ngb0izbwy {
  d: path("M16.66 9.549c.064.085-.069.189-.22.301c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o2hcjzb3o {
  cx: 12.089px;
  cy: 9.742px;
  rx: 0.39px;
  ry: 0.197px;
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o9vjlcb2u {
  d: path("M17.52 10.135a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.om452db7q {
  fill: var(--svg-color--6c3421, #6C3421);
  d: path("M18.275 8.023a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 0 0 .067.55c.481-.058.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.opi_ovbwb {
  d: path("M19.645 7.51q.046.172.05.357l-.079 1.606c.233.041.48.138.667.268V8.553c0-.31.096-.616.27-.874a1 1 0 0 0 .093-.168z");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.osv8xjxbj {
  stop-color: var(--svg-color--b46d50, #B46D50);
  stop-opacity: 0;
}

.oxsr71-dz {
  stop-color: var(--svg-color--b2654f, #B2654F);
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.p93hnxttz {
  stop-color: var(--svg-color--d1908b, #D1908B);
  stop-opacity: 0;
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

.pwea_2rka {
  d: path("M14.542 13.65c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qmt1lfg1g {
  stop-color: var(--svg-color--df9e74, #DF9E74);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rcozcsb6t {
  d: path("M8.439 7.52q.037.085.093.168c.172.257.266.563.266.874v1.2c.198-.141.459-.226.708-.263l-.03-1.538q0-.225.028-.442z");
}

.rhksyobfb {
  stop-color: var(--svg-color--e8a77d, #E8A77D);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
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

.s12_7xc-l {
  fill-rule: evenodd;
  d: path("M11.117 16.039v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.879h-1.896c-.942 0-1.813-.33-2.496-.885");
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

.solc8wbap {
  stop-color: var(--svg-color--b68361, #B68361);
}

.swd336bml {
  d: path("M19.504 11.443q.058-.952.11-1.903a.956.956 0 0 1-.11 1.903");
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

.tdeyyz51e {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.111 10.417l-.692 1.656c-.101.378.142.756.487.756h.735c.344 0 .588-.384.486-.756l-.497-1.838c-.106-.408-.407-.225-.519.182");
}

.tq1-3z4lm {
  stop-color: var(--svg-color--b37d58, #B37D58);
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.twozr_ehz {
  stop-color: var(--svg-color--b46d50, #B46D50);
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1pnl7bal {
  d: path("M21.537 26.145H7.567v3.8h13.97z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.u44sxcbtw {
  stop-color: var(--svg-color--ffd5a6, #FFD5A6);
}

.u4vma9bug {
  d: path("M19.403 12.003c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.uk-_dobib {
  d: path("M9.68 12.003a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uokpokbkf {
  stop-color: var(--svg-color--bd8760, #BD8760);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
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

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w7tknbcto {
  d: path("M13.173 10.148c0-.288-.234-.48-.298-.539l-.288.279l.177.361z");
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wswqs7s-z {
  stop-color: var(--svg-color--dba38f, #DBA38F);
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.x8ohsgb6n {
  d: path("M15.127 19.578h-1.17v6.57h1.17z");
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xdpeznbmk {
  d: path("M22.134 7.945H7.112c-.395.32-.78 1.336-1.164 1.656v1.344c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.601c-.354-.42-.687-1.206-1.011-1.656");
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xtob7mb0f {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.547 15.445c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xw_yjab3v {
  stop-color: var(--svg-color--d79a80, #D79A80);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
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

.yj5rken3l {
  stop-color: var(--svg-color--c47473, #C47473);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yo8g-xb4j {
  d: path("M25.609 17.983a3.5 3.5 0 0 0 .85-.172l.148-.054c.178-.062.4-.054.554.107c1.072 1.125 1.43 2.621.984 4.236c-.448 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.142-.14a3.5 3.5 0 0 0-.641-.588c1.567-.053 2.817-1.085 3.203-2.53c.39-1.468-.236-3.003-1.472-3.735z");
}

.yv1wrjbcb {
  d: path("M13.237 15.945v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z-5icob1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.506 17.945l-1.08 3.968");
}

.z2dz3ccft {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.117 16.039v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.879h-1.896c-.942 0-1.813-.33-2.496-.885");
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

.zs8s-9phz {
  stop-color: var(--svg-color--b2654f, #B2654F);
  stop-opacity: 0;
}

</style>
