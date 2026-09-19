<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i2HxZpe)" clip-rule="evenodd" class="a104mxb3m"/><path fill="url(#iLDbWZF)" clip-rule="evenodd" class="a104mxb3m"/><path fill="url(#iSuIcrb)" clip-rule="evenodd" class="a104mxb3m"/><path fill="url(#idwnaTd)" clip-rule="evenodd" class="a104mxb3m"/><path fill="url(#iMvoNwL)" clip-rule="evenodd" class="a104mxb3m"/><path fill="url(#ib20Rld)" class="t5pe4nbwg"/><path fill="url(#iCuIpPe)" class="t5pe4nbwg"/><path fill="url(#iBz9hnb)" class="an3sujbfk"/><path fill="url(#iCaGFud)" class="an3sujbfk"/><path class="z0o2_9bqb"/><path fill="url(#ivJovsc)" class="qblt4li6u"/><path fill="url(#iKvRQXj)" class="qblt4li6u"/><path fill="url(#igFFTkZ)" class="i07pcvbxr"/><path fill="url(#iS4kcAe)" class="i07pcvbxr"/><path fill="url(#iUlwmgf)" class="i07pcvbxr"/><path clip-rule="evenodd" class="sfeqtebzu"/><path fill="url(#iSkNwse)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iOY3k9q)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i6iKomb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iOVxnbe)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iOUqCSd)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iYThuKb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iSuXQ4d)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#izNounc)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iSXrQEX)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#isfKEBM)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iGYYGvc)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i66TSxc)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iHmoTzb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iYzIl3d)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iP1MScb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iACpyTc)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i40BGob)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i6upKNb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i9kWTcb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i1Rynhm)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iKAkO4b)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iaKrOXd)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iBjnmdd)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iBuR4ad)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iLOR8ke)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iZJRtzb)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#i4djMDe)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iseLb5c)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#iY9PqOd)" clip-rule="evenodd" class="kffs63b8s"/><path fill="url(#ikcsLGb)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iBVGtYc)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iRJ4Yrd)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#i5zXp5b)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iqwuxSb)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iHMxa9d)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iQDxo4b)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iMuwzGb)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iznjECc)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iJjpK8b)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#iRbMsbd)" clip-rule="evenodd" class="jlk-hdnmw"/><path fill="url(#ihMcbvd)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#i5LzKze)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#i7LwIbd)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#irkvZke)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#imnGClb)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#iyDqakc)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#ifZzqeb)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#iupVnCb)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#itS8TNb)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#iuUe9Pe)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#idxi9fb)" clip-rule="evenodd" class="no9d59beu"/><path fill="url(#iiWCqbe)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iLLps2g)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#i2vCPyc)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iNnN4Kb)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iuGOy1c)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iVjpS2c)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#i24p0Bb)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iVsG1we)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#ijN9CHd)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#ivY9aTb)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iQDtusn)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iI7gNve)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#ihoHBeb)" clip-rule="evenodd" class="dtnuuu9_z"/><path fill="url(#iHFaaOc)" class="vsi3lxb3v"/><path fill="url(#inFs5ne)" class="vsi3lxb3v"/><path fill="url(#iRmzjke)" class="vsi3lxb3v"/><path class="fypc07nbh"/><path fill="url(#iTh9mEe)" class="r0pofkanr"/><path fill="url(#ihg7qWc)" class="r0pofkanr"/><path fill="url(#iu2s4uO)" class="r0pofkanr"/><path class="k1tdo2boa"/><path fill="url(#iNtKzbb)" class="b71nelbcx"/><path fill="url(#iAQdr0c)" class="b71nelbcx"/><path fill="url(#iQ16L2b)" class="b71nelbcx"/><path fill="url(#iR5fZVg)" class="b71nelbcx"/><ellipse fill="url(#i8kq9Cd)" transform="rotate(-30.288 9.652 6.039)" class="b6pq288im"/><ellipse fill="url(#iHRbu0c)" transform="rotate(-30.288 9.652 6.039)" class="b6pq288im"/><ellipse fill="url(#iQ3dHMb)" transform="rotate(-30.288 9.652 6.039)" class="b6pq288im"/><ellipse fill="url(#iq0fEjZ)" transform="rotate(-30.288 9.652 6.039)" class="b6pq288im"/><ellipse fill="url(#i1LGVGb)" transform="rotate(-30.288 13.694 12.959)" class="hpujxmbpr"/><ellipse fill="url(#ib7haDc)" transform="rotate(-30.288 13.694 12.959)" class="hpujxmbpr"/><ellipse fill="url(#iyVoHcb)" transform="rotate(-30.288 13.694 12.959)" class="hpujxmbpr"/><ellipse fill="url(#iqHuMeS)" transform="rotate(-30.288 13.694 12.959)" class="hpujxmbpr"/><defs><radialGradient id="iLDbWZF" cx="0" cy="0" r="1" gradientTransform="matrix(-3.37497 4.56251 -3.28947 -2.43328 19.313 20.844)" gradientUnits="userSpaceOnUse"><stop class="vpryp5v6i"/><stop offset="1" class="gf34pvbar"/></radialGradient><radialGradient id="iSuIcrb" cx="0" cy="0" r="1" gradientTransform="rotate(92.272 4.946 17.559)scale(16.556 7.5754)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="jx8djmb0j"/><stop offset=".874" class="i6wphsb-g"/><stop offset=".933" class="i6wphsb-g"/><stop offset=".986" class="wiaq39fhw"/></radialGradient><radialGradient id="idwnaTd" cx="0" cy="0" r="1" gradientTransform="matrix(19.31249 9.0625 -4.14666 8.83667 8.5 21.063)" gradientUnits="userSpaceOnUse"><stop offset=".796" class="jx8djmb0j"/><stop offset=".861" class="thu3phbnv"/><stop offset=".89" class="upbv48bda"/></radialGradient><radialGradient id="iMvoNwL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31252 3.40624 -2.45582 -.9463 24.188 25.625)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="lhwguvymf"/><stop offset="1" class="n3vj4acwv"/></radialGradient><radialGradient id="ib20Rld" cx="0" cy="0" r="1" gradientTransform="rotate(129.202 6.166 7.217)scale(7.21848 2.0448)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="yj0oogb7d"/><stop offset=".602" class="aao7ssbkc"/><stop offset=".857" class="iieaw9dmq"/></radialGradient><radialGradient id="iCuIpPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 .75 -.44164 -1.2145 15.563 8.219)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="ptr6_pbgw"/><stop offset="1" class="uultnxbbr"/></radialGradient><radialGradient id="iBz9hnb" cx="0" cy="0" r="1" gradientTransform="matrix(2.9924 -2.2119 .66807 .9038 10.063 18.031)" gradientUnits="userSpaceOnUse"><stop class="joewbnbwp"/><stop offset="1" class="x3___2b4g"/></radialGradient><radialGradient id="iCaGFud" cx="0" cy="0" r="1" gradientTransform="matrix(2.12501 -2.18749 1.376 1.3367 7.406 17.906)" gradientUnits="userSpaceOnUse"><stop class="vlgt4rb_q"/><stop offset="1" class="wbdgc8bbj"/></radialGradient><radialGradient id="ivJovsc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08496 1.46289 -.46618 -.6644 18.835 12.443)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="lo5xyqbxv"/><stop offset="1" class="a98vdlbkg"/></radialGradient><radialGradient id="iKvRQXj" cx="0" cy="0" r="1" gradientTransform="rotate(114.88 6.75 12.405)scale(1.03987 .65411)" gradientUnits="userSpaceOnUse"><stop class="f4tiuebfp"/><stop offset="1" class="gs5vyzbqd"/></radialGradient><radialGradient id="igFFTkZ" cx="0" cy="0" r="1" gradientTransform="matrix(4.50977 -1.71875 .46256 1.21368 7.125 11.625)" gradientUnits="userSpaceOnUse"><stop class="y_p3j19sj"/><stop offset="1" class="gno2crpzn"/></radialGradient><radialGradient id="iS4kcAe" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -1.96875 1.24617 1.97805 5.125 10.25)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="mnau5_bvg"/><stop offset="1" class="zbjkuhbbg"/></radialGradient><radialGradient id="iUlwmgf" cx="0" cy="0" r="1" gradientTransform="matrix(2.41698 -2.9707 1.35331 1.10106 8.896 12.752)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="yi339pefe"/><stop offset="1" class="sdh5vac-y"/></radialGradient><radialGradient id="iSkNwse" cx="0" cy="0" r="1" gradientTransform="matrix(11.93751 21.18749 -14.80162 8.33957 10.875 6.938)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="c14u26e5f"/><stop offset=".515" class="c14u26e5f"/><stop offset=".678" class="ojey5f5pz"/></radialGradient><radialGradient id="iOY3k9q" cx="0" cy="0" r="1" gradientTransform="rotate(124.739 7.51 9.346)scale(5.20985 1.7155)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="re-s51bov"/><stop offset="1" class="di9i-wbmu"/></radialGradient><radialGradient id="i6iKomb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.03124 2.06254 -.381 -.9294 18.344 7.531)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="re-s51bov"/><stop offset="1" class="di9i-wbmu"/></radialGradient><radialGradient id="iOVxnbe" cx="0" cy="0" r="1" gradientTransform="rotate(113.629 6.913 10.578)scale(3.27455 .32378)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="q_ej8bbvk"/><stop offset="1" class="di9i-wbmu"/></radialGradient><radialGradient id="iOUqCSd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 1.25002 -.11354 -.26965 18.344 7.5)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="t_6959aeo"/><stop offset="1" class="di9i-wbmu"/></radialGradient><radialGradient id="iYThuKb" cx="0" cy="0" r="1" gradientTransform="rotate(157.264 4.768 7.575)scale(3.5577 1.33919)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="gyj3sueig"/><stop offset="1" class="k2904dbqc"/></radialGradient><radialGradient id="iSuXQ4d" cx="0" cy="0" r="1" gradientTransform="rotate(-106.783 10.076 1.11)scale(2.05634 .95704)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="sf8ibn16b"/><stop offset="1" class="d69z9kb6u"/></radialGradient><radialGradient id="izNounc" cx="0" cy="0" r="1" gradientTransform="rotate(156.14 7.91 8.298)scale(3.55372 .23798)" gradientUnits="userSpaceOnUse"><stop class="csyjjublr"/><stop offset="1" class="fmoxrzb1q"/></radialGradient><radialGradient id="iSXrQEX" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53127 1.84373 -.12347 -.1695 17.25 9.406)" gradientUnits="userSpaceOnUse"><stop class="csyjjublr"/><stop offset="1" class="fmoxrzb1q"/></radialGradient><radialGradient id="isfKEBM" cx="0" cy="0" r="1" gradientTransform="matrix(-4.125 .31248 -.05917 -.7811 19.344 13.969)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="d4etdkb8p"/><stop offset="1" class="lzo-aybqf"/></radialGradient><radialGradient id="iGYYGvc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.92187 .90626 -.03478 -.18888 20.953 15.031)" gradientUnits="userSpaceOnUse"><stop class="csyjjublr"/><stop offset="1" class="fmoxrzb1q"/></radialGradient><radialGradient id="i66TSxc" cx="0" cy="0" r="1" gradientTransform="matrix(4.53125 -3.21875 1.25092 1.761 5 13.656)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="c8xcnwb6r"/><stop offset="1" class="ukia4q36v"/></radialGradient><radialGradient id="iHmoTzb" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 .375 -.20144 1.1415 11.188 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="p5rn5ziom"/><stop offset="1" class="xuvsu-_8n"/></radialGradient><radialGradient id="iYzIl3d" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .125 -.0574 1.1912 15.5 14.344)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="bl5w9254v"/><stop offset="1" class="xuvsu-_8n"/></radialGradient><radialGradient id="iP1MScb" cx="0" cy="0" r="1" gradientTransform="matrix(2 -1.34375 .61713 .91852 14.594 11.156)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="bl5w9254v"/><stop offset="1" class="xuvsu-_8n"/></radialGradient><radialGradient id="iACpyTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -1.65625 .21595 .35448 11.063 17)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="iutxp_ysa"/><stop offset="1" class="glw1xt6de"/></radialGradient><radialGradient id="i40BGob" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 -2 1.07436 -.21823 12.844 16.313)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="ovywq0q6q"/><stop offset="1" class="xuvsu-_8n"/></radialGradient><radialGradient id="i6upKNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -2.625 .77189 .5146 12 18.594)" gradientUnits="userSpaceOnUse"><stop offset=".421" class="a82_fdcqu"/><stop offset="1" class="t18-i7h_v"/></radialGradient><radialGradient id="i9kWTcb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -3.28124 .96486 .95567 12.406 21.469)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="dzh06wbhv"/><stop offset="1" class="qqolyab8d"/></radialGradient><radialGradient id="i1Rynhm" cx="0" cy="0" r="1" gradientTransform="matrix(3.2705 -3.71874 .40639 .3574 11.719 21)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="b6cr-gbzj"/><stop offset="1" class="y70gp9buj"/></radialGradient><radialGradient id="iKAkO4b" cx="0" cy="0" r="1" gradientTransform="rotate(-58.206 23.502 3.156)scale(6.28715 1.68197)" gradientUnits="userSpaceOnUse"><stop class="r56t17k6u"/><stop offset="1" class="nj0yaz3xv"/></radialGradient><radialGradient id="iaKrOXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75002 2.24998 -.19492 -.23824 14.563 7.376)" gradientUnits="userSpaceOnUse"><stop offset=".42" class="nwqbctdur"/><stop offset="1" class="f5kkdl_dt"/></radialGradient><radialGradient id="iBjnmdd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46875 .09374 -.03024 -1.11913 8.563 7.563)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="qvd_ohbrm"/><stop offset="1" class="kq2oimbzd"/></radialGradient><radialGradient id="iBuR4ad" cx="0" cy="0" r="1" gradientTransform="matrix(.34376 3.03125 -.97798 .1109 8.562 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="i3ry-63rx"/><stop offset="1" class="daj581ddf"/></radialGradient><radialGradient id="iLOR8ke" cx="0" cy="0" r="1" gradientTransform="rotate(4.899 -84.524 128.394)scale(3.29328 1.06252)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="qj9l8uo4u"/><stop offset="1" class="e88fbdb6e"/></radialGradient><radialGradient id="iZJRtzb" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 2.46875 -1.0757 .0817 15.813 17.719)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="qj9l8uo4u"/><stop offset="1" class="e88fbdb6e"/></radialGradient><radialGradient id="i4djMDe" cx="0" cy="0" r="1" gradientTransform="rotate(171.539 7.233 10.747)scale(3.82286 2.19221)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="w2e94jb9c"/><stop offset=".708" class="h4osjvb8t"/></radialGradient><radialGradient id="iseLb5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -2.59374 .83683 .63519 11.437 5.812)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="eaepvbc3x"/><stop offset="1" class="bolo20bvv"/></radialGradient><radialGradient id="iY9PqOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 3 -1.37377 -.1431 14.063 4.844)" gradientUnits="userSpaceOnUse"><stop class="f03kn2b2e"/><stop offset="1" class="h8j-usbqw"/></radialGradient><radialGradient id="ikcsLGb" cx="0" cy="0" r="1" gradientTransform="rotate(153.146 6.025 3.817)scale(8.30151 8.69209)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="ygaqz8yxp"/><stop offset=".8" class="hkvtr9wky"/></radialGradient><radialGradient id="iBVGtYc" cx="0" cy="0" r="1" gradientTransform="rotate(63.435 -.412 7.417)scale(3.00472)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="bp7whacwf"/><stop offset=".554" class="it1h_acmt"/><stop offset=".917" class="st80wfikg"/></radialGradient><radialGradient id="iRJ4Yrd" cx="0" cy="0" r="1" gradientTransform="rotate(111.303 3.833 5.393)scale(5.33314 1.69202)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="hsq3dfbnm"/><stop offset="1" class="o3w9gtaqi"/></radialGradient><radialGradient id="i5zXp5b" cx="0" cy="0" r="1" gradientTransform="rotate(67.62 1.964 8.282)scale(2.87262 1.19664)" gradientUnits="userSpaceOnUse"><stop class="oboj3dkel"/><stop offset="1" class="e3htrz5kf"/></radialGradient><radialGradient id="iqwuxSb" cx="0" cy="0" r="1" gradientTransform="rotate(95.171 3.33 6.381)scale(2.41608 .34235)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="jmjuocn8l"/><stop offset=".664" class="psdz3c18e"/></radialGradient><radialGradient id="iHMxa9d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88281 .66407 -.03874 -.1682 11.875 5.555)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="td7mgg75w"/><stop offset="1" class="jwz1hdunq"/></radialGradient><radialGradient id="iQDxo4b" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 2.09375 -.83828 1.00094 10.25 6.75)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="t71f6kbpu"/><stop offset="1" class="o4_dym0sq"/></radialGradient><radialGradient id="iMuwzGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 2.5 -.97494 -.19499 10 9.25)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ij24isu0e"/><stop offset="1" class="uqrk6isha"/></radialGradient><radialGradient id="iznjECc" cx="0" cy="0" r="1" gradientTransform="rotate(115.598 2.6 6.058)scale(2.82082 2.29222)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="gbq8qwbms"/><stop offset=".72" class="w_yegrjfk"/></radialGradient><radialGradient id="iJjpK8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.35939 2.10936 -.2289 .14751 10.5 7.078)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="t71f6kbpu"/><stop offset="1" class="aatu_7jsq"/></radialGradient><radialGradient id="iRbMsbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 .46875 -.09311 .20484 7.844 5.187)" gradientUnits="userSpaceOnUse"><stop class="m5ucrbawd"/><stop offset="1" class="rgkvw6bct"/></radialGradient><radialGradient id="ihMcbvd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.40459 3.74828 -3.92406 -7.75184 17.164 11.417)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="cojfyq43x"/><stop offset=".8" class="n_mxcybuj"/></radialGradient><radialGradient id="i5LzKze" cx="0" cy="0" r="1" gradientTransform="matrix(1.34345 2.68625 -2.68664 1.34365 10.447 11.386)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="xjhdaybsu"/><stop offset=".917" class="st80wfikg"/></radialGradient><radialGradient id="i7LwIbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93703 4.96644 -1.57596 -.61466 14.29 10.698)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="maos0ju8s"/><stop offset="1" class="obdxu_0ib"/></radialGradient><radialGradient id="irkvZke" cx="0" cy="0" r="1" gradientTransform="matrix(1.0935 2.655 -1.10618 .4556 12.915 10.23)" gradientUnits="userSpaceOnUse"><stop class="oboj3dkel"/><stop offset="1" class="e3htrz5kf"/></radialGradient><radialGradient id="imnGClb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21774 2.40512 -.34088 -.03086 14.025 10.557)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="jmjuocn8l"/><stop offset=".664" class="psdz3c18e"/></radialGradient><radialGradient id="iyDqakc" cx="0" cy="0" r="1" gradientTransform="rotate(167.031 7.249 7.14)scale(2.95761 .17252)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="td7mgg75w"/><stop offset="1" class="jwz1hdunq"/></radialGradient><radialGradient id="ifZzqeb" cx="0" cy="0" r="1" gradientTransform="rotate(39.939 -11.66 26.496)scale(3.25989 1.30512)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="t71f6kbpu"/><stop offset="1" class="o4_dym0sq"/></radialGradient><radialGradient id="iupVnCb" cx="0" cy="0" r="1" gradientTransform="rotate(101.313 .394 13.837)scale(2.54834 .99402)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ij24isu0e"/><stop offset="1" class="uqrk6isha"/></radialGradient><radialGradient id="itS8TNb" cx="0" cy="0" r="1" gradientTransform="rotate(115.604 2.443 10.788)scale(2.81963 2.2916)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="flrrwlbmd"/><stop offset=".72" class="jfx4yvwgg"/></radialGradient><radialGradient id="iuUe9Pe" cx="0" cy="0" r="1" gradientTransform="matrix(1.35907 2.10839 -.22881 .1475 14.54 13.994)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="t71f6kbpu"/><stop offset="1" class="aatu_7jsq"/></radialGradient><radialGradient id="idxi9fb" cx="0" cy="0" r="1" gradientTransform="rotate(24.439 -22.004 33.49)scale(1.13249 .22491)" gradientUnits="userSpaceOnUse"><stop class="phvt2rban"/><stop offset="1" class="xb93ataev"/></radialGradient><radialGradient id="iiWCqbe" cx="0" cy="0" r="1" gradientTransform="rotate(153.151 8.424 11.728)scale(8.30111 8.69047)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="moxzorbzd"/><stop offset=".8" class="vei0avbyj"/></radialGradient><radialGradient id="iLLps2g" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 2.68688 -2.68725 1.34394 14.518 18.357)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="sy0t_8d-w"/><stop offset=".554" class="mes7y7bnb"/><stop offset=".917" class="xxfgtybcl"/></radialGradient><radialGradient id="i2vCPyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93748 4.9676 -1.57632 -.6148 18.361 17.67)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="tljvg2s1j"/><stop offset="1" class="zif_sdbfi"/></radialGradient><radialGradient id="iNnN4Kb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09376 2.65563 -1.10643 .4557 16.987 17.2)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="z51m5gb8k"/><stop offset="1" class="ud7c6qb1s"/></radialGradient><radialGradient id="iuGOy1c" cx="0" cy="0" r="1" gradientTransform="rotate(95.173 1.041 17.03)scale(2.41553 .34235)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="okb60kb1b"/><stop offset=".664" class="iznz80bds"/></radialGradient><radialGradient id="iVjpS2c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8828 .6639 -.03873 -.16816 19.986 19.442)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="slmbt8fak"/><stop offset="1" class="ts48tfbny"/></radialGradient><radialGradient id="i24p0Bb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 2.09326 -.83805 1.0009 18.361 20.638)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="t71f6kbpu"/><stop offset="1" class="o4_dym0sq"/></radialGradient><radialGradient id="iVsG1we" cx="0" cy="0" r="1" gradientTransform="matrix(-.50002 2.49941 -.97492 -.19504 18.111 23.137)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="svruvo2lc"/><stop offset="1" class="uqrk6isha"/></radialGradient><radialGradient id="ijN9CHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 2.54336 -2.06706 -.9905 17.299 20.219)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="gbq8qwbms"/><stop offset=".72" class="w_yegrjfk"/></radialGradient><radialGradient id="ivY9aTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.35939 2.10887 -.22886 .14753 18.612 20.965)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="t71f6kbpu"/><stop offset="1" class="aatu_7jsq"/></radialGradient><radialGradient id="iQDtusn" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 .46864 -.09307 .2048 15.955 19.076)" gradientUnits="userSpaceOnUse"><stop class="fnytecb6t"/><stop offset="1" class="axg7yqbry"/></radialGradient><radialGradient id="iI7gNve" cx="0" cy="0" r="1" gradientTransform="matrix(1.90626 2.37499 -1.77307 1.42314 15.188 22.72)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="p0-f05bhu"/><stop offset="1" class="k3s3y9x9x"/></radialGradient><radialGradient id="ihoHBeb" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 3.8125 -2.84626 .41994 22.438 17.875)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="lfka5xbyc"/><stop offset="1" class="xtxia1bse"/></radialGradient><radialGradient id="iHFaaOc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64944 1.07908 -1.07689 -1.6461 18.19 19.927)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggrcv68af"/><stop offset=".596" class="l6dgy2nlj"/><stop offset=".758" class="nl2s8bd-g"/></radialGradient><radialGradient id="inFs5ne" cx="0" cy="0" r="1" gradientTransform="matrix(.58418 -.15955 .1245 .45589 18.086 19.627)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="ex2_2pvde"/><stop offset="1" class="ahmqnhabn"/></radialGradient><radialGradient id="iRmzjke" cx="0" cy="0" r="1" gradientTransform="matrix(-.2291 .47864 -.35592 -.17035 16.952 19.57)" gradientUnits="userSpaceOnUse"><stop class="ah8fnybuw"/><stop offset="1" class="rxy5vs-2k"/></radialGradient><radialGradient id="iTh9mEe" cx="0" cy="0" r="1" gradientTransform="rotate(24.308 -55.739 32.591)scale(24.2646 6.136)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="mqde36bmz"/><stop offset=".764" class="g4x08gpks"/></radialGradient><radialGradient id="ihg7qWc" cx="0" cy="0" r="1" gradientTransform="rotate(28.178 -37.452 38.395)scale(7.75147 1.65229)" gradientUnits="userSpaceOnUse"><stop class="x_qx6sczp"/><stop offset="1" class="tr6ybwbrh"/></radialGradient><radialGradient id="iu2s4uO" cx="0" cy="0" r="1" gradientTransform="matrix(7.40625 5.4375 -.49912 .67984 19.281 26.813)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="uw_gacbhb"/><stop offset="1" class="pwlp4sbzy"/></radialGradient><radialGradient id="iNtKzbb" cx="0" cy="0" r="1" gradientTransform="rotate(109.199 11.072 21.085)scale(18.5306 16.1702)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="gsrsoz4rt"/><stop offset=".826" class="yx3w6wbqh"/></radialGradient><radialGradient id="iAQdr0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.4375 -2.5 0 24.438 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".099" class="uxbj02bsu"/><stop offset="1" class="zk8zs5jmn"/></radialGradient><radialGradient id="iQ16L2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 4.9375 -.35555 -.0315 24.531 11.781)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="oxgf7zbcq"/><stop offset="1" class="k_4s-ebvj"/></radialGradient><radialGradient id="iR5fZVg" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 4.46875 -2.16675 .13637 24.531 24.969)" gradientUnits="userSpaceOnUse"><stop class="in4fonnhj"/><stop offset="1" class="el6-b7bsq"/></radialGradient><radialGradient id="i8kq9Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0507 .78477 -.5118 -1.33738 10.277 6.403)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="ggrcv68af"/><stop offset=".913" class="vk4gb2c7w"/></radialGradient><radialGradient id="iHRbu0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.00989 .19175 -.12834 .67592 10.458 6.03)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ex2_2pvde"/><stop offset="1" class="ahmqnhabn"/></radialGradient><radialGradient id="iQ3dHMb" cx="0" cy="0" r="1" gradientTransform="rotate(147.75 4.098 4.797)scale(5.35324 3.13226)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="dipi1511d"/><stop offset=".643" class="drlfxwcxq"/></radialGradient><radialGradient id="iq0fEjZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.16316 .13994 -.25127 -.29297 10.7 5.168)" gradientUnits="userSpaceOnUse"><stop class="eft5i5bhq"/><stop offset="1" class="ytc6wlbsd"/></radialGradient><radialGradient id="i1LGVGb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0507 .78477 -.5118 -1.33738 14.32 13.323)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="ggrcv68af"/><stop offset=".913" class="vk4gb2c7w"/></radialGradient><radialGradient id="ib7haDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.00989 .19175 -.12834 .67592 14.5 12.95)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ex2_2pvde"/><stop offset="1" class="ahmqnhabn"/></radialGradient><radialGradient id="iyVoHcb" cx="0" cy="0" r="1" gradientTransform="rotate(147.75 5.119 8.841)scale(5.35324 3.13226)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="dipi1511d"/><stop offset=".643" class="drlfxwcxq"/></radialGradient><radialGradient id="iqHuMeS" cx="0" cy="0" r="1" gradientTransform="matrix(-.16316 .13994 -.25127 -.29297 14.743 12.087)" gradientUnits="userSpaceOnUse"><stop class="eft5i5bhq"/><stop offset="1" class="ytc6wlbsd"/></radialGradient><linearGradient id="i2HxZpe" x1="21.344" x2="19.25" y1="23.094" y2="24.344" gradientUnits="userSpaceOnUse"><stop class="skehobcwt"/><stop offset=".296" class="aq9jfmb0m"/><stop offset=".806" class="hzx2uabiw"/><stop offset=".858" class="s26slh_sw"/><stop offset=".982" class="p8d75mbdl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hyacinth" /></template>
<style>
.a104mxb3m {
  fill-rule: evenodd;
  d: path("m16.191 14.897l-1.976 1.213l5.952 9.696l-1.09.622l1.24 2.17c.7 1.2 2.22 1.61 3.42.93s1.62-2.21.93-3.41l-1.24-2.17l-1.244.71z");
}

.a82_fdcqu {
  stop-color: var(--svg-color--7f2afa, #7F2AFA);
}

.a98vdlbkg {
  stop-color: var(--svg-color--5d33ab, #5D33AB);
  stop-opacity: 0;
}

.aao7ssbkc {
  stop-color: var(--svg-color--632bb6, #632BB6);
}

.aatu_7jsq {
  stop-color: var(--svg-color--a456ff, #A456FF);
  stop-opacity: 0;
}

.ah8fnybuw {
  stop-color: var(--svg-color--8534ff, #8534FF);
}

.ahmqnhabn {
  stop-color: var(--svg-color--a36eff, #A36EFF);
  stop-opacity: 0;
}

.an3sujbfk {
  d: path("M13.153 16.464a3.184 3.184 0 0 1-4.009 2.342a.885.885 0 0 1-.612-1.048a3.184 3.184 0 0 1 4.01-2.341a.884.884 0 0 1 .611 1.047");
}

.aq9jfmb0m {
  stop-color: var(--svg-color--81a434, #81A434);
}

.axg7yqbry {
  stop-color: var(--svg-color--9350e2, #9350E2);
  stop-opacity: 0;
}

.b6cr-gbzj {
  stop-color: var(--svg-color--571ab5, #571AB5);
}

.b6pq288im {
  cx: 9.652px;
  cy: 6.039px;
  rx: 1.515px;
  ry: 1.482px;
}

.b71nelbcx {
  d: path("M25 27.117V7.68s-3.504 3.57-3.504 10.07S25 27.117 25 27.117");
}

.bl5w9254v {
  stop-color: var(--svg-color--5f18fc, #5F18FC);
}

.bolo20bvv {
  stop-color: var(--svg-color--6e23d6, #6E23D6);
  stop-opacity: 0;
}

.bp7whacwf {
  stop-color: var(--svg-color--b163ca, #B163CA);
}

.c14u26e5f {
  stop-color: var(--svg-color--40138c, #40138C);
  stop-opacity: 0;
}

.c8xcnwb6r {
  stop-color: var(--svg-color--863cbb, #863CBB);
}

.cojfyq43x {
  stop-color: var(--svg-color--da9aff, #DA9AFF);
}

.csyjjublr {
  stop-color: var(--svg-color--8d43ff, #8D43FF);
}

.d4etdkb8p {
  stop-color: var(--svg-color--8038f9, #8038F9);
}

.d69z9kb6u {
  stop-color: var(--svg-color--5817e4, #5817E4);
  stop-opacity: 0;
}

.daj581ddf {
  stop-color: var(--svg-color--671ae6, #671AE6);
  stop-opacity: 0;
}

.di9i-wbmu {
  stop-color: var(--svg-color--9241ff, #9241FF);
  stop-opacity: 0;
}

.dipi1511d {
  stop-color: var(--svg-color--8f52c5, #8F52C5);
  stop-opacity: 0;
}

.drlfxwcxq {
  stop-color: var(--svg-color--8f52c5, #8F52C5);
}

.dtnuuu9_z {
  fill-rule: evenodd;
  d: path("M16.013 16.082c.92.255 1.682.894 2.07 1.697a3.5 3.5 0 0 1 2.077-1.194c.4-.069.478-.01.52.387a3.34 3.34 0 0 1-.76 2.483a3.25 3.25 0 0 1 2.226 1.634c.19.35.159.444-.207.62c-.93.45-2.021.46-2.888.048c-.067.957-.611 1.903-1.46 2.492c-.334.232-.431.213-.642-.124a3.26 3.26 0 0 1-.368-2.62c-.933.273-2.002.1-2.827-.488c-.325-.232-.337-.33-.08-.643a3.48 3.48 0 0 1 2.292-1.256c-.553-.737-.76-1.745-.523-2.702c.096-.39.183-.441.57-.334");
}

.dzh06wbhv {
  stop-color: var(--svg-color--6a25be, #6A25BE);
}

.e3htrz5kf {
  stop-color: var(--svg-color--bb7cff, #BB7CFF);
  stop-opacity: 0;
}

.e88fbdb6e {
  stop-color: var(--svg-color--5e14ff, #5E14FF);
  stop-opacity: 0;
}

.eaepvbc3x {
  stop-color: var(--svg-color--6e23d6, #6E23D6);
}

.eft5i5bhq {
  stop-color: var(--svg-color--8f5eff, #8F5EFF);
}

.el6-b7bsq {
  stop-color: var(--svg-color--8bb33f, #8BB33F);
  stop-opacity: 0;
}

.ex2_2pvde {
  stop-color: var(--svg-color--a271ff, #A271FF);
}

.f03kn2b2e {
  stop-color: var(--svg-color--9d48ff, #9D48FF);
}

.f4tiuebfp {
  stop-color: var(--svg-color--6940af, #6940AF);
}

.f5kkdl_dt {
  stop-color: var(--svg-color--923fff, #923FFF);
  stop-opacity: 0;
}

.flrrwlbmd {
  stop-color: var(--svg-color--954eff, #954EFF);
}

.fmoxrzb1q {
  stop-color: var(--svg-color--8d43ff, #8D43FF);
  stop-opacity: 0;
}

.fnytecb6t {
  stop-color: var(--svg-color--9350e2, #9350E2);
}

.ft5dv1b6b {
  fill: none;
}

.fypc07nbh {
  fill: var(--svg-color--8ca949, #8CA949);
  d: path("m4.332 20.835l17.179 8.821s-1.466-4.68-7.247-7.652s-9.932-1.169-9.932-1.169");
}

.g4x08gpks {
  stop-color: var(--svg-color--8ca54a, #8CA54A);
  stop-opacity: 0;
}

.gbq8qwbms {
  stop-color: var(--svg-color--8f54da, #8F54DA);
}

.gf34pvbar {
  stop-color: var(--svg-color--537a1a, #537A1A);
  stop-opacity: 0;
}

.ggrcv68af {
  stop-color: var(--svg-color--8025ff, #8025FF);
}

.glw1xt6de {
  stop-color: var(--svg-color--7024de, #7024DE);
  stop-opacity: 0;
}

.gno2crpzn {
  stop-color: var(--svg-color--511ca0, #511CA0);
}

.gs5vyzbqd {
  stop-color: var(--svg-color--6940af, #6940AF);
  stop-opacity: 0;
}

.gsrsoz4rt {
  stop-color: var(--svg-color--637e5f, #637E5F);
  stop-opacity: 0;
}

.gyj3sueig {
  stop-color: var(--svg-color--4910b2, #4910B2);
}

.h4osjvb8t {
  stop-color: var(--svg-color--5216be, #5216BE);
  stop-opacity: 0;
}

.h8j-usbqw {
  stop-color: var(--svg-color--9d48ff, #9D48FF);
  stop-opacity: 0;
}

.hkvtr9wky {
  stop-color: var(--svg-color--ac64ff, #AC64FF);
}

.hpujxmbpr {
  cx: 13.694px;
  cy: 12.959px;
  rx: 1.515px;
  ry: 1.482px;
}

.hsq3dfbnm {
  stop-color: var(--svg-color--a46ad1, #A46AD1);
}

.hzx2uabiw {
  stop-color: var(--svg-color--739723, #739723);
}

.i07pcvbxr {
  d: path("M11.264 11.037c-1.087 1.52-3.137 1.825-4.578.68a.89.89 0 0 1-.16-1.206c1.087-1.52 3.137-1.825 4.578-.68c.36.286.432.826.16 1.206");
}

.i3ry-63rx {
  stop-color: var(--svg-color--671ae6, #671AE6);
}

.i6wphsb-g {
  stop-color: var(--svg-color--98b84e, #98B84E);
}

.iieaw9dmq {
  stop-color: var(--svg-color--553086, #553086);
}

.ij24isu0e {
  stop-color: var(--svg-color--d592ff, #D592FF);
}

.in4fonnhj {
  stop-color: var(--svg-color--8bb340, #8BB340);
}

.it1h_acmt {
  stop-color: var(--svg-color--b163ea, #B163EA);
}

.iutxp_ysa {
  stop-color: var(--svg-color--7024de, #7024DE);
}

.iznz80bds {
  stop-color: var(--svg-color--945ff5, #945FF5);
  stop-opacity: 0;
}

.jfx4yvwgg {
  stop-color: var(--svg-color--954eff, #954EFF);
  stop-opacity: 0;
}

.jlk-hdnmw {
  fill-rule: evenodd;
  d: path("M7.9 2.194c.92.255 1.682.893 2.07 1.696a3.5 3.5 0 0 1 2.076-1.193c.4-.07.479-.01.521.386a3.34 3.34 0 0 1-.761 2.485a3.25 3.25 0 0 1 2.229 1.634c.19.35.159.444-.208.621c-.93.45-2.02.459-2.887.047c-.068.958-.611 1.903-1.46 2.492c-.334.232-.431.214-.643-.124a3.26 3.26 0 0 1-.367-2.622a3.33 3.33 0 0 1-2.827-.488c-.325-.231-.338-.329-.081-.643a3.48 3.48 0 0 1 2.291-1.256c-.553-.736-.76-1.745-.524-2.702c.097-.39.184-.44.571-.333");
}

.jmjuocn8l {
  stop-color: var(--svg-color--a76ddd, #A76DDD);
}

.joewbnbwp {
  stop-color: var(--svg-color--511e99, #511E99);
}

.jwz1hdunq {
  stop-color: var(--svg-color--e8a9ff, #E8A9FF);
  stop-opacity: 0;
}

.jx8djmb0j {
  stop-color: var(--svg-color--7b9f2c, #7B9F2C);
  stop-opacity: 0;
}

.k_4s-ebvj {
  stop-color: var(--svg-color--a5d065, #A5D065);
  stop-opacity: 0;
}

.k1tdo2boa {
  fill: var(--svg-color--85ae38, #85AE38);
  d: path("M25 27.117V7.68s-3.504 3.57-3.504 10.07S25 27.117 25 27.117");
}

.k2904dbqc {
  stop-color: var(--svg-color--6b1ee3, #6B1EE3);
  stop-opacity: 0;
}

.k3s3y9x9x {
  stop-color: var(--svg-color--915ddd, #915DDD);
  stop-opacity: 0;
}

.kffs63b8s {
  fill-rule: evenodd;
  d: path("M18.344 7.878c.253-.325-.032-.603-.402-.64c-.515-.05-1.37 0-1.906.121c-.441.1-.8.24-1.087.352c-.387.151-.644.252-.8.134c-.166-.125-.137-.495-.1-.966c.025-.302.052-.645.034-.991q-.01-.172-.013-.336c-.016-.51-.03-.974-.312-1.464c-.218-.38-.484-.544-.737-.22L11.32 6.057c-.35.45-.57.958-.663 1.477a3.4 3.4 0 0 0-1.614-.149l-2.74.408c-.408.06-.395.373-.172.75c.289.486.685.725 1.122.99q.142.084.286.176c.293.186.605.331.88.458c.429.2.766.355.793.561c.026.194-.188.369-.51.631a7 7 0 0 0-.84.775a7.2 7.2 0 0 0-1.042 1.6c-.15.34-.048.725.36.665l2.306-.343l-2.206 1.288c-.357.208-.224.49.128.752c.455.338.917.41 1.426.489q.164.025.334.054c.345.062.691.077.996.091c.476.022.85.039.955.218c.098.168-.034.409-.234.77a7 7 0 0 0-.487 1.027a7 7 0 0 0-.358 1.86c-.009.368.233.683.59.474l1.68-.98l-1.209 1.553c-.253.325.033.603.402.64c.515.05 1.37 0 1.906-.12c.441-.1.8-.24 1.088-.353c.386-.15.643-.252.8-.134c.166.125.136.495.099.967a7 7 0 0 0-.033.99q.009.172.013.336c.015.511.03.974.311 1.465c.218.378.484.544.737.218l1.701-2.186a3.36 3.36 0 0 0 .71-1.882l.112-.065a3.36 3.36 0 0 0 1.988.305l2.741-.407c.408-.06.394-.374.171-.75c-.289-.486-.685-.726-1.122-.99q-.142-.085-.286-.176a7 7 0 0 0-.88-.459c-.428-.198-.765-.355-.793-.56c-.025-.194.189-.37.51-.631c.24-.196.538-.44.841-.775a7.2 7.2 0 0 0 1.042-1.601c.149-.34.047-.724-.36-.664l-1.948.29l1.541-.9c.357-.209.202-.575-.123-.747a7 7 0 0 0-1.796-.603a7 7 0 0 0-1.134-.08c-.412-.003-.687-.006-.786-.174c-.104-.18.065-.514.28-.939a8 8 0 0 0 .41-.912q.058-.164.117-.318c.181-.482.346-.92.275-1.482c-.055-.435-.236-.69-.593-.48l-2.128 1.242zm-4.24 6.939l1.127-.659a3.32 3.32 0 0 1 .212-3.114a3.43 3.43 0 0 1-2.637.17a3.43 3.43 0 0 1-1.51 2.256a3.32 3.32 0 0 1 2.808 1.347m4.137 1.27l-.002-.004h.006z");
}

.kq2oimbzd {
  stop-color: var(--svg-color--5d1dcc, #5D1DCC);
  stop-opacity: 0;
}

.l6dgy2nlj {
  stop-color: var(--svg-color--6733ff, #6733FF);
}

.lfka5xbyc {
  stop-color: var(--svg-color--8a5ec5, #8A5EC5);
}

.lhwguvymf {
  stop-color: var(--svg-color--8bb03d, #8BB03D);
}

.lo5xyqbxv {
  stop-color: var(--svg-color--5d33ab, #5D33AB);
}

.lzo-aybqf {
  stop-color: var(--svg-color--8038f9, #8038F9);
  stop-opacity: 0;
}

.m5ucrbawd {
  stop-color: var(--svg-color--ab60c9, #AB60C9);
}

.maos0ju8s {
  stop-color: var(--svg-color--a269f3, #A269F3);
}

.mes7y7bnb {
  stop-color: var(--svg-color--ad6af5, #AD6AF5);
}

.mnau5_bvg {
  stop-color: var(--svg-color--623676, #623676);
}

.moxzorbzd {
  stop-color: var(--svg-color--c387ff, #C387FF);
}

.mqde36bmz {
  stop-color: var(--svg-color--818a55, #818A55);
}

.n_mxcybuj {
  stop-color: var(--svg-color--b067ff, #B067FF);
}

.n3vj4acwv {
  stop-color: var(--svg-color--8bb03d, #8BB03D);
  stop-opacity: 0;
}

.nj0yaz3xv {
  stop-color: var(--svg-color--7735ab, #7735AB);
  stop-opacity: 0;
}

.nl2s8bd-g {
  stop-color: var(--svg-color--641ad9, #641AD9);
}

.no9d59beu {
  fill-rule: evenodd;
  d: path("M11.941 9.112c.92.255 1.683.894 2.07 1.698a3.5 3.5 0 0 1 2.078-1.195c.4-.07.479-.01.52.386a3.34 3.34 0 0 1-.76 2.484a3.25 3.25 0 0 1 2.225 1.633c.19.35.159.444-.208.621c-.93.45-2.019.459-2.885.048c-.069.956-.612 1.9-1.46 2.49c-.334.232-.432.213-.643-.125a3.26 3.26 0 0 1-.368-2.617a3.33 3.33 0 0 1-2.826-.489c-.325-.231-.338-.329-.081-.643a3.48 3.48 0 0 1 2.291-1.256c-.553-.736-.76-1.745-.524-2.702c.097-.39.184-.44.571-.333");
}

.nwqbctdur {
  stop-color: var(--svg-color--9e49ff, #9E49FF);
}

.o3w9gtaqi {
  stop-color: var(--svg-color--bf80ff, #BF80FF);
  stop-opacity: 0;
}

.o4_dym0sq {
  stop-color: var(--svg-color--ca83ff, #CA83FF);
  stop-opacity: 0;
}

.obdxu_0ib {
  stop-color: var(--svg-color--a269f3, #A269F3);
  stop-opacity: 0;
}

.oboj3dkel {
  stop-color: var(--svg-color--cc8dff, #CC8DFF);
}

.ojey5f5pz {
  stop-color: var(--svg-color--40138c, #40138C);
}

.okb60kb1b {
  stop-color: var(--svg-color--945ff5, #945FF5);
}

.ovywq0q6q {
  stop-color: var(--svg-color--681ce8, #681CE8);
}

.oxgf7zbcq {
  stop-color: var(--svg-color--a5d065, #A5D065);
}

.p0-f05bhu {
  stop-color: var(--svg-color--915ddd, #915DDD);
}

.p5rn5ziom {
  stop-color: var(--svg-color--671df4, #671DF4);
}

.p8d75mbdl {
  stop-color: var(--svg-color--668656, #668656);
}

.phvt2rban {
  stop-color: var(--svg-color--a75ee1, #A75EE1);
}

.psdz3c18e {
  stop-color: var(--svg-color--a76ddd, #A76DDD);
  stop-opacity: 0;
}

.ptr6_pbgw {
  stop-color: var(--svg-color--6638c0, #6638C0);
}

.pwlp4sbzy {
  stop-color: var(--svg-color--97b74e, #97B74E);
  stop-opacity: 0;
}

.q_ej8bbvk {
  stop-color: var(--svg-color--9a4bff, #9A4BFF);
}

.qblt4li6u {
  d: path("M17.136 14.138a3.184 3.184 0 0 0 4.009-2.341a.885.885 0 0 0-.612-1.048a3.184 3.184 0 0 0-4.009 2.342c-.108.45.166.92.612 1.047");
}

.qj9l8uo4u {
  stop-color: var(--svg-color--460cd2, #460CD2);
}

.qqolyab8d {
  stop-color: var(--svg-color--7726ef, #7726EF);
  stop-opacity: 0;
}

.qvd_ohbrm {
  stop-color: var(--svg-color--5d1dcc, #5D1DCC);
}

.r0pofkanr {
  d: path("m4.332 20.835l17.179 8.821s-1.466-4.68-7.247-7.652s-9.932-1.169-9.932-1.169");
}

.r56t17k6u {
  stop-color: var(--svg-color--7735ab, #7735AB);
}

.re-s51bov {
  stop-color: var(--svg-color--9241ff, #9241FF);
}

.rgkvw6bct {
  stop-color: var(--svg-color--ab60c9, #AB60C9);
  stop-opacity: 0;
}

.rxy5vs-2k {
  stop-color: var(--svg-color--8534ff, #8534FF);
  stop-opacity: 0;
}

.s26slh_sw {
  stop-color: var(--svg-color--668f14, #668F14);
}

.sdh5vac-y {
  stop-color: var(--svg-color--41137e, #41137E);
  stop-opacity: 0;
}

.sf8ibn16b {
  stop-color: var(--svg-color--621ae5, #621AE5);
}

.sfeqtebzu {
  fill: var(--svg-color--802afc, #802AFC);
  fill-rule: evenodd;
  d: path("M18.344 7.878c.253-.325-.032-.603-.402-.64c-.515-.05-1.37 0-1.906.121c-.441.1-.8.24-1.087.352c-.387.151-.644.252-.8.134c-.166-.125-.137-.495-.1-.966c.025-.302.052-.645.034-.991q-.01-.172-.013-.336c-.016-.51-.03-.974-.312-1.464c-.218-.38-.484-.544-.737-.22L11.32 6.057c-.35.45-.57.958-.663 1.477a3.4 3.4 0 0 0-1.614-.149l-2.74.408c-.408.06-.395.373-.172.75c.289.486.685.725 1.122.99q.142.084.286.176c.293.186.605.331.88.458c.429.2.766.355.793.561c.026.194-.188.369-.51.631a7 7 0 0 0-.84.775a7.2 7.2 0 0 0-1.042 1.6c-.15.34-.048.725.36.665l2.306-.343l-2.206 1.288c-.357.208-.224.49.128.752c.455.338.917.41 1.426.489q.164.025.334.054c.345.062.691.077.996.091c.476.022.85.039.955.218c.098.168-.034.409-.234.77a7 7 0 0 0-.487 1.027a7 7 0 0 0-.358 1.86c-.009.368.233.683.59.474l1.68-.98l-1.209 1.553c-.253.325.033.603.402.64c.515.05 1.37 0 1.906-.12c.441-.1.8-.24 1.088-.353c.386-.15.643-.252.8-.134c.166.125.136.495.099.967a7 7 0 0 0-.033.99q.009.172.013.336c.015.511.03.974.311 1.465c.218.378.484.544.737.218l1.701-2.186a3.36 3.36 0 0 0 .71-1.882l.112-.065a3.36 3.36 0 0 0 1.988.305l2.741-.407c.408-.06.394-.374.171-.75c-.289-.486-.685-.726-1.122-.99q-.142-.085-.286-.176a7 7 0 0 0-.88-.459c-.428-.198-.765-.355-.793-.56c-.025-.194.189-.37.51-.631c.24-.196.538-.44.841-.775a7.2 7.2 0 0 0 1.042-1.601c.149-.34.047-.724-.36-.664l-1.948.29l1.541-.9c.357-.209.202-.575-.123-.747a7 7 0 0 0-1.796-.603a7 7 0 0 0-1.134-.08c-.412-.003-.687-.006-.786-.174c-.104-.18.065-.514.28-.939a8 8 0 0 0 .41-.912q.058-.164.117-.318c.181-.482.346-.92.275-1.482c-.055-.435-.236-.69-.593-.48l-2.128 1.242zm-4.24 6.939l1.127-.659a3.32 3.32 0 0 1 .212-3.114a3.43 3.43 0 0 1-2.637.17a3.43 3.43 0 0 1-1.51 2.256a3.32 3.32 0 0 1 2.808 1.347m4.137 1.27l-.002-.004h.006z");
}

.skehobcwt {
  stop-color: var(--svg-color--6e9055, #6E9055);
}

.slmbt8fak {
  stop-color: var(--svg-color--c690ff, #C690FF);
}

.st80wfikg {
  stop-color: var(--svg-color--b163ea, #B163EA);
  stop-opacity: 0;
}

.svruvo2lc {
  stop-color: var(--svg-color--d08bff, #D08BFF);
}

.sy0t_8d-w {
  stop-color: var(--svg-color--934ee8, #934EE8);
}

.t_6959aeo {
  stop-color: var(--svg-color--9d4aff, #9D4AFF);
}

.t18-i7h_v {
  stop-color: var(--svg-color--7f2afa, #7F2AFA);
  stop-opacity: 0;
}

.t5pe4nbwg {
  d: path("M13.412 9.785c1.858-.2 3.13-1.836 2.841-3.653a.89.89 0 0 0-.972-.732c-1.858.2-3.13 1.835-2.842 3.653a.89.89 0 0 0 .973.732");
}

.t71f6kbpu {
  stop-color: var(--svg-color--a456ff, #A456FF);
}

.td7mgg75w {
  stop-color: var(--svg-color--e8a9ff, #E8A9FF);
}

.thu3phbnv {
  stop-color: var(--svg-color--8cb640, #8CB640);
}

.tljvg2s1j {
  stop-color: var(--svg-color--9a62f2, #9A62F2);
}

.tr6ybwbrh {
  stop-color: var(--svg-color--8eba38, #8EBA38);
  stop-opacity: 0;
}

.ts48tfbny {
  stop-color: var(--svg-color--c288ff, #C288FF);
  stop-opacity: 0;
}

.ud7c6qb1s {
  stop-color: var(--svg-color--c188ff, #C188FF);
  stop-opacity: 0;
}

.ukia4q36v {
  stop-color: var(--svg-color--863cbb, #863CBB);
  stop-opacity: 0;
}

.upbv48bda {
  stop-color: var(--svg-color--87b13c, #87B13C);
}

.uqrk6isha {
  stop-color: var(--svg-color--d592ff, #D592FF);
  stop-opacity: 0;
}

.uultnxbbr {
  stop-color: var(--svg-color--6638c0, #6638C0);
  stop-opacity: 0;
}

.uw_gacbhb {
  stop-color: var(--svg-color--97b74e, #97B74E);
}

.uxbj02bsu {
  stop-color: var(--svg-color--a6d660, #A6D660);
}

.vei0avbyj {
  stop-color: var(--svg-color--ac69ff, #AC69FF);
}

.vk4gb2c7w {
  stop-color: var(--svg-color--681ff9, #681FF9);
}

.vlgt4rb_q {
  stop-color: var(--svg-color--5b3379, #5B3379);
}

.vpryp5v6i {
  stop-color: var(--svg-color--537a1a, #537A1A);
}

.vsi3lxb3v {
  d: path("M19.073 19.163c.413.706.162 1.621-.56 2.043s-1.644.192-2.057-.515c-.412-.707-.161-1.622.561-2.044s1.644-.191 2.056.516");
}

.w_yegrjfk {
  stop-color: var(--svg-color--a65ef4, #A65EF4);
  stop-opacity: 0;
}

.w2e94jb9c {
  stop-color: var(--svg-color--5216be, #5216BE);
}

.wbdgc8bbj {
  stop-color: var(--svg-color--5b3379, #5B3379);
  stop-opacity: 0;
}

.wiaq39fhw {
  stop-color: var(--svg-color--869750, #869750);
}

.x_qx6sczp {
  stop-color: var(--svg-color--8eba38, #8EBA38);
}

.x3___2b4g {
  stop-color: var(--svg-color--4b1998, #4B1998);
}

.xb93ataev {
  stop-color: var(--svg-color--a75ee1, #A75EE1);
  stop-opacity: 0;
}

.xjhdaybsu {
  stop-color: var(--svg-color--ae68ea, #AE68EA);
}

.xtxia1bse {
  stop-color: var(--svg-color--8a5ec5, #8A5EC5);
  stop-opacity: 0;
}

.xuvsu-_8n {
  stop-color: var(--svg-color--671df4, #671DF4);
  stop-opacity: 0;
}

.xxfgtybcl {
  stop-color: var(--svg-color--ad6af5, #AD6AF5);
  stop-opacity: 0;
}

.y_p3j19sj {
  stop-color: var(--svg-color--571da3, #571DA3);
}

.y70gp9buj {
  stop-color: var(--svg-color--7526f2, #7526F2);
  stop-opacity: 0;
}

.ygaqz8yxp {
  stop-color: var(--svg-color--de9dff, #DE9DFF);
}

.yi339pefe {
  stop-color: var(--svg-color--41137e, #41137E);
}

.yj0oogb7d {
  stop-color: var(--svg-color--7846ce, #7846CE);
}

.ytc6wlbsd {
  stop-color: var(--svg-color--8f5eff, #8F5EFF);
  stop-opacity: 0;
}

.yx3w6wbqh {
  stop-color: var(--svg-color--637e5f, #637E5F);
}

.z0o2_9bqb {
  fill: var(--svg-color--522699, #522699);
  d: path("M17.136 14.138a3.184 3.184 0 0 0 4.009-2.341a.885.885 0 0 0-.612-1.048a3.184 3.184 0 0 0-4.009 2.342c-.108.45.166.92.612 1.047");
}

.z51m5gb8k {
  stop-color: var(--svg-color--c188ff, #C188FF);
}

.zbjkuhbbg {
  stop-color: var(--svg-color--623676, #623676);
  stop-opacity: 0;
}

.zif_sdbfi {
  stop-color: var(--svg-color--9a62f2, #9A62F2);
  stop-opacity: 0;
}

.zk8zs5jmn {
  stop-color: var(--svg-color--86af38, #86AF38);
  stop-opacity: 0;
}

</style>
