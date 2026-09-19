<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="iinq6ac4y"/><g filter="url(#i92avMc)"><path fill="url(#igwYaxb)" class="vvk5gcc8o"/><path fill="url(#ieGy8Lb)" class="vvk5gcc8o"/><path fill="url(#iHvQyZb)" class="vvk5gcc8o"/></g><g filter="url(#iced26d)"><path class="dea0e4bih"/><path fill="url(#i53d12d)" class="adktqpbyv"/><path fill="url(#iVtrNNb)" class="adktqpbyv"/></g><path fill="url(#iZDIvod)" class="z76-9ebyb"/><path fill="url(#iO4Q6xd)" class="z76-9ebyb"/><path fill="url(#iF2O6te)" class="z76-9ebyb"/><path fill="url(#inf2BoR)" clip-rule="evenodd" class="iegtdbqjb"/><path fill="url(#iTgOrdd)" clip-rule="evenodd" class="iegtdbqjb"/><path fill="url(#iUQl0Ec)" class="ihge7tbdv"/><path fill="url(#i5vp7ub)" class="ihge7tbdv"/><path fill="url(#iz4tqEe)" class="ihge7tbdv"/><path fill="url(#i816MZG)" class="ihge7tbdv"/><path fill="url(#iCayDlc)" class="ee0nxr24c"/><path fill="url(#i0Gqxfb)" class="ee0nxr24c"/><path fill="url(#iTtoSke)" class="ee0nxr24c"/><path fill="url(#iWGByXb)" class="ee0nxr24c"/><g filter="url(#inAt8Yb)"><path fill="url(#i6iJzLc)" class="qf376hl_o"/><path fill="url(#iyxZHic)" class="qf376hl_o"/></g><path fill="url(#iZ5goDe)" class="qf376hl_o"/><path fill="url(#iyQl8wd)" class="qf376hl_o"/><g filter="url(#iRyzD8d)"><path fill="url(#iX4X8Me)" class="u7oio7bil"/><path fill="url(#iA6k24c)" class="u7oio7bil"/></g><path fill="url(#iGpQSQF)" class="u7oio7bil"/><path fill="url(#i2BBTMe)" class="b-_2ti19t"/><g filter="url(#iKtTzFd)"><path fill="url(#ioYgN0b)" class="n6n5q7z4u"/></g><g filter="url(#ibR9CJe)"><path class="bjbu_bb2k"/></g><path fill="url(#ipnEznb)" class="sd1n-45mo"/><g filter="url(#i9jtxle)"><path class="almegmbsu"/></g><path fill="url(#ik5dY6C)" class="uq_64wbwx"/><path class="o3ajxnbmt"/><g filter="url(#iLE80Hc)"><path class="qtdijkbts"/><path fill="url(#iKgBtCb)" class="z19p6pvyb"/><path fill="url(#iccK4ub)" class="z19p6pvyb"/></g><path fill="url(#i0cp4kV)" class="iv2ctj7tz"/><path fill="url(#iAg7n0q)" class="iv2ctj7tz"/><g filter="url(#ifxyTtb)"><path fill="url(#i6X26gc)" class="txx1a2bwg"/></g><path fill="url(#iy5AJmz)" class="txx1a2bwg"/><path fill="url(#iwj04Yb)" class="txx1a2bwg"/><path fill="url(#iak3Uhd)" class="txx1a2bwg"/><g filter="url(#iRxnpsb)"><path fill="url(#isQMMid)" class="hwtdoqbhu"/></g><path fill="url(#i7siVPd)" class="hwtdoqbhu"/><g filter="url(#iDedTfb)"><path fill="url(#iTO11hJ)" class="wfrswybfg"/></g><path fill="url(#iJj6cNb)" class="wfrswybfg"/><path fill="url(#i3KghCc)" class="wfrswybfg"/><g filter="url(#iLM5H3b)"><path stroke="url(#icKxcYO)" class="gpnyj1b0k"/></g><g filter="url(#i4Ux1Je)"><path fill="url(#iczfbme)" class="i9lef1c_r"/></g><defs><linearGradient id="igwYaxb" x1="17.402" x2="26.473" y1="8.294" y2="15.272" gradientUnits="userSpaceOnUse"><stop class="zdzs69inc"/><stop offset="0" class="x4-r_-foh"/><stop offset="1" class="an7ekthzq"/></linearGradient><linearGradient id="ieGy8Lb" x1="27.372" x2="21.956" y1="15.571" y2="13.511" gradientUnits="userSpaceOnUse"><stop class="kwy6o1n-h"/><stop offset="1" class="hhitj8fwx"/></linearGradient><linearGradient id="iHvQyZb" x1="25.453" x2="25.453" y1="15.75" y2="14.562" gradientUnits="userSpaceOnUse"><stop offset=".105" class="fnuj_jbcr"/><stop offset="1" class="t7lzpfbbk"/></linearGradient><linearGradient id="i53d12d" x1="6.453" x2="6.453" y1="15.031" y2="14.836" gradientUnits="userSpaceOnUse"><stop class="lco7ncowo"/><stop offset="1" class="g1aet7ifi"/></linearGradient><linearGradient id="iVtrNNb" x1="7.89" x2="8.609" y1="13.156" y2="13.906" gradientUnits="userSpaceOnUse"><stop class="ugdfpa_dp"/><stop offset="1" class="iboil8bjd"/></linearGradient><linearGradient id="iZDIvod" x1="3.669" x2="7.798" y1="21.765" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="wph8q-bqo"/><stop offset=".25" class="y8cf4cbun"/><stop offset=".738" class="u16y8mbxn"/><stop offset=".885" class="e5woykbnf"/></linearGradient><linearGradient id="iO4Q6xd" x1="4.978" x2="4.978" y1="30.421" y2="29.124" gradientUnits="userSpaceOnUse"><stop class="vzicwmbfk"/><stop offset="1" class="v_8rtja-e"/></linearGradient><linearGradient id="inf2BoR" x1="24.152" x2="28.298" y1="23.035" y2="22.772" gradientUnits="userSpaceOnUse"><stop class="fw_cblbpw"/><stop offset=".21" class="wqso7kyoe"/><stop offset="1" class="abolntb_v"/></linearGradient><linearGradient id="iTgOrdd" x1="15.444" x2="15.444" y1="30.417" y2="29.12" gradientUnits="userSpaceOnUse"><stop class="vzicwmbfk"/><stop offset="1" class="v_8rtja-e"/></linearGradient><linearGradient id="iUQl0Ec" x1="7.898" x2="13.372" y1="20.974" y2="21.642" gradientUnits="userSpaceOnUse"><stop offset=".042" class="kfq40zqow"/><stop offset=".146" class="glx6xub_c"/><stop offset="1" class="ffmv3lbrb"/></linearGradient><linearGradient id="i5vp7ub" x1="13.311" x2="12.399" y1="19.737" y2="19.696" gradientUnits="userSpaceOnUse"><stop class="i2fulr8cj"/><stop offset="1" class="ux8x8_bek"/></linearGradient><linearGradient id="iz4tqEe" x1="9.317" x2="9.317" y1="30.421" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="lt4agybjp"/><stop offset="1" class="rfna4kbaa"/></linearGradient><linearGradient id="iCayDlc" x1="18.886" x2="24.036" y1="20.223" y2="19.919" gradientUnits="userSpaceOnUse"><stop offset=".036" class="uqp0_bv0v"/><stop offset=".2" class="qxh3z3vnu"/><stop offset="1" class="njoxcwbsd"/></linearGradient><linearGradient id="i0Gqxfb" x1="24.563" x2="23.144" y1="24.015" y2="24.136" gradientUnits="userSpaceOnUse"><stop class="dvda_ycbn"/><stop offset="1" class="gosulzdmf"/></linearGradient><linearGradient id="iTtoSke" x1="25.739" x2="20.792" y1="31.191" y2="25.637" gradientUnits="userSpaceOnUse"><stop class="t498k0bri"/><stop offset="1" class="efyhq6aow"/></linearGradient><linearGradient id="iWGByXb" x1="22.698" x2="22.698" y1="30.239" y2="29.123" gradientUnits="userSpaceOnUse"><stop offset=".09" class="pezdmbb0l"/><stop offset="1" class="ix7ascc6q"/></linearGradient><linearGradient id="i6iJzLc" x1="4.945" x2="8.784" y1="17.753" y2="14.739" gradientUnits="userSpaceOnUse"><stop class="omqbx3bgh"/><stop offset="1" class="it3f_9zqt"/></linearGradient><linearGradient id="iZ5goDe" x1="6.638" x2="6.638" y1="14.813" y2="15.273" gradientUnits="userSpaceOnUse"><stop class="wcw3drb6p"/><stop offset="1" class="vg2nhccic"/></linearGradient><linearGradient id="iA6k24c" x1="25.405" x2="25.405" y1="14.867" y2="15.062" gradientUnits="userSpaceOnUse"><stop class="afg7wtasa"/><stop offset="1" class="pn-xo0bof"/></linearGradient><linearGradient id="i2BBTMe" x1="13.355" x2="18.774" y1="19.019" y2="19.019" gradientUnits="userSpaceOnUse"><stop class="mj5ai0wuc"/><stop offset=".136" class="wqso7kyoe"/><stop offset=".857" class="z1inge64e"/><stop offset="1" class="qozzjrm-a"/></linearGradient><linearGradient id="ioYgN0b" x1="11.009" x2="20.996" y1="25.793" y2="25.793" gradientUnits="userSpaceOnUse"><stop class="n9t9q0bzq"/><stop offset="1" class="xtak37bzz"/></linearGradient><linearGradient id="ik5dY6C" x1="11.453" x2="11.453" y1="15.062" y2="14.601" gradientUnits="userSpaceOnUse"><stop class="rrowarz-c"/><stop offset="1" class="tvzsfqhus"/></linearGradient><linearGradient id="iKgBtCb" x1="23.418" x2="19.394" y1="15.326" y2="13.78" gradientUnits="userSpaceOnUse"><stop class="xjntzhbyx"/><stop offset="1" class="qqtrjabga"/></linearGradient><linearGradient id="iccK4ub" x1="20.926" x2="20.926" y1="15.326" y2="14.375" gradientUnits="userSpaceOnUse"><stop class="nxnomrl6m"/><stop offset="1" class="y8vxw2bje"/></linearGradient><linearGradient id="i0cp4kV" x1="16.453" x2="19.982" y1="4.961" y2="4.961" gradientUnits="userSpaceOnUse"><stop class="do1e9gb2e"/><stop offset="1" class="epa2cvt-u"/></linearGradient><linearGradient id="iAg7n0q" x1="18.437" x2="18.297" y1="4.578" y2="4.141" gradientUnits="userSpaceOnUse"><stop class="ks5ymd8mx"/><stop offset="1" class="f2jwpabvd"/></linearGradient><linearGradient id="i6X26gc" x1="14.999" x2="16.3" y1="6.712" y2="6.712" gradientUnits="userSpaceOnUse"><stop class="s8ibn4mvw"/><stop offset="1" class="xv-yltbce"/></linearGradient><linearGradient id="iak3Uhd" x1="16.482" x2="16.482" y1="8.206" y2="7.823" gradientUnits="userSpaceOnUse"><stop class="wcpg47b1z"/><stop offset="1" class="j_f2huxqx"/></linearGradient><linearGradient id="i7siVPd" x1="21.069" x2="21.069" y1="14.734" y2="15.234" gradientUnits="userSpaceOnUse"><stop class="rfn8p6juo"/><stop offset="1" class="dgk3unbtm"/></linearGradient><linearGradient id="iTO11hJ" x1="14.422" x2="19.265" y1="16.488" y2="16.488" gradientUnits="userSpaceOnUse"><stop class="xk-4-6bhe"/><stop offset="1" class="dvda_ycbn"/></linearGradient><linearGradient id="iJj6cNb" x1="16.056" x2="16.056" y1="14.711" y2="15.219" gradientUnits="userSpaceOnUse"><stop class="xm-ocvwqq"/><stop offset="1" class="fi2wlysof"/></linearGradient><linearGradient id="icKxcYO" x1="11.836" x2="11.836" y1="29.647" y2="20.909" gradientUnits="userSpaceOnUse"><stop class="g2sgr8mmx"/><stop offset="1" class="psd5utbfl"/></linearGradient><linearGradient id="iczfbme" x1="8.912" x2="13.108" y1="16.468" y2="16.468" gradientUnits="userSpaceOnUse"><stop class="xae324byd"/><stop offset="1" class="y882llhzt"/></linearGradient><filter id="i92avMc" width="11.246" height="8.537" x="16.272" y="7.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.529412 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="iced26d" width="10.682" height="7.687" x="4.798" y="7.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.784314 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="inAt8Yb" width="4.492" height="3.219" x="4.292" y="14.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.781851 0 0 0 0 0.554688 0 0 0 0 0.9375 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="iRyzD8d" width="4.512" height="3.119" x="23.274" y="14.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.427451 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="iKtTzFd" width="10.487" height="10.526" x="10.509" y="19.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.12549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="ibR9CJe" width="5.938" height="7.277" x="13.033" y="7.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.94902 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8919" result="effect2_innerShadow_18_8919"/></filter><filter id="i9jtxle" width="7.382" height="8.159" x="8.482" y="7.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.227451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.301961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8919" result="effect2_innerShadow_18_8919"/></filter><filter id="iLE80Hc" width="7.317" height="7.359" x="16.243" y="7.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.223529 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="ifxyTtb" width="2.443" height="5.963" x="14.849" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.333333 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.87451 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8919" result="effect2_innerShadow_18_8919"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_8919" result="effect3_innerShadow_18_8919"/></filter><filter id="iRxnpsb" width="5.24" height="3.25" x="18.574" y="14.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.176471 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="iDedTfb" width="5.316" height="3.174" x="13.448" y="14.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.407843 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><filter id="iLM5H3b" width="3.616" height="9.362" x="10.885" y="20.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8919" stdDeviation=".3"/></filter><filter id="i4Ux1Je" width="5.225" height="3.1" x="8.492" y="14.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.235294 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8919"/></filter><radialGradient id="iF2O6te" cx="0" cy="0" r="1" gradientTransform="rotate(121.718 -1.063 9.915)scale(2.64506 1.76959)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="o3mc0yj9q"/><stop offset="1" class="z5octemly"/></radialGradient><radialGradient id="i816MZG" cx="0" cy="0" r="1" gradientTransform="rotate(96.033 -2.07 12.73)scale(2.07418 2.4816)" gradientUnits="userSpaceOnUse"><stop offset=".845" class="gesvv2bcw"/><stop offset="1" class="svoxunfuh"/></radialGradient><radialGradient id="iyxZHic" cx="0" cy="0" r="1" gradientTransform="rotate(-174.104 4.112 8.123)scale(2.88983 3.35794)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="q8-63qpuh"/><stop offset="1" class="pjj6wjldh"/></radialGradient><radialGradient id="iyQl8wd" cx="0" cy="0" r="1" gradientTransform="rotate(22.077 -36.35 22.772)scale(2.76699 3.40683)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="gaisxwbrp"/><stop offset=".99" class="r2oq_jbrj"/></radialGradient><radialGradient id="iX4X8Me" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73556 2.32336 -3.27993 -2.45013 27.14 14.958)" gradientUnits="userSpaceOnUse"><stop class="m0vgjjb4r"/><stop offset="1" class="iq5t73biu"/></radialGradient><radialGradient id="iGpQSQF" cx="0" cy="0" r="1" gradientTransform="matrix(1.54688 2.27647 -.5701 .38739 22.594 14.958)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="bmkg2sbeb"/><stop offset="1" class="udx_f9b6a"/></radialGradient><radialGradient id="ipnEznb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.11313 3.38489 0 16.052 15.25)" gradientUnits="userSpaceOnUse"><stop class="sf6is8s2j"/><stop offset="1" class="dw4mctsba"/></radialGradient><radialGradient id="iy5AJmz" cx="0" cy="0" r="1" gradientTransform="rotate(124.216 7.655 5.457)scale(.59279 .57705)" gradientUnits="userSpaceOnUse"><stop class="digbd6blf"/><stop offset="1" class="z3ta75bti"/></radialGradient><radialGradient id="iwj04Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.62745 -.87255 0 16.473 -.667)" gradientUnits="userSpaceOnUse"><stop class="digbd6blf"/><stop offset="1" class="z3ta75bti"/></radialGradient><radialGradient id="isQMMid" cx="0" cy="0" r="1" gradientTransform="matrix(4.70519 .5 -.53121 4.99888 18.86 15.656)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="mh6v9j2ja"/><stop offset="1" class="sbydx3joi"/></radialGradient><radialGradient id="i3KghCc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.56742 1.46873 -1.77472 -5.51901 18.015 15.406)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="rlab36tup"/><stop offset="1" class="ximszebkm"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:circus-tent" /></template>
<style>
.abolntb_v {
  stop-color: var(--svg-color--ff55ab, #FF55AB);
}

.adktqpbyv {
  d: path("M8.555 15.66c.103-.385.17-.57.342-.646c.03-.092.121-.259.335-.45l.172-.146c.793-.67 3.82-3.222 6.075-6.445h-.214c-2.076 1.994-5.968 4.379-7.428 5.27c-.997.61-2.002 1.223-2.55 1.557a.5.5 0 0 0-.24.427v.433z");
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.almegmbsu {
  fill: var(--svg-color--e62e8a, #E62E8A);
  d: path("M9.232 14.564c-.259.231-.339.427-.346.496c-.07.173.888.266 2.099.266c1.21 0 2.457-.07 2.56-.335c.739-1.707 1.854-5.394 2.319-7.024h-.38c-2.492 3.564-5.93 6.31-6.252 6.597");
}

.an7ekthzq {
  stop-color: var(--svg-color--c3c1c4, #C3C1C4);
}

.b-_2ti19t {
  d: path("m13.166 22.473l.344-6.907h5.074l.364 6.906z");
}

.bjbu_bb2k {
  fill: var(--svg-color--d2c9dc, #D2C9DC);
  d: path("M18.672 15.25c-.742-1.715-1.961-5.652-2.428-7.277h-.382c-.464 1.625-1.691 5.562-2.429 7.277z");
}

.bmkg2sbeb {
  stop-color: var(--svg-color--957d8d, #957D8D);
}

.dea0e4bih {
  fill: var(--svg-color--adaab0, #ADAAB0);
  d: path("M8.555 15.66c.103-.385.17-.57.342-.646c.03-.092.121-.259.335-.45l.172-.146c.793-.67 3.82-3.222 6.075-6.445h-.214c-2.076 1.994-5.968 4.379-7.428 5.27c-.997.61-2.002 1.223-2.55 1.557a.5.5 0 0 0-.24.427v.433z");
}

.dgk3unbtm {
  stop-color: var(--svg-color--fd2230, #FD2230);
  stop-opacity: 0;
}

.digbd6blf {
  stop-color: var(--svg-color--ffe65e, #FFE65E);
}

.do1e9gb2e {
  stop-color: var(--svg-color--ff4564, #FF4564);
}

.dvda_ycbn {
  stop-color: var(--svg-color--fff4ff, #FFF4FF);
}

.dw4mctsba {
  stop-color: var(--svg-color--b597d3, #B597D3);
  stop-opacity: 0;
}

.e5woykbnf {
  stop-color: var(--svg-color--ec3095, #EC3095);
}

.ee0nxr24c {
  d: path("M16.003 29.993h.054l8.512-.008c.496 0 .553-.407.516-.744c-.052-.468-1.091-8.904-1.62-13.107l-4.822-.844h-2.64z");
}

.efyhq6aow {
  stop-color: var(--svg-color--fef, #FEF);
  stop-opacity: 0;
}

.epa2cvt-u {
  stop-color: var(--svg-color--ff51aa, #FF51AA);
}

.f2jwpabvd {
  stop-color: var(--svg-color--f33161, #F33161);
  stop-opacity: 0;
}

.ffmv3lbrb {
  stop-color: var(--svg-color--c8afe2, #C8AFE2);
}

.fi2wlysof {
  stop-color: var(--svg-color--8a779c, #8A779C);
  stop-opacity: 0;
}

.fnuj_jbcr {
  stop-color: var(--svg-color--9c97a1, #9C97A1);
}

.ft5dv1b6b {
  fill: none;
}

.fw_cblbpw {
  stop-color: var(--svg-color--ff436d, #FF436D);
}

.g1aet7ifi {
  stop-color: var(--svg-color--817e84, #817E84);
  stop-opacity: 0;
}

.g2sgr8mmx {
  stop-color: var(--svg-color--644f7c, #644F7C);
}

.gaisxwbrp {
  stop-color: var(--svg-color--ded2e4, #DED2E4);
  stop-opacity: 0;
}

.gesvv2bcw {
  stop-color: var(--svg-color--9663a3, #9663A3);
}

.glx6xub_c {
  stop-color: var(--svg-color--9e87b5, #9E87B5);
}

.gosulzdmf {
  stop-color: var(--svg-color--fff4ff, #FFF4FF);
  stop-opacity: 0;
}

.gpnyj1b0k {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M13.516 21.828c-.577.21-1.732 1.112-1.732 3.043v4.435");
}

.hhitj8fwx {
  stop-color: var(--svg-color--ebe8ee, #EBE8EE);
  stop-opacity: 0;
}

.hwtdoqbhu {
  d: path("M23.512 15.698c-.153-.581-.222-.73-.637-.73h-3.97c-.38 0-.338.313-.319.454c.016.112.044.257.056.316c.311 1.316 1.545 2.23 2.857 2.23c1.761 0 2.24-1.505 2.013-2.27");
}

.i2fulr8cj {
  stop-color: var(--svg-color--f1d3ff, #F1D3FF);
}

.i9lef1c_r {
  d: path("M8.545 15.698c.153-.581.223-.73.64-.73h3.999c.383 0 .34.313.32.454a5 5 0 0 1-.056.316c-.313 1.316-1.555 2.23-2.877 2.23c-1.773 0-2.255-1.505-2.027-2.27");
}

.iboil8bjd {
  stop-color: var(--svg-color--9c9b9d, #9C9B9D);
  stop-opacity: 0;
}

.iegtdbqjb {
  fill-rule: evenodd;
  d: path("m11.009 30l5.077-.006q6.03-.009 12.059-.01c.774 0 .906-.49.84-1.044l-.187-1.536c-.133-1.089-.313-2.562-.477-3.922c-.277-2.29-1-6.828-1.089-7.384c-.09-.555-.25-.862-.663-.862h-15.56z");
}

.ihge7tbdv {
  d: path("M16.003 15.29h-2.544l-4.771.706A4930 4930 0 0 0 6.99 29.403c-.04.393.177.599.59.599l8.422-.009z");
}

.iinq6ac4y {
  fill: var(--svg-color--653e45, #653E45);
  d: path("M7.007 14.063h18.086v4.183H7.007z");
}

.iq5t73biu {
  stop-color: var(--svg-color--cbc4d4, #CBC4D4);
}

.it3f_9zqt {
  stop-color: var(--svg-color--bbb1c5, #BBB1C5);
}

.iv2ctj7tz {
  d: path("M18.683 2.902c-1.549-.649-2.252-.769-2.41-.748c0 .936.012 1.872 0 2.807c.54 0 3.273-.981 3.521-1.092s.254-.401 0-.517a25 25 0 0 0-1.111-.45");
}

.ix7ascc6q {
  stop-color: var(--svg-color--cc85ff, #CC85FF);
  stop-opacity: 0;
}

.j_f2huxqx {
  stop-color: var(--svg-color--e44730, #E44730);
  stop-opacity: 0;
}

.kfq40zqow {
  stop-color: var(--svg-color--806586, #806586);
}

.ks5ymd8mx {
  stop-color: var(--svg-color--f33161, #F33161);
}

.kwy6o1n-h {
  stop-color: var(--svg-color--ebe8ee, #EBE8EE);
}

.lco7ncowo {
  stop-color: var(--svg-color--817e84, #817E84);
}

.lt4agybjp {
  stop-color: var(--svg-color--bf70fc, #BF70FC);
}

.m0vgjjb4r {
  stop-color: var(--svg-color--f2eff4, #F2EFF4);
}

.mh6v9j2ja {
  stop-color: var(--svg-color--ff5768, #FF5768);
}

.mj5ai0wuc {
  stop-color: var(--svg-color--d33643, #D33643);
}

.n6n5q7z4u {
  d: path("M16.05 19.97c-2.67 0-5.041 2.17-5.041 4.84v5.186h9.987V24.81c0-2.67-2.276-4.84-4.946-4.84");
}

.n9t9q0bzq {
  stop-color: var(--svg-color--533f68, #533F68);
}

.njoxcwbsd {
  stop-color: var(--svg-color--f2e0ff, #F2E0FF);
}

.nxnomrl6m {
  stop-color: var(--svg-color--ff2464, #FF2464);
}

.o3ajxnbmt {
  fill: var(--svg-color--ff5e59, #FF5E59);
  d: path("M22.909 14.564c.26.231.34.427.348.496c.07.173-.893.266-2.11.266c-1.218 0-2.47-.07-2.574-.335c-.742-1.707-1.863-5.394-2.33-7.024h.383c2.503 3.564 5.958 6.31 6.283 6.597");
}

.o3mc0yj9q {
  stop-color: var(--svg-color--b32f73, #B32F73);
}

.omqbx3bgh {
  stop-color: var(--svg-color--9481a7, #9481A7);
}

.pezdmbb0l {
  stop-color: var(--svg-color--cc85ff, #CC85FF);
}

.pjj6wjldh {
  stop-color: var(--svg-color--81788b, #81788B);
}

.pn-xo0bof {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
  stop-opacity: 0;
}

.psd5utbfl {
  stop-color: var(--svg-color--644f7c, #644F7C);
  stop-opacity: 0;
}

.q8-63qpuh {
  stop-color: var(--svg-color--81788b, #81788B);
  stop-opacity: 0;
}

.qf376hl_o {
  d: path("M4.892 17.474c-.66-.865-.351-1.758-.14-2.156c.194-.367.378-.36.715-.36h2.914c.407 0 .5.089.304.59c-.196.5-.701 1.38-1.3 1.88s-1.834.912-2.493.046");
}

.qozzjrm-a {
  stop-color: var(--svg-color--ff4dbb, #FF4DBB);
}

.qqtrjabga {
  stop-color: var(--svg-color--ff5ea9, #FF5EA9);
  stop-opacity: 0;
}

.qtdijkbts {
  fill: var(--svg-color--ff5b65, #FF5B65);
  d: path("M22.909 14.564c.26.231.34.427.348.496c.07.173-.893.266-2.11.266c-1.218 0-2.465-.034-2.57-.299c-.741-1.707-1.867-5.43-2.334-7.06h.383c2.503 3.564 5.958 6.31 6.283 6.597");
}

.qxh3z3vnu {
  stop-color: var(--svg-color--d3c1e6, #D3C1E6);
}

.r2oq_jbrj {
  stop-color: var(--svg-color--ded2e4, #DED2E4);
}

.rfn8p6juo {
  stop-color: var(--svg-color--fd2230, #FD2230);
}

.rfna4kbaa {
  stop-color: var(--svg-color--bf70fc, #BF70FC);
  stop-opacity: 0;
}

.rlab36tup {
  stop-color: var(--svg-color--8b688a, #8B688A);
  stop-opacity: 0;
}

.rrowarz-c {
  stop-color: var(--svg-color--d30d68, #D30D68);
}

.s8ibn4mvw {
  stop-color: var(--svg-color--ec622e, #EC622E);
}

.sbydx3joi {
  stop-color: var(--svg-color--ff59bc, #FF59BC);
}

.sd1n-45mo {
  d: path("M18.672 15.25c-.742-1.715-1.961-5.652-2.428-7.277h-.382c-.464 1.625-1.691 5.562-2.429 7.277z");
}

.sf6is8s2j {
  stop-color: var(--svg-color--b597d3, #B597D3);
}

.svoxunfuh {
  stop-color: var(--svg-color--9663a3, #9663A3);
  stop-opacity: 0;
}

.t498k0bri {
  stop-color: var(--svg-color--fef, #FEF);
}

.t7lzpfbbk {
  stop-color: var(--svg-color--9c97a1, #9C97A1);
  stop-opacity: 0;
}

.tvzsfqhus {
  stop-color: var(--svg-color--d30d68, #D30D68);
  stop-opacity: 0;
}

.txx1a2bwg {
  d: path("M14.999 7.648c0 .254.147.385.336.385h1.255c.27 0 .402-.189.402-.385v-.5c0-.64-.402-.73-.402-1.297V2.767c0-.525-.27-.697-.574-.697s-.582.172-.582.697v3.084c0 .632-.435.542-.435 1.296z");
}

.u16y8mbxn {
  stop-color: var(--svg-color--cc2d70, #CC2D70);
}

.u7oio7bil {
  d: path("M27.14 17.474c.654-.865.348-1.758.139-2.156c-.193-.367-.377-.36-.711-.36h-2.894c-.404 0-.497.089-.302.59c.195.5.697 1.38 1.291 1.88c.595.5 1.821.912 2.476.046");
}

.udx_f9b6a {
  stop-color: var(--svg-color--957d8d, #957D8D);
  stop-opacity: 0;
}

.ugdfpa_dp {
  stop-color: var(--svg-color--9c9b9d, #9C9B9D);
}

.uq_64wbwx {
  d: path("M9.232 14.564c-.259.231-.339.427-.346.496c-.07.173.888.266 2.099.266c1.21 0 2.457-.07 2.56-.335c.739-1.707 1.854-5.394 2.319-7.024h-.38c-2.492 3.564-5.93 6.31-6.252 6.597");
}

.uqp0_bv0v {
  stop-color: var(--svg-color--a8b, #A8B);
}

.ux8x8_bek {
  stop-color: var(--svg-color--f1d3ff, #F1D3FF);
  stop-opacity: 0;
}

.v_8rtja-e {
  stop-color: var(--svg-color--e849a5, #E849A5);
  stop-opacity: 0;
}

.vg2nhccic {
  stop-color: var(--svg-color--a19fa4, #A19FA4);
  stop-opacity: 0;
}

.vvk5gcc8o {
  d: path("M23.798 15.322c-3.854-2.459-7.526-7.35-7.526-7.35h.433c.892.736 3.13 2.501 4.947 3.682c1.317.856 2.629 1.647 3.653 2.264c.479.289.894.54 1.219.741a.96.96 0 0 1 .448.82v.181s.68 2.12-3.174-.338");
}

.vzicwmbfk {
  stop-color: var(--svg-color--e849a5, #E849A5);
}

.wcpg47b1z {
  stop-color: var(--svg-color--e44730, #E44730);
}

.wcw3drb6p {
  stop-color: var(--svg-color--a19fa4, #A19FA4);
}

.wfrswybfg {
  d: path("M14.018 15.002H18.3c.289 0 .32.158.355.447c.125 1.625-1.296 2.526-2.658 2.526c-1.664 0-2.664-1.355-2.54-2.526c.048-.447.158-.447.56-.447");
}

.wph8q-bqo {
  stop-color: var(--svg-color--aa4350, #AA4350);
}

.wqso7kyoe {
  stop-color: var(--svg-color--f63b5e, #F63B5E);
}

.x4-r_-foh {
  stop-color: var(--svg-color--c0bcbd, #C0BCBD);
}

.xae324byd {
  stop-color: var(--svg-color--dc364a, #DC364A);
}

.ximszebkm {
  stop-color: var(--svg-color--8b688a, #8B688A);
}

.xjntzhbyx {
  stop-color: var(--svg-color--ff5ea9, #FF5EA9);
}

.xk-4-6bhe {
  stop-color: var(--svg-color--a89bb6, #A89BB6);
}

.xm-ocvwqq {
  stop-color: var(--svg-color--8a779c, #8A779C);
}

.xtak37bzz {
  stop-color: var(--svg-color--40364b, #40364B);
}

.xv-yltbce {
  stop-color: var(--svg-color--ffa94b, #FFA94B);
}

.y882llhzt {
  stop-color: var(--svg-color--ff3eac, #FF3EAC);
}

.y8cf4cbun {
  stop-color: var(--svg-color--bd3152, #BD3152);
}

.y8vxw2bje {
  stop-color: var(--svg-color--ff2464, #FF2464);
  stop-opacity: 0;
}

.z19p6pvyb {
  d: path("M22.909 14.564c.26.231.34.427.348.496c.07.173-.893.266-2.11.266c-1.218 0-2.465-.034-2.57-.299c-.741-1.707-1.867-5.43-2.334-7.06h.383c2.503 3.564 5.958 6.31 6.283 6.597");
}

.z1inge64e {
  stop-color: var(--svg-color--ff43a4, #FF43A4);
}

.z3ta75bti {
  stop-color: var(--svg-color--ffe65e, #FFE65E);
  stop-opacity: 0;
}

.z5octemly {
  stop-color: var(--svg-color--b32f73, #B32F73);
  stop-opacity: 0;
}

.z76-9ebyb {
  d: path("M11.009 15.236V30l-6.982.004c-.683 0-1.065-.366-1.017-.986S4.6 16.905 4.822 15.951c1.437-.56 3.238-.71 3.958-.715z");
}

.zdzs69inc {
  stop-color: var(--svg-color--c1bfc2, #C1BFC2);
}

</style>
