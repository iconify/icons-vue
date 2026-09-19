<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#i67LovW)"><path fill="url(#i6aJFZY)" class="ocwvddb0y"/><path fill="url(#izDA0dI)" class="ocwvddb0y"/></g><g filter="url(#iG97DSb)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#iAH5icF)"><ellipse transform="rotate(-40.534 9.937 22.244)" class="a_d5m7-5r"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#iwemcjc)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.955 40.983)" class="tto44ccna"/><g filter="url(#iytnFrZ)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#ie86Gud)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iO1qq0c)"><circle class="wfn54lnxd"/></g><g filter="url(#ij44tOe)"><circle class="a1tpsrb8u"/></g><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><path fill="url(#iev6V6k)" class="purq57pgo"/><path fill="url(#ibk36Tc)" class="purq57pgo"/><path fill="url(#iviBr0b)" class="de2fbu6oj"/><path fill="url(#ivNS6Sb)" class="de2fbu6oj"/><g filter="url(#ii5Jbbb)"><path fill="url(#icMTaqc)" class="q_8-edbbw"/></g><path fill="url(#iKPbcBb)" class="q_8-edbbw"/><path fill="url(#iQ7OrqH)" class="q_8-edbbw"/><path fill="url(#iErJ6yd)" class="q_8-edbbw"/><path fill="url(#iEN2kce)" class="q_8-edbbw"/><g filter="url(#iBVduTc)"><path class="b1y6yg_hm"/></g><g filter="url(#il5izgc)"><path fill="url(#i6s5SKc)" class="jnalq1b2q"/><path fill="url(#idUX2ue)" class="jnalq1b2q"/><path fill="url(#iYtk9Nd)" class="jnalq1b2q"/></g><g filter="url(#imflske)"><path fill="url(#i0Cl3Ed)" class="c4igjqbks"/></g><g filter="url(#imQoZUH)"><path stroke="url(#iS0JIRb)" class="diam-ir6u"/></g><path fill="url(#iqPqF7d)" class="m11-c_2nv"/><path class="zj5qjebes"/><path fill="url(#iflLz8d)" class="xn0vgvbrk"/><path class="egnx42bgo"/><g filter="url(#iKpYxnb)"><path class="m19bmzbka"/><path fill="url(#iir2bcl)" class="zxyhyd42q"/></g><g filter="url(#igNqXlZ)"><path fill="url(#i9YZdWX)" class="xf4fqt6mt"/></g><path class="t4xrl4bsb"/><path fill="url(#irMSzCe)" class="lmqr1f2_b"/><path class="dwuyjbbcl"/><g filter="url(#iWEFSpe)"><path fill="url(#iCCRrel)" class="ihnar8byd"/></g><g filter="url(#iORj0Hb)"><ellipse transform="rotate(-27.914 13.5 14.41)" class="uqrnp29vx"/><ellipse fill="url(#iASWxBe)" transform="rotate(-27.914 13.5 14.41)" class="hm5e9d16y"/></g><path fill="url(#i0J2zic)" class="st5ia9s2v"/><path fill="url(#i1wwycH)" class="st5ia9s2v"/><path fill="url(#iZMUw0c)" class="st5ia9s2v"/><path fill="url(#isBZMre)" class="f3mul7xhg"/><path fill="url(#iQTkrMA)" class="f3mul7xhg"/><g filter="url(#iTLOR3c)"><path class="qv3y0q56w"/></g><g filter="url(#iiC4U3d)"><path class="t1in2hb1l"/></g><g filter="url(#ilACmIe)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#i5LS0ld)"><path fill="url(#iEi7LFc)" clip-rule="evenodd" class="w1ctn3wss"/><path fill="url(#ir8abXE)" clip-rule="evenodd" class="w1ctn3wss"/><path fill="url(#iyBJvOb)" clip-rule="evenodd" class="w1ctn3wss"/></g><defs><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="ie86Gud" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="fmz42zp1p"/><stop offset="1" class="gumxcfc4t"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iev6V6k" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 4.262 16.707)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="ibk36Tc" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -5.978 28.727)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iviBr0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.406 16.48)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="ivNS6Sb" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -5.743 15.812)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="icMTaqc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.11408 0 0 -10.8157 19.647 15.423)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iKPbcBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.84375 11.0625 0 15.76 21.99)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iQ7OrqH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.862 14.242)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iErJ6yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.442 13.83)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iS0JIRb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 23.381 -3.297)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iqPqF7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.953 18.962)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iflLz8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2265 1.34466 0 18.135 15.302)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="b9-6lxb8p"/><stop offset="1" class="lwsqinbxc"/></radialGradient><radialGradient id="iir2bcl" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.526 2.91)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irMSzCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.22656 1.34473 0 13.771 15.302)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="b9-6lxb8p"/><stop offset="1" class="lwsqinbxc"/></radialGradient><radialGradient id="iASWxBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.484 14.725)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1wwycH" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.57 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iZMUw0c" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.93 15.065)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iQTkrMA" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.682 11.73)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="i67LovW" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2834"/></filter><filter id="iG97DSb" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2834" result="effect2_innerShadow_4002_2834"/></filter><filter id="iAH5icF" width="2.189" height="2.153" x="8.842" y="21.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".25"/></filter><filter id="iwemcjc" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".125"/></filter><filter id="iytnFrZ" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2834" result="effect2_innerShadow_4002_2834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2834" result="effect3_innerShadow_4002_2834"/></filter><filter id="iO1qq0c" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".25"/></filter><filter id="ij44tOe" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".25"/></filter><filter id="ii5Jbbb" width="11.22" height="13.042" x="10.39" y="8.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2834" result="effect2_innerShadow_4002_2834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2834" result="effect3_innerShadow_4002_2834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.501961 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_4002_2834" result="effect4_innerShadow_4002_2834"/></filter><filter id="iBVduTc" width="3.877" height="4.9" x="13.807" y="13.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".5"/></filter><filter id="il5izgc" width="2.077" height="3.1" x="14.914" y="14.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".05"/></filter><filter id="imflske" width="2.077" height="3.1" x="14.914" y="14.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".05"/></filter><filter id="imQoZUH" width="3.718" height="1.573" x="14.094" y="17.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".05"/></filter><filter id="iKpYxnb" width=".787" height=".696" x="17.401" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".05"/></filter><filter id="igNqXlZ" width=".891" height=".913" x="18.241" y="14.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".1"/></filter><filter id="iWEFSpe" width=".986" height="1.04" x="13.798" y="14.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".1"/></filter><filter id="iORj0Hb" width=".913" height=".705" x="13.043" y="14.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".05"/></filter><filter id="iTLOR3c" width="1.329" height="2.379" x="9.92" y="13.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".125"/></filter><filter id="iiC4U3d" width="1.447" height="2.403" x="20.665" y="13.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2834" stdDeviation=".125"/></filter><filter id="ilACmIe" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2834"/></filter><filter id="i5LS0ld" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2834"/></filter><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iEN2kce" x1="16" x2="16" y1="14.021" y2="15.521" gradientUnits="userSpaceOnUse"><stop class="fvnywfb0n"/><stop offset="1" class="f5sckbn0k"/></linearGradient><linearGradient id="i6s5SKc" x1="15.953" x2="16.808" y1="16.251" y2="16.251" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="idUX2ue" x1="14.88" x2="15.954" y1="16.096" y2="16.155" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iYtk9Nd" x1="15.953" x2="15.953" y1="16.65" y2="17.502" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i0Cl3Ed" x1="15.953" x2="15.953" y1="14.278" y2="15.443" gradientUnits="userSpaceOnUse"><stop class="f2y-9hbod"/><stop offset="1" class="eh5vg-wth"/></linearGradient><linearGradient id="i9YZdWX" x1="18.913" x2="18.599" y1="14.56" y2="14.754" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCCRrel" x1="14.515" x2="14.201" y1="14.56" y2="14.754" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0J2zic" x1="22.389" x2="21.182" y1="14.587" y2="16.763" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="isBZMre" x1="10.103" x2="11.562" y1="15.291" y2="15.164" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iEi7LFc" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="haq-yyb5a"/><stop offset="1" class="fnv2cqusr"/></linearGradient><linearGradient id="ir8abXE" x1="15.94" x2="15.94" y1="13.927" y2="15.458" gradientUnits="userSpaceOnUse"><stop class="aa_k4sbxt"/><stop offset="1" class="t9tvqlbrf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:guard" /></template>
<style>
.a_d5m7-5r {
  cx: 9.937px;
  cy: 22.244px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.aa_k4sbxt {
  stop-color: var(--svg-color--cc9bd2, #CC9BD2);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b1y6yg_hm {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.467 14.904l-.635 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.53-1.838c-.115-.407-.543-.407-.662 0");
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.b9-6lxb8p {
  stop-color: var(--svg-color--784c4d, #784C4D);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c4igjqbks {
  d: path("m15.57 14.584l-.53 1.838c-.11.378.151.756.52.756h.786c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.de2fbu6oj {
  d: path("M11.092 16.673a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.diam-ir6u {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.602 17.924c.39.203.855.32 1.351.32c.5 0 .96-.117 1.35-.32h.001a.23.23 0 0 1 .271.044a.214.214 0 0 1 .024.273m-2.997-.317l2.934.276m-2.934-.276a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27m.295-.317l-.232.276m3.229.041l-.063-.041m.063.041l-.063-.041m.063.041a1.97 1.97 0 0 1-1.646.88a1.97 1.97 0 0 1-1.646-.88m3.23-.041a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.063.042h.001l.062-.042m-.063.042v-.001l.063-.041");
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.dwuyjbbcl {
  fill: var(--svg-color--000, #000);
  d: path("M14.28 14.922a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.454.747h.904a.5.5 0 0 0 .061-.235");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.egnx42bgo {
  fill: var(--svg-color--000, #000);
  d: path("M17.626 14.922a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .454.747h-.904a.46.46 0 0 1-.061-.236");
}

.eh5vg-wth {
  stop-color: var(--svg-color--f0972a, #F0972A);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f2y-9hbod {
  stop-color: var(--svg-color--f0972a, #F0972A);
}

.f3mul7xhg {
  d: path("M10.899 13.564a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.f5sckbn0k {
  stop-color: var(--svg-color--f7aa2d, #F7AA2D);
  stop-opacity: 0;
}

.fmz42zp1p {
  stop-color: var(--svg-color--f28235, #F28235);
}

.fnv2cqusr {
  stop-color: var(--svg-color--e3bbe0, #E3BBE0);
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.fvnywfb0n {
  stop-color: var(--svg-color--ea8526, #EA8526);
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gumxcfc4t {
  stop-color: var(--svg-color--fdac39, #FDAC39);
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gw4u-ub3u {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.004-.008l.02-.04c.061-.121.152-.298-.02-.578c-.193-.313-.375-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.07-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.066-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.452-.58c.046-.215.132-.502.293-.663a1.06 1.06 0 0 1 .791-.3c.257.007.535-.03.752-.254c.217-.225.458-.413.699-.453s.471.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112c.098 0 .214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.484-.184.725-.144s.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.246.448.292.663c.088.417.243.491.452.58l.02.008c.219.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.117.86c.33.641.193.955 0 1.268c-.171.28-.081.457-.02.577l.02.041l.005.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.gx_0zqbtq {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.099px;
  rx: 1.969px;
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.haq-yyb5a {
  stop-color: var(--svg-color--f6d3f9, #F6D3F9);
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hm5e9d16y {
  cx: 13.5px;
  cy: 14.411px;
  rx: 0.39px;
  ry: 0.197px;
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ihnar8byd {
  d: path("M14.584 14.817c0-.289-.234-.48-.297-.539l-.289.279l.178.361z");
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jnalq1b2q {
  d: path("m15.57 14.708l-.53 1.838c-.11.378.151.757.52.757h.786c.369 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmqr1f2_b {
  d: path("M13.769 14.03a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.lwsqinbxc {
  stop-color: var(--svg-color--543235, #543235);
}

.m11-c_2nv {
  d: path("M15.953 18.32c-.508 0-.985-.12-1.385-.33c-.137-.069-.285.085-.198.21c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.m19bmzbka {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.071 14.218c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.ocwvddb0y {
  d: path("M11.926 20.161c-1.364.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .704.02a12.3 12.3 0 0 1 3.107-1.857z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.purq57pgo {
  d: path("M20.814 16.673c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.019a4.1 4.1 0 0 0 .346-1.18z");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q_8-edbbw {
  d: path("M11.128 18.188a3.916 3.916 0 0 0 3.886 3.405H16.9a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qv3y0q56w {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.916 14.225a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.st5ia9s2v {
  d: path("M20.875 16.763q.1-1.596.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.sy7gbya4q {
  d: path("M22.942 29.911h3.63a9.98 9.98 0 0 0-3.63-7.355z");
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.t1in2hb1l {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.915 16.113q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.t4xrl4bsb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.562 13.758c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.t9tvqlbrf {
  stop-color: var(--svg-color--e5bde2, #E5BDE2);
  stop-opacity: 0;
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.uqrnp29vx {
  cx: 13.5px;
  cy: 14.411px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.w1ctn3wss {
  fill-rule: evenodd;
  d: path("m10.5 14.156l.12 3.518c.082 2.424 2.07 4.378 4.497 4.378h1.677c2.44 0 4.435-1.976 4.498-4.416l.09-3.48h-.909l-.12 3.48c-.049 1.898-1.662 3.486-3.56 3.486h-1.676c-1.887 0-3.489-1.597-3.553-3.482l-.09-3.485z");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wfn54lnxd {
  cx: 17.439px;
  cy: 25.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xf4fqt6mt {
  d: path("M18.932 14.804a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xn0vgvbrk {
  d: path("M18.137 14.03a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zj5qjebes {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.344 13.758c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.zxyhyd42q {
  d: path("M18.071 14.218c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

</style>
