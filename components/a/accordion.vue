<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEWvlMx)"><path fill="url(#i4YS05u)" class="xf1pikbxv"/><path fill="url(#i2LzflE)" class="xf1pikbxv"/></g><g filter="url(#iTLLqdb)"><path fill="url(#ioKmlIe)" class="yc32d4bvg"/></g><g filter="url(#iiJRchc)"><path class="ff_omwbij"/></g><path fill="url(#iDKVZPe)" class="s_f-7rbha"/><path fill="url(#izRByoc)" class="s_f-7rbha"/><path fill="url(#iyfHQpq)" class="s_f-7rbha"/><path fill="url(#i14ubgc)" class="l7r6awbqe"/><path fill="url(#ilYkrbb)" class="l7r6awbqe"/><path fill="url(#iu1i8Gb)" class="l7r6awbqe"/><path fill="url(#innyCjd)" class="ht7ax9bvn"/><path fill="url(#ib56mAc)" class="ht7ax9bvn"/><path fill="url(#if6gmkb)" class="ht7ax9bvn"/><path fill="url(#iJa5cIc)" class="z4f5fibfw"/><path fill="url(#iXvrIGc)" class="z4f5fibfw"/><path fill="url(#i07UwSc)" class="z4f5fibfw"/><path fill="url(#iBD5uMI)" class="oy59mobsl"/><path fill="url(#ijZIgGc)" class="oy59mobsl"/><path fill="url(#iJHXwre)" class="oy59mobsl"/><path fill="url(#iJHXwre)" class="oy59mobsl"/><path fill="url(#iBQFkqc)" class="fxivlac-m"/><path fill="url(#icbaLib)" class="fxivlac-m"/><path fill="url(#iT01F3b)" class="fxivlac-m"/><path fill="url(#iT01F3b)" class="fxivlac-m"/><path fill="url(#ihQ0cUh)" class="fct13fbnq"/><path fill="url(#i8QDtPc)" class="fct13fbnq"/><path fill="url(#iXDVhbc)" class="fct13fbnq"/><path fill="url(#iiu6Pmd)" class="ixl4ljbol"/><path fill="url(#iO8WH5c)" class="ixl4ljbol"/><path fill="url(#iweGw8u)" class="ixl4ljbol"/><path fill="url(#iIbvZfj)" class="of03x4fnj"/><path fill="url(#iTGvrqc)" class="of03x4fnj"/><path fill="url(#iJPLMme)" class="of03x4fnj"/><path fill="url(#iyJBp8c)" class="kbjbkqb1k"/><path fill="url(#iNrsZSb)" class="kbjbkqb1k"/><path fill="url(#inuNtAc)" class="kbjbkqb1k"/><g filter="url(#i56sYve)"><path class="f4jjqpwmn"/></g><g filter="url(#iqCtRSd)"><path class="wg40-kbxs"/></g><g filter="url(#iHkNBFb)"><path class="a_wzurf5i"/></g><g filter="url(#iWHOt7d)"><path class="ul8g4tb7c"/></g><g filter="url(#iBjlXBc)"><path class="if9mleaey"/></g><g filter="url(#ip74vdF)"><path class="y33boeghi"/></g><g filter="url(#i0uWrke)"><path class="hkdgnkbsx"/></g><g filter="url(#iaqRPYy)"><path fill="url(#iUinJRd)" class="l2257ya7n"/></g><g filter="url(#i3nZgeb)"><path fill="url(#i5PJDFd)" class="n7ocz0bdg"/></g><g filter="url(#iGKKz6b)"><path fill="url(#i7xYObe)" class="praylff0j"/></g><g filter="url(#i3KYMjb)"><path fill="url(#ij2fbLb)" class="sgaijxw5r"/></g><g filter="url(#izEP6hc)"><path fill="url(#iCaJnhx)" class="x0e16ccqv"/></g><g filter="url(#iIeAVTw)"><path fill="url(#i6jTqme)" class="r0jrjtbzm"/></g><g filter="url(#i4VH53b)"><path fill="url(#ivmStyc)" class="rajw40b-o"/></g><g filter="url(#irt1DdV)"><path class="wtdk0s_sl"/></g><g filter="url(#iZIAYxd)"><path class="hdtcilbml"/></g><g filter="url(#iBOyBYK)"><path class="i93a1zb-a"/></g><g filter="url(#inYGF5b)"><path stroke="url(#iK4EGqD)" class="jzx72pknm"/></g><g filter="url(#iJHsiZb)"><path stroke="url(#i7Zsbvb)" class="v885acbyt"/></g><g filter="url(#ip68TFB)"><path stroke="url(#ieUgKgb)" class="gexv6vbft"/></g><g filter="url(#i2gVC6U)"><path stroke="url(#iNXeToZ)" class="m_a1vnbef"/></g><g filter="url(#iVvWONd)"><path stroke="url(#iYzFDlc)" class="ipt2-3geo"/></g><g filter="url(#ivq53Fe)"><path stroke="url(#i1el64c)" class="dd6kkkqpk"/></g><g filter="url(#ipniaZb)"><circle fill="url(#iQaKQPb)" class="xw9f1rbld"/><circle fill="url(#iu8c4Le)" class="xw9f1rbld"/></g><g filter="url(#iPLG1ve)"><circle fill="url(#itv4vec)" class="w_0lzcg7e"/><circle fill="url(#i8R5hHb)" class="w_0lzcg7e"/></g><g filter="url(#iLA5K9d)"><circle fill="url(#iVPDIrd)" class="vy5nfxpgl"/><circle fill="url(#i0O0plg)" class="vy5nfxpgl"/></g><g filter="url(#iHf021b)"><circle fill="url(#i2LeSwl)" class="koj922bzb"/><circle fill="url(#iXEWlvd)" class="koj922bzb"/></g><g filter="url(#iwIStUc)"><circle fill="url(#iXl6hMc)" class="zi3-f2kwa"/><circle fill="url(#ihJnj7x)" class="zi3-f2kwa"/></g><g filter="url(#ig1IuIb)"><circle fill="url(#iU2kMhd)" class="epvvr9dci"/><circle fill="url(#iSG0ggb)" class="epvvr9dci"/></g><g filter="url(#iinCEDa)"><circle fill="url(#iLISNQe)" class="jtyvh_b7j"/><circle fill="url(#iQTPDid)" class="jtyvh_b7j"/></g><g filter="url(#iGHbzbe)"><circle fill="url(#iiagcHv)" class="mbc01qbev"/><circle fill="url(#iRCIJ6b)" class="mbc01qbev"/></g><g filter="url(#iT8GE9b)"><circle fill="url(#iUvdPwd)" class="dzmefl78e"/><circle fill="url(#iBmaRad)" class="dzmefl78e"/></g><g filter="url(#iBUFyVd)"><circle fill="url(#iNc6zQe)" class="xbeoe-gfa"/><circle fill="url(#iBRSsqc)" class="xbeoe-gfa"/></g><g filter="url(#iD1Xl8W)"><circle fill="url(#iRV4eQc)" class="rzsbwlbst"/><circle fill="url(#iNq4P8m)" class="rzsbwlbst"/></g><g filter="url(#iCSLDgG)"><circle fill="url(#i1MeP6d)" class="t13458b-a"/><circle fill="url(#iDu8kuy)" class="t13458b-a"/></g><g filter="url(#iohsbNb)"><path fill="url(#iIOAEsd)" class="tue6eugyq"/><path fill="url(#iMciuBe)" class="tue6eugyq"/></g><defs><linearGradient id="i4YS05u" x1="17.215" x2="18.551" y1="3.79" y2="24.24" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s1t6g6y2l"/><stop offset="1" class="jufiuqe8v"/></linearGradient><linearGradient id="ioKmlIe" x1="30.301" x2="21.489" y1="6.677" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="b4mcazbkx"/><stop offset="1" class="l7q-p1bsd"/></linearGradient><linearGradient id="iDKVZPe" x1="5.765" x2="5.347" y1="8.633" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="emfa8_c3l"/><stop offset="1" class="lxr2_5bhx"/></linearGradient><linearGradient id="izRByoc" x1="9.034" x2="7.699" y1="7.835" y2="8.194" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iyfHQpq" x1="5.176" x2="5.114" y1="9.404" y2="9.146" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="i14ubgc" x1="6.204" x2="5.725" y1="10.746" y2="8.872" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="ilYkrbb" x1="9.518" x2="8.182" y1="9.826" y2="10.185" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iu1i8Gb" x1="5.66" x2="5.597" y1="11.395" y2="11.137" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="innyCjd" x1="6.687" x2="6.209" y1="12.737" y2="10.863" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="ib56mAc" x1="10.001" x2="8.666" y1="11.817" y2="12.176" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="if6gmkb" x1="6.143" x2="6.081" y1="13.386" y2="13.128" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iJa5cIc" x1="7.171" x2="6.692" y1="14.728" y2="12.854" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="iXvrIGc" x1="10.485" x2="9.149" y1="13.808" y2="14.167" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="i07UwSc" x1="6.627" x2="6.564" y1="15.376" y2="15.119" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iBD5uMI" x1="7.654" x2="7.176" y1="16.718" y2="14.845" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="ijZIgGc" x1="10.968" x2="9.633" y1="15.799" y2="16.158" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iJHXwre" x1="7.11" x2="7.048" y1="17.367" y2="17.109" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iBQFkqc" x1="8.138" x2="7.659" y1="18.711" y2="16.836" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="icbaLib" x1="11.451" x2="10.116" y1="17.791" y2="18.149" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iT01F3b" x1="7.594" x2="7.531" y1="19.36" y2="19.102" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="ihQ0cUh" x1="8.621" x2="8.143" y1="20.7" y2="18.826" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="i8QDtPc" x1="11.935" x2="10.6" y1="19.781" y2="20.14" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iXDVhbc" x1="8.077" x2="8.015" y1="21.349" y2="21.091" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iiu6Pmd" x1="9.105" x2="8.626" y1="22.691" y2="20.817" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="iO8WH5c" x1="12.419" x2="11.083" y1="21.771" y2="22.13" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iweGw8u" x1="8.56" x2="8.498" y1="23.34" y2="23.082" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iIbvZfj" x1="9.588" x2="9.11" y1="24.682" y2="22.808" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="iTGvrqc" x1="12.902" x2="11.567" y1="23.762" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="iJPLMme" x1="9.044" x2="8.981" y1="25.331" y2="25.073" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iyJBp8c" x1="10.072" x2="9.593" y1="26.673" y2="24.799" gradientUnits="userSpaceOnUse"><stop class="euhpb0bis"/><stop offset="1" class="nwatl5but"/></linearGradient><linearGradient id="iNrsZSb" x1="13.386" x2="12.05" y1="25.753" y2="26.112" gradientUnits="userSpaceOnUse"><stop class="wvg4obbwy"/><stop offset="1" class="dtfs_6bda"/></linearGradient><linearGradient id="inuNtAc" x1="9.527" x2="9.465" y1="27.322" y2="27.064" gradientUnits="userSpaceOnUse"><stop offset=".19" class="etan2xy7o"/><stop offset="1" class="kevm16jfu"/></linearGradient><linearGradient id="iUinJRd" x1="7.082" x2="9.215" y1="9.232" y2="8.732" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="i5PJDFd" x1="7.539" x2="9.672" y1="11.205" y2="10.705" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="i7xYObe" x1="8.586" x2="10.719" y1="15.199" y2="14.699" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="ij2fbLb" x1="9.069" x2="11.202" y1="17.21" y2="16.71" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="iCaJnhx" x1="9.553" x2="11.686" y1="19.183" y2="18.683" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="i6jTqme" x1="10.52" x2="12.653" y1="23.199" y2="22.699" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="ivmStyc" x1="11.004" x2="13.136" y1="25.172" y2="24.672" gradientUnits="userSpaceOnUse"><stop class="oq8yqv8oa"/><stop offset="1" class="zalzrpb2d"/></linearGradient><linearGradient id="iK4EGqD" x1="14.301" x2="17.887" y1="4.279" y2="26.865" gradientUnits="userSpaceOnUse"><stop class="nxa7axj7c"/><stop offset="1" class="gncae_39n"/></linearGradient><linearGradient id="i7Zsbvb" x1="14.301" x2="19.801" y1="4.279" y2="35.427" gradientUnits="userSpaceOnUse"><stop class="bre8vnbtz"/><stop offset="1" class="q-urprqob"/></linearGradient><linearGradient id="ieUgKgb" x1="17.293" x2="24.825" y1="3.724" y2="24.668" gradientUnits="userSpaceOnUse"><stop class="nxa7axj7c"/><stop offset="1" class="gncae_39n"/></linearGradient><linearGradient id="iNXeToZ" x1="17.221" x2="28.397" y1="3.764" y2="32.451" gradientUnits="userSpaceOnUse"><stop class="bre8vnbtz"/><stop offset="1" class="q-urprqob"/></linearGradient><linearGradient id="iYzFDlc" x1="19.903" x2="31.453" y1="4.06" y2="14.133" gradientUnits="userSpaceOnUse"><stop class="nxa7axj7c"/><stop offset="1" class="gncae_39n"/></linearGradient><linearGradient id="i1el64c" x1="19.88" x2="35.791" y1="4.1" y2="16.907" gradientUnits="userSpaceOnUse"><stop class="bre8vnbtz"/><stop offset="1" class="q-urprqob"/></linearGradient><linearGradient id="iIOAEsd" x1="14.614" x2="4.864" y1="19.177" y2="22.302" gradientUnits="userSpaceOnUse"><stop class="bn7a9ebba"/><stop offset="1" class="tqijppbjz"/></linearGradient><linearGradient id="iMciuBe" x1="15.614" x2="14.739" y1="17.427" y2="17.662" gradientUnits="userSpaceOnUse"><stop offset=".418" class="u1qrckbcu"/><stop offset="1" class="b-vf28w9g"/></linearGradient><filter id="iEWvlMx" width="11.766" height="21.9" x="11.332" y="3.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.721569 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="iTLLqdb" width="10.059" height="23.933" x="19.929" y="3.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.337255 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.133333 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18515" result="effect2_innerShadow_18_18515"/></filter><filter id="iiJRchc" width="15.616" height="24.356" x="1.78" y="4.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.141176 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="i56sYve" width="5.266" height="2.774" x="5.565" y="7.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iqCtRSd" width="5.266" height="2.774" x="6.021" y="9.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iHkNBFb" width="5.266" height="2.774" x="7.068" y="13.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iWHOt7d" width="5.266" height="2.774" x="7.552" y="15.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iBjlXBc" width="5.266" height="2.774" x="8.035" y="17.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="ip74vdF" width="5.266" height="2.774" x="9.002" y="21.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="i0uWrke" width="5.266" height="2.774" x="9.486" y="23.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iaqRPYy" width="4.366" height="1.774" x="6.111" y="7.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="i3nZgeb" width="4.366" height="1.774" x="6.567" y="9.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="iGKKz6b" width="4.366" height="1.774" x="7.615" y="13.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="i3KYMjb" width="4.366" height="1.774" x="8.098" y="15.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="izEP6hc" width="4.366" height="1.774" x="8.582" y="17.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="iIeAVTw" width="4.366" height="1.774" x="9.549" y="21.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="i4VH53b" width="4.366" height="1.774" x="10.032" y="23.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="irt1DdV" width="5.398" height="22.067" x="13.301" y="4.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iZIAYxd" width="3.532" height="22.497" x="16.136" y="3.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="iBOyBYK" width="2.474" height="22.208" x="18.609" y="4.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".25"/></filter><filter id="inYGF5b" width="4.686" height="22.317" x="13.801" y="3.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.427451 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="iJHsiZb" width="4.219" height="21.719" x="14.082" y="3.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".125"/></filter><filter id="ip68TFB" width="2.717" height="22.77" x="16.793" y="3.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.427451 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="i2gVC6U" width="2.406" height="21.969" x="17.051" y="3.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".125"/></filter><filter id="iVvWONd" width="1.6" height="22.466" x="19.403" y="3.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.427451 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/></filter><filter id="ivq53Fe" width="1.25" height="22.031" x="19.707" y="3.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18515" stdDeviation=".125"/></filter><filter id="ipniaZb" width="1.827" height="1.827" x="26.839" y="7.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iPLG1ve" width="1.827" height="1.827" x="26.479" y="10.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iLA5K9d" width="1.827" height="1.827" x="26.12" y="12.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iHf021b" width="1.827" height="1.827" x="25.792" y="15.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iwIStUc" width="1.827" height="1.827" x="25.436" y="18.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="ig1IuIb" width="1.827" height="1.827" x="25.093" y="21.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iinCEDa" width="1.827" height="1.827" x="24.671" y="7.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iGHbzbe" width="1.827" height="1.827" x="24.311" y="10.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iT8GE9b" width="1.827" height="1.827" x="23.952" y="13.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iBUFyVd" width="1.827" height="1.827" x="23.624" y="16.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iD1Xl8W" width="1.827" height="1.827" x="23.268" y="19.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iCSLDgG" width="1.827" height="1.827" x="22.925" y="22.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18515"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18515" result="shape"/></filter><filter id="iohsbNb" width="15.751" height="24.555" x="1.745" y="4.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.270588 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18515"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.270588 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18515" result="effect2_innerShadow_18_18515"/></filter><radialGradient id="i2LzflE" cx="0" cy="0" r="1" gradientTransform="matrix(-.92193 6.28124 -1.69415 -.24866 23.099 5.302)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="w3njnhday"/><stop offset="1" class="evmyrr9dw"/></radialGradient><radialGradient id="iQaKQPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 28.302 7.724)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iu8c4Le" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 27.77 8.591)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="itv4vec" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 27.943 10.661)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="i8R5hHb" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 27.41 11.529)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iVPDIrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 .59375 -.505 -.62461 27.582 13.6)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="i0O0plg" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 27.051 14.466)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="i2LeSwl" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 27.254 16.54)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iXEWlvd" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 26.723 17.408)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iXl6hMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 26.899 19.482)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="ihJnj7x" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 26.368 20.35)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iU2kMhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 26.554 22.428)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iSG0ggb" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 26.024 23.294)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iLISNQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 26.132 8.477)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iQTPDid" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 25.602 9.345)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iiagcHv" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 25.774 11.416)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iRCIJ6b" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 25.243 12.283)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iUvdPwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 25.414 14.351)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iBmaRad" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 24.883 15.22)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iNc6zQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 25.087 17.295)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iBRSsqc" cx="0" cy="0" r="1" gradientTransform="rotate(-82.333 22.663 -4.96)scale(.61487 .93031)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="iRV4eQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 24.73 20.235)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iNq4P8m" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60938 .922 .12411 24.2 21.103)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient><radialGradient id="i1MeP6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .59375 -.505 -.6246 24.387 23.18)" gradientUnits="userSpaceOnUse"><stop class="k4tludulq"/><stop offset="1" class="d9ok6gbhu"/></radialGradient><radialGradient id="iDu8kuy" cx="0" cy="0" r="1" gradientTransform="matrix(.08203 -.60937 .922 .12412 23.856 24.05)" gradientUnits="userSpaceOnUse"><stop class="b82n6xbzs"/><stop offset="1" class="fg6q6mxum"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:accordion" /></template>
<style>
.a_wzurf5i {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M7.583 15.212a.463.463 0 0 1 .335-.563l3.34-.847a.463.463 0 0 1 .227.898l-3.34.847a.463.463 0 0 1-.562-.335");
}

.b-vf28w9g {
  stop-color: var(--svg-color--ff57a3, #FF57A3);
  stop-opacity: 0;
}

.b4mcazbkx {
  stop-color: var(--svg-color--f13781, #F13781);
}

.b82n6xbzs {
  stop-color: var(--svg-color--dea6d6, #DEA6D6);
}

.bn7a9ebba {
  stop-color: var(--svg-color--f4378e, #F4378E);
}

.bre8vnbtz {
  stop-color: var(--svg-color--ffbb7e, #FFBB7E);
}

.d9ok6gbhu {
  stop-color: var(--svg-color--d8b3cd, #D8B3CD);
}

.dd6kkkqpk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m20.582 3.99l-.5 21.281");
}

.dtfs_6bda {
  stop-color: var(--svg-color--e2c3d1, #E2C3D1);
  stop-opacity: 0;
}

.dzmefl78e {
  cx: 24.965px;
  cy: 14.552px;
  r: 0.613px;
}

.emfa8_c3l {
  stop-color: var(--svg-color--e7d2da, #E7D2DA);
}

.epvvr9dci {
  cx: 26.106px;
  cy: 22.627px;
  r: 0.613px;
}

.etan2xy7o {
  stop-color: var(--svg-color--ca77ad, #CA77AD);
}

.euhpb0bis {
  stop-color: var(--svg-color--e8d5dd, #E8D5DD);
}

.evmyrr9dw {
  stop-color: var(--svg-color--e1a37d, #E1A37D);
  stop-opacity: 0;
}

.f4jjqpwmn {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M6.079 9.246a.463.463 0 0 1 .335-.563l3.34-.848a.463.463 0 1 1 .227.898l-3.34.848a.463.463 0 0 1-.562-.335");
}

.fct13fbnq {
  d: path("M5.657 20.101a.35.35 0 0 1 .257-.424l5.62-1.381a.35.35 0 0 1 .422.256l.318 1.31a.35.35 0 0 1-.257.424l-5.62 1.382a.35.35 0 0 1-.422-.257z");
}

.ff_omwbij {
  fill: var(--svg-color--c83563, #C83563);
  d: path("M12.51 5.608a1.4 1.4 0 0 0-1.7-1.027L2.84 6.574a1.4 1.4 0 0 0-1.02 1.691l4.775 19.463a1.4 1.4 0 0 0 1.697 1.025l7.94-1.968a1.4 1.4 0 0 0 1.024-1.69z");
}

.fg6q6mxum {
  stop-color: var(--svg-color--dea6d6, #DEA6D6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxivlac-m {
  d: path("M5.174 18.113a.35.35 0 0 1 .257-.426l5.619-1.382a.35.35 0 0 1 .423.259l.317 1.307a.35.35 0 0 1-.257.426l-5.618 1.382a.35.35 0 0 1-.424-.259z");
}

.gexv6vbft {
  stroke-linecap: round;
  d: path("m17.293 3.724l1.617 21.57");
}

.gncae_39n {
  stop-color: var(--svg-color--fb916d, #FB916D);
}

.hdtcilbml {
  stroke: var(--svg-color--fcbd90, #FCBD90);
  stroke-linecap: round;
  d: path("M17.136 4.802L18.67 25.3");
}

.hkdgnkbsx {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M10 25.186a.463.463 0 0 1 .335-.563l3.34-.847a.463.463 0 1 1 .227.897l-3.34.848a.463.463 0 0 1-.562-.335");
}

.ht7ax9bvn {
  d: path("M3.723 12.138a.35.35 0 0 1 .258-.424l5.618-1.382a.35.35 0 0 1 .423.257l.318 1.31a.35.35 0 0 1-.257.424l-5.62 1.381a.35.35 0 0 1-.422-.256z");
}

.i93a1zb-a {
  stroke: var(--svg-color--fcbd90, #FCBD90);
  stroke-linecap: round;
  d: path("m20.082 5.122l-.473 20.207");
}

.if9mleaey {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M8.55 19.197a.463.463 0 0 1 .335-.563l3.339-.847a.463.463 0 0 1 .228.898l-3.34.847a.463.463 0 0 1-.562-.335");
}

.ipt2-3geo {
  stroke-linecap: round;
  d: path("m20.403 4.06l-.5 21.266");
}

.ixl4ljbol {
  d: path("M6.14 22.092a.35.35 0 0 1 .258-.424l5.619-1.381a.35.35 0 0 1 .422.256l.318 1.31a.35.35 0 0 1-.257.424l-5.619 1.381a.35.35 0 0 1-.422-.256z");
}

.jtyvh_b7j {
  cx: 25.684px;
  cy: 8.677px;
  r: 0.613px;
}

.jufiuqe8v {
  stop-color: var(--svg-color--ffad98, #FFAD98);
}

.jzx72pknm {
  stroke-linecap: round;
  d: path("m14.301 4.279l3.586 21.117");
}

.k4tludulq {
  stop-color: var(--svg-color--fff9f1, #FFF9F1);
}

.kbjbkqb1k {
  d: path("M7.108 26.073a.35.35 0 0 1 .257-.423l5.619-1.382a.35.35 0 0 1 .422.257l.318 1.31a.35.35 0 0 1-.257.424L7.848 27.64a.35.35 0 0 1-.422-.256z");
}

.kevm16jfu {
  stop-color: var(--svg-color--d9c0d2, #D9C0D2);
  stop-opacity: 0;
}

.koj922bzb {
  cx: 26.805px;
  cy: 16.74px;
  r: 0.613px;
}

.l2257ya7n {
  d: path("M6.125 9.082a.463.463 0 0 1 .335-.563L9.8 7.67a.463.463 0 1 1 .228.898l-3.34.848a.463.463 0 0 1-.563-.335");
}

.l7q-p1bsd {
  stop-color: var(--svg-color--f03791, #F03791);
}

.l7r6awbqe {
  d: path("M3.24 10.147a.35.35 0 0 1 .257-.424l5.619-1.382a.35.35 0 0 1 .422.257l.318 1.31a.35.35 0 0 1-.257.424L3.98 11.713a.35.35 0 0 1-.422-.256z");
}

.lxr2_5bhx {
  stop-color: var(--svg-color--e0b9cb, #E0B9CB);
}

.m_a1vnbef {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m17.426 3.771l1.656 21.219");
}

.mbc01qbev {
  cx: 25.325px;
  cy: 11.615px;
  r: 0.613px;
}

.n7ocz0bdg {
  d: path("M6.582 11.055a.463.463 0 0 1 .335-.563l3.34-.848a.463.463 0 1 1 .227.898l-3.34.848a.463.463 0 0 1-.562-.335");
}

.nwatl5but {
  stop-color: var(--svg-color--e3cfd8, #E3CFD8);
}

.nxa7axj7c {
  stop-color: var(--svg-color--f59d5d, #F59D5D);
}

.of03x4fnj {
  d: path("M6.624 24.083a.35.35 0 0 1 .257-.424l5.62-1.381a.35.35 0 0 1 .422.256l.318 1.31a.35.35 0 0 1-.257.424l-5.62 1.381a.35.35 0 0 1-.422-.256z");
}

.oq8yqv8oa {
  stop-color: var(--svg-color--4b3f57, #4B3F57);
}

.oy59mobsl {
  d: path("M4.69 16.12a.35.35 0 0 1 .257-.425l5.62-1.381a.35.35 0 0 1 .422.256l.318 1.31a.35.35 0 0 1-.257.424l-5.62 1.382a.35.35 0 0 1-.422-.257z");
}

.praylff0j {
  d: path("M7.63 15.048a.463.463 0 0 1 .334-.563l3.34-.847a.463.463 0 0 1 .227.898l-3.34.847a.463.463 0 0 1-.562-.335");
}

.q-urprqob {
  stop-color: var(--svg-color--fb916d, #FB916D);
  stop-opacity: 0;
}

.r0jrjtbzm {
  d: path("M9.563 23.049a.463.463 0 0 1 .335-.563l3.34-.848a.463.463 0 1 1 .227.898l-3.34.848a.463.463 0 0 1-.562-.335");
}

.rajw40b-o {
  d: path("M10.046 25.022a.463.463 0 0 1 .335-.563l3.34-.848a.463.463 0 0 1 .228.898l-3.34.848a.463.463 0 0 1-.563-.335");
}

.rzsbwlbst {
  cx: 24.282px;
  cy: 20.435px;
  r: 0.613px;
}

.s_f-7rbha {
  d: path("M2.756 8.156a.35.35 0 0 1 .258-.424l5.618-1.381a.35.35 0 0 1 .423.256l.318 1.31a.35.35 0 0 1-.257.424L3.497 9.723a.35.35 0 0 1-.422-.257z");
}

.s1t6g6y2l {
  stop-color: var(--svg-color--ffd8a7, #FFD8A7);
}

.sgaijxw5r {
  d: path("M8.112 17.06a.463.463 0 0 1 .335-.563l3.34-.847a.463.463 0 0 1 .228.897l-3.34.848a.463.463 0 0 1-.563-.335");
}

.t13458b-a {
  cx: 23.938px;
  cy: 23.38px;
  r: 0.613px;
}

.tqijppbjz {
  stop-color: var(--svg-color--ec3882, #EC3882);
}

.tue6eugyq {
  d: path("M10.81 4.581a1.4 1.4 0 0 1 1.7 1.027l4.746 19.487a1.4 1.4 0 0 1-1.023 1.69l-7.941 1.968a1.4 1.4 0 0 1-1.314-.355c-.218-.213-.055-.541.241-.614l5.513-1.348a.7.7 0 0 0 .514-.846L8.712 7.054a.7.7 0 0 0-.846-.513L2.36 7.887c-.301.074-.6-.15-.493-.441c.156-.419.508-.756.974-.872z");
}

.u1qrckbcu {
  stop-color: var(--svg-color--ff57a3, #FF57A3);
}

.ul8g4tb7c {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M8.066 17.224a.463.463 0 0 1 .335-.563l3.34-.847a.463.463 0 1 1 .227.898l-3.339.847a.463.463 0 0 1-.563-.335");
}

.v885acbyt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m14.457 4.24l3.47 20.969");
}

.vy5nfxpgl {
  cx: 27.133px;
  cy: 13.798px;
  r: 0.613px;
}

.w_0lzcg7e {
  cx: 27.493px;
  cy: 10.861px;
  r: 0.613px;
}

.w3njnhday {
  stop-color: var(--svg-color--e1a37d, #E1A37D);
}

.wg40-kbxs {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M6.535 11.219a.463.463 0 0 1 .335-.563l3.34-.847a.463.463 0 1 1 .228.897l-3.34.848a.463.463 0 0 1-.563-.335");
}

.wtdk0s_sl {
  stroke: var(--svg-color--fcbd90, #FCBD90);
  stroke-linecap: round;
  d: path("M14.301 5.33L17.7 25.395");
}

.wvg4obbwy {
  stop-color: var(--svg-color--bd8da4, #BD8DA4);
}

.x0e16ccqv {
  d: path("M8.596 19.033a.463.463 0 0 1 .335-.563l3.34-.847a.463.463 0 0 1 .227.898l-3.34.847a.463.463 0 0 1-.562-.335");
}

.xbeoe-gfa {
  cx: 24.637px;
  cy: 17.494px;
  r: 0.613px;
}

.xf1pikbxv {
  d: path("M23.098 4.896c-4.8-2.225-9.87-.583-11.766.5l5.5 20.094c2.175-.325 3.74-.26 4.25-.188z");
}

.xw9f1rbld {
  cx: 27.852px;
  cy: 7.923px;
  r: 0.613px;
}

.y33boeghi {
  fill: var(--svg-color--bfa5b6, #BFA5B6);
  d: path("M9.517 23.213a.463.463 0 0 1 .335-.563l3.339-.848a.463.463 0 0 1 .228.898l-3.34.848a.463.463 0 0 1-.562-.335");
}

.yc32d4bvg {
  d: path("M22.716 4.678a.8.8 0 0 1 .885-.705l5.277.6a.8.8 0 0 1 .705.886L27.2 26.391a.8.8 0 0 1-.886.705l-5.277-.6a.8.8 0 0 1-.704-.886z");
}

.z4f5fibfw {
  d: path("M4.207 14.128a.35.35 0 0 1 .257-.423l5.619-1.382a.35.35 0 0 1 .422.257l.318 1.31a.35.35 0 0 1-.257.424l-5.619 1.381a.35.35 0 0 1-.422-.256z");
}

.zalzrpb2d {
  stop-color: var(--svg-color--3a2c40, #3A2C40);
}

.zi3-f2kwa {
  cx: 26.45px;
  cy: 19.681px;
  r: 0.613px;
}

</style>
