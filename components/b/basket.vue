<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iMWy7Qc" class="oc-r1blvf"/></defs><g class="ft5dv1b6b"><use href="#iMWy7Qc" class="dgzelcbqo"/><use href="#iMWy7Qc" class="dgzelcbqo"/><use href="#iMWy7Qc" class="dgzelcbqo"/><path fill="url(#iCmSUQd)" class="e5cu7xb4f"/><path fill="url(#ilNK1Hd)" class="e5cu7xb4f"/><path fill="url(#irp3bee)" class="e5cu7xb4f"/><path fill="url(#iQIm5Yc)" class="e5cu7xb4f"/><g filter="url(#iTM0D6O)"><path fill="url(#iJbENue)" class="x1i906erw"/></g><g filter="url(#i5DoSZd)"><path fill="url(#iey9ITc)" class="rodedwbsq"/></g><g filter="url(#ir4RnTb)"><path fill="url(#iv2vVFe)" class="fu4zcbbhg"/></g><g filter="url(#iVGwurw)"><path class="zm__3dbtv"/></g><g filter="url(#iaSctQc)"><path fill="url(#iN4HEvd)" class="idns_ibkl"/></g><g filter="url(#iDffHkc)"><path class="hq-a7v4tp"/><path class="orbfnqbgz"/></g><g filter="url(#iztvpmA)"><path fill="url(#iUkkYHc)" class="lwomiiipw"/></g><g filter="url(#i8aZ1bK)"><path class="dhgp5wlye"/><path fill="url(#iYGS9zc)" class="uoos0pn5y"/></g><g filter="url(#irz6TEc)"><path fill="url(#ifQ4r5W)" class="pbftr1b3f"/></g><g filter="url(#iIsFODc)"><path class="ej9de1btf"/><path fill="url(#irgtbGd)" class="sm2p805_p"/></g><g filter="url(#iPiNM4c)"><path fill="url(#ix42IBd)" class="nffkxxbug"/></g><g filter="url(#ixplIrb)"><path fill="url(#iQecoqS)" class="ezwa8tbqe"/><path fill="url(#iKv9Ndc)" class="ezwa8tbqe"/></g><g filter="url(#iztWYye)"><path fill="url(#ixr89ae)" class="y_xju_s_b"/><path fill="url(#iL3uMxn)" class="y_xju_s_b"/></g><g filter="url(#iWLRIDc)"><path fill="url(#iOSTyjF)" class="wzz9fibxj"/></g><g filter="url(#iB8PLpb)"><path fill="url(#icdHWwc)" class="p72l95bbh"/></g><g filter="url(#i6rVXnb)"><path fill="url(#i5CRQ4b)" class="ugz-jthii"/><path fill="url(#iNcIsEe)" class="ugz-jthii"/></g><path fill="url(#inh0Grb)" clip-rule="evenodd" class="q3bvr1-lq"/><path fill="url(#iiv7DqI)" clip-rule="evenodd" class="q3bvr1-lq"/><rect fill="url(#iL5jLon)" class="rpwht9egv"/><rect fill="url(#iVbEM0f)" class="rpwht9egv"/><rect fill="url(#ivv9KKe)" class="rpwht9egv"/><rect fill="url(#iwJGyRd)" class="rpwht9egv"/><rect fill="url(#itLulAd)" class="rpwht9egv"/><rect fill="url(#inbfUud)" class="rpwht9egv"/><rect fill="url(#iOYA2jY)" class="rpwht9egv"/><g filter="url(#isNJIod)"><path class="cnkbhxkaa"/></g><g filter="url(#iRaMyLd)"><path fill="url(#iQZWLpc)" class="iq8occblw"/><path fill="url(#iHBlune)" class="iq8occblw"/><path fill="url(#idRRKHd)" class="iq8occblw"/></g><g filter="url(#i3HpzIe)"><path fill="url(#iF22UTb)" class="e_a9k7h0g"/><path fill="url(#iFnMocM)" class="e_a9k7h0g"/></g><defs><linearGradient id="ilNK1Hd" x1="4.075" x2="19.95" y1="20.521" y2="22.63" gradientUnits="userSpaceOnUse"><stop offset=".213" class="bplfxdfrt"/><stop offset="1" class="jo93x4bgt"/></linearGradient><linearGradient id="irp3bee" x1="18.137" x2="18.137" y1="30.197" y2="28.177" gradientUnits="userSpaceOnUse"><stop class="ow2yv0fhv"/><stop offset="1" class="abqx1-bby"/></linearGradient><linearGradient id="iQIm5Yc" x1="16.091" x2="16.091" y1="15.064" y2="17.115" gradientUnits="userSpaceOnUse"><stop class="hkcuiabba"/><stop offset="1" class="p5f30acvv"/></linearGradient><linearGradient id="iJbENue" x1="11.613" x2="23.982" y1="17.672" y2="30.335" gradientUnits="userSpaceOnUse"><stop class="rr1zc3blj"/><stop offset="1" class="lui-8gy_i"/></linearGradient><linearGradient id="iey9ITc" x1="8.115" x2="20.552" y1="17.718" y2="30.498" gradientUnits="userSpaceOnUse"><stop class="mzd37bbfw"/><stop offset="1" class="bq28rl01a"/></linearGradient><linearGradient id="iv2vVFe" x1="6.762" x2="16.521" y1="19.927" y2="29.396" gradientUnits="userSpaceOnUse"><stop class="we6cdrw9y"/><stop offset="1" class="dcyht_bhl"/></linearGradient><linearGradient id="iN4HEvd" x1="14.871" x2="25.413" y1="17.286" y2="27.939" gradientUnits="userSpaceOnUse"><stop class="rr1zc3blj"/><stop offset="1" class="lui-8gy_i"/></linearGradient><linearGradient id="iUkkYHc" x1="18.259" x2="26.292" y1="16.757" y2="24.936" gradientUnits="userSpaceOnUse"><stop class="mlk754bqh"/><stop offset="1" class="tlu1kc06e"/></linearGradient><linearGradient id="iYGS9zc" x1="5.137" x2="5.528" y1="19.927" y2="20.271" gradientUnits="userSpaceOnUse"><stop class="rtvyf2l6d"/><stop offset="1" class="zjs-1ynsq"/></linearGradient><linearGradient id="ifQ4r5W" x1="21.647" x2="27.171" y1="16.229" y2="21.931" gradientUnits="userSpaceOnUse"><stop class="mlk754bqh"/><stop offset="1" class="tlu1kc06e"/></linearGradient><linearGradient id="irgtbGd" x1="3.7" x2="4.14" y1="17.381" y2="17.696" gradientUnits="userSpaceOnUse"><stop offset=".156" class="rtvyf2l6d"/><stop offset="1" class="zjs-1ynsq"/></linearGradient><linearGradient id="ix42IBd" x1="25.035" x2="28.047" y1="15.7" y2="18.924" gradientUnits="userSpaceOnUse"><stop class="mlk754bqh"/><stop offset="1" class="tlu1kc06e"/></linearGradient><linearGradient id="iQecoqS" x1="10.071" x2="22.128" y1="27.488" y2="16.364" gradientUnits="userSpaceOnUse"><stop class="uhww3nb1j"/><stop offset="1" class="zh1ss-btm"/><stop offset="1" class="lk9n1rbck"/></linearGradient><linearGradient id="iKv9Ndc" x1="10.418" x2="11.175" y1="25.99" y2="26.473" gradientUnits="userSpaceOnUse"><stop class="t02w-h0-n"/><stop offset="1" class="s_ha1i5fu"/></linearGradient><linearGradient id="ixr89ae" x1="11.512" x2="25.475" y1="30.552" y2="16.273" gradientUnits="userSpaceOnUse"><stop class="s2fcd8byf"/><stop offset="1" class="pvz1_3qjj"/></linearGradient><linearGradient id="iL3uMxn" x1="13.642" x2="14.412" y1="26.175" y2="26.671" gradientUnits="userSpaceOnUse"><stop class="t02w-h0-n"/><stop offset="1" class="s_ha1i5fu"/></linearGradient><linearGradient id="iOSTyjF" x1="15.412" x2="27.562" y1="30.506" y2="18.579" gradientUnits="userSpaceOnUse"><stop class="a5qqyubvo"/><stop offset="1" class="vcjboc1hd"/></linearGradient><linearGradient id="icdHWwc" x1="19.252" x2="26.023" y1="30.369" y2="23.722" gradientUnits="userSpaceOnUse"><stop class="a5qqyubvo"/><stop offset="1" class="vcjboc1hd"/></linearGradient><linearGradient id="i5CRQ4b" x1="8.543" x2="19.45" y1="25.459" y2="15.064" gradientUnits="userSpaceOnUse"><stop class="aai16citf"/><stop offset="1" class="zh1ss-btm"/></linearGradient><linearGradient id="iNcIsEe" x1="8.71" x2="9.464" y1="23.954" y2="24.605" gradientUnits="userSpaceOnUse"><stop class="t02w-h0-n"/><stop offset="1" class="s_ha1i5fu"/></linearGradient><linearGradient id="inh0Grb" x1="33.313" x2="16.144" y1="22" y2="15.064" gradientUnits="userSpaceOnUse"><stop class="rl7d0ccrw"/><stop offset="1" class="i339uab_l"/></linearGradient><linearGradient id="iiv7DqI" x1="15.563" x2="15.563" y1="33.188" y2="27.625" gradientUnits="userSpaceOnUse"><stop offset=".27" class="vg_wgmytu"/><stop offset="1" class="aib48lbwl"/></linearGradient><linearGradient id="iL5jLon" x1="24.762" x2="11.887" y1="12.104" y2="24.834" gradientUnits="userSpaceOnUse"><stop class="enovc_rbs"/><stop offset="1" class="zjthxcbzc"/></linearGradient><linearGradient id="ivv9KKe" x1="30.575" x2="28.2" y1="14.896" y2="14.959" gradientUnits="userSpaceOnUse"><stop offset=".089" class="khu18p50j"/><stop offset="1" class="arvi0mb8k"/></linearGradient><linearGradient id="iwJGyRd" x1="20.7" x2="20.7" y1="16.115" y2="15.24" gradientUnits="userSpaceOnUse"><stop class="rlvtu1hnt"/><stop offset="1" class="v304sybqf"/></linearGradient><linearGradient id="iOYA2jY" x1="2.918" x2="4.356" y1="16.459" y2="12.959" gradientUnits="userSpaceOnUse"><stop class="dj_lv3pfy"/><stop offset="1" class="t0wf1v4ia"/></linearGradient><linearGradient id="iQZWLpc" x1="16" x2="16" y1="2.364" y2="15.051" gradientUnits="userSpaceOnUse"><stop class="wye3atf3f"/><stop offset="1" class="u0tzp7ntd"/></linearGradient><linearGradient id="iF22UTb" x1="11.718" x2="11.718" y1="3.326" y2="12.63" gradientUnits="userSpaceOnUse"><stop class="wye3atf3f"/><stop offset="1" class="u0tzp7ntd"/></linearGradient><linearGradient id="iFnMocM" x1="11.212" x2="11.212" y1="3.421" y2="7.365" gradientUnits="userSpaceOnUse"><stop offset=".263" class="w-z26ebyc"/><stop offset="1" class="p9h7hgrnr"/></linearGradient><filter id="iTM0D6O" width="15.835" height="15.018" x="8.018" y="15.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="i5DoSZd" width="15.982" height="15.102" x="4.488" y="15.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="ir4RnTb" width="12.806" height="12.428" x="3.865" y="17.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.337255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26154" result="effect2_innerShadow_18_26154"/></filter><filter id="iVGwurw" width="6.832" height="6.64" x="5.891" y="23.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.337255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iaSctQc" width="13.342" height="12.797" x="11.823" y="15.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iDffHkc" width="9.928" height="9.558" x="5.727" y="14.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.337255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iztvpmA" width="10.278" height="9.753" x="15.884" y="15.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="i8aZ1bK" width="6.857" height="6.505" x="4.737" y="14.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.337255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="irz6TEc" width="7.215" height="6.709" x="19.945" y="15.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iIsFODc" width="3.785" height="3.453" x="3.748" y="14.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.337255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iPiNM4c" width="4.151" height="3.664" x="24.006" y="15.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.603922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="ixplIrb" width="15.619" height="15.042" x="7.901" y="14.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.4 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iztWYye" width="15.932" height="15.202" x="11.219" y="15.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iWLRIDc" width="13.324" height="13.241" x="15.167" y="17.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.564706 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="iB8PLpb" width="7.47" height="7.423" x="19.116" y="22.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.564706 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="i6rVXnb" width="13" height="12.61" x="6.716" y="14.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.364706 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="isNJIod" width="2.699" height="3.699" x="19.97" y="11.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26154" stdDeviation=".25"/></filter><filter id="iRaMyLd" width="14.345" height="12.937" x="8.953" y="2.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.466667 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><filter id="i3HpzIe" width="3.532" height="8.682" x="9.497" y="3.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.580392 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26154"/></filter><radialGradient id="iCmSUQd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.338 15.844 8.313)scale(10.3314 14.7527)" gradientUnits="userSpaceOnUse"><stop class="e6ts6_bdd"/><stop offset="1" class="uovxjzb8i"/></radialGradient><radialGradient id="iVbEM0f" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.3125 -6.625 0 25.575 11.646)" gradientUnits="userSpaceOnUse"><stop class="w5ry8p2zc"/><stop offset="1" class="ehm-dq_9g"/></radialGradient><radialGradient id="itLulAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -17.6671 0 21.481 11.177)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="lfuv0ccas"/><stop offset="1" class="gu0wn3bxh"/></radialGradient><radialGradient id="inbfUud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .5 -9.65625 0 24.669 12.865)" gradientUnits="userSpaceOnUse"><stop class="qugwsd39v"/><stop offset="1" class="tqwx9d36g"/></radialGradient><radialGradient id="iHBlune" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 3.34375 -6.22794 7.62488 9.825 3.709)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="y2kgzgbzu"/><stop offset="1" class="plazpbc7f"/></radialGradient><radialGradient id="idRRKHd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.09374 .96878 -.55837 -2.35948 23.606 3.802)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="j-__qbb0q"/><stop offset="1" class="mz3f5ubxf"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:basket" /></template>
<style>
.a5qqyubvo {
  stop-color: var(--svg-color--b6794d, #B6794D);
}

.aai16citf {
  stop-color: var(--svg-color--9a6640, #9A6640);
}

.abqx1-bby {
  stop-color: var(--svg-color--cc9467, #CC9467);
  stop-opacity: 0;
}

.aib48lbwl {
  stop-color: var(--svg-color--8e5a50, #8E5A50);
  stop-opacity: 0;
}

.arvi0mb8k {
  stop-color: var(--svg-color--f9c385, #F9C385);
  stop-opacity: 0;
}

.bplfxdfrt {
  stop-color: var(--svg-color--b0845b, #B0845B);
}

.bq28rl01a {
  stop-color: var(--svg-color--b97c4d, #B97C4D);
}

.cnkbhxkaa {
  fill: var(--svg-color--da9653, #DA9653);
  d: path("M20.47 12.396h1.699v1.85a.85.85 0 0 1-1.699 0z");
}

.dcyht_bhl {
  stop-color: var(--svg-color--a56c46, #A56C46);
}

.dgzelcbqo {
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
}

.dhgp5wlye {
  fill: var(--svg-color--8e6243, #8E6243);
  d: path("m11.594 15.064l-6.396 6.355l-.31-.96l5.429-5.395z");
}

.dj_lv3pfy {
  stop-color: var(--svg-color--a07965, #A07965);
}

.e_a9k7h0g {
  d: path("M12.924 3.422c-1.102 0-1.8 1.531-1.8 2.537v6.144H9.498V6.496c0-3.17 3.569-3.074 3.427-3.074");
}

.e5cu7xb4f {
  d: path("M7.483 28.468L3.138 15.064h25.906L24.65 28.476a2.5 2.5 0 0 1-2.376 1.721H9.862a2.5 2.5 0 0 1-2.379-1.729");
}

.e6ts6_bdd {
  stop-color: var(--svg-color--f4b572, #F4B572);
}

.ehm-dq_9g {
  stop-color: var(--svg-color--ffcd87, #FFCD87);
  stop-opacity: 0;
}

.ej9de1btf {
  fill: var(--svg-color--8e6243, #8E6243);
  d: path("m7.533 15.064l-3.324 3.303l-.311-.96l2.358-2.343z");
}

.enovc_rbs {
  stop-color: var(--svg-color--fbc584, #FBC584);
}

.ezwa8tbqe {
  d: path("m23.268 15.064l.253.254L8.79 29.956a2.5 2.5 0 0 1-.74-.534L22.5 15.064z");
}

.ft5dv1b6b {
  fill: none;
}

.fu4zcbbhg {
  d: path("M16.521 30.197h-1.277L4.622 19.641l-.607-1.872z");
}

.gu0wn3bxh {
  stop-color: var(--svg-color--da9954, #DA9954);
  stop-opacity: 0;
}

.hkcuiabba {
  stop-color: var(--svg-color--b58253, #B58253);
}

.hq-a7v4tp {
  fill: var(--svg-color--8e6243, #8E6243);
  d: path("M15.655 15.064L6.188 24.47l-.311-.96l8.5-8.447z");
}

.i339uab_l {
  stop-color: var(--svg-color--d4945a, #D4945A);
  stop-opacity: 0;
}

.idns_ibkl {
  d: path("m24.851 27.861l.314-.957l-11.915-11.84h-1.277z");
}

.iq8occblw {
  d: path("M8.953 6.164a3.8 3.8 0 0 1 3.8-3.8h6.695a3.6 3.6 0 0 1 3.6 3.6v8.003a1.084 1.084 0 0 1-2.168 0V5.722c0-1.27-1.09-2.3-1.83-2.3h-6.126c-1.097 0-1.79 1.531-1.79 2.537v6.144H8.952z");
}

.j-__qbb0q {
  stop-color: var(--svg-color--eeaa73, #EEAA73);
}

.jo93x4bgt {
  stop-color: var(--svg-color--b0845b, #B0845B);
  stop-opacity: 0;
}

.khu18p50j {
  stop-color: var(--svg-color--f9c385, #F9C385);
}

.lfuv0ccas {
  stop-color: var(--svg-color--da9954, #DA9954);
}

.lk9n1rbck {
  stop-color: var(--svg-color--c18352, #C18352);
}

.lui-8gy_i {
  stop-color: var(--svg-color--cd8d55, #CD8D55);
}

.lwomiiipw {
  d: path("m25.849 24.817l.313-.957l-8.851-8.796h-1.277z");
}

.mlk754bqh {
  stop-color: var(--svg-color--b97b4c, #B97B4C);
}

.mz3f5ubxf {
  stop-color: var(--svg-color--eeaa73, #EEAA73);
  stop-opacity: 0;
}

.mzd37bbfw {
  stop-color: var(--svg-color--91603f, #91603F);
}

.nffkxxbug {
  d: path("m27.843 18.728l.314-.957l-2.724-2.707h-1.277z");
}

.oc-r1blvf {
  fill: var(--svg-color--4cc88c, #4CC88C);
  d: path("M7.483 28.468L3.138 15.064h25.906L24.65 28.476a2.5 2.5 0 0 1-2.376 1.721H9.862a2.5 2.5 0 0 1-2.379-1.729");
}

.orbfnqbgz {
  fill: var(--svg-color--946340, #946340);
  d: path("M15.655 15.064L6.188 24.47l-.311-.96l8.5-8.447z");
}

.ow2yv0fhv {
  stop-color: var(--svg-color--af7c6d, #AF7C6D);
}

.p5f30acvv {
  stop-color: var(--svg-color--b58253, #B58253);
  stop-opacity: 0;
}

.p72l95bbh {
  d: path("M20.392 30.197h-1.276l7.37-7.323l-.617 1.881z");
}

.p9h7hgrnr {
  stop-color: var(--svg-color--ca7c35, #CA7C35);
  stop-opacity: 0;
}

.pbftr1b3f {
  d: path("m26.846 21.773l.314-.958l-5.788-5.751h-1.277z");
}

.plazpbc7f {
  stop-color: var(--svg-color--cd7e35, #CD7E35);
  stop-opacity: 0;
}

.pvz1_3qjj {
  stop-color: var(--svg-color--ce8e56, #CE8E56);
}

.q3bvr1-lq {
  fill-rule: evenodd;
  d: path("m6.387 16.203l1.146-1.14H6.256l-.508.505l-.476-.473l-.634.638l.472.47l-1.212 1.204l.724 2.234l.544.541l-.279.277l.311.96l.607-.602L7.197 22.2l-1.32 1.312l.621 1.917l.755.75l-.387.385l.311.96l.714-.71l1.393 1.383l-1.233 1.225c.212.221.462.403.74.534l1.131-1.125l1.336 1.328l-.039.038h1.354l-.039-.038l1.336-1.328l1.336 1.328l-.039.038h1.354l-.038-.038l1.335-1.328l1.336 1.328l-.038.038h1.354l-.039-.038l1.336-1.328l1.258 1.25c.303-.095.584-.247.828-.445l-1.448-1.439l1.392-1.383l1.054 1.047l.314-.957l-.73-.725l1.393-1.383l.02.02l.637-1.942l-.657.653l-1.336-1.327l1.392-1.383l.962.956l.314-.958l-.638-.633l1.253-1.244l.616-1.882l-.477.474l-1.335-1.327l.472-.47l-.634-.638l-.477.473l-.507-.504h-1.277l1.146 1.139l-1.392 1.383l-1.336-1.327l.947-.941l-.253-.254H22.5l-.564.56l-.564-.56h-1.277l1.202 1.195l-1.392 1.383l-1.392-1.383l1.203-1.195h-1.277l-.564.56l-.564-.56h-1.277l1.202 1.195l-1.392 1.383l-1.392-1.383l1.203-1.195h-1.277l-.564.56l-.564-.56h-1.277l1.202 1.195l-1.392 1.383l-1.392-1.383l1.203-1.195h-1.277l-.564.56l-.564-.56H8.42l-.253.254l.946.94l-1.335 1.328zm8.819 2.073l-1.392-1.383l-1.392 1.383l1.392 1.384zm-.754 2.018l1.392-1.383l1.392 1.383l-1.392 1.383zm-1.277 0l-1.392-1.383l-1.335 1.327l1.392 1.384zm-.697 1.962l1.336-1.328l1.392 1.384l-1.336 1.327zm-1.277 0L9.81 20.872L8.474 22.2l1.392 1.383zm-.697 1.962l1.336-1.328l1.392 1.384l-1.336 1.327zm-1.277 0l-1.392-1.384L6.5 24.162l1.392 1.383zm-.697 1.961l1.336-1.327l1.392 1.383l-1.336 1.328zm7.953-7.903l1.392-1.383l1.392 1.383l-1.392 1.384zm4.645 9.921l-1.335 1.327l-1.336-1.327l1.335-1.327zm2.03-2.018l-1.391 1.384l-1.336-1.328l1.392-1.383zm2.031-2.017l-1.392 1.383l-1.336-1.327l1.393-1.384zm2.087-5.998l-1.336-1.327l-1.392 1.383l1.336 1.328zm-2.03 2.018l-1.336-1.327l-1.392 1.383l1.335 1.328zm-2.03 2.018l-1.337-1.328l-1.392 1.384l1.336 1.327zm-2.031 2.018l-1.336-1.328l-1.392 1.384l1.335 1.327zm-2.03 2.017l-1.337-1.327l-1.335 1.327l1.335 1.328zm-1.975 1.962l-1.336-1.327l-1.335 1.327l1.335 1.327zm-3.948 0l-1.336 1.328l-1.336-1.328l1.336-1.327zm1.974-1.962l-1.336 1.328l-1.335-1.328l1.335-1.327zm1.974-1.961L15.844 25.6l-1.335-1.327l1.335-1.328zm2.03-2.018l-1.392 1.383l-1.335-1.327l1.392-1.383zm2.031-2.018l-1.392 1.384l-1.336-1.328l1.392-1.383zm2.03-2.018l-1.392 1.384l-1.335-1.328l1.392-1.383zM5.748 16.837l-1.335 1.327l1.392 1.384L7.14 18.22zm4.005.056L8.417 18.22l1.392 1.384l1.336-1.328zm-1.974 1.962l-1.336 1.327l1.392 1.384l1.336-1.328z");
}

.qugwsd39v {
  stop-color: var(--svg-color--ffd899, #FFD899);
}

.rl7d0ccrw {
  stop-color: var(--svg-color--d4945a, #D4945A);
}

.rlvtu1hnt {
  stop-color: var(--svg-color--c6854e, #C6854E);
}

.rodedwbsq {
  d: path("M20.47 30.197h-1.277L4.638 15.733l.634-.638z");
}

.rpwht9egv {
  width: 27.905px;
  height: 4.01px;
  x: 2.152px;
  y: 12.104px;
  rx: 0.9px;
}

.rr1zc3blj {
  stop-color: var(--svg-color--9a633e, #9A633E);
}

.rtvyf2l6d {
  stop-color: var(--svg-color--9a8070, #9A8070);
}

.s_ha1i5fu {
  stop-color: var(--svg-color--947562, #947562);
  stop-opacity: 0;
}

.s2fcd8byf {
  stop-color: var(--svg-color--a46b46, #A46B46);
}

.sm2p805_p {
  d: path("m7.533 15.064l-3.324 3.303l-.311-.96l2.358-2.343z");
}

.t02w-h0-n {
  stop-color: var(--svg-color--947562, #947562);
}

.t0wf1v4ia {
  stop-color: var(--svg-color--cc975f, #CC975F);
  stop-opacity: 0;
}

.tlu1kc06e {
  stop-color: var(--svg-color--d59458, #D59458);
}

.tqwx9d36g {
  stop-color: var(--svg-color--ffd899, #FFD899);
  stop-opacity: 0;
}

.u0tzp7ntd {
  stop-color: var(--svg-color--e09959, #E09959);
}

.ugz-jthii {
  d: path("M19.716 15.064L7.177 27.524l-.31-.96l11.572-11.5z");
}

.uhww3nb1j {
  stop-color: var(--svg-color--976441, #976441);
}

.uoos0pn5y {
  d: path("m11.594 15.064l-6.396 6.355l-.31-.96l5.429-5.395z");
}

.uovxjzb8i {
  stop-color: var(--svg-color--e8a464, #E8A464);
}

.v304sybqf {
  stop-color: var(--svg-color--c6854e, #C6854E);
  stop-opacity: 0;
}

.vcjboc1hd {
  stop-color: var(--svg-color--d4955b, #D4955B);
}

.vg_wgmytu {
  stop-color: var(--svg-color--8e5a50, #8E5A50);
}

.w-z26ebyc {
  stop-color: var(--svg-color--ca7c35, #CA7C35);
}

.w5ry8p2zc {
  stop-color: var(--svg-color--ffcd87, #FFCD87);
}

.we6cdrw9y {
  stop-color: var(--svg-color--8c6142, #8C6142);
}

.wye3atf3f {
  stop-color: var(--svg-color--e49b5a, #E49B5A);
}

.wzz9fibxj {
  d: path("M16.444 30.197h-1.277l13.224-13.14l-.616 1.88z");
}

.x1i906erw {
  d: path("M23.025 30.082c.303-.096.584-.248.828-.446L9.189 15.064H8.42l-.253.254z");
}

.y_xju_s_b {
  d: path("M12.496 30.197h-1.277l15.198-15.102l.634.638z");
}

.y2kgzgbzu {
  stop-color: var(--svg-color--cd7e35, #CD7E35);
}

.zh1ss-btm {
  stop-color: var(--svg-color--b4784c, #B4784C);
}

.zjs-1ynsq {
  stop-color: var(--svg-color--9a8070, #9A8070);
  stop-opacity: 0;
}

.zjthxcbzc {
  stop-color: var(--svg-color--c38e57, #C38E57);
}

.zm__3dbtv {
  fill: var(--svg-color--8e6144, #8E6144);
  d: path("M12.573 30.197h-1.277L6.498 25.43l-.607-1.872z");
}

</style>
