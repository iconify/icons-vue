<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iO80ZYc)"><rect fill="url(#iP2qgob)" class="q91h-m1_i"/></g><rect fill="url(#iSInf8d)" class="q91h-m1_i"/><g filter="url(#i7lJRVd)"><path stroke="url(#iFq5pCu)" class="uz2_4t-2g"/></g><g filter="url(#i99B3hd)"><path fill="url(#iHooS3c)" class="jvxl-bbuf"/></g><path fill="url(#iC5jyqO)" class="jvxl-bbuf"/><path fill="url(#iwE5oZv)" class="jvxl-bbuf"/><path fill="url(#inDh8te)" class="jvxl-bbuf"/><g filter="url(#iC5BmSW)"><path fill="url(#i5kd1hb)" class="jj3ou0kae"/></g><g filter="url(#i2MBJ5d)"><path fill="url(#ihrJafb)" class="ok_tlnscx"/></g><path fill="url(#ij7cTkd)" class="ok_tlnscx"/><g filter="url(#isCqbgd)"><path fill="url(#iIYXETb)" class="tigsvdbfs"/></g><path fill="url(#igEEMjb)" class="tigsvdbfs"/><g filter="url(#iV8COoe)"><path fill="url(#ixp3vAW)" class="q6ue3ccyt"/></g><path fill="url(#iV804zo)" class="u1h0atohp"/><path fill="url(#ikHcnQc)" class="u1h0atohp"/><path fill="url(#iDLfjVL)" class="gopv8m8sx"/><path fill="url(#iB5Bard)" class="gopv8m8sx"/><path fill="url(#i0JlXJd)" class="p-lg627vs"/><path fill="url(#iPjoHJb)" class="p-lg627vs"/><path fill="url(#iWFcpjc)" class="pgi6bacvr"/><path fill="url(#i9C0oMc)" class="pgi6bacvr"/><path fill="url(#iaSPbmk)" class="rqhxevh5t"/><path fill="url(#izvFFGd)" class="rqhxevh5t"/><path fill="url(#i3uHbfp)" class="abqng1bxf"/><path fill="url(#i0iLz4d)" class="abqng1bxf"/><g filter="url(#iXPh7nE)"><path fill="url(#i2dXRQO)" class="g6e17moar"/><path fill="url(#ij3OBGe)" class="g6e17moar"/><path fill="url(#i5Wwgjt)" class="g6e17moar"/><path fill="url(#iRjRazc)" class="g6e17moar"/></g><g filter="url(#iL29Kye)"><path fill="url(#iJO2NAd)" class="yb-zk_8qn"/></g><g filter="url(#iWNz3Sd)"><path fill="url(#ik0iEWi)" class="qbp77ac3d"/><path fill="url(#iBUNcGb)" class="qbp77ac3d"/></g><g filter="url(#iBDLPkQ)"><path fill="url(#iLHOv9d)" class="vxaz9wb7l"/></g><path fill="url(#iLEuf4E)" class="vxaz9wb7l"/><path fill="url(#ikPfcVo)" class="vxaz9wb7l"/><path fill="url(#i8e4OHe)" class="qga48384p"/><path fill="url(#iPYEqca)" class="qga48384p"/><path fill="url(#iD9Y2Rb)" class="qga48384p"/><path fill="url(#ikyTI0b)" class="qga48384p"/><path fill="url(#iIzdFob)" class="b2dx6pbop"/><path fill="url(#ihGSQOd)" class="b2dx6pbop"/><path fill="url(#ixCxhMe)" class="b2dx6pbop"/><path fill="url(#iy5W33I)" class="b2dx6pbop"/><path fill="url(#isrQOnb)" class="d1np5kbud"/><path fill="url(#iMBOYzd)" class="d1np5kbud"/><g filter="url(#iVKTE3d)"><path stroke="url(#iTvFswx)" class="d0z0t1bim"/></g><defs><linearGradient id="iP2qgob" x1="15.998" x2="15.998" y1="1.978" y2="23.353" gradientUnits="userSpaceOnUse"><stop class="alj3iu22y"/><stop offset="1" class="ozmr9l-gb"/><stop offset="1" class="h4z9fdbjq"/></linearGradient><linearGradient id="iHooS3c" x1="2.936" x2="28.373" y1="26.728" y2="26.728" gradientUnits="userSpaceOnUse"><stop class="okn7h-m0l"/><stop offset="1" class="qype44o0t"/></linearGradient><linearGradient id="inDh8te" x1="30.382" x2="27.21" y1="25.076" y2="25.076" gradientUnits="userSpaceOnUse"><stop class="ohguyhb8j"/><stop offset="1" class="yyvmppb4x"/></linearGradient><linearGradient id="i5kd1hb" x1="7.316" x2="21.851" y1="28.946" y2="28.946" gradientUnits="userSpaceOnUse"><stop class="fp_ewyb6g"/><stop offset=".471" class="zbsgpw22f"/><stop offset=".949" class="fp_ewyb6g"/></linearGradient><linearGradient id="ihrJafb" x1="5.877" x2="10.813" y1="27.478" y2="27.478" gradientUnits="userSpaceOnUse"><stop class="j4nt61bhz"/><stop offset="1" class="zn8ah5bor"/></linearGradient><linearGradient id="iIYXETb" x1="20.998" x2="26.813" y1="27.478" y2="27.478" gradientUnits="userSpaceOnUse"><stop class="j4nt61bhz"/><stop offset="1" class="zn8ah5bor"/></linearGradient><linearGradient id="ixp3vAW" x1="9.052" x2="26.787" y1="28.478" y2="28.478" gradientUnits="userSpaceOnUse"><stop class="d4cvybbbo"/><stop offset="1" class="ko2c-bbgt"/></linearGradient><linearGradient id="iV804zo" x1="4.047" x2="5.016" y1="16.913" y2="16.913" gradientUnits="userSpaceOnUse"><stop class="udwi7ebnu"/><stop offset="1" class="it0i-9poh"/></linearGradient><linearGradient id="iDLfjVL" x1="11.031" x2="12" y1="16.913" y2="16.913" gradientUnits="userSpaceOnUse"><stop class="udwi7ebnu"/><stop offset="1" class="it0i-9poh"/></linearGradient><linearGradient id="i0JlXJd" x1="14.031" x2="15" y1="17.251" y2="17.251" gradientUnits="userSpaceOnUse"><stop class="udwi7ebnu"/><stop offset="1" class="it0i-9poh"/></linearGradient><linearGradient id="iWFcpjc" x1="17.031" x2="18" y1="17.251" y2="17.251" gradientUnits="userSpaceOnUse"><stop class="udwi7ebnu"/><stop offset="1" class="it0i-9poh"/></linearGradient><linearGradient id="iaSPbmk" x1="20.031" x2="21" y1="16.939" y2="16.939" gradientUnits="userSpaceOnUse"><stop class="udwi7ebnu"/><stop offset="1" class="it0i-9poh"/></linearGradient><linearGradient id="i3uHbfp" x1="26.98" x2="27.949" y1="16.913" y2="16.913" gradientUnits="userSpaceOnUse"><stop class="udwi7ebnu"/><stop offset="1" class="it0i-9poh"/></linearGradient><linearGradient id="i2dXRQO" x1="12.509" x2="19.865" y1="13.249" y2="13.249" gradientUnits="userSpaceOnUse"><stop class="d6lrezb2f"/><stop offset="1" class="d39v1ub7g"/></linearGradient><linearGradient id="ij3OBGe" x1="23.391" x2="21.868" y1="8.396" y2="11.851" gradientUnits="userSpaceOnUse"><stop class="l6i612b1v"/><stop offset="1" class="r-lfmsbvw"/></linearGradient><linearGradient id="iJO2NAd" x1="25.721" x2="30.62" y1="9.365" y2="13.555" gradientUnits="userSpaceOnUse"><stop class="j-aptt15b"/><stop offset="1" class="i-rt11buu"/></linearGradient><linearGradient id="ik0iEWi" x1="2.438" x2="6.811" y1="13.342" y2="9.728" gradientUnits="userSpaceOnUse"><stop class="wvuis7b2m"/><stop offset="1" class="zvp50jbmn"/></linearGradient><linearGradient id="iLHOv9d" x1="13.947" x2="18.808" y1="9.664" y2="5.046" gradientUnits="userSpaceOnUse"><stop class="zm1hxgf7w"/><stop offset="1" class="m4fa0wb5e"/></linearGradient><linearGradient id="i8e4OHe" x1="7.03" x2="9.018" y1="14.11" y2="14.11" gradientUnits="userSpaceOnUse"><stop offset=".229" class="umerbsb-c"/><stop offset=".849" class="mfxn3hoxy"/></linearGradient><linearGradient id="iPYEqca" x1="6.313" x2="7.606" y1="16.879" y2="16.879" gradientUnits="userSpaceOnUse"><stop class="h79ctimmt"/><stop offset="1" class="ua7he-b8p"/></linearGradient><linearGradient id="iIzdFob" x1="22.978" x2="24.966" y1="14.11" y2="14.11" gradientUnits="userSpaceOnUse"><stop offset=".229" class="umerbsb-c"/><stop offset=".849" class="mfxn3hoxy"/></linearGradient><linearGradient id="ihGSQOd" x1="22.261" x2="23.554" y1="16.879" y2="16.879" gradientUnits="userSpaceOnUse"><stop class="h79ctimmt"/><stop offset="1" class="ua7he-b8p"/></linearGradient><linearGradient id="isrQOnb" x1="4.565" x2="26.605" y1="19.976" y2="19.976" gradientUnits="userSpaceOnUse"><stop class="vxf1fitfb"/><stop offset="1" class="gw_93kxmw"/></linearGradient><linearGradient id="iMBOYzd" x1="16" x2="16" y1="20.275" y2="19.541" gradientUnits="userSpaceOnUse"><stop class="bckik1b0u"/><stop offset="1" class="pya7srbzo"/></linearGradient><linearGradient id="iTvFswx" x1="28.842" x2="4.092" y1="18.762" y2="18.762" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="nj3s9qb9i"/></linearGradient><radialGradient id="iSInf8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37461 1.8875 -2.06396 -2.5966 29.237 3.272)" gradientUnits="userSpaceOnUse"><stop class="fc6xl4k1i"/><stop offset="1" class="q9tjrbwzt"/></radialGradient><radialGradient id="iFq5pCu" cx="0" cy="0" r="1" gradientTransform="rotate(148.617 14.086 7.833)scale(13.4976 28.6012)" gradientUnits="userSpaceOnUse"><stop class="a0u9zbvpn"/><stop offset="1" class="dltowtbiz"/></radialGradient><radialGradient id="iC5jyqO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41706 0 0 -8.96694 7.304 24.873)" gradientUnits="userSpaceOnUse"><stop class="u-nlirbno"/><stop offset="1" class="xcnhx-bbk"/></radialGradient><radialGradient id="iwE5oZv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26523 0 0 -8.0062 23.33 24.873)" gradientUnits="userSpaceOnUse"><stop class="nyjnbtbvn"/><stop offset="1" class="v6j0164xh"/></radialGradient><radialGradient id="ij7cTkd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2838 -3.79411 4.69119 4.06021 7.587 29.514)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="k3i26nb1s"/><stop offset="1" class="b5a4jnbxo"/></radialGradient><radialGradient id="igEEMjb" cx="0" cy="0" r="1" gradientTransform="matrix(3.2838 -3.79411 4.69119 4.06021 23.587 29.514)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="k3i26nb1s"/><stop offset="1" class="b5a4jnbxo"/></radialGradient><radialGradient id="ikHcnQc" cx="0" cy="0" r="1" gradientTransform="matrix(.625 .75781 -1.45648 1.20122 4.28 13.025)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="lwkae0bsk"/><stop offset="1" class="lom73agzk"/></radialGradient><radialGradient id="iB5Bard" cx="0" cy="0" r="1" gradientTransform="matrix(-.48438 .9375 -1.42765 -.73762 12 13.103)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="lwkae0bsk"/><stop offset="1" class="lom73agzk"/></radialGradient><radialGradient id="iPjoHJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.32609 .875 -1.4936 -.55662 14.842 14.384)" gradientUnits="userSpaceOnUse"><stop offset=".4" class="lwkae0bsk"/><stop offset="1" class="lom73agzk"/></radialGradient><radialGradient id="i9C0oMc" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .75 -1.28023 .66679 17.28 14.369)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="lwkae0bsk"/><stop offset="1" class="lom73agzk"/></radialGradient><radialGradient id="izvFFGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.48438 .92246 -1.41783 -.7445 21 13.19)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="lwkae0bsk"/><stop offset="1" class="lom73agzk"/></radialGradient><radialGradient id="i0iLz4d" cx="0" cy="0" r="1" gradientTransform="rotate(117.324 9.985 15.061)scale(1.05524 1.60695)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="lwkae0bsk"/><stop offset="1" class="lom73agzk"/></radialGradient><radialGradient id="i5Wwgjt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27852 3.07735 -.67994 -.28249 23.264 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g03qwlikt"/><stop offset="1" class="wng64zbqh"/></radialGradient><radialGradient id="iRjRazc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0812 -.21624 .90681 4.53404 8.858 10.318)" gradientUnits="userSpaceOnUse"><stop class="r74xyh21x"/><stop offset="1" class="vjpgr6bjb"/></radialGradient><radialGradient id="iBUNcGb" cx="0" cy="0" r="1" gradientTransform="rotate(110.416 .406 7.514)scale(3.0227 1.01844)" gradientUnits="userSpaceOnUse"><stop class="wq89lbb9h"/><stop offset="1" class="xovz5wb3m"/></radialGradient><radialGradient id="iLEuf4E" cx="0" cy="0" r="1" gradientTransform="matrix(4.84417 -2.65804 2.81274 5.1261 14.153 7.874)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="s2ob8jbyv"/><stop offset=".985" class="vq8mz-o-g"/></radialGradient><radialGradient id="ikPfcVo" cx="0" cy="0" r="1" gradientTransform="matrix(.31072 -.61348 1.32047 .6688 13.721 7.935)" gradientUnits="userSpaceOnUse"><stop class="rox1ooecz"/><stop offset="1" class="igog3bb6m"/></radialGradient><radialGradient id="iD9Y2Rb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89596 .62501 -.28506 -.86472 8.024 19.666)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="f-1b3sqyj"/><stop offset="1" class="guscp3bzc"/></radialGradient><radialGradient id="ikyTI0b" cx="0" cy="0" r="1" gradientTransform="rotate(135.526 3.13 4.937)scale(.80538 .77596)" gradientUnits="userSpaceOnUse"><stop class="ea-i3pbyu"/><stop offset="1" class="sy7xhjb2q"/></radialGradient><radialGradient id="ixCxhMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89596 .62501 -.28506 -.86472 23.972 19.667)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="f-1b3sqyj"/><stop offset="1" class="guscp3bzc"/></radialGradient><radialGradient id="iy5W33I" cx="0" cy="0" r="1" gradientTransform="rotate(135.526 11.104 8.198)scale(.80538 .77596)" gradientUnits="userSpaceOnUse"><stop class="ea-i3pbyu"/><stop offset="1" class="sy7xhjb2q"/></radialGradient><filter id="iO80ZYc" width="30" height="28" x="1.998" y="1.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.145098 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/></filter><filter id="i7lJRVd" width="26.203" height="25.037" x="4.996" y="1.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8408" stdDeviation="1.25"/></filter><filter id="i99B3hd" width="28" height="8.5" x="1.998" y="21.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".6"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.643137 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.47451 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8408" result="effect2_innerShadow_18_8408"/></filter><filter id="iC5BmSW" width="26.933" height="6.55" x=".696" y="24.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8408" stdDeviation="1"/></filter><filter id="i2MBJ5d" width="6.4" height="3" x="4.798" y="25.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.890196 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.372549 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8408" result="effect2_innerShadow_18_8408"/></filter><filter id="isCqbgd" width="6.4" height="3" x="20.798" y="25.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.890196 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.372549 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8408" result="effect2_innerShadow_18_8408"/></filter><filter id="iV8COoe" width="27.479" height="3.5" x="2.509" y="26.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.752941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.490196 0 0 0 0 0.858824 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_18_8408" result="effect2_innerShadow_18_8408"/></filter><filter id="iXPh7nE" width="15.969" height="8.028" x="8.003" y="6.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.156863 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/></filter><filter id="iL29Kye" width="6.172" height="7.782" x="23.972" y="6.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.223529 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/></filter><filter id="iWNz3Sd" width="5.996" height="7.732" x="1.998" y="6.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.113725 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/></filter><filter id="iBDLPkQ" width="6.196" height="5.863" x="12.952" y="4.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.337255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8408"/></filter><filter id="iVKTE3d" width="27.375" height="2" x="2.092" y="17.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8408" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bridge-at-night" /></template>
<style>
.a0u9zbvpn {
  stop-color: var(--svg-color--736183, #736183);
}

.abqng1bxf {
  d: path("M26.98 12.713h.969v5.844h-.969z");
}

.alj3iu22y {
  stop-color: var(--svg-color--594367, #594367);
}

.b2dx6pbop {
  d: path("M22.978 7.016a.994.994 0 0 1 1.988 0v18.962h-1.988z");
}

.b5a4jnbxo {
  stop-color: var(--svg-color--f4f1f8, #F4F1F8);
}

.bckik1b0u {
  stop-color: var(--svg-color--af3e6d, #AF3E6D);
}

.d0z0t1bim {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M3.092 18.974h25.375");
}

.d1np5kbud {
  d: path("M2.002 17.972h27.996v2.004H2.002z");
}

.d39v1ub7g {
  stop-color: var(--svg-color--ed703f, #ED703F);
}

.d4cvybbbo {
  stop-color: var(--svg-color--6490f5, #6490F5);
}

.d6lrezb2f {
  stop-color: var(--svg-color--ff4c8d, #FF4C8D);
}

.dltowtbiz {
  stop-color: var(--svg-color--736183, #736183);
  stop-opacity: 0;
}

.ea-i3pbyu {
  stop-color: var(--svg-color--ff9e58, #FF9E58);
}

.f-1b3sqyj {
  stop-color: var(--svg-color--b3294f, #B3294F);
}

.fc6xl4k1i {
  stop-color: var(--svg-color--705e80, #705E80);
}

.fp_ewyb6g {
  stop-color: var(--svg-color--416bce, #416BCE);
}

.ft5dv1b6b {
  fill: none;
}

.g03qwlikt {
  stop-color: var(--svg-color--a93723, #A93723);
}

.g6e17moar {
  d: path("M8.003 6.891c0 4.35 3.575 7.878 7.985 7.878s7.984-3.527 7.984-7.878l-.981.024c0 3.783-3.136 6.849-7.003 6.849s-6.98-3.09-6.98-6.873z");
}

.gopv8m8sx {
  d: path("M11.031 12.713H12v5.844h-.969z");
}

.guscp3bzc {
  stop-color: var(--svg-color--b3294f, #B3294F);
  stop-opacity: 0;
}

.gw_93kxmw {
  stop-color: var(--svg-color--ff8043, #FF8043);
}

.h4z9fdbjq {
  stop-color: var(--svg-color--31293a, #31293A);
}

.h79ctimmt {
  stop-color: var(--svg-color--a82553, #A82553);
}

.hhyc553gq {
  stop-color: var(--svg-color--ff9459, #FF9459);
}

.i-rt11buu {
  stop-color: var(--svg-color--ff9046, #FF9046);
}

.igog3bb6m {
  stop-color: var(--svg-color--ffc361, #FFC361);
  stop-opacity: 0;
}

.it0i-9poh {
  stop-color: var(--svg-color--ff954f, #FF954F);
}

.j-aptt15b {
  stop-color: var(--svg-color--ff6995, #FF6995);
}

.j4nt61bhz {
  stop-color: var(--svg-color--9b99a9, #9B99A9);
}

.jj3ou0kae {
  d: path("M5.661 28.946h17.001a3.4 3.4 0 0 0 2.967-1.738c-.335-.064-.57-.199-.815-.341c-.393-.227-.816-.47-1.727-.47c-.91 0-1.334.243-1.726.47c-.34.196-.657.38-1.249.38s-.909-.184-1.249-.38c-.392-.227-.815-.47-1.726-.47s-1.334.243-1.726.47c-.34.196-.657.38-1.25.38c-.637 0-1.062-.213-1.487-.426c-.425-.212-.85-.425-1.487-.425s-1.063.213-1.488.425c-.425.213-.85.425-1.487.425s-1.063-.212-1.488-.425c-.425-.212-.85-.425-1.488-.425c-.637 0-1.062.213-1.487.425c-.32.16-.641.32-1.053.39a3.4 3.4 0 0 0 2.965 1.735");
}

.jvxl-bbuf {
  d: path("M1.998 21.978v4a4 4 0 0 0 4 4h20a4 4 0 0 0 4-3.996v-4.004c-.696 0-1.07.216-1.469.446c-.462.267-.96.554-2.031.554s-1.57-.287-2.03-.554c-.4-.23-.774-.446-1.47-.446c-.75 0-1.25.25-1.75.5s-1 .5-1.75.5s-1.25-.25-1.75-.5s-1-.5-1.75-.5s-1.25.25-1.75.5s-1 .5-1.75.5s-1.25-.25-1.75-.5s-1-.5-1.75-.5s-1.25.25-1.75.5s-1 .5-1.75.5s-1.25-.25-1.75-.5s-1-.5-1.75-.5");
}

.k3i26nb1s {
  stop-color: var(--svg-color--f4f1f8, #F4F1F8);
  stop-opacity: 0;
}

.ko2c-bbgt {
  stop-color: var(--svg-color--6bafff, #6BAFFF);
}

.l6i612b1v {
  stop-color: var(--svg-color--b24f25, #B24F25);
}

.lom73agzk {
  stop-color: var(--svg-color--cc3536, #CC3536);
  stop-opacity: 0;
}

.lwkae0bsk {
  stop-color: var(--svg-color--cc3536, #CC3536);
}

.m4fa0wb5e {
  stop-color: var(--svg-color--f0c651, #F0C651);
}

.mfxn3hoxy {
  stop-color: var(--svg-color--ff954c, #FF954C);
}

.nj3s9qb9i {
  stop-color: var(--svg-color--ff5b97, #FF5B97);
}

.nyjnbtbvn {
  stop-color: var(--svg-color--3e78c9, #3E78C9);
}

.ohguyhb8j {
  stop-color: var(--svg-color--6cc0ff, #6CC0FF);
}

.ok_tlnscx {
  d: path("M4.998 26.978a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2h-6z");
}

.okn7h-m0l {
  stop-color: var(--svg-color--5e85de, #5E85DE);
}

.ozmr9l-gb {
  stop-color: var(--svg-color--31293b, #31293B);
}

.p-lg627vs {
  d: path("M14.031 13.916H15v4.641h-.969z");
}

.pgi6bacvr {
  d: path("M17.031 13.916H18v4.641h-.969z");
}

.pya7srbzo {
  stop-color: var(--svg-color--af3e6d, #AF3E6D);
  stop-opacity: 0;
}

.q6ue3ccyt {
  d: path("M5.997 29.978h20c1.5 0 2.806-.824 3.49-2.045c-.394-.075-.67-.234-.959-.401c-.462-.267-.96-.554-2.03-.554c-1.073 0-1.57.287-2.032.554c-.4.23-.773.446-1.469.446s-1.07-.215-1.469-.446c-.462-.267-.96-.554-2.03-.554c-1.073 0-1.57.287-2.032.554c-.4.23-.773.446-1.469.446c-.75 0-1.25-.25-1.75-.5s-1-.5-1.75-.5s-1.25.25-1.75.5s-1 .5-1.75.5s-1.25-.25-1.75-.5s-1-.5-1.75-.5s-1.25.25-1.75.5c-.377.189-.754.377-1.238.459a4 4 0 0 0 3.488 2.041");
}

.q91h-m1_i {
  width: 28px;
  height: 28px;
  x: 1.998px;
  y: 1.978px;
  rx: 4px;
}

.q9tjrbwzt {
  stop-color: var(--svg-color--705e80, #705E80);
  stop-opacity: 0;
}

.qbp77ac3d {
  d: path("M1.998 13.481c2.893-.844 5.053-3.483 5.053-6.59h.944c0 3.674-2.55 6.76-5.997 7.632z");
}

.qga48384p {
  d: path("M7.03 7.016a.994.994 0 0 1 1.988 0v18.962H7.03z");
}

.qype44o0t {
  stop-color: var(--svg-color--6abcff, #6ABCFF);
}

.r-lfmsbvw {
  stop-color: var(--svg-color--b24f25, #B24F25);
  stop-opacity: 0;
}

.r74xyh21x {
  stop-color: var(--svg-color--c31749, #C31749);
}

.rox1ooecz {
  stop-color: var(--svg-color--ffc361, #FFC361);
}

.rqhxevh5t {
  d: path("M20.031 12.806H21v5.75h-.969z");
}

.s2ob8jbyv {
  stop-color: var(--svg-color--ffff80, #FFFF80);
  stop-opacity: 0;
}

.sy7xhjb2q {
  stop-color: var(--svg-color--ff9e58, #FF9E58);
  stop-opacity: 0;
}

.tigsvdbfs {
  d: path("M20.998 26.978a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2h-6z");
}

.u-nlirbno {
  stop-color: var(--svg-color--385db9, #385DB9);
}

.u1h0atohp {
  d: path("M4.047 12.713h.969v5.844h-.969z");
}

.ua7he-b8p {
  stop-color: var(--svg-color--a82553, #A82553);
  stop-opacity: 0;
}

.udwi7ebnu {
  stop-color: var(--svg-color--d72e54, #D72E54);
}

.umerbsb-c {
  stop-color: var(--svg-color--d33d68, #D33D68);
}

.uz2_4t-2g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.496 4.26h18.453a2 2 0 0 1 2 2v17.286");
}

.v6j0164xh {
  stop-color: var(--svg-color--3e78c9, #3E78C9);
  stop-opacity: 0;
}

.vjpgr6bjb {
  stop-color: var(--svg-color--c31749, #C31749);
  stop-opacity: 0;
}

.vq8mz-o-g {
  stop-color: var(--svg-color--ffff80, #FFFF80);
}

.vxaz9wb7l {
  d: path("M14.417 8.366a3.207 3.207 0 0 0 3.207-3.207a2.8 2.8 0 0 0-.094-.735c-.033-.133.112-.212.215-.133c.768.586 1.252 1.435 1.252 2.475a3.207 3.207 0 0 1-6.03 1.522c-.061-.114.068-.232.188-.18c.387.166.814.258 1.262.258");
}

.vxf1fitfb {
  stop-color: var(--svg-color--ee3384, #EE3384);
}

.wng64zbqh {
  stop-color: var(--svg-color--a93723, #A93723);
  stop-opacity: 0;
}

.wq89lbb9h {
  stop-color: var(--svg-color--962e1e, #962E1E);
}

.wvuis7b2m {
  stop-color: var(--svg-color--ea3986, #EA3986);
}

.xcnhx-bbk {
  stop-color: var(--svg-color--385db9, #385DB9);
  stop-opacity: 0;
}

.xovz5wb3m {
  stop-color: var(--svg-color--962e1e, #962E1E);
  stop-opacity: 0;
}

.yb-zk_8qn {
  d: path("M29.994 13.481c-2.905-.844-5.043-3.483-5.043-6.59h-.979c0 3.674 2.56 6.76 6.022 7.632z");
}

.yyvmppb4x {
  stop-color: var(--svg-color--6cc0ff, #6CC0FF);
  stop-opacity: 0;
}

.zbsgpw22f {
  stop-color: var(--svg-color--416bce, #416BCE);
  stop-opacity: 0;
}

.zm1hxgf7w {
  stop-color: var(--svg-color--fbb15a, #FBB15A);
}

.zn8ah5bor {
  stop-color: var(--svg-color--cdc4db, #CDC4DB);
}

.zvp50jbmn {
  stop-color: var(--svg-color--b65335, #B65335);
}

</style>
