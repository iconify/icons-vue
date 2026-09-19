<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#i0FTBQb)"><path fill="url(#i9I7f3b)" class="sl2x5tbig"/><path fill="url(#isUJOpd)" class="sl2x5tbig"/><path fill="url(#iLDpxsd)" class="sl2x5tbig"/><path fill="url(#iL3lDUd)" class="sl2x5tbig"/></g><g filter="url(#i6fR8xs)"><path fill="url(#ivoMlrc)" class="sdl6__ybo"/></g><g filter="url(#i0OwSQb)"><path stroke="url(#iPUY2Dd)" class="fhae83b5d"/><path stroke="url(#iHThoic)" class="fhae83b5d"/><path stroke="url(#iwDbrxb)" class="fhae83b5d"/><path stroke="url(#ijpVHGe)" class="fhae83b5d"/><path stroke="url(#iUcBMMe)" class="fhae83b5d"/></g><path fill="url(#iKcklGz)" class="x6ria4bvz"/><path fill="url(#i2TqVqR)" class="x6ria4bvz"/><path fill="url(#i80seCe)" class="x6ria4bvz"/><g filter="url(#i4krlfb)"><path stroke="url(#ih0YKeb)" class="uhnha0ihn"/></g><g filter="url(#iyqeAtC)"><path fill="url(#iu4wNuc)" class="ka7p-4bra"/><path fill="url(#ieyipSb)" class="ka7p-4bra"/><path fill="url(#ih9twjb)" class="ka7p-4bra"/><path fill="url(#iIZQ2Pc)" class="ka7p-4bra"/><path fill="url(#iqlbBfc)" class="ka7p-4bra"/><path fill="url(#idkny1Z)" class="ka7p-4bra"/></g><g filter="url(#ioJyX7c)"><path class="dl2t2ijsi"/></g><g filter="url(#iM44W3X)"><rect class="ip4uevb4p"/></g><g filter="url(#i1GvGwj)"><ellipse transform="rotate(36.373 14.266 6.002)" class="ab51sacat"/></g><g filter="url(#iMsRFUb)"><circle fill="url(#il2eDnc)" class="gn2d_ubbz"/></g><path fill="url(#iR5Qrsb)" class="na2qm1bnp"/><g filter="url(#itAop1l)"><path stroke="url(#iaP3hvd)" class="q7typtk1k"/></g><g filter="url(#iNdJPkd)"><path stroke="url(#iqs25zc)" class="i-j138bls"/><path stroke="url(#it1Ivdq)" class="i-j138bls"/><path stroke="url(#iF6cIDc)" class="i-j138bls"/><path stroke="url(#il7lW5c)" class="i-j138bls"/></g><g filter="url(#inS7zHc)"><path fill="url(#issWwxb)" class="kjwxy6buy"/><path fill="url(#ieLncYd)" class="kjwxy6buy"/><path fill="url(#ijX8b2d)" class="kjwxy6buy"/><path fill="url(#iNm2qme)" class="kjwxy6buy"/><path fill="url(#iAfYArd)" class="kjwxy6buy"/></g><g filter="url(#iidJiOe)"><path stroke="url(#iWDwD9d)" class="uhqpwabva"/></g><g filter="url(#iMrgTgk)"><ellipse class="guuv_8bhg"/></g><g filter="url(#iHwbOjc)"><ellipse class="lkuzhebbb"/></g><g filter="url(#ianDmmc)"><ellipse transform="rotate(37.529 12.262 4.3)" class="nenc74bdb"/></g><g filter="url(#iRhqORb)"><ellipse transform="rotate(43.56 4.358 10.373)" class="wtmgjacnt"/></g><g filter="url(#iPlT2lc)"><ellipse transform="rotate(138.521 5.16 22.894)" class="kgq8hfb8c"/></g><g filter="url(#i7sUHad)"><ellipse class="tl8enjk5c"/></g><path fill="url(#iJ7x2rb)" class="m64bvt1kw"/><path fill="url(#iYJFnMc)" class="m64bvt1kw"/><path fill="url(#i7QYdZc)" class="m64bvt1kw"/><path fill="url(#iSrDLzi)" class="pp4n1s4os"/><path fill="url(#ilXSsDb)" class="pp4n1s4os"/><g filter="url(#ic175Fr)"><path fill="url(#iZYfD8X)" class="kzwn3w_rw"/></g><path fill="url(#io89Dhf)" class="ggvp6bbze"/><path fill="url(#iWK0g2R)" class="ggvp6bbze"/><g filter="url(#isr9ure)"><path fill="url(#i2bnefd)" class="wjwh01fhd"/></g><path fill="url(#i1qjFdc)" class="fen5pxeqo"/><path fill="url(#iDstzWA)" class="x4n1t1bnt"/><path fill="url(#im51Mwd)" class="x4n1t1bnt"/><path fill="url(#iUp19xb)" class="ls3b9954k"/><path fill="url(#ijj7qXb)" class="ls3b9954k"/><g filter="url(#i2Sn7Sc)"><path fill="url(#i4kduJe)" class="okz-aacqg"/><path fill="url(#iAVPMyd)" class="okz-aacqg"/></g><path fill="url(#iQNS1cb)" class="j0x5bdbhe"/><path fill="url(#i7duO0d)" class="j0x5bdbhe"/><g filter="url(#i0iTWed)"><path fill="url(#iQ1Yvec)" class="e_1gj49qa"/><path fill="url(#iJwmvUd)" class="e_1gj49qa"/></g><g filter="url(#ifQQUDd)"><path fill="url(#iMk1fKc)" class="lc91jtbpj"/><path fill="url(#iuEKlzb)" class="lc91jtbpj"/></g><g filter="url(#imkxxZc)"><path stroke="url(#iblYjlb)" class="qpp1fqbcr"/></g><g filter="url(#iBhhDoe)"><path stroke="url(#i962Smb)" class="otc1a0b7k"/></g><g filter="url(#i3vaktc)"><ellipse transform="rotate(-45 19.531 4.457)" class="vi5372q9m"/></g><path fill="url(#iS4Vjub)" class="vjdzhnb0d"/><path fill="url(#iblY3kd)" class="vjdzhnb0d"/><path fill="url(#i0eAcoe)" class="vjdzhnb0d"/><g filter="url(#irPJaoe)"><path class="h-m3dib0s"/></g><g filter="url(#i1doqGG)"><path stroke="url(#iAGP6Ad)" class="v2wyrho8q"/></g><path fill="url(#iYtnvAe)" class="n-jixqb4r"/><g filter="url(#iS6oZPn)"><path stroke="url(#iFbb0sd)" class="p840u1f_i"/></g><g filter="url(#iLbdL0J)"><path class="wy2yzchau"/></g><g filter="url(#iMTT2gb)"><path class="o-vz963lt"/></g></g><defs><linearGradient id="i9I7f3b" x1="20.75" x2="27.313" y1="15.637" y2="6.012" gradientUnits="userSpaceOnUse"><stop class="wmh6jhb_b"/><stop offset="1" class="jh_n68r6e"/></linearGradient><linearGradient id="ivoMlrc" x1="27.563" x2="27.563" y1="6.355" y2="14.855" gradientUnits="userSpaceOnUse"><stop class="iv2v15bau"/><stop offset="1" class="w1l4wl4lo"/></linearGradient><linearGradient id="iKcklGz" x1="23.375" x2="27" y1="16.012" y2="10.637" gradientUnits="userSpaceOnUse"><stop class="lj_d4dboj"/><stop offset="1" class="xjt_u1buz"/></linearGradient><linearGradient id="i2TqVqR" x1="23.734" x2="23.734" y1="16.105" y2="15.809" gradientUnits="userSpaceOnUse"><stop class="ca4k7zb1j"/><stop offset="1" class="x7th1qq_j"/></linearGradient><linearGradient id="iu4wNuc" x1="12.01" x2="12.01" y1="30" y2="4.875" gradientUnits="userSpaceOnUse"><stop class="r-5bdgbtr"/><stop offset="1" class="izta7ibph"/></linearGradient><linearGradient id="ieyipSb" x1="17.072" x2="17.135" y1="30.5" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="fz0chvzue"/><stop offset="1" class="gl5c37tng"/></linearGradient><linearGradient id="iqlbBfc" x1=".813" x2="6" y1="20.824" y2="20.824" gradientUnits="userSpaceOnUse"><stop class="mmiff3blk"/><stop offset="1" class="rbo_s-jjr"/></linearGradient><linearGradient id="iR5Qrsb" x1="17.625" x2="17.625" y1="7.699" y2="29.699" gradientUnits="userSpaceOnUse"><stop class="zwza16bcb"/><stop offset="1" class="lux5dlb5d"/></linearGradient><linearGradient id="iaP3hvd" x1="18.391" x2="20.195" y1="8.515" y2="8.681" gradientUnits="userSpaceOnUse"><stop class="ro_5gddxj"/><stop offset="1" class="lv4qp2-ew"/></linearGradient><linearGradient id="iqs25zc" x1="6.115" x2="9.112" y1="21.574" y2="18.901" gradientUnits="userSpaceOnUse"><stop class="epjbasbnm"/><stop offset="1" class="mjodvub5d"/></linearGradient><linearGradient id="issWwxb" x1="11.876" x2="11.876" y1="14.465" y2="29.793" gradientUnits="userSpaceOnUse"><stop class="xdwx347wr"/><stop offset="1" class="bklq3prpk"/></linearGradient><linearGradient id="ieLncYd" x1="14.141" x2="13.844" y1="16.824" y2="16.824" gradientUnits="userSpaceOnUse"><stop class="lz315bcby"/><stop offset="1" class="oxtivy4zd"/></linearGradient><linearGradient id="iWDwD9d" x1="13.391" x2="15.195" y1="8.515" y2="8.681" gradientUnits="userSpaceOnUse"><stop class="l3fx-cchf"/><stop offset="1" class="lv4qp2-ew"/></linearGradient><linearGradient id="iJ7x2rb" x1="26.317" x2="27.613" y1="15.725" y2="17.022" gradientUnits="userSpaceOnUse"><stop class="pno2nxw-q"/><stop offset="1" class="jomfc9b8f"/></linearGradient><linearGradient id="i7QYdZc" x1="26.836" x2="27.163" y1="16.652" y2="16.308" gradientUnits="userSpaceOnUse"><stop class="hd9pe2bmk"/><stop offset="1" class="rep9lgbin"/></linearGradient><linearGradient id="iSrDLzi" x1="25.71" x2="24.322" y1="7.59" y2="6.127" gradientUnits="userSpaceOnUse"><stop class="jgr65gdmw"/><stop offset="1" class="mr-h662wk"/></linearGradient><linearGradient id="ilXSsDb" x1="24.477" x2="24.85" y1="7.371" y2="7.066" gradientUnits="userSpaceOnUse"><stop class="e27u0yb7u"/><stop offset="1" class="pmnn8bcah"/></linearGradient><linearGradient id="iZYfD8X" x1="3.142" x2="4.557" y1="9.153" y2="10.568" gradientUnits="userSpaceOnUse"><stop class="hwii8_bof"/><stop offset="1" class="lrxnavxra"/></linearGradient><linearGradient id="io89Dhf" x1="8.867" x2="7.453" y1="14.149" y2="15.563" gradientUnits="userSpaceOnUse"><stop class="xi5a2nbde"/><stop offset="1" class="yt-4_jbks"/></linearGradient><linearGradient id="i2bnefd" x1="4.145" x2="5.559" y1="23.877" y2="22.463" gradientUnits="userSpaceOnUse"><stop class="ip-9jqbcn"/><stop offset="1" class="qqjuhk71j"/></linearGradient><linearGradient id="i1qjFdc" x1="10" x2="11.711" y1="26.355" y2="26.355" gradientUnits="userSpaceOnUse"><stop class="a3-58qdsq"/><stop offset="1" class="gg0f93b8q"/><stop offset="1" class="cn_sc0vcm"/></linearGradient><linearGradient id="iDstzWA" x1="22" x2="20.32" y1="24.512" y2="24.512" gradientUnits="userSpaceOnUse"><stop class="k34ypyjwp"/><stop offset="1" class="gg0f93b8q"/></linearGradient><linearGradient id="iUp19xb" x1="18.516" x2="19.96" y1="21.996" y2="19.558" gradientUnits="userSpaceOnUse"><stop class="bclz0xn3o"/><stop offset="1" class="pgg4nwb8e"/></linearGradient><linearGradient id="i4kduJe" x1="14.141" x2="12.359" y1="17.324" y2="15.465" gradientUnits="userSpaceOnUse"><stop class="bclz0xn3o"/><stop offset="1" class="pgg4nwb8e"/></linearGradient><linearGradient id="iAVPMyd" x1="12.04" x2="12.766" y1="15.302" y2="16.074" gradientUnits="userSpaceOnUse"><stop class="phya_shmn"/><stop offset="1" class="bd2b-8b4v"/></linearGradient><linearGradient id="iQNS1cb" x1="18" x2="20" y1="11.512" y2="11.512" gradientUnits="userSpaceOnUse"><stop class="osu878trg"/><stop offset="1" class="rrksbku7e"/></linearGradient><linearGradient id="iQ1Yvec" x1="10" x2="12" y1="9.512" y2="9.512" gradientUnits="userSpaceOnUse"><stop class="s-zkkvaky"/><stop offset="1" class="qug8vqbjp"/></linearGradient><linearGradient id="iMk1fKc" x1="12.67" x2="11.646" y1="4.235" y2="2.82" gradientUnits="userSpaceOnUse"><stop class="bclz0xn3o"/><stop offset="1" class="pgg4nwb8e"/></linearGradient><linearGradient id="iuEKlzb" x1="10.99" x2="11.405" y1="3.012" y2="3.596" gradientUnits="userSpaceOnUse"><stop class="phya_shmn"/><stop offset="1" class="bd2b-8b4v"/></linearGradient><linearGradient id="iblYjlb" x1="27.68" x2="26.719" y1="16.504" y2="15.582" gradientUnits="userSpaceOnUse"><stop class="rt1s6ex_z"/><stop offset="1" class="dv1opcdad"/></linearGradient><linearGradient id="i962Smb" x1="25.391" x2="24.459" y1="7.199" y2="6.285" gradientUnits="userSpaceOnUse"><stop class="oy0jjgbly"/><stop offset="1" class="iecbuu4_i"/></linearGradient><linearGradient id="iS4Vjub" x1="20.866" x2="19.452" y1="3.152" y2="4.566" gradientUnits="userSpaceOnUse"><stop class="ygcq6___g"/><stop offset="1" class="pr1bl8nwg"/></linearGradient><linearGradient id="iblY3kd" x1="19.742" x2="20.023" y1="3.441" y2="3.723" gradientUnits="userSpaceOnUse"><stop class="n7n8j7bun"/><stop offset="1" class="mj1634v-j"/></linearGradient><linearGradient id="iAGP6Ad" x1="5.344" x2="10.072" y1="11.927" y2="18.724" gradientUnits="userSpaceOnUse"><stop class="ro_5gddxj"/><stop offset="1" class="lv4qp2-ew"/></linearGradient><linearGradient id="iFbb0sd" x1="7.813" x2="11.875" y1="14.23" y2="24.074" gradientUnits="userSpaceOnUse"><stop class="rmp-xs0ph"/><stop offset="1" class="xm3j-pb_d"/></linearGradient><filter id="i0FTBQb" width="13.83" height="12" x="15.57" y="6.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.831373 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="i6fR8xs" width="3.813" height="8.025" x="25.656" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".5"/></filter><filter id="i0OwSQb" width="6.697" height="7.556" x="20.703" y="8.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".1"/></filter><filter id="i4krlfb" width="5.438" height="6.281" x="21.438" y="9.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="iyqeAtC" width="18.7" height="28" x="3.01" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".7"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.858824 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="ioJyX7c" width="5.906" height="27.328" x="10.594" y="4.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation="1"/></filter><filter id="iM44W3X" width="5.614" height="26.882" x="15.69" y="4.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation="1"/></filter><filter id="i1GvGwj" width="7.691" height="7.98" x="10.42" y="2.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation="1"/></filter><filter id="iMsRFUb" width="9.324" height="9.324" x="12.954" y="1.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation="1"/></filter><filter id="itAop1l" width=".65" height="22.536" x="18.066" y="7.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="iNdJPkd" width="9.8" height="23.731" x="4.6" y="6.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".1"/></filter><filter id="inS7zHc" width="17" height="30.931" x="1" y="6.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_28327_7697"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_28327_7697" result="shape"/></filter><filter id="iidJiOe" width=".65" height="21.977" x="13.066" y="7.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="iMrgTgk" width="1.285" height="1.661" x="19.937" y="23.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="iHwbOjc" width="1.122" height="1.6" x="10.992" y="25.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="ianDmmc" width="1.484" height="1.613" x="11.52" y="3.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="iRhqORb" width="1.538" height="1.563" x="3.589" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="iPlT2lc" width="1.479" height="1.551" x="4.421" y="22.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="i7sUHad" width="1.132" height="1.62" x="11.027" y="8.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="ic175Fr" width="1.784" height="1.779" x="3" y="9.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.734379 0 0 0 0 0.776471 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="isr9ure" width="1.519" height="1.515" x="3.99" y="22.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.72549 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="i2Sn7Sc" width="2.06" height="2.81" x="12.04" y="15.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658297 0 0 0 0 0.716667 0 0 0 0 0.495694 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="i0iTWed" width="1.795" height="1" x="10" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.776471 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="ifQQUDd" width="1.667" height="1.739" x="10.99" y="2.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658297 0 0 0 0 0.716667 0 0 0 0 0.495694 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7697"/></filter><filter id="imkxxZc" width="1.58" height="1.573" x="26.508" y="15.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="iBhhDoe" width="1.654" height="1.642" x="24.122" y="5.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="i3vaktc" width="1.516" height="1.516" x="18.773" y="3.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".15"/></filter><filter id="irPJaoe" width="1.943" height="1.957" x="12.255" y="15.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="i1doqGG" width="8.544" height="11.794" x="5.019" y="11.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".125"/></filter><filter id="iS6oZPn" width="5.469" height="13.344" x="5.344" y="9.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".5"/></filter><filter id="iLbdL0J" width="1.287" height="1.275" x="11.313" y="3.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".1"/></filter><filter id="iMTT2gb" width="1.383" height="1.38" x="3.286" y="9.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7697" stdDeviation=".1"/></filter><radialGradient id="isUJOpd" cx="0" cy="0" r="1" gradientTransform="matrix(3.6826 6.44452 -7.64478 4.36846 22.832 10.688)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="ochscsbud"/><stop offset="1" class="jb87ofoqn"/></radialGradient><radialGradient id="iLDpxsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 0 0 2.46875 20.969 15.73)" gradientUnits="userSpaceOnUse"><stop class="cas1bibmw"/><stop offset="1" class="eqtocubaz"/></radialGradient><radialGradient id="iL3lDUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43818 1.2472 -2.99485 -3.45346 29 6.574)" gradientUnits="userSpaceOnUse"><stop class="xczfe0g-o"/><stop offset="1" class="lhjq19zcb"/></radialGradient><radialGradient id="iPUY2Dd" cx="0" cy="0" r="1" gradientTransform="matrix(.84325 2.22858 -8.04213 3.04298 24.109 12.907)" gradientUnits="userSpaceOnUse"><stop class="lvlqg1bio"/><stop offset="1" class="u3523xabg"/></radialGradient><radialGradient id="iHThoic" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 .17187 -.76257 3.95152 25.734 11.73)" gradientUnits="userSpaceOnUse"><stop class="lvlqg1bio"/><stop offset="1" class="u3523xabg"/></radialGradient><radialGradient id="iwDbrxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70773 -.51197 6.63556 -9.17273 26.021 14.955)" gradientUnits="userSpaceOnUse"><stop class="jsnt1acdf"/><stop offset="1" class="a-9e1knvo"/></radialGradient><radialGradient id="ijpVHGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.06023 -.8583 13.79575 -.96808 23.583 16.22)" gradientUnits="userSpaceOnUse"><stop class="jsnt1acdf"/><stop offset="1" class="a-9e1knvo"/></radialGradient><radialGradient id="iUcBMMe" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 14.064 5.482)scale(1.07081 3.10974)" gradientUnits="userSpaceOnUse"><stop class="jsnt1acdf"/><stop offset="1" class="a-9e1knvo"/></radialGradient><radialGradient id="i80seCe" cx="0" cy="0" r="1" gradientTransform="matrix(.82813 3.15625 -1.04355 .2738 25.547 10.527)" gradientUnits="userSpaceOnUse"><stop class="wceq6d_3s"/><stop offset="1" class="vuk6hhbbg"/></radialGradient><radialGradient id="ih0YKeb" cx="0" cy="0" r="1" gradientTransform="rotate(-133.1 16.154 1.419)scale(2.33253 9.83474)" gradientUnits="userSpaceOnUse"><stop class="m1amb3xdn"/><stop offset="1" class="bs0_ywbus"/></radialGradient><radialGradient id="ih9twjb" cx="0" cy="0" r="1" gradientTransform="rotate(124.563 3.435 15.435)scale(1.03561 .55318)" gradientUnits="userSpaceOnUse"><stop offset=".474" class="k3rcqtbgh"/><stop offset="1" class="t6zp_vbou"/></radialGradient><radialGradient id="iIZQ2Pc" cx="0" cy="0" r="1" gradientTransform="rotate(-54.857 27.311 7.639)scale(5.80889 13.4548)" gradientUnits="userSpaceOnUse"><stop class="mmiff3blk"/><stop offset="1" class="rbo_s-jjr"/></radialGradient><radialGradient id="idkny1Z" cx="0" cy="0" r="1" gradientTransform="rotate(130.649 .03 11.365)scale(2.03881 2.33898)" gradientUnits="userSpaceOnUse"><stop class="ph6oltr7q"/><stop offset="1" class="k6q60wqyz"/></radialGradient><radialGradient id="il2eDnc" cx="0" cy="0" r="1" gradientTransform="rotate(143.49 8.383 5.89)scale(4.88593 3.7854)" gradientUnits="userSpaceOnUse"><stop class="rusvdfbke"/><stop offset="1" class="wg44jfb0m"/></radialGradient><radialGradient id="it1Ivdq" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .59375 -.91364 3.22179 4.75 10.98)" gradientUnits="userSpaceOnUse"><stop class="t71hcq-9g"/><stop offset="1" class="lzlbv9bqd"/></radialGradient><radialGradient id="iF6cIDc" cx="0" cy="0" r="1" gradientTransform="rotate(39.107 -23.278 28.11)scale(3.44325 3.5708)" gradientUnits="userSpaceOnUse"><stop class="kd15uccja"/><stop offset="1" class="bb-pvfwss"/></radialGradient><radialGradient id="il7lW5c" cx="0" cy="0" r="1" gradientTransform="matrix(.875 0 0 6.90625 12.688 15.95)" gradientUnits="userSpaceOnUse"><stop class="kd15uccja"/><stop offset="1" class="bb-pvfwss"/></radialGradient><radialGradient id="ijX8b2d" cx="0" cy="0" r="1" gradientTransform="rotate(116.896 1.242 12.712)scale(1.20889 .94053)" gradientUnits="userSpaceOnUse"><stop class="az_czogtx"/><stop offset="1" class="rcxid8v0e"/></radialGradient><radialGradient id="iNm2qme" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.28125 -2.85773 0 5.469 11.387)" gradientUnits="userSpaceOnUse"><stop class="q5-sar3gn"/><stop offset="1" class="atg4m0bwe"/></radialGradient><radialGradient id="iAfYArd" cx="0" cy="0" r="1" gradientTransform="rotate(96.623 3.866 9.595)scale(4.33518 4.37293)" gradientUnits="userSpaceOnUse"><stop class="z5g7nxrjl"/><stop offset="1" class="j3mnzh9sq"/></radialGradient><radialGradient id="iYJFnMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47343 -.4382 .4401 -.47549 28.01 16.972)" gradientUnits="userSpaceOnUse"><stop class="vz2jq3bwf"/><stop offset="1" class="sn4t7ybex"/></radialGradient><radialGradient id="iWK0g2R" cx="0" cy="0" r="1" gradientTransform="rotate(135 1.409 9.084)scale(1.19324 .56446)" gradientUnits="userSpaceOnUse"><stop class="o8cz93b2v"/><stop offset="1" class="xowusrb5d"/></radialGradient><radialGradient id="im51Mwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.39993 0 0 -.38817 21.823 24.346)" gradientUnits="userSpaceOnUse"><stop class="qq23hkxyl"/><stop offset="1" class="xohfwn0yn"/></radialGradient><radialGradient id="ijj7qXb" cx="0" cy="0" r="1" gradientTransform="rotate(138.365 6.042 13.704)scale(.36633 .3579)" gradientUnits="userSpaceOnUse"><stop class="s1y2gac1n"/><stop offset="1" class="xohfwn0yn"/></radialGradient><radialGradient id="i7duO0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.37026 0 0 -.2974 19.592 11.383)" gradientUnits="userSpaceOnUse"><stop class="s1y2gac1n"/><stop offset="1" class="xohfwn0yn"/></radialGradient><radialGradient id="iJwmvUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.94922 0 0 -.25 11.797 9.512)" gradientUnits="userSpaceOnUse"><stop class="d7v28gw8g"/><stop offset="1" class="rjzrd0bnq"/></radialGradient><radialGradient id="i0eAcoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.36025 .17064 -.1361 -.2873 20.848 3.389)" gradientUnits="userSpaceOnUse"><stop class="pvv72w7rp"/><stop offset="1" class="mi77ykdnk"/></radialGradient><radialGradient id="iYtnvAe" cx="0" cy="0" r="1" gradientTransform="rotate(-55.592 29.805 2.91)scale(2.76505 1.14713)" gradientUnits="userSpaceOnUse"><stop class="mmiff3blk"/><stop offset="1" class="rbo_s-jjr"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cactus" /></template>
<style>
.a-9e1knvo {
  stop-color: var(--svg-color--47ae4a, #47AE4A);
  stop-opacity: 0;
}

.a3-58qdsq {
  stop-color: var(--svg-color--989258, #989258);
}

.ab51sacat {
  cx: 14.266px;
  cy: 6.002px;
  fill: var(--svg-color--5db65a, #5DB65A);
  rx: 1.659px;
  ry: 2.148px;
}

.atg4m0bwe {
  stop-color: var(--svg-color--40a047, #40A047);
  stop-opacity: 0;
}

.az_czogtx {
  stop-color: var(--svg-color--2b6b33, #2B6B33);
}

.bb-pvfwss {
  stop-color: var(--svg-color--85bb83, #85BB83);
  stop-opacity: 0;
}

.bclz0xn3o {
  stop-color: var(--svg-color--9ab584, #9AB584);
}

.bd2b-8b4v {
  stop-color: var(--svg-color--9f9652, #9F9652);
  stop-opacity: 0;
}

.bklq3prpk {
  stop-color: var(--svg-color--2e5d3f, #2E5D3F);
}

.bs0_ywbus {
  stop-color: var(--svg-color--5c9f65, #5C9F65);
  stop-opacity: 0;
}

.ca4k7zb1j {
  stop-color: var(--svg-color--30733e, #30733E);
}

.cas1bibmw {
  stop-color: var(--svg-color--5aba57, #5ABA57);
}

.cn_sc0vcm {
  stop-color: var(--svg-color--7f9d72, #7F9D72);
}

.d7v28gw8g {
  stop-color: var(--svg-color--97b27f, #97B27F);
}

.dl2t2ijsi {
  fill: var(--svg-color--5db65a, #5DB65A);
  d: path("M12.594 6.012H14.5V29.34h-1.906z");
}

.dv1opcdad {
  stop-color: var(--svg-color--c5c58f, #C5C58F);
  stop-opacity: 0;
}

.e_1gj49qa {
  d: path("M11.348 10.012H10.5c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h.848c.28 0 .347.22.347.5s-.067.5-.347.5");
}

.e27u0yb7u {
  stop-color: var(--svg-color--a6ba82, #A6BA82);
}

.epjbasbnm {
  stop-color: var(--svg-color--79b876, #79B876);
}

.eqtocubaz {
  stop-color: var(--svg-color--5aba57, #5ABA57);
  stop-opacity: 0;
}

.fen5pxeqo {
  d: path("M11.418 27.012H10.5c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h.918c.28 0 .293.22.293.5s-.013.5-.293.5");
}

.fhae83b5d {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.125 14.92h-.111l.012.11l.092.869l.01.09h1.362a4.616 4.616 0 0 0 4.61-4.61V9.614a.582.582 0 0 0-1.164 0v1.763c0 1.901-1.638 3.541-3.539 3.541z");
}

.ft5dv1b6b {
  fill: none;
}

.fz0chvzue {
  stop-color: var(--svg-color--518761, #518761);
}

.gg0f93b8q {
  stop-color: var(--svg-color--a0c784, #A0C784);
}

.ggvp6bbze {
  d: path("m7.801 14.488l.349-.336c.2-.2.51-.2.71 0s.2.51 0 .71l-.71.71c-.2.2-.447.404-.556 0s.007-.884.207-1.084");
}

.gl5c37tng {
  stop-color: var(--svg-color--518761, #518761);
  stop-opacity: 0;
}

.gn2d_ubbz {
  cx: 17.616px;
  cy: 6.34px;
  r: 2.662px;
}

.guuv_8bhg {
  cx: 20.579px;
  cy: 24.61px;
  fill: var(--svg-color--3cac34, #3CAC34);
  rx: 0.342px;
  ry: 0.531px;
}

.h-m3dib0s {
  stroke: var(--svg-color--b4b987, #B4B987);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.594 15.7l1.265 1.28");
}

.hd9pe2bmk {
  stop-color: var(--svg-color--93a880, #93A880);
}

.hwii8_bof {
  stop-color: var(--svg-color--b7b06a, #B7B06A);
}

.i-j138bls {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.9 23.112v6.18a.6.6 0 1 0 1.2 0V7.363a.6.6 0 1 0-1.2 0v14.55H9.68a3.583 3.583 0 0 1-3.58-3.58v-6.77c0-.336-.265-.65-.6-.65h-.014a.606.606 0 0 0-.586.6v6.82a4.786 4.786 0 0 0 4.78 4.78z");
}

.iecbuu4_i {
  stop-color: var(--svg-color--c0c682, #C0C682);
  stop-opacity: 0;
}

.ip-9jqbcn {
  stop-color: var(--svg-color--9d9461, #9D9461);
}

.ip4uevb4p {
  width: 1.614px;
  height: 22.882px;
  x: 17.69px;
  y: 6.458px;
  fill: var(--svg-color--7bd377, #7BD377);
  rx: 0.807px;
}

.iv2v15bau {
  stop-color: var(--svg-color--91e38b, #91E38B);
}

.izta7ibph {
  stop-color: var(--svg-color--6ccc66, #6CCC66);
}

.j0x5bdbhe {
  d: path("M19.277 11.012H18.1a.1.1 0 0 0-.1.1v.8a.1.1 0 0 0 .1.1h1.177c.28 0 .5-.22.5-.5s-.22-.5-.5-.5");
}

.j3mnzh9sq {
  stop-color: var(--svg-color--489e4f, #489E4F);
  stop-opacity: 0;
}

.jb87ofoqn {
  stop-color: var(--svg-color--5c9e61, #5C9E61);
}

.jgr65gdmw {
  stop-color: var(--svg-color--92bb7c, #92BB7C);
}

.jh_n68r6e {
  stop-color: var(--svg-color--6dce67, #6DCE67);
}

.jomfc9b8f {
  stop-color: var(--svg-color--a5a96d, #A5A96D);
}

.jsnt1acdf {
  stop-color: var(--svg-color--47ae4a, #47AE4A);
}

.k34ypyjwp {
  stop-color: var(--svg-color--bebd70, #BEBD70);
}

.k3rcqtbgh {
  stop-color: var(--svg-color--278620, #278620);
}

.k6q60wqyz {
  stop-color: var(--svg-color--4bad46, #4BAD46);
  stop-opacity: 0;
}

.ka7p-4bra {
  d: path("M16.01 2c-2.76 0-5 2.24-5 5v13H9.69c-.93 0-1.68-.75-1.68-1.68v-6.77c0-1.4-1.15-2.58-2.55-2.55a2.504 2.504 0 0 0-2.45 2.5v6.82A6.68 6.68 0 0 0 9.69 25h1.32v4.06c0 .52.42.94.94.94h8.12c.52 0 .94-.42.94-.94V7c0-2.76-2.24-5-5-5");
}

.kd15uccja {
  stop-color: var(--svg-color--85bb83, #85BB83);
}

.kgq8hfb8c {
  cx: 5.161px;
  cy: 22.894px;
  fill: var(--svg-color--4fa24f, #4FA24F);
  rx: 0.274px;
  ry: 0.586px;
}

.kjwxy6buy {
  d: path("M13.5 6.862a.5.5 0 0 0-.5.5v14.65H9.68c-2.03 0-3.68-1.65-3.68-3.68v-6.77c0-.29-.23-.55-.5-.55h-.01c-.27.01-.49.23-.49.5v6.82c0 2.58 2.1 4.68 4.68 4.68H13v6.28a.5.5 0 1 0 1 0V7.363a.5.5 0 0 0-.5-.5");
}

.kzwn3w_rw {
  d: path("m3.85 10.572l-.7-.71c-.2-.2-.2-.51 0-.71s.51-.2.71 0l.71.71c.2.2.114.41-.086.61s-.434.3-.634.1");
}

.l3fx-cchf {
  stop-color: var(--svg-color--58b159, #58B159);
}

.lc91jtbpj {
  d: path("m12.445 3.734l-.595-.572c-.2-.2-.51-.2-.71 0s-.2.51 0 .71l.67.67c.2.2.355.118.592-.198c.223-.297.177-.476.043-.61");
}

.lhjq19zcb {
  stop-color: var(--svg-color--91db89, #91DB89);
  stop-opacity: 0;
}

.lj_d4dboj {
  stop-color: var(--svg-color--2b7839, #2B7839);
}

.lkuzhebbb {
  cx: 11.553px;
  cy: 26.512px;
  fill: var(--svg-color--488f42, #488F42);
  rx: 0.261px;
  ry: 0.5px;
}

.lrxnavxra {
  stop-color: var(--svg-color--9ab883, #9AB883);
}

.ls3b9954k {
  d: path("M19.81 20.297L18 22.147v-1.44l1.1-1.12c.2-.2.51-.2.71 0s.2.52 0 .71");
}

.lux5dlb5d {
  stop-color: var(--svg-color--37754b, #37754B);
}

.lv4qp2-ew {
  stop-color: var(--svg-color--668b74, #668B74);
}

.lvlqg1bio {
  stop-color: var(--svg-color--7ccd79, #7CCD79);
}

.lz315bcby {
  stop-color: var(--svg-color--5a9b5b, #5A9B5B);
}

.lzlbv9bqd {
  stop-color: var(--svg-color--8bd485, #8BD485);
  stop-opacity: 0;
}

.m1amb3xdn {
  stop-color: var(--svg-color--5c9f65, #5C9F65);
}

.m64bvt1kw {
  d: path("m27.15 15.452l.71.71c.2.2.2.51 0 .71s-.51.2-.71 0l-.71-.71c-.2-.2-.14-.43.06-.63c.19-.2.45-.28.65-.08");
}

.mi77ykdnk {
  stop-color: var(--svg-color--d2d18e, #D2D18E);
  stop-opacity: 0;
}

.mj1634v-j {
  stop-color: var(--svg-color--afc786, #AFC786);
  stop-opacity: 0;
}

.mjodvub5d {
  stop-color: var(--svg-color--79b876, #79B876);
  stop-opacity: 0;
}

.mmiff3blk {
  stop-color: var(--svg-color--469747, #469747);
}

.mr-h662wk {
  stop-color: var(--svg-color--b3b75e, #B3B75E);
}

.n-jixqb4r {
  d: path("M13.016 23.574c-.488 1.175-1.495 1.388-1.938 1.383c-2.078 0-3.37-.898-3.484-1.383z");
}

.n7n8j7bun {
  stop-color: var(--svg-color--b8d18c, #B8D18C);
}

.na2qm1bnp {
  d: path("M18.5 6.862a.5.5 0 0 0-.5.5v21.93a.5.5 0 1 0 1 0V7.363a.5.5 0 0 0-.5-.5");
}

.nenc74bdb {
  cx: 12.262px;
  cy: 4.299px;
  fill: var(--svg-color--58b651, #58B651);
  rx: 0.329px;
  ry: 0.586px;
}

.o-vz963lt {
  stroke: var(--svg-color--b5cb9a, #B5CB9A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m3.586 9.332l.783.78");
}

.o8cz93b2v {
  stop-color: var(--svg-color--bec284, #BEC284);
}

.ochscsbud {
  stop-color: var(--svg-color--5c9e61, #5C9E61);
  stop-opacity: 0;
}

.okz-aacqg {
  d: path("m12.19 16.162l1.81 1.85v-1.44l-1.1-1.12c-.2-.2-.51-.2-.71 0s-.2.51 0 .71");
}

.osu878trg {
  stop-color: var(--svg-color--9ebb83, #9EBB83);
}

.otc1a0b7k {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.438 7.238l-.979-.964");
}

.oxtivy4zd {
  stop-color: var(--svg-color--5a9b5b, #5A9B5B);
  stop-opacity: 0;
}

.oy0jjgbly {
  stop-color: var(--svg-color--bad39f, #BAD39F);
}

.p840u1f_i {
  stroke-linecap: round;
  d: path("M6.844 10.856v7.374a2.97 2.97 0 0 0 2.968 2.97v0");
}

.pgg4nwb8e {
  stop-color: var(--svg-color--b2ac5e, #B2AC5E);
}

.ph6oltr7q {
  stop-color: var(--svg-color--4bad46, #4BAD46);
}

.phya_shmn {
  stop-color: var(--svg-color--9f9652, #9F9652);
}

.pmnn8bcah {
  stop-color: var(--svg-color--a6ba82, #A6BA82);
  stop-opacity: 0;
}

.pno2nxw-q {
  stop-color: var(--svg-color--86b372, #86B372);
}

.pp4n1s4os {
  d: path("m24.85 7.572l-.71-.71c-.2-.2-.2-.51 0-.71s.51-.2.71 0l.71.71c.2.2.2.51 0 .71c-.19.2-.51.2-.71 0");
}

.pr1bl8nwg {
  stop-color: var(--svg-color--96c47d, #96C47D);
}

.pvv72w7rp {
  stop-color: var(--svg-color--d2d18e, #D2D18E);
}

.q5-sar3gn {
  stop-color: var(--svg-color--40a047, #40A047);
}

.q7typtk1k {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M18.39 7.515V29.55");
}

.qpp1fqbcr {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m26.846 15.624l.904.896");
}

.qq23hkxyl {
  stop-color: var(--svg-color--d2d090, #D2D090);
}

.qqjuhk71j {
  stop-color: var(--svg-color--89a27b, #89A27B);
}

.qug8vqbjp {
  stop-color: var(--svg-color--87a972, #87A972);
}

.r-5bdgbtr {
  stop-color: var(--svg-color--52af55, #52AF55);
}

.rbo_s-jjr {
  stop-color: var(--svg-color--469747, #469747);
  stop-opacity: 0;
}

.rcxid8v0e {
  stop-color: var(--svg-color--2b6b33, #2B6B33);
  stop-opacity: 0;
}

.rep9lgbin {
  stop-color: var(--svg-color--93a880, #93A880);
  stop-opacity: 0;
}

.rjzrd0bnq {
  stop-color: var(--svg-color--97b27f, #97B27F);
  stop-opacity: 0;
}

.rmp-xs0ph {
  stop-color: var(--svg-color--8ed989, #8ED989);
}

.ro_5gddxj {
  stop-color: var(--svg-color--75c876, #75C876);
}

.rrksbku7e {
  stop-color: var(--svg-color--bebc71, #BEBC71);
}

.rt1s6ex_z {
  stop-color: var(--svg-color--c5c58f, #C5C58F);
}

.rusvdfbke {
  stop-color: var(--svg-color--95e491, #95E491);
}

.s-zkkvaky {
  stop-color: var(--svg-color--a8a75a, #A8A75A);
}

.s1y2gac1n {
  stop-color: var(--svg-color--cfcd8d, #CFCD8D);
}

.sdl6__ybo {
  d: path("M26.656 8.143a.906.906 0 0 1 1.813 0v3.306a1.813 1.813 0 0 1-1.813 1.813z");
}

.sl2x5tbig {
  d: path("M22.32 18.012h-4.25a2.5 2.5 0 0 1 0-5h4.25c.93 0 1.68-.75 1.68-1.68v-2.82a2.5 2.5 0 0 1 5 0v2.82c0 3.68-3 6.68-6.68 6.68");
}

.sn4t7ybex {
  stop-color: var(--svg-color--a79c66, #A79C66);
  stop-opacity: 0;
}

.t6zp_vbou {
  stop-color: var(--svg-color--278620, #278620);
  stop-opacity: 0;
}

.t71hcq-9g {
  stop-color: var(--svg-color--8bd485, #8BD485);
}

.tl8enjk5c {
  cx: 11.593px;
  cy: 9.512px;
  fill: var(--svg-color--58b651, #58B651);
  rx: 0.266px;
  ry: 0.51px;
}

.u3523xabg {
  stop-color: var(--svg-color--7ccd79, #7CCD79);
  stop-opacity: 0;
}

.uhnha0ihn {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.688 15.543h.562a4.25 4.25 0 0 0 4.25-4.25V9.887");
}

.uhqpwabva {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.39 8.074v21.477");
}

.v2wyrho8q {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.344 11.418v6.719a4.5 4.5 0 0 0 4.5 4.5h3.469");
}

.vi5372q9m {
  cx: 19.531px;
  cy: 4.457px;
  fill: var(--svg-color--53c84c, #53C84C);
  rx: 0.376px;
  ry: 0.528px;
}

.vjdzhnb0d {
  d: path("m19.44 3.862l.71-.71c.2-.2.51-.2.71 0s.2.51 0 .71l-.71.71c-.2.2-.51.2-.71 0c-.2-.19-.2-.51 0-.71");
}

.vuk6hhbbg {
  stop-color: var(--svg-color--6cb26e, #6CB26E);
  stop-opacity: 0;
}

.vz2jq3bwf {
  stop-color: var(--svg-color--a79c66, #A79C66);
}

.w1l4wl4lo {
  stop-color: var(--svg-color--91e38b, #91E38B);
  stop-opacity: 0;
}

.wceq6d_3s {
  stop-color: var(--svg-color--6cb26e, #6CB26E);
}

.wg44jfb0m {
  stop-color: var(--svg-color--95e491, #95E491);
  stop-opacity: 0;
}

.wjwh01fhd {
  d: path("m5.355 23.367l-.505.505c-.2.2-.51.2-.71 0s-.2-.51 0-.71l.505-.505c.2-.2.393-.071.593.129c.2.19.317.381.117.581");
}

.wmh6jhb_b {
  stop-color: var(--svg-color--56bd50, #56BD50);
}

.wtmgjacnt {
  cx: 4.358px;
  cy: 10.373px;
  fill: var(--svg-color--58b651, #58B651);
  rx: 0.329px;
  ry: 0.586px;
}

.wy2yzchau {
  stroke: var(--svg-color--aac28f, #AAC28F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.613 3.36l.688.675");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x4n1t1bnt {
  d: path("M20.727 24.012h.773c.28 0 .5.22.5.5s-.22.5-.5.5h-.773c-.28 0-.407-.22-.407-.5s.127-.5.407-.5");
}

.x6ria4bvz {
  d: path("M26.5 9.002a.5.5 0 0 0-.5.5v1.83c0 2.03-1.65 3.68-3.68 3.68H21v1h1.32c2.58 0 4.68-2.1 4.68-4.68v-1.83a.5.5 0 0 0-.5-.5");
}

.x7th1qq_j {
  stop-color: var(--svg-color--30733e, #30733E);
  stop-opacity: 0;
}

.xczfe0g-o {
  stop-color: var(--svg-color--91db89, #91DB89);
}

.xdwx347wr {
  stop-color: var(--svg-color--46914c, #46914C);
}

.xi5a2nbde {
  stop-color: var(--svg-color--acb05e, #ACB05E);
}

.xjt_u1buz {
  stop-color: var(--svg-color--59aa5f, #59AA5F);
}

.xm3j-pb_d {
  stop-color: var(--svg-color--8ed989, #8ED989);
  stop-opacity: 0;
}

.xohfwn0yn {
  stop-color: var(--svg-color--cfcd8d, #CFCD8D);
  stop-opacity: 0;
}

.xowusrb5d {
  stop-color: var(--svg-color--bec284, #BEC284);
  stop-opacity: 0;
}

.ygcq6___g {
  stop-color: var(--svg-color--bdbb6b, #BDBB6B);
}

.yt-4_jbks {
  stop-color: var(--svg-color--90b779, #90B779);
}

.z5g7nxrjl {
  stop-color: var(--svg-color--489e4f, #489E4F);
}

.zwza16bcb {
  stop-color: var(--svg-color--60b765, #60B765);
}

</style>
