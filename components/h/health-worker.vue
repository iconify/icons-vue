<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#in4FIrv)" class="yqh8f3bfu"/><path fill="url(#iK5ngOv)" class="yqh8f3bfu"/><path fill="url(#iRn9jyb)" class="yqh8f3bfu"/><path fill="url(#ilFG9fb)" class="yqh8f3bfu"/><path fill="url(#idGklue)" class="yqh8f3bfu"/><path fill="url(#iF7aCda)" class="yqh8f3bfu"/><path fill="url(#iHuMeHe)" class="yqh8f3bfu"/><path fill="url(#iav82fd)" class="cshvfv4mr"/><path fill="url(#iLUzYLb)" class="l719ofbil"/><path fill="url(#iXobMCu)" class="a2af2gsoe"/><path fill="url(#iMc3z6c)" class="a2af2gsoe"/><path fill="url(#iHGqNFb)" class="a2af2gsoe"/><path fill="url(#iprhsVi)" class="ckpq6cbbz"/><path fill="url(#iMbJPab)" class="ckpq6cbbz"/><path fill="url(#inMk86b)" class="ckpq6cbbz"/><path fill="url(#ilRP94d)" class="r2g2v5bav"/><path fill="url(#iDI67vd)" class="r2g2v5bav"/><path fill="url(#iav82fd)" class="cshvfv4mr"/><path fill="url(#iLUzYLb)" class="l719ofbil"/><g filter="url(#iUlXhBd)"><path class="fcsf_zb4h"/></g><g filter="url(#i9nXdme)"><path fill="url(#iAU2rKb)" class="cr4vpibfc"/></g><path fill="url(#iHgozhd)" class="v6mol8i_w"/><path fill="url(#i192yee)" class="v6mol8i_w"/><path fill="url(#i2TSoXc)" class="v6mol8i_w"/><path fill="url(#iiEZLNe)" class="v6mol8i_w"/><path fill="url(#iV4dDBe)" class="v6mol8i_w"/><path fill="url(#imYZewc)" class="v6mol8i_w"/><path fill="url(#i4RwDmc)" class="byzf41gac"/><path fill="url(#i5eVWFb)" class="byzf41gac"/><path fill="url(#ibDlFkd)" class="byzf41gac"/><path fill="url(#ixDTyrW)" class="byzf41gac"/><path fill="url(#iil0oDn)" class="byzf41gac"/><path fill="url(#i4YxDxc)" class="byzf41gac"/><path fill="url(#ipy9kMc)" class="njxg2tppx"/><path clip-rule="evenodd" class="y2m71f9gw"/><path fill="url(#iS5RSRd)" clip-rule="evenodd" class="ruqg683_m"/><path fill="url(#iOhDGEe)" clip-rule="evenodd" class="ruqg683_m"/><path fill="url(#iJzuHCe)" clip-rule="evenodd" class="ruqg683_m"/><path fill="url(#iNC6UFb)" clip-rule="evenodd" class="ruqg683_m"/><g filter="url(#irFGrRc)"><path class="xh3px69yj"/></g><path fill="url(#ix2qOSb)" class="shqkb3bgz"/><g filter="url(#iWv7MXd)"><path fill="url(#ixfCZNc)" class="npms2-bys"/></g><g filter="url(#iw8LgWc)"><path fill="url(#i9WhBNb)" clip-rule="evenodd" class="iss-_bcft"/></g><g filter="url(#i8FFG6d)"><path class="o7b3grg3h"/></g><path fill="url(#iHmDWXC)" clip-rule="evenodd" class="cfv3vkbbo"/><path fill="url(#i1fCtBb)" clip-rule="evenodd" class="cfv3vkbbo"/><path fill="url(#iyaJxyd)" clip-rule="evenodd" class="yf3js1r3y"/><path fill="url(#isAjnye)" clip-rule="evenodd" class="yf3js1r3y"/><path fill="url(#i1r86ie)" class="xaa8swm1e"/><path fill="url(#iM6EbJc)" class="xaa8swm1e"/><path fill="url(#iuILYnb)" class="l-4_4pb_k"/><path fill="url(#ibfzXfx)" class="l-4_4pb_k"/><g filter="url(#ijYtQiN)"><path fill="url(#iBqHTse)" class="r9ptygktb"/></g><path fill="url(#ik9tggH)" class="r9ptygktb"/><path fill="url(#isgh8dc)" class="r9ptygktb"/><path fill="url(#inHuM5d)" class="r9ptygktb"/><path fill="url(#iIGdbgb)" class="r9ptygktb"/><g filter="url(#ibOvNgb)"><path class="eo2zg9b5q"/></g><g filter="url(#ieXXx9d)"><path fill="url(#iXRqbGX)" class="pkncdnbsd"/><path fill="url(#iZYsZad)" class="pkncdnbsd"/><path fill="url(#iAGZ6bc)" class="pkncdnbsd"/><path fill="url(#i3QDGHb)" class="pkncdnbsd"/></g><g filter="url(#i4wEUFd)"><path stroke="url(#iKg8Wzb)" class="v3s_tvltw"/></g><path fill="url(#iJkLKIe)" class="v2l31obiy"/><g filter="url(#ibUdN1c)"><path fill="url(#i6SOmSc)" class="n1130ub2h"/><path fill="url(#iYLkN1H)" class="n1130ub2h"/><path fill="url(#i5hMK1b)" class="n1130ub2h"/><path fill="url(#izGUuub)" class="n1130ub2h"/><path fill="url(#iJZ8y7p)" class="n1130ub2h"/></g><g filter="url(#itcAlMe)"><path class="a13z79b3g"/></g><g filter="url(#icfyRAi)"><path class="btdcctb-s"/></g><g filter="url(#i99r43c)"><path fill="url(#iYrlVHE)" class="rf0snvbcb"/><path fill="url(#iW1IRcL)" class="rf0snvbcb"/></g><g filter="url(#idnMqPb)"><path fill="url(#iZW068b)" class="e1yw_lhor"/><path fill="url(#iHgGX9b)" class="e1yw_lhor"/><path fill="url(#iW9PYLl)" class="e1yw_lhor"/><path fill="url(#iMzlUwc)" class="e1yw_lhor"/><path fill="url(#iWf7a6d)" class="e1yw_lhor"/></g><path class="c0_uynzww"/><path fill="url(#ijsCGZd)" class="icxn-4bej"/><path class="uptr03y8u"/><g filter="url(#iiE95Rc)"><path class="rhd6ajb5p"/><path fill="url(#iqGeKDb)" class="hzlf5p9pl"/></g><g filter="url(#iWgZkKX)"><path fill="url(#inGj5Wc)" class="bxktz0b-e"/></g><path class="hzk_cze2a"/><path fill="url(#isPhjbi)" class="z1zmjebmz"/><path class="a7cr10tok"/><g filter="url(#iYtpmrp)"><path fill="url(#iVFMLLb)" class="wbl1mv4if"/></g><g filter="url(#ir19s9h)"><ellipse transform="rotate(-27.914 13.387 10.065)" class="bbb6nqbkj"/><ellipse fill="url(#i0jRl2Z)" transform="rotate(-27.914 13.387 10.065)" class="m3hs70bsg"/></g><path fill="url(#inTz5fc)" class="b7j9q7t_h"/><path fill="url(#iLSRdUV)" class="b7j9q7t_h"/><path fill="url(#iP3fbye)" class="b7j9q7t_h"/><path fill="url(#iehpFQw)" class="t-bhx2bra"/><path fill="url(#ibXADkb)" class="t-bhx2bra"/><g filter="url(#iPmadOd)"><path class="nhk9aqb2a"/></g><g filter="url(#iqnjMlN)"><path class="pv_89yvsa"/></g><g filter="url(#iISS1Uc)"><path class="o89gwcc-h"/></g><g filter="url(#iB5hLOc)"><path class="ijica1bxp"/></g><defs><radialGradient id="in4FIrv" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.05 24.058)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="idGklue" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.12 8.287)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iF7aCda" cx="0" cy="0" r="1" gradientTransform="matrix(.81252 3.5625 -3.94168 .899 17.906 24.62)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iHuMeHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.821 30.127)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iXobMCu" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.187 24.84)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iMc3z6c" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.832 12.346)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iprhsVi" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.086 22.09)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iMbJPab" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.398 20.465)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="ilRP94d" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 15.855 18.683)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="pmel6eb9u"/><stop offset="1" class="ahs4l-bul"/></radialGradient><radialGradient id="iDI67vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.219 30.62)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rz95hov5a"/><stop offset="1" class="pwmvjmb6w"/></radialGradient><radialGradient id="iiEZLNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 18.994 18.246)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iV4dDBe" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.302 26.688)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="imYZewc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 18.994 24.996)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="i4RwDmc" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.295 11.33)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="i5eVWFb" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 9.985 25.05)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="ixDTyrW" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.156 19.622)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iil0oDn" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 11.953 18.45)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="i4YxDxc" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.242 24.132)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="ipy9kMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72628 3.2225 0 15.84 18.847)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="uwu4h0bpr"/><stop offset=".577" class="cd6o9mbpd"/><stop offset="1" class="gqtxsdait"/></radialGradient><radialGradient id="iOhDGEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.36 16.512)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="iJzuHCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.437 20.168)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iNC6UFb" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.705 12.214)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="ix2qOSb" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.046 18.09)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="ixfCZNc" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.103 26.035)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="i1fCtBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 9.985 23.7)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="i1r86ie" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 5.929 14.49)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iM6EbJc" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.76 26.442)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iuILYnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.291 12.135)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="ibfzXfx" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.824 13.562)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iBqHTse" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.648 11.077)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="ik9tggH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.38582 13.1712 0 15.646 17.412)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="isgh8dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 20.997 10.845)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="inHuM5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.748 9.896)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iIGdbgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.329 9.485)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iKg8Wzb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.616 -5.373)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iJkLKIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.84 14.616)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iYLkN1H" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.61 9.495)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="i5hMK1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.7 9.495)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="izGUuub" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 19.946 3.218)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iJZ8y7p" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 14.935 1.626)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iYrlVHE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 16.093 3.068)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iW1IRcL" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 10.41 7.828)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iZW068b" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -8.395 85.526)scale(3.4792 1.94581)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iHgGX9b" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.028 -1.622)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iW9PYLl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.603 -1.526)scale(2.56111 1.83441)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iMzlUwc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.634 4.112)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iWf7a6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.293 3.987)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ijsCGZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.022 10.16)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iqGeKDb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.406 .765)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isPhjbi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.658 10.16)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i0jRl2Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.371 10.38)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLSRdUV" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.457 10.174)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iP3fbye" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.818 10.719)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ibXADkb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.045 9.511)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><linearGradient id="iK5ngOv" x1="23.164" x2="22.852" y1="24.738" y2="24.738" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iRn9jyb" x1="8.586" x2="8.922" y1="24.738" y2="24.738" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="ilFG9fb" x1="16.031" x2="16.031" y1="31.09" y2="29.277" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iav82fd" x1="8.67" x2="23.046" y1="15.567" y2="15.567" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iLUzYLb" x1="8.67" x2="23.046" y1="15.536" y2="15.536" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHGqNFb" x1="6.85" x2="6.85" y1="30.903" y2="29.443" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="inMk86b" x1="22.521" x2="23.3" y1="25.776" y2="25.776" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iAU2rKb" x1="16.031" x2="23.656" y1="27.121" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iHgozhd" x1="21.745" x2="16.63" y1="18.517" y2="24.035" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="i192yee" x1="19.899" x2="19.742" y1="15.798" y2="17.86" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="i2TSoXc" x1="17.438" x2="18.594" y1="19.043" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="ibDlFkd" x1="12.125" x2="12.453" y1="23.34" y2="22.98" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iS5RSRd" x1="20.164" x2="19.492" y1="23.808" y2="23.824" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="i9WhBNb" x1="12.06" x2="12.06" y1="20.007" y2="28.59" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="iHmDWXC" x1="9.369" x2="10.264" y1="25.406" y2="25.406" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iyaJxyd" x1="13.742" x2="14.414" y1="25.416" y2="25.416" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="isAjnye" x1="14.805" x2="14.563" y1="24.934" y2="24.934" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iXRqbGX" x1="15.84" x2="16.695" y1="11.905" y2="11.905" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iZYsZad" x1="14.767" x2="15.841" y1="11.75" y2="11.809" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iAGZ6bc" x1="15.84" x2="15.84" y1="12.304" y2="13.156" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i3QDGHb" x1="15.84" x2="15.84" y1="10.057" y2="10.476" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i6SOmSc" x1="21.203" x2="11.08" y1="5.414" y2="5.414" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="inGj5Wc" x1="18.8" x2="18.486" y1="10.214" y2="10.408" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVFMLLb" x1="14.402" x2="14.088" y1="10.214" y2="10.408" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inTz5fc" x1="22.276" x2="21.069" y1="10.241" y2="12.417" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iehpFQw" x1="9.99" x2="11.448" y1="10.945" y2="10.818" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><filter id="iUlXhBd" width="7.147" height="11.557" x="8.885" y="15.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".5"/></filter><filter id="i9nXdme" width="7.147" height="11.557" x="15.779" y="15.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".5"/></filter><filter id="irFGrRc" width="3.699" height="3.699" x="16.85" y="24.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".375"/></filter><filter id="iWv7MXd" width="1.42" height="1.42" x="18.82" y="24.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24141"/></filter><filter id="iw8LgWc" width="5.381" height="7.171" x="9.369" y="19.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24141"/></filter><filter id="i8FFG6d" width="5.3" height="6.89" x="9.435" y="19.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".15"/></filter><filter id="ijYtQiN" width="10.72" height="12.542" x="10.777" y="4.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24141" result="effect2_innerShadow_3987_24141"/></filter><filter id="ibOvNgb" width="3.877" height="4.9" x="13.694" y="9.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".5"/></filter><filter id="ieXXx9d" width="2.077" height="3.1" x="14.801" y="9.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".05"/></filter><filter id="i4wEUFd" width="3.718" height="1.573" x="13.981" y="13.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".05"/></filter><filter id="ibUdN1c" width="12.873" height="8.356" x="9.404" y="1.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24141" result="effect2_innerShadow_3987_24141"/></filter><filter id="itcAlMe" width="2.339" height="1.19" x="17.429" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24141"/></filter><filter id="icfyRAi" width="2.339" height="1.176" x="12.173" y="7.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24141"/></filter><filter id="i99r43c" width="6.584" height="5.992" x="9.759" y="2.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".125"/></filter><filter id="idnMqPb" width="6.362" height="5.736" x="15.681" y="3.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".125"/></filter><filter id="iiE95Rc" width=".787" height=".696" x="17.288" y="9.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".05"/></filter><filter id="iWgZkKX" width=".891" height=".913" x="18.128" y="9.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".1"/></filter><filter id="iYtpmrp" width=".986" height="1.04" x="13.685" y="9.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".1"/></filter><filter id="ir19s9h" width=".913" height=".704" x="12.93" y="9.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".05"/></filter><filter id="iPmadOd" width="1.329" height="2.379" x="9.807" y="9.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".125"/></filter><filter id="iqnjMlN" width="1.447" height="2.403" x="20.552" y="9.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".125"/></filter><filter id="iISS1Uc" width="2.305" height="1.061" x="12.142" y="7.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".125"/></filter><filter id="iB5hLOc" width="2.305" height="1.061" x="17.421" y="7.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24141" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:health-worker" /></template>
<style>
.a13z79b3g {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.573 8.097a1.85 1.85 0 0 0-.688-.412c-.304-.095-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.027.979.036c.198.063.332.164.49.301a.277.277 0 0 0 .364-.418");
}

.a2af2gsoe {
  d: path("m5.78 22.897l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.a7cr10tok {
  fill: var(--svg-color--000, #000);
  d: path("M14.167 10.576a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
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

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ahs4l-bul {
  stop-color: var(--svg-color--b04418, #B04418);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b7j9q7t_h {
  d: path("M20.762 12.417q.1-1.596.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bbb6nqbkj {
  cx: 13.387px;
  cy: 10.065px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.btdcctb-s {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.43 7.988a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.002.001a.277.277 0 0 1-.34-.438z");
}

.bxktz0b-e {
  d: path("M18.819 10.458a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.byzf41gac {
  d: path("M15.225 21.819c.263.515.263.94.263 1.305v2.991c0 .17-.209.26-.328.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.059a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.135a.3.3 0 0 1 .04.08z");
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c0_uynzww {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.231 9.412c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cd6o9mbpd {
  stop-color: var(--svg-color--cc711f, #CC711F);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.cfv3vkbbo {
  fill-rule: evenodd;
  d: path("M9.37 26.317v-2.47h.98v2.14h.25v.98h-.58a.65.65 0 0 1-.65-.65");
}

.ckpq6cbbz {
  d: path("M26.681 28.097c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cr4vpibfc {
  d: path("m21.748 20.282l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.296l-4.505 4.599c-.112.111-.306.037-.306-.12v-3.33c0-.036.009-.064.018-.101l2.54-5.888a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.185 2.003a.214.214 0 0 1-.176.232");
}

.cshvfv4mr {
  d: path("M16.21 15.537c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e1yw_lhor {
  d: path("m21.053 8.833l-.03-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.136-.12-.368c-.256-.97.671-1.712 1.656-1.522c.973.19 2.082.517 2.902 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.eo2zg9b5q {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.354 10.557l-.635 1.839c-.108.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.53-1.839c-.115-.407-.543-.407-.662 0");
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fcsf_zb4h {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.062 20.282l.732.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .01.296l4.505 4.599c.111.111.306.037.306-.12v-3.33c0-.036-.01-.064-.018-.101l-2.54-5.888a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.003a.214.214 0 0 0 .177.232");
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gqtxsdait {
  stop-color: var(--svg-color--964b08, #964B08);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hzk_cze2a {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.45 9.411c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.hzlf5p9pl {
  d: path("M17.958 9.872c.064.085-.069.188-.22.302s-.263.192-.327.107c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icxn-4bej {
  d: path("M18.024 9.683a.892.892 0 0 1 .86 1.128H17.16a.896.896 0 0 1 .864-1.128");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ijica1bxp {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.4 8.221c-.256-.184-.897-.508-1.654-.381");
}

.iss-_bcft {
  fill-rule: evenodd;
  d: path("M12.06 20.988c-.94 0-1.71.762-1.71 1.71v3.299h.67a.49.49 0 0 1 0 .981h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 1 1 0-.981h.6v-3.3a1.71 1.71 0 0 0-1.71-1.709");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
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

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-4_4pb_k {
  d: path("M10.979 12.326a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l719ofbil {
  d: path("M15.88 15.537h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3hs70bsg {
  cx: 13.387px;
  cy: 10.065px;
  rx: 0.39px;
  ry: 0.197px;
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.n1130ub2h {
  d: path("M20.695 4.434c.514.177.976.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.34 2.34 0 0 1 1.299-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nhk9aqb2a {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.803 9.879a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.njxg2tppx {
  d: path("M15.84 18.847a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.npms2-bys {
  d: path("M19.53 26.307a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o7b3grg3h {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.046 26.42h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.o89gwcc-h {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.467 8.268c.257-.185.897-.51 1.655-.382");
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkncdnbsd {
  d: path("m15.458 10.362l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.pmel6eb9u {
  stop-color: var(--svg-color--e56e23, #E56E23);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pv_89yvsa {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.802 11.766q.058-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pwmvjmb6w {
  stop-color: var(--svg-color--e35628, #E35628);
  stop-opacity: 0;
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r2g2v5bav {
  d: path("M16.348 22.641c0-.04-.01-.203 0-.243l2.662-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.055.05.055.09l.055 3.6h.01v3.97h.79v-3.97l.078-3.416z");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.r9ptygktb {
  d: path("M11.015 13.842a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rf0snvbcb {
  d: path("m16.072 5.461l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.rhd6ajb5p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.958 9.872c.064.085-.069.188-.22.302s-.263.192-.327.107c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.ruqg683_m {
  fill-rule: evenodd;
  d: path("M15.79 15.248a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.rz95hov5a {
  stop-color: var(--svg-color--e35628, #E35628);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.shqkb3bgz {
  d: path("M19.53 26.857a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t-bhx2bra {
  d: path("M10.786 9.218a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uptr03y8u {
  fill: var(--svg-color--000, #000);
  d: path("M17.513 10.576c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uwu4h0bpr {
  stop-color: var(--svg-color--e18e23, #E18E23);
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v2l31obiy {
  d: path("M15.84 13.973c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.v3s_tvltw {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.49 13.578c.389.203.854.32 1.35.32c.5 0 .96-.117 1.35-.32h.001a.23.23 0 0 1 .271.045a.214.214 0 0 1 .024.272m-2.997-.317l2.934.276m-2.934-.276a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27m.295-.317l-.232.276m3.229.041l-.063-.041m.063.041l-.063-.041m.063.041a1.97 1.97 0 0 1-1.646.88a1.97 1.97 0 0 1-1.646-.88m3.23-.041a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.063.042l.063-.042m-.063.042v-.001l.063-.041");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6mol8i_w {
  d: path("M16.504 21.819c-.262.515-.262.94-.262 1.305v2.991c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.059a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.426-1.135a.3.3 0 0 0-.04.08z");
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wbl1mv4if {
  d: path("M14.471 10.47c0-.288-.234-.48-.298-.538l-.288.279l.178.361z");
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xaa8swm1e {
  d: path("M20.701 12.326c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xh3px69yj {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.7 27.086a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.199");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.y2m71f9gw {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.79 15.248a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.yf3js1r3y {
  fill-rule: evenodd;
  d: path("M14.75 23.857v2.47a.65.65 0 0 1-.65.651h-.58v-.981h.25v-2.14z");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.yqh8f3bfu {
  d: path("M15.841 15.537c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z1zmjebmz {
  d: path("M13.656 9.683a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
