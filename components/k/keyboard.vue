<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAxNSGc)"><rect fill="url(#iKLANYj)" class="fcwlqz1-h"/></g><g filter="url(#ih9q89W)"><path class="eh8bbmb-n"/></g><path fill="url(#iMezuKe)" class="ufvdc7dgr"/><path fill="url(#iKqHNCe)" class="ufvdc7dgr"/><g filter="url(#itofA3b)"><rect class="oxho15bph"/></g><g filter="url(#iyyH5Sd)"><rect class="nu_8jvbid"/></g><g filter="url(#iXOZjmd)"><rect class="rsy8r1bgp"/></g><g filter="url(#i65UFkd)"><rect class="wntmqdbpy"/></g><g filter="url(#iTQ1F0g)"><rect class="mqgicqfgr"/></g><g filter="url(#ic9ORec)"><rect class="qriqdy4pb"/></g><g filter="url(#ieQB7se)"><rect class="bgwj8sbia"/></g><g filter="url(#iy8Rj0b)"><rect class="xe90vcbsi"/></g><g filter="url(#itVAtQd)"><rect class="ii8io3hum"/></g><g filter="url(#ib4smnc)"><rect class="p-j7f5b5a"/></g><g filter="url(#iu5Icic)"><rect class="dfvomyf1u"/></g><g filter="url(#iFtCCJd)"><rect class="t_wb-7c-h"/></g><g filter="url(#iGveLPl)"><rect class="b9jj98jca"/></g><g filter="url(#iUsKM4c)"><rect class="z826-ebzp"/></g><g filter="url(#ieW5Xpc)"><rect class="oe2wmzbhj"/></g><g filter="url(#iO9BSOX)"><rect class="x96hurxov"/></g><g filter="url(#iWIjg3b)"><rect class="j4rpwcivr"/></g><g filter="url(#iNL05Kd)"><rect class="jrihqacnn"/></g><g filter="url(#iNroFMc)"><rect class="ftaxck29i"/></g><g filter="url(#igCMyLp)"><rect class="oop3v7bzy"/></g><g filter="url(#i55yUGb)"><rect class="o_8qg1btv"/></g><g filter="url(#iiQMt3c)"><rect class="yd3ah-ykm"/></g><g filter="url(#iH9RInc)"><rect class="wz45x4boi"/></g><g filter="url(#iTAr2Cc)"><rect class="rta478b5g"/></g><g filter="url(#idyUSze)"><rect class="dfez-r69w"/></g><defs><filter id="iAxNSGc" width="28.169" height="17.356" x="1.941" y="10.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.960784 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.8 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19642" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.686275 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="ih9q89W" width="27.719" height="4.469" x="2.141" y="25.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.576471 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19642"/></filter><filter id="itofA3b" width="3.313" height="2.488" x="3.287" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iyyH5Sd" width="3.313" height="3.215" x="3.287" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iXOZjmd" width="3.313" height="3.215" x="6.375" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="i65UFkd" width="3.313" height="3.215" x="9.462" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iTQ1F0g" width="3.313" height="3.215" x="12.55" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="ic9ORec" width="3.313" height="3.215" x="15.638" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="ieQB7se" width="3.313" height="3.215" x="18.725" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iy8Rj0b" width="3.313" height="3.215" x="21.813" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="itVAtQd" width="3.313" height="3.215" x="24.9" y="17.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="ib4smnc" width="3.313" height="3.215" x="4.82" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iu5Icic" width="3.313" height="3.215" x="7.908" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iFtCCJd" width="3.313" height="3.215" x="10.995" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iGveLPl" width="3.313" height="3.215" x="14.083" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iUsKM4c" width="3.313" height="3.215" x="17.171" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="ieW5Xpc" width="3.313" height="3.215" x="20.258" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iO9BSOX" width="3.313" height="3.215" x="23.346" y="19.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iWIjg3b" width="3.313" height="3.215" x="6.281" y="22.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iNL05Kd" width="12.317" height="3.215" x="9.587" y="22.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iNroFMc" width="3.313" height="3.215" x="21.914" y="22.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="igCMyLp" width="3.313" height="2.488" x="9.455" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="i55yUGb" width="3.313" height="2.488" x="12.541" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iiQMt3c" width="3.313" height="2.488" x="15.627" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iH9RInc" width="3.313" height="2.488" x="18.713" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="iTAr2Cc" width="3.313" height="2.488" x="21.799" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><filter id="idyUSze" width="3.313" height="2.488" x="24.885" y="13.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.721569 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19642"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19642" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.694118 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19642"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.517647 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19642" result="effect3_innerShadow_18_19642"/></filter><linearGradient id="iKLANYj" x1="16" x2="16" y1="11.047" y2="27.953" gradientUnits="userSpaceOnUse"><stop class="d0j164baw"/><stop offset="1" class="lygh4tkkk"/></linearGradient><linearGradient id="iMezuKe" x1="2.516" x2="4.828" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="sly-hname"/><stop offset="1" class="mcr7y1b_c"/></linearGradient><linearGradient id="iKqHNCe" x1="29.484" x2="27.453" y1="27.531" y2="27.531" gradientUnits="userSpaceOnUse"><stop class="e8wnkk36h"/><stop offset="1" class="vggy9bc7o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keyboard" /></template>
<style>
.b9jj98jca {
  width: 2.313px;
  height: 2.215px;
  x: 14.833px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.bgwj8sbia {
  width: 2.313px;
  height: 2.215px;
  x: 19.475px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.d0j164baw {
  stop-color: var(--svg-color--dad5e0, #DAD5E0);
}

.dfez-r69w {
  width: 2.313px;
  height: 1.488px;
  x: 25.635px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.dfvomyf1u {
  width: 2.313px;
  height: 2.215px;
  x: 8.658px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.e8wnkk36h {
  stop-color: var(--svg-color--cdc9d2, #CDC9D2);
}

.eh8bbmb-n {
  fill: var(--svg-color--98a, #98A);
  d: path("M2.14 25.453v1.969a2.5 2.5 0 0 0 2.5 2.5h22.72a2.5 2.5 0 0 0 2.5-2.5v-1.969a2.5 2.5 0 0 1-2.5 2.5H4.64a2.5 2.5 0 0 1-2.5-2.5");
}

.fcwlqz1-h {
  width: 27.719px;
  height: 16.906px;
  x: 2.141px;
  y: 11.047px;
  rx: 2.5px;
}

.ft5dv1b6b {
  fill: none;
}

.ftaxck29i {
  width: 2.313px;
  height: 2.215px;
  x: 22.664px;
  y: 23.145px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.ii8io3hum {
  width: 2.313px;
  height: 2.215px;
  x: 25.65px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.j4rpwcivr {
  width: 2.313px;
  height: 2.215px;
  x: 7.031px;
  y: 23.145px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.jrihqacnn {
  width: 11.317px;
  height: 2.215px;
  x: 10.337px;
  y: 23.145px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.lygh4tkkk {
  stop-color: var(--svg-color--d7d0df, #D7D0DF);
}

.mcr7y1b_c {
  stop-color: var(--svg-color--afaab5, #AFAAB5);
  stop-opacity: 0;
}

.mqgicqfgr {
  width: 2.313px;
  height: 2.215px;
  x: 13.3px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.nu_8jvbid {
  width: 2.313px;
  height: 2.215px;
  x: 4.037px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.o_8qg1btv {
  width: 2.313px;
  height: 1.488px;
  x: 13.291px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.oe2wmzbhj {
  width: 2.313px;
  height: 2.215px;
  x: 21.008px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.oop3v7bzy {
  width: 2.313px;
  height: 1.488px;
  x: 10.205px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.oxho15bph {
  width: 2.313px;
  height: 1.488px;
  x: 4.037px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.p-j7f5b5a {
  width: 2.313px;
  height: 2.215px;
  x: 5.57px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.qriqdy4pb {
  width: 2.313px;
  height: 2.215px;
  x: 16.388px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.rsy8r1bgp {
  width: 2.313px;
  height: 2.215px;
  x: 7.125px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.rta478b5g {
  width: 2.313px;
  height: 1.488px;
  x: 22.549px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.sly-hname {
  stop-color: var(--svg-color--afaab5, #AFAAB5);
}

.t_wb-7c-h {
  width: 2.313px;
  height: 2.215px;
  x: 11.745px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.ufvdc7dgr {
  d: path("M2.14 25.453v1.969a2.5 2.5 0 0 0 2.5 2.5h22.72a2.5 2.5 0 0 0 2.5-2.5v-1.969a2.5 2.5 0 0 1-2.5 2.5H4.64a2.5 2.5 0 0 1-2.5-2.5");
}

.vggy9bc7o {
  stop-color: var(--svg-color--9f92ad, #9F92AD);
  stop-opacity: 0;
}

.wntmqdbpy {
  width: 2.313px;
  height: 2.215px;
  x: 10.212px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.wz45x4boi {
  width: 2.313px;
  height: 1.488px;
  x: 19.463px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.x96hurxov {
  width: 2.313px;
  height: 2.215px;
  x: 24.096px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.xe90vcbsi {
  width: 2.313px;
  height: 2.215px;
  x: 22.563px;
  y: 17.355px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.yd3ah-ykm {
  width: 2.313px;
  height: 1.488px;
  x: 16.377px;
  y: 13.641px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

.z826-ebzp {
  width: 2.313px;
  height: 2.215px;
  x: 17.921px;
  y: 20.23px;
  fill: var(--svg-color--9d9aa2, #9D9AA2);
  rx: 0.4px;
}

</style>
