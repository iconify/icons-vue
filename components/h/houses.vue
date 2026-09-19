<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVS6Axe)" class="tcttjrbhj"/><path fill="url(#icaVnod)" class="gq308acqd"/><path fill="url(#i4MhThc)" class="gq308acqd"/><path fill="url(#ic6GKmb)" class="gq308acqd"/><path fill="url(#iiEJ7fb)" class="gq308acqd"/><path fill="url(#iA0kULd)" class="gq308acqd"/><path fill="url(#ieGdthc)" class="oob98ebpv"/><path fill="url(#imdxLxb)" class="oob98ebpv"/><path fill="url(#iScIK8d)" class="oob98ebpv"/><path fill="url(#iPVuvNe)" class="oob98ebpv"/><path fill="url(#igHo0Cd)" class="oob98ebpv"/><path fill="url(#ijGKS2b)" class="oob98ebpv"/><path fill="url(#iqrwlCd)" class="oob98ebpv"/><path fill="url(#ivYNVBe)" class="l134h2b_j"/><g filter="url(#iNCFVob)"><path stroke="url(#iunhRxd)" class="o7-2b4b-r"/></g><g filter="url(#iqYhJPm)"><path stroke="url(#iOFL2ve)" class="be99tqbxd"/></g><path fill="url(#igBGSDe)" class="ncldowb5k"/><path fill="url(#i1HiHBV)" class="ncldowb5k"/><path fill="url(#iru1FQc)" class="ncldowb5k"/><path fill="url(#iH7nVcb)" class="ncldowb5k"/><path fill="url(#i5aLfxb)" class="ncldowb5k"/><path fill="url(#iejC81J)" class="ncldowb5k"/><path fill="url(#i1HiHBV)" class="ncldowb5k"/><path fill="url(#iru1FQc)" class="ncldowb5k"/><path fill="url(#iH7nVcb)" class="ncldowb5k"/><path fill="url(#iPNYZfc)" class="ncldowb5k"/><path fill="url(#ipvP4hb)" class="izr6bygkz"/><path fill="url(#ik2Cy8b)" class="izr6bygkz"/><path fill="url(#iTXOIwb)" class="izr6bygkz"/><path fill="url(#ilKraBe)" class="izr6bygkz"/><path fill="url(#iae23Jb)" class="izr6bygkz"/><path fill="url(#iIV0Gzb)" class="izr6bygkz"/><path fill="url(#irGENut)" class="izr6bygkz"/><path fill="url(#it9QE5U)" class="izr6bygkz"/><path fill="url(#iJBi6lK)" class="snyc7730a"/><g filter="url(#i6pLKOX)"><path stroke="url(#iAnEb9d)" class="gmdm0tbia"/></g><g filter="url(#iYFsHFd)"><path stroke="url(#ipu5mgc)" class="t0d8u9fem"/></g><path fill="url(#ijl2Dfc)" class="x6-g55bew"/><path fill="url(#id2LYrQ)" class="x6-g55bew"/><path fill="url(#ir3xire)" class="x6-g55bew"/><path fill="url(#iUfoCyd)" class="x6-g55bew"/><path fill="url(#iP9KXVp)" class="x6-g55bew"/><path fill="url(#i5nTnhd)" class="x6-g55bew"/><path fill="url(#iCuDwBk)" class="x6-g55bew"/><g filter="url(#igcoNon)"><path fill="url(#iBjO4be)" class="m9zp7-b4c"/></g><g filter="url(#iWd2ftd)"><path fill="url(#ie458dL)" class="eeh5esb7i"/><path fill="url(#iiQZMzb)" class="eeh5esb7i"/></g><path fill="url(#izmfqIb)" class="eeh5esb7i"/><path fill="url(#iOv1Gge)" class="eeh5esb7i"/><g filter="url(#iDeHDoe)"><path fill="url(#iAyrMXc)" class="g3xjxtboo"/></g><g filter="url(#ioB6fRd)"><path class="xy9tfqbpg"/></g><path fill="url(#iE8Zo3b)" class="ed70xxbmp"/><g filter="url(#iiU61xc)"><path class="h7l2nr80b"/></g><path fill="url(#ih9bBeb)" class="j3dxsyunw"/><path fill="url(#iQk8W6d)" class="j3dxsyunw"/><path fill="url(#isFGhOc)" class="j3dxsyunw"/><g filter="url(#if5UKac)"><path stroke="url(#iUDKbde)" class="t3nb6qaow"/></g><g filter="url(#i2aiTrc)"><path stroke="url(#i1fNidb)" class="i4uxb1epo"/></g><g filter="url(#iUf1IVd)"><path class="wkt6lhbex"/><path fill="url(#i2lgYEe)" class="gexqvtwki"/><path fill="url(#iwR54hd)" class="gexqvtwki"/><path fill="url(#iHvbAKd)" class="gexqvtwki"/></g><g filter="url(#iHopvJe)"><path class="qgcnv_btp"/><path fill="url(#iBf6SJb)" class="mddmsqhiw"/><path fill="url(#ijCC16c)" class="mddmsqhiw"/><path fill="url(#ilE7jMb)" class="mddmsqhiw"/></g><g filter="url(#iRNqeoc)"><path class="n9h9s3kza"/><path fill="url(#i3meaQb)" class="f9x44vo9q"/><path fill="url(#ivXrefe)" class="f9x44vo9q"/><path fill="url(#iJAr2ie)" class="f9x44vo9q"/></g><g filter="url(#icW66Lb)"><path class="wdq9jxbgd"/><path fill="url(#ixe8cKc)" class="t97x2ibwe"/><path fill="url(#iMMOrNe)" class="t97x2ibwe"/></g><path fill="url(#ilmgFBe)" class="gexqvtwki"/><path fill="url(#i8ulV4U)" class="mddmsqhiw"/><path fill="url(#i8s68LS)" class="mddmsqhiw"/><path fill="url(#iBGfIjd)" class="mddmsqhiw"/><path fill="url(#iYjmjZd)" class="f9x44vo9q"/><path fill="url(#ir9m98b)" class="t97x2ibwe"/><g filter="url(#irHjbTb)"><path class="h1djfpuxc"/></g><g filter="url(#i7XFKwe)"><path class="wr52h6aeu"/></g><g filter="url(#i3Y1uYb)"><path class="hoig2xb1i"/></g><defs><linearGradient id="iVS6Axe" x1="3.549" x2="29.361" y1="26.844" y2="26.844" gradientUnits="userSpaceOnUse"><stop class="lx2gwjlwx"/><stop offset="1" class="gkpww5q-f"/></linearGradient><linearGradient id="i4MhThc" x1="3.973" x2="4.799" y1="8.366" y2="8.366" gradientUnits="userSpaceOnUse"><stop class="zlve4xbhd"/><stop offset="1" class="mk0kxp2ew"/></linearGradient><linearGradient id="ic6GKmb" x1="5.59" x2="5.229" y1="9.016" y2="8.59" gradientUnits="userSpaceOnUse"><stop class="zq7du-bdj"/><stop offset="1" class="nw_qsv-ec"/></linearGradient><linearGradient id="iiEJ7fb" x1="5.096" x2="5.096" y1="6.129" y2="6.222" gradientUnits="userSpaceOnUse"><stop class="xvg0squwb"/><stop offset="1" class="o3xwhwsse"/></linearGradient><linearGradient id="ieGdthc" x1="8.598" x2="5.986" y1="16.969" y2="14.344" gradientUnits="userSpaceOnUse"><stop offset=".164" class="i829-kbbz"/><stop offset="1" class="nh51m9bdp"/></linearGradient><linearGradient id="imdxLxb" x1="3.782" x2="7.935" y1="19.325" y2="13.463" gradientUnits="userSpaceOnUse"><stop class="i6p-dub2h"/><stop offset="1" class="sqabk-b9d"/></linearGradient><linearGradient id="iPVuvNe" x1="14.103" x2="13.749" y1="16.379" y2="16.379" gradientUnits="userSpaceOnUse"><stop class="pv7n3io0c"/><stop offset="1" class="uliagebas"/></linearGradient><linearGradient id="ijGKS2b" x1="10.451" x2="9.59" y1="8.58" y2="9.576" gradientUnits="userSpaceOnUse"><stop class="vu2peg21y"/><stop offset="1" class="o-gekhbbu"/></linearGradient><linearGradient id="iqrwlCd" x1="3.024" x2="3.4" y1="17.584" y2="17.584" gradientUnits="userSpaceOnUse"><stop class="q3hfn2asc"/><stop offset="1" class="rh7pjiozr"/></linearGradient><linearGradient id="ivYNVBe" x1="8.484" x2="8.484" y1="5.672" y2="10.82" gradientUnits="userSpaceOnUse"><stop class="k11oh3pvi"/><stop offset="1" class="vyow51wth"/></linearGradient><linearGradient id="iunhRxd" x1="8.397" x2="15.401" y1="6.061" y2="13.271" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="iOFL2ve" x1="8.798" x2="1.795" y1="6.061" y2="13.271" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="i1HiHBV" x1="19.004" x2="19.83" y1="8.366" y2="8.366" gradientUnits="userSpaceOnUse"><stop class="zlve4xbhd"/><stop offset="1" class="mk0kxp2ew"/></linearGradient><linearGradient id="iru1FQc" x1="20.622" x2="20.26" y1="9.016" y2="8.59" gradientUnits="userSpaceOnUse"><stop class="zq7du-bdj"/><stop offset="1" class="nw_qsv-ec"/></linearGradient><linearGradient id="iH7nVcb" x1="20.128" x2="20.128" y1="6.129" y2="6.222" gradientUnits="userSpaceOnUse"><stop class="xvg0squwb"/><stop offset="1" class="o3xwhwsse"/></linearGradient><linearGradient id="ipvP4hb" x1="21.611" x2="28.831" y1="14.658" y2="14.658" gradientUnits="userSpaceOnUse"><stop class="zj8rkybal"/><stop offset="1" class="keuf9wi3y"/></linearGradient><linearGradient id="ik2Cy8b" x1="18.814" x2="22.966" y1="19.325" y2="13.463" gradientUnits="userSpaceOnUse"><stop class="i6p-dub2h"/><stop offset="1" class="sqabk-b9d"/></linearGradient><linearGradient id="ilKraBe" x1="29.134" x2="28.781" y1="16.379" y2="16.379" gradientUnits="userSpaceOnUse"><stop class="pv7n3io0c"/><stop offset="1" class="uliagebas"/></linearGradient><linearGradient id="iIV0Gzb" x1="25.314" x2="24.691" y1="8.734" y2="9.378" gradientUnits="userSpaceOnUse"><stop class="t7pzc9bko"/><stop offset="1" class="rakas7bcy"/></linearGradient><linearGradient id="irGENut" x1="18.055" x2="18.431" y1="17.584" y2="17.584" gradientUnits="userSpaceOnUse"><stop class="q3hfn2asc"/><stop offset="1" class="rh7pjiozr"/></linearGradient><linearGradient id="iJBi6lK" x1="23.516" x2="23.516" y1="5.672" y2="10.072" gradientUnits="userSpaceOnUse"><stop class="alduh6bry"/><stop offset="1" class="rpggkhbuy"/></linearGradient><linearGradient id="iAnEb9d" x1="23.428" x2="30.432" y1="6.061" y2="13.271" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="ipu5mgc" x1="23.829" x2="16.826" y1="6.061" y2="13.271" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="ijl2Dfc" x1="8.476" x2="23.813" y1="19.721" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="tniejuz7g"/><stop offset="1" class="mt-6s8beo"/></linearGradient><linearGradient id="id2LYrQ" x1="8.907" x2="14.917" y1="26.523" y2="17.862" gradientUnits="userSpaceOnUse"><stop class="i6p-dub2h"/><stop offset="1" class="sqabk-b9d"/></linearGradient><linearGradient id="iUfoCyd" x1="24.265" x2="23.739" y1="22.23" y2="22.23" gradientUnits="userSpaceOnUse"><stop class="pv7n3io0c"/><stop offset="1" class="uliagebas"/></linearGradient><linearGradient id="i5nTnhd" x1="18.83" x2="18.477" y1="10.862" y2="11.215" gradientUnits="userSpaceOnUse"><stop class="t7pzc9bko"/><stop offset="1" class="rakas7bcy"/></linearGradient><linearGradient id="iCuDwBk" x1="7.779" x2="8.338" y1="23.986" y2="23.986" gradientUnits="userSpaceOnUse"><stop class="q3hfn2asc"/><stop offset="1" class="rh7pjiozr"/></linearGradient><linearGradient id="iBjO4be" x1="12.609" x2="12.609" y1="17.54" y2="25.812" gradientUnits="userSpaceOnUse"><stop class="vnara5bda"/><stop offset="1" class="bx90284fu"/></linearGradient><linearGradient id="ie458dL" x1="17.955" x2="22.767" y1="22.042" y2="17.245" gradientUnits="userSpaceOnUse"><stop class="joxkjnbrh"/><stop offset="1" class="ltv62lbpd"/></linearGradient><linearGradient id="iiQZMzb" x1="20.184" x2="20.184" y1="21.985" y2="21.107" gradientUnits="userSpaceOnUse"><stop class="d3e5ejb3h"/><stop offset="1" class="t14pfjqht"/></linearGradient><linearGradient id="izmfqIb" x1="17.955" x2="18.85" y1="20.571" y2="20.571" gradientUnits="userSpaceOnUse"><stop class="e2etblb5i"/><stop offset="1" class="o_i1ny-qt"/></linearGradient><linearGradient id="iOv1Gge" x1="18.629" x2="19.229" y1="16.465" y2="18.265" gradientUnits="userSpaceOnUse"><stop class="j1zlpsbpa"/><stop offset="1" class="cl26vbbfz"/></linearGradient><linearGradient id="iAyrMXc" x1="10.266" x2="16.155" y1="22.211" y2="22.173" gradientUnits="userSpaceOnUse"><stop class="c0ag3-bmb"/><stop offset="1" class="ujxwohptv"/></linearGradient><linearGradient id="iE8Zo3b" x1="16.049" x2="16.049" y1="6.156" y2="17.541" gradientUnits="userSpaceOnUse"><stop class="alduh6bry"/><stop offset="1" class="rpggkhbuy"/></linearGradient><linearGradient id="ih9bBeb" x1="9.706" x2="16.576" y1="26.096" y2="26.096" gradientUnits="userSpaceOnUse"><stop class="ibux5fbxv"/><stop offset="1" class="w_5a8mv2g"/></linearGradient><linearGradient id="iQk8W6d" x1="9.385" x2="10.26" y1="26.096" y2="26.096" gradientUnits="userSpaceOnUse"><stop class="hx6t6eb3x"/><stop offset="1" class="xyd7gvbgv"/></linearGradient><linearGradient id="isFGhOc" x1="16.843" x2="16.031" y1="25.665" y2="26.096" gradientUnits="userSpaceOnUse"><stop class="h7id9xbgp"/><stop offset="1" class="uwl25k4xr"/></linearGradient><linearGradient id="iUDKbde" x1="15.918" x2="26.34" y1="6.735" y2="17.465" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="i1fNidb" x1="16.516" x2="6.094" y1="6.735" y2="17.465" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="i2lgYEe" x1="23.903" x2="23.903" y1="26.631" y2="24.753" gradientUnits="userSpaceOnUse"><stop class="hw5_rcbgc"/><stop offset="1" class="nu-_8vbpz"/></linearGradient><linearGradient id="iBf6SJb" x1="8.242" x2="8.242" y1="26.631" y2="24.753" gradientUnits="userSpaceOnUse"><stop class="hw5_rcbgc"/><stop offset="1" class="nu-_8vbpz"/></linearGradient><linearGradient id="i3meaQb" x1="27.534" x2="27.534" y1="20.402" y2="19.374" gradientUnits="userSpaceOnUse"><stop class="hw5_rcbgc"/><stop offset="1" class="nu-_8vbpz"/></linearGradient><linearGradient id="ixe8cKc" x1="4.563" x2="4.563" y1="20.402" y2="19.374" gradientUnits="userSpaceOnUse"><stop class="hw5_rcbgc"/><stop offset="1" class="nu-_8vbpz"/></linearGradient><linearGradient id="i8s68LS" x1="8.242" x2="8.242" y1="26.531" y2="24.753" gradientUnits="userSpaceOnUse"><stop class="hw5_rcbgc"/><stop offset=".819" class="nu-_8vbpz"/></linearGradient><radialGradient id="icaVnod" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.53622 -1.25918 0 5.817 6.48)" gradientUnits="userSpaceOnUse"><stop class="adbob9crr"/><stop offset="1" class="tnuyfsboe"/></radialGradient><radialGradient id="iA0kULd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36805 0 0 -.29407 6.315 6.263)" gradientUnits="userSpaceOnUse"><stop class="ql4_rdbeu"/><stop offset="1" class="ekszfhgkk"/></radialGradient><radialGradient id="iScIK8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.88468 -1.7548 2.09693 -1.05717 10.71 18.624)" gradientUnits="userSpaceOnUse"><stop class="ivc3auy3b"/><stop offset="1" class="pq25vebpj"/></radialGradient><radialGradient id="igHo0Cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46128 -.50998 0 14.233 11.6)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="kt2r_rbsm"/><stop offset="1" class="ixipe2brm"/></radialGradient><radialGradient id="igBGSDe" cx="0" cy="0" r="1" gradientTransform="scale(1.25918 2.53622)rotate(90 7 9.556)" gradientUnits="userSpaceOnUse"><stop class="olcdc20km"/><stop offset="1" class="h1je16bkl"/></radialGradient><radialGradient id="i5aLfxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36805 0 0 -.29407 21.347 6.263)" gradientUnits="userSpaceOnUse"><stop class="o_1pjbcxb"/><stop offset="1" class="y3_h8dezk"/></radialGradient><radialGradient id="iejC81J" cx="0" cy="0" r="1" gradientTransform="scale(1.25918 2.53622)rotate(90 7 9.556)" gradientUnits="userSpaceOnUse"><stop class="adbob9crr"/><stop offset="1" class="tnuyfsboe"/></radialGradient><radialGradient id="iPNYZfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36805 0 0 -.29407 21.347 6.263)" gradientUnits="userSpaceOnUse"><stop class="ql4_rdbeu"/><stop offset="1" class="ekszfhgkk"/></radialGradient><radialGradient id="iTXOIwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.88468 -1.7548 2.09693 -1.05717 25.741 18.624)" gradientUnits="userSpaceOnUse"><stop class="ivc3auy3b"/><stop offset="1" class="pq25vebpj"/></radialGradient><radialGradient id="iae23Jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46128 -.50998 0 29.265 11.6)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="kt2r_rbsm"/><stop offset="1" class="ixipe2brm"/></radialGradient><radialGradient id="it9QE5U" cx="0" cy="0" r="1" gradientTransform="matrix(2.98213 0 0 3.49335 23.629 17.531)" gradientUnits="userSpaceOnUse"><stop class="jd5pj4bbj"/><stop offset="1" class="og2x-rbkq"/></radialGradient><radialGradient id="ir3xire" cx="0" cy="0" r="1" gradientTransform="rotate(-117.235 17.386 6.89)scale(2.87659 3.47954)" gradientUnits="userSpaceOnUse"><stop class="ivc3auy3b"/><stop offset="1" class="pq25vebpj"/></radialGradient><radialGradient id="iP9KXVp" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.58741 -.75887 0 24.459 15.263)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="kt2r_rbsm"/><stop offset="1" class="ixipe2brm"/></radialGradient><radialGradient id="iwR54hd" cx="0" cy="0" r="1" gradientTransform="rotate(-110.329 22.873 5.446)scale(6.19158 2.82035)" gradientUnits="userSpaceOnUse"><stop class="v6xq5oj1z"/><stop offset="1" class="pv_zrhbhj"/></radialGradient><radialGradient id="iHvbAKd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.43867 4.23206 -5.72823 -7.36141 26.64 22.561)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="pv_zrhbhj"/><stop offset=".966" class="v6xq5oj1z"/></radialGradient><radialGradient id="ijCC16c" cx="0" cy="0" r="1" gradientTransform="matrix(2.151 -5.80593 2.64468 .9798 6.432 28.787)" gradientUnits="userSpaceOnUse"><stop class="v6xq5oj1z"/><stop offset="1" class="pv_zrhbhj"/></radialGradient><radialGradient id="ilE7jMb" cx="0" cy="0" r="1" gradientTransform="matrix(5.4387 4.23203 -5.72819 7.36144 5.505 22.561)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="pv_zrhbhj"/><stop offset=".966" class="v6xq5oj1z"/></radialGradient><radialGradient id="ivXrefe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17725 -3.17758 1.44744 -.53626 28.525 21.581)" gradientUnits="userSpaceOnUse"><stop class="v6xq5oj1z"/><stop offset="1" class="pv_zrhbhj"/></radialGradient><radialGradient id="iJAr2ie" cx="0" cy="0" r="1" gradientTransform="rotate(142.112 11.397 14.07)scale(3.77159 5.10496)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="pv_zrhbhj"/><stop offset=".966" class="v6xq5oj1z"/></radialGradient><radialGradient id="iMMOrNe" cx="0" cy="0" r="1" gradientTransform="matrix(2.97659 2.3162 -3.13506 4.0289 3.065 18.174)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="pv_zrhbhj"/><stop offset=".966" class="v6xq5oj1z"/></radialGradient><radialGradient id="ilmgFBe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.36286 2.02989 -1.9324 -3.20136 28.092 22.001)" gradientUnits="userSpaceOnUse"><stop class="f2hgsjbqb"/><stop offset="1" class="wkn48ebdp"/></radialGradient><radialGradient id="i8ulV4U" cx="0" cy="0" r="1" gradientTransform="rotate(133.452 .148 13.154)scale(4.90734 6.94449)" gradientUnits="userSpaceOnUse"><stop class="f2hgsjbqb"/><stop offset="1" class="wkn48ebdp"/></radialGradient><radialGradient id="iBGfIjd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.93748 2.50003 -3.34867 -7.95296 10.111 22.469)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="j_loa24zq"/><stop offset="1" class="se1dg36cr"/></radialGradient><radialGradient id="iYjmjZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8405 1.11096 -1.0576 -1.7521 29.826 17.868)" gradientUnits="userSpaceOnUse"><stop class="f2hgsjbqb"/><stop offset="1" class="wkn48ebdp"/></radialGradient><radialGradient id="ir9m98b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 1.96875 -1.8742 -1.39821 5.361 17.5)" gradientUnits="userSpaceOnUse"><stop class="f2hgsjbqb"/><stop offset="1" class="wkn48ebdp"/></radialGradient><filter id="iNCFVob" width="8.03" height="7.93" x="7.848" y="5.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".3"/></filter><filter id="iqYhJPm" width="8.03" height="7.93" x="1.318" y="5.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".3"/></filter><filter id="i6pLKOX" width="8.03" height="7.93" x="22.879" y="5.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".3"/></filter><filter id="iYFsHFd" width="8.03" height="7.93" x="16.349" y="5.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".3"/></filter><filter id="igcoNon" width="6.28" height="9.272" x="9.469" y="17.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".25"/></filter><filter id="iWd2ftd" width="4.959" height="4.96" x="17.455" y="17.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.47451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/></filter><filter id="iDeHDoe" width="6.339" height="8.11" x="10.066" y="17.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.188235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5845" result="effect2_innerShadow_18_5845"/></filter><filter id="ioB6fRd" width="1.148" height="1.148" x="14.106" y="20.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".075"/></filter><filter id="iiU61xc" width="1.057" height=".857" x="14.262" y="20.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.482353 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.184314 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5845" result="effect2_innerShadow_18_5845"/></filter><filter id="if5UKac" width="11.216" height="11.067" x="15.467" y="6.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".3"/></filter><filter id="i2aiTrc" width="11.216" height="11.067" x="5.751" y="6.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".3"/></filter><filter id="iUf1IVd" width="7.458" height="5.619" x="21.099" y="20.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.564706 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/></filter><filter id="iHopvJe" width="7.458" height="5.619" x="3.787" y="20.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.564706 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/></filter><filter id="iRNqeoc" width="4.173" height="3.166" x="26" y="17.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.564706 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/></filter><filter id="icW66Lb" width="4.173" height="3.166" x="2.125" y="17.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.564706 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5845"/></filter><filter id="irHjbTb" width="3.619" height="3.833" x="21.231" y="22.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".375"/></filter><filter id="i7XFKwe" width="2.66" height="2.777" x="25.732" y="17.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".375"/></filter><filter id="i3Y1uYb" width="2.66" height="2.777" x="3.705" y="17.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5845" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:houses" /></template>
<style>
.adbob9crr {
  stop-color: var(--svg-color--d39364, #D39364);
}

.alduh6bry {
  stop-color: var(--svg-color--ea6d2e, #EA6D2E);
}

.be99tqbxd {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m8.598 6.16l-6.53 6.43");
}

.bx90284fu {
  stop-color: var(--svg-color--6d4d2f, #6D4D2F);
}

.c0ag3-bmb {
  stop-color: var(--svg-color--70504d, #70504D);
}

.cl26vbbfz {
  stop-color: var(--svg-color--43b3f2, #43B3F2);
  stop-opacity: 0;
}

.d3e5ejb3h {
  stop-color: var(--svg-color--1e9fe4, #1E9FE4);
}

.e2etblb5i {
  stop-color: var(--svg-color--48e0ff, #48E0FF);
}

.ed70xxbmp {
  d: path("m26.408 15.971l-9.69-9.545a.923.923 0 0 0-1.303 0s-.01 0-.01.01l-9.71 9.556a.9.9 0 0 0 0 1.283a.93.93 0 0 0 1.303 0l8.888-8.757a.25.25 0 0 1 .35 0l8.858 8.726c.36.36.944.36 1.303 0c.36-.36.37-.924.01-1.273");
}

.eeh5esb7i {
  d: path("M21.777 21.705h-3.185a.637.637 0 0 1-.637-.637v-3.186c0-.358.29-.637.637-.637h3.185c.357 0 .637.29.637.637v3.186a.63.63 0 0 1-.637.637");
}

.ekszfhgkk {
  stop-color: var(--svg-color--eaaa75, #EAAA75);
  stop-opacity: 0;
}

.f2hgsjbqb {
  stop-color: var(--svg-color--60fb9a, #60FB9A);
}

.f9x44vo9q {
  d: path("M28.958 20.1a1.53 1.53 0 0 0 1.014-1.436c0-.845-.695-1.53-1.554-1.53c-.584 0-1.092.317-1.358.786a.95.95 0 0 1-.44.384a1.037 1.037 0 0 0-.18 1.795z");
}

.ft5dv1b6b {
  fill: none;
}

.g3xjxtboo {
  d: path("M16.155 25.235h-5.889v-7.122a1 1 0 0 1 1.001-.988h3.887a1 1 0 0 1 1 .988z");
}

.gexqvtwki {
  d: path("M26.504 26.08a2.8 2.8 0 0 0 1.854-2.623c0-1.544-1.271-2.796-2.84-2.796a2.85 2.85 0 0 0-2.27 1.118c-.36.471-.864.865-1.347 1.21a1.9 1.9 0 0 0-.802 1.544c0 .637.317 1.2.804 1.547z");
}

.gkpww5q-f {
  stop-color: var(--svg-color--50db92, #50DB92);
}

.gmdm0tbia {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m23.629 6.16l6.53 6.43");
}

.gq308acqd {
  d: path("M4.11 6.51a.35.35 0 0 1 .35-.35h1.274a.35.35 0 0 1 .35.35v5.362H4.109z");
}

.h1djfpuxc {
  fill: var(--svg-color--31b570, #31B570);
  d: path("M24.07 25.366a4.85 4.85 0 0 1-.905-1.938c-.025-.12-.152-.197-.267-.153l-.163.061a1.168 1.168 0 0 0 .414 2.26h.815c.116 0 .178-.14.106-.23");
}

.h1je16bkl {
  stop-color: var(--svg-color--dfa276, #DFA276);
}

.h7id9xbgp {
  stop-color: var(--svg-color--c8cac6, #C8CAC6);
}

.h7l2nr80b {
  fill: var(--svg-color--895d56, #895D56);
  d: path("M14.79 21.682a.429.429 0 1 0 0-.857a.429.429 0 0 0 0 .857");
}

.hoig2xb1i {
  fill: var(--svg-color--31b570, #31B570);
  d: path("M4.472 19.71c.295-.372.44-.8.495-1.061c.014-.066.083-.108.146-.084l.09.034a.639.639 0 0 1-.227 1.236H4.53c-.064 0-.098-.076-.058-.126");
}

.hw5_rcbgc {
  stop-color: var(--svg-color--3b8478, #3B8478);
}

.hx6t6eb3x {
  stop-color: var(--svg-color--59675c, #59675C);
}

.i4uxb1epo {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.217 6.883l-9.716 9.568");
}

.i6p-dub2h {
  stop-color: var(--svg-color--ba8951, #BA8951);
}

.i829-kbbz {
  stop-color: var(--svg-color--836444, #836444);
}

.ibux5fbxv {
  stop-color: var(--svg-color--9fa1a3, #9FA1A3);
}

.ivc3auy3b {
  stop-color: var(--svg-color--beab75, #BEAB75);
}

.ixipe2brm {
  stop-color: var(--svg-color--9e413e, #9E413E);
  stop-opacity: 0;
}

.izr6bygkz {
  d: path("M29.135 19.031H18.123v-7.013l5.506-5.61l5.505 5.61z");
}

.j_loa24zq {
  stop-color: var(--svg-color--39895b, #39895B);
  stop-opacity: 0;
}

.j1zlpsbpa {
  stop-color: var(--svg-color--43b3f2, #43B3F2);
}

.j3dxsyunw {
  d: path("M9.508 25.985a.75.75 0 0 1 .75-.75h5.836a.75.75 0 0 1 .75.75v.11H9.507z");
}

.jd5pj4bbj {
  stop-color: var(--svg-color--bb825c, #BB825C);
}

.joxkjnbrh {
  stop-color: var(--svg-color--4cccff, #4CCCFF);
}

.k11oh3pvi {
  stop-color: var(--svg-color--e85430, #E85430);
}

.keuf9wi3y {
  stop-color: var(--svg-color--ebb48c, #EBB48C);
}

.kt2r_rbsm {
  stop-color: var(--svg-color--9e413e, #9E413E);
}

.l134h2b_j {
  d: path("M15.446 12.268L8.934 5.853a.62.62 0 0 0-.876 0s-.006 0-.006.007l-6.526 6.422a.604.604 0 0 0 0 .862a.627.627 0 0 0 .876 0l5.916-5.828a.25.25 0 0 1 .35 0l5.895 5.807a.62.62 0 0 0 .876 0a.595.595 0 0 0 .007-.855");
}

.ltv62lbpd {
  stop-color: var(--svg-color--3a9ee6, #3A9EE6);
}

.lx2gwjlwx {
  stop-color: var(--svg-color--42cf80, #42CF80);
}

.m9zp7-b4c {
  d: path("M15.25 25.812H9.97v-7.264c0-.553.404-1.008.897-1.008h3.485c.492 0 .897.455.897 1.009z");
}

.mddmsqhiw {
  d: path("M5.64 26.08a2.8 2.8 0 0 1-1.853-2.623c0-1.544 1.271-2.796 2.84-2.796c.928 0 1.753.439 2.27 1.118c.36.471.864.865 1.347 1.21c.486.346.801.909.801 1.544c0 .637-.316 1.2-.803 1.547z");
}

.mk0kxp2ew {
  stop-color: var(--svg-color--8e694b, #8E694B);
  stop-opacity: 0;
}

.mt-6s8beo {
  stop-color: var(--svg-color--e8bc97, #E8BC97);
}

.n9h9s3kza {
  fill: var(--svg-color--3abd6c, #3ABD6C);
  d: path("M28.958 20.1a1.53 1.53 0 0 0 1.014-1.436c0-.845-.695-1.53-1.554-1.53c-.584 0-1.092.317-1.358.786a.95.95 0 0 1-.44.384a1.037 1.037 0 0 0-.18 1.795z");
}

.ncldowb5k {
  d: path("M19.14 6.51a.35.35 0 0 1 .35-.35h1.275a.35.35 0 0 1 .35.35v5.362H19.14z");
}

.nh51m9bdp {
  stop-color: var(--svg-color--d38157, #D38157);
}

.nu-_8vbpz {
  stop-color: var(--svg-color--3b8478, #3B8478);
  stop-opacity: 0;
}

.nw_qsv-ec {
  stop-color: var(--svg-color--c77958, #C77958);
  stop-opacity: 0;
}

.o_1pjbcxb {
  stop-color: var(--svg-color--ffe9b1, #FFE9B1);
}

.o_i1ny-qt {
  stop-color: var(--svg-color--48e0ff, #48E0FF);
  stop-opacity: 0;
}

.o-gekhbbu {
  stop-color: var(--svg-color--9d3c3a, #9D3C3A);
  stop-opacity: 0;
}

.o3xwhwsse {
  stop-color: var(--svg-color--d5ad80, #D5AD80);
  stop-opacity: 0;
}

.o7-2b4b-r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m8.598 6.16l6.53 6.43");
}

.og2x-rbkq {
  stop-color: var(--svg-color--bb825c, #BB825C);
  stop-opacity: 0;
}

.olcdc20km {
  stop-color: var(--svg-color--ffd1a3, #FFD1A3);
}

.oob98ebpv {
  d: path("M14.103 19.031H3.092v-7.013l5.506-5.61l5.505 5.61z");
}

.pq25vebpj {
  stop-color: var(--svg-color--beab75, #BEAB75);
  stop-opacity: 0;
}

.pv_zrhbhj {
  stop-color: var(--svg-color--2c785b, #2C785B);
  stop-opacity: 0;
}

.pv7n3io0c {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
}

.q3hfn2asc {
  stop-color: var(--svg-color--845f3d, #845F3D);
}

.qgcnv_btp {
  fill: var(--svg-color--2ead69, #2EAD69);
  d: path("M5.64 26.08a2.8 2.8 0 0 1-1.853-2.623c0-1.544 1.271-2.796 2.84-2.796c.928 0 1.753.439 2.27 1.118c.36.471.864.865 1.347 1.21c.486.346.801.909.801 1.544c0 .637-.316 1.2-.803 1.547z");
}

.ql4_rdbeu {
  stop-color: var(--svg-color--eaaa75, #EAAA75);
}

.rakas7bcy {
  stop-color: var(--svg-color--b55852, #B55852);
  stop-opacity: 0;
}

.rh7pjiozr {
  stop-color: var(--svg-color--845f3d, #845F3D);
  stop-opacity: 0;
}

.rpggkhbuy {
  stop-color: var(--svg-color--ca222b, #CA222B);
}

.se1dg36cr {
  stop-color: var(--svg-color--39895b, #39895B);
}

.snyc7730a {
  d: path("m30.477 12.268l-6.511-6.415a.62.62 0 0 0-.876 0s-.007 0-.007.007l-6.525 6.422a.604.604 0 0 0 0 .862a.627.627 0 0 0 .875 0l5.916-5.828a.25.25 0 0 1 .35 0l5.895 5.807a.62.62 0 0 0 .876 0a.596.596 0 0 0 .007-.855");
}

.sqabk-b9d {
  stop-color: var(--svg-color--ba8951, #BA8951);
  stop-opacity: 0;
}

.t0d8u9fem {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m23.629 6.16l-6.53 6.43");
}

.t14pfjqht {
  stop-color: var(--svg-color--1e9fe4, #1E9FE4);
  stop-opacity: 0;
}

.t3nb6qaow {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.217 6.883l9.717 9.568");
}

.t7pzc9bko {
  stop-color: var(--svg-color--b55852, #B55852);
}

.t97x2ibwe {
  d: path("M3.14 20.1a1.53 1.53 0 0 1-1.015-1.436c0-.845.696-1.53 1.554-1.53c.584 0 1.092.317 1.358.786a.95.95 0 0 0 .441.384c.365.165.62.528.62.95c0 .348-.174.656-.44.846z");
}

.tcttjrbhj {
  d: path("M1.986 18.703h27.986V30H1.986z");
}

.tniejuz7g {
  stop-color: var(--svg-color--d7905f, #D7905F);
}

.tnuyfsboe {
  stop-color: var(--svg-color--9f6941, #9F6941);
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.ujxwohptv {
  stop-color: var(--svg-color--9b665e, #9B665E);
}

.uliagebas {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
  stop-opacity: 0;
}

.uwl25k4xr {
  stop-color: var(--svg-color--c8cac6, #C8CAC6);
  stop-opacity: 0;
}

.v6xq5oj1z {
  stop-color: var(--svg-color--2c785b, #2C785B);
}

.vnara5bda {
  stop-color: var(--svg-color--805139, #805139);
}

.vttv7fbef {
  stop-color: var(--svg-color--f24747, #F24747);
}

.vu2peg21y {
  stop-color: var(--svg-color--9d3c3a, #9D3C3A);
}

.vyow51wth {
  stop-color: var(--svg-color--c11c2a, #C11C2A);
}

.w_5a8mv2g {
  stop-color: var(--svg-color--c4c1c7, #C4C1C7);
}

.wdq9jxbgd {
  fill: var(--svg-color--2ba75c, #2BA75C);
  d: path("M3.14 20.1a1.53 1.53 0 0 1-1.015-1.436c0-.845.696-1.53 1.554-1.53c.584 0 1.092.317 1.358.786a.95.95 0 0 0 .441.384c.365.165.62.528.62.95c0 .348-.174.656-.44.846z");
}

.wkn48ebdp {
  stop-color: var(--svg-color--60fb9a, #60FB9A);
  stop-opacity: 0;
}

.wkt6lhbex {
  fill: var(--svg-color--2ead69, #2EAD69);
  d: path("M26.504 26.08a2.8 2.8 0 0 0 1.854-2.623c0-1.544-1.271-2.796-2.84-2.796a2.85 2.85 0 0 0-2.27 1.118c-.36.471-.864.865-1.347 1.21a1.9 1.9 0 0 0-.802 1.544c0 .637.317 1.2.804 1.547z");
}

.wr52h6aeu {
  fill: var(--svg-color--31b570, #31B570);
  d: path("M27.625 19.71c-.295-.372-.44-.8-.495-1.061c-.014-.066-.083-.108-.146-.084l-.089.034a.64.64 0 0 0 .227 1.236h.446c.063 0 .097-.076.057-.126");
}

.x6-g55bew {
  d: path("M24.265 26.096H7.88V15.874l8.192-8.178l8.193 8.178z");
}

.xvg0squwb {
  stop-color: var(--svg-color--d5ad80, #D5AD80);
}

.xy9tfqbpg {
  fill: var(--svg-color--62393d, #62393D);
  d: path("M14.68 21.746a.424.424 0 1 0 0-.849a.424.424 0 0 0 0 .849");
}

.xyd7gvbgv {
  stop-color: var(--svg-color--59675c, #59675C);
  stop-opacity: 0;
}

.y3_h8dezk {
  stop-color: var(--svg-color--ffe9b1, #FFE9B1);
  stop-opacity: 0;
}

.zj8rkybal {
  stop-color: var(--svg-color--e39162, #E39162);
}

.zlve4xbhd {
  stop-color: var(--svg-color--8e694b, #8E694B);
}

.zq7du-bdj {
  stop-color: var(--svg-color--c77958, #C77958);
}

</style>
