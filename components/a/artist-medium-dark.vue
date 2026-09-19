<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHzmtfe)" class="vbuc_sdez"/><path fill="url(#inA3Tpe)" class="vbuc_sdez"/><path fill="url(#i6KXFTY)" class="vbuc_sdez"/><path fill="url(#i04jDnj)" class="vbuc_sdez"/><g filter="url(#iN0Tlwv)"><path clip-rule="evenodd" class="cvzy-mbfm"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#ioBZztm)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#iC9gYeE)"><path fill="url(#iZYJJTd)" class="rqxxjhbor"/><path fill="url(#iYcv9Wc)" class="rqxxjhbor"/></g><g filter="url(#iPfyWsd)"><path fill="url(#iCgYo9c)" class="r1d1qpblj"/><path fill="url(#iNSLv7d)" class="r1d1qpblj"/><path fill="url(#i8efCLe)" class="r1d1qpblj"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#i5nzXEb)"><path fill="url(#iIo36rp)" class="c2bk9yb6a"/><path fill="url(#ignAelv)" class="c2bk9yb6a"/></g><path fill="url(#iqkeVzb)" class="b8wkgccyf"/><path fill="url(#ib6zMLd)" class="b8wkgccyf"/><g filter="url(#iSdnrDd)"><path fill="url(#izcCUib)" class="uj-94poim"/></g><g filter="url(#iYTnsxd)"><path class="oh_l9db2x"/></g><g filter="url(#ifaJfwF)"><path class="teu3yl5ky"/></g><g filter="url(#ic74Ldc)"><path class="waw2uhbiy"/></g><g filter="url(#i3uG8Qc)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#i2rqnxc)"><path fill="url(#iV1Av9c)" class="yx08hybsl"/></g><g filter="url(#i58haec)"><path fill="url(#iO8TsTc)" class="hvyevjb_p"/></g><path fill="url(#i4gM3yb)" class="hvyevjb_p"/><path fill="url(#ivW3tMd)" class="h36ax9_yz"/><path fill="url(#i1IV5se)" class="h36ax9_yz"/><path fill="url(#iK4s60b)" class="jhj9frbew"/><path fill="url(#ib9Hitc)" class="jhj9frbew"/><path fill="url(#iTfdAvb)" class="vfzn0su_w"/><path fill="url(#iTkYgvd)" class="vfzn0su_w"/><path fill="url(#iqMfzad)" class="vfzn0su_w"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iw1p9ce)" class="s80w1fafw"/><g filter="url(#iBkxi7e)"><path fill="url(#i1FSYJc)" class="o7yoj0s6u"/><path fill="url(#iZLdWle)" class="o7yoj0s6u"/><path fill="url(#iZaoaBd)" class="o7yoj0s6u"/><path fill="url(#izMYsjd)" class="o7yoj0s6u"/></g><path fill="url(#ieEgdTd)" class="fbdpw4j2k"/><g filter="url(#i0gMuab)"><path fill="url(#iSbgAfc)" class="i9gy75kqp"/><path fill="url(#ibRVbPt)" class="i9gy75kqp"/><path fill="url(#iR3m9Xd)" class="i9gy75kqp"/><path fill="url(#ixbEKEd)" class="i9gy75kqp"/></g><g filter="url(#ixUrsJp)"><path fill="url(#i929CYc)" class="qppq5ybfo"/><path fill="url(#iILW5qO)" class="qppq5ybfo"/><path fill="url(#iBokQme)" class="qppq5ybfo"/><path fill="url(#iNISImd)" class="qppq5ybfo"/><path fill="url(#iCmIxte)" class="qppq5ybfo"/></g><g filter="url(#itxz5ne)"><path stroke="url(#iX7P55F)" class="ct65j078y"/></g><g filter="url(#ix6ZJZd)"><path stroke="url(#ihsaQCd)" class="ze5nteb_r"/></g><g filter="url(#ibRxNBd)"><path stroke="url(#i3Vf8mb)" class="jz78atb4u"/></g><path fill="url(#ip6sHGc)" class="k-ui63bml"/><path fill="url(#iWpaUPd)" class="zcxyhibbq"/><g filter="url(#iIadpHc)"><path fill="url(#iUDCizb)" class="vmwsxjbzv"/><path fill="url(#imE6YFd)" class="vmwsxjbzv"/></g><path fill="url(#i2W9gje)" class="vmwsxjbzv"/><path fill="url(#iDBPVwe)" class="vmwsxjbzv"/><path fill="url(#iO17HgX)" class="vmwsxjbzv"/><path fill="url(#iyLi3Ad)" class="vmwsxjbzv"/><path fill="url(#iPWAavc)" class="vmwsxjbzv"/><path fill="url(#iomWgRb)" class="vmwsxjbzv"/><path fill="url(#ix9om1b)" class="vmwsxjbzv"/><g filter="url(#ioFh3oe)"><path class="d8s7k0b-m"/></g><g filter="url(#iCxxhPc)"><path class="mdjz8kbri"/><path fill="url(#iE7ZirG)" class="ywgfz3bpv"/><path fill="url(#iXc3FYX)" class="ywgfz3bpv"/><path fill="url(#itLyT1b)" class="ywgfz3bpv"/><path fill="url(#ioUthYd)" class="ywgfz3bpv"/><path fill="url(#ig7O35d)" class="ywgfz3bpv"/></g><path fill="url(#i6HF7pe)" class="ywgfz3bpv"/><path fill="url(#iwnfz3d)" class="ywgfz3bpv"/><g filter="url(#i0jWJDc)"><path stroke="url(#iCkwjmb)" class="zzlk6cbpf"/></g><path fill="url(#i6Objly)" class="s1kl3yohs"/><g filter="url(#icS9XFm)"><path class="pux477hlu"/></g><g filter="url(#iCfWJbb)"><path class="zv_8pcb5c"/></g><path class="fzl5a8b_j"/><path fill="url(#iS0n2Bd)" class="a0ditfo3z"/><path class="phlamtb2c"/><g filter="url(#ilmSm7b)"><path class="dea_x4yps"/><path fill="url(#iaQPNRb)" class="leuog6b3j"/></g><g filter="url(#iL6MkMe)"><path fill="url(#ibmoomb)" class="t-s8-4gfe"/></g><path class="cspvum9if"/><path fill="url(#i8AJMbe)" class="zhkgq7bex"/><path class="jbmi23bxx"/><g filter="url(#io8uQRd)"><path fill="url(#ijrNN9b)" class="a2oppkbgc"/></g><g filter="url(#iGU2VAb)"><ellipse transform="rotate(-27.914 13.688 9.883)" class="bjeicf0bm"/><ellipse fill="url(#iiIueLb)" transform="rotate(-27.914 13.688 9.883)" class="x8xbz6r1q"/></g><path fill="url(#iv3N4pc)" class="hdeyp_qqk"/><path fill="url(#iPZ9ypd)" class="hdeyp_qqk"/><path fill="url(#icxqSKe)" class="hdeyp_qqk"/><path fill="url(#iTLcGrz)" class="hdeyp_qqk"/><path fill="url(#ijVmTKe)" class="xyg80fboq"/><path fill="url(#ilja51b)" class="xyg80fboq"/><g filter="url(#iZHScSb)"><path fill="url(#imAeWxc)" class="cesufhovt"/></g><g filter="url(#ij9Ml2C)"><path fill="url(#i0KSujb)" class="e1b_as25z"/></g><g filter="url(#ilXZfJb)"><path class="rad__zbfl"/></g><g filter="url(#iFRKXYc)"><path class="ue_-ozblu"/></g><path fill="url(#igWAw5l)" class="hw5lu9yyj"/><path fill="url(#ivIuiNc)" class="hw5lu9yyj"/><path fill="url(#i1ZC3Ed)" class="lnkgikb1m"/><path fill="url(#ixBratb)" class="lnkgikb1m"/><path fill="url(#iXiXb4d)" class="tpv18l7lf"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><path fill="url(#iCultsb)" class="tpv18l7lf"/><g filter="url(#iKDkGWd)"><path fill="url(#iwfm65c)" class="ansdxpmor"/></g><g filter="url(#iCIdz5P)"><path fill="url(#in6AZkm)" class="ok43c2qsk"/></g><defs><radialGradient id="iHzmtfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.975)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="i6KXFTY" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.975)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="iYcv9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.422 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iV1Av9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.783)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="ivW3tMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42193 -3.27267 0 16.143 17.096)" gradientUnits="userSpaceOnUse"><stop offset=".395" class="skdvgyl5e"/><stop offset="1" class="id0p6ebfb"/></radialGradient><radialGradient id="i1IV5se" cx="0" cy="0" r="1" gradientTransform="matrix(3.94043 .98437 -.58167 2.32843 14.233 16.566)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="qr2pggbsg"/><stop offset=".952" class="a58eh2bhn"/></radialGradient><radialGradient id="iK4s60b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59797 1.31329 -1.29023 -1.56991 28.701 23.652)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="ib9Hitc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibRVbPt" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.595)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="iILW5qO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iBokQme" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iNISImd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iCmIxte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ip6sHGc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.941 20.934)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iWpaUPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 10.085 12.327)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iUDCizb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.95 10.896)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="imE6YFd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.616 8.194)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iDBPVwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.589 9.583)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iO17HgX" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09428 1.19083 .00428 13.841 9.63)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iyLi3Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.575 11.883)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iPWAavc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.35 8.162)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iomWgRb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.211 13.861)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ix9om1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31977 -11.6636 0 16.189 8.244)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="dzncn8b4b"/><stop offset="1" class="g1yxg76gz"/></radialGradient><radialGradient id="iXc3FYX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.608 12.256)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="ioUthYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.724 11.686)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iwnfz3d" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 6.004 9.018)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="i6Objly" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.65 14.518)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iS0n2Bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.324 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iaQPNRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.096 10.063)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8AJMbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.96 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iiIueLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.673 10.199)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPZ9ypd" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.759 9.994)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="icxqSKe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.12 10.538)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iTLcGrz" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.234 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ilja51b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.226 10.634)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="imAeWxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.226 10.638)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="igWAw5l" cx="0" cy="0" r="1" gradientTransform="matrix(.10988 2.06825 -.2705 .01437 21.685 6.576)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="tsl7a682d"/><stop offset=".983" class="x9lmz_g3o"/></radialGradient><radialGradient id="ivIuiNc" cx="0" cy="0" r="1" gradientTransform="matrix(.77484 2.11719 -.88881 .32528 20.631 6.936)" gradientUnits="userSpaceOnUse"><stop offset=".498" class="iknen6bxg"/><stop offset="1" class="t1quln-9k"/></radialGradient><radialGradient id="ixBratb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75581 -.2665 0 10.678 6.809)" gradientUnits="userSpaceOnUse"><stop class="cn_gd9b3y"/><stop offset="1" class="t4u9hgbuu"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iN0Tlwv" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".75"/></filter><filter id="ioBZztm" width="8.987" height="5.737" x="11.649" y="14.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".2"/></filter><filter id="iC9gYeE" width="2.812" height="4.17" x="13.354" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="iPfyWsd" width="2.762" height="4.17" x="16.118" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="i5nzXEb" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="iSdnrDd" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2388" result="effect2_innerShadow_4002_2388"/></filter><filter id="iYTnsxd" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".075"/></filter><filter id="ifaJfwF" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".075"/></filter><filter id="ic74Ldc" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".075"/></filter><filter id="i3uG8Qc" width="2.58" height="2.68" x="7.143" y="22.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2388" result="effect2_innerShadow_4002_2388"/></filter><filter id="i2rqnxc" width="2.58" height="2.68" x="10.143" y="25.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2388" result="effect2_innerShadow_4002_2388"/></filter><filter id="i58haec" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2388" result="effect2_innerShadow_4002_2388"/></filter><filter id="iBkxi7e" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="i0gMuab" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="ixUrsJp" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="itxz5ne" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".05"/></filter><filter id="ix6ZJZd" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".05"/></filter><filter id="ibRxNBd" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".05"/></filter><filter id="iIadpHc" width="11.22" height="12.542" x="11.079" y="4.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2388" result="effect2_innerShadow_4002_2388"/></filter><filter id="ioFh3oe" width="3.747" height="4.9" x="14.126" y="9.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".5"/></filter><filter id="iCxxhPc" width="2.277" height="3.3" x="15.003" y="9.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".1"/></filter><filter id="i0jWJDc" width="3.718" height="1.573" x="14.282" y="13.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".05"/></filter><filter id="icS9XFm" width="2.339" height="1.19" x="17.731" y="7.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="iCfWJbb" width="2.339" height="1.176" x="12.475" y="7.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2388"/></filter><filter id="ilmSm7b" width=".787" height=".696" x="17.59" y="9.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".05"/></filter><filter id="iL6MkMe" width=".891" height=".913" x="18.43" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".1"/></filter><filter id="io8uQRd" width=".986" height="1.04" x="13.987" y="9.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".1"/></filter><filter id="iGU2VAb" width=".913" height=".705" x="13.232" y="9.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".05"/></filter><filter id="iZHScSb" width="1.329" height="2.379" x="10.061" y="9.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".125"/></filter><filter id="ij9Ml2C" width="1.947" height="2.903" x="20.585" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".25"/></filter><filter id="ilXZfJb" width="2.405" height="1.16" x="12.394" y="7.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".125"/></filter><filter id="iFRKXYc" width="2.405" height="1.16" x="17.673" y="7.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".125"/></filter><filter id="iKDkGWd" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".5"/></filter><filter id="iCIdz5P" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2388" stdDeviation=".75"/></filter><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="iNSLv7d" x1="16.549" x2="17.449" y1="19.059" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iw1p9ce" x1="26.353" x2="26.353" y1="20.725" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="izMYsjd" x1="26.502" x2="26.502" y1="20.725" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="i929CYc" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iX7P55F" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ihsaQCd" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i3Vf8mb" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i2W9gje" x1="21.299" x2="18.77" y1="12.581" y2="12.581" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iE7ZirG" x1="16.98" x2="16.142" y1="11.57" y2="11.605" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="itLyT1b" x1="16.142" x2="16.142" y1="12.709" y2="12.244" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ig7O35d" x1="16.142" x2="16.142" y1="10.004" y2="10.551" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i6HF7pe" x1="16.557" x2="16.557" y1="12.847" y2="12.654" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iCkwjmb" x1="14.94" x2="15.258" y1="14.28" y2="13.446" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ibmoomb" x1="19.102" x2="18.788" y1="10.033" y2="10.226" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijrNN9b" x1="14.704" x2="14.39" y1="10.033" y2="10.226" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iv3N4pc" x1="22.578" x2="21.371" y1="10.06" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="ijVmTKe" x1="10.292" x2="11.75" y1="10.764" y2="10.637" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="i0KSujb" x1="21.558" x2="21.558" y1="9.678" y2="11.582" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="i1ZC3Ed" x1="11.29" x2="10.302" y1="7.342" y2="7.342" gradientUnits="userSpaceOnUse"><stop offset=".476" class="p1w14cckd"/><stop offset="1" class="d_e3-zbue"/></linearGradient><linearGradient id="iXiXb4d" x1="15.975" x2="16.813" y1="2.025" y2="6.975" gradientUnits="userSpaceOnUse"><stop class="nblx7ib8n"/><stop offset="1" class="h7is5ynaf"/></linearGradient><linearGradient id="iCultsb" x1="17.532" x2="17.532" y1="6.928" y2="6.6" gradientUnits="userSpaceOnUse"><stop class="hj8-3eb_v"/><stop offset="1" class="zofh5ufwh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:artist-medium-dark" /></template>
<style>
.a0ditfo3z {
  d: path("M18.326 9.502a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a2oppkbgc {
  d: path("M14.773 10.29c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a58eh2bhn {
  stop-color: var(--svg-color--62282f, #62282F);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.ansdxpmor {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.784-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b8wkgccyf {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.533-4.61-2.954c-2.718.333-4.203 3.217-3.156 6.123z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bjeicf0bm {
  cx: 13.688px;
  cy: 9.883px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c2bk9yb6a {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.44");
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.cesufhovt {
  d: path("M11.056 9.697a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn_gd9b3y {
  stop-color: var(--svg-color--534f4e, #534F4E);
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.cspvum9if {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.75 9.23c-.652 0-1.204.45-1.354 1.06a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.272A1.4 1.4 0 0 0 13.75 9.23");
}

.ct65j078y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.952h1.797");
}

.cvzy-mbfm {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.425-1.683-2.58-3.759-2.58s-3.758 1.155-3.758 2.58c0 .979.795 1.83 1.967 2.267c-.389.436-.404.98-.404 1.486l-.014.924c-.002.176.152.312.323.266c.381-.1.909-.315 1.264-.706c.378-.415.565-.814.622-1.433c.058.62.245 1.018.622 1.433c.356.391.883.605 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.d_e3-zbue {
  stop-color: var(--svg-color--423b39, #423B39);
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.d8s7k0b-m {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.74 10.377l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.495-1.838c-.105-.408-.504-.408-.615 0");
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dea_x4yps {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.26 9.69c.064.086-.07.19-.22.303c-.151.113-.264.192-.327.107c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dzncn8b4b {
  stop-color: var(--svg-color--7e455d, #7E455D);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1b_as25z {
  d: path("M21.085 11.582q.057-.953.11-1.904a.955.955 0 0 1-.11 1.904");
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.ekxbkpvzc {
  d: path("M5.143 26.475c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fbdpw4j2k {
  d: path("m25.169 16.58l.685-.092c.322 0 .735.47.735.793c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.058.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.169.102-.19");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fzl5a8b_j {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.533 9.23c.653 0 1.204.45 1.354 1.06a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.g1yxg76gz {
  stop-color: var(--svg-color--833766, #833766);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.h36ax9_yz {
  d: path("M16.142 18.394c-1.05 0-1.908-.507-1.908-1.291V14.41c0-1.11.858-2.017 1.908-2.017s1.91.907 1.91 2.017v2.692c0 .796-.86 1.29-1.91 1.29");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h7is5ynaf {
  stop-color: var(--svg-color--3f334f, #3F334F);
}

.hdeyp_qqk {
  d: path("M21.064 12.236c.065-1.064.129-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hj8-3eb_v {
  stop-color: var(--svg-color--481b64, #481B64);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hvyevjb_p {
  d: path("M7.383 29.105a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.hw5lu9yyj {
  d: path("M20.632 6.934c.182.15.604.549.604 1.08c0 .323-.02.719-.04 1.039c.183.032.305.074.47.155c.003-.293.045-.701.14-.99c.049-.146.104-.28.157-.408c.158-.382.296-.715.167-1.189h-1.498z");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i9gy75kqp {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.075c-1.248.082-2.375.649-2.978 1.739a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.365.87-.828c0-.053-.01-.107-.02-.161v-.01c-.162-.7-.054-1.29.279-1.882a.33.33 0 0 0-.075-.387");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.id0p6ebfb {
  stop-color: var(--svg-color--6d3251, #6D3251);
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.iknen6bxg {
  stop-color: var(--svg-color--2a1c30, #2A1C30);
}

.izb4o5hjh {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
  stop-opacity: 0;
}

.j_c7fcbhg {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
}

.j-4y6njnd {
  stop-color: var(--svg-color--41225a, #41225A);
}

.j-p-7tbjt {
  stop-color: var(--svg-color--5eccf3, #5ECCF3);
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.jbmi23bxx {
  fill: var(--svg-color--000, #000);
  d: path("M14.469 10.395a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.jhj9frbew {
  d: path("M27.734 23.019a.97.97 0 0 1 .967.967V26.2h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jujuy5bla {
  stop-color: var(--svg-color--8e5e5c, #8E5E5C);
}

.juq22w2kb {
  stop-color: var(--svg-color--ab95b9, #AB95B9);
}

.jvqqj3hdm {
  stop-color: var(--svg-color--c01b54, #C01B54);
}

.jyboxmbnp {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
}

.jz78atb4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 28.562h1.797");
}

.k-ui63bml {
  d: path("M21.003 12.145c.335-.01.65-.124.905-.308v.93c0 .894-.533 1.69-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.leuog6b3j {
  d: path("M18.26 9.69c.064.086-.07.19-.22.303c-.151.113-.264.192-.327.107c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lnkgikb1m {
  d: path("m11.55 6.901l-.402.96c-.088.268-.06.68-.06 1.18a1.6 1.6 0 0 0-.537.176v-.5c0-.15 0-.312-.154-.775l-.04-.12c-.172-.51-.274-.812-.123-1.302z");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m9kxmpbyp {
  stop-color: var(--svg-color--603a3e, #603A3E);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbdolbbcq {
  stop-color: var(--svg-color--ff5aaa, #FF5AAA);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdjz8kbri {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.76 10.18l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n2f566bzz {
  stop-color: var(--svg-color--66606e, #66606E);
  stop-opacity: 0;
}

.n39vpub1b {
  cx: 16.142px;
  cy: 17.066px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 3.844px;
  ry: 2.219px;
}

.n4l67hb-g {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nblx7ib8n {
  stop-color: var(--svg-color--352b40, #352B40);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o7yoj0s6u {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.114a11.5 11.5 0 0 0-.432-1.876h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.112z");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.ok43c2qsk {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.213c-.174.135-.48.54-.31 1.08c.17.542.574.651.754.638c3.302-.637 3.92-1.815 2.703-1.93");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p1w14cckd {
  stop-color: var(--svg-color--27172c, #27172C);
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.phlamtb2c {
  fill: var(--svg-color--000, #000);
  d: path("M17.815 10.395c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.pux477hlu {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.875 7.916a1.85 1.85 0 0 0-.688-.412c-.304-.095-.685-.121-1.213-.057a.277.277 0 1 0 .068.551c.481-.059.776-.028.978.035c.199.063.333.164.49.301a.277.277 0 0 0 .364-.418");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qmqo746eg {
  stop-color: var(--svg-color--e0ad88, #E0AD88);
}

.qn-z6_0fu {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
  stop-opacity: 0;
}

.qob7fubko {
  stop-color: var(--svg-color--d42045, #D42045);
}

.qppq5ybfo {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qr2pggbsg {
  stop-color: var(--svg-color--62282f, #62282F);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r1d1qpblj {
  d: path("M18.221 19.957c-.824-.79-1.717-.937-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.467 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rad__zbfl {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.769 8.086c.257-.184.897-.508 1.655-.38");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rqxxjhbor {
  d: path("M14.064 19.957c.824-.79 1.717-.937 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.467-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.s1kl3yohs {
  d: path("M16.142 13.792c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.208c.335.508.919.846 1.584.846s1.248-.338 1.583-.846c.086-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.skdvgyl5e {
  stop-color: var(--svg-color--7c3954, #7C3954);
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t-s8-4gfe {
  d: path("M19.12 10.277a.84.84 0 0 0-.23-.463l-.26.286l.117.228z");
}

.t1quln-9k {
  stop-color: var(--svg-color--2a1c30, #2A1C30);
  stop-opacity: 0;
}

.t4u9hgbuu {
  stop-color: var(--svg-color--534f4e, #534F4E);
  stop-opacity: 0;
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.teu3yl5ky {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M11.32 28.314a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.tm2bmw9uh {
  stop-color: var(--svg-color--4cc6ef, #4CC6EF);
}

.tpv18l7lf {
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tsl7a682d {
  stop-color: var(--svg-color--4c484a, #4C484A);
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ue_-ozblu {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.703 8.04c-.257-.184-.898-.508-1.655-.381");
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uj-94poim {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.977c-2.718.336-4.203 3.243-3.156 6.172z");
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vbuc_sdez {
  d: path("M9.143 17.99a10.96 10.96 0 0 1 7-2.515c2.658 0 5.097.943 7 2.514v11.986h-14z");
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vfzn0su_w {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.506z");
}

.vmwsxjbzv {
  d: path("M11.317 13.66a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418H14.42c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.556");
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.x8xbz6r1q {
  cx: 13.688px;
  cy: 9.883px;
  rx: 0.39px;
  ry: 0.197px;
}

.x9lmz_g3o {
  stop-color: var(--svg-color--444041, #444041);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xyg80fboq {
  d: path("M11.098 9.032a1.62 1.62 0 0 0-1.393 1.598c0 .859.674 1.56 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.ywgfz3bpv {
  d: path("m15.76 10.18l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.yx08hybsl {
  d: path("M11.383 28.263a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.zcxyhibbq {
  d: path("M11.28 12.145a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zhkgq7bex {
  d: path("M13.958 9.502a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.zofh5ufwh {
  stop-color: var(--svg-color--481b64, #481B64);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zv_8pcb5c {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.73 7.807a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

.zzlk6cbpf {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.79 13.397a.23.23 0 0 0-.27.047a.21.21 0 0 0-.024.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.002c-.39.203-.85.32-1.35.32c-.496 0-.961-.117-1.351-.32Z");
}

</style>
