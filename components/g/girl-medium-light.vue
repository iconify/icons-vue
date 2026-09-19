<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixzDpve)"><path class="kl05g-bti"/></g><g filter="url(#iISfZUz)"><path fill="url(#iHPgSSv)" class="oz5kevsqv"/></g><g filter="url(#iYoFexb)"><path class="hjlqtbu-h"/><path fill="url(#inwxafz)" class="jcx_qeb7e"/></g><g filter="url(#ikGkmMe)"><path fill="url(#iupC7Je)" class="nanijx3af"/></g><g filter="url(#ixDSFlb)"><path class="ax9fg1bbf"/><path fill="url(#isy3Kee)" class="i_-1mrvtn"/></g><g filter="url(#i2ES1Wb)"><path class="u30bsrkfu"/><path fill="url(#iOrAI8d)" class="oroa7vwoo"/><path fill="url(#ifagFqc)" class="oroa7vwoo"/></g><g filter="url(#iZi2IWb)"><path fill="url(#ipqJgBe)" class="yvajbz8lc"/><path fill="url(#iF1anEe)" class="yvajbz8lc"/><path fill="url(#izISEOb)" class="yvajbz8lc"/></g><path fill="url(#i4GXYBb)" class="yvajbz8lc"/><path fill="url(#ib9Khne)" class="yvajbz8lc"/><path fill="url(#iUNzJnH)" class="yvajbz8lc"/><path class="kwl5p8b4p"/><g filter="url(#i2Ds4id)"><path class="f2znwobvf"/></g><g filter="url(#isBnPld)"><path stroke="url(#iEAUBpe)" class="j0v80ebyh"/></g><g filter="url(#iBVnMnc)"><path class="bix3bcpry"/></g><g filter="url(#in2UmRd)"><path stroke="url(#i9Nmp1b)" class="ngglvlb8p"/></g><g filter="url(#iJTOVCc)"><path fill="url(#inlLhpc)" class="tbjyjpzjq"/></g><path fill="url(#i2C66de)" class="tbjyjpzjq"/><path fill="url(#isOLPYc)" class="tbjyjpzjq"/><path fill="url(#iGVJDyd)" class="tbjyjpzjq"/><path fill="url(#iUyShte)" class="tbjyjpzjq"/><g filter="url(#i61GNHe)"><path class="m4e-80bao"/></g><g filter="url(#iTlikyb)"><path class="ll2dt01fd"/><path fill="url(#iJz10Le)" class="q4na5j0rh"/><path fill="url(#iPtkGhe)" class="q4na5j0rh"/><path fill="url(#iCBCDfb)" class="q4na5j0rh"/></g><g filter="url(#iaOdoZd)"><path class="s_-r2acdm"/><path fill="url(#iIgrZyb)" class="p0e1uebyo"/></g><path class="qrc2bisni"/><path fill="url(#iZ5J0Nb)" class="ntre80m-m"/><path class="l63ahbelw"/><g filter="url(#iIt9wOe)"><path class="kkc0cxb4t"/><path fill="url(#it0MtOA)" class="ieoeq9k2t"/></g><g filter="url(#iacKWHe)"><path fill="url(#iUsuOMd)" class="mgr9d0bbh"/></g><path class="zrdieeknv"/><path fill="url(#iouKpzb)" class="tzchu9qsk"/><path class="d4nxjip-a"/><g filter="url(#iWD1xac)"><path fill="url(#ijhsrdb)" class="kvzlxcs2e"/></g><g filter="url(#iCgXb0b)"><ellipse transform="rotate(-27.914 11.075 17.47)" class="vp_82byvi"/><ellipse fill="url(#invfrad)" transform="rotate(-27.914 11.075 17.47)" class="bpf5fz53d"/></g><g filter="url(#i8fvhnX)"><path fill="url(#iNkG66d)" class="mstcoz5vv"/></g><defs><radialGradient id="iHPgSSv" cx="0" cy="0" r="1" gradientTransform="rotate(-46.534 34.683 -19.425)scale(4.95152 3.97141)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="deqzvbcwp"/><stop offset="1" class="cn0xe4wwo"/></radialGradient><radialGradient id="inwxafz" cx="0" cy="0" r="1" gradientTransform="translate(24.766 17.642)scale(2.89063)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="vmwe85bmx"/><stop offset="1" class="pm2an5o7k"/></radialGradient><radialGradient id="iOrAI8d" cx="0" cy="0" r="1" gradientTransform="rotate(152.79 1.164 13.78)scale(2.79678 4.60023)" gradientUnits="userSpaceOnUse"><stop class="iyvn0kbmb"/><stop offset="1" class="v_tdjh1fb"/></radialGradient><radialGradient id="ipqJgBe" cx="0" cy="0" r="1" gradientTransform="rotate(121.935 5.859 14.307)scale(13.391 14.0248)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="wm0dr9b9p"/><stop offset="1" class="fm9vhqbuv"/></radialGradient><radialGradient id="iF1anEe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1991 16.20413 -18.59213 -3.67055 19.188 14.875)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="rjmsdzbap"/><stop offset="1" class="u42k9fb7y"/></radialGradient><radialGradient id="i4GXYBb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.16825 0 0 -11.9901 26.163 18.82)" gradientUnits="userSpaceOnUse"><stop class="j23ndhcki"/><stop offset="1" class="vijwexbvn"/></radialGradient><radialGradient id="ib9Khne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.86429 3.55676 0 21.037 17.312)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="tjmo9ub5q"/><stop offset="1" class="p13tn10da"/></radialGradient><radialGradient id="iUNzJnH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.92724 3.10574 0 11.972 17.217)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="au6tbndjk"/><stop offset="1" class="q-hbhfb7u"/></radialGradient><radialGradient id="inlLhpc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.722 6.065 4.031)scale(4.97651 8.30621)" gradientUnits="userSpaceOnUse"><stop class="mnikv3jnk"/><stop offset="1" class="w43borwfn"/></radialGradient><radialGradient id="i2C66de" cx="0" cy="0" r="1" gradientTransform="rotate(120.316 2.4 7.493)scale(7.30541 5.3846)" gradientUnits="userSpaceOnUse"><stop offset=".534" class="l1tcvcbwz"/><stop offset="1" class="dri9dpmkh"/></radialGradient><radialGradient id="isOLPYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2815 3.78125 -2.1414 -.72574 8.829 9.392)" gradientUnits="userSpaceOnUse"><stop class="h9wqmtbbg"/><stop offset="1" class="gls_vvbmy"/></radialGradient><radialGradient id="iGVJDyd" cx="0" cy="0" r="1" gradientTransform="rotate(153.072 5.68 4.565)scale(4.41632 5.86956)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="jt7qesbba"/><stop offset="1" class="vwkt462qc"/></radialGradient><radialGradient id="iUyShte" cx="0" cy="0" r="1" gradientTransform="matrix(4.58941 3.42824 -6.24799 8.36424 5.759 8.733)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="cvxaptb-r"/><stop offset="1" class="dt6o7bc2u"/></radialGradient><radialGradient id="iJz10Le" cx="0" cy="0" r="1" gradientTransform="matrix(-.8656 -3.55676 1.7961 -.43711 17.543 20.49)" gradientUnits="userSpaceOnUse"><stop class="jgzv3_tcu"/><stop offset="1" class="omhdffyfp"/></radialGradient><radialGradient id="iIgrZyb" cx="0" cy="0" r="1" gradientTransform="rotate(124.181 11.483 9.014)scale(10.1236 15.0089)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iZ5J0Nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80382 -2.86918 0 20.33 17.665)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="it0MtOA" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 -.66445 .9148 -.7099 19.823 17.852)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iouKpzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80042 -2.86377 0 11.677 17.683)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="invfrad" cx="0" cy="0" r="1" gradientTransform="matrix(-.01717 -1.09638 1.31789 -.02063 11.042 18.17)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNkG66d" cx="0" cy="0" r="1" gradientTransform="rotate(23.234 -6.513 47.874)scale(15.8965 8.74181)" gradientUnits="userSpaceOnUse"><stop class="sb6eau4zv"/><stop offset="1" class="oze4hdc_s"/></radialGradient><filter id="ixzDpve" width="6.7" height="6.5" x="3.238" y="14.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="iISfZUz" width="6.7" height="6.75" x="22.238" y="14.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.596078 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="iYoFexb" width="5.059" height="5.059" x="22.959" y="15.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".25"/></filter><filter id="ikGkmMe" width="5.059" height="5.059" x="3.959" y="15.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".25"/></filter><filter id="ixDSFlb" width="8.699" height="9.582" x="22.007" y="20.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.8"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="i2ES1Wb" width="8.299" height="9.532" x="1.738" y="20.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.545098 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="iZi2IWb" width="20.332" height="22.543" x="5.831" y="7.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.498039 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="i2Ds4id" width="3.73" height="1.554" x="9.049" y="12.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="isBnPld" width="3.93" height="1.754" x="8.849" y="12.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".25"/></filter><filter id="iBVnMnc" width="3.77" height="1.592" x="19.358" y="12.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="in2UmRd" width="3.97" height="1.792" x="19.158" y="12.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".25"/></filter><filter id="iJTOVCc" width="7.56" height="12.119" x="3.517" y="3.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.635294 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="i61GNHe" width="4.728" height="5.777" x="13.361" y="16.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".375"/></filter><filter id="iTlikyb" width="3.997" height="5.131" x="13.99" y="17.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".125"/></filter><filter id="iaOdoZd" width="18.74" height="14.471" x="10.037" y="1.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.764706 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3631"/></filter><filter id="iIt9wOe" width="1.505" height="1.303" x="18.82" y="16.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".05"/></filter><filter id="iacKWHe" width="1.492" height="1.541" x="20.81" y="17.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".1"/></filter><filter id="iWD1xac" width="1.701" height="1.821" x="11.981" y="16.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".1"/></filter><filter id="iCgXb0b" width="1.782" height="1.319" x="10.184" y="16.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation=".05"/></filter><filter id="i8fvhnX" width="19.318" height="13.526" x="9.635" y=".767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3631" stdDeviation="1"/></filter><linearGradient id="iupC7Je" x1="4.641" x2="6.204" y1="17.642" y2="17.642" gradientUnits="userSpaceOnUse"><stop class="faebvgbkw"/><stop offset="1" class="zj3b63b2l"/></linearGradient><linearGradient id="isy3Kee" x1="27.922" x2="26.86" y1="24.001" y2="25.642" gradientUnits="userSpaceOnUse"><stop class="x9fro9bos"/><stop offset="1" class="lg4yi3nou"/></linearGradient><linearGradient id="ifagFqc" x1="3.985" x2="4.985" y1="23.673" y2="25.11" gradientUnits="userSpaceOnUse"><stop class="vhu374_za"/><stop offset="1" class="jf5h12g1n"/></linearGradient><linearGradient id="izISEOb" x1="5.738" x2="8" y1="18.61" y2="18.61" gradientUnits="userSpaceOnUse"><stop class="kz6uw51jm"/><stop offset="1" class="jh48jobrf"/></linearGradient><linearGradient id="iEAUBpe" x1="12.029" x2="9.383" y1="13.982" y2="13.982" gradientUnits="userSpaceOnUse"><stop class="xi2s9ub1o"/><stop offset="1" class="arowiqbhr"/></linearGradient><linearGradient id="i9Nmp1b" x1="22.378" x2="19.688" y1="14.001" y2="14.001" gradientUnits="userSpaceOnUse"><stop class="xi2s9ub1o"/><stop offset="1" class="arowiqbhr"/></linearGradient><linearGradient id="iPtkGhe" x1="14.08" x2="15.481" y1="20.018" y2="20.081" gradientUnits="userSpaceOnUse"><stop class="s_x23lb-y"/><stop offset="1" class="bqi6z3beb"/></linearGradient><linearGradient id="iCBCDfb" x1="15.812" x2="15.812" y1="22.19" y2="20.428" gradientUnits="userSpaceOnUse"><stop class="zruu8dbqj"/><stop offset="1" class="jko_07g_i"/></linearGradient><linearGradient id="iUsuOMd" x1="22.06" x2="21.362" y1="17.785" y2="18.214" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijhsrdb" x1="13.328" x2="12.632" y1="17.803" y2="18.232" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:girl-medium-light" /></template>
<style>
.arowiqbhr {
  stop-color: var(--svg-color--a36f45, #A36F45);
  stop-opacity: 0;
}

.au6tbndjk {
  stop-color: var(--svg-color--c1837a, #C1837A);
}

.ax9fg1bbf {
  fill: var(--svg-color--ffc5a3, #FFC5A3);
  d: path("m23.617 21.112l6 4.03c.55.37.59 1.17.08 1.6l-3.19 2.81c-.72.64-1.85.34-2.18-.56l-2.32-6.49z");
}

.bix3bcpry {
  stroke: var(--svg-color--965c2c, #965C2C);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M22.378 14.001c-.59-.21-1.41-.36-2.47-.26");
}

.bpf5fz53d {
  cx: 11.075px;
  cy: 17.471px;
  rx: 0.865px;
  ry: 0.438px;
}

.bqi6z3beb {
  stop-color: var(--svg-color--d09676, #D09676);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn0xe4wwo {
  stop-color: var(--svg-color--f6c5a4, #F6C5A4);
}

.cvxaptb-r {
  stop-color: var(--svg-color--d7ac8b, #D7AC8B);
  stop-opacity: 0;
}

.d4nxjip-a {
  fill: var(--svg-color--000, #000);
  d: path("M12.807 18.605a1.13 1.13 0 0 0-1.134-1.134a1.13 1.13 0 0 0-1.134 1.134c0 .19.045.37.126.522h2.007c.081-.153.135-.333.135-.522");
}

.deqzvbcwp {
  stop-color: var(--svg-color--e2a68d, #E2A68D);
}

.dri9dpmkh {
  stop-color: var(--svg-color--efd59c, #EFD59C);
  stop-opacity: 0;
}

.dt6o7bc2u {
  stop-color: var(--svg-color--d7ac8b, #D7AC8B);
}

.f2znwobvf {
  stroke: var(--svg-color--965c2c, #965C2C);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M9.599 13.982c.59-.21 1.37-.315 2.43-.215");
}

.faebvgbkw {
  stop-color: var(--svg-color--bc7b67, #BC7B67);
}

.fm9vhqbuv {
  stop-color: var(--svg-color--cc9581, #CC9581);
}

.ft5dv1b6b {
  fill: none;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gls_vvbmy {
  stop-color: var(--svg-color--fee1b2, #FEE1B2);
  stop-opacity: 0;
}

.h9wqmtbbg {
  stop-color: var(--svg-color--fee1b2, #FEE1B2);
}

.hjlqtbu-h {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M25.488 19.67a2.03 2.03 0 1 0 0-4.058a2.03 2.03 0 0 0 0 4.059");
}

.i_-1mrvtn {
  d: path("m23.617 21.112l6 4.03c.55.37.59 1.17.08 1.6l-3.19 2.81c-.72.64-1.85.34-2.18-.56l-2.32-6.49z");
}

.ieoeq9k2t {
  d: path("M20.189 17.024c.141.189-.154.42-.49.67c-.336.252-.585.428-.727.24c-.141-.19.017-.547.353-.798s.723-.301.864-.112");
}

.iyvn0kbmb {
  stop-color: var(--svg-color--bc7975, #BC7975);
}

.j0v80ebyh {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.599 13.982c.59-.21 1.37-.315 2.43-.215");
}

.j23ndhcki {
  stop-color: var(--svg-color--f3bf99, #F3BF99);
}

.jcx_qeb7e {
  d: path("M25.488 19.67a2.03 2.03 0 1 0 0-4.058a2.03 2.03 0 0 0 0 4.059");
}

.jf5h12g1n {
  stop-color: var(--svg-color--e8b283, #E8B283);
  stop-opacity: 0;
}

.jgzv3_tcu {
  stop-color: var(--svg-color--fbc6a6, #FBC6A6);
}

.jh48jobrf {
  stop-color: var(--svg-color--d99e80, #D99E80);
  stop-opacity: 0;
}

.jko_07g_i {
  stop-color: var(--svg-color--c37c82, #C37C82);
  stop-opacity: 0;
}

.jt7qesbba {
  stop-color: var(--svg-color--d4c191, #D4C191);
}

.kkc0cxb4t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.189 17.024c.141.189-.154.42-.49.67c-.336.252-.585.428-.727.24c-.141-.19.017-.547.353-.798s.723-.301.864-.112");
}

.kl05g-bti {
  fill: var(--svg-color--c48874, #C48874);
  d: path("M6.488 20.892a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.kvzlxcs2e {
  d: path("M13.482 18.373c0-.64-.52-1.067-.661-1.196l-.64.619l.394.802z");
}

.kwl5p8b4p {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.002 23.265a6.5 6.5 0 0 1-3.016-.733c-.3-.16-.619.18-.429.471a4.088 4.088 0 0 0 6.89 0c.18-.28-.13-.622-.43-.471a6.35 6.35 0 0 1-3.015.733");
}

.kz6uw51jm {
  stop-color: var(--svg-color--d99e80, #D99E80);
}

.l1tcvcbwz {
  stop-color: var(--svg-color--efd59c, #EFD59C);
}

.l63ahbelw {
  fill: var(--svg-color--000, #000);
  d: path("M19.199 18.588c0-.63.504-1.136 1.136-1.136s1.136.505 1.136 1.136c0 .19-.045.37-.126.524h-2.011a1.03 1.03 0 0 1-.136-.524");
}

.lg4yi3nou {
  stop-color: var(--svg-color--ffe7b0, #FFE7B0);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll2dt01fd {
  fill: var(--svg-color--f1b995, #F1B995);
  d: path("M17.703 20.398a.72.72 0 0 1-.09.62c-.35.528-.95.874-1.62.874s-1.27-.346-1.63-.873a.72.72 0 0 1-.007-.797l1.17-2.657a.51.51 0 0 1 .934 0l1.203 2.732l.021.05l.023.051z");
}

.m4e-80bao {
  fill: var(--svg-color--c48577, #C48577);
  d: path("M17.321 20.571a.66.66 0 0 1-.127.566a1.8 1.8 0 0 1-1.557.686a1.83 1.83 0 0 1-1.44-.924a.67.67 0 0 1 .052-.735l1.272-2.363a.473.473 0 0 1 .862.068l.909 2.606l.016.047l.017.05z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgr9d0bbh {
  d: path("M22.102 18.327a1.87 1.87 0 0 0-.514-1.029l-.578.635l.26.507z");
}

.mnikv3jnk {
  stop-color: var(--svg-color--ecc69a, #ECC69A);
}

.mstcoz5vv {
  d: path("M26.954 12.205c-10.844.833-15.319-4.41-15.319-9.438h6.205c7.291 0 9.114 6.292 9.114 9.438");
}

.nanijx3af {
  d: path("M6.488 19.67a2.03 2.03 0 1 0 0-4.058a2.03 2.03 0 0 0 0 4.059");
}

.ngglvlb8p {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M22.378 14.001c-.59-.21-1.41-.36-2.47-.26");
}

.ntre80m-m {
  d: path("M20.335 16.604a1.984 1.984 0 0 1 1.912 2.508h-3.833a2 2 0 0 1-.072-.523c0-1.092.893-1.985 1.993-1.985");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omhdffyfp {
  stop-color: var(--svg-color--fbc6a6, #FBC6A6);
  stop-opacity: 0;
}

.oroa7vwoo {
  d: path("m8.427 21.112l-6 4.03c-.55.37-.59 1.17-.08 1.6l3.19 2.81c.72.64 1.85.34 2.18-.56l2.32-6.49z");
}

.oz5kevsqv {
  d: path("M25.488 20.892a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.oze4hdc_s {
  stop-color: var(--svg-color--ffffc9, #FFFFC9);
  stop-opacity: 0;
}

.p0e1uebyo {
  d: path("M18.847 12.892c-5.004-.844-8.81-3.94-8.81-8.81c0-1.21.98-2.19 2.18-2.19h5.81c5.52 0 10 4.48 10 10v3.72a3.25 3.25 0 0 0-1.883-1.154l.02-.555a.48.48 0 0 0-.413-.498c-.85-.113-1.976-.171-3.157-.232c-1.28-.066-2.624-.136-3.747-.281");
}

.p13tn10da {
  stop-color: var(--svg-color--de9f8c, #DE9F8C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm2an5o7k {
  stop-color: var(--svg-color--e2a27d, #E2A27D);
}

.q-hbhfb7u {
  stop-color: var(--svg-color--c1837a, #C1837A);
  stop-opacity: 0;
}

.q4na5j0rh {
  d: path("M17.703 20.398a.72.72 0 0 1-.09.62c-.35.528-.95.874-1.62.874s-1.27-.346-1.63-.873a.72.72 0 0 1-.007-.797l1.17-2.657a.51.51 0 0 1 .934 0l1.203 2.732l.021.05l.023.051z");
}

.qrc2bisni {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.795 16a3.105 3.105 0 0 1 3.012 2.354a.61.61 0 0 1-.595.758h-4.96a.512.512 0 0 1-.506-.605A3.11 3.11 0 0 1 20.795 16");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.rjmsdzbap {
  stop-color: var(--svg-color--b36d8b, #B36D8B);
  stop-opacity: 0;
}

.s_-r2acdm {
  fill: var(--svg-color--f4dda0, #F4DDA0);
  d: path("M18.847 12.892c-5.004-.844-8.81-3.94-8.81-8.81c0-1.21.98-2.19 2.18-2.19h5.81c5.52 0 10 4.48 10 10v3.72a3.25 3.25 0 0 0-1.883-1.154l.02-.555a.48.48 0 0 0-.413-.498c-.85-.113-1.976-.171-3.157-.232c-1.28-.066-2.624-.136-3.747-.281");
}

.s_x23lb-y {
  stop-color: var(--svg-color--d09676, #D09676);
}

.sb6eau4zv {
  stop-color: var(--svg-color--ffffc9, #FFFFC9);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.tbjyjpzjq {
  d: path("M4.017 10.952c0-3.9 3.16-7.06 7.06-7.06v.97c0 3.18-.46 6.905-4.522 8.655c-.339.146-.68.328-.726.937c-.602.14-1.29.477-1.795 1.056a7 7 0 0 1-.017-.488z");
}

.tjmo9ub5q {
  stop-color: var(--svg-color--de9f8c, #DE9F8C);
}

.tzchu9qsk {
  d: path("M11.673 16.625a1.98 1.98 0 0 0-1.909 2.502h3.826a2 2 0 0 0 .072-.522a1.994 1.994 0 0 0-1.99-1.98");
}

.u30bsrkfu {
  fill: var(--svg-color--e9ad91, #E9AD91);
  d: path("m8.427 21.112l-6 4.03c-.55.37-.59 1.17-.08 1.6l3.19 2.81c.72.64 1.85.34 2.18-.56l2.32-6.49z");
}

.u42k9fb7y {
  stop-color: var(--svg-color--b36d8b, #B36D8B);
}

.v_tdjh1fb {
  stop-color: var(--svg-color--bc7975, #BC7975);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vhu374_za {
  stop-color: var(--svg-color--e8b283, #E8B283);
}

.vijwexbvn {
  stop-color: var(--svg-color--f3bf99, #F3BF99);
  stop-opacity: 0;
}

.vmwe85bmx {
  stop-color: var(--svg-color--e2a27d, #E2A27D);
  stop-opacity: 0;
}

.vp_82byvi {
  cx: 11.075px;
  cy: 17.471px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.865px;
  ry: 0.438px;
}

.vwkt462qc {
  stop-color: var(--svg-color--d4c191, #D4C191);
  stop-opacity: 0;
}

.w43borwfn {
  stop-color: var(--svg-color--dfca91, #DFCA91);
}

.wm0dr9b9p {
  stop-color: var(--svg-color--ffc69c, #FFC69C);
}

.x9fro9bos {
  stop-color: var(--svg-color--ffe7b0, #FFE7B0);
}

.xi2s9ub1o {
  stop-color: var(--svg-color--a36f45, #A36F45);
}

.yvajbz8lc {
  d: path("M18.847 12.892c-3.6-.608-6.582-2.381-7.97-5.143c-.383 2.316-1.456 4.533-4.322 5.768c-.333.143-.668.322-.724.907l.193 5.683c.24 5.858 4.624 9.785 9.964 9.785c5.331 0 9.726-3.927 9.965-9.785l.21-6.204a.48.48 0 0 0-.412-.498c-.85-.113-1.976-.171-3.157-.232c-1.28-.066-2.624-.136-3.747-.281");
}

.zj3b63b2l {
  stop-color: var(--svg-color--b3745d, #B3745D);
}

.zrdieeknv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.214 16.022a3.1 3.1 0 0 0-3.007 2.35a.608.608 0 0 0 .594.755h4.951a.51.51 0 0 0 .504-.603a3.11 3.11 0 0 0-3.042-2.502");
}

.zruu8dbqj {
  stop-color: var(--svg-color--c37c82, #C37C82);
}

</style>
