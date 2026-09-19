<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihMULab)"><path fill="url(#iF1TM5c)" class="hakz2sbwy"/><path fill="url(#itdXU0E)" class="hakz2sbwy"/></g><g filter="url(#i0rxFKc)"><path fill="url(#ivROHSd)" class="xzmyp6bta"/><path fill="url(#i6IxcTd)" class="xzmyp6bta"/></g><g filter="url(#iyZXEze)"><path class="ep4oxn0_t"/><path fill="url(#iLR9tNe)" class="vdtgm7xsd"/></g><g filter="url(#iuSFoOc)"><path class="mut1k97cq"/></g><g filter="url(#iBrBLSc)"><path class="ag4s_dbfu"/><path fill="url(#i1InJ7Y)" class="nf6c7hbnp"/><path fill="url(#ife4ycc)" class="nf6c7hbnp"/><path fill="url(#iWnvqud)" class="nf6c7hbnp"/><path fill="url(#i3R3ywc)" class="nf6c7hbnp"/></g><g filter="url(#iAd9gLb)"><path class="xkvjufbme"/><path fill="url(#i2jWroT)" class="aq_4l9bbr"/><path fill="url(#iypwVld)" class="aq_4l9bbr"/></g><g filter="url(#iTU6j4d)"><path fill="url(#iKfyywc)" class="mm9owdb0r"/><path fill="url(#il175Ub)" class="mm9owdb0r"/><path fill="url(#iayOoDc)" class="mm9owdb0r"/></g><path fill="url(#iilN6wb)" class="mm9owdb0r"/><path fill="url(#iAKLXOv)" class="mm9owdb0r"/><path fill="url(#ihDBBUZ)" class="mm9owdb0r"/><path class="b6jrsfltb"/><g filter="url(#ipHHd2b)"><path class="unk8_xbdl"/></g><g filter="url(#iipxnye)"><path stroke="url(#iSWTn8c)" class="lfdng0b2d"/></g><g filter="url(#irTW3de)"><path class="k2iz9bc_e"/></g><g filter="url(#i1S3brd)"><path stroke="url(#ifEHAya)" class="e8xwptb6r"/></g><g filter="url(#iKTi50c)"><path fill="url(#i8N3b3b)" class="drutxp4de"/></g><path fill="url(#i1gtbcb)" class="drutxp4de"/><g filter="url(#iHeyJOv)"><path fill="url(#iHbKIvb)" class="c6hpfe6cl"/></g><g filter="url(#inGjftd)"><path class="umndhzi_c"/><path fill="url(#iz0zSgT)" class="a_fow0f6t"/><path fill="url(#iT8UPrb)" class="a_fow0f6t"/><path fill="url(#iInk0Nb)" class="a_fow0f6t"/><path fill="url(#ihjLpKl)" class="a_fow0f6t"/></g><path fill="url(#idBoOJe)" class="a_fow0f6t"/><path fill="url(#i6gFQqe)" class="a_fow0f6t"/><g filter="url(#iqLuQHD)"><path class="o2wu4jcqm"/><path fill="url(#id9wrgb)" class="umx0l3bka"/><path fill="url(#iZpH30m)" class="umx0l3bka"/></g><path class="m2heqyb4t"/><path fill="url(#i9ldeGc)" class="cpdnzl34v"/><path class="yyrmmdbue"/><g filter="url(#iL3bX1d)"><path class="qwqj08bqh"/><path fill="url(#i3eKYEd)" class="p77arcc7e"/></g><g filter="url(#idHo8Dd)"><path fill="url(#iELZJrb)" class="xcjy9rb_j"/></g><path class="pnmdd2_9u"/><path fill="url(#iR5ecoc)" class="c_9a4-b-t"/><path class="slyafnbhq"/><g filter="url(#iAjln4d)"><path fill="url(#iRKWadR)" class="j390lfhbc"/></g><g filter="url(#i9bI4cZ)"><ellipse transform="rotate(-27.914 11.087 17.58)" class="ko6huuboy"/><ellipse fill="url(#ipC32Rd)" transform="rotate(-27.914 11.087 17.58)" class="m0yzwzemw"/></g><g filter="url(#iopSbib)"><path fill="url(#irczU0d)" class="ssfhyevuj"/></g><g filter="url(#ikX0W8c)"><path stroke="url(#iFTsgte)" class="w9a8ar5_s"/></g><defs><radialGradient id="itdXU0E" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8125 0 0 -3.21299 6.402 17.436)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="qh4a5gb-b"/><stop offset="1" class="rcahx0bsc"/></radialGradient><radialGradient id="ivROHSd" cx="0" cy="0" r="1" gradientTransform="matrix(3.5821 -2.8125 2.25578 2.87304 25.168 19.233)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="z0wyshbsx"/><stop offset="1" class="igx665z_i"/></radialGradient><radialGradient id="i6IxcTd" cx="0" cy="0" r="1" gradientTransform="matrix(1.57416 -4.10937 3.9878 1.52759 25.5 18.436)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="agqmsowgt"/><stop offset="1" class="bosb_khrm"/></radialGradient><radialGradient id="iLR9tNe" cx="0" cy="0" r="1" gradientTransform="translate(24.778 17.75)scale(2.89063)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="tumonybba"/><stop offset="1" class="fndgygbrm"/></radialGradient><radialGradient id="ife4ycc" cx="0" cy="0" r="1" gradientTransform="matrix(4.26564 3.39061 -.5845 .73535 24.668 23.218)" gradientUnits="userSpaceOnUse"><stop class="fwsbo0ewv"/><stop offset="1" class="f43zsnb8n"/></radialGradient><radialGradient id="iWnvqud" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45313 .42188 -.09485 -.55156 30.262 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="glx9rn1kk"/><stop offset="1" class="st-pambja"/></radialGradient><radialGradient id="i3R3ywc" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 1.5625 -2.82655 4.35289 22.7 25.14)" gradientUnits="userSpaceOnUse"><stop class="tycdnbcuq"/><stop offset="1" class="h3pxxebyt"/></radialGradient><radialGradient id="i2jWroT" cx="0" cy="0" r="1" gradientTransform="rotate(153.831 1.055 13.947)scale(2.37151 5.41349)" gradientUnits="userSpaceOnUse"><stop class="fkplxnb2t"/><stop offset="1" class="e_3wt6qjx"/></radialGradient><radialGradient id="iKfyywc" cx="0" cy="0" r="1" gradientTransform="rotate(131.847 7.314 14.355)scale(13.2787 13.9072)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="zxf8fbvkt"/><stop offset="1" class="gdw4yvomr"/></radialGradient><radialGradient id="il175Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3938 16.48338 -15.50427 -1.311 17.403 14.375)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="wnx14ccpe"/><stop offset="1" class="am2--6b1r"/></radialGradient><radialGradient id="iayOoDc" cx="0" cy="0" r="1" gradientTransform="matrix(-16.6063 0 0 -17.8828 22.45 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".875" class="po9fgwcjk"/><stop offset="1" class="tf1uumwhx"/></radialGradient><radialGradient id="iilN6wb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.16825 0 0 -11.9901 26.175 18.929)" gradientUnits="userSpaceOnUse"><stop class="r7j1q4bew"/><stop offset="1" class="hn789jbyj"/></radialGradient><radialGradient id="iAKLXOv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33392 3.24473 0 21.048 16.89)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="jmfxvacvx"/><stop offset="1" class="x8a3b7h6b"/></radialGradient><radialGradient id="ihDBBUZ" cx="0" cy="0" r="1" gradientTransform="matrix(.409 -2.4288 2.5769 .43394 11.574 16.827)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="qi4y7qage"/><stop offset="1" class="ml5q6cbha"/></radialGradient><radialGradient id="i8N3b3b" cx="0" cy="0" r="1" gradientTransform="rotate(-176.074 5.232 4.477)scale(6.64718 11.0947)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="yf7jysbox"/><stop offset="1" class="ic1hwob4v"/></radialGradient><radialGradient id="i1gtbcb" cx="0" cy="0" r="1" gradientTransform="rotate(110.487 1.808 7.495)scale(3.15794 .91085)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="gapir9_xn"/><stop offset="1" class="g5493zbcm"/></radialGradient><radialGradient id="iz0zSgT" cx="0" cy="0" r="1" gradientTransform="matrix(-.8656 -3.55676 1.51165 -.36789 17.554 20.6)" gradientUnits="userSpaceOnUse"><stop class="ul5c_ilzp"/><stop offset="1" class="yrqws0u6j"/></radialGradient><radialGradient id="iT8UPrb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 0 0 -.35938 17.527 20.765)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="ul5c_ilzp"/><stop offset="1" class="yrqws0u6j"/></radialGradient><radialGradient id="idBoOJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.51563 -2.65432 0 16 18.78)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="txl73obtj"/><stop offset="1" class="ys6q0z5tx"/></radialGradient><radialGradient id="id9wrgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94118 -10.2724 0 17.947 .33)" gradientUnits="userSpaceOnUse"><stop class="ysl_u5bjy"/><stop offset="1" class="lxhfm0bgl"/></radialGradient><radialGradient id="iZpH30m" cx="0" cy="0" r="1" gradientTransform="matrix(-7.125 0 0 -7.6875 30.387 13.046)" gradientUnits="userSpaceOnUse"><stop class="hx7_zcbyj"/><stop offset="1" class="vsyg2xbej"/></radialGradient><radialGradient id="i9ldeGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80382 -2.86918 0 20.342 17.773)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="ykjypuqrh"/></radialGradient><radialGradient id="i3eKYEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51563 -.66445 .9148 -.7099 19.835 17.96)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iR5ecoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80042 -2.86377 0 11.689 17.792)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="ykjypuqrh"/></radialGradient><radialGradient id="ipC32Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01717 -1.09638 1.31789 -.02063 11.053 18.278)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irczU0d" cx="0" cy="0" r="1" gradientTransform="matrix(-9.1672 -5.8514 2.15611 -3.37791 22.368 11.902)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><filter id="ihMULab" width="6.5" height="6.9" x="3.25" y="14.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.52549 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="i0rxFKc" width="6.7" height="6.75" x="22.25" y="14.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="iyZXEze" width="5.059" height="5.059" x="22.971" y="15.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".25"/></filter><filter id="iuSFoOc" width="5.059" height="5.059" x="3.971" y="15.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".25"/></filter><filter id="iBrBLSc" width="8.699" height="9.582" x="22.019" y="20.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.8"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.0666667 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="iAd9gLb" width="8.299" height="9.532" x="1.75" y="20.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.054902 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="iTU6j4d" width="20.332" height="22.543" x="5.843" y="7.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.552941 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="ipHHd2b" width="3.73" height="1.554" x="9.06" y="13.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="iipxnye" width="3.93" height="1.754" x="8.861" y="13.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".25"/></filter><filter id="irTW3de" width="3.77" height="1.592" x="19.369" y="13.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="i1S3brd" width="3.97" height="1.792" x="19.169" y="13.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".25"/></filter><filter id="iKTi50c" width="7.56" height="12.119" x="3.529" y="3.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0117647 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="iHeyJOv" width="4.815" height="5.893" x="13.274" y="17.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".375"/></filter><filter id="inGjftd" width="3.997" height="5.131" x="14.002" y="17.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".125"/></filter><filter id="iqLuQHD" width="18.74" height="14.471" x="10.049" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.0156863 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3632"/></filter><filter id="iL3bX1d" width="1.505" height="1.303" x="18.832" y="16.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".05"/></filter><filter id="idHo8Dd" width="1.492" height="1.541" x="20.822" y="17.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".1"/></filter><filter id="iAjln4d" width="1.701" height="1.821" x="11.993" y="17.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".1"/></filter><filter id="i9bI4cZ" width="1.782" height="1.319" x="10.196" y="16.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".05"/></filter><filter id="iopSbib" width="19.318" height="13.526" x="9.647" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation="1"/></filter><filter id="ikX0W8c" width="6.4" height="7.619" x="4.093" y="4.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3632" stdDeviation=".375"/></filter><linearGradient id="iF1TM5c" x1="4.184" x2="6.727" y1="18.711" y2="18.711" gradientUnits="userSpaceOnUse"><stop class="osrj76b1s"/><stop offset="1" class="l0z_46m4n"/></linearGradient><linearGradient id="i1InJ7Y" x1="27.934" x2="26.872" y1="24.109" y2="25.75" gradientUnits="userSpaceOnUse"><stop class="k991bob9t"/><stop offset="1" class="bbb_dsbqn"/></linearGradient><linearGradient id="iypwVld" x1="3.997" x2="4.997" y1="23.781" y2="25.219" gradientUnits="userSpaceOnUse"><stop class="xskddsfhw"/><stop offset="1" class="c4kf-0g9v"/></linearGradient><linearGradient id="iSWTn8c" x1="12.04" x2="9.395" y1="14.091" y2="14.091" gradientUnits="userSpaceOnUse"><stop class="d_wzpg_av"/><stop offset="1" class="ekg1bobit"/></linearGradient><linearGradient id="ifEHAya" x1="22.389" x2="19.7" y1="14.11" y2="14.11" gradientUnits="userSpaceOnUse"><stop class="d_wzpg_av"/><stop offset="1" class="ekg1bobit"/></linearGradient><linearGradient id="iHbKIvb" x1="14.34" x2="17.829" y1="21.769" y2="19.978" gradientUnits="userSpaceOnUse"><stop offset=".274" class="ckmkqkblo"/><stop offset="1" class="w_zczw3bj"/></linearGradient><linearGradient id="iInk0Nb" x1="14.092" x2="15.493" y1="20.127" y2="20.19" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ihjLpKl" x1="15.823" x2="15.823" y1="22.299" y2="20.536" gradientUnits="userSpaceOnUse"><stop class="izqfrr_of"/><stop offset="1" class="vzd9cdche"/></linearGradient><linearGradient id="i6gFQqe" x1="14.887" x2="14.012" y1="19.89" y2="19.684" gradientUnits="userSpaceOnUse"><stop class="txl73obtj"/><stop offset=".898" class="ys6q0z5tx"/></linearGradient><linearGradient id="iELZJrb" x1="22.072" x2="21.374" y1="17.893" y2="18.323" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRKWadR" x1="13.339" x2="12.643" y1="17.911" y2="18.34" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFTsgte" x1="9.23" x2="5.41" y1="5.187" y2="11.537" gradientUnits="userSpaceOnUse"><stop class="gxtrnld9p"/><stop offset="1" class="ys1_p49mq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:girl-light" /></template>
<style>
.a_fow0f6t {
  d: path("M17.714 20.506a.72.72 0 0 1-.089.62c-.35.529-.95.874-1.62.874s-1.27-.345-1.63-.873a.72.72 0 0 1-.007-.797l1.169-2.656a.511.511 0 0 1 .935 0l1.202 2.732l.022.049l.023.051z");
}

.ag4s_dbfu {
  fill: var(--svg-color--262229, #262229);
  d: path("m23.629 21.22l6 4.03c.55.37.59 1.17.08 1.6l-3.19 2.81c-.72.64-1.85.34-2.18-.56l-2.32-6.49z");
}

.agqmsowgt {
  stop-color: var(--svg-color--cea084, #CEA084);
  stop-opacity: 0;
}

.am2--6b1r {
  stop-color: var(--svg-color--b57894, #B57894);
}

.aq_4l9bbr {
  d: path("m8.439 21.22l-6 4.03c-.55.37-.59 1.17-.08 1.6l3.19 2.81c.72.64 1.85.34 2.18-.56l2.32-6.49z");
}

.b6jrsfltb {
  fill: var(--svg-color--89014e, #89014E);
  d: path("M16.014 23.373a6.5 6.5 0 0 1-3.016-.733a.329.329 0 0 0-.43.472a4.088 4.088 0 0 0 6.89 0c.18-.281-.13-.622-.429-.472a6.35 6.35 0 0 1-3.015.733");
}

.bbb_dsbqn {
  stop-color: var(--svg-color--323131, #323131);
  stop-opacity: 0;
}

.bosb_khrm {
  stop-color: var(--svg-color--cea084, #CEA084);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.c_9a4-b-t {
  d: path("M11.684 16.733a1.98 1.98 0 0 0-1.908 2.503h3.826a2 2 0 0 0 .072-.522a1.994 1.994 0 0 0-1.99-1.98");
}

.c4kf-0g9v {
  stop-color: var(--svg-color--3c3a3a, #3C3A3A);
  stop-opacity: 0;
}

.c6hpfe6cl {
  d: path("M17.321 21.06a.68.68 0 0 1-.131.58a1.85 1.85 0 0 1-1.6.706a1.88 1.88 0 0 1-1.477-.95a.69.69 0 0 1 .052-.754l1.307-2.428a.485.485 0 0 1 .885.07l.934 2.677l.017.049l.017.05z");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ckmkqkblo {
  stop-color: var(--svg-color--d0938d, #D0938D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpdnzl34v {
  d: path("M20.347 16.713a1.984 1.984 0 0 1 1.912 2.507h-3.834a2 2 0 0 1-.072-.523c0-1.091.893-1.984 1.994-1.984");
}

.d_wzpg_av {
  stop-color: var(--svg-color--353535, #353535);
}

.drutxp4de {
  d: path("M4.029 11.06c0-3.9 3.16-7.06 7.06-7.06v.97c0 3.18-.46 6.905-4.522 8.655c-.34.146-.68.328-.727.938c-.601.14-1.29.476-1.794 1.056a7 7 0 0 1-.017-.489z");
}

.e_3wt6qjx {
  stop-color: var(--svg-color--140f18, #140F18);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8xwptb6r {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M22.39 14.11c-.59-.21-1.41-.36-2.47-.26");
}

.ekg1bobit {
  stop-color: var(--svg-color--353535, #353535);
  stop-opacity: 0;
}

.ep4oxn0_t {
  fill: var(--svg-color--f8bfa5, #F8BFA5);
  d: path("M25.5 19.78a2.03 2.03 0 1 0 0-4.06a2.03 2.03 0 0 0 0 4.06");
}

.f43zsnb8n {
  stop-color: var(--svg-color--3c3b3b, #3C3B3B);
  stop-opacity: 0;
}

.fkplxnb2t {
  stop-color: var(--svg-color--140f18, #140F18);
}

.fndgygbrm {
  stop-color: var(--svg-color--f3b79c, #F3B79C);
}

.ft5dv1b6b {
  fill: none;
}

.fwsbo0ewv {
  stop-color: var(--svg-color--3c3b3b, #3C3B3B);
}

.g5493zbcm {
  stop-color: var(--svg-color--3b3438, #3B3438);
  stop-opacity: 0;
}

.gapir9_xn {
  stop-color: var(--svg-color--3b3438, #3B3438);
}

.gdw4yvomr {
  stop-color: var(--svg-color--d49f95, #D49F95);
}

.glx9rn1kk {
  stop-color: var(--svg-color--494949, #494949);
}

.gxtrnld9p {
  stop-color: var(--svg-color--504e4e, #504E4E);
}

.h3pxxebyt {
  stop-color: var(--svg-color--09040c, #09040C);
  stop-opacity: 0;
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hakz2sbwy {
  d: path("M6.5 21a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.hn789jbyj {
  stop-color: var(--svg-color--ffd5b8, #FFD5B8);
  stop-opacity: 0;
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hx7_zcbyj {
  stop-color: var(--svg-color--565253, #565253);
}

.ic1hwob4v {
  stop-color: var(--svg-color--5e5959, #5E5959);
}

.igx665z_i {
  stop-color: var(--svg-color--ffd3bb, #FFD3BB);
}

.izqfrr_of {
  stop-color: var(--svg-color--d29294, #D29294);
}

.j390lfhbc {
  d: path("M13.494 18.48c0-.64-.52-1.066-.661-1.195l-.64.62l.393.801z");
}

.jmfxvacvx {
  stop-color: var(--svg-color--f1b7a7, #F1B7A7);
}

.k2iz9bc_e {
  stroke: var(--svg-color--110a18, #110A18);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M22.39 14.11c-.59-.21-1.41-.36-2.47-.26");
}

.k991bob9t {
  stop-color: var(--svg-color--323131, #323131);
}

.ko6huuboy {
  cx: 11.087px;
  cy: 17.579px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.865px;
  ry: 0.438px;
}

.l0z_46m4n {
  stop-color: var(--svg-color--c0866f, #C0866F);
}

.lfdng0b2d {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.61 14.09c.59-.21 1.37-.315 2.43-.215");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lxhfm0bgl {
  stop-color: var(--svg-color--433d3f, #433D3F);
  stop-opacity: 0;
}

.m0yzwzemw {
  cx: 11.087px;
  cy: 17.579px;
  rx: 0.865px;
  ry: 0.438px;
}

.m2heqyb4t {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.807 16.108a3.105 3.105 0 0 1 3.012 2.354a.61.61 0 0 1-.595.758h-4.96a.512.512 0 0 1-.506-.604a3.11 3.11 0 0 1 3.049-2.508");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.ml5q6cbha {
  stop-color: var(--svg-color--d0968f, #D0968F);
  stop-opacity: 0;
}

.mm9owdb0r {
  d: path("M18.859 13c-3.601-.607-6.582-2.38-7.97-5.143c-.383 2.316-1.456 4.533-4.322 5.768c-.334.144-.669.322-.724.908l.193 5.682C6.275 26.074 10.659 30 16 30c5.33 0 9.725-3.926 9.964-9.785l.21-6.204a.48.48 0 0 0-.412-.498c-.849-.113-1.975-.171-3.156-.232c-1.28-.066-2.624-.135-3.747-.281");
}

.mut1k97cq {
  fill: var(--svg-color--c88a7b, #C88A7B);
  d: path("M6.5 19.78a2.03 2.03 0 1 0 0-4.06a2.03 2.03 0 0 0 0 4.06");
}

.nf6c7hbnp {
  d: path("m23.629 21.22l6 4.03c.55.37.59 1.17.08 1.6l-3.19 2.81c-.72.64-1.85.34-2.18-.56l-2.32-6.49z");
}

.o2wu4jcqm {
  fill: var(--svg-color--32272a, #32272A);
  d: path("M18.859 13c-5.004-.844-8.81-3.94-8.81-8.81c0-1.21.98-2.19 2.18-2.19h5.81c5.52 0 10 4.48 10 10v3.72a3.25 3.25 0 0 0-1.883-1.154l.019-.555a.48.48 0 0 0-.413-.498c-.849-.113-1.975-.171-3.156-.232c-1.28-.066-2.624-.135-3.747-.281");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.osrj76b1s {
  stop-color: var(--svg-color--d19888, #D19888);
}

.p77arcc7e {
  d: path("M20.2 17.132c.142.19-.153.42-.49.67c-.335.252-.585.429-.726.24c-.142-.19.016-.546.352-.797c.336-.252.723-.302.865-.113");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmdd2_9u {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.225 16.13a3.1 3.1 0 0 0-3.006 2.35a.608.608 0 0 0 .594.756h4.95a.51.51 0 0 0 .505-.603a3.11 3.11 0 0 0-3.043-2.503");
}

.po9fgwcjk {
  stop-color: var(--svg-color--e9ae96, #E9AE96);
  stop-opacity: 0;
}

.qh4a5gb-b {
  stop-color: var(--svg-color--cf9384, #CF9384);
}

.qi4y7qage {
  stop-color: var(--svg-color--d0968f, #D0968F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwqj08bqh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.2 17.132c.142.19-.153.42-.49.67c-.335.252-.585.429-.726.24c-.142-.19.016-.546.352-.797c.336-.252.723-.302.865-.113");
}

.r7j1q4bew {
  stop-color: var(--svg-color--ffd5b8, #FFD5B8);
}

.rcahx0bsc {
  stop-color: var(--svg-color--cf9384, #CF9384);
  stop-opacity: 0;
}

.slyafnbhq {
  fill: var(--svg-color--000, #000);
  d: path("M12.819 18.714a1.13 1.13 0 0 0-1.135-1.135a1.13 1.13 0 0 0-1.134 1.135c0 .189.045.369.126.522h2.008c.08-.153.135-.333.135-.522");
}

.ssfhyevuj {
  d: path("M26.965 12.314c-10.843.832-15.318-4.411-15.318-9.439h6.205c7.29 0 9.113 6.292 9.113 9.439");
}

.st-pambja {
  stop-color: var(--svg-color--494949, #494949);
  stop-opacity: 0;
}

.tf1uumwhx {
  stop-color: var(--svg-color--e9ae96, #E9AE96);
}

.tumonybba {
  stop-color: var(--svg-color--f3b79c, #F3B79C);
  stop-opacity: 0;
}

.txl73obtj {
  stop-color: var(--svg-color--d08f90, #D08F90);
  stop-opacity: 0;
}

.tycdnbcuq {
  stop-color: var(--svg-color--09040c, #09040C);
}

.ul5c_ilzp {
  stop-color: var(--svg-color--ffd9c1, #FFD9C1);
}

.umndhzi_c {
  fill: var(--svg-color--ecc1ac, #ECC1AC);
  d: path("M17.714 20.506a.72.72 0 0 1-.089.62c-.35.529-.95.874-1.62.874s-1.27-.345-1.63-.873a.72.72 0 0 1-.007-.797l1.169-2.656a.511.511 0 0 1 .935 0l1.202 2.732l.022.049l.023.051z");
}

.umx0l3bka {
  d: path("M18.859 13c-5.004-.844-8.81-3.94-8.81-8.81c0-1.21.98-2.19 2.18-2.19h5.81c5.52 0 10 4.48 10 10v3.72a3.25 3.25 0 0 0-1.883-1.154l.019-.555a.48.48 0 0 0-.413-.498c-.849-.113-1.975-.171-3.156-.232c-1.28-.066-2.624-.135-3.747-.281");
}

.unk8_xbdl {
  stroke: var(--svg-color--110a18, #110A18);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M9.61 14.09c.59-.21 1.37-.315 2.43-.215");
}

.vdtgm7xsd {
  d: path("M25.5 19.78a2.03 2.03 0 1 0 0-4.06a2.03 2.03 0 0 0 0 4.06");
}

.vsyg2xbej {
  stop-color: var(--svg-color--565253, #565253);
  stop-opacity: 0;
}

.vzd9cdche {
  stop-color: var(--svg-color--d29294, #D29294);
  stop-opacity: 0;
}

.w_zczw3bj {
  stop-color: var(--svg-color--ffdbc0, #FFDBC0);
}

.w9a8ar5_s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.543 4.952c-1.323.43-4.075 2.176-4.5 5.719");
}

.wnx14ccpe {
  stop-color: var(--svg-color--b57894, #B57894);
  stop-opacity: 0;
}

.x8a3b7h6b {
  stop-color: var(--svg-color--f1b7a7, #F1B7A7);
  stop-opacity: 0;
}

.xcjy9rb_j {
  d: path("M22.114 18.436a1.87 1.87 0 0 0-.514-1.03l-.578.635l.26.507z");
}

.xkvjufbme {
  fill: var(--svg-color--221f26, #221F26);
  d: path("m8.439 21.22l-6 4.03c-.55.37-.59 1.17-.08 1.6l3.19 2.81c.72.64 1.85.34 2.18-.56l2.32-6.49z");
}

.xskddsfhw {
  stop-color: var(--svg-color--3c3a3a, #3C3A3A);
}

.xzmyp6bta {
  d: path("M25.5 21a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.yf7jysbox {
  stop-color: var(--svg-color--22181c, #22181C);
}

.ykjypuqrh {
  stop-color: var(--svg-color--644945, #644945);
}

.yrqws0u6j {
  stop-color: var(--svg-color--ffd9c1, #FFD9C1);
  stop-opacity: 0;
}

.ys1_p49mq {
  stop-color: var(--svg-color--504e4e, #504E4E);
  stop-opacity: 0;
}

.ys6q0z5tx {
  stop-color: var(--svg-color--d08f90, #D08F90);
}

.ysl_u5bjy {
  stop-color: var(--svg-color--433d3f, #433D3F);
}

.yyrmmdbue {
  fill: var(--svg-color--000, #000);
  d: path("M19.21 18.697c0-.631.505-1.136 1.136-1.136c.632 0 1.137.505 1.137 1.136c0 .19-.045.37-.126.523h-2.012a1.03 1.03 0 0 1-.135-.523");
}

.z0wyshbsx {
  stop-color: var(--svg-color--f2bcaa, #F2BCAA);
}

.zxf8fbvkt {
  stop-color: var(--svg-color--ffdcbf, #FFDCBF);
}

</style>
