<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iPQsKjb)" class="d_oc3pb6h"/><g filter="url(#iY8yoDc)"><path fill="url(#id0TQgc)" class="vh89mvbib"/></g><g filter="url(#ipeFSJp)"><path fill="url(#igjxjww)" class="xyx6-34by"/><path fill="url(#i9QKiJA)" class="xyx6-34by"/></g><g filter="url(#il9WrPO)"><path class="uhc_xg1rw"/><path fill="url(#im8MDuc)" class="te9ep8bjm"/><path fill="url(#iZo4Fhb)" class="te9ep8bjm"/></g><g filter="url(#iQF0olb)"><path fill="url(#iujP4Dd)" class="dqavq1bhu"/><path fill="url(#irQvmlb)" class="dqavq1bhu"/><path fill="url(#iZSvrPb)" class="dqavq1bhu"/><path fill="url(#iMvqBTd)" class="dqavq1bhu"/></g><path fill="url(#i1Bnxuc)" class="dqavq1bhu"/><path fill="url(#iq9IAAc)" class="dqavq1bhu"/><path fill="url(#igFcyXb)" class="dqavq1bhu"/><path fill="url(#i2vfgye)" class="dqavq1bhu"/><path class="ae5uxccgh"/><g filter="url(#iqfTJnb)"><path class="fmub3_f3z"/></g><g filter="url(#iODgqtb)"><path stroke="url(#ighOFac)" class="w-tiexbfy"/></g><g filter="url(#izUJoRc)"><path class="fixr86nla"/></g><g filter="url(#ixceqVv)"><path stroke="url(#iEvoqAe)" class="h8wc_ig9r"/></g><g filter="url(#iWdjrDW)"><path class="tw1jqobsd"/><path fill="url(#in4su0c)" class="ht4oiqb3k"/><path fill="url(#iXdtF0d)" class="ht4oiqb3k"/></g><path fill="url(#iRThhwe)" class="ht4oiqb3k"/><path fill="url(#irCb4jd)" class="ht4oiqb3k"/><path fill="url(#i3LpcCs)" class="ht4oiqb3k"/><path fill="url(#ibnxkcd)" class="ht4oiqb3k"/><path fill="url(#isPJEXb)" class="ht4oiqb3k"/><path fill="url(#ioY36xe)" class="ht4oiqb3k"/><path fill="url(#i4nCyEd)" class="ht4oiqb3k"/><g filter="url(#ioouCcb)"><path class="et4utnb5g"/></g><g filter="url(#ipjgoPd)"><path class="y7wk7mwbz"/><path fill="url(#itSpnAc)" class="xs67m9lfd"/><path fill="url(#i1Trztd)" class="xs67m9lfd"/><path fill="url(#ipELvPb)" class="xs67m9lfd"/></g><path fill="url(#iCdAE9x)" class="xs67m9lfd"/><path class="bmkwn9qqq"/><path fill="url(#icViUZb)" class="jnsjuwjrr"/><path class="bxu4qezaz"/><g filter="url(#isCzzFb)"><path class="zrnpsc2lb"/><path fill="url(#ioHKjre)" class="ou0xmdboy"/></g><g filter="url(#iZN4zSc)"><path fill="url(#iGk0xPc)" class="cvp-8abvz"/></g><path class="pqi7xt6xb"/><path fill="url(#iA2tZjc)" class="no2a_zbhx"/><path class="fv1g4xboo"/><g filter="url(#izd1dne)"><path fill="url(#ic2ptzb)" class="g4c1labol"/></g><g filter="url(#i4MgBqp)"><ellipse transform="rotate(-27.914 11.039 16.972)" class="ryzsubbkp"/><ellipse fill="url(#iMwe9sd)" transform="rotate(-27.914 11.039 16.972)" class="k_eg2bc7t"/></g><g filter="url(#iGclYRb)"><path fill="url(#iJYgMVc)" class="sd5-q37vo"/><path fill="url(#iS2MpId)" class="sd5-q37vo"/><path fill="url(#i1eHCSy)" class="sd5-q37vo"/></g><g filter="url(#iseAQee)"><path stroke="url(#iyeqtKe)" class="e6dh-03sc"/></g><defs><radialGradient id="iPQsKjb" cx="0" cy="0" r="1" gradientTransform="matrix(3.41626 0 0 5.97849 2.99 17.759)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="i9QKiJA" cx="0" cy="0" r="1" gradientTransform="matrix(1.60937 -1.17187 1.33754 1.8369 26.484 17.243)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="im8MDuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -3.21875 1.88395 1.02428 25.672 19.509)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iZo4Fhb" cx="0" cy="0" r="1" gradientTransform="matrix(.55251 .5469 -.70503 .71226 25.76 17.759)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iujP4Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.25009 7.91165 -8.96041 -17.27163 22.938 16.972)" gradientUnits="userSpaceOnUse"><stop class="fn-t2vbtn"/><stop offset=".726" class="tdjnlb1gn"/><stop offset="1" class="c1x3tsp4e"/></radialGradient><radialGradient id="irQvmlb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.75 0 0 -6.04833 19.75 18.321)" gradientUnits="userSpaceOnUse"><stop class="lp846hbmw"/><stop offset="1" class="mow2ajbvq"/></radialGradient><radialGradient id="iZSvrPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78125 3.62405 0 20.906 16.353)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="wtbp23h1x"/><stop offset="1" class="ecu1mobnq"/></radialGradient><radialGradient id="iMvqBTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.83828 2.73811 0 12.313 16.972)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="dwya1gbte"/><stop offset="1" class="dw4852bji"/></radialGradient><radialGradient id="i1Bnxuc" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 3.1875 -1.89485 2.21066 14.344 8.665)" gradientUnits="userSpaceOnUse"><stop offset=".015" class="n_hoeqbdx"/><stop offset="1" class="c7l_a1b7z"/></radialGradient><radialGradient id="iq9IAAc" cx="0" cy="0" r="1" gradientTransform="rotate(42.842 -7.073 15.919)scale(3.81445 1.99642)" gradientUnits="userSpaceOnUse"><stop class="n_hoeqbdx"/><stop offset="1" class="c7l_a1b7z"/></radialGradient><radialGradient id="igFcyXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87501 15.68754 -17.76526 -2.12335 17.438 15.071)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="fynezkbik"/><stop offset="1" class="ptlmjm6ef"/></radialGradient><radialGradient id="i2vfgye" cx="0" cy="0" r="1" gradientTransform="matrix(-.54687 .9375 -2.00105 -1.16726 10.594 11.103)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="rxjfyob9j"/><stop offset="1" class="qr4efnb1f"/></radialGradient><radialGradient id="in4su0c" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -7 8.16731 .51045 5.75 16.696)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="n32mfvwve"/><stop offset="1" class="t24p8qb2e"/></radialGradient><radialGradient id="iXdtF0d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.87498 7.56252 -19.20532 -14.91974 25.5 4.571)" gradientUnits="userSpaceOnUse"><stop class="pddl9kbtn"/><stop offset="1" class="kovmn0bpr"/></radialGradient><radialGradient id="iRThhwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53126 -3.375 1.86554 -1.39916 12.531 12.071)" gradientUnits="userSpaceOnUse"><stop class="cljbb3w0c"/><stop offset="1" class="d5tjgmbpj"/></radialGradient><radialGradient id="irCb4jd" cx="0" cy="0" r="1" gradientTransform="rotate(-114.58 10.127 1.095)scale(3.86816 .7011)" gradientUnits="userSpaceOnUse"><stop class="zrulh6btb"/><stop offset="1" class="wsvwr-55a"/></radialGradient><radialGradient id="i3LpcCs" cx="0" cy="0" r="1" gradientTransform="rotate(108.277 -.23 7.608)scale(1.79361 .5322)" gradientUnits="userSpaceOnUse"><stop class="cymhb9bnr"/><stop offset="1" class="cx9z25cuz"/></radialGradient><radialGradient id="ibnxkcd" cx="0" cy="0" r="1" gradientTransform="matrix(3.46875 -1.3001 .60745 1.6207 18.625 2.028)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="jtysutbfx"/><stop offset="1" class="giiyytb7x"/></radialGradient><radialGradient id="isPJEXb" cx="0" cy="0" r="1" gradientTransform="rotate(-33.302 9.89 -8.653)scale(10.2449 4.19799)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="ecc2hesmm"/><stop offset="1" class="xlyb0nb-w"/></radialGradient><radialGradient id="ioY36xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.67187 1.73438 0 27.25 17.071)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="cr57gbc8g"/><stop offset="1" class="x0qjlacpe"/></radialGradient><radialGradient id="i4nCyEd" cx="0" cy="0" r="1" gradientTransform="rotate(119.814 7.22 5.819)scale(1.60276 2.07887)" gradientUnits="userSpaceOnUse"><stop class="efobfd6qd"/><stop offset="1" class="h-bkq0ben"/></radialGradient><radialGradient id="iCdAE9x" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28125 -2.74 0 15.99 18.853)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="u4h591ezq"/><stop offset="1" class="xl4q7gbwl"/></radialGradient><radialGradient id="icViUZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80763 -2.87524 0 20.326 17.18)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="tlhq_eb6r"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/></radialGradient><radialGradient id="ioHKjre" cx="0" cy="0" r="1" gradientTransform="matrix(-.51672 -.66586 .91673 -.7114 19.817 17.366)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iA2tZjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80073 -2.86427 0 11.64 17.185)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="tlhq_eb6r"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/></radialGradient><radialGradient id="iMwe9sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01717 -1.09657 1.31812 -.02064 11.005 17.671)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJYgMVc" cx="0" cy="0" r="1" gradientTransform="rotate(162.306 11.773 4.558)scale(10.6933 18.7067)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="io344do_p"/><stop offset="1" class="x-2--yzhu"/></radialGradient><radialGradient id="iS2MpId" cx="0" cy="0" r="1" gradientTransform="matrix(-3.06252 6.06249 -11.37448 -5.74591 21.563 5.509)" gradientUnits="userSpaceOnUse"><stop class="g6vud3bdk"/><stop offset="1" class="a5shsxbpl"/></radialGradient><radialGradient id="i1eHCSy" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 -6.875 14.85244 6.076 19.875 12.071)" gradientUnits="userSpaceOnUse"><stop offset=".849" class="erudflbej"/><stop offset="1" class="t1i8-m29x"/></radialGradient><filter id="iY8yoDc" width="5.24" height="5.24" x="3.62" y="15.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".25"/></filter><filter id="ipeFSJp" width="6.75" height="6.75" x="22.51" y="14.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3652"/></filter><filter id="il9WrPO" width="5.24" height="5.24" x="23.14" y="15.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".25"/></filter><filter id="iQF0olb" width="21.5" height="26" x="5.74" y="3.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.623529 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3652"/></filter><filter id="iqfTJnb" width="3.67" height="1.492" x="8.93" y="13.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.239216 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3652"/></filter><filter id="iODgqtb" width="3.37" height="1.192" x="8.98" y="13.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".15"/></filter><filter id="izUJoRc" width="3.67" height="1.492" x="19.03" y="13.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.239216 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3652"/></filter><filter id="ixceqVv" width="3.37" height="1.192" x="19.08" y="13.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".15"/></filter><filter id="iWdjrDW" width="24.099" height="16.983" x="4.676" y="1.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.498039 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3652"/></filter><filter id="ioouCcb" width="4.335" height="5.078" x="13.425" y="17.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".25"/></filter><filter id="ipjgoPd" width="3.997" height="5.016" x="13.992" y="17.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".125"/></filter><filter id="isCzzFb" width="1.507" height="1.306" x="18.813" y="16.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".05"/></filter><filter id="iZN4zSc" width="1.494" height="1.544" x="20.807" y="16.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".1"/></filter><filter id="izd1dne" width="1.701" height="1.821" x="11.944" y="16.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".1"/></filter><filter id="i4MgBqp" width="1.783" height="1.32" x="10.147" y="16.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".05"/></filter><filter id="iGclYRb" width="18.25" height="11.289" x="10.039" y="2.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".5"/></filter><filter id="iseAQee" width="1.822" height="3.07" x="11.457" y="6.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3652" stdDeviation=".125"/></filter><linearGradient id="id0TQgc" x1="6.24" x2="4.875" y1="18.353" y2="18.353" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="igjxjww" x1="27.875" x2="26.281" y1="15.634" y2="20.571" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="ighOFac" x1="11.656" x2="9.203" y1="13.955" y2="14.384" gradientUnits="userSpaceOnUse"><stop class="yag6w7bgr"/><stop offset="1" class="ekpe4jiwg"/></linearGradient><linearGradient id="iEvoqAe" x1="21.756" x2="19.303" y1="13.955" y2="14.384" gradientUnits="userSpaceOnUse"><stop class="yag6w7bgr"/><stop offset="1" class="ekpe4jiwg"/></linearGradient><linearGradient id="itSpnAc" x1="17.738" x2="15.672" y1="20.462" y2="20.712" gradientUnits="userSpaceOnUse"><stop class="gqhi1ccoz"/><stop offset="1" class="br6f00bnt"/></linearGradient><linearGradient id="i1Trztd" x1="14" x2="15.625" y1="20.853" y2="21.103" gradientUnits="userSpaceOnUse"><stop class="jmo7hmb8n"/><stop offset="1" class="n3ahwtbnh"/></linearGradient><linearGradient id="ipELvPb" x1="15.99" x2="15.99" y1="22.118" y2="20.618" gradientUnits="userSpaceOnUse"><stop class="u7wna2bwt"/><stop offset="1" class="tylp9fbgl"/></linearGradient><linearGradient id="iGk0xPc" x1="22.059" x2="21.36" y1="17.299" y2="17.73" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic2ptzb" x1="13.292" x2="12.595" y1="17.304" y2="17.733" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyeqtKe" x1="11.5" x2="12.75" y1="6.851" y2="9.398" gradientUnits="userSpaceOnUse"><stop class="g02s8lqle"/><stop offset="1" class="bddhnbbar"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:boy" /></template>
<style>
.a5shsxbpl {
  stop-color: var(--svg-color--ffe632, #FFE632);
  stop-opacity: 0;
}

.ae5uxccgh {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.992 23.183a6.5 6.5 0 0 1-3.016-.733a.328.328 0 0 0-.429.472a4.1 4.1 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.18-.281-.13-.623-.43-.472a6.35 6.35 0 0 1-3.015.733");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bddhnbbar {
  stop-color: var(--svg-color--dc9228, #DC9228);
  stop-opacity: 0;
}

.bmkwn9qqq {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.791 15.51a3.11 3.11 0 0 1 3.02 2.36a.61.61 0 0 1-.597.759h-4.971a.513.513 0 0 1-.507-.606a3.114 3.114 0 0 1 3.055-2.512");
}

.br6f00bnt {
  stop-color: var(--svg-color--ffe83c, #FFE83C);
  stop-opacity: 0;
}

.bxu4qezaz {
  fill: var(--svg-color--000, #000);
  d: path("M19.192 18.105c0-.633.506-1.14 1.138-1.14c.633 0 1.14.507 1.14 1.14c0 .19-.046.37-.127.524h-2.016a1.03 1.03 0 0 1-.136-.524");
}

.c1x3tsp4e {
  stop-color: var(--svg-color--da8140, #DA8140);
}

.c7l_a1b7z {
  stop-color: var(--svg-color--e26e13, #E26E13);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cljbb3w0c {
  stop-color: var(--svg-color--ffc12f, #FFC12F);
}

.cr57gbc8g {
  stop-color: var(--svg-color--ffcf32, #FFCF32);
}

.cvp-8abvz {
  d: path("M22.102 17.843a1.87 1.87 0 0 0-.516-1.031l-.579.635l.261.509z");
}

.cx9z25cuz {
  stop-color: var(--svg-color--ffac26, #FFAC26);
  stop-opacity: 0;
}

.cymhb9bnr {
  stop-color: var(--svg-color--ffac26, #FFAC26);
}

.d_oc3pb6h {
  d: path("M6.24 21.009a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.d5tjgmbpj {
  stop-color: var(--svg-color--ffc12f, #FFC12F);
  stop-opacity: 0;
}

.dqavq1bhu {
  d: path("M13.386 3.972c-4.343 0-7.819 3.632-7.64 7.993l.28 8.224c.239 5.852 4.63 9.783 9.969 9.783s9.73-3.931 9.97-9.783l.083-4.131l.185-4.093c.18-4.361-3.296-7.993-7.639-7.993z");
}

.dw4852bji {
  stop-color: var(--svg-color--ed9228, #ED9228);
  stop-opacity: 0;
}

.dwya1gbte {
  stop-color: var(--svg-color--ed9228, #ED9228);
}

.e6dh-03sc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.782 6.71c.046.365.35 1.378 1.187 2.516");
}

.ecc2hesmm {
  stop-color: var(--svg-color--c79b39, #C79B39);
}

.ecu1mobnq {
  stop-color: var(--svg-color--ffbe28, #FFBE28);
  stop-opacity: 0;
}

.efobfd6qd {
  stop-color: var(--svg-color--ffcf31, #FFCF31);
}

.ekpe4jiwg {
  stop-color: var(--svg-color--d06654, #D06654);
  stop-opacity: 0;
}

.erudflbej {
  stop-color: var(--svg-color--f8c32e, #F8C32E);
  stop-opacity: 0;
}

.et4utnb5g {
  fill: var(--svg-color--ed8c2b, #ED8C2B);
  d: path("m14.047 20.52l1.468-2.27a.426.426 0 0 1 .75.067l.918 2.203h-.009a.72.72 0 0 1-.038.744c-.36.528-.815.87-1.495.87c-.67 0-1.244-.342-1.594-.87c-.176-.262-.15-.514 0-.744");
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.fixr86nla {
  stroke: var(--svg-color--bf4b28, #BF4B28);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22 14.101c-.59-.21-1.41-.36-2.47-.26");
}

.fmub3_f3z {
  stroke: var(--svg-color--bf4b28, #BF4B28);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.43 14.101c.59-.21 1.41-.36 2.47-.26");
}

.fn-t2vbtn {
  stop-color: var(--svg-color--ffe232, #FFE232);
}

.ft5dv1b6b {
  fill: none;
}

.fv1g4xboo {
  fill: var(--svg-color--000, #000);
  d: path("M12.77 18.107a1.13 1.13 0 0 0-1.134-1.135a1.13 1.13 0 0 0-1.134 1.135c0 .189.045.369.126.522h2.008c.08-.153.135-.333.135-.522");
}

.fynezkbik {
  stop-color: var(--svg-color--d77970, #D77970);
  stop-opacity: 0;
}

.g02s8lqle {
  stop-color: var(--svg-color--dc9228, #DC9228);
}

.g4c1labol {
  d: path("M13.446 17.874c0-.64-.52-1.067-.661-1.196l-.64.62l.393.801z");
}

.g6vud3bdk {
  stop-color: var(--svg-color--ffe632, #FFE632);
}

.giiyytb7x {
  stop-color: var(--svg-color--d1a83f, #D1A83F);
  stop-opacity: 0;
}

.gqhi1ccoz {
  stop-color: var(--svg-color--ffe83c, #FFE83C);
}

.h-bkq0ben {
  stop-color: var(--svg-color--ffcf31, #FFCF31);
  stop-opacity: 0;
}

.h8wc_ig9r {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22 14.101c-.59-.21-1.41-.36-2.47-.26");
}

.ht4oiqb3k {
  d: path("m4.704 12.9l.097 4.078c0 .779.668 1.008 1.047 1.032a.093.093 0 0 0 .097-.094l-.054-3.907c0-.61.186-1.286.75-1.813c.578-.539.937-1.085 1.016-1.726c.058-.48.152-.735.24-.895c.065-.117.283-.09.341.03c.846 1.763 2.454 2.341 3.672 2.434c.538.04.912-.456.909-.996c-.005-.708.064-1.405.197-1.643c2.203 2.703 5.422 2.64 6.375 2.609s3.297.031 5 .172c1.363.112 1.625 1.437 1.625 1.89v3.822a.1.1 0 0 0 .1.1h.113c.49 0 .881-.391.875-.88a34 34 0 0 1 .006-1.776c.047-1.14.015-1.344.828-2.89c.707-1.346 1.086-2.282.656-3.938c-.366-1.41-1.89-2.266-2.469-2.563c-.545-.28-.851-.554-1.117-1.07c-.265-.516-.644-1.66-2.648-2.5c-1.79-.75-2.969-.086-3.703.242c-.735.328-1.454.39-2.657-.187c-1.796-.781-3.453-.36-4.421.687c-.97 1.047-1.985 1.125-2.954 1.532c-.968.406-1.687 1.03-2.64 2.421c-1.263 1.55-1.38 4.532-1.281 5.829");
}

.io344do_p {
  stop-color: var(--svg-color--fcae1d, #FCAE1D);
  stop-opacity: 0;
}

.jmo7hmb8n {
  stop-color: var(--svg-color--ee9b22, #EE9B22);
}

.jnsjuwjrr {
  d: path("M20.33 16.116a1.988 1.988 0 0 1 1.917 2.513h-3.842a2 2 0 0 1-.072-.524c0-1.094.895-1.989 1.997-1.989");
}

.jtysutbfx {
  stop-color: var(--svg-color--d1a83f, #D1A83F);
}

.k_eg2bc7t {
  cx: 11.039px;
  cy: 16.972px;
  rx: 0.865px;
  ry: 0.438px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kovmn0bpr {
  stop-color: var(--svg-color--ffea38, #FFEA38);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lp846hbmw {
  stop-color: var(--svg-color--ffe931, #FFE931);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mow2ajbvq {
  stop-color: var(--svg-color--ffe931, #FFE931);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n_hoeqbdx {
  stop-color: var(--svg-color--e26e13, #E26E13);
}

.n32mfvwve {
  stop-color: var(--svg-color--ef8c1f, #EF8C1F);
}

.n3ahwtbnh {
  stop-color: var(--svg-color--ee9b22, #EE9B22);
  stop-opacity: 0;
}

.no2a_zbhx {
  d: path("M11.636 16.126a1.98 1.98 0 0 0-1.909 2.503h3.827a2 2 0 0 0 .072-.522a1.994 1.994 0 0 0-1.99-1.981");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou0xmdboy {
  d: path("M20.184 16.537c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pddl9kbtn {
  stop-color: var(--svg-color--ffea38, #FFEA38);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqi7xt6xb {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.177 15.523a3.1 3.1 0 0 0-3.007 2.35a.608.608 0 0 0 .594.756h4.952a.51.51 0 0 0 .504-.603a3.11 3.11 0 0 0-3.043-2.503");
}

.ptlmjm6ef {
  stop-color: var(--svg-color--d77970, #D77970);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qr4efnb1f {
  stop-color: var(--svg-color--db7e1e, #DB7E1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rxjfyob9j {
  stop-color: var(--svg-color--db7e1e, #DB7E1E);
}

.ryzsubbkp {
  cx: 11.039px;
  cy: 16.972px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.865px;
  ry: 0.438px;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sd5-q37vo {
  d: path("M17.469 11.196c-3.063-.625-5.032-3.968-6.43-5.937c4.687-3.828 11.375-.438 14.578 1.969c2.562 1.925 1.588 4.656.922 5.593c-.227-.812-1.147-1.46-2.164-1.625c-1.36-.218-3.687 0-6.906 0");
}

.t1i8-m29x {
  stop-color: var(--svg-color--f8c32e, #F8C32E);
}

.t24p8qb2e {
  stop-color: var(--svg-color--ef8c1f, #EF8C1F);
  stop-opacity: 0;
}

.tdjnlb1gn {
  stop-color: var(--svg-color--ffa929, #FFA929);
}

.te9ep8bjm {
  d: path("M25.76 19.879a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.tlhq_eb6r {
  stop-color: var(--svg-color--915c51, #915C51);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tw1jqobsd {
  fill: var(--svg-color--eea622, #EEA622);
  d: path("m4.704 12.9l.097 4.078c0 .779.668 1.008 1.047 1.032a.093.093 0 0 0 .097-.094l-.054-3.907c0-.61.186-1.286.75-1.813c.578-.539.937-1.085 1.016-1.726c.058-.48.152-.735.24-.895c.065-.117.283-.09.341.03c.846 1.763 2.454 2.341 3.672 2.434c.538.04.912-.456.909-.996c-.005-.708.064-1.405.197-1.643c2.203 2.703 5.422 2.64 6.375 2.609s3.297.031 5 .172c1.363.112 1.625 1.437 1.625 1.89v3.822a.1.1 0 0 0 .1.1h.113c.49 0 .881-.391.875-.88a34 34 0 0 1 .006-1.776c.047-1.14.015-1.344.828-2.89c.707-1.346 1.086-2.282.656-3.938c-.366-1.41-1.89-2.266-2.469-2.563c-.545-.28-.851-.554-1.117-1.07c-.265-.516-.644-1.66-2.648-2.5c-1.79-.75-2.969-.086-3.703.242c-.735.328-1.454.39-2.657-.187c-1.796-.781-3.453-.36-4.421.687c-.97 1.047-1.985 1.125-2.954 1.532c-.968.406-1.687 1.03-2.64 2.421c-1.263 1.55-1.38 4.532-1.281 5.829");
}

.tylp9fbgl {
  stop-color: var(--svg-color--e08137, #E08137);
  stop-opacity: 0;
}

.u4h591ezq {
  stop-color: var(--svg-color--de7f30, #DE7F30);
  stop-opacity: 0;
}

.u7wna2bwt {
  stop-color: var(--svg-color--e08137, #E08137);
}

.uhc_xg1rw {
  fill: var(--svg-color--ffbf34, #FFBF34);
  d: path("M25.76 19.879a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.vh89mvbib {
  d: path("M6.24 19.879a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.w-tiexbfy {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.43 14.101c.59-.21 1.41-.36 2.47-.26");
}

.wsvwr-55a {
  stop-color: var(--svg-color--f78423, #F78423);
  stop-opacity: 0;
}

.wtbp23h1x {
  stop-color: var(--svg-color--ffbe28, #FFBE28);
}

.x-2--yzhu {
  stop-color: var(--svg-color--fcae1d, #FCAE1D);
}

.x0qjlacpe {
  stop-color: var(--svg-color--ffcf32, #FFCF32);
  stop-opacity: 0;
}

.xl4q7gbwl {
  stop-color: var(--svg-color--de7f30, #DE7F30);
}

.xlyb0nb-w {
  stop-color: var(--svg-color--c79b39, #C79B39);
  stop-opacity: 0;
}

.xs67m9lfd {
  d: path("m14.363 20.331l1.25-2.604a.412.412 0 0 1 .74-.003l1.309 2.668h-.01a.72.72 0 0 1-.037.744a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.002-.805");
}

.xyx6-34by {
  d: path("M25.76 21.009a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.y7wk7mwbz {
  fill: var(--svg-color--ffc82e, #FFC82E);
  d: path("m14.363 20.331l1.25-2.604a.412.412 0 0 1 .74-.003l1.309 2.668h-.01a.72.72 0 0 1-.037.744a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.002-.805");
}

.yag6w7bgr {
  stop-color: var(--svg-color--d06654, #D06654);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.zrnpsc2lb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.184 16.537c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.zrulh6btb {
  stop-color: var(--svg-color--ce5b02, #CE5B02);
}

</style>
