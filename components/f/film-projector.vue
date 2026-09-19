<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i3SbgSd)" class="d2kvgvbvc"><path class="ocxyv8o0f"/><path fill="url(#ikBCS3o)" class="mnpj3xbit"/></g><g clip-rule="evenodd" filter="url(#ilOWX2c)" class="d2kvgvbvc"><path class="hm-7vdbxt"/><path fill="url(#iirRjkd)" class="vyiz8abzb"/></g><g filter="url(#iTdWlAy)"><path class="arcz4abbp"/></g><g filter="url(#id6VxOd)" class="xj_9e55xi"><circle class="nxe36ccbj"/><circle stroke="url(#ioSQ27c)" class="xtv1q9bzz"/></g><g filter="url(#iLs16Gc)" class="omlm15gvn"><circle stroke="url(#iRWvCOe)" class="rfvrbbcey"/><circle stroke="url(#iv2zyoe)" class="rfvrbbcey"/></g><g filter="url(#iDZF0dg)" class="omlm15gvn"><circle stroke="url(#iulJYwT)" class="tt6q01jgb"/><circle stroke="url(#ijN7YGe)" class="tt6q01jgb"/></g><g filter="url(#io5TAYr)"><path fill="url(#iiMlNXd)" class="of63cfb0q"/></g><path fill="url(#i5WvbWb)" class="of63cfb0q"/><path fill="url(#igtJc8c)" class="of63cfb0q"/><path fill="url(#iUcOVCd)" class="b223azb5c"/><path fill="url(#icBPhWM)" class="d2_xbkaen"/><path fill="url(#i6cpULh)" class="pqzf_6ekv"/><g filter="url(#iAqRI6k)"><circle fill="url(#ixo87se)" class="a89eh2o8b"/><circle fill="url(#imWUeZb)" class="a89eh2o8b"/></g><g filter="url(#izSFy1c)"><circle class="qunh96r0q"/></g><g filter="url(#iDt4whc)"><circle fill="url(#io000jL)" class="sd7nlvh_y"/><circle fill="url(#ihP1IGi)" class="sd7nlvh_y"/></g><g filter="url(#iLt0xPd)"><circle class="eh1y6ws0o"/><circle fill="url(#ixDCv4b)" class="ih-p-hioo"/></g><path fill="url(#iAf0LVb)" class="vkei71sge"/><path fill="url(#ih5LSwd)" class="vkei71sge"/><path fill="url(#iadLZae)" class="vkei71sge"/><g filter="url(#iU03Mrb)"><path fill="url(#ioOovee)" class="a89tm4l9b"/><path fill="url(#iVGbzUk)" class="a89tm4l9b"/><path fill="url(#iIXiDee)" class="a89tm4l9b"/></g><g filter="url(#iwPczwY)"><rect class="a-1ao60vz"/><rect stroke="url(#iT6nagd)" class="qb3s6xbxm"/></g><g filter="url(#iBkEJtM)"><rect class="fw62ko8ac"/><rect stroke="url(#izF7XXd)" class="s9ht7rb3n"/></g><g filter="url(#ictqadH)"><rect class="l4jesmetb"/><rect stroke="url(#idhfSSc)" class="w9xufqx3f"/></g><g filter="url(#iDutnld)"><path stroke="url(#i1VTsIY)" class="vuhddwbqf"/></g><g filter="url(#ibbDhcB)"><path stroke="url(#i17SOBh)" class="nzmbdm-7u"/></g><g filter="url(#iKi8nOd)"><path stroke="url(#iSlTQXb)" class="c6syojkfu"/></g><g filter="url(#i8cdKUb)" class="tryqaac1t"><circle stroke="url(#in3voGe)" class="uyi484b8e"/><circle stroke="url(#iYfvG8b)" class="uyi484b8e"/></g><g filter="url(#inXyeic)" class="tryqaac1t"><circle stroke="url(#iYlsokb)" class="p2k6l290t"/><circle stroke="url(#idMYISb)" class="p2k6l290t"/></g><g filter="url(#i1wxBJd)"><path stroke="url(#iqmpaGc)" class="xi22fjzth"/></g><g filter="url(#ibMm5Ge)"><path stroke="url(#iWEUVSc)" class="txrieucog"/></g><g filter="url(#iCOS8Pc)"><path stroke="url(#irt22Bc)" class="wfl8r9bnb"/></g><g filter="url(#iMBnCXc)"><path stroke="url(#innSMEd)" class="iqwg51e2h"/></g><defs><linearGradient id="iRWvCOe" x1="24.667" x2="22.259" y1="8.959" y2="11.274" gradientUnits="userSpaceOnUse"><stop offset=".148" class="d1tvggbzl"/><stop offset="1" class="nwv8fugxv"/></linearGradient><linearGradient id="iv2zyoe" x1="15.93" x2="18.153" y1="16.986" y2="14.886" gradientUnits="userSpaceOnUse"><stop class="d1tvggbzl"/><stop offset="1" class="nwv8fugxv"/></linearGradient><linearGradient id="iulJYwT" x1="11.554" x2="9.441" y1="10.907" y2="12.939" gradientUnits="userSpaceOnUse"><stop offset=".148" class="d1tvggbzl"/><stop offset="1" class="nwv8fugxv"/></linearGradient><linearGradient id="ijN7YGe" x1="3.886" x2="5.837" y1="17.952" y2="16.109" gradientUnits="userSpaceOnUse"><stop class="d1tvggbzl"/><stop offset="1" class="nwv8fugxv"/></linearGradient><linearGradient id="iiMlNXd" x1="14.062" x2="14.062" y1="17.422" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="g_qgmwbxk"/><stop offset="1" class="g4lcke2ys"/><stop offset="1" class="yqlqvac-z"/></linearGradient><linearGradient id="i5WvbWb" x1="22.453" x2="22.192" y1="24.337" y2="24.337" gradientUnits="userSpaceOnUse"><stop class="sxfeeeb8t"/><stop offset="1" class="bawe3zibs"/></linearGradient><linearGradient id="igtJc8c" x1="5.671" x2="6.046" y1="24.063" y2="24.063" gradientUnits="userSpaceOnUse"><stop class="h2qa_4-qq"/><stop offset="1" class="t27u-ccvx"/></linearGradient><linearGradient id="iUcOVCd" x1="8.546" x2="12.89" y1="23.063" y2="23.063" gradientUnits="userSpaceOnUse"><stop class="wzu_o2bcv"/><stop offset="1" class="c0goksbgz"/></linearGradient><linearGradient id="icBPhWM" x1="8.546" x2="12.89" y1="24.852" y2="24.852" gradientUnits="userSpaceOnUse"><stop class="wzu_o2bcv"/><stop offset="1" class="c0goksbgz"/></linearGradient><linearGradient id="i6cpULh" x1="8.546" x2="12.89" y1="26.641" y2="26.641" gradientUnits="userSpaceOnUse"><stop class="wzu_o2bcv"/><stop offset="1" class="c0goksbgz"/></linearGradient><linearGradient id="ixo87se" x1="20.238" x2="19.07" y1="19.363" y2="21.372" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="i09ltdbfn"/></linearGradient><linearGradient id="io000jL" x1="20.238" x2="19.07" y1="25.066" y2="27.075" gradientUnits="userSpaceOnUse"><stop class="by-fq41bl"/><stop offset="1" class="whtrl6zio"/></linearGradient><linearGradient id="iAf0LVb" x1="23.718" x2="23.718" y1="20.805" y2="25.219" gradientUnits="userSpaceOnUse"><stop class="s53ynhzyr"/><stop offset="1" class="jnsbl2b9a"/></linearGradient><linearGradient id="ih5LSwd" x1="24.828" x2="24.828" y1="26.523" y2="25.359" gradientUnits="userSpaceOnUse"><stop class="r-3o4_95v"/><stop offset="1" class="djz-g7a3a"/></linearGradient><linearGradient id="iadLZae" x1="25.328" x2="24.234" y1="25.469" y2="25.469" gradientUnits="userSpaceOnUse"><stop class="x0t82pb_c"/><stop offset="1" class="odvazsbnq"/></linearGradient><linearGradient id="ioOovee" x1="27.328" x2="27.328" y1="23.031" y2="28.531" gradientUnits="userSpaceOnUse"><stop class="k6upvab7v"/><stop offset="1" class="lm38gjbom"/></linearGradient><linearGradient id="iVGbzUk" x1="26.75" x2="27.546" y1="28.453" y2="26.906" gradientUnits="userSpaceOnUse"><stop class="i4b031izo"/><stop offset="1" class="fk9wwhbvs"/></linearGradient><linearGradient id="i1VTsIY" x1="4.867" x2="8.714" y1="11.492" y2="14.664" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="i17SOBh" x1="18.954" x2="21.264" y1="8.9" y2="13.479" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="iSlTQXb" x1="8.975" x2="12.481" y1="15.488" y2="17.374" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="in3voGe" x1="6.312" x2="7.258" y1="15.297" y2="14.429" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="iYfvG8b" x1="8.812" x2="8.4" y1="13.781" y2="14.274" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="iYlsokb" x1="18.695" x2="19.736" y1="13.922" y2="12.968" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="idMYISb" x1="21.445" x2="20.992" y1="12.255" y2="12.798" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="iqmpaGc" x1="8.968" x2="9.944" y1="10.922" y2="11.836" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="iWEUVSc" x1="21.078" x2="23.182" y1="15.203" y2="15.622" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="irt22Bc" x1="21.702" x2="23.851" y1="12.534" y2="16.101" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><linearGradient id="innSMEd" x1="15.624" x2="16.208" y1="11.683" y2="13.62" gradientUnits="userSpaceOnUse"><stop class="iv3noriwk"/><stop offset="1" class="dmqgfidqi"/></linearGradient><filter id="i3SbgSd" width="11.117" height="11.523" x="14.261" y="8.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.2 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_236_100"/></filter><filter id="ilOWX2c" width="9.646" height="10.102" x="2.492" y="9.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.2 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_236_100"/></filter><filter id="iTdWlAy" width="12.242" height="12.492" x="13.828" y="6.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.560784 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_236_100"/></filter><filter id="id6VxOd" width="10.906" height="11.156" x="1.89" y="8.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.560784 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_236_100"/></filter><filter id="iLs16Gc" width="11.681" height="11.681" x="14.332" y="7.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".125"/></filter><filter id="iDZF0dg" width="10.344" height="10.344" x="2.437" y="9.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".125"/></filter><filter id="io5TAYr" width="18.281" height="13.984" x="4.921" y="16.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.862745 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_236_100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.741176 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_236_100" result="effect2_innerShadow_236_100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.635294 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_236_100" result="effect3_innerShadow_236_100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.52549 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_236_100" result="effect4_innerShadow_236_100"/></filter><filter id="iAqRI6k" width="3.302" height="3.302" x="17.629" y="18.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.611765 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_236_100"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_236_100" result="shape"/></filter><filter id="izSFy1c" width="2.007" height="2.007" x="18.476" y="19.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="iDt4whc" width="3.302" height="3.302" x="17.629" y="24.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.611765 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_236_100"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_236_100" result="shape"/></filter><filter id="iLt0xPd" width="1.978" height="1.978" x="18.491" y="25.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="iU03Mrb" width="4.688" height="11.975" x="24.984" y="17.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.270588 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_236_100"/></filter><filter id="iwPczwY" width="5.359" height=".632" x="7.885" y="22.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".05"/></filter><filter id="iBkEJtM" width="5.359" height=".632" x="7.885" y="24.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".05"/></filter><filter id="ictqadH" width="5.359" height=".632" x="7.885" y="26.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".05"/></filter><filter id="iDutnld" width="2.702" height="2.298" x="4.567" y="11.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="ibbDhcB" width="2.146" height="3.463" x="18.577" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".15"/></filter><filter id="iKi8nOd" width="2.07" height="2.42" x="8.675" y="15.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="i8cdKUb" width="3.342" height="3.342" x="5.77" y="12.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="inXyeic" width="3.616" height="3.616" x="18.129" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="i1wxBJd" width="1.334" height="3.084" x="7.934" y="10.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".1"/></filter><filter id="ibMm5Ge" width="1.65" height="3.338" x="20.628" y="14.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".15"/></filter><filter id="iCOS8Pc" width="3.666" height="1.978" x="21.252" y="11.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".15"/></filter><filter id="iMBnCXc" width="3.588" height="1.525" x="15.175" y="11.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_236_100" stdDeviation=".15"/></filter><radialGradient id="ikBCS3o" cx="0" cy="0" r="1" gradientTransform="rotate(93.957 5.326 14.763)scale(8.72319 5.74492)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="drjhmk1ia"/><stop offset="1" class="ok78h-vin"/></radialGradient><radialGradient id="iirRjkd" cx="0" cy="0" r="1" gradientTransform="matrix(2.8233 7.03522 -4.63325 1.85936 6.777 12.318)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="drjhmk1ia"/><stop offset="1" class="ok78h-vin"/></radialGradient><radialGradient id="ioSQ27c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -1.65626 3.76316 -3.69212 5.765 19.219)" gradientUnits="userSpaceOnUse"><stop class="s7225sejn"/><stop offset="1" class="atq3wridc"/></radialGradient><radialGradient id="imWUeZb" cx="0" cy="0" r="1" gradientTransform="rotate(-135.385 14.303 6.393)scale(1.8377 2.28294)" gradientUnits="userSpaceOnUse"><stop offset=".665" class="xb_fvdb_y"/><stop offset="1" class="w84k5bc_l"/></radialGradient><radialGradient id="ihP1IGi" cx="0" cy="0" r="1" gradientTransform="rotate(-135.385 15.473 9.244)scale(1.8377 2.28294)" gradientUnits="userSpaceOnUse"><stop offset=".665" class="o4zap0bag"/><stop offset="1" class="swv2hrb1g"/></radialGradient><radialGradient id="ixDCv4b" cx="0" cy="0" r="1" gradientTransform="rotate(-42.955 43.187 -11.097)scale(1.23823)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="qb_1kqbbl"/><stop offset="1" class="lgseriloi"/></radialGradient><radialGradient id="iIXiDee" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.96875 -.4375 0 29.421 22.594)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="ea9x8q-yv"/><stop offset="1" class="f--azwn0g"/></radialGradient><radialGradient id="iT6nagd" cx="0" cy="0" r="1" gradientTransform="matrix(3.72612 0 0 .59662 8.286 23.107)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ngv1kkbnd"/><stop offset="1" class="p61j2ubpv"/></radialGradient><radialGradient id="izF7XXd" cx="0" cy="0" r="1" gradientTransform="matrix(3.72612 0 0 .59662 8.286 24.96)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ngv1kkbnd"/><stop offset="1" class="p61j2ubpv"/></radialGradient><radialGradient id="idhfSSc" cx="0" cy="0" r="1" gradientTransform="matrix(3.72612 0 0 .59662 8.286 26.72)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ngv1kkbnd"/><stop offset="1" class="p61j2ubpv"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:film-projector" /></template>
<style>
.a-1ao60vz {
  width: 5.059px;
  height: 0.332px;
  x: 8.035px;
  y: 22.775px;
  fill: var(--svg-color--4a3e56, #4A3E56);
  rx: 0.166px;
}

.a89eh2o8b {
  cx: 19.48px;
  cy: 20.414px;
  r: 1.051px;
}

.a89tm4l9b {
  d: path("M29.671 18.565a.6.6 0 0 0-.868-.537l-3.266 1.633a1 1 0 0 0-.553.895v6.247a1 1 0 0 0 .543.89l3.27 1.679a.6.6 0 0 0 .874-.534z");
}

.arcz4abbp {
  stroke: var(--svg-color--a6a1ab, #A6A1AB);
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M25.42 13.188a5.471 5.471 0 1 1-10.942 0a5.471 5.471 0 0 1 10.942 0Z");
}

.atq3wridc {
  stop-color: var(--svg-color--90869a, #90869A);
  stop-opacity: 0;
}

.b223azb5c {
  d: path("M7.765 22.887a.48.48 0 0 1 .48-.48h4.673a.48.48 0 0 1 0 .96H8.246a.48.48 0 0 1-.48-.48");
}

.bawe3zibs {
  stop-color: var(--svg-color--beb8c4, #BEB8C4);
  stop-opacity: 0;
}

.by-fq41bl {
  stop-color: var(--svg-color--ff4676, #FF4676);
}

.c0goksbgz {
  stop-color: var(--svg-color--32273f, #32273F);
}

.c6syojkfu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.984 15.32c-.02.06-.02.228.148.422c.17.194.946 1.013 1.313 1.399");
}

.d1tvggbzl {
  stop-color: var(--svg-color--c0bec3, #C0BEC3);
}

.d2_xbkaen {
  d: path("M7.765 24.676a.48.48 0 0 1 .48-.48h4.673a.48.48 0 0 1 0 .96H8.246a.48.48 0 0 1-.48-.48");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.djz-g7a3a {
  stop-color: var(--svg-color--84699e, #84699E);
  stop-opacity: 0;
}

.dmqgfidqi {
  stop-color: var(--svg-color--62596b, #62596B);
  stop-opacity: 0;
}

.drjhmk1ia {
  stop-color: var(--svg-color--3a3043, #3A3043);
  stop-opacity: 0;
}

.ea9x8q-yv {
  stop-color: var(--svg-color--5a5560, #5A5560);
}

.eh1y6ws0o {
  cx: 19.48px;
  cy: 26.117px;
  r: 0.789px;
  fill: var(--svg-color--f4396b, #F4396B);
}

.f--azwn0g {
  stop-color: var(--svg-color--5a5560, #5A5560);
  stop-opacity: 0;
}

.fk9wwhbvs {
  stop-color: var(--svg-color--442d59, #442D59);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fw62ko8ac {
  width: 5.059px;
  height: 0.332px;
  x: 8.035px;
  y: 24.629px;
  fill: var(--svg-color--4a3e56, #4A3E56);
  rx: 0.166px;
}

.g_qgmwbxk {
  stop-color: var(--svg-color--bfb8c7, #BFB8C7);
}

.g4lcke2ys {
  stop-color: var(--svg-color--bfb4cb, #BFB4CB);
}

.h2qa_4-qq {
  stop-color: var(--svg-color--c5c1ca, #C5C1CA);
}

.hm-7vdbxt {
  fill: var(--svg-color--4d4259, #4D4259);
  d: path("M4.995 10.94L3.81 12.06l1.577 1.669a.348.348 0 0 1-.17.577l-2.725.663l.386 1.585l2.72-.663c.26-.063.491.18.415.436l-.81 2.74l1.564.463l.806-2.728a.348.348 0 0 1 .586-.14l2.198 2.325l1.186-1.12l-2.22-2.349a.348.348 0 0 1 .17-.576l2.645-.645l-.386-1.584l-2.613.637a.348.348 0 0 1-.416-.437l.746-2.523l-1.564-.463l-.75 2.539a.348.348 0 0 1-.586.14zm2.894 4.623a1.042 1.042 0 1 0-.908-1.877a1.042 1.042 0 0 0 .908 1.877");
}

.i09ltdbfn {
  stop-color: var(--svg-color--ba9fd1, #BA9FD1);
}

.i4b031izo {
  stop-color: var(--svg-color--694787, #694787);
}

.ih-p-hioo {
  cx: 19.48px;
  cy: 26.117px;
  r: 0.789px;
}

.iqwg51e2h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m15.625 11.64l2.687.626");
}

.iv3noriwk {
  stop-color: var(--svg-color--62596b, #62596B);
}

.jnsbl2b9a {
  stop-color: var(--svg-color--9481a8, #9481A8);
}

.k6upvab7v {
  stop-color: var(--svg-color--343137, #343137);
}

.l4jesmetb {
  width: 5.059px;
  height: 0.332px;
  x: 8.035px;
  y: 26.389px;
  fill: var(--svg-color--4a3e56, #4A3E56);
  rx: 0.166px;
}

.lgseriloi {
  stop-color: var(--svg-color--ff6285, #FF6285);
}

.lm38gjbom {
  stop-color: var(--svg-color--402b54, #402B54);
}

.mnpj3xbit {
  d: path("m19.267 8.148l-1.789.567l.797 2.518a.4.4 0 0 1-.465.512l-3.155-.678l-.394 1.835l3.149.676a.4.4 0 0 1 .212.66l-2.213 2.433l1.388 1.262L19 15.513a.4.4 0 0 1 .677.148l1.112 3.51l1.789-.566l-1.123-3.546a.4.4 0 0 1 .466-.511l3.063.658l.394-1.835l-3.026-.65a.4.4 0 0 1-.212-.66l2.038-2.24l-1.388-1.263l-2.05 2.253a.4.4 0 0 1-.677-.149zm.682 6.239a1.2 1.2 0 1 0 0-2.399a1.2 1.2 0 0 0 0 2.399");
}

.ngv1kkbnd {
  stop-color: var(--svg-color--544b5e, #544B5E);
}

.nwv8fugxv {
  stop-color: var(--svg-color--c0bec3, #C0BEC3);
  stop-opacity: 0;
}

.nxe36ccbj {
  cx: 7.343px;
  cy: 14.605px;
  r: 4.803px;
  stroke: var(--svg-color--a6a1ab, #A6A1AB);
}

.nzmbdm-7u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m19.028 8.749l.745 2.298c0 .148.281.36.5.219");
}

.o4zap0bag {
  stop-color: var(--svg-color--b9526a, #B9526A);
  stop-opacity: 0;
}

.ocxyv8o0f {
  fill: var(--svg-color--4d4259, #4D4259);
  d: path("m19.267 8.148l-1.789.567l.797 2.518a.4.4 0 0 1-.465.512l-3.155-.678l-.394 1.835l3.149.676a.4.4 0 0 1 .212.66l-2.213 2.433l1.388 1.262L19 15.513a.4.4 0 0 1 .677.148l1.112 3.51l1.789-.566l-1.123-3.546a.4.4 0 0 1 .466-.511l3.063.658l.394-1.835l-3.026-.65a.4.4 0 0 1-.212-.66l2.038-2.24l-1.388-1.263l-2.05 2.253a.4.4 0 0 1-.677-.149zm.682 6.239a1.2 1.2 0 1 0 0-2.399a1.2 1.2 0 0 0 0 2.399");
}

.odvazsbnq {
  stop-color: var(--svg-color--848087, #848087);
  stop-opacity: 0;
}

.of63cfb0q {
  d: path("M5.671 19.522c0-1.16.94-2.1 2.1-2.1h12.582c1.16 0 2.1.94 2.1 2.1v8.284a2.1 2.1 0 0 1-2.1 2.1H7.77a2.1 2.1 0 0 1-2.1-2.1z");
}

.ok78h-vin {
  stop-color: var(--svg-color--3a3043, #3A3043);
}

.omlm15gvn {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.p2k6l290t {
  cx: 19.937px;
  cy: 13.188px;
  r: 1.508px;
}

.p61j2ubpv {
  stop-color: var(--svg-color--544b5e, #544B5E);
  stop-opacity: 0;
}

.pqzf_6ekv {
  d: path("M7.765 26.465a.48.48 0 0 1 .48-.48h4.673a.48.48 0 0 1 0 .96H8.246a.48.48 0 0 1-.48-.48");
}

.qb_1kqbbl {
  stop-color: var(--svg-color--ff6285, #FF6285);
  stop-opacity: 0;
}

.qb3s6xbxm {
  width: 5.059px;
  height: 0.332px;
  x: 8.035px;
  y: 22.775px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  rx: 0.166px;
}

.qunh96r0q {
  cx: 19.48px;
  cy: 20.414px;
  r: 0.804px;
  fill: var(--svg-color--e1d7eb, #E1D7EB);
}

.r-3o4_95v {
  stop-color: var(--svg-color--9e75c2, #9E75C2);
}

.rfvrbbcey {
  cx: 20.172px;
  cy: 12.91px;
  r: 5.465px;
}

.s53ynhzyr {
  stop-color: var(--svg-color--adabae, #ADABAE);
}

.s7225sejn {
  stop-color: var(--svg-color--90869a, #90869A);
}

.s9ht7rb3n {
  width: 5.059px;
  height: 0.332px;
  x: 8.035px;
  y: 24.629px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  rx: 0.166px;
}

.sd7nlvh_y {
  cx: 19.48px;
  cy: 26.117px;
  r: 1.051px;
}

.swv2hrb1g {
  stop-color: var(--svg-color--b9526a, #B9526A);
}

.sxfeeeb8t {
  stop-color: var(--svg-color--beb8c4, #BEB8C4);
}

.t27u-ccvx {
  stop-color: var(--svg-color--c5c1ca, #C5C1CA);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tt6q01jgb {
  cx: 7.609px;
  cy: 14.374px;
  r: 4.797px;
}

.txrieucog {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m21.078 14.984l.75 2.438");
}

.uyi484b8e {
  cx: 7.441px;
  cy: 14.629px;
  r: 1.371px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vkei71sge {
  d: path("M22.453 20.805h2.531v5.648h-2.531z");
}

.vuhddwbqf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m4.867 11.336l1.479 1.547a.48.48 0 0 0 .622.062");
}

.vyiz8abzb {
  d: path("M4.995 10.94L3.81 12.06l1.577 1.669a.348.348 0 0 1-.17.577l-2.725.663l.386 1.585l2.72-.663c.26-.063.491.18.415.436l-.81 2.74l1.564.463l.806-2.728a.348.348 0 0 1 .586-.14l2.198 2.325l1.186-1.12l-2.22-2.349a.348.348 0 0 1 .17-.576l2.645-.645l-.386-1.584l-2.613.637a.348.348 0 0 1-.416-.437l.746-2.523l-1.564-.463l-.75 2.539a.348.348 0 0 1-.586.14zm2.894 4.623a1.042 1.042 0 1 0-.908-1.877a1.042 1.042 0 0 0 .908 1.877");
}

.w84k5bc_l {
  stop-color: var(--svg-color--b6b2ba, #B6B2BA);
}

.w9xufqx3f {
  width: 5.059px;
  height: 0.332px;
  x: 8.035px;
  y: 26.389px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  rx: 0.166px;
}

.wfl8r9bnb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.703 12.438c-.01.171.115.543.703.656c.587.112 1.62.328 2.062.422");
}

.whtrl6zio {
  stop-color: var(--svg-color--bc3e68, #BC3E68);
}

.wzu_o2bcv {
  stop-color: var(--svg-color--3b284d, #3B284D);
}

.x0t82pb_c {
  stop-color: var(--svg-color--848087, #848087);
}

.xb_fvdb_y {
  stop-color: var(--svg-color--b6b2ba, #B6B2BA);
  stop-opacity: 0;
}

.xi22fjzth {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m8.968 10.922l-.734 2.484");
}

.xj_9e55xi {
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
}

.xtv1q9bzz {
  cx: 7.343px;
  cy: 14.605px;
  r: 4.803px;
}

.yqlqvac-z {
  stop-color: var(--svg-color--bfb8c7, #BFB8C7);
  stop-opacity: 0;
}

</style>
