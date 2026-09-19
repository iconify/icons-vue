<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ikoviJQ)" class="q6kd1acht"/><path fill="url(#iu4R1Ab)" class="q6kd1acht"/><path fill="url(#imFQvVd)" class="q6kd1acht"/><path fill="url(#iXpDxSd)" class="q6kd1acht"/><path fill="url(#iVsUO5b)" class="pgjh8db0y"/><path fill="url(#iqki5qd)" class="pgjh8db0y"/><path fill="url(#isOk6wd)" class="pgjh8db0y"/><path fill="url(#i3Pdt6c)" class="pgjh8db0y"/><path fill="url(#iacwHWh)" class="hyrkarmdc"/><path fill="url(#iOAadbi)" class="hyrkarmdc"/><path fill="url(#imXgq6d)" class="hyrkarmdc"/><path fill="url(#i4qXIZv)" class="hyrkarmdc"/><g filter="url(#ixTl6wb)"><path fill="url(#ieMdPzc)" class="fsztfkb0e"/></g><path fill="url(#iYEoaPd)" class="fsztfkb0e"/><g filter="url(#idqHMId)"><path fill="url(#i71IVie)" class="em6clacso"/></g><path fill="url(#iF6PFqc)" class="em6clacso"/><g filter="url(#iL8jJfX)"><path fill="url(#iDs4Hpd)" class="xh50n7bui"/></g><path fill="url(#iiCt6Vb)" class="xh50n7bui"/><g filter="url(#ihHvbFe)"><path fill="url(#i1Ejbjb)" class="hgracsb0w"/></g><g filter="url(#i2Xyhfe)"><path fill="url(#i5REZ4d)" class="cevonje8d"/><path fill="url(#i6rdfPe)" class="cevonje8d"/></g><g filter="url(#inPRqje)"><path fill="url(#i1rV1fo)" class="lr5ht2brr"/><path fill="url(#i4AIGMv)" class="lr5ht2brr"/></g><g filter="url(#iHx1rCQ)"><path fill="url(#iL0Tf8f)" class="vqfay7w9y"/><path fill="url(#idtyHHc)" class="vqfay7w9y"/></g><g filter="url(#i8BOlrc)"><path fill="url(#it8gGvd)" class="si6np4b5k"/><path fill="url(#i6UyoSc)" class="si6np4b5k"/></g><g filter="url(#iCFTHne)"><path fill="url(#iAR008A)" class="zxybgi6sg"/><path fill="url(#i8RFGAU)" class="zxybgi6sg"/></g><g filter="url(#iw2hFGb)"><path fill="url(#inIwi1b)" class="bin-9zp3w"/><path fill="url(#iHEUNSd)" class="bin-9zp3w"/></g><g filter="url(#izCwmge)"><path fill="url(#iv3IVnv)" class="rhg321euv"/><path fill="url(#iDEn1QL)" class="rhg321euv"/></g><g filter="url(#ijDj9zc)"><path stroke="url(#iSI9bdd)" class="tajk8nbbd"/></g><g filter="url(#iXpARDe)"><path stroke="url(#iDLdtvk)" class="t_x8embww"/></g><g filter="url(#iM4lvEW)"><path stroke="url(#i8bxwZB)" class="h2tlpzbae"/></g><g filter="url(#iUV1kse)"><path stroke="url(#imcIHfd)" class="k4-3rcp1w"/></g><g filter="url(#i5n6F0c)"><path stroke="url(#iBFQfke)" class="kjloopbvp"/></g><g filter="url(#i2rdSAc)"><path stroke="url(#igyo9ic)" class="goq6hdbun"/></g><defs><linearGradient id="ikoviJQ" x1="7.059" x2="24.467" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="akx-0nbzs"/><stop offset="1" class="u_kvj7wdc"/></linearGradient><linearGradient id="iu4R1Ab" x1="5" x2="5.587" y1="27.875" y2="27.875" gradientUnits="userSpaceOnUse"><stop class="hv5k0l-0h"/><stop offset="1" class="wye4olbbu"/></linearGradient><linearGradient id="imFQvVd" x1="16" x2="16" y1="23.531" y2="24.906" gradientUnits="userSpaceOnUse"><stop class="ge9excv0v"/><stop offset="1" class="vaiffr-vt"/></linearGradient><linearGradient id="iXpDxSd" x1="27" x2="26.181" y1="28.413" y2="28.413" gradientUnits="userSpaceOnUse"><stop class="oetw53b6e"/><stop offset="1" class="v-qo369no"/></linearGradient><linearGradient id="iVsUO5b" x1="16" x2="16" y1="15" y2="20.375" gradientUnits="userSpaceOnUse"><stop class="ull5ejh4e"/><stop offset="1" class="nazuqlb1z"/></linearGradient><linearGradient id="iqki5qd" x1="25" x2="24.33" y1="19.809" y2="19.809" gradientUnits="userSpaceOnUse"><stop class="imfkqdkbn"/><stop offset="1" class="yfx8w1hcq"/></linearGradient><linearGradient id="isOk6wd" x1="7" x2="7.676" y1="19.407" y2="19.407" gradientUnits="userSpaceOnUse"><stop class="gimow3ucd"/><stop offset="1" class="jlf0w2caf"/></linearGradient><linearGradient id="i3Pdt6c" x1="16" x2="16" y1="15.694" y2="16.316" gradientUnits="userSpaceOnUse"><stop class="mj5p-rcfs"/><stop offset="1" class="te-9cmy7j"/></linearGradient><linearGradient id="iacwHWh" x1="16" x2="16" y1="7" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="ull5ejh4e"/><stop offset="1" class="nazuqlb1z"/></linearGradient><linearGradient id="iOAadbi" x1="22" x2="21.553" y1="11.809" y2="11.809" gradientUnits="userSpaceOnUse"><stop class="imfkqdkbn"/><stop offset="1" class="yfx8w1hcq"/></linearGradient><linearGradient id="imXgq6d" x1="10" x2="10.536" y1="11.407" y2="11.407" gradientUnits="userSpaceOnUse"><stop class="gimow3ucd"/><stop offset="1" class="jlf0w2caf"/></linearGradient><linearGradient id="i4qXIZv" x1="16" x2="16" y1="7.694" y2="8.316" gradientUnits="userSpaceOnUse"><stop class="mj5p-rcfs"/><stop offset="1" class="te-9cmy7j"/></linearGradient><linearGradient id="ieMdPzc" x1="8.214" x2="24.299" y1="23.633" y2="23.633" gradientUnits="userSpaceOnUse"><stop class="co8079b8k"/><stop offset="1" class="ow32qabmv"/></linearGradient><linearGradient id="i71IVie" x1="9.049" x2="23.41" y1="15.633" y2="15.633" gradientUnits="userSpaceOnUse"><stop class="co8079b8k"/><stop offset="1" class="ow32qabmv"/></linearGradient><linearGradient id="iDs4Hpd" x1="10.995" x2="21.335" y1="7.45" y2="7.45" gradientUnits="userSpaceOnUse"><stop class="co8079b8k"/><stop offset="1" class="ow32qabmv"/></linearGradient><linearGradient id="i1Ejbjb" x1="13" x2="19" y1="28.156" y2="28.215" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="i5REZ4d" x1="7.01" x2="11.01" y1="26.894" y2="26.937" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="i6rdfPe" x1="9.01" x2="9.01" y1="28.131" y2="27.46" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="i1rV1fo" x1="21.01" x2="25.01" y1="26.894" y2="26.937" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="i4AIGMv" x1="23.01" x2="23.01" y1="28.131" y2="27.46" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="iL0Tf8f" x1="9" x2="11" y1="18.262" y2="18.279" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="idtyHHc" x1="10" x2="10" y1="19.088" y2="18.64" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="it8gGvd" x1="15" x2="17" y1="18.262" y2="18.279" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="i6UyoSc" x1="16" x2="16" y1="19.088" y2="18.64" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="iAR008A" x1="21" x2="23" y1="18.262" y2="18.279" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="i8RFGAU" x1="22" x2="22" y1="19.088" y2="18.64" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="inIwi1b" x1="12" x2="14" y1="10.262" y2="10.279" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="iHEUNSd" x1="13" x2="13" y1="11.088" y2="10.64" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="iv3IVnv" x1="18" x2="20" y1="10.262" y2="10.279" gradientUnits="userSpaceOnUse"><stop class="b_x7p8b4q"/><stop offset="1" class="jlm1s-bzn"/></linearGradient><linearGradient id="iDEn1QL" x1="19" x2="19" y1="11.088" y2="10.64" gradientUnits="userSpaceOnUse"><stop class="ngaxfbnxm"/><stop offset="1" class="s-ujr5bmh"/></linearGradient><linearGradient id="iSI9bdd" x1="5.434" x2="2.787" y1="23.032" y2="22.369" gradientUnits="userSpaceOnUse"><stop class="qmaqdmbgt"/><stop offset="1" class="kq5t-2-np"/></linearGradient><linearGradient id="iDLdtvk" x1="6.874" x2="4.227" y1="14.845" y2="14.182" gradientUnits="userSpaceOnUse"><stop class="qmaqdmbgt"/><stop offset="1" class="kq5t-2-np"/></linearGradient><linearGradient id="i8bxwZB" x1="10.218" x2="7.571" y1="6.767" y2="6.104" gradientUnits="userSpaceOnUse"><stop class="qmaqdmbgt"/><stop offset="1" class="kq5t-2-np"/></linearGradient><linearGradient id="imcIHfd" x1="26.803" x2="29.313" y1="23.368" y2="20.83" gradientUnits="userSpaceOnUse"><stop class="nyiln1b3h"/><stop offset="1" class="n-zkz-bpb"/></linearGradient><linearGradient id="iBFQfke" x1="25.347" x2="27.857" y1="15.399" y2="12.861" gradientUnits="userSpaceOnUse"><stop class="nyiln1b3h"/><stop offset="1" class="n-zkz-bpb"/></linearGradient><linearGradient id="igyo9ic" x1="21.791" x2="24.3" y1="7.321" y2="4.783" gradientUnits="userSpaceOnUse"><stop class="nyiln1b3h"/><stop offset="1" class="n-zkz-bpb"/></linearGradient><filter id="ixTl6wb" width="28.8" height="4.8" x="1.6" y="19.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.227451 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.188235 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="idqHMId" width="25.8" height="4.8" x="3.1" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.227451 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.188235 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="iL8jJfX" width="18.8" height="6.8" x="6.6" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.227451 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.188235 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="ihHvbFe" width="6.4" height="5.25" x="12.75" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="i2Xyhfe" width="4.4" height="3.25" x="6.76" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="inPRqje" width="4.4" height="3.25" x="20.76" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="iHx1rCQ" width="2.4" height="2.25" x="8.75" y="17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="i8BOlrc" width="2.4" height="2.25" x="14.75" y="17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="iCFTHne" width="2.4" height="2.25" x="20.75" y="17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="iw2hFGb" width="2.4" height="2.25" x="11.75" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="izCwmge" width="2.4" height="2.25" x="17.75" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.282353 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6793" result="effect2_innerShadow_18_6793"/></filter><filter id="ijDj9zc" width="3.638" height="2.856" x="2.397" y="20.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6793" stdDeviation=".2"/></filter><filter id="iXpARDe" width="3.638" height="2.856" x="3.837" y="12.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6793" stdDeviation=".2"/></filter><filter id="iM4lvEW" width="3.638" height="2.856" x="7.181" y="4.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6793" stdDeviation=".2"/></filter><filter id="iUV1kse" width="3.7" height="2.638" x="26.287" y="20.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6793" stdDeviation=".2"/></filter><filter id="i5n6F0c" width="3.7" height="2.638" x="24.832" y="12.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6793" stdDeviation=".2"/></filter><filter id="i2rdSAc" width="3.7" height="2.638" x="21.275" y="4.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6793" stdDeviation=".2"/></filter><radialGradient id="iYEoaPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.07786 1.3529 -1.74502 1.39027 6.225 20)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cbhnmuz7f"/><stop offset="1" class="eyvyhb1ob"/></radialGradient><radialGradient id="iF6PFqc" cx="0" cy="0" r="1" gradientTransform="matrix(.96238 1.3529 -1.69123 1.20305 7.272 12)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cbhnmuz7f"/><stop offset="1" class="eyvyhb1ob"/></radialGradient><radialGradient id="iiCt6Vb" cx="0" cy="0" r="1" gradientTransform="rotate(123.513 5.031 4.535)scale(4.21661 2.2383)" gradientUnits="userSpaceOnUse"><stop offset=".458" class="cbhnmuz7f"/><stop offset="1" class="eyvyhb1ob"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:japanese-castle" /></template>
<style>
.akx-0nbzs {
  stop-color: var(--svg-color--b9adc0, #B9ADC0);
}

.b_x7p8b4q {
  stop-color: var(--svg-color--4f3b62, #4F3B62);
}

.bin-9zp3w {
  d: path("M13.57 11h-1.14c-.24 0-.43-.19-.43-.43V9.43c0-.24.19-.43.43-.43h1.14c.24 0 .43.19.43.43v1.14a.42.42 0 0 1-.43.43");
}

.cbhnmuz7f {
  stop-color: var(--svg-color--bc5c77, #BC5C77);
}

.cevonje8d {
  d: path("M10.26 28h-2.5c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75h2.5c.41 0 .75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.co8079b8k {
  stop-color: var(--svg-color--ff4294, #FF4294);
}

.em6clacso {
  d: path("M28.5 13.56c0 .28-.14.54-.372.69l-2.009 1.33c-.412.27-.894.42-1.396.42H7.276c-.492 0-.984-.15-1.396-.42l-2.009-1.33a.82.82 0 0 1-.371-.69c0-.49.402-.84.843-.84a.9.9 0 0 1 .463.14a2.535 2.535 0 0 0 3.173-.31c.352-.35.834-.55 1.336-.55h13.38c.501 0 .983.2 1.335.55c.482.48 1.125.73 1.778.73c.482 0 .964-.14 1.396-.42c.15-.1.301-.14.462-.14c.432 0 .834.35.834.84");
}

.eyvyhb1ob {
  stop-color: var(--svg-color--bb5272, #BB5272);
  stop-opacity: 0;
}

.fsztfkb0e {
  d: path("M30 21.56c0 .28-.14.54-.37.69l-2 1.33c-.41.27-.89.42-1.39.42H5.76c-.49 0-.98-.15-1.39-.42l-2-1.33a.82.82 0 0 1-.37-.69c0-.49.4-.84.84-.84c.15 0 .31.05.46.14c.42.28.91.42 1.39.42c.65 0 1.29-.25 1.77-.73c.35-.35.83-.55 1.33-.55h16.43c.5 0 .98.2 1.33.55c.48.48 1.12.73 1.77.73c.48 0 .96-.14 1.39-.42a.8.8 0 0 1 .46-.14c.42 0 .83.35.83.84");
}

.ft5dv1b6b {
  fill: none;
}

.ge9excv0v {
  stop-color: var(--svg-color--7f5e7e, #7F5E7E);
}

.gimow3ucd {
  stop-color: var(--svg-color--83757e, #83757E);
}

.goq6hdbun {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m24.375 5.406l-2.5 1.438");
}

.h2tlpzbae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.781 5.266l2.438 1.656");
}

.hgracsb0w {
  d: path("M19 30h-6v-3.99c0-.56.45-1.01 1.01-1.01h3.98c.56 0 1.01.45 1.01 1.01z");
}

.hv5k0l-0h {
  stop-color: var(--svg-color--857b8b, #857B8B);
}

.hyrkarmdc {
  d: path("M22 7H10v6h12z");
}

.imfkqdkbn {
  stop-color: var(--svg-color--dfd4db, #DFD4DB);
}

.jlf0w2caf {
  stop-color: var(--svg-color--83757e, #83757E);
  stop-opacity: 0;
}

.jlm1s-bzn {
  stop-color: var(--svg-color--3f3446, #3F3446);
}

.k4-3rcp1w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m29.388 21.453l-2.5 1.438");
}

.kjloopbvp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m27.932 13.484l-2.5 1.438");
}

.kq5t-2-np {
  stop-color: var(--svg-color--ff50ae, #FF50AE);
}

.lr5ht2brr {
  d: path("M24.26 28h-2.5c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75h2.5c.41 0 .75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.mj5p-rcfs {
  stop-color: var(--svg-color--915474, #915474);
}

.n-zkz-bpb {
  stop-color: var(--svg-color--ff6474, #FF6474);
}

.nazuqlb1z {
  stop-color: var(--svg-color--bfa8b0, #BFA8B0);
}

.ngaxfbnxm {
  stop-color: var(--svg-color--35253e, #35253E);
}

.nyiln1b3h {
  stop-color: var(--svg-color--ff6474, #FF6474);
  stop-opacity: 0;
}

.oetw53b6e {
  stop-color: var(--svg-color--ded6e0, #DED6E0);
}

.ow32qabmv {
  stop-color: var(--svg-color--ff2f5e, #FF2F5E);
}

.pgjh8db0y {
  d: path("M25 15H7v6h18z");
}

.q6kd1acht {
  d: path("M27 22H5v8h22z");
}

.qmaqdmbgt {
  stop-color: var(--svg-color--ff50ae, #FF50AE);
  stop-opacity: 0;
}

.rhg321euv {
  d: path("M19.57 11h-1.14c-.24 0-.43-.19-.43-.43V9.43c0-.24.19-.43.43-.43h1.14c.24 0 .43.19.43.43v1.14a.42.42 0 0 1-.43.43");
}

.s-ujr5bmh {
  stop-color: var(--svg-color--35253e, #35253E);
  stop-opacity: 0;
}

.si6np4b5k {
  d: path("M16.57 19h-1.14c-.24 0-.43-.19-.43-.43v-1.14c0-.24.19-.43.43-.43h1.14c.24 0 .43.19.43.43v1.14a.42.42 0 0 1-.43.43");
}

.t_x8embww {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M4.437 13.344L6.875 15");
}

.tajk8nbbd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m2.997 21.531l2.437 1.657");
}

.te-9cmy7j {
  stop-color: var(--svg-color--915474, #915474);
  stop-opacity: 0;
}

.u_kvj7wdc {
  stop-color: var(--svg-color--c1b6c8, #C1B6C8);
}

.ull5ejh4e {
  stop-color: var(--svg-color--aa93a7, #AA93A7);
}

.v-qo369no {
  stop-color: var(--svg-color--ded6e0, #DED6E0);
  stop-opacity: 0;
}

.vaiffr-vt {
  stop-color: var(--svg-color--7f5e7e, #7F5E7E);
  stop-opacity: 0;
}

.vqfay7w9y {
  d: path("M10.57 19H9.43c-.24 0-.43-.19-.43-.43v-1.14c0-.24.19-.43.43-.43h1.14c.24 0 .43.19.43.43v1.14a.42.42 0 0 1-.43.43");
}

.wye4olbbu {
  stop-color: var(--svg-color--857b8b, #857B8B);
  stop-opacity: 0;
}

.xh50n7bui {
  d: path("M25 5.55c0 .28-.141.54-.372.69l-2.033 1.34c-.412.27-.895.42-1.378.42H10.793a2.6 2.6 0 0 1-1.409-.42L7.372 6.24A.82.82 0 0 1 7 5.55c0-.49.402-.83.845-.83c.15 0 .312.04.453.14c.432.28.915.42 1.398.42c.866 0 1.72-.44 2.204-1.28l.815-1.43c.2-.35.573-.57.986-.57h4.678c.423 0 .815.24 1.006.61L20.1 4a2.53 2.53 0 0 0 2.203 1.28c.483 0 .966-.14 1.399-.42c.14-.1.302-.14.463-.14a.83.83 0 0 1 .835.83");
}

.yfx8w1hcq {
  stop-color: var(--svg-color--dfd4db, #DFD4DB);
  stop-opacity: 0;
}

.zxybgi6sg {
  d: path("M22.57 19h-1.14c-.24 0-.43-.19-.43-.43v-1.14c0-.24.19-.43.43-.43h1.14c.24 0 .43.19.43.43v1.14a.42.42 0 0 1-.43.43");
}

</style>
