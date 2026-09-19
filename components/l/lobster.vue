<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWi4ofb)" class="aau6o3x6f"/><path fill="url(#iGBI4Hd)" class="aau6o3x6f"/><path fill="url(#iCgXiYb)" class="aau6o3x6f"/><path fill="url(#ihXbkfe)" class="yxxmf3mab"/><g filter="url(#i8J3jge)"><path fill="url(#i2yovFW)" class="dppm6ebxf"/></g><path fill="url(#i5COhSt)" class="ixqtd9bjm"/><path fill="url(#iACcRBY)" class="ixqtd9bjm"/><g filter="url(#icG1Hpb)"><path fill="url(#iW3WnQd)" class="h0ewpf04l"/></g><path class="rbycsmgua"/><path fill="url(#imm8b5b)" class="k39albcgt"/><path fill="url(#i1QrLqe)" class="k39albcgt"/><path fill="url(#ixeJYZb)" class="tejb0b7uv"/><path fill="url(#ikYSiCb)" class="tejb0b7uv"/><g filter="url(#iW60pJG)"><path fill="url(#iCs6uTb)" class="k_m935bak"/><path fill="url(#iRqe4Nd)" class="k_m935bak"/></g><path fill="url(#iIfVsJb)" class="lvi8a9bcs"/><path fill="url(#ibsT41d)" class="lvi8a9bcs"/><path fill="url(#iOThmed)" class="lvi8a9bcs"/><path fill="url(#iRG9Zhd)" class="i95mrsb3d"/><g filter="url(#iOvNJFb)"><path class="zb--ncckg"/><path fill="url(#iicCe2d)" class="pp0wq78pw"/></g><path fill="url(#ihYbiNe)" class="whmtv8gxq"/><g filter="url(#ifXtrnn)"><path fill="url(#iBGNezb)" class="gwkh3vb5n"/></g><path fill="url(#iOoUQWd)" class="qx072acpa"/><path fill="url(#i5Pu27d)" class="gq5jbac-g"/><path stroke="url(#ilx0BAC)" class="m-27yccxb"/><path stroke="url(#iFwLiKW)" class="nmw17-wek"/><path stroke="url(#iPVLcGd)" class="z9q01ubye"/><path stroke="url(#iZdOK5b)" class="iqske7fva"/><path stroke="url(#ioLYjoE)" class="fhpn-cc1b"/><path stroke="url(#iDt9IYb)" class="rk0y-kbzi"/><path stroke="url(#izSfyEb)" class="iakgiobxd"/><g filter="url(#i5UWpBn)"><path class="x023d6bvk"/><path class="qqakkz7ui"/></g><g filter="url(#ifajr4b)"><path stroke="url(#i3GkWhE)" class="un2r7bzjs"/></g><g filter="url(#iNMwG3g)"><path stroke="url(#izCFiqb)" class="qoz2cxbtf"/></g><path stroke="url(#iS5hA0d)" class="f9sa_8yxs"/><path fill="url(#iJG6DNe)" class="dyphehnga"/><path fill="url(#iCa1cqd)" class="dyphehnga"/><path fill="url(#ia3rRGr)" class="dyphehnga"/><path fill="url(#iSCvVue)" class="dyphehnga"/><path fill="url(#i33ODmn)" class="ca65gd4ie"/><path fill="url(#iXwaZgd)" class="ca65gd4ie"/><path fill="url(#i128sOe)" class="oi-vo5bap"/><path fill="url(#iZP4ioT)" class="oi-vo5bap"/><path fill="url(#iDSurEb)" class="oi-vo5bap"/><path fill="url(#ixF1akT)" class="oi-vo5bap"/><path fill="url(#imwKX0c)" class="y-olwtbxr"/><path fill="url(#iP6Fl4d)" class="c5wglx3lq"/><g filter="url(#iNYpRif)"><path stroke="url(#inVJyBb)" class="faiivbb8o"/></g><g filter="url(#iMMA1tb)"><path stroke="url(#iWp6rib)" class="q9i20euwg"/></g><g filter="url(#ibhftde)"><path stroke="url(#ihB6zad)" class="hrr_37bzt"/></g><g filter="url(#iGCz9gV)"><path stroke="url(#iHpXRkm)" class="twfzesbvj"/></g><g filter="url(#iuQeTLb)"><path stroke="url(#ixJ82qe)" class="d8wo5-bxd"/></g><g filter="url(#ihAKguc)"><path stroke="url(#igJazKb)" class="s-4qrqbzo"/></g><g filter="url(#im76Uee)"><path stroke="url(#iZlzQ7c)" class="jyoehxvcj"/></g><g filter="url(#idYhOWp)"><path stroke="url(#i9uLIkb)" class="ubn1qtb6q"/></g><defs><linearGradient id="ihXbkfe" x1="8.97" x2="6.65" y1="3.938" y2="3.938" gradientUnits="userSpaceOnUse"><stop class="u1-f47b8g"/><stop offset=".64" class="fbtsr8b_u"/><stop offset=".93" class="q73dyibzb"/></linearGradient><linearGradient id="i2yovFW" x1="7.807" x2="7.788" y1="7.125" y2="2.469" gradientUnits="userSpaceOnUse"><stop class="b69a92b4e"/><stop offset="1" class="fd99hlbyi"/></linearGradient><linearGradient id="i5COhSt" x1="2" x2="8.98" y1="6.563" y2="6.563" gradientUnits="userSpaceOnUse"><stop class="lfdtwy12j"/><stop offset=".501" class="c93cdibfk"/><stop offset="1" class="ng2qtmh1b"/></linearGradient><linearGradient id="iACcRBY" x1="8.375" x2="3.688" y1="3.063" y2="12.625" gradientUnits="userSpaceOnUse"><stop offset=".528" class="f8v85nbvc"/><stop offset=".881" class="eqyjdobxy"/></linearGradient><linearGradient id="iW3WnQd" x1="5.49" x2="5.49" y1="2.66" y2="12.342" gradientUnits="userSpaceOnUse"><stop class="qum_a2nji"/><stop offset=".61" class="dhduy4b6b"/><stop offset="1" class="j19w5cbtf"/></linearGradient><linearGradient id="ixeJYZb" x1="25.32" x2="23" y1="3.941" y2="3.941" gradientUnits="userSpaceOnUse"><stop class="u1-f47b8g"/><stop offset=".64" class="fbtsr8b_u"/><stop offset=".93" class="q73dyibzb"/></linearGradient><linearGradient id="ikYSiCb" x1="23.75" x2="24.438" y1="4.25" y2="7.75" gradientUnits="userSpaceOnUse"><stop class="ulty2wr-s"/><stop offset="1" class="ldg_qk7bv"/></linearGradient><linearGradient id="iCs6uTb" x1="24.189" x2="24.208" y1="7.125" y2="2.469" gradientUnits="userSpaceOnUse"><stop class="b69a92b4e"/><stop offset="1" class="fd99hlbyi"/></linearGradient><linearGradient id="iIfVsJb" x1="22.99" x2="29.97" y1="6.563" y2="6.563" gradientUnits="userSpaceOnUse"><stop class="lfdtwy12j"/><stop offset=".501" class="c93cdibfk"/><stop offset="1" class="ng2qtmh1b"/></linearGradient><linearGradient id="ibsT41d" x1="29.365" x2="24.677" y1="3.063" y2="12.625" gradientUnits="userSpaceOnUse"><stop offset=".528" class="f8v85nbvc"/><stop offset=".881" class="eqyjdobxy"/></linearGradient><linearGradient id="iRG9Zhd" x1="13.545" x2="13.545" y1="25.75" y2="30" gradientUnits="userSpaceOnUse"><stop class="ckum5db6o"/><stop offset="1" class="t3gv8nb7b"/></linearGradient><linearGradient id="iicCe2d" x1="13.575" x2="12.781" y1="27.399" y2="27.688" gradientUnits="userSpaceOnUse"><stop offset=".34" class="yz56m5b-n"/><stop offset=".818" class="kxk7zm8xp"/></linearGradient><linearGradient id="ihYbiNe" x1="18.395" x2="18.395" y1="24.85" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".502" class="r8ylniejx"/><stop offset="1" class="tcohyrw_p"/></linearGradient><linearGradient id="iBGNezb" x1="26.474" x2="26.474" y1="2.66" y2="12.342" gradientUnits="userSpaceOnUse"><stop class="qum_a2nji"/><stop offset=".61" class="dhduy4b6b"/><stop offset="1" class="j19w5cbtf"/></linearGradient><linearGradient id="iOoUQWd" x1="12.465" x2="12.465" y1="2" y2="13.235" gradientUnits="userSpaceOnUse"><stop class="c_pzsqbqv"/><stop offset=".328" class="jq5s11ztn"/><stop offset=".757" class="o3lo83bkk"/></linearGradient><linearGradient id="i5Pu27d" x1="19.465" x2="19.465" y1="2" y2="13.235" gradientUnits="userSpaceOnUse"><stop class="c_pzsqbqv"/><stop offset=".328" class="jq5s11ztn"/><stop offset=".757" class="o3lo83bkk"/></linearGradient><linearGradient id="ilx0BAC" x1="7.5" x2="10.875" y1="19.083" y2="19.083" gradientUnits="userSpaceOnUse"><stop offset=".13" class="x0yvoccsb"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="iFwLiKW" x1="9.287" x2="11.8" y1="26.664" y2="24.092" gradientUnits="userSpaceOnUse"><stop offset=".229" class="hucduvbqn"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="iPVLcGd" x1="6.399" x2="11.157" y1="23.472" y2="23.472" gradientUnits="userSpaceOnUse"><stop offset=".229" class="tksr4bcab"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="iZdOK5b" x1="5.725" x2="10.742" y1="20.788" y2="20.788" gradientUnits="userSpaceOnUse"><stop offset=".229" class="tksr4bcab"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="ioLYjoE" x1="24.39" x2="21.015" y1="19.083" y2="19.083" gradientUnits="userSpaceOnUse"><stop offset=".13" class="x0yvoccsb"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="iDt9IYb" x1="22.603" x2="20.09" y1="26.664" y2="24.092" gradientUnits="userSpaceOnUse"><stop offset=".229" class="hucduvbqn"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="izSfyEb" x1="25.491" x2="20.733" y1="23.472" y2="23.472" gradientUnits="userSpaceOnUse"><stop offset=".229" class="tksr4bcab"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="i3GkWhE" x1="12.906" x2="12.906" y1="2.688" y2="9.375" gradientUnits="userSpaceOnUse"><stop offset=".051" class="kl0gndbba"/><stop offset="1" class="lv2sqnbzy"/></linearGradient><linearGradient id="izCFiqb" x1="19.113" x2="19.113" y1="2.688" y2="9.375" gradientUnits="userSpaceOnUse"><stop offset=".051" class="kl0gndbba"/><stop offset="1" class="lv2sqnbzy"/></linearGradient><linearGradient id="iS5hA0d" x1="26.165" x2="21.148" y1="20.788" y2="20.788" gradientUnits="userSpaceOnUse"><stop offset=".229" class="tksr4bcab"/><stop offset="1" class="juu3v0q0g"/></linearGradient><linearGradient id="i128sOe" x1="15.975" x2="15.975" y1="24.188" y2="29.989" gradientUnits="userSpaceOnUse"><stop class="t0i0pzbgu"/><stop offset=".528" class="coyk0lboz"/><stop offset="1" class="dnwz-0lce"/></linearGradient><linearGradient id="iDSurEb" x1="19.91" x2="18.031" y1="26.438" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".268" class="vyvn4ib4r"/><stop offset=".738" class="if3rt2bcd"/></linearGradient><linearGradient id="ixF1akT" x1="12.04" x2="14" y1="26.25" y2="25.813" gradientUnits="userSpaceOnUse"><stop offset=".268" class="zoyzd4bus"/><stop offset=".641" class="hkzay866c"/></linearGradient><linearGradient id="inVJyBb" x1="7.969" x2="9.141" y1="18.219" y2="20.031" gradientUnits="userSpaceOnUse"><stop class="hoc8v5bfa"/><stop offset="1" class="gwmp84bzh"/></linearGradient><linearGradient id="iWp6rib" x1="6.396" x2="10.469" y1="19.757" y2="22.493" gradientUnits="userSpaceOnUse"><stop offset=".379" class="h8h6zobqe"/><stop offset="1" class="n-6fdzcag"/></linearGradient><linearGradient id="ihB6zad" x1="7.537" x2="11.611" y1="21.963" y2="24.699" gradientUnits="userSpaceOnUse"><stop offset=".379" class="h8h6zobqe"/><stop offset="1" class="n-6fdzcag"/></linearGradient><linearGradient id="iHpXRkm" x1="8.98" x2="13.782" y1="25.8" y2="26.482" gradientUnits="userSpaceOnUse"><stop class="rbctgzbis"/><stop offset="1" class="tbodwx39q"/></linearGradient><linearGradient id="ixJ82qe" x1="24.019" x2="22.847" y1="18.219" y2="20.031" gradientUnits="userSpaceOnUse"><stop class="hoc8v5bfa"/><stop offset="1" class="gwmp84bzh"/></linearGradient><linearGradient id="igJazKb" x1="25.592" x2="21.519" y1="19.757" y2="22.493" gradientUnits="userSpaceOnUse"><stop offset=".379" class="h8h6zobqe"/><stop offset="1" class="n-6fdzcag"/></linearGradient><linearGradient id="iZlzQ7c" x1="24.45" x2="20.377" y1="21.963" y2="24.699" gradientUnits="userSpaceOnUse"><stop offset=".379" class="h8h6zobqe"/><stop offset="1" class="n-6fdzcag"/></linearGradient><linearGradient id="i9uLIkb" x1="23.008" x2="18.206" y1="25.8" y2="26.482" gradientUnits="userSpaceOnUse"><stop class="rbctgzbis"/><stop offset="1" class="tbodwx39q"/></linearGradient><radialGradient id="iWi4ofb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5 3.875 -2.57944 2.32982 9.688 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="x14rbd3sf"/><stop offset=".413" class="hyqyvobvb"/><stop offset=".642" class="z-u4zdbet"/><stop offset=".871" class="n4og0_7kx"/></radialGradient><radialGradient id="iGBI4Hd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 4.125 -2.41128 -.14614 10.938 15.063)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="k6c8iabxn"/><stop offset=".849" class="txzt4fbie"/></radialGradient><radialGradient id="iCgXiYb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.28125 -4.30385 1.57458 7.438 12.25)" gradientUnits="userSpaceOnUse"><stop class="l2-etnbyx"/><stop offset="1" class="pb4av_b-t"/></radialGradient><radialGradient id="imm8b5b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58123 4.48002 -2.98218 -1.71823 22.675 13.75)" gradientUnits="userSpaceOnUse"><stop class="yjdv2nbqt"/><stop offset=".179" class="s-r5klbqh"/><stop offset=".501" class="uremmztjm"/><stop offset=".841" class="oxog_ebjd"/></radialGradient><radialGradient id="i1QrLqe" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 3.5 -2.32982 .20802 20.375 15.25)" gradientUnits="userSpaceOnUse"><stop class="p3sbsrblf"/><stop offset="1" class="gv7yz7lik"/></radialGradient><radialGradient id="iRqe4Nd" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.34375 -2.13075 .74329 24 7.281)" gradientUnits="userSpaceOnUse"><stop class="a9v36geqs"/><stop offset="1" class="s5j8a88ej"/></radialGradient><radialGradient id="iOThmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51564 2.48437 -.49574 -.30244 23.61 6.672)" gradientUnits="userSpaceOnUse"><stop class="ob29sdp9n"/><stop offset="1" class="s-jx-u4ys"/></radialGradient><radialGradient id="iJG6DNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 9.6875 -8.67038 -1.28658 17.938 12.75)" gradientUnits="userSpaceOnUse"><stop class="vr3g63rah"/><stop offset=".624" class="j-gmzlbvu"/><stop offset="1" class="nz5yx22bi"/></radialGradient><radialGradient id="iCa1cqd" cx="0" cy="0" r="1" gradientTransform="rotate(149.284 7.664 8.927)scale(3.30379 8.45705)" gradientUnits="userSpaceOnUse"><stop class="w84f_kbhv"/><stop offset="1" class="y_q02vkbm"/></radialGradient><radialGradient id="ia3rRGr" cx="0" cy="0" r="1" gradientTransform="rotate(119.438 3.229 9.47)scale(7.24838 3.05476)" gradientUnits="userSpaceOnUse"><stop class="kh6dvkbvz"/><stop offset="1" class="wlp_yfbqf"/></radialGradient><radialGradient id="iSCvVue" cx="0" cy="0" r="1" gradientTransform="matrix(-.41034 3.3125 -1.69907 -.21047 10.813 16.438)" gradientUnits="userSpaceOnUse"><stop class="bb_x3_baq"/><stop offset="1" class="oig1098cc"/></radialGradient><radialGradient id="i33ODmn" cx="0" cy="0" r="1" gradientTransform="matrix(-.68746 6.125 -10.02118 -1.12476 17.062 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ipw8i8lvn"/><stop offset=".883" class="bpvlakyeh"/></radialGradient><radialGradient id="iXwaZgd" cx="0" cy="0" r="1" gradientTransform="matrix(.125 4.125 -8.12133 .2461 13.25 20)" gradientUnits="userSpaceOnUse"><stop class="uuqgiwben"/><stop offset=".796" class="b0uho53uq"/></radialGradient><radialGradient id="iZP4ioT" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 3.25 -5.52442 -.95615 17.063 24.625)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="ipjhywbre"/><stop offset="1" class="aia7rmg8o"/></radialGradient><radialGradient id="imwKX0c" cx="0" cy="0" r="1" gradientTransform="rotate(137.421 6.606 9.701)scale(1.48537)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vtwedfbeg"/><stop offset=".392" class="f0j6pdcdx"/><stop offset=".764" class="arc7qbbxg"/></radialGradient><radialGradient id="iP6Fl4d" cx="0" cy="0" r="1" gradientTransform="rotate(137.421 4.886 9.03)scale(1.48537)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vtwedfbeg"/><stop offset=".392" class="f0j6pdcdx"/><stop offset=".764" class="arc7qbbxg"/></radialGradient><filter id="i8J3jge" width="2.078" height="6.301" x="6.797" y="2.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="icG1Hpb" width="6.344" height="10.182" x="2.313" y="2.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iW60pJG" width="2.078" height="6.301" x="23.121" y="2.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iOvNJFb" width="5.071" height="5.073" x="11.039" y="24.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".25"/></filter><filter id="ifXtrnn" width="6.344" height="10.182" x="23.308" y="2.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="i5UWpBn" width="5.071" height="5.073" x="15.912" y="24.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".25"/></filter><filter id="ifajr4b" width="4.969" height="7.688" x="10.031" y="1.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iNMwG3g" width="4.969" height="7.688" x="17.019" y="1.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iNYpRif" width="3.469" height="2.844" x="7.531" y="17.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iMMA1tb" width="5.656" height="3.395" x="6" y="19.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="ibhftde" width="5.219" height="1.719" x="6.844" y="22.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iGCz9gV" width="3.895" height="1.582" x="8.605" y="24.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="iuQeTLb" width="3.469" height="2.844" x="20.988" y="17.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="ihAKguc" width="5.656" height="3.395" x="20.331" y="19.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="im76Uee" width="5.219" height="1.719" x="19.925" y="22.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter><filter id="idYhOWp" width="3.895" height="1.582" x="19.488" y="24.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30023" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lobster" /></template>
<style>
.a9v36geqs {
  stop-color: var(--svg-color--c43d45, #C43D45);
}

.aau6o3x6f {
  d: path("m11.53 18.23l-2.54-.97a4.72 4.72 0 0 1-3.01-4.38V8.27h3v4.61c0 .7.44 1.33 1.09 1.58l2.54.97z");
}

.aia7rmg8o {
  stop-color: var(--svg-color--ed7759, #ED7759);
  stop-opacity: 0;
}

.arc7qbbxg {
  stop-color: var(--svg-color--301a31, #301A31);
}

.b0uho53uq {
  stop-color: var(--svg-color--c3482f, #C3482F);
  stop-opacity: 0;
}

.b69a92b4e {
  stop-color: var(--svg-color--e05553, #E05553);
}

.bb_x3_baq {
  stop-color: var(--svg-color--ce6f73, #CE6F73);
}

.bpvlakyeh {
  stop-color: var(--svg-color--cb3874, #CB3874);
}

.c_pzsqbqv {
  stop-color: var(--svg-color--d9494c, #D9494C);
}

.c5wglx3lq {
  d: path("M14.25 13.38a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.c93cdibfk {
  stop-color: var(--svg-color--ed7562, #ED7562);
}

.ca65gd4ie {
  d: path("M15.97 21.73c-2.93 0-5.34-2.27-5.55-5.15c-.06 1.11.07 2.25.41 3.36l2.53 8.1a2.745 2.745 0 0 0 2.39 1.94c1.28.1 2.44-.69 2.82-1.9l2.54-8.15c.34-1.1.48-2.24.41-3.35a5.56 5.56 0 0 1-5.55 5.15");
}

.ckum5db6o {
  stop-color: var(--svg-color--c95143, #C95143);
}

.coyk0lboz {
  stop-color: var(--svg-color--d84878, #D84878);
}

.d8wo5-bxd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M23.956 18.094c-.25.541-.968 1.718-2.468 1.843");
}

.dhduy4b6b {
  stop-color: var(--svg-color--d9526b, #D9526B);
}

.dnwz-0lce {
  stop-color: var(--svg-color--c1228f, #C1228F);
}

.dppm6ebxf {
  d: path("M7.122 2.58a.43.43 0 0 0-.075.25v5.44h1.578V4.615c0-1.036-.537-1.934-1.252-2.137c-.095-.028-.183.009-.251.102");
}

.dyphehnga {
  d: path("M19.29 11L17.7 9.08c-.43-.51-1.06-.81-1.73-.81s-1.3.3-1.73.81l-1.46 1.77a9.47 9.47 0 0 0-1.95 9.09l2.53 8.1a2.745 2.745 0 0 0 2.39 1.94c1.28.1 2.44-.69 2.82-1.9l2.54-8.15c.98-3.12.26-6.49-1.82-8.93");
}

.eqyjdobxy {
  stop-color: var(--svg-color--c1217f, #C1217F);
}

.f0j6pdcdx {
  stop-color: var(--svg-color--2f2a36, #2F2A36);
}

.f8v85nbvc {
  stop-color: var(--svg-color--cb4471, #CB4471);
  stop-opacity: 0;
}

.f9sa_8yxs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M25.515 19.563c-.453 1.359-2.406 3.187-5.156 2.14");
}

.faiivbb8o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.031 18.094c.25.541.969 1.718 2.469 1.843");
}

.fbtsr8b_u {
  stop-color: var(--svg-color--ec7649, #EC7649);
}

.fd99hlbyi {
  stop-color: var(--svg-color--e86743, #E86743);
}

.fhpn-cc1b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M23.952 18.14c-.198.709-1.168 2.085-3.468 1.86");
}

.ft5dv1b6b {
  fill: none;
}

.gq5jbac-g {
  d: path("M17.47 13.24c.28 0 .5-.22.5-.5V4.49c0-.82.67-1.49 1.49-1.49s1.49.67 1.49 1.49l.01.01c0 .28.22.5.5.5s.5-.22.5-.5l-.01-.01c0-1.37-1.12-2.49-2.49-2.49s-2.49 1.12-2.49 2.49v8.24c0 .28.22.51.5.51");
}

.gv7yz7lik {
  stop-color: var(--svg-color--d7434f, #D7434F);
  stop-opacity: 0;
}

.gwkh3vb5n {
  d: path("M25.612 6.516c.44 0 1.25-.3 1.25-.865V3.133a.478.478 0 0 1 .555-.467c1.427.265 1.985 1.56 1.985 3.065v2.834c0 2.087-1.546 3.777-3.632 3.777h-1.294c-.59 0-.918-.475-.918-1.074V8.407c.009-1.224.839-1.891 2.054-1.891");
}

.gwmp84bzh {
  stop-color: var(--svg-color--d35e41, #D35E41);
  stop-opacity: 0;
}

.h0ewpf04l {
  d: path("M6.353 6.516c-.44 0-1.251-.3-1.251-.865V3.133a.478.478 0 0 0-.555-.467c-1.426.265-1.985 1.56-1.985 3.065v2.834c0 2.087 1.546 3.777 3.632 3.777h1.294c.59 0 .918-.475.918-1.074V8.407c-.009-1.224-.838-1.891-2.053-1.891");
}

.h8h6zobqe {
  stop-color: var(--svg-color--d8664a, #D8664A);
}

.hkzay866c {
  stop-color: var(--svg-color--d1776c, #D1776C);
  stop-opacity: 0;
}

.hoc8v5bfa {
  stop-color: var(--svg-color--d25c3f, #D25C3F);
}

.hrr_37bzt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.219 22.938c.812.921 2.531 1.28 4.469.656");
}

.hucduvbqn {
  stop-color: var(--svg-color--cb5667, #CB5667);
}

.hyqyvobvb {
  stop-color: var(--svg-color--d56166, #D56166);
}

.i95mrsb3d {
  d: path("m13.48 25.3l-2.06 2.06c-.6.6-.6 1.58 0 2.18l.01.01c.6.6 1.58.6 2.18 0l2.06-2.06c.6-.6.6-1.58 0-2.18l-.01-.01c-.61-.6-1.58-.6-2.18 0");
}

.iakgiobxd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M24.874 23c-1.39 1.078-3.14 1.266-4.89.39");
}

.if3rt2bcd {
  stop-color: var(--svg-color--e04e76, #E04E76);
  stop-opacity: 0;
}

.ipjhywbre {
  stop-color: var(--svg-color--ec7558, #EC7558);
}

.ipw8i8lvn {
  stop-color: var(--svg-color--ec7348, #EC7348);
}

.iqske7fva {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M6.375 19.563c.453 1.359 2.406 3.187 5.156 2.14");
}

.ixqtd9bjm {
  d: path("M6.47 6.02h-.36c-.35 0-.62-.28-.62-.62V2.54a.543.543 0 0 0-.63-.53C3.24 2.31 2 3.78 2 5.49v3.22A4.29 4.29 0 0 0 6.29 13h1.47c.67 0 1.22-.54 1.22-1.22V8.53a2.52 2.52 0 0 0-2.51-2.51");
}

.j-gmzlbvu {
  stop-color: var(--svg-color--da5369, #DA5369);
}

.j19w5cbtf {
  stop-color: var(--svg-color--cd3e81, #CD3E81);
}

.jq5s11ztn {
  stop-color: var(--svg-color--d94b5b, #D94B5B);
}

.juu3v0q0g {
  stop-color: var(--svg-color--be2962, #BE2962);
}

.jyoehxvcj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M24.769 22.938c-.813.921-2.531 1.28-4.469.656");
}

.k_m935bak {
  d: path("M24.874 2.58a.43.43 0 0 1 .075.25v5.44h-1.578V4.615c0-1.036.537-1.934 1.252-2.137c.095-.028.183.009.251.102");
}

.k39albcgt {
  d: path("m20.44 18.23l2.54-.97c1.8-.69 3.01-2.45 3.01-4.38V8.27h-3v4.61c0 .7-.44 1.33-1.09 1.58l-2.54.97z");
}

.k6c8iabxn {
  stop-color: var(--svg-color--be363d, #BE363D);
}

.kh6dvkbvz {
  stop-color: var(--svg-color--cb553d, #CB553D);
}

.kl0gndbba {
  stop-color: var(--svg-color--de6652, #DE6652);
}

.kxk7zm8xp {
  stop-color: var(--svg-color--bb2951, #BB2951);
  stop-opacity: 0;
}

.l2-etnbyx {
  stop-color: var(--svg-color--cb363f, #CB363F);
}

.ldg_qk7bv {
  stop-color: var(--svg-color--c64943, #C64943);
}

.lfdtwy12j {
  stop-color: var(--svg-color--d45158, #D45158);
}

.lv2sqnbzy {
  stop-color: var(--svg-color--da5672, #DA5672);
}

.lvi8a9bcs {
  d: path("M25.5 6.02h.36c.35 0 .62-.28.62-.62V2.54a.543.543 0 0 1 .63-.53c1.62.3 2.86 1.77 2.86 3.48v3.22A4.29 4.29 0 0 1 25.68 13h-1.47c-.67 0-1.22-.54-1.22-1.22V8.53c0-1.39 1.12-2.51 2.51-2.51");
}

.m-27yccxb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M7.938 18.14c.197.709 1.168 2.085 3.468 1.86");
}

.n-6fdzcag {
  stop-color: var(--svg-color--cd5062, #CD5062);
  stop-opacity: 0;
}

.n4og0_7kx {
  stop-color: var(--svg-color--be3266, #BE3266);
}

.ng2qtmh1b {
  stop-color: var(--svg-color--ea727c, #EA727C);
}

.nmw17-wek {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M8.906 25.64c.86.25 2.547.344 3.992-1.266");
}

.nz5yx22bi {
  stop-color: var(--svg-color--c82f64, #C82F64);
}

.o3lo83bkk {
  stop-color: var(--svg-color--d0335f, #D0335F);
}

.ob29sdp9n {
  stop-color: var(--svg-color--d9888b, #D9888B);
}

.oi-vo5bap {
  d: path("M15.97 25.43c-1.54 0-2.92-.62-3.93-1.63l1.32 4.24a2.745 2.745 0 0 0 2.39 1.94c1.28.1 2.44-.69 2.82-1.9l1.34-4.28a5.58 5.58 0 0 1-3.94 1.63");
}

.oig1098cc {
  stop-color: var(--svg-color--c76c70, #C76C70);
  stop-opacity: 0;
}

.oxog_ebjd {
  stop-color: var(--svg-color--ca376a, #CA376A);
}

.p3sbsrblf {
  stop-color: var(--svg-color--d5434d, #D5434D);
}

.pb4av_b-t {
  stop-color: var(--svg-color--bb373c, #BB373C);
  stop-opacity: 0;
}

.pp0wq78pw {
  d: path("m13.752 25.79l-1.69 1.688c-.491.492-.751 1.19-.26 1.681l.009.008c.492.492 1.196.248 1.688-.244l1.688-1.689c.492-.492.592-1.051.1-1.543l-.008-.008c-.5-.492-1.036-.386-1.527.106");
}

.q73dyibzb {
  stop-color: var(--svg-color--e2503a, #E2503A);
}

.q9i20euwg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.5 19.594c.313.906 1.781 2.812 4.656 2.312");
}

.qoz2cxbtf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.488 4.531c-.053-.687-.47-2.062-2-2.062c-1.325 0-1.97 1.25-1.97 2.062v4.625");
}

.qqakkz7ui {
  fill: var(--svg-color--e2566b, #E2566B);
  d: path("m18.271 25.79l1.69 1.688c.491.492.75 1.19.259 1.681l-.008.008c-.492.492-1.196.248-1.688-.244l-1.689-1.689c-.492-.492-.592-1.051-.1-1.543l.009-.008c.5-.492 1.035-.386 1.527.106");
}

.qum_a2nji {
  stop-color: var(--svg-color--e36446, #E36446);
}

.qx072acpa {
  d: path("M14.46 13.24c-.28 0-.5-.22-.5-.5V4.49a1.496 1.496 0 0 0-2.99 0l.01.01c0 .28-.22.5-.5.5s-.5-.22-.5-.5l-.01-.01c0-1.37 1.12-2.49 2.5-2.49a2.49 2.49 0 0 1 2.49 2.49v8.24c0 .28-.23.51-.5.51");
}

.r8ylniejx {
  stop-color: var(--svg-color--ec7469, #EC7469);
}

.rbctgzbis {
  stop-color: var(--svg-color--cd4b69, #CD4B69);
}

.rbycsmgua {
  fill: var(--svg-color--d9516d, #D9516D);
  d: path("m20.44 18.23l2.54-.97c1.8-.69 3.01-2.45 3.01-4.38V8.27h-3v4.61c0 .7-.44 1.33-1.09 1.58l-2.54.97z");
}

.rk0y-kbzi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M22.984 25.64c-.86.25-2.547.344-3.992-1.266");
}

.s-4qrqbzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.488 19.594c-.313.906-1.782 2.812-4.657 2.312");
}

.s-jx-u4ys {
  stop-color: var(--svg-color--cc7376, #CC7376);
  stop-opacity: 0;
}

.s-r5klbqh {
  stop-color: var(--svg-color--cf4642, #CF4642);
}

.s5j8a88ej {
  stop-color: var(--svg-color--c53e46, #C53E46);
  stop-opacity: 0;
}

.t0i0pzbgu {
  stop-color: var(--svg-color--c84d32, #C84D32);
}

.t3gv8nb7b {
  stop-color: var(--svg-color--c4307d, #C4307D);
}

.tbodwx39q {
  stop-color: var(--svg-color--ce4c6d, #CE4C6D);
  stop-opacity: 0;
}

.tcohyrw_p {
  stop-color: var(--svg-color--cc3181, #CC3181);
}

.tejb0b7uv {
  d: path("M25.2 2.12c.07.07.12.17.12.28v5.88H23V4.32c0-1.12.79-2.09 1.84-2.31c.13-.03.27.01.36.11");
}

.tksr4bcab {
  stop-color: var(--svg-color--d45a3f, #D45A3F);
}

.twfzesbvj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.98 25.563c.895.406 2.239.343 3.145-.594");
}

.txzt4fbie {
  stop-color: var(--svg-color--bb2e45, #BB2E45);
  stop-opacity: 0;
}

.u1-f47b8g {
  stop-color: var(--svg-color--ef7d62, #EF7D62);
}

.ubn1qtb6q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.008 25.563c-.895.406-2.24.343-3.145-.594");
}

.ulty2wr-s {
  stop-color: var(--svg-color--c74a44, #C74A44);
  stop-opacity: 0;
}

.un2r7bzjs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.531 4.531c.052-.687.469-2.062 2-2.062c1.325 0 1.969 1.25 1.969 2.062v4.625");
}

.uremmztjm {
  stop-color: var(--svg-color--db5e69, #DB5E69);
}

.uuqgiwben {
  stop-color: var(--svg-color--c2472d, #C2472D);
}

.vr3g63rah {
  stop-color: var(--svg-color--ed7067, #ED7067);
}

.vtwedfbeg {
  stop-color: var(--svg-color--4e4c4f, #4E4C4F);
}

.vyvn4ib4r {
  stop-color: var(--svg-color--ce575c, #CE575C);
}

.w84f_kbhv {
  stop-color: var(--svg-color--f37b64, #F37B64);
}

.whmtv8gxq {
  d: path("m18.46 25.3l2.06 2.06c.6.6.6 1.58 0 2.18l-.01.01c-.6.6-1.58.6-2.18 0l-2.06-2.06c-.6-.6-.6-1.58 0-2.18l.01-.01c.6-.6 1.58-.6 2.18 0");
}

.wlp_yfbqf {
  stop-color: var(--svg-color--ce573c, #CE573C);
  stop-opacity: 0;
}

.x023d6bvk {
  fill: var(--svg-color--cb4e6b, #CB4E6B);
  d: path("m18.271 25.79l1.69 1.688c.491.492.75 1.19.259 1.681l-.008.008c-.492.492-1.196.248-1.688-.244l-1.689-1.689c-.492-.492-.592-1.051-.1-1.543l.009-.008c.5-.492 1.035-.386 1.527.106");
}

.x0yvoccsb {
  stop-color: var(--svg-color--cf5125, #CF5125);
}

.x14rbd3sf {
  stop-color: var(--svg-color--cd5858, #CD5858);
}

.y_q02vkbm {
  stop-color: var(--svg-color--e8704e, #E8704E);
  stop-opacity: 0;
}

.y-olwtbxr {
  d: path("M17.69 13.38a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.yjdv2nbqt {
  stop-color: var(--svg-color--d56665, #D56665);
}

.yxxmf3mab {
  d: path("M6.76 2.12c-.07.07-.11.17-.11.27v5.88h2.32V4.32c0-1.12-.79-2.09-1.84-2.31a.39.39 0 0 0-.37.11");
}

.yz56m5b-n {
  stop-color: var(--svg-color--bb294c, #BB294C);
}

.z-u4zdbet {
  stop-color: var(--svg-color--c9445f, #C9445F);
}

.z9q01ubye {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M7.016 23c1.39 1.078 3.14 1.266 4.89.39");
}

.zb--ncckg {
  fill: var(--svg-color--cb4e6b, #CB4E6B);
  d: path("m13.752 25.79l-1.69 1.688c-.491.492-.751 1.19-.26 1.681l.009.008c.492.492 1.196.248 1.688-.244l1.688-1.689c.492-.492.592-1.051.1-1.543l-.008-.008c-.5-.492-1.036-.386-1.527.106");
}

.zoyzd4bus {
  stop-color: var(--svg-color--d1776c, #D1776C);
}

</style>
