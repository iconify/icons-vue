<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irt8L2d)" class="kag-l7b-r"/><path fill="url(#ixcVuqc)" class="kag-l7b-r"/><path fill="url(#iENNp3c)" class="kag-l7b-r"/><path fill="url(#i9zleGb)" class="kag-l7b-r"/><path fill="url(#iDwlNCc)" class="wrro9_bwf"/><path fill="url(#iJ5qdve)" class="wrro9_bwf"/><path fill="url(#iYBPZys)" class="wrro9_bwf"/><path fill="url(#ijzQZee)" class="wrro9_bwf"/><path fill="url(#iojt92b)" class="zmp8hzbhx"/><path fill="url(#iW3amAe)" class="zmp8hzbhx"/><path fill="url(#i8YpEJa)" class="zmp8hzbhx"/><path fill="url(#ihZAN2c)" class="zmp8hzbhx"/><path fill="url(#iJiesYc)" class="xtk66rb_v"/><path fill="url(#ioDVCIc)" class="xtk66rb_v"/><path fill="url(#iM9vuyc)" class="xtk66rb_v"/><path fill="url(#ibngAgd)" class="xtk66rb_v"/><g filter="url(#iOwi1Pc)"><rect stroke="url(#i9uH9Pb)" class="hj0txu2mf"/></g><g filter="url(#ivwxe5d)"><rect stroke="url(#iROEJmb)" class="jz03zvttq"/></g><g filter="url(#iQxICQc)"><rect fill="url(#iTCGPac)" class="x8pjg43qx"/></g><g filter="url(#imUVqge)"><rect fill="url(#i9ZdPTc)" class="f39migbls"/></g><g filter="url(#i23FvZA)"><rect fill="url(#iP1hOPd)" class="jza4ct8ew"/></g><g filter="url(#i1jETLo)"><rect fill="url(#iYj3Tbb)" class="g5p4fcb-v"/></g><g filter="url(#iGBfheF)"><rect fill="url(#ik6eQAc)" class="bo4rubc5w"/></g><g filter="url(#ivcDdad)"><rect fill="url(#iAGi0Hb)" class="o0m4i6v_q"/></g><g filter="url(#iAxMOOc)"><rect fill="url(#ifH2xvc)" class="bpkw7jbua"/></g><g filter="url(#izEftyc)"><rect fill="url(#i4cw0Tc)" class="mpwuet_mo"/></g><g filter="url(#ir0si9b)"><rect fill="url(#iBlDfOd)" class="i7pxg1odi"/></g><g filter="url(#iWEvKub)"><rect fill="url(#i00veRd)" class="n4gjdm1om"/></g><g filter="url(#iL5uYsd)"><rect fill="url(#ijgTRfe)" class="rowlxhy9c"/></g><g filter="url(#iYGHtpb)"><rect fill="url(#iPVJLTA)" class="mi72xeb_h"/></g><g filter="url(#iWkvmfb)"><rect fill="url(#imWaFHb)" class="t-zubnkzg"/></g><g filter="url(#iol1F5d)"><rect fill="url(#iyIJ7ie)" class="i8m15rbje"/></g><g filter="url(#inpFewd)"><rect fill="url(#izhDE4c)" class="fl_canbrl"/></g><g filter="url(#iIGErUc)"><rect fill="url(#ibyEibd)" class="bgsiujbhq"/></g><g filter="url(#ik9mB9b)"><rect fill="url(#iKUGSmc)" class="icha96vew"/></g><g filter="url(#iyQNknn)"><rect fill="url(#iY7moPb)" class="lm_2w3quc"/></g><g filter="url(#ie5gj1c)"><rect fill="url(#i3kM2KL)" class="l7ilvefam"/></g><g filter="url(#iMUEtKe)"><rect fill="url(#iduGFnI)" class="qqhr9rblw"/></g><g filter="url(#iMhzLBd)"><rect fill="url(#i37R0TY)" class="j5c-_hrtw"/></g><g filter="url(#iGHyGHL)"><rect fill="url(#iYpEqAb)" class="ur73amz1v"/></g><g filter="url(#iWJQZ6c)"><rect fill="url(#iinvdKc)" class="a38mguu7z"/></g><g filter="url(#iPshuub)"><rect fill="url(#i8xYoob)" class="pomkri1fr"/></g><g filter="url(#iimaEad)"><rect fill="url(#iR7bBNb)" class="ycq-2hpka"/></g><g filter="url(#idpEDjc)"><rect fill="url(#ioYZZfc)" class="rswv7eb-l"/></g><g filter="url(#iipJ2eS)"><rect fill="url(#iYTU72d)" class="g1ax2gbsr"/></g><g filter="url(#iQqjGce)"><rect fill="url(#ivrg10W)" class="tdxsay-bc"/></g><g filter="url(#iLuA0Hc)"><rect fill="url(#i9FwIje)" class="xs8g7ccfz"/></g><g filter="url(#iTIDBJd)"><rect fill="url(#iEyu0Ab)" class="kzdmhzbyd"/></g><g filter="url(#ijuC3tb)"><rect fill="url(#iAVyFDb)" class="jsgoqwb3z"/></g><g filter="url(#i069dCb)"><rect fill="url(#iYbfzmo)" class="llpsm2v_p"/></g><g filter="url(#iKTP9Fb)"><rect fill="url(#ikWarLb)" class="txbkz9phc"/></g><g filter="url(#iyPKdId)"><rect fill="url(#ieiRCoH)" class="hsyugcboi"/></g><g filter="url(#iT63Sie)"><rect fill="url(#iHQiPtc)" class="lbr7o4h4n"/></g><g filter="url(#iRFXQzb)"><rect fill="url(#iaT0pWd)" class="mipyuwe0k"/></g><g filter="url(#iky77Dd)"><rect fill="url(#infS1Bx)" class="uxdlcjbaz"/></g><g filter="url(#isiijHb)"><rect fill="url(#iWAwKGb)" class="e4kmp4jul"/></g><g filter="url(#igdcCzc)"><rect fill="url(#iTMIkOd)" class="s5jso6b2g"/></g><g filter="url(#iawRNBb)"><rect fill="url(#i82806c)" class="whpfdr7nf"/></g><defs><linearGradient id="irt8L2d" x1="15.914" x2="15.914" y1="8.258" y2="9.273" gradientUnits="userSpaceOnUse"><stop offset=".008" class="gmitdyv0u"/><stop offset="1" class="win2h9brf"/></linearGradient><linearGradient id="ixcVuqc" x1="18.5" x2="18.5" y1="9.273" y2="8.563" gradientUnits="userSpaceOnUse"><stop class="xscifobah"/><stop offset="1" class="vogcktckt"/></linearGradient><linearGradient id="iDwlNCc" x1="15.914" x2="15.914" y1="13.484" y2="14.5" gradientUnits="userSpaceOnUse"><stop offset=".008" class="gmitdyv0u"/><stop offset="1" class="win2h9brf"/></linearGradient><linearGradient id="iJ5qdve" x1="18.5" x2="18.5" y1="14.5" y2="13.789" gradientUnits="userSpaceOnUse"><stop class="xscifobah"/><stop offset="1" class="vogcktckt"/></linearGradient><linearGradient id="iojt92b" x1="15.914" x2="15.914" y1="18.195" y2="19.211" gradientUnits="userSpaceOnUse"><stop offset=".008" class="gmitdyv0u"/><stop offset="1" class="win2h9brf"/></linearGradient><linearGradient id="iW3amAe" x1="18.5" x2="18.5" y1="19.211" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="xscifobah"/><stop offset="1" class="vogcktckt"/></linearGradient><linearGradient id="iJiesYc" x1="15.914" x2="15.914" y1="23.164" y2="24.18" gradientUnits="userSpaceOnUse"><stop offset=".008" class="gmitdyv0u"/><stop offset="1" class="win2h9brf"/></linearGradient><linearGradient id="ioDVCIc" x1="18.5" x2="18.5" y1="24.18" y2="23.469" gradientUnits="userSpaceOnUse"><stop class="xscifobah"/><stop offset="1" class="vogcktckt"/></linearGradient><linearGradient id="i9uH9Pb" x1="30.063" x2="12.688" y1="17.75" y2="17.75" gradientUnits="userSpaceOnUse"><stop class="j59_2qbmh"/><stop offset=".41" class="f5yelnbkd"/><stop offset="1" class="f17fqpbnk"/></linearGradient><linearGradient id="iROEJmb" x1="30.514" x2="12.924" y1="17.78" y2="17.78" gradientUnits="userSpaceOnUse"><stop class="wrg1wkb9z"/><stop offset="1" class="mhi1o4bjb"/></linearGradient><linearGradient id="iTCGPac" x1="8.236" x2="6.111" y1="9.125" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="du5xphbzi"/><stop offset="1" class="jaxrzjb5b"/></linearGradient><linearGradient id="i9ZdPTc" x1="11.254" x2="9.129" y1="9.125" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="du5xphbzi"/><stop offset="1" class="jaxrzjb5b"/></linearGradient><linearGradient id="iP1hOPd" x1="14.271" x2="12.146" y1="9.125" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="du5xphbzi"/><stop offset="1" class="jaxrzjb5b"/></linearGradient><linearGradient id="iYj3Tbb" x1="17.289" x2="15.164" y1="9.125" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="du5xphbzi"/><stop offset="1" class="jaxrzjb5b"/></linearGradient><linearGradient id="ik6eQAc" x1="8.236" x2="6.111" y1="14.117" y2="14.117" gradientUnits="userSpaceOnUse"><stop class="wzjrnmnzs"/><stop offset="1" class="j1c8fgp_r"/></linearGradient><linearGradient id="iAGi0Hb" x1="8.236" x2="6.111" y1="19.109" y2="19.109" gradientUnits="userSpaceOnUse"><stop class="ly-lrdbmq"/><stop offset="1" class="u584s-b7u"/></linearGradient><linearGradient id="ifH2xvc" x1="8.236" x2="6.111" y1="24.102" y2="24.102" gradientUnits="userSpaceOnUse"><stop class="vw3y686gm"/><stop offset="1" class="deplh9ifs"/></linearGradient><linearGradient id="i4cw0Tc" x1="11.254" x2="9.129" y1="14.117" y2="14.117" gradientUnits="userSpaceOnUse"><stop class="wzjrnmnzs"/><stop offset="1" class="j1c8fgp_r"/></linearGradient><linearGradient id="iBlDfOd" x1="11.254" x2="9.129" y1="19.109" y2="19.109" gradientUnits="userSpaceOnUse"><stop class="ly-lrdbmq"/><stop offset="1" class="u584s-b7u"/></linearGradient><linearGradient id="i00veRd" x1="11.254" x2="9.129" y1="24.102" y2="24.102" gradientUnits="userSpaceOnUse"><stop class="vw3y686gm"/><stop offset="1" class="deplh9ifs"/></linearGradient><linearGradient id="ijgTRfe" x1="14.271" x2="12.146" y1="14.117" y2="14.117" gradientUnits="userSpaceOnUse"><stop class="wzjrnmnzs"/><stop offset="1" class="j1c8fgp_r"/></linearGradient><linearGradient id="iPVJLTA" x1="14.271" x2="12.146" y1="19.109" y2="19.109" gradientUnits="userSpaceOnUse"><stop class="ly-lrdbmq"/><stop offset="1" class="u584s-b7u"/></linearGradient><linearGradient id="imWaFHb" x1="14.271" x2="12.146" y1="24.102" y2="24.102" gradientUnits="userSpaceOnUse"><stop class="vw3y686gm"/><stop offset="1" class="deplh9ifs"/></linearGradient><linearGradient id="iyIJ7ie" x1="17.289" x2="15.164" y1="14.117" y2="14.117" gradientUnits="userSpaceOnUse"><stop class="wzjrnmnzs"/><stop offset="1" class="j1c8fgp_r"/></linearGradient><linearGradient id="izhDE4c" x1="17.289" x2="15.164" y1="19.109" y2="19.109" gradientUnits="userSpaceOnUse"><stop class="ly-lrdbmq"/><stop offset="1" class="u584s-b7u"/></linearGradient><linearGradient id="ibyEibd" x1="17.289" x2="15.164" y1="24.102" y2="24.102" gradientUnits="userSpaceOnUse"><stop class="vw3y686gm"/><stop offset="1" class="deplh9ifs"/></linearGradient><linearGradient id="iKUGSmc" x1="25.344" x2="23.219" y1="24.102" y2="24.102" gradientUnits="userSpaceOnUse"><stop class="vw3y686gm"/><stop offset="1" class="deplh9ifs"/></linearGradient><linearGradient id="iY7moPb" x1="25.344" x2="23.219" y1="19.109" y2="19.109" gradientUnits="userSpaceOnUse"><stop class="ly-lrdbmq"/><stop offset="1" class="u584s-b7u"/></linearGradient><linearGradient id="i3kM2KL" x1="25.344" x2="23.219" y1="14.117" y2="14.117" gradientUnits="userSpaceOnUse"><stop class="wzjrnmnzs"/><stop offset="1" class="j1c8fgp_r"/></linearGradient><linearGradient id="iduGFnI" x1="25.344" x2="23.219" y1="9.125" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="du5xphbzi"/><stop offset="1" class="jaxrzjb5b"/></linearGradient><linearGradient id="i37R0TY" x1="25.117" x2="25.117" y1="7.836" y2="10.641" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p9q383b-e"/><stop offset="1" class="xa9na5b8g"/></linearGradient><linearGradient id="iYpEqAb" x1="16.944" x2="16.944" y1="7.836" y2="10.641" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p9q383b-e"/><stop offset="1" class="xa9na5b8g"/></linearGradient><linearGradient id="iinvdKc" x1="13.804" x2="13.804" y1="7.836" y2="10.641" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p9q383b-e"/><stop offset="1" class="xa9na5b8g"/></linearGradient><linearGradient id="i8xYoob" x1="10.909" x2="10.909" y1="7.836" y2="10.641" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p9q383b-e"/><stop offset="1" class="xa9na5b8g"/></linearGradient><linearGradient id="iR7bBNb" x1="7.892" x2="7.892" y1="7.836" y2="10.641" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p9q383b-e"/><stop offset="1" class="xa9na5b8g"/></linearGradient><linearGradient id="ioYZZfc" x1="7.892" x2="7.892" y1="12.891" y2="15.695" gradientUnits="userSpaceOnUse"><stop offset=".28" class="k74ci1bfo"/><stop offset="1" class="akb15n6vn"/></linearGradient><linearGradient id="iYTU72d" x1="7.892" x2="7.892" y1="17.883" y2="20.688" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dzyut_o4s"/><stop offset="1" class="zslljg9ps"/></linearGradient><linearGradient id="ivrg10W" x1="7.892" x2="7.892" y1="22.875" y2="25.68" gradientUnits="userSpaceOnUse"><stop offset=".28" class="nksboy0xo"/><stop offset="1" class="p0e0exb6q"/></linearGradient><linearGradient id="i9FwIje" x1="10.909" x2="10.909" y1="22.875" y2="25.68" gradientUnits="userSpaceOnUse"><stop offset=".28" class="nksboy0xo"/><stop offset="1" class="p0e0exb6q"/></linearGradient><linearGradient id="iEyu0Ab" x1="13.927" x2="13.927" y1="22.875" y2="25.68" gradientUnits="userSpaceOnUse"><stop offset=".28" class="nksboy0xo"/><stop offset="1" class="p0e0exb6q"/></linearGradient><linearGradient id="iAVyFDb" x1="16.944" x2="16.944" y1="22.875" y2="25.68" gradientUnits="userSpaceOnUse"><stop offset=".28" class="nksboy0xo"/><stop offset="1" class="p0e0exb6q"/></linearGradient><linearGradient id="iYbfzmo" x1="24.999" x2="24.999" y1="22.875" y2="25.68" gradientUnits="userSpaceOnUse"><stop offset=".28" class="nksboy0xo"/><stop offset="1" class="p0e0exb6q"/></linearGradient><linearGradient id="ikWarLb" x1="10.909" x2="10.909" y1="17.883" y2="20.688" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dzyut_o4s"/><stop offset="1" class="zslljg9ps"/></linearGradient><linearGradient id="ieiRCoH" x1="13.927" x2="13.927" y1="17.883" y2="20.688" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dzyut_o4s"/><stop offset="1" class="zslljg9ps"/></linearGradient><linearGradient id="iHQiPtc" x1="16.944" x2="16.944" y1="17.883" y2="20.688" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dzyut_o4s"/><stop offset="1" class="zslljg9ps"/></linearGradient><linearGradient id="iaT0pWd" x1="24.999" x2="24.999" y1="17.883" y2="20.688" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dzyut_o4s"/><stop offset="1" class="zslljg9ps"/></linearGradient><linearGradient id="infS1Bx" x1="10.909" x2="10.909" y1="12.891" y2="15.695" gradientUnits="userSpaceOnUse"><stop offset=".28" class="k74ci1bfo"/><stop offset="1" class="akb15n6vn"/></linearGradient><linearGradient id="iWAwKGb" x1="13.927" x2="13.927" y1="12.891" y2="15.695" gradientUnits="userSpaceOnUse"><stop offset=".28" class="k74ci1bfo"/><stop offset="1" class="akb15n6vn"/></linearGradient><linearGradient id="iTMIkOd" x1="16.944" x2="16.944" y1="12.891" y2="15.695" gradientUnits="userSpaceOnUse"><stop offset=".28" class="k74ci1bfo"/><stop offset="1" class="akb15n6vn"/></linearGradient><linearGradient id="i82806c" x1="24.999" x2="24.999" y1="12.891" y2="15.695" gradientUnits="userSpaceOnUse"><stop offset=".28" class="k74ci1bfo"/><stop offset="1" class="akb15n6vn"/></linearGradient><filter id="iOwi1Pc" width="28.137" height="27.794" x="2.031" y="2.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.321569 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="ivwxe5d" width="27.858" height="27.694" x="2.348" y="2.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".3"/></filter><filter id="iQxICQc" width="3.018" height="4.266" x="5.914" y="6.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.254902 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="imUVqge" width="3.018" height="4.266" x="8.932" y="6.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.254902 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="i23FvZA" width="3.018" height="4.266" x="11.949" y="6.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.254902 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="i1jETLo" width="3.018" height="4.266" x="14.967" y="6.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.254902 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iGBfheF" width="3.168" height="4.266" x="5.914" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.341176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="ivcDdad" width="3.168" height="4.266" x="5.914" y="16.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.415686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iAxMOOc" width="3.168" height="4.266" x="5.914" y="21.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.545098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="izEftyc" width="3.168" height="4.266" x="8.932" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.341176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="ir0si9b" width="3.168" height="4.266" x="8.932" y="16.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.415686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iWEvKub" width="3.168" height="4.266" x="8.932" y="21.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.545098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iL5uYsd" width="3.168" height="4.266" x="11.949" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.341176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iYGHtpb" width="3.168" height="4.266" x="11.949" y="16.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.415686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iWkvmfb" width="3.168" height="4.266" x="11.949" y="21.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.545098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iol1F5d" width="3.168" height="4.266" x="14.967" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.341176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="inpFewd" width="3.168" height="4.266" x="14.967" y="16.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.415686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iIGErUc" width="3.168" height="4.266" x="14.967" y="21.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.545098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="ik9mB9b" width="3.168" height="4.266" x="23.021" y="21.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.545098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iyQNknn" width="3.168" height="4.266" x="23.021" y="16.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.415686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="ie5gj1c" width="3.168" height="4.266" x="23.021" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.341176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iMUEtKe" width="3.018" height="4.266" x="23.021" y="6.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.254902 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19902"/></filter><filter id="iMhzLBd" width="1.938" height="3.203" x="24.148" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iGHyGHL" width="1.938" height="3.203" x="15.976" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iWJQZ6c" width="1.938" height="3.203" x="12.835" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iPshuub" width="1.938" height="3.203" x="9.94" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iimaEad" width="1.938" height="3.203" x="6.923" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="idpEDjc" width="1.938" height="3.203" x="6.923" y="12.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iipJ2eS" width="1.938" height="3.203" x="6.923" y="17.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iQqjGce" width="1.938" height="3.203" x="6.923" y="22.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iLuA0Hc" width="1.938" height="3.203" x="9.94" y="22.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iTIDBJd" width="1.938" height="3.203" x="12.958" y="22.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="ijuC3tb" width="1.938" height="3.203" x="15.975" y="22.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="i069dCb" width="1.938" height="3.203" x="24.03" y="22.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iKTP9Fb" width="1.938" height="3.203" x="9.94" y="17.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iyPKdId" width="1.938" height="3.203" x="12.958" y="17.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iT63Sie" width="1.938" height="3.203" x="15.975" y="17.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iRFXQzb" width="1.938" height="3.203" x="24.03" y="17.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iky77Dd" width="1.938" height="3.203" x="9.94" y="12.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="isiijHb" width="1.938" height="3.203" x="12.958" y="12.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="igdcCzc" width="1.938" height="3.203" x="15.975" y="12.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><filter id="iawRNBb" width="1.938" height="3.203" x="24.03" y="12.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19902" stdDeviation=".25"/></filter><radialGradient id="iENNp3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -26.7096 23.438 8.766)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="i9zleGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -36.9221 6.5 8.969)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="iYBPZys" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -26.7096 23.438 13.992)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="ijzQZee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -36.9221 6.5 14.195)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="i8YpEJa" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -26.7096 23.438 18.703)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="ihZAN2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -36.9221 6.5 18.906)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="iM9vuyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -26.7096 23.438 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient><radialGradient id="ibngAgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -36.9221 6.5 23.875)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="matgb8s6i"/><stop offset="1" class="j2ez0cb1g"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:abacus" /></template>
<style>
.a38mguu7z {
  width: 0.938px;
  height: 2.203px;
  x: 13.335px;
  y: 7.836px;
  rx: 0.469px;
}

.akb15n6vn {
  stop-color: var(--svg-color--64b4ff, #64B4FF);
  stop-opacity: 0;
}

.bgsiujbhq {
  width: 3.018px;
  height: 4.016px;
  x: 14.967px;
  y: 21.969px;
  rx: 1.5px;
}

.bo4rubc5w {
  width: 3.018px;
  height: 4.016px;
  x: 5.914px;
  y: 11.984px;
  rx: 1.5px;
}

.bpkw7jbua {
  width: 3.018px;
  height: 4.016px;
  x: 5.914px;
  y: 21.969px;
  rx: 1.5px;
}

.deplh9ifs {
  stop-color: var(--svg-color--40b472, #40B472);
}

.du5xphbzi {
  stop-color: var(--svg-color--ff2c7d, #FF2C7D);
}

.dzyut_o4s {
  stop-color: var(--svg-color--ffe067, #FFE067);
}

.e4kmp4jul {
  width: 0.938px;
  height: 2.203px;
  x: 13.458px;
  y: 12.891px;
  rx: 0.469px;
}

.f17fqpbnk {
  stop-color: var(--svg-color--f93728, #F93728);
}

.f39migbls {
  width: 3.018px;
  height: 4.016px;
  x: 8.932px;
  y: 6.992px;
  rx: 1.5px;
}

.f5yelnbkd {
  stop-color: var(--svg-color--fb7c30, #FB7C30);
}

.fl_canbrl {
  width: 3.018px;
  height: 4.016px;
  x: 14.967px;
  y: 16.977px;
  rx: 1.5px;
}

.ft5dv1b6b {
  fill: none;
}

.g1ax2gbsr {
  width: 0.938px;
  height: 2.203px;
  x: 7.423px;
  y: 17.883px;
  rx: 0.469px;
}

.g5p4fcb-v {
  width: 3.018px;
  height: 4.016px;
  x: 14.967px;
  y: 6.992px;
  rx: 1.5px;
}

.gmitdyv0u {
  stop-color: var(--svg-color--d6c0c2, #D6C0C2);
}

.hj0txu2mf {
  width: 25.938px;
  height: 25.594px;
  x: 3.031px;
  y: 3.438px;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  rx: 4.9px;
}

.hsyugcboi {
  width: 0.938px;
  height: 2.203px;
  x: 13.458px;
  y: 17.883px;
  rx: 0.469px;
}

.i7pxg1odi {
  width: 3.018px;
  height: 4.016px;
  x: 8.932px;
  y: 16.977px;
  rx: 1.5px;
}

.i8m15rbje {
  width: 3.018px;
  height: 4.016px;
  x: 14.967px;
  y: 11.984px;
  rx: 1.5px;
}

.icha96vew {
  width: 3.018px;
  height: 4.016px;
  x: 23.021px;
  y: 21.969px;
  rx: 1.5px;
}

.j1c8fgp_r {
  stop-color: var(--svg-color--2e7bcd, #2E7BCD);
}

.j2ez0cb1g {
  stop-color: var(--svg-color--bdabb5, #BDABB5);
  stop-opacity: 0;
}

.j59_2qbmh {
  stop-color: var(--svg-color--ff9c45, #FF9C45);
}

.j5c-_hrtw {
  width: 0.938px;
  height: 2.203px;
  x: 24.648px;
  y: 7.836px;
  rx: 0.469px;
}

.jaxrzjb5b {
  stop-color: var(--svg-color--d53246, #D53246);
}

.jsgoqwb3z {
  width: 0.938px;
  height: 2.203px;
  x: 16.475px;
  y: 22.875px;
  rx: 0.469px;
}

.jz03zvttq {
  width: 26.258px;
  height: 26.094px;
  x: 3.148px;
  y: 3.188px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 4.9px;
}

.jza4ct8ew {
  width: 3.018px;
  height: 4.016px;
  x: 11.949px;
  y: 6.992px;
  rx: 1.5px;
}

.k74ci1bfo {
  stop-color: var(--svg-color--64b4ff, #64B4FF);
}

.kag-l7b-r {
  d: path("M3.148 8.258h25.531v1.016H3.148z");
}

.kzdmhzbyd {
  width: 0.938px;
  height: 2.203px;
  x: 13.458px;
  y: 22.875px;
  rx: 0.469px;
}

.l7ilvefam {
  width: 3.018px;
  height: 4.016px;
  x: 23.021px;
  y: 11.984px;
  rx: 1.5px;
}

.lbr7o4h4n {
  width: 0.938px;
  height: 2.203px;
  x: 16.475px;
  y: 17.883px;
  rx: 0.469px;
}

.llpsm2v_p {
  width: 0.938px;
  height: 2.203px;
  x: 24.53px;
  y: 22.875px;
  rx: 0.469px;
}

.lm_2w3quc {
  width: 3.018px;
  height: 4.016px;
  x: 23.021px;
  y: 16.977px;
  rx: 1.5px;
}

.ly-lrdbmq {
  stop-color: var(--svg-color--fed344, #FED344);
}

.matgb8s6i {
  stop-color: var(--svg-color--966b73, #966B73);
}

.mhi1o4bjb {
  stop-color: var(--svg-color--ff695f, #FF695F);
}

.mi72xeb_h {
  width: 3.018px;
  height: 4.016px;
  x: 11.949px;
  y: 16.977px;
  rx: 1.5px;
}

.mipyuwe0k {
  width: 0.938px;
  height: 2.203px;
  x: 24.53px;
  y: 17.883px;
  rx: 0.469px;
}

.mpwuet_mo {
  width: 3.018px;
  height: 4.016px;
  x: 8.932px;
  y: 11.984px;
  rx: 1.5px;
}

.n4gjdm1om {
  width: 3.018px;
  height: 4.016px;
  x: 8.932px;
  y: 21.969px;
  rx: 1.5px;
}

.nksboy0xo {
  stop-color: var(--svg-color--6fffaf, #6FFFAF);
}

.o0m4i6v_q {
  width: 3.018px;
  height: 4.016px;
  x: 5.914px;
  y: 16.977px;
  rx: 1.5px;
}

.p0e0exb6q {
  stop-color: var(--svg-color--6fffaf, #6FFFAF);
  stop-opacity: 0;
}

.p9q383b-e {
  stop-color: var(--svg-color--ff669c, #FF669C);
}

.pomkri1fr {
  width: 0.938px;
  height: 2.203px;
  x: 10.44px;
  y: 7.836px;
  rx: 0.469px;
}

.qqhr9rblw {
  width: 3.018px;
  height: 4.016px;
  x: 23.021px;
  y: 6.992px;
  rx: 1.5px;
}

.rowlxhy9c {
  width: 3.018px;
  height: 4.016px;
  x: 11.949px;
  y: 11.984px;
  rx: 1.5px;
}

.rswv7eb-l {
  width: 0.938px;
  height: 2.203px;
  x: 7.423px;
  y: 12.891px;
  rx: 0.469px;
}

.s5jso6b2g {
  width: 0.938px;
  height: 2.203px;
  x: 16.475px;
  y: 12.891px;
  rx: 0.469px;
}

.t-zubnkzg {
  width: 3.018px;
  height: 4.016px;
  x: 11.949px;
  y: 21.969px;
  rx: 1.5px;
}

.tdxsay-bc {
  width: 0.938px;
  height: 2.203px;
  x: 7.423px;
  y: 22.875px;
  rx: 0.469px;
}

.txbkz9phc {
  width: 0.938px;
  height: 2.203px;
  x: 10.44px;
  y: 17.883px;
  rx: 0.469px;
}

.u584s-b7u {
  stop-color: var(--svg-color--ec8a34, #EC8A34);
}

.ur73amz1v {
  width: 0.938px;
  height: 2.203px;
  x: 16.476px;
  y: 7.836px;
  rx: 0.469px;
}

.uxdlcjbaz {
  width: 0.938px;
  height: 2.203px;
  x: 10.44px;
  y: 12.891px;
  rx: 0.469px;
}

.vogcktckt {
  stop-color: var(--svg-color--a481c1, #A481C1);
  stop-opacity: 0;
}

.vw3y686gm {
  stop-color: var(--svg-color--54f290, #54F290);
}

.whpfdr7nf {
  width: 0.938px;
  height: 2.203px;
  x: 24.53px;
  y: 12.891px;
  rx: 0.469px;
}

.win2h9brf {
  stop-color: var(--svg-color--d5cad6, #D5CAD6);
}

.wrg1wkb9z {
  stop-color: var(--svg-color--ffaa61, #FFAA61);
}

.wrro9_bwf {
  d: path("M3.148 13.484h25.531V14.5H3.148z");
}

.wzjrnmnzs {
  stop-color: var(--svg-color--44a3e7, #44A3E7);
}

.x8pjg43qx {
  width: 3.018px;
  height: 4.016px;
  x: 5.914px;
  y: 6.992px;
  rx: 1.5px;
}

.xa9na5b8g {
  stop-color: var(--svg-color--ff669c, #FF669C);
  stop-opacity: 0;
}

.xs8g7ccfz {
  width: 0.938px;
  height: 2.203px;
  x: 10.44px;
  y: 22.875px;
  rx: 0.469px;
}

.xscifobah {
  stop-color: var(--svg-color--a481c1, #A481C1);
}

.xtk66rb_v {
  d: path("M3.148 23.164h25.531v1.016H3.148z");
}

.ycq-2hpka {
  width: 0.938px;
  height: 2.203px;
  x: 7.423px;
  y: 7.836px;
  rx: 0.469px;
}

.zmp8hzbhx {
  d: path("M3.148 18.195h25.531v1.016H3.148z");
}

.zslljg9ps {
  stop-color: var(--svg-color--ffe067, #FFE067);
  stop-opacity: 0;
}

</style>
