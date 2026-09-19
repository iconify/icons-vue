<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6BR7zc)" class="qi5vm-bno"/><path fill="url(#iZ2CONe)" class="qi5vm-bno"/><path fill="url(#iI7tBnc)" class="qi5vm-bno"/><path fill="url(#iRyOPQd)" class="qi5vm-bno"/><path fill="url(#ierCk0c)" class="qi5vm-bno"/><path fill="url(#ix87zge)" class="qi5vm-bno"/><path fill="url(#i8eOFVb)" class="qi5vm-bno"/><path fill="url(#iq3SMvj)" class="zh7scwblw"/><path fill="url(#iUim46d)" class="fb8ai0vtx"/><path fill="url(#iSG4HZf)" class="bbea3tbpx"/><path fill="url(#i7gnFce)" class="bbea3tbpx"/><path fill="url(#izvRTgd)" class="bbea3tbpx"/><path fill="url(#ii7o90d)" class="w2evd1b3c"/><path fill="url(#in06VDb)" class="w2evd1b3c"/><path fill="url(#iXcArrj)" class="w2evd1b3c"/><path fill="url(#iFpgmod)" class="axwdtu2hc"/><path fill="url(#iNHYPMd)" class="axwdtu2hc"/><path fill="url(#iq3SMvj)" class="zh7scwblw"/><path fill="url(#iUim46d)" class="fb8ai0vtx"/><g filter="url(#iYzcrAd)"><path class="u1d7jsb6y"/></g><g filter="url(#iZhfqKc)"><path fill="url(#i7GqaVc)" class="pfpnowbaa"/></g><path fill="url(#ic7Ozbg)" class="yy0y75wcv"/><path fill="url(#i41m0Bc)" class="yy0y75wcv"/><path fill="url(#i0pbO2f)" class="yy0y75wcv"/><path fill="url(#idMLjWc)" class="yy0y75wcv"/><path fill="url(#iLmNkad)" class="yy0y75wcv"/><path fill="url(#iB8vi8x)" class="yy0y75wcv"/><path fill="url(#i6Iy0ry)" class="qv5jebbjg"/><path fill="url(#iUmuV8b)" class="qv5jebbjg"/><path fill="url(#iy9iWbe)" class="qv5jebbjg"/><path fill="url(#ivbqMhe)" class="qv5jebbjg"/><path fill="url(#i9fgn8d)" class="qv5jebbjg"/><path fill="url(#iAMD7tO)" class="qv5jebbjg"/><path fill="url(#iRmUPmd)" class="h4snadcjd"/><path clip-rule="evenodd" class="l3z082bpf"/><path fill="url(#iYHwUNe)" clip-rule="evenodd" class="ialn8vbpq"/><path fill="url(#i9QCric)" clip-rule="evenodd" class="ialn8vbpq"/><path fill="url(#iTpN8rd)" clip-rule="evenodd" class="ialn8vbpq"/><path fill="url(#iAbGvTc)" clip-rule="evenodd" class="ialn8vbpq"/><g filter="url(#iMz1fch)"><path class="zua6tomxw"/></g><path fill="url(#ilzXzqe)" class="jmplt-bdt"/><g filter="url(#ieG6c8b)"><path fill="url(#i8dRURF)" class="aquqbkbwc"/></g><g filter="url(#iUpeVod)"><path fill="url(#iFHuJLc)" clip-rule="evenodd" class="omhelabjd"/></g><g filter="url(#iXioKFI)"><path class="f08r55tca"/></g><path fill="url(#ityccEc)" clip-rule="evenodd" class="t97hycfxj"/><path fill="url(#i1VkPSb)" clip-rule="evenodd" class="t97hycfxj"/><path fill="url(#iyZFEic)" clip-rule="evenodd" class="bc8_rbz7v"/><path fill="url(#i2muEde)" clip-rule="evenodd" class="bc8_rbz7v"/><path fill="url(#ikZit1r)" class="cwwodzbjb"/><path fill="url(#ir45Bdd)" class="r_tvlv_hz"/><path fill="url(#i2Hhiec)" class="r_tvlv_hz"/><path fill="url(#ir45Bdd)" class="r_tvlv_hz"/><path fill="url(#i2Hhiec)" class="r_tvlv_hz"/><g filter="url(#iXwtr7y)"><path fill="url(#ix3TaKb)" class="c6ojpibud"/></g><path fill="url(#iR71JGe)" class="c6ojpibud"/><path fill="url(#iDYGgHW)" class="c6ojpibud"/><path fill="url(#ihGgFce)" class="c6ojpibud"/><path fill="url(#iayjKIb)" class="c6ojpibud"/><path fill="url(#iVL4DtK)" class="c6ojpibud"/><path fill="url(#i2bxVCe)" class="c6ojpibud"/><path fill="url(#iJcJjPc)" class="c6ojpibud"/><path fill="url(#iCOGIjb)" class="c6ojpibud"/><g filter="url(#i1lli5u)"><path class="w6atk-kqt"/></g><g filter="url(#iZ9dlHe)"><path fill="url(#iMmlbPc)" class="z56c12b2v"/><path fill="url(#iHCUbvb)" class="z56c12b2v"/><path fill="url(#iObkTKX)" class="z56c12b2v"/><path fill="url(#i4scyMd)" class="z56c12b2v"/></g><path fill="url(#iNiwwtF)" class="z56c12b2v"/><path fill="url(#iGItr6c)" class="z56c12b2v"/><g filter="url(#inWZVkc)"><path stroke="url(#it57IIb)" class="w1zd2kbal"/></g><path fill="url(#iU3qNXb)" class="cogr02bok"/><g filter="url(#iWKY8Zb)"><path fill="url(#iv6sFue)" class="gtbdp0bsg"/><path fill="url(#i6GxMQd)" class="gtbdp0bsg"/><path fill="url(#ioosSyc)" class="gtbdp0bsg"/><path fill="url(#ixJE8Aa)" class="gtbdp0bsg"/><path fill="url(#ilQNoFe)" class="gtbdp0bsg"/></g><g filter="url(#ixkhInb)"><path class="lob5imb1o"/></g><g filter="url(#iWXBHne)"><path class="uoxg1eqgu"/></g><g filter="url(#i0Iu3Hb)"><path fill="url(#iOfhHsu)" class="x2ctyvbwu"/><path fill="url(#ineVeMi)" class="x2ctyvbwu"/></g><g filter="url(#i8mNXoc)"><path fill="url(#iHYoPBe)" class="x7wxp-ebl"/><path fill="url(#iSqUcmb)" class="x7wxp-ebl"/><path fill="url(#imwbm8b)" class="x7wxp-ebl"/><path fill="url(#iJF5Fvb)" class="x7wxp-ebl"/><path fill="url(#iraHn9d)" class="x7wxp-ebl"/><path fill="url(#iQzfW1d)" class="x7wxp-ebl"/></g><path class="tobezjb7y"/><path fill="url(#i2rYsGc)" class="t1174bbcz"/><path class="vg-n2vbvo"/><g filter="url(#ieTo33c)"><path class="lu8xc_z5o"/><path fill="url(#isajSNd)" class="rut7c-k8d"/></g><g filter="url(#iOXlzbr)"><path fill="url(#iat5qYc)" class="ovjjuvbqy"/></g><path class="dxg186a1w"/><path fill="url(#i2n5j5c)" class="czgmoeb4f"/><path class="i19g5od0w"/><g filter="url(#ioIKhee)"><path fill="url(#ifQau6Y)" class="fytcl7bbi"/></g><g filter="url(#i4cD0Fb)"><ellipse transform="rotate(-27.914 13.482 9.938)" class="mfab67bhe"/><ellipse fill="url(#i6DuNKc)" transform="rotate(-27.914 13.482 9.938)" class="h86udlb9m"/></g><path fill="url(#iglEtjZ)" class="mrr09hb1f"/><path fill="url(#iB4azgb)" class="mrr09hb1f"/><path fill="url(#iRA1m5b)" class="mrr09hb1f"/><path fill="url(#iYjuCId)" class="fm2k-_bje"/><path fill="url(#iNQf9pz)" class="fm2k-_bje"/><g filter="url(#ijv8WWb)"><path class="udlxeab9y"/></g><g filter="url(#iM45Nie)"><path class="gwrfxybzv"/></g><g filter="url(#ixILXXN)"><path class="tk5u1yhly"/></g><g filter="url(#iSAQrpc)"><path class="iqvk0hbtj"/></g><defs><radialGradient id="i6BR7zc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.18 23.932)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="ierCk0c" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.15 8.187)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="ix87zge" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.337 23.554)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="i8eOFVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.951 30.001)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iSG4HZf" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.317 24.713)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="i7gnFce" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.721 12.33)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="ii7o90d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.216 21.963)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="in06VDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.529 20.338)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="iFpgmod" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 15.985 18.557)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="pmel6eb9u"/><stop offset="1" class="ahs4l-bul"/></radialGradient><radialGradient id="iNHYPMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.349 30.495)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rz95hov5a"/><stop offset="1" class="pwmvjmb6w"/></radialGradient><radialGradient id="idMLjWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.124 18.12)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iLmNkad" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.431 26.562)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="iB8vi8x" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.124 24.87)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="i6Iy0ry" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.372 11.28)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="iUmuV8b" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.115 24.924)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="ivbqMhe" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.286 19.495)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="i9fgn8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.083 18.323)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iAMD7tO" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.04 24.21)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="iRmUPmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.84375 3.36136 0 15.97 18.948)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="yb3h58i8u"/><stop offset=".857" class="j5609-eye"/></radialGradient><radialGradient id="i9QCric" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.49 16.385)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="iTpN8rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.567 20.041)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iAbGvTc" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.809 12.19)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="ilzXzqe" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.146 18.063)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="i8dRURF" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.233 25.909)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="i1VkPSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.115 23.573)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="ikZit1r" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.395 11.726)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="ir45Bdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.388 12.01)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="i2Hhiec" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.26 12.4)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="ix3TaKb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.744 10.95)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iDYGgHW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14299 12.963 -10.73495 -.94653 17.517 5.037)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="ihGgFce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.383 9.83)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iayjKIb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.447 -1.651)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iVL4DtK" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.055 11.335)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="i2bxVCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.083 7.949)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iJcJjPc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.782 15.022)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iCOGIjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.893 5.569)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iGItr6c" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.233 8.937)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="it57IIb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.556 -5.518)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iU3qNXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.936 14.49)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i6GxMQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.706 9.368)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ioosSyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.797 9.368)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="ixJE8Aa" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.306 -.3)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ilQNoFe" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.03 1.5)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iOfhHsu" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.837 2.887)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="ineVeMi" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.239 -5.68)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iHYoPBe" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.556 4.102)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iSqUcmb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.04 -1.713)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="imwbm8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 20.445 8.407)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iJF5Fvb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.73 3.985)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iraHn9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.389 3.86)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iQzfW1d" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.78 7.345)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="i2rYsGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.118 10.034)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isajSNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.89 10.118)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2n5j5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.754 10.034)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i6DuNKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.466 10.253)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iB4azgb" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.554 10.048)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iRA1m5b" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.914 10.592)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iNQf9pz" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.899 4.945)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="iZ2CONe" x1="23.294" x2="22.982" y1="24.612" y2="24.612" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iI7tBnc" x1="8.716" x2="9.052" y1="24.612" y2="24.612" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iRyOPQd" x1="16.161" x2="16.161" y1="30.964" y2="29.151" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iq3SMvj" x1="8.8" x2="23.176" y1="15.441" y2="15.441" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iUim46d" x1="8.8" x2="23.176" y1="15.41" y2="15.41" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="izvRTgd" x1="6.98" x2="6.98" y1="30.776" y2="29.316" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iXcArrj" x1="22.651" x2="23.43" y1="25.65" y2="25.65" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="i7GqaVc" x1="16.161" x2="23.786" y1="26.995" y2="19.401" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="ic7Ozbg" x1="21.875" x2="16.76" y1="18.39" y2="23.908" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="i41m0Bc" x1="20.029" x2="19.872" y1="15.671" y2="17.734" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="i0pbO2f" x1="17.567" x2="18.724" y1="18.916" y2="19.401" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="iy9iWbe" x1="12.255" x2="12.583" y1="23.213" y2="22.854" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iYHwUNe" x1="20.294" x2="19.622" y1="23.682" y2="23.698" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="iFHuJLc" x1="12.19" x2="12.19" y1="19.88" y2="28.463" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="ityccEc" x1="9.499" x2="10.393" y1="25.279" y2="25.279" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iyZFEic" x1="13.872" x2="14.544" y1="25.29" y2="25.29" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="i2muEde" x1="14.935" x2="14.692" y1="24.807" y2="24.807" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iR71JGe" x1="21.093" x2="16.74" y1="12.636" y2="12.636" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iMmlbPc" x1="15.936" x2="16.791" y1="11.779" y2="11.779" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iHCUbvb" x1="14.863" x2="15.937" y1="11.623" y2="11.683" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iObkTKX" x1="15.936" x2="15.936" y1="12.178" y2="13.03" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="i4scyMd" x1="15.936" x2="15.936" y1="9.93" y2="10.35" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iNiwwtF" x1="16.067" x2="16.067" y1="12.852" y2="12.793" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iv6sFue" x1="21.299" x2="11.175" y1="5.288" y2="5.288" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iat5qYc" x1="18.896" x2="18.582" y1="10.088" y2="10.281" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifQau6Y" x1="14.498" x2="14.184" y1="10.088" y2="10.281" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iglEtjZ" x1="22.372" x2="21.165" y1="10.115" y2="12.291" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iYjuCId" x1="10.086" x2="11.544" y1="10.819" y2="10.691" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="iYzcrAd" width="7.147" height="11.557" x="9.015" y="15.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".5"/></filter><filter id="iZhfqKc" width="7.147" height="11.557" x="15.909" y="15.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".5"/></filter><filter id="iMz1fch" width="3.699" height="3.699" x="16.98" y="24.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".375"/></filter><filter id="ieG6c8b" width="1.42" height="1.42" x="18.95" y="24.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24153"/></filter><filter id="iUpeVod" width="5.381" height="7.171" x="9.499" y="19.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24153"/></filter><filter id="iXioKFI" width="5.3" height="6.89" x="9.565" y="19.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".15"/></filter><filter id="iXwtr7y" width="10.97" height="12.542" x="10.873" y="4.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24153" result="effect2_innerShadow_3987_24153"/></filter><filter id="i1lli5u" width="3.754" height="4.824" x="13.79" y="9.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".5"/></filter><filter id="iZ9dlHe" width="2.077" height="3.1" x="14.897" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".05"/></filter><filter id="inWZVkc" width="3.718" height="1.573" x="14.076" y="13.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".05"/></filter><filter id="iWKY8Zb" width="12.873" height="8.356" x="9.499" y="1.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24153" result="effect2_innerShadow_3987_24153"/></filter><filter id="ixkhInb" width="2.339" height="1.19" x="17.525" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24153"/></filter><filter id="iWXBHne" width="2.339" height="1.176" x="12.269" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24153"/></filter><filter id="i0Iu3Hb" width="6.584" height="5.992" x="9.855" y="2.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".125"/></filter><filter id="i8mNXoc" width="6.362" height="5.736" x="15.777" y="3.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".125"/></filter><filter id="ieTo33c" width=".787" height=".696" x="17.384" y="9.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".05"/></filter><filter id="iOXlzbr" width=".891" height=".913" x="18.224" y="9.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".1"/></filter><filter id="ioIKhee" width=".986" height="1.04" x="13.781" y="9.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".1"/></filter><filter id="i4cD0Fb" width=".913" height=".704" x="13.026" y="9.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".05"/></filter><filter id="ijv8WWb" width="1.329" height="2.379" x="9.903" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".125"/></filter><filter id="iM45Nie" width="1.447" height="2.403" x="20.648" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".125"/></filter><filter id="ixILXXN" width="2.405" height="1.16" x="12.188" y="7.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".125"/></filter><filter id="iSAQrpc" width="2.405" height="1.16" x="17.466" y="7.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24153" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:health-worker-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ahs4l-bul {
  stop-color: var(--svg-color--b04418, #B04418);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.aquqbkbwc {
  d: path("M19.66 26.18a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.axwdtu2hc {
  d: path("M16.478 22.515c0-.04-.01-.203 0-.243l2.662-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.054.05.054.09l.056 3.6h.01v3.97h.79v-3.97l.078-3.416z");
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.bbea3tbpx {
  d: path("m5.91 22.771l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.bc8_rbz7v {
  fill-rule: evenodd;
  d: path("M14.88 23.731v2.47c0 .36-.29.65-.65.65h-.58v-.98h.25v-2.14z");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c6ojpibud {
  d: path("M11.11 13.715a3.916 3.916 0 0 0 3.887 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.433h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cogr02bok {
  d: path("M15.936 13.847c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.086-.13-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.cwwodzbjb {
  d: path("M20.797 12.2c.335-.01.65-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02q.256-.546.345-1.18z");
}

.czgmoeb4f {
  d: path("M13.752 9.557a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dxg186a1w {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.545 9.285c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.f08r55tca {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.175 26.295h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fb8ai0vtx {
  d: path("M16.01 15.411h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fm2k-_bje {
  d: path("M10.882 9.091a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.fytcl7bbi {
  d: path("M14.567 10.345c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gtbdp0bsg {
  d: path("M20.79 4.307a2.32 2.32 0 0 1 1.268 1.052a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.616-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38l.03 1.537c-.254.037-.52.122-.72.264v-1.2c0-.312-.095-.618-.27-.875a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.326 2.326 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.843 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.072");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gwrfxybzv {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.898 11.64q.057-.952.11-1.903a.955.955 0 0 1-.11 1.903");
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h4snadcjd {
  d: path("M15.97 18.721a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.h86udlb9m {
  cx: 13.482px;
  cy: 9.938px;
  rx: 0.39px;
  ry: 0.197px;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i19g5od0w {
  fill: var(--svg-color--000, #000);
  d: path("M14.263 10.45a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.ialn8vbpq {
  fill-rule: evenodd;
  d: path("M15.92 15.121a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iqvk0hbtj {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.497 8.095c-.257-.185-.898-.509-1.655-.382");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j5609-eye {
  stop-color: var(--svg-color--894e38, #894E38);
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jmplt-bdt {
  d: path("M19.66 26.73a1.26 1.26 0 1 0 0-2.519a1.26 1.26 0 0 0 0 2.52");
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l3z082bpf {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.92 15.121a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lob5imb1o {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.669 7.97a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 0 0 .067.55c.481-.058.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lu8xc_z5o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.054 9.745c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfab67bhe {
  cx: 13.482px;
  cy: 9.938px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mrr09hb1f {
  d: path("M20.858 12.29q.1-1.594.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.omhelabjd {
  fill-rule: evenodd;
  d: path("M12.19 20.862c-.94 0-1.71.761-1.71 1.709v3.3h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 0 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ovjjuvbqy {
  d: path("M18.915 10.332a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.pfpnowbaa {
  d: path("m21.878 20.155l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.297l-4.505 4.598c-.112.112-.306.038-.306-.12v-3.329c0-.037.009-.065.018-.102l2.54-5.887a.15.15 0 0 1 .038-.065c.844.269 1.64.649 2.364 1.122l.186 2.002a.214.214 0 0 1-.177.232");
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmel6eb9u {
  stop-color: var(--svg-color--e56e23, #E56E23);
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pwmvjmb6w {
  stop-color: var(--svg-color--e35628, #E35628);
  stop-opacity: 0;
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qi5vm-bno {
  d: path("M15.971 15.411c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.qv5jebbjg {
  d: path("M15.355 21.692c.262.516.262.942.262 1.306v2.99c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.189-.25l.188-2.058a.25.25 0 0 1 .113-.187a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r_tvlv_hz {
  d: path("M11.074 12.2a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rut7c-k8d {
  d: path("M18.054 9.745c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.rz95hov5a {
  stop-color: var(--svg-color--e35628, #E35628);
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.t1174bbcz {
  d: path("M18.12 9.557a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.t97hycfxj {
  fill-rule: evenodd;
  d: path("M9.5 26.19v-2.47h.98v2.14h.25v.981h-.58a.65.65 0 0 1-.65-.65");
}

.tk5u1yhly {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.563 8.141c.256-.184.897-.509 1.655-.381");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tobezjb7y {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.327 9.285c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1d7jsb6y {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.192 20.155l.732.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .01.297l4.505 4.598c.111.112.306.038.306-.12v-3.329c0-.037-.01-.065-.018-.102l-2.54-5.887a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.002a.214.214 0 0 0 .176.232");
}

.udlxeab9y {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.899 9.752a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uoxg1eqgu {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.525 7.862a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.003.001a.277.277 0 0 1-.34-.438z");
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vg-n2vbvo {
  fill: var(--svg-color--000, #000);
  d: path("M17.609 10.45c0-.285.227-.512.51-.512a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w1zd2kbal {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.585 13.452a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.w2evd1b3c {
  d: path("M26.811 27.97c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59V30h3.65z");
}

.w6atk-kqt {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.505 10.614l-.692 1.655c-.101.379.142.757.487.757h.735c.344 0 .587-.384.486-.757l-.497-1.838c-.106-.407-.407-.224-.519.183");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.x2ctyvbwu {
  d: path("m16.168 5.335l-.066-.137a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.33-.253q.047-.047.1-.104c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x7wxp-ebl {
  d: path("m21.148 8.707l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.083.517 2.903 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.yb3h58i8u {
  stop-color: var(--svg-color--ab716d, #AB716D);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yy0y75wcv {
  d: path("M16.634 21.692c-.262.516-.262.942-.262 1.306v2.99c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.058a.25.25 0 0 0-.113-.187a10.5 10.5 0 0 0-2.426-1.134a.3.3 0 0 0-.04.08z");
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z56c12b2v {
  d: path("m15.553 10.236l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.zh7scwblw {
  d: path("M16.34 15.411c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zua6tomxw {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.83 26.96a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

</style>
