<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ith1qbcjo"/><path fill="url(#iyzKlIc)" class="bgsz9sl-r"/><path fill="url(#iF6GoGd)" class="bgsz9sl-r"/><path fill="url(#ihzTKyc)" class="bgsz9sl-r"/><path fill="url(#inA4uyb)" class="jvejd4a1e"/><path fill="url(#i9ZSDvp)" class="jvejd4a1e"/><path fill="url(#ihEGhKd)" class="jvejd4a1e"/><path fill="url(#iMBkXxc)" class="jvejd4a1e"/><path fill="url(#izWBkFd)" class="jvejd4a1e"/><path fill="url(#iEFUxVb)" class="eeufawbbr"/><path fill="url(#iruGDHc)" class="eeufawbbr"/><path fill="url(#iklpqJb)" class="eeufawbbr"/><g filter="url(#iHNJqac)"><path fill="url(#iVgT6Cf)" class="nm2wmkbsb"/><path fill="url(#iK4p1oc)" class="nm2wmkbsb"/></g><g filter="url(#ieblQEe)"><path fill="url(#irp6zUc)" class="aj5ijqtna"/><path fill="url(#iu1bs8d)" class="aj5ijqtna"/></g><g filter="url(#ipgspGd)"><path fill="url(#imQbyec)" class="vtv60fbyw"/><path fill="url(#ifShBvb)" class="vtv60fbyw"/></g><g filter="url(#iOCbUYc)"><path fill="url(#igL2bBj)" class="nzgq4jbpy"/><path fill="url(#iyDLj3b)" class="nzgq4jbpy"/></g><g filter="url(#ioiyF9d)"><path class="zgn9fqbsy"/></g><g filter="url(#ipyh9kg)"><path fill="url(#iEpWr6X)" class="hp0ctlbgf"/></g><path fill="url(#ij0W6Mb)" class="c0k1a-8eh"/><path fill="url(#iOYreae)" class="c0k1a-8eh"/><path fill="url(#igLeGbd)" class="c0k1a-8eh"/><path fill="url(#iTtieAe)" class="c0k1a-8eh"/><path fill="url(#id1Xmub)" class="c0k1a-8eh"/><g filter="url(#iYjmetd)"><path fill="url(#i9XyNHb)" class="hlo1cfbkh"/></g><g filter="url(#i22SoQs)"><rect fill="url(#i7diXid)" class="b013aeboa"/></g><g filter="url(#iUcnMnb)"><rect fill="url(#i3x72Vd)" class="mph8x45fy"/></g><g filter="url(#iPE8Q3l)"><path class="rw9bocjez"/></g><g filter="url(#ik49Lrn)"><path class="bxe92dbwa"/></g><g filter="url(#ip7ngeb)"><path fill="url(#ifBnb6c)" class="v0k5n9g9d"/></g><g filter="url(#ifacsfV)"><path fill="url(#iBtr28p)" class="q8pubuukg"/><path fill="url(#igtB78Z)" class="q8pubuukg"/><path fill="url(#iPUBRhc)" class="q8pubuukg"/><path fill="url(#iXxewRd)" class="q8pubuukg"/></g><g filter="url(#iDxQLXE)"><path class="d9e7fbbcb"/></g><g filter="url(#iqUUTld)"><path class="j7dxbdcrr"/></g><g filter="url(#iKQwNlb)"><path fill="url(#iwdTnte)" class="yr3wtcbsb"/><path fill="url(#iwuNOWc)" class="yr3wtcbsb"/></g><g filter="url(#ifEsqpc)"><path class="k3angwbef"/></g><g filter="url(#iHhAlEi)"><path class="qo_cl0bmu"/></g><g filter="url(#iYZpbpy)"><path stroke="url(#ijrlVoV)" class="q477bm37i"/></g><g filter="url(#iyg88Cc)"><path stroke="url(#iM4zKPC)" class="z0j4-it_z"/></g><g filter="url(#iAIrUab)"><path stroke="url(#i22c0xb)" class="rwk5yz6vz"/></g><defs><linearGradient id="iyzKlIc" x1="11.522" x2="7.122" y1="21.235" y2="21.235" gradientUnits="userSpaceOnUse"><stop class="jsja1_b4l"/><stop offset="1" class="e6fh96x5x"/></linearGradient><linearGradient id="iF6GoGd" x1="7.122" x2="7.122" y1="11.334" y2="13.873" gradientUnits="userSpaceOnUse"><stop class="jsja1_b4l"/><stop offset="1" class="e6fh96x5x"/></linearGradient><linearGradient id="ihzTKyc" x1="2.883" x2="4.013" y1="20.996" y2="20.996" gradientUnits="userSpaceOnUse"><stop class="xo-26j82a"/><stop offset="1" class="r38yor7pq"/></linearGradient><linearGradient id="inA4uyb" x1="22.442" x2="22.442" y1="9.83" y2="22.394" gradientUnits="userSpaceOnUse"><stop class="ut--nabfr"/><stop offset="1" class="nswcn3bvc"/></linearGradient><linearGradient id="i9ZSDvp" x1="28.883" x2="26.599" y1="19.785" y2="19.785" gradientUnits="userSpaceOnUse"><stop class="v87kpx-pj"/><stop offset="1" class="yihajpbrc"/></linearGradient><linearGradient id="ihEGhKd" x1="29.255" x2="28.559" y1="20.311" y2="20.311" gradientUnits="userSpaceOnUse"><stop class="h95fdl38x"/><stop offset="1" class="o3doe2i5s"/></linearGradient><linearGradient id="iEFUxVb" x1="15.838" x2="15.838" y1="11.247" y2="29.74" gradientUnits="userSpaceOnUse"><stop class="v26eh-bfe"/><stop offset="1" class="qditvp6kr"/></linearGradient><linearGradient id="iruGDHc" x1="10.272" x2="13.534" y1="24.896" y2="24.896" gradientUnits="userSpaceOnUse"><stop class="ovjtfkb8v"/><stop offset="1" class="w46qowkvj"/></linearGradient><linearGradient id="iklpqJb" x1="21.741" x2="19.13" y1="18.337" y2="18.337" gradientUnits="userSpaceOnUse"><stop class="zc2rh-bte"/><stop offset="1" class="m4g3qib9j"/></linearGradient><linearGradient id="iVgT6Cf" x1="5.072" x2="7.57" y1="17.75" y2="13.744" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iK4p1oc" x1="4.914" x2="5.731" y1="15.75" y2="15.75" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="irp6zUc" x1="5.072" x2="7.57" y1="24.75" y2="20.744" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iu1bs8d" x1="4.914" x2="5.731" y1="22.75" y2="22.75" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="imQbyec" x1="24.072" x2="26.57" y1="17.75" y2="13.744" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="ifShBvb" x1="23.914" x2="24.731" y1="15.75" y2="15.75" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="igL2bBj" x1="24.072" x2="26.57" y1="24.75" y2="20.744" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iyDLj3b" x1="23.914" x2="24.731" y1="22.75" y2="22.75" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iEpWr6X" x1="14.422" x2="17.555" y1="14.25" y2="14.25" gradientUnits="userSpaceOnUse"><stop class="w-fr9sbjq"/><stop offset="1" class="v07uuzr1n"/></linearGradient><linearGradient id="ij0W6Mb" x1="15.914" x2="15.914" y1="21.527" y2="30.161" gradientUnits="userSpaceOnUse"><stop class="ifxssk_kk"/><stop offset="1" class="xy-6xyb3t"/></linearGradient><linearGradient id="iOYreae" x1="11.461" x2="12.126" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="kgqsyxyqs"/><stop offset="1" class="uo-mvdbrb"/></linearGradient><linearGradient id="i9XyNHb" x1="15.914" x2="15.914" y1="21.543" y2="22.589" gradientUnits="userSpaceOnUse"><stop class="q6_o4gb6z"/><stop offset="1" class="fhvmp0b0u"/></linearGradient><linearGradient id="i7diXid" x1="13.912" x2="13.912" y1="20.875" y2="28.339" gradientUnits="userSpaceOnUse"><stop class="xz_7ousyx"/><stop offset="1" class="duocvfbtx"/></linearGradient><linearGradient id="i3x72Vd" x1="17.914" x2="17.914" y1="20.875" y2="28.339" gradientUnits="userSpaceOnUse"><stop class="xz_7ousyx"/><stop offset="1" class="duocvfbtx"/></linearGradient><linearGradient id="ifBnb6c" x1="15.904" x2="15.904" y1="17.77" y2="21.73" gradientUnits="userSpaceOnUse"><stop class="b63ui5jbj"/><stop offset="1" class="zvubohbgf"/></linearGradient><linearGradient id="iBtr28p" x1="15.914" x2="15.914" y1="5.75" y2="10.47" gradientUnits="userSpaceOnUse"><stop class="u56xkml5d"/><stop offset="1" class="ku_3hrg3y"/></linearGradient><linearGradient id="ijrlVoV" x1="14.852" x2="16.852" y1="14.156" y2="14.156" gradientUnits="userSpaceOnUse"><stop class="qa61gc0vj"/><stop offset="1" class="qta8mu4fc"/></linearGradient><filter id="iHNJqac" width="3.25" height="4.25" x="4.664" y="13.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/></filter><filter id="ieblQEe" width="3.25" height="4.25" x="4.664" y="20.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/></filter><filter id="ipgspGd" width="3.25" height="4.25" x="23.664" y="13.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/></filter><filter id="iOCbUYc" width="3.25" height="4.25" x="23.664" y="20.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/></filter><filter id="ioiyF9d" width="5" height="5.904" x="13.176" y="11.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".25"/></filter><filter id="ipyh9kg" width="4.25" height="5.25" x="13.914" y="11.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.0784314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.0745098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6492" result="effect2_innerShadow_18_6492"/></filter><filter id="iYjmetd" width="9.488" height="3.032" x="11.17" y="19.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".25"/></filter><filter id="i22SoQs" width="3.486" height="8.589" x="12.119" y="19.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.466667 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.682353 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6492" result="effect2_innerShadow_18_6492"/></filter><filter id="iUcnMnb" width="3.486" height="8.589" x="16.121" y="19.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.466667 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.682353 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6492" result="effect2_innerShadow_18_6492"/></filter><filter id="iPE8Q3l" width="3.735" height="2.861" x="16.046" y="19.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".25"/></filter><filter id="ik49Lrn" width="3.735" height="2.861" x="12.044" y="19.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".25"/></filter><filter id="ip7ngeb" width="11.25" height="4.31" x="10.404" y="17.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.172549 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.172549 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6492" result="effect2_innerShadow_18_6492"/></filter><filter id="ifacsfV" width="7.55" height="6" x="12.114" y="5.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.376471 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_6492"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_6492" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8" dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.137255 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_6492"/></filter><filter id="iDxQLXE" width="13.407" height="10.561" x="9.13" y="1.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".5"/></filter><filter id="iqUUTld" width="13.038" height="9.754" x="9.314" y="1.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".3"/></filter><filter id="iKQwNlb" width="28.484" height="10.853" x="1.846" y="1.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.141176 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6492"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.2 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6492" result="effect2_innerShadow_18_6492"/></filter><filter id="ifEsqpc" width=".95" height="4.434" x="16.986" y="12.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".175"/></filter><filter id="iHhAlEi" width=".95" height="4.434" x="14.018" y="12.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".175"/></filter><filter id="iYZpbpy" width="3.763" height=".95" x="14.002" y="13.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".175"/></filter><filter id="iyg88Cc" width="4.781" height="3.484" x="16.461" y="17.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".125"/></filter><filter id="iAIrUab" width="12.019" height="8.421" x="11.47" y="1.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6492" stdDeviation=".4"/></filter><radialGradient id="iMBkXxc" cx="0" cy="0" r="1" gradientTransform="rotate(147.475 10.31 8.519)scale(10.5778 5.06583)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="l4bdnpbww"/><stop offset="1" class="x1axjxb3y"/></radialGradient><radialGradient id="izWBkFd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 1.06248 -.35963 -.90967 28.883 11.14)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="ysxrizoyy"/><stop offset=".988" class="w_nj4ibxp"/></radialGradient><radialGradient id="igLeGbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.08613 2.31453 -2.13575 1.00223 11.46 21.078)" gradientUnits="userSpaceOnUse"><stop class="u-y2_jbxf"/><stop offset="1" class="b-557ccbk"/></radialGradient><radialGradient id="iTtieAe" cx="0" cy="0" r="1" gradientTransform="matrix(.3355 .55609 -1.01992 .61533 20.032 21.334)" gradientUnits="userSpaceOnUse"><stop class="u-y2_jbxf"/><stop offset="1" class="b-557ccbk"/></radialGradient><radialGradient id="id1Xmub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.42451 .81983 0 20.367 30.517)" gradientUnits="userSpaceOnUse"><stop class="i1ao2kbxl"/><stop offset="1" class="o54m2cczc"/></radialGradient><radialGradient id="igtB78Z" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -1.15625 .69496 .39444 16.352 6.031)" gradientUnits="userSpaceOnUse"><stop class="ogcvnibsz"/><stop offset="1" class="d032wwa1g"/></radialGradient><radialGradient id="iPUBRhc" cx="0" cy="0" r="1" gradientTransform="rotate(138.957 8.229 6.821)scale(2.2368 3.01638)" gradientUnits="userSpaceOnUse"><stop class="d_fo324un"/><stop offset="1" class="go_bdo91j"/></radialGradient><radialGradient id="iXxewRd" cx="0" cy="0" r="1" gradientTransform="rotate(142.765 6.317 5.973)scale(.98127 1.32327)" gradientUnits="userSpaceOnUse"><stop class="d_fo324un"/><stop offset="1" class="go_bdo91j"/></radialGradient><radialGradient id="iwdTnte" cx="0" cy="0" r="1" gradientTransform="rotate(105.556 8.327 8.19)scale(9.74117 27.3883)" gradientUnits="userSpaceOnUse"><stop class="c6d85ebjg"/><stop offset="1" class="s6hbfob1p"/></radialGradient><radialGradient id="iwuNOWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.51088 1.23545 -3.08266 -6.26506 29.83 9.072)" gradientUnits="userSpaceOnUse"><stop class="mpa84ccmv"/><stop offset="1" class="w30a7_b9p"/></radialGradient><radialGradient id="iM4zKPC" cx="0" cy="0" r="1" gradientTransform="rotate(117.613 3.874 15.318)scale(1.14618 2.86949)" gradientUnits="userSpaceOnUse"><stop class="prcwqgblh"/><stop offset="1" class="gl8aqmupb"/></radialGradient><radialGradient id="i22c0xb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.08865 2.73568 -4.42002 -4.9903 20.657 3.38)" gradientUnits="userSpaceOnUse"><stop class="kms0glbgc"/><stop offset="1" class="k27ftkbzr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:love-hotel" /></template>
<style>
.aclvogb1n {
  stop-color: var(--svg-color--5adfff, #5ADFFF);
  stop-opacity: 0;
}

.aj5ijqtna {
  d: path("M7.304 24.75h-1.78c-.34 0-.61-.27-.61-.61v-1.89c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v1.89c0 .33-.27.61-.61.61");
}

.b-557ccbk {
  stop-color: var(--svg-color--a85540, #A85540);
  stop-opacity: 0;
}

.b013aeboa {
  width: 2.986px;
  height: 8.589px;
  x: 12.419px;
  y: 19.75px;
  rx: 0.4px;
}

.b63ui5jbj {
  stop-color: var(--svg-color--e33981, #E33981);
}

.bgsz9sl-r {
  d: path("M15.405 9.83H2.883v19.91h12.522z");
}

.bxe92dbwa {
  fill: var(--svg-color--275fb2, #275FB2);
  d: path("M12.544 22.043V20.18h2.735v1.836a.5.5 0 0 1-.186-.124a.2.2 0 0 0-.141-.068a.2.2 0 0 0-.142.068a.46.46 0 0 1-.677 0a.2.2 0 0 0-.141-.068a.2.2 0 0 0-.142.068a.46.46 0 0 1-.677 0a.2.2 0 0 0-.142-.068a.2.2 0 0 0-.141.068a.46.46 0 0 1-.339.15z");
}

.c0k1a-8eh {
  d: path("M11.461 20.344h8.906v9.396h-8.906z");
}

.c6d85ebjg {
  stop-color: var(--svg-color--db377f, #DB377F);
}

.d_fo324un {
  stop-color: var(--svg-color--ff4d84, #FF4D84);
}

.d032wwa1g {
  stop-color: var(--svg-color--bc2e4f, #BC2E4F);
  stop-opacity: 0;
}

.d9e7fbbcb {
  fill: var(--svg-color--b24340, #B24340);
  d: path("M15.758 4.257h.16c2.824 0 5.114 2.152 5.114 4.807v1.4c0 .354.202.663.505.831V8.17c0-3-2.552-5.43-5.704-5.43S10.13 5.17 10.13 8.17v3.13a.96.96 0 0 0 .515-.836v-1.4c0-2.655 2.289-4.807 5.113-4.807");
}

.duocvfbtx {
  stop-color: var(--svg-color--36a1fe, #36A1FE);
}

.e6fh96x5x {
  stop-color: var(--svg-color--c15953, #C15953);
  stop-opacity: 0;
}

.eeufawbbr {
  d: path("M21.404 29.74H10.272V8.37c0-3.11 2.488-5.63 5.561-5.63s5.561 2.52 5.561 5.63v21.37z");
}

.fhvmp0b0u {
  stop-color: var(--svg-color--a43d3b, #A43D3B);
  stop-opacity: 0;
}

.fk6fa6byv {
  stop-color: var(--svg-color--3892e6, #3892E6);
}

.ft5dv1b6b {
  fill: none;
}

.g12vzib_v {
  stop-color: var(--svg-color--47caff, #47CAFF);
}

.gl8aqmupb {
  stop-color: var(--svg-color--f33c7f, #F33C7F);
  stop-opacity: 0;
}

.go_bdo91j {
  stop-color: var(--svg-color--ff4d84, #FF4D84);
  stop-opacity: 0;
}

.h95fdl38x {
  stop-color: var(--svg-color--ffae98, #FFAE98);
}

.hlo1cfbkh {
  d: path("M20.158 22.065v-1.78l-.024-.025h-8.436l-.028.028v1.77a.2.2 0 0 1 .041-.004c.06 0 .114.031.155.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .113.031.154.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .114.031.154.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .114.031.155.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .113.031.154.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .114.031.154.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .114.031.154.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075c.06 0 .114.031.155.075a.5.5 0 0 0 .74 0a.22.22 0 0 1 .154-.075q.03 0 .06.01");
}

.hp0ctlbgf {
  d: path("M17.425 11.75h-.02a.49.49 0 0 0-.489.49v1.51h-2.005v-1.51a.49.49 0 0 0-.488-.49h-.02a.49.49 0 0 0-.489.49v4.02c0 .27.22.49.489.49h.02a.49.49 0 0 0 .489-.49v-1.5h2.004v1.5c0 .27.22.49.49.49h.019a.49.49 0 0 0 .489-.49v-4.02a.48.48 0 0 0-.489-.49");
}

.i1ao2kbxl {
  stop-color: var(--svg-color--fff1c0, #FFF1C0);
}

.ifxssk_kk {
  stop-color: var(--svg-color--db946d, #DB946D);
}

.ith1qbcjo {
  fill: var(--svg-color--f8a18d, #F8A18D);
  d: path("M15.405 9.83H2.883v19.91h12.522z");
}

.j7dxbdcrr {
  fill: var(--svg-color--741019, #741019);
  d: path("M15.755 3.673h.167c2.93 0 5.306 2.232 5.306 4.985v1.452c0 .367.21.688.524.862V8.054c0-3.112-2.648-5.63-5.919-5.63s-5.919 2.518-5.919 5.63v2.923a.99.99 0 0 0 .535-.867V8.658c0-2.753 2.376-4.985 5.306-4.985");
}

.jsja1_b4l {
  stop-color: var(--svg-color--c15953, #C15953);
}

.jvejd4a1e {
  d: path("M28.883 9.83H16v19.91h12.883z");
}

.k27ftkbzr {
  stop-color: var(--svg-color--ff4c76, #FF4C76);
  stop-opacity: 0;
}

.k3angwbef {
  stroke: var(--svg-color--ec4287, #EC4287);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.461 12.516V16");
}

.kgqsyxyqs {
  stop-color: var(--svg-color--a57364, #A57364);
}

.kms0glbgc {
  stop-color: var(--svg-color--ed4383, #ED4383);
}

.ku_3hrg3y {
  stop-color: var(--svg-color--e41d4a, #E41D4A);
}

.l4bdnpbww {
  stop-color: var(--svg-color--c25251, #C25251);
}

.m4g3qib9j {
  stop-color: var(--svg-color--ffcfaa, #FFCFAA);
  stop-opacity: 0;
}

.mpa84ccmv {
  stop-color: var(--svg-color--ff5371, #FF5371);
}

.mph8x45fy {
  width: 2.986px;
  height: 8.589px;
  x: 16.421px;
  y: 19.75px;
  rx: 0.4px;
}

.ngob4nbyz {
  stop-color: var(--svg-color--5adfff, #5ADFFF);
}

.nm2wmkbsb {
  d: path("M7.304 17.75h-1.78c-.34 0-.61-.27-.61-.61v-1.89c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v1.89c0 .33-.27.61-.61.61");
}

.nswcn3bvc {
  stop-color: var(--svg-color--ffb39c, #FFB39C);
}

.nzgq4jbpy {
  d: path("M26.304 24.75h-1.78c-.34 0-.61-.27-.61-.61v-1.89c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v1.89c0 .33-.27.61-.61.61");
}

.o3doe2i5s {
  stop-color: var(--svg-color--ffae98, #FFAE98);
  stop-opacity: 0;
}

.o54m2cczc {
  stop-color: var(--svg-color--fff1c0, #FFF1C0);
  stop-opacity: 0;
}

.ogcvnibsz {
  stop-color: var(--svg-color--bc2e4f, #BC2E4F);
}

.ovjtfkb8v {
  stop-color: var(--svg-color--cd897b, #CD897B);
}

.prcwqgblh {
  stop-color: var(--svg-color--f33c7f, #F33C7F);
}

.q477bm37i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.477 14.156h2.813");
}

.q6_o4gb6z {
  stop-color: var(--svg-color--a43d3b, #A43D3B);
}

.q8pubuukg {
  d: path("M18.914 7.243v.03c0 .471-.141.912-.394 1.273a8.4 8.4 0 0 1-2.293 2.124a.56.56 0 0 1-.313.08a.66.66 0 0 1-.313-.08a8.9 8.9 0 0 1-2.293-2.124a2.2 2.2 0 0 1-.394-1.273v-.03c.01-.832.697-1.493 1.546-1.493c.12 0 .252.02.363.05c.424.08.788.35.99.712c.03.04.06.06.101.06c.04 0 .08-.02.101-.06c.202-.361.566-.632.99-.712c.111-.03.242-.05.364-.05c.858 0 1.545.661 1.545 1.493");
}

.qa61gc0vj {
  stop-color: var(--svg-color--f83b5d, #F83B5D);
}

.qditvp6kr {
  stop-color: var(--svg-color--ffd2ae, #FFD2AE);
}

.qo_cl0bmu {
  stroke: var(--svg-color--f83b5d, #F83B5D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.493 12.516V16");
}

.qta8mu4fc {
  stop-color: var(--svg-color--f83b5d, #F83B5D);
  stop-opacity: 0;
}

.r38yor7pq {
  stop-color: var(--svg-color--be8a79, #BE8A79);
  stop-opacity: 0;
}

.rw9bocjez {
  fill: var(--svg-color--275fb2, #275FB2);
  d: path("M16.546 22.043V20.18h2.736v1.836a.5.5 0 0 1-.186-.124a.2.2 0 0 0-.142-.068a.2.2 0 0 0-.141.068a.46.46 0 0 1-.678 0a.2.2 0 0 0-.141-.068a.2.2 0 0 0-.142.068a.46.46 0 0 1-.677 0a.2.2 0 0 0-.142-.068a.2.2 0 0 0-.14.068a.46.46 0 0 1-.34.15z");
}

.rwk5yz6vz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M12.67 3.469c.736-.47 2.758-1.185 5.008-.464c2.89.927 4.479 3.067 4.611 5.715");
}

.s6hbfob1p {
  stop-color: var(--svg-color--ee3455, #EE3455);
}

.u-y2_jbxf {
  stop-color: var(--svg-color--a85540, #A85540);
}

.u56xkml5d {
  stop-color: var(--svg-color--e93178, #E93178);
}

.uo-mvdbrb {
  stop-color: var(--svg-color--a57364, #A57364);
  stop-opacity: 0;
}

.ut--nabfr {
  stop-color: var(--svg-color--fd937f, #FD937F);
}

.v07uuzr1n {
  stop-color: var(--svg-color--da3178, #DA3178);
}

.v0k5n9g9d {
  d: path("M21.354 20.94c-.01-.02 0-.03-.01-.05a6.29 6.29 0 0 0-5.43-3.12c-2.32 0-4.33 1.26-5.43 3.12c0 .01 0 .02-.01.03a.56.56 0 0 0-.07.26c0 .3.25.55.55.55c.155 0 .29-.066.388-.172a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.527.527 0 0 0 .776 0a.23.23 0 0 1 .162-.078c.063 0 .12.033.162.078a.53.53 0 0 0 .388.172a.555.555 0 0 0 .5-.79");
}

.v26eh-bfe {
  stop-color: var(--svg-color--ffb193, #FFB193);
}

.v87kpx-pj {
  stop-color: var(--svg-color--ffd2ad, #FFD2AD);
}

.vtv60fbyw {
  d: path("M26.304 17.75h-1.78c-.34 0-.61-.27-.61-.61v-1.89c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v1.89c0 .33-.27.61-.61.61");
}

.w_nj4ibxp {
  stop-color: var(--svg-color--b56057, #B56057);
  stop-opacity: 0;
}

.w-fr9sbjq {
  stop-color: var(--svg-color--e22a4d, #E22A4D);
}

.w30a7_b9p {
  stop-color: var(--svg-color--ff5371, #FF5371);
  stop-opacity: 0;
}

.w46qowkvj {
  stop-color: var(--svg-color--cd897b, #CD897B);
  stop-opacity: 0;
}

.x1axjxb3y {
  stop-color: var(--svg-color--c25251, #C25251);
  stop-opacity: 0;
}

.xo-26j82a {
  stop-color: var(--svg-color--be8a79, #BE8A79);
}

.xy-6xyb3t {
  stop-color: var(--svg-color--ffccad, #FFCCAD);
}

.xz_7ousyx {
  stop-color: var(--svg-color--348fe8, #348FE8);
}

.yihajpbrc {
  stop-color: var(--svg-color--ffd2ad, #FFD2AD);
  stop-opacity: 0;
}

.yr3wtcbsb {
  d: path("M15.924 3.597h-.172a5.466 5.466 0 0 0-5.465 5.466v1.687a1 1 0 0 1-1 1H2.446a.6.6 0 0 1-.6-.6v-.133a3.25 3.25 0 0 1 3.25-3.25h3.297a.256.256 0 0 0 .249-.205a7.27 7.27 0 0 1 7.11-5.765h.172a7.27 7.27 0 0 1 7.11 5.765a.256.256 0 0 0 .25.206h3.296a3.25 3.25 0 0 1 3.25 3.25v.132a.6.6 0 0 1-.6.6h-6.84a1 1 0 0 1-1-1V9.063a5.466 5.466 0 0 0-5.466-5.466");
}

.ysxrizoyy {
  stop-color: var(--svg-color--b56057, #B56057);
}

.z0j4-it_z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.836 18.328c.97.11 2.97.822 4.032 2.735");
}

.zc2rh-bte {
  stop-color: var(--svg-color--ffcfaa, #FFCFAA);
}

.zgn9fqbsy {
  fill: var(--svg-color--b14e46, #B14E46);
  d: path("M17.187 11.916h-.02a.486.486 0 0 0-.49.48v1.482h-2.004v-1.481c0-.265-.22-.48-.489-.48h-.02a.485.485 0 0 0-.488.48v3.943c0 .264.22.48.488.48h.02c.27 0 .49-.216.49-.48v-1.472h2.004v1.472c0 .264.22.48.489.48h.02a.485.485 0 0 0 .488-.48v-3.943a.473.473 0 0 0-.488-.48");
}

.zvubohbgf {
  stop-color: var(--svg-color--ea2653, #EA2653);
}

</style>
