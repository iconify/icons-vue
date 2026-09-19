<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="j_dulcbnt"/><path fill="url(#iAlKUYw)" class="ng-28zxwb"/><path fill="url(#itbtQzd)" class="ng-28zxwb"/><path fill="url(#iOhOn5b)" class="ng-28zxwb"/><path fill="url(#i8ngfnv)" class="ng-28zxwb"/><path fill="url(#iWXDRFe)" class="ng-28zxwb"/><path class="t9v2librs"/><path fill="url(#imSQI2c)" class="cej917bjj"/><path fill="url(#i4d8iJd)" class="cej917bjj"/><path fill="url(#iHdaBGb)" class="cej917bjj"/><g filter="url(#itHaYEe)"><path class="pn-givnji"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#im8Vkvd)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iWKZSod)" class="by194g1ei"/><path fill="url(#idsRMlc)" class="by194g1ei"/><g filter="url(#i66KoOc)"><path fill="url(#iRjyRMt)" class="hazfh8b2v"/></g><path fill="url(#iollnke)" class="vi7fu79ul"/><path fill="url(#im9eHqM)" class="vi7fu79ul"/><path fill="url(#i4hNkDe)" class="vi7fu79ul"/><path fill="url(#i8KloTQ)" class="agjep-b6f"/><path fill="url(#iMIg2ZO)" class="agjep-b6f"/><path fill="url(#iEpqGnc)" class="agjep-b6f"/><path fill="url(#iHu3LFd)" class="agjep-b6f"/><path fill="url(#iIipaHv)" class="agjep-b6f"/><path class="y411x-6nn"/><path fill="url(#iY8ko2d)" class="wgl1mtbjd"/><path fill="url(#iGkGbCb)" class="wgl1mtbjd"/><path fill="url(#imdlgvc)" class="wgl1mtbjd"/><path fill="url(#ira2lKd)" class="wgl1mtbjd"/><path fill="url(#iknlR1o)" class="wgl1mtbjd"/><g filter="url(#iFydGfe)"><path fill="url(#i2SCZzd)" class="jg8e9blws"/><path fill="url(#iotqXAe)" class="jg8e9blws"/></g><g filter="url(#iv9e7fd)"><path fill="url(#iimzjsu)" class="irpqnktdz"/><path fill="url(#iv8hTQc)" class="irpqnktdz"/><path fill="url(#iMAGDRc)" class="irpqnktdz"/><path fill="url(#i2jMWwb)" class="irpqnktdz"/><path fill="url(#irOFmTd)" class="irpqnktdz"/></g><g filter="url(#imp8dNc)"><path fill="url(#i1VflDU)" class="my_84zz7a"/><path fill="url(#iEAfnnc)" class="my_84zz7a"/><path fill="url(#isUiL6c)" class="my_84zz7a"/><path fill="url(#iVjF54c)" class="my_84zz7a"/></g><g filter="url(#iwEL1Eb)"><path fill="url(#i8gh6Fe)" class="u29lq70aj"/></g><path fill="url(#iXGLOGd)" class="qy2xrui7g"/><path fill="url(#iejYbrc)" class="qy2xrui7g"/><rect fill="url(#iGFxt3d)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#irFYPtc)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#iz1ecHe)"><path fill="url(#irI5LDd)" clip-rule="evenodd" class="hx_wmlsuf"/></g><rect fill="url(#ihSbEiX)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#i3bwMYc)"><path fill="url(#iroLFre)" class="dcjhnibya"/><path fill="url(#i4p48ob)" class="dcjhnibya"/><path fill="url(#iZmJ6cd)" class="dcjhnibya"/><path fill="url(#iMY7ere)" class="dcjhnibya"/><path fill="url(#iO1rLsd)" class="dcjhnibya"/></g><g filter="url(#iZwXIie)"><path stroke="url(#iXiyPSb)" class="fkavrburz"/></g><g filter="url(#iyv564d)"><path stroke="url(#iEmyyOd)" class="tnviirb6b"/></g><g filter="url(#ignQyic)"><path stroke="url(#i5CGbMd)" class="bc7i0ongh"/></g><path fill="url(#iJqLyBQ)" class="yooezabeg"/><path fill="url(#iOAUFHe)" class="aso7y9t3a"/><g filter="url(#ihR4lfe)"><path fill="url(#iAT6K2d)" class="h82gmvb7d"/></g><path fill="url(#iTxZWHb)" class="h82gmvb7d"/><path fill="url(#iB60qyc)" class="h82gmvb7d"/><path fill="url(#i8t3Aid)" class="h82gmvb7d"/><path fill="url(#iOZA9Sc)" class="h82gmvb7d"/><path fill="url(#inEEXmb)" class="h82gmvb7d"/><path fill="url(#ioo8Kse)" class="h82gmvb7d"/><path fill="url(#iIjOkzc)" class="h82gmvb7d"/><path fill="url(#iTH15SF)" class="h82gmvb7d"/><path fill="url(#iT7ss5X)" class="h82gmvb7d"/><path fill="url(#isnK1md)" class="h82gmvb7d"/><path fill="url(#iBzze8c)" class="h82gmvb7d"/><path fill="url(#iKIthSc)" class="h82gmvb7d"/><g filter="url(#iajKHqe)"><path class="dufkwykiq"/></g><g filter="url(#iSEE6Bb)"><path class="ly8_6p2-a"/><path fill="url(#iQpFd5d)" class="cxp_ozbgz"/><path fill="url(#ix6Z2nd)" class="cxp_ozbgz"/><path fill="url(#ifOI0Id)" class="cxp_ozbgz"/><path fill="url(#i1XCyie)" class="cxp_ozbgz"/><path fill="url(#iVks1rd)" class="cxp_ozbgz"/></g><g filter="url(#iBtlsVb)"><path fill="url(#injssUc)" class="rf-597aio"/></g><g filter="url(#iOdhLSd)"><path stroke="url(#ivYcmgn)" class="a2ahyy3ac"/></g><path fill="url(#iQWYvOb)" class="wbyalobvj"/><path class="sdjzlvbcx"/><path fill="url(#iW6lzze)" class="bao3x4ksh"/><path class="w99r55b4z"/><g filter="url(#imhtiwd)"><path class="n4gtx789p"/><path fill="url(#iZASrWd)" class="tvf5vim8r"/></g><g filter="url(#ivQF9Eb)"><path fill="url(#ix6voEd)" class="fzuuphmhb"/></g><path class="zc4o1ibpk"/><path fill="url(#ipwtEPd)" class="zjsacebfn"/><path class="davo8hbwp"/><g filter="url(#i2KYKCc)"><path fill="url(#ieu1eIb)" class="euaooqlxy"/></g><g filter="url(#icsM9Ie)"><ellipse transform="rotate(-27.914 12.127 11.994)" class="tb-tcdaqs"/><ellipse fill="url(#icDi2bd)" transform="rotate(-27.914 12.127 11.994)" class="gdzfyikkh"/></g><path fill="url(#ijU5rWc)" class="fn22o4byw"/><path fill="url(#il05T7d)" class="fn22o4byw"/><path fill="url(#ia7I2cb)" class="fn22o4byw"/><path fill="url(#iHysmzZ)" class="fn22o4byw"/><path fill="url(#iJJ4jce)" class="eyaitxboh"/><path fill="url(#iGgzKhb)" class="eyaitxboh"/><g filter="url(#ia4cFzb)"><path fill="url(#iy0LfCb)" class="k9_2cabme"/></g><g filter="url(#i1fcMNe)"><path fill="url(#iShqLDD)" class="paktu1bpf"/></g><path fill="url(#iBfj5Pd)" class="u29lq70aj"/><path fill="url(#ieAjMmb)" class="u29lq70aj"/><g filter="url(#ieFVIbb)"><path fill="url(#iodu1md)" class="jsq1u4rsj"/></g><path fill="url(#iQFwsnd)" class="wjttd5b7m"/><path fill="url(#iAJlZRd)" class="wjttd5b7m"/><path fill="url(#iLKj4pc)" class="wjttd5b7m"/><path fill="url(#iUdJvBb)" class="wjttd5b7m"/><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="i8ngfnv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.157)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="iWXDRFe" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.417 66.252)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="i4d8iJd" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .523 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iHdaBGb" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.884)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="im8Vkvd" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.545 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iWKZSod" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.47)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="idsRMlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.921)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iRjyRMt" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.654)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iollnke" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.781)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i8KloTQ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.969)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iIipaHv" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.05 20.861)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iY8ko2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.469)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="imdlgvc" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.371 20.582)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="i2SCZzd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.302 1.29944 -.6979 -1.23635 16.779 20.349)" gradientUnits="userSpaceOnUse"><stop class="ap133vb3r"/><stop offset="1" class="rryre-agq"/></radialGradient><radialGradient id="iotqXAe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5045 .1671 -.03048 -.45688 14.29 19.958)" gradientUnits="userSpaceOnUse"><stop class="v6yinkbrb"/><stop offset="1" class="lit-3eb_c"/></radialGradient><radialGradient id="iMAGDRc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.283)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="irOFmTd" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.253)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iVjF54c" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.983)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iXGLOGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84252 1.83738 -2.2703 -2.27664 28.357 22.616)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iejYbrc" cx="0" cy="0" r="1" gradientTransform="matrix(.8321 -.63357 .33086 .43454 28.001 22.853)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="ihSbEiX" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.119)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="i4p48ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iZmJ6cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iMY7ere" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iO1rLsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iJqLyBQ" cx="0" cy="0" r="1" gradientTransform="matrix(.83142 2.24244 -2.66385 .98767 20.13 14.163)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iOAUFHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.63943 .51524 -1.58956 5.05775 8.126 14.707)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iAT6K2d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.80487 0 0 -10.2688 17.969 13.118)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iB60qyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13506 13.79478 -11.4237 -.93996 16.607 6.551)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i8t3Aid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2751 1.57793 0 17.569 11.66)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iOZA9Sc" cx="0" cy="0" r="1" gradientTransform="matrix(.00436 -1.21506 1.32227 .00475 12.297 11.711)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="inEEXmb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.43372 .5955 -1.52121 -24.09843 18.663 14.215)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="ioo8Kse" cx="0" cy="0" r="1" gradientTransform="matrix(4.52255 -2.9406 1.07646 1.65557 8.78 8.315)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iIjOkzc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.007 14.502)scale(2.7853 1.1134)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iTH15SF" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.633 8.742)scale(3.74083 3.08836)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="isnK1md" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.95469 -6.12262 0 14.903 10.55)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="fji22nf_n"/><stop offset="1" class="yesv-cbgi"/></radialGradient><radialGradient id="iBzze8c" cx="0" cy="0" r="1" gradientTransform="rotate(-78.198 18.93 1.982)scale(1.06948 3.3073)" gradientUnits="userSpaceOnUse"><stop offset=".299" class="f198r_bwl"/><stop offset="1" class="k1gnwflea"/></radialGradient><radialGradient id="iKIthSc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.81 16.597 3.53)scale(1.75592 5.43005)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="f198r_bwl"/><stop offset="1" class="k1gnwflea"/></radialGradient><radialGradient id="ix6Z2nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .27105 -.85186 0 15.37 14.628)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="i1XCyie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68904 .7744 -1.24454 -2.71442 15.498 13.996)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iQWYvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.80029 3.21976 0 14.851 17.048)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iW6lzze" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90087 -1.43293 0 17.274 12.1)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="iZASrWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25752 -.33184 .45687 -.35454 17.02 12.194)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipwtEPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90091 -1.43301 0 12.429 12.1)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="t_blaotnz"/><stop offset="1" class="e-5wyxbvo"/></radialGradient><radialGradient id="icDi2bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00859 -.54862 .65946 -.01033 12.11 12.344)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="il05T7d" cx="0" cy="0" r="1" gradientTransform="matrix(.6979 2.49088 -2.3765 .66585 19.977 12.116)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ia7I2cb" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 22.694 -13.672)scale(1.48533 1.245)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iHysmzZ" cx="0" cy="0" r="1" gradientTransform="matrix(.65179 -1.72155 2.30023 .87088 20.506 12.912)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iGgzKhb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.544 9.847)scale(2.35031 2.31057)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iy0LfCb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01764 .17468 -.07704 -.44883 9.394 12.83)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iQFwsnd" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.609)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><linearGradient id="iOhOn5b" x1="6.988" x2="7.195" y1="29.407" y2="29.407" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="imSQI2c" x1="16.932" x2="14.847" y1="28.545" y2="28.119" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="i4hNkDe" x1="16.414" x2="15.153" y1="29.069" y2="29.122" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="iMIg2ZO" x1="11.675" x2="12.612" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iGkGbCb" x1="18.074" x2="17.137" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iimzjsu" x1="12.219" x2="9.392" y1="26.17" y2="26.807" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iv8hTQc" x1="9.392" x2="11.086" y1="16.977" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="i2jMWwb" x1="12.268" x2="12.268" y1="29.922" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="i1VflDU" x1="18.023" x2="21.304" y1="29.125" y2="16.977" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iEAfnnc" x1="17" x2="17.152" y1="26.539" y2="26.571" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iGFxt3d" x1="26.981" x2="24.992" y1="21.781" y2="21.781" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="irI5LDd" x1="28.179" x2="23.367" y1="14.344" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="iroLFre" x1="27.914" x2="23.132" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iXiyPSb" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iEmyyOd" x1="23.614" x2="25.48" y1="27.034" y2="27.034" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i5CGbMd" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iTxZWHb" x1="20.578" x2="15.745" y1="14.989" y2="14.989" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iT7ss5X" x1="14.904" x2="14.904" y1="20.06" y2="19.349" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iQpFd5d" x1="15.894" x2="15.207" y1="13.841" y2="13.937" gradientUnits="userSpaceOnUse"><stop class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ifOI0Id" x1="14.851" x2="14.851" y1="15.132" y2="14.616" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iVks1rd" x1="14.851" x2="14.851" y1="11.851" y2="12.735" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="injssUc" x1="14.851" x2="14.993" y1="11.847" y2="13.054" gradientUnits="userSpaceOnUse"><stop offset=".114" class="oeyfdqnea"/><stop offset="1" class="w447cccda"/></linearGradient><linearGradient id="ivYcmgn" x1="13.517" x2="13.87" y1="16.876" y2="15.95" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="ix6voEd" x1="18.138" x2="17.79" y1="12.16" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieu1eIb" x1="13.254" x2="12.906" y1="12.16" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijU5rWc" x1="21.998" x2="20.658" y1="12.19" y2="14.607" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iJJ4jce" x1="8.356" x2="9.975" y1="12.972" y2="12.83" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iShqLDD" x1="20.865" x2="20.865" y1="11.766" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iUdJvBb" x1="15.508" x2="15.508" y1="5.848" y2="5.984" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="itHaYEe" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".25"/></filter><filter id="i66KoOc" width="3.106" height="2.966" x="13.406" y="21.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="iFydGfe" width="4.5" height="2.352" x="12.625" y="19.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.0666667 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="iv9e7fd" width="8.299" height="13.046" x="5.293" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="imp8dNc" width="8.299" height="13.046" x="16.154" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="iwEL1Eb" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="irFYPtc" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".125"/></filter><filter id="iz1ecHe" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="i3bwMYc" width="5.277" height="6.052" x="23.132" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/></filter><filter id="iZwXIie" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".05"/></filter><filter id="iyv564d" width="2.262" height=".3" x="23.464" y="26.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".05"/></filter><filter id="ignQyic" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".05"/></filter><filter id="ihR4lfe" width="12.348" height="13.904" x="9.229" y="6.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2750" result="effect2_innerShadow_4002_2750"/></filter><filter id="iajKHqe" width="3.94" height="5.22" x="12.724" y="11.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".5"/></filter><filter id="iSEE6Bb" width="2.484" height="3.62" x="13.609" y="11.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".1"/></filter><filter id="iBtlsVb" width="2.484" height="3.62" x="13.609" y="11.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".1"/></filter><filter id="iOdhLSd" width="4.074" height="1.691" x="12.814" y="15.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".05"/></filter><filter id="imhtiwd" width=".852" height=".751" x="16.47" y="11.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".05"/></filter><filter id="ivQF9Eb" width=".945" height=".97" x="17.414" y="11.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".1"/></filter><filter id="i2KYKCc" width="1.051" height="1.111" x="12.48" y="11.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".1"/></filter><filter id="icsM9Ie" width=".992" height=".76" x="11.631" y="11.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".05"/></filter><filter id="ia4cFzb" width="1.42" height="2.587" x="8.127" y="11.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".125"/></filter><filter id="i1fcMNe" width="2.051" height="3.113" x="19.84" y="11.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2750" stdDeviation=".25"/></filter><filter id="ieFVIbb" width="19.912" height="4.003" x="4.916" y="7.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2750" result="effect2_innerShadow_4002_2750"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:detective-dark" /></template>
<style>
.a2ahyy3ac {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.348 15.903c.434.226.951.356 1.503.356c.558 0 1.07-.13 1.504-.356a.245.245 0 0 1 .291.047a.23.23 0 0 1 .026.293l-.063-.041a2.1 2.1 0 0 1-1.758.939a2.1 2.1 0 0 1-1.758-.94zm0 0h-.001a.245.245 0 0 0-.291.05a.23.23 0 0 0-.025.29z");
}

.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.agjep-b6f {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.78c-.097.084-.327.215-.477.071s-.357-.504-.475-1.015");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.ap133vb3r {
  stop-color: var(--svg-color--473739, #473739);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.aso7y9t3a {
  d: path("M9.454 14.506a1.8 1.8 0 0 1-1.005-.343v1.034c0 .992.591 1.875 1.49 2.242a4.5 4.5 0 0 1-.385-1.31z");
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bao3x4ksh {
  d: path("M17.277 11.57a.99.99 0 0 1 .954 1.253h-1.914a.995.995 0 0 1 .96-1.252");
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

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
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

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
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

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.cej917bjj {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
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

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.cxp_ozbgz {
  d: path("m14.427 12.324l-.59 2.041c-.12.42.168.84.578.84h.873c.41 0 .698-.426.578-.84l-.59-2.041c-.127-.452-.717-.452-.85 0");
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.davo8hbwp {
  fill: var(--svg-color--000, #000);
  d: path("M12.994 12.562a.565.565 0 0 0-.568-.568a.565.565 0 0 0-.504.829h1.004a.56.56 0 0 0 .068-.261");
}

.dcjhnibya {
  d: path("M23.132 24.819c0-.438.355-.799.793-.799h3.023c.724 0 1.31.587 1.31 1.31v3.5c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.435a.8.8 0 0 1-.444-.717");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dufkwykiq {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.406 12.542l-.656 2.041c-.113.42.156.84.537.84h.813c.38 0 .65-.427.538-.84l-.55-2.041c-.117-.452-.56-.452-.682 0");
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e-5wyxbvo {
  stop-color: var(--svg-color--52342d, #52342D);
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.euaooqlxy {
  d: path("M13.332 12.445c0-.32-.26-.533-.331-.598l-.32.31l.197.401z");
}

.eyaitxboh {
  d: path("M9.24 11.054a1.787 1.787 0 0 0 .153 3.553a87 87 0 0 1-.154-3.553");
}

.f198r_bwl {
  stop-color: var(--svg-color--4a3d45, #4A3D45);
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fji22nf_n {
  stop-color: var(--svg-color--2c1922, #2C1922);
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

.fn22o4byw {
  d: path("M20.317 14.607q.111-1.772.204-3.544a1.787 1.787 0 0 1-.204 3.544");
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

.fzuuphmhb {
  d: path("M18.16 12.431a.93.93 0 0 0-.258-.513l-.288.316l.13.254z");
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gdzfyikkh {
  cx: 12.127px;
  cy: 11.994px;
  rx: 0.433px;
  ry: 0.219px;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h82gmvb7d {
  d: path("M9.494 16.188a4.35 4.35 0 0 0 4.315 3.782h2.094a4.35 4.35 0 0 0 4.315-3.782c.13-2.092.263-4.175.36-6.266a1.61 1.61 0 0 0-1.531-1.59h-1.555a2.69 2.69 0 0 1-2.456-1.602a.74.74 0 0 0-.683-.464H12.94c-2.05 0-3.71 1.68-3.71 3.752c0 2.066.128 4.098.264 6.17");
}

.hazfh8b2v {
  d: path("m14.098 24.349l-.692-1.333l1.453-1.352l1.453 1.352l-.662 1.33a.15.15 0 0 1-.134.084h-1.285a.15.15 0 0 1-.133-.081");
}

.hx_wmlsuf {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.594a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.97");
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.irpqnktdz {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1566 1566 0 0 1-4.625-7.734c-.422-.735-.219-.906-.14-1.031s.375-.36.671-.47c.238-.087.329-.202.344-.25c.057-.067.069-.3-.344-.687c-.412-.387-1.307-1.067-1.703-1.36c-.234-.187-.651-.608-.601-.983s.65-.435.765-.43z");
}

.j_dulcbnt {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.jg8e9blws {
  d: path("M12.625 19.547c.026.291.262.987.999 1.437c.736.45 1.14.63 1.25.664c.11-.033.515-.214 1.252-.664c.736-.45.973-1.146.999-1.437z");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsq1u4rsj {
  d: path("M6.386 7.879c-.26-.016-.991.034-1.316.36c-.357.357-.055 1.073.508 1.652c.539.554 2.335 1.738 5.18 1.738h8.167c2.874 0 4.689-1.184 5.234-1.738c.568-.58.874-1.295.513-1.653c-.328-.325-1.067-.375-1.33-.359z");
}

.k1gnwflea {
  stop-color: var(--svg-color--4a3d45, #4A3D45);
  stop-opacity: 0;
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
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

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k9_2cabme {
  d: path("M9.205 11.787a1.061 1.061 0 0 0 .092 2.087a87 87 0 0 1-.092-2.087");
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
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

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
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

.lit-3eb_c {
  stop-color: var(--svg-color--372138, #372138);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.ly8_6p2-a {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.427 12.324l-.59 2.041c-.12.42.168.84.578.84h.873c.41 0 .698-.426.578-.84l-.59-2.041c-.127-.452-.717-.452-.85 0");
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
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

.n4gtx789p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.204 11.78c.07.095-.077.21-.245.335s-.292.214-.363.12c-.07-.095.008-.273.176-.399c.168-.125.361-.15.432-.056");
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.ng-28zxwb {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
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

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeyfdqnea {
  stop-color: var(--svg-color--311d25, #311D25);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.paktu1bpf {
  d: path("M20.34 13.88q.064-1.058.123-2.114a1.061 1.061 0 0 1-.123 2.114");
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn-givnji {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.702 19.668l.69 3.215c.1.437.277.745.406.868c.128.123.325.011.407-.06l1.67-1.516l1.669 1.516c.082.072.28.183.408.06s.299-.414.4-.852l.696-3.232h-1.584l-1.59 2.116l-1.588-2.116z");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qy2xrui7g {
  d: path("M27.203 22.328c.58 0 1.055.475 1.055 1.056V25.8h-2.111v-2.417c.01-.58.475-1.056 1.056-1.056");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rf-597aio {
  d: path("m14.427 12.186l-.59 2.042c-.12.42.168.84.578.84h.873c.41 0 .698-.427.578-.84l-.59-2.042c-.127-.452-.717-.452-.85 0");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rryre-agq {
  stop-color: var(--svg-color--331a20, #331A20);
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sdjzlvbcx {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.506 11.269c.725 0 1.338.5 1.505 1.176c.05.193-.1.378-.298.378h-2.477a.256.256 0 0 1-.252-.302a1.55 1.55 0 0 1 1.522-1.252");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t_blaotnz {
  stop-color: var(--svg-color--67433f, #67433F);
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t9v2librs {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
}

.tb-tcdaqs {
  cx: 12.127px;
  cy: 11.994px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.433px;
  ry: 0.219px;
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

.tnviirb6b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.956h1.962");
}

.tvf5vim8r {
  d: path("M17.204 11.78c.07.095-.077.21-.245.335s-.292.214-.363.12c-.07-.095.008-.273.176-.399c.168-.125.361-.15.432-.056");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u29lq70aj {
  d: path("M8.804 5.743a.1.1 0 0 0 .094.132h11.92a.1.1 0 0 0 .094-.133a86 86 0 0 0-.639-1.789c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567q-.103.067-.194.12c-.578.344-.808.4-1.277.4c-.37 0-.761-.15-1.183-.368a5 5 0 0 1-.248-.142c-.436-.26-1.078-.642-1.905-.526c-.956.134-1.66.93-2.097 1.945a29 29 0 0 0-.618 1.669");
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v6yinkbrb {
  stop-color: var(--svg-color--372138, #372138);
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vi7fu79ul {
  d: path("m13.289 29.922l.854-5.408a.1.1 0 0 1 .098-.084h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w447cccda {
  stop-color: var(--svg-color--311d25, #311D25);
  stop-opacity: 0;
}

.w99r55b4z {
  fill: var(--svg-color--000, #000);
  d: path("M16.709 12.562c0-.316.252-.568.568-.568a.565.565 0 0 1 .504.829h-1.004a.5.5 0 0 1-.068-.261");
}

.wbyalobvj {
  d: path("M14.851 16.334a3.34 3.34 0 0 1-1.538-.365c-.152-.077-.316.094-.22.232c.372.564 1.02.94 1.758.94s1.386-.376 1.758-.94c.096-.143-.067-.309-.22-.232a3.3 3.3 0 0 1-1.538.365");
}

.wgl1mtbjd {
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.78c.097.084.327.215.477.071s.35-.484.467-.996");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wjttd5b7m {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.13h13.287a.1.1 0 0 0 .094-.132l-.192-.559l-.429-1.245a.1.1 0 0 0-.094-.067H8.829a.1.1 0 0 0-.094.067c-.19.554-.38 1.12-.532 1.575z");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.y411x-6nn {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.78c.097.084.327.215.477.071s.35-.484.467-.996");
}

.yesv-cbgi {
  stop-color: var(--svg-color--2c1922, #2C1922);
  stop-opacity: 0;
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yooezabeg {
  d: path("M20.25 14.506c.372-.012.72-.139 1.004-.343v1.034c0 .992-.591 1.875-1.49 2.242q.286-.606.385-1.31z");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.zc4o1ibpk {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.197 11.269c-.726 0-1.338.5-1.505 1.176c-.05.193.1.378.297.378h2.478a.256.256 0 0 0 .252-.302a1.556 1.556 0 0 0-1.522-1.252");
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zjsacebfn {
  d: path("M12.426 11.57a.99.99 0 0 0-.955 1.253h1.915q.035-.127.036-.261a1 1 0 0 0-.996-.991");
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
