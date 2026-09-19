<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iCcyQqe)" class="d2kvgvbvc"><path fill="url(#imeSCmO)" class="hf7j1mwxc"/><path fill="url(#itSwLPb)" class="hf7j1mwxc"/><path fill="url(#irtR9eb)" class="hf7j1mwxc"/><path fill="url(#ihh2Gce)" class="hf7j1mwxc"/><path fill="url(#iYuPlZb)" class="hf7j1mwxc"/><path fill="url(#itIXpBb)" class="hf7j1mwxc"/><path fill="url(#iBAUzib)" class="hf7j1mwxc"/><path fill="url(#igLatwc)" class="hf7j1mwxc"/><path fill="url(#iOP6Jbd)" class="hf7j1mwxc"/></g><path fill="url(#iAeu2Ub)" clip-rule="evenodd" class="hokoarktc"/><path fill="url(#i7tGT2c)" clip-rule="evenodd" class="hokoarktc"/><path fill="url(#ihZveBc)" clip-rule="evenodd" class="hokoarktc"/><path fill="url(#i5PJmdd)" clip-rule="evenodd" class="hokoarktc"/><path class="t11jj7g0p"/><path fill="url(#ilc6PWK)" class="y8ddjqa_l"/><g filter="url(#i383YLd)"><path fill="url(#ilZx7qb)" class="ol5q01bzf"/><path fill="url(#ioCP6cd)" class="ol5q01bzf"/><path fill="url(#ioZ82Ob)" class="ol5q01bzf"/></g><g filter="url(#iUjq5zd)"><path fill="url(#ir60ydb)" class="nxcp7drxh"/></g><g filter="url(#iFdAOQd)"><path fill="url(#iooalOK)" class="srddfxbul"/></g><g filter="url(#iD7myQc)"><path class="j4yu7gpks"/><path fill="url(#ii916rb)" class="rru85ybco"/></g><g filter="url(#iNeG4Cc)"><path class="ide6vizoj"/><path fill="url(#isyKeQc)" class="uz71m0bcb"/></g><g filter="url(#i4JPrIL)"><path fill="url(#i422mCd)" class="avc38xboi"/><path fill="url(#iTWLZOd)" class="avc38xboi"/><path fill="url(#icrGkTb)" class="avc38xboi"/><path fill="url(#itdTm1c)" class="avc38xboi"/><path fill="url(#iNbV9Ad)" class="avc38xboi"/></g><path fill="url(#iDErkGe)" class="avc38xboi"/><g filter="url(#iac0GFd)"><path class="zdmgu47df"/></g><g filter="url(#izD0UKb)"><path fill="url(#i9BBxve)" class="i4-il_z6k"/><path fill="url(#iYeysMc)" class="i4-il_z6k"/><path fill="url(#iwXkXQb)" class="i4-il_z6k"/><path fill="url(#igLYAHb)" class="i4-il_z6k"/></g><g filter="url(#iDCJktj)"><path fill="url(#iq43gmd)" class="m4uik1qzh"/></g><g filter="url(#i3f3iKc)"><path stroke="url(#iNLm6Wd)" class="ecm0zqbhs"/></g><path class="bieie1q3p"/><g filter="url(#iKzvNIe)"><path fill="url(#iCesN2c)" class="qswustbfm"/><path fill="url(#iOJZ8Pd)" class="qswustbfm"/></g><g filter="url(#iMCX4rt)"><path fill="url(#iZvlYNd)" class="yd5uj4llx"/><path fill="url(#ij7Rd0d)" class="yd5uj4llx"/><path fill="url(#iaYf8fg)" class="yd5uj4llx"/></g><g filter="url(#ifbH9db)"><path stroke="url(#iYj0TPd)" class="pjb1_mveq"/></g><path fill="url(#i96TgAc)" class="fl7kbbbgj"/><path fill="url(#iTl8Fxw)" class="x22v_oxmd"/><path fill="url(#iDyLvtb)" class="rjaj9xbwv"/><path fill="url(#i4fHXlb)" class="rjaj9xbwv"/><path fill="url(#irVgrkd)" class="rjaj9xbwv"/><g filter="url(#iOmLdTT)"><path fill="url(#iO2hU6b)" class="be_37eq6m"/><path fill="url(#ivWEl9c)" class="be_37eq6m"/><path fill="url(#iv23YKb)" class="be_37eq6m"/><path fill="url(#ihlKTab)" class="be_37eq6m"/></g><g filter="url(#iSJnScB)"><path fill="url(#iUBNkNd)" class="iv8lx-bbk"/></g><g filter="url(#ipGB1Zc)"><path stroke="url(#iIIGXLs)" class="nx-0f1bho"/></g><g filter="url(#idBntwd)"><path fill="url(#iNK4qAc)" class="pl207l2go"/></g><g filter="url(#igYHFNb)"><path stroke="url(#iu5NXfb)" class="r4jombc7m"/></g><g filter="url(#iEiCryc)"><path fill="url(#iTHySxe)" class="udb4a2bwg"/><path fill="url(#iSlL77c)" class="udb4a2bwg"/></g><g filter="url(#ivhbEfe)"><path fill="url(#ibZtc0b)" class="ai8tm4gte"/><path fill="url(#izc3wGc)" class="ai8tm4gte"/><path fill="url(#ikkmfve)" class="ai8tm4gte"/><path fill="url(#iw3rtTI)" class="ai8tm4gte"/></g><path fill="url(#ipRXIhc)" class="mo17i3bvc"/><path fill="url(#iuH4oYb)" class="mo17i3bvc"/><path fill="url(#iCrA8fe)" class="xb-sglp8w"/><path fill="url(#io7rQfe)" class="xb-sglp8w"/><g filter="url(#iJ68P2c)"><path fill="url(#i53TCXp)" class="yueg0n5my"/><path fill="url(#iHWyiib)" class="yueg0n5my"/><path fill="url(#i2sZlYb)" class="yueg0n5my"/><path fill="url(#i3HuMMb)" class="yueg0n5my"/><path fill="url(#ip1EIwd)" class="yueg0n5my"/></g><path fill="url(#ifbJ2Gz)" class="yueg0n5my"/><g filter="url(#iVndq0d)"><path fill="url(#i7qQYVb)" class="emrn-tmef"/></g><g filter="url(#iEjd1ce)" class="tryqaac1t"><path stroke="url(#iDv1Xeb)" class="bvs2yab1t"/><path stroke="url(#ihfygKe)" class="bvs2yab1t"/></g><g filter="url(#if6BOsc)" class="tryqaac1t"><path stroke="url(#i2KjJpb)" class="jfgmi3bgp"/><path stroke="url(#iCd8Rhc)" class="jfgmi3bgp"/></g><g filter="url(#iXwkCTd)"><path fill="url(#iZEtgUO)" class="z47nt4bif"/></g><g filter="url(#i9r32Cw)"><path fill="url(#ishPDuL)" class="eevw7bbab"/></g><g filter="url(#iXWZwOe)"><path class="c1pc50b3k"/></g><g filter="url(#i29Ctfb)"><path clip-rule="evenodd" class="qwzeypbhs"/></g><g filter="url(#iCWMcGd)"><path class="f65hhupfk"/></g><g filter="url(#i3fawuc)"><path class="qe8hvs01u"/></g><g filter="url(#iv0y3tD)"><path stroke="url(#iMIvSAe)" class="aeq1u9-lv"/></g><g filter="url(#i2eOqtH)"><path stroke="url(#iZbdAud)" class="qnozvmjjn"/></g><g filter="url(#ia0GSQc)"><path stroke="url(#iJobbxc)" class="exv2s-bbh"/></g><g filter="url(#ispKNMb)"><path stroke="url(#iuaKMKe)" class="o4olk18av"/></g><g filter="url(#if5CK8d)"><path stroke="url(#i36PMwc)" class="hfn_x0p8e"/></g><defs><radialGradient id="itSwLPb" cx="0" cy="0" r="1" gradientTransform="rotate(79.088 -2.96 13.98)scale(4.78973 2.88566)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="irtR9eb" cx="0" cy="0" r="1" gradientTransform="matrix(1.13345 5.87936 -6.12443 1.1807 16.17 13.408)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="ihh2Gce" cx="0" cy="0" r="1" gradientTransform="rotate(116.706 1.457 9.523)scale(2.18477 2.1213)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iYuPlZb" cx="0" cy="0" r="1" gradientTransform="matrix(.01797 2.74805 -2.86158 .0187 10.748 9.81)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="itIXpBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.58628 2.00807 -3.82533 3.02182 10.758 4.283)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iBAUzib" cx="0" cy="0" r="1" gradientTransform="matrix(-.92196 1.49868 -2.09438 -1.28842 20.37 3.981)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="igLatwc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.83658 .94116 -2.04784 -3.99616 23.488 8.738)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iOP6Jbd" cx="0" cy="0" r="1" gradientTransform="rotate(-101.263 8.75 -1.502)scale(1.47718 .48432)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iAeu2Ub" cx="0" cy="0" r="1" gradientTransform="rotate(118.526 5.491 9.217)scale(11.8441 14.5952)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="j3monpcls"/><stop offset=".969" class="dqxdj-bqs"/></radialGradient><radialGradient id="ihZveBc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.25004 .37412 -6.63958 13.837 17.107)" gradientUnits="userSpaceOnUse"><stop class="n34issb-z"/><stop offset="1" class="a0d1ktmmz"/></radialGradient><radialGradient id="i5PJmdd" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -1.8125 4.88961 2.02328 19.837 17.607)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="bqexp4b8k"/><stop offset="1" class="k7gdagbzg"/></radialGradient><radialGradient id="ilc6PWK" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 1.9893 19.18 29.852)" gradientUnits="userSpaceOnUse"><stop class="n2a634bwb"/><stop offset="1" class="y9owwpbix"/></radialGradient><radialGradient id="ilZx7qb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50378 0 0 -5.6875 21.43 19.076)" gradientUnits="userSpaceOnUse"><stop class="pwe9avbwo"/><stop offset="1" class="r5lqkxb5o"/></radialGradient><radialGradient id="ioCP6cd" cx="0" cy="0" r="1" gradientTransform="rotate(-154.983 12.292 9.018)scale(2.5864 3.5607)" gradientUnits="userSpaceOnUse"><stop class="k27foaczd"/><stop offset="1" class="if-fw02py"/></radialGradient><radialGradient id="ioZ82Ob" cx="0" cy="0" r="1" gradientTransform="rotate(68.199 -3.915 20.364)scale(2.27187 4.46829)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="o2nbnyboi"/><stop offset="1" class="qo4bk2z1r"/></radialGradient><radialGradient id="iooalOK" cx="0" cy="0" r="1" gradientTransform="matrix(2.39665 -1.70043 2.07614 2.9262 20.09 10.806)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="ii916rb" cx="0" cy="0" r="1" gradientTransform="rotate(-31.209 29.079 -31.696)scale(1.40215)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="isyKeQc" cx="0" cy="0" r="1" gradientTransform="rotate(169.088 4.828 6.573)scale(1.15444 1.10429)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="i422mCd" cx="0" cy="0" r="1" gradientTransform="rotate(144.332 7.712 8.007)scale(7.69734 10.3028)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iTWLZOd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9995 1.6069 -1.36334 -1.69644 17.775 10.946)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="icrGkTb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.223 16.577 1.645)scale(4.43973 5.63319)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="itdTm1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.51383 7.85245 -12.47185 2.40439 15.253 10.14)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="dcmach-gg"/><stop offset="1" class="ihi4ay12v"/></radialGradient><radialGradient id="iNbV9Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-5.41767 2.6857 -4.62396 -9.32758 16.627 12.217)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iDErkGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42151 .27405 -.90217 -4.67965 21.223 10.688)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iYeysMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23444 -2.44346 1.39818 -.70636 16.82 12.332)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iCesN2c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.76628 5.06487 -2.20895 -1.20646 11.457 4.378)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iOJZ8Pd" cx="0" cy="0" r="1" gradientTransform="rotate(133.546 4.64 4.943)scale(4.09838 2.02548)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iZvlYNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37955 5.2518 -7.45668 -1.95873 15.974 2.224)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="ij7Rd0d" cx="0" cy="0" r="1" gradientTransform="rotate(94.997 6.935 9.483)scale(3.6973 7.74838)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iaYf8fg" cx="0" cy="0" r="1" gradientTransform="matrix(-4.9218 -6.13025 5.48007 -4.39979 16.698 9.62)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="i4fHXlb" cx="0" cy="0" r="1" gradientTransform="matrix(2.79688 2.04686 -1.95763 2.67496 23.087 27.294)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="ftxo3fi5a"/><stop offset="1" class="c0n6rcbid"/></radialGradient><radialGradient id="irVgrkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.3125 -2.12008 2.12008 21.68 27.732)" gradientUnits="userSpaceOnUse"><stop class="fpntxsvxv"/><stop offset="1" class="d62ajsaau"/></radialGradient><radialGradient id="ivWEl9c" cx="0" cy="0" r="1" gradientTransform="rotate(126.08 2.976 12.005)scale(4.98797 9.68383)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7fe64b-m"/><stop offset="1" class="o3yqmrbrg"/></radialGradient><radialGradient id="iv23YKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45313 -.6875 0 13.54 28.232)" gradientUnits="userSpaceOnUse"><stop class="la4e9obft"/><stop offset="1" class="sq95r4vix"/></radialGradient><radialGradient id="ihlKTab" cx="0" cy="0" r="1" gradientTransform="rotate(-117.519 14.448 7.23)scale(1.35267 2.95016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="kc6luf8ah"/><stop offset="1" class="yit44gm3t"/></radialGradient><radialGradient id="iUBNkNd" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 -1.6057 .88152 .74629 11.43 25.654)" gradientUnits="userSpaceOnUse"><stop class="c_e6lvb0e"/><stop offset="1" class="bzrv_p78g"/></radialGradient><radialGradient id="iIIGXLs" cx="0" cy="0" r="1" gradientTransform="rotate(-162.16 15.372 12.051)scale(.71402 1.53504)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></radialGradient><radialGradient id="iSlL77c" cx="0" cy="0" r="1" gradientTransform="rotate(163.67 8.929 15.433)scale(5.1125 7.55864)" gradientUnits="userSpaceOnUse"><stop class="khg6a5-nz"/><stop offset="1" class="jyzijgb5l"/></radialGradient><radialGradient id="ibZtc0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.3638 -1.04204 1.57355 5.07954 14.95 28.758)" gradientUnits="userSpaceOnUse"><stop class="a5efvqnnr"/><stop offset="1" class="a_09dwbav"/></radialGradient><radialGradient id="iw3rtTI" cx="0" cy="0" r="1" gradientTransform="matrix(.00784 -.79123 4.62168 .04582 18.823 29.852)" gradientUnits="userSpaceOnUse"><stop offset=".067" class="fxslr17fv"/><stop offset="1" class="g228gpr1w"/></radialGradient><radialGradient id="ipRXIhc" cx="0" cy="0" r="1" gradientTransform="rotate(154.496 10.637 13.731)scale(3.77401 4.40797)" gradientUnits="userSpaceOnUse"><stop class="w-wd4mb8i"/><stop offset="1" class="jswq_j2dq"/></radialGradient><radialGradient id="iuH4oYb" cx="0" cy="0" r="1" gradientTransform="rotate(42.983 -16.059 40.17)scale(5.22527)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="i54m18vgp"/><stop offset=".995" class="nybv-x_bu"/></radialGradient><radialGradient id="io7rQfe" cx="0" cy="0" r="1" gradientTransform="matrix(.39062 -3.01563 4.79304 .62086 19.087 24.326)" gradientUnits="userSpaceOnUse"><stop class="l99uylilx"/><stop offset="1" class="xjvfic_gd"/></radialGradient><radialGradient id="i53TCXp" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.024 27.732)" gradientUnits="userSpaceOnUse"><stop class="ilmkod2my"/><stop offset="1" class="e-8izbcdn"/></radialGradient><radialGradient id="iHWyiib" cx="0" cy="0" r="1" gradientTransform="matrix(2.25781 1.67188 -.22076 .29813 19.04 23.318)" gradientUnits="userSpaceOnUse"><stop class="t9k7tiocc"/><stop offset="1" class="n84vunlix"/></radialGradient><radialGradient id="i2sZlYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.89294 1.21094 -.1599 .24995 18.78 24.85)" gradientUnits="userSpaceOnUse"><stop class="t9k7tiocc"/><stop offset="1" class="n84vunlix"/></radialGradient><radialGradient id="i3HuMMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.70752 2.17188 -.28678 .22547 20.4 22.404)" gradientUnits="userSpaceOnUse"><stop class="t9k7tiocc"/><stop offset="0" class="lsn1jtqvl"/><stop offset="1" class="r2l3kgbhd"/></radialGradient><radialGradient id="ip1EIwd" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 1.58593 -.49286 .06798 23.345 22.834)" gradientUnits="userSpaceOnUse"><stop class="cb2k4sbte"/><stop offset="1" class="gtope1bxc"/></radialGradient><radialGradient id="ihfygKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 18.869 10.312)" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></radialGradient><radialGradient id="iCd8Rhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 14.27 11.122)" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></radialGradient><filter id="iCcyQqe" width="16.897" height="17.101" x="7.744" y="1.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="i383YLd" width="12.09" height="8.809" x="14.827" y="16.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.796078 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iUjq5zd" width="3.559" height="3.459" x="9.062" y="10.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iFdAOQd" width="3.459" height="3.709" x="19.102" y="8.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iD7myQc" width="3.309" height="3.31" x="19.177" y="8.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".25"/></filter><filter id="iNeG4Cc" width="2.809" height="2.81" x="9.408" y="10.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".125"/></filter><filter id="i4JPrIL" width="11.362" height="11.251" x="9.952" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iac0GFd" width="3.001" height="3.942" x="14.398" y="10.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".25"/></filter><filter id="izD0UKb" width="2.501" height="3.43" x="14.791" y="10.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".125"/></filter><filter id="iDCJktj" width="2.501" height="3.43" x="14.727" y="10.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".125"/></filter><filter id="i3f3iKc" width="3.89" height="1.933" x="14.38" y="13.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".05"/></filter><filter id="iKzvNIe" width="4.961" height="5.989" x="7.86" y="4.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".375"/></filter><filter id="iMCX4rt" width="10.168" height="5.014" x="10.944" y="2.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".125"/></filter><filter id="ifbH9db" width="1.523" height="2.293" x="11.055" y="4.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".125"/></filter><filter id="iOmLdTT" width="12.107" height="12.935" x="3.962" y="16.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iSJnScB" width="3.547" height="2.605" x="9.915" y="23.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".25"/></filter><filter id="ipGB1Zc" width="1.338" height="3.484" x="25.32" y="26.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".05"/></filter><filter id="idBntwd" width="8.034" height="4.188" x="6.337" y="26.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".5"/></filter><filter id="igYHFNb" width="1.907" height="4.376" x="10.874" y="20.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".125"/></filter><filter id="iEiCryc" width="10.856" height="8.359" x="11.434" y="21.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="ivhbEfe" width="6.652" height="4.473" x="13.787" y="25.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.65098 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iJ68P2c" width="6.654" height="7.23" x="18.78" y="21.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.509804 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iVndq0d" width="5.813" height="5.503" x="7.399" y="21.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".5"/></filter><filter id="iEjd1ce" width="2.582" height="1.236" x="16.626" y="10.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".075"/></filter><filter id="if6BOsc" width="2.582" height="1.236" x="12.027" y="10.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".075"/></filter><filter id="iXwkCTd" width="3.872" height="2.503" x="11.377" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".3"/></filter><filter id="i9r32Cw" width="3.682" height="2.825" x="16.156" y="7.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".3"/></filter><filter id="iXWZwOe" width="2.522" height="1.466" x="11.305" y="8.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.27451 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="i29Ctfb" width="2.653" height=".937" x="16.977" y="7.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.27451 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3504"/></filter><filter id="iCWMcGd" width="2.423" height=".781" x="17.021" y="7.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".1"/></filter><filter id="i3fawuc" width="2.283" height="1.302" x="11.318" y="8.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".1"/></filter><filter id="iv0y3tD" width="3.309" height="3.341" x="20.549" y="21.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".2"/></filter><filter id="i2eOqtH" width="3.909" height="3.941" x="18.967" y="22.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".35"/></filter><filter id="ia0GSQc" width="3.294" height="2.926" x="19.331" y="22.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".2"/></filter><filter id="ispKNMb" width="3.106" height="2.411" x="18.893" y="23.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".2"/></filter><filter id="if5CK8d" width="2.356" height="1.81" x="18.877" y="25.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3504" stdDeviation=".2"/></filter><linearGradient id="imeSCmO" x1="19.275" x2="14.368" y1="2.872" y2="18.532" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="i7tGT2c" x1="20.152" x2="19.521" y1="18.575" y2="16.773" gradientUnits="userSpaceOnUse"><stop offset=".354" class="kc6u0dx1c"/><stop offset="1" class="z6eg73bhs"/></linearGradient><linearGradient id="ir60ydb" x1="9.111" x2="12.235" y1="12.536" y2="11.934" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i9BBxve" x1="16.152" x2="15.606" y1="13.315" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iwXkXQb" x1="14.892" x2="15.815" y1="12.723" y2="12.659" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="igLYAHb" x1="16.17" x2="16.046" y1="13.412" y2="12.768" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iq43gmd" x1="15.542" x2="15.815" y1="10.279" y2="11.484" gradientUnits="userSpaceOnUse"><stop class="xn8v49gcn"/><stop offset="1" class="nqfu_dp4n"/></linearGradient><linearGradient id="iNLm6Wd" x1="15.74" x2="16.04" y1="15.384" y2="14.373" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iYj0TPd" x1="11.425" x2="12.259" y1="5.211" y2="6.444" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="i96TgAc" x1="18.759" x2="17.196" y1="10.674" y2="11.498" gradientUnits="userSpaceOnUse"><stop offset=".558" class="y8a_xmbaj"/><stop offset="1" class="l_uz_8har"/></linearGradient><linearGradient id="iTl8Fxw" x1="12.275" x2="14.645" y1="11.666" y2="11.219" gradientUnits="userSpaceOnUse"><stop offset=".558" class="htafuph4g"/><stop offset="1" class="l_uz_8har"/><stop offset="1" class="tv-41kbsn"/></linearGradient><linearGradient id="iDyLvtb" x1="26.462" x2="24.16" y1="25.014" y2="29.852" gradientUnits="userSpaceOnUse"><stop class="up7b_htug"/><stop offset="1" class="bvctw1bkc"/></linearGradient><linearGradient id="iO2hU6b" x1="14.931" x2="6.462" y1="19.17" y2="29.852" gradientUnits="userSpaceOnUse"><stop class="eoa632ltp"/><stop offset="1" class="rlw3b4b7i"/></linearGradient><linearGradient id="iNK4qAc" x1="13.149" x2="7.598" y1="28.857" y2="28.832" gradientUnits="userSpaceOnUse"><stop class="lzdnytbwv"/><stop offset="1" class="yasfqbb-e"/></linearGradient><linearGradient id="iu5NXfb" x1="12.824" x2="12.774" y1="24.245" y2="21.296" gradientUnits="userSpaceOnUse"><stop class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></linearGradient><linearGradient id="iTHySxe" x1="21.024" x2="13.962" y1="27.576" y2="27.139" gradientUnits="userSpaceOnUse"><stop class="vrjrrpcnz"/><stop offset="1" class="qarzv5b-l"/></linearGradient><linearGradient id="izc3wGc" x1="20.439" x2="18.399" y1="29.461" y2="29.461" gradientUnits="userSpaceOnUse"><stop class="qbmhocbuh"/><stop offset="1" class="d-g761b1f"/></linearGradient><linearGradient id="ikkmfve" x1="14.988" x2="15.426" y1="25.92" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="fbpp2-h2x"/><stop offset="1" class="al-gpubwr"/></linearGradient><linearGradient id="iCrA8fe" x1="21.337" x2="19.837" y1="18.573" y2="23.17" gradientUnits="userSpaceOnUse"><stop class="rm6lemo-n"/><stop offset=".635" class="uny69rbro"/></linearGradient><linearGradient id="ifbJ2Gz" x1="25.227" x2="24.04" y1="25.188" y2="25.451" gradientUnits="userSpaceOnUse"><stop offset=".049" class="o5fmjwvfp"/><stop offset="1" class="mpub8bbrg"/></linearGradient><linearGradient id="i7qQYVb" x1="10.306" x2="12.962" y1="25.58" y2="22.332" gradientUnits="userSpaceOnUse"><stop class="lk8w5cclk"/><stop offset="1" class="qrasocbfu"/></linearGradient><linearGradient id="iDv1Xeb" x1="16.728" x2="19.056" y1="10.772" y2="10.934" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></linearGradient><linearGradient id="i2KjJpb" x1="12.129" x2="14.457" y1="11.581" y2="11.743" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></linearGradient><linearGradient id="iZEtgUO" x1="14.204" x2="12.149" y1="10.482" y2="10.189" gradientUnits="userSpaceOnUse"><stop offset=".329" class="qbyjgz8xo"/><stop offset="1" class="b1zy4ibbj"/></linearGradient><linearGradient id="ishPDuL" x1="18.853" x2="15.379" y1="9.652" y2="8.497" gradientUnits="userSpaceOnUse"><stop offset=".329" class="xoq3wtioq"/><stop offset="1" class="pij34sbcm"/></linearGradient><linearGradient id="iMIvSAe" x1="21.634" x2="23.915" y1="22.451" y2="24.748" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="bmpot-bwo"/></linearGradient><linearGradient id="iZbdAud" x1="20.351" x2="22.633" y1="23.181" y2="25.478" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="bmpot-bwo"/></linearGradient><linearGradient id="iJobbxc" x1="20.415" x2="22.696" y1="23.084" y2="25.381" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="bmpot-bwo"/></linearGradient><linearGradient id="iuaKMKe" x1="19.978" x2="21.298" y1="24.459" y2="25.466" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="bmpot-bwo"/></linearGradient><linearGradient id="i36PMwc" x1="19.477" x2="20.696" y1="25.779" y2="26.537" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="bmpot-bwo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:breast-feeding" /></template>
<style>
.a_09dwbav {
  stop-color: var(--svg-color--ffbe38, #FFBE38);
}

.a0d1ktmmz {
  stop-color: var(--svg-color--bb5d1b, #BB5D1B);
  stop-opacity: 0;
}

.a5efvqnnr {
  stop-color: var(--svg-color--ffcd38, #FFCD38);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.aeq1u9-lv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m21.15 22.248l2.109 2.14");
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ai8tm4gte {
  d: path("M13.987 29.852h5.602c.47 0 .85-.38.85-.85c0-.545-.508-.957-1.05-.9c-1.244.13-2.715.11-3.597.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.al-gpubwr {
  stop-color: var(--svg-color--f8be33, #F8BE33);
  stop-opacity: 0;
}

.avc38xboi {
  d: path("m10.111 10.866l.013-.002l-.065-.278l-.073-.321c-.171-1.006.338-1.506.563-1.683l.05-.032q.026-.019.05-.032c.512-.367.88-.907 1.004-1.545l.047-.221a.283.283 0 0 1 .477-.148a4.15 4.15 0 0 0 3.706 1.117l3.398-.655c.19-.037 1.16-.128 1.47 1.175l.5 3.267c.44 2.983-1.487 5.414-4.306 5.958c-2.82.543-5.512-.998-6.212-3.93z");
}

.b1zy4ibbj {
  stop-color: var(--svg-color--f2962e, #F2962E);
  stop-opacity: 0;
}

.be_37eq6m {
  d: path("M13.238 16.918c-3.352 1.352-6.48 5.4-8.31 7.956c-.712.853-1.72 2.661-.087 4.978h9.18c.104-.703.154-1.981-.053-3.129c-.11-.612-.72-.996-1.341-.996H11.43c.102-.265.731-1.357 1.801-1.936c.505-.274.855-.563 1.413-.887l.495-.287l.73-.42a6.03 6.03 0 0 1-.942-3.245V17.5a5.2 5.2 0 0 1-1.689-.582");
}

.bieie1q3p {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.368 14.502a3.25 3.25 0 0 1-1.57-.075c-.164-.048-.29.154-.17.273a2.076 2.076 0 0 0 3.429-.66c.066-.162-.125-.297-.259-.19c-.39.314-.875.545-1.43.652");
}

.bmpot-bwo {
  stop-color: var(--svg-color--ffde47, #FFDE47);
  stop-opacity: 0;
}

.bqexp4b8k {
  stop-color: var(--svg-color--ce6826, #CE6826);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bvctw1bkc {
  stop-color: var(--svg-color--9c69f1, #9C69F1);
}

.bvs2yab1t {
  d: path("M16.876 10.682c.13.122.518.353 1.022.298s.947-.543 1.06-.728");
}

.bzrv_p78g {
  stop-color: var(--svg-color--44327f, #44327F);
  stop-opacity: 0;
}

.c_e6lvb0e {
  stop-color: var(--svg-color--44327f, #44327F);
}

.c0n6rcbid {
  stop-color: var(--svg-color--8c60d9, #8C60D9);
  stop-opacity: 0;
}

.c1pc50b3k {
  fill: var(--svg-color--a64023, #A64023);
  d: path("m11.79 9.787l-.005.004a.288.288 0 0 1-.384-.43l.001-.001l.003-.003l.009-.007l.03-.026l.11-.086c.095-.07.231-.161.4-.254c.337-.183.82-.376 1.38-.385a.288.288 0 1 1 .01.576a2.44 2.44 0 0 0-1.113.315a3 3 0 0 0-.441.297");
}

.cb2k4sbte {
  stop-color: var(--svg-color--e6ac25, #E6AC25);
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d-g761b1f {
  stop-color: var(--svg-color--f9b130, #F9B130);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d62ajsaau {
  stop-color: var(--svg-color--6440b8, #6440B8);
  stop-opacity: 0;
}

.dcmach-gg {
  stop-color: var(--svg-color--ee9d35, #EE9D35);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dqxdj-bqs {
  stop-color: var(--svg-color--b2614c, #B2614C);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e-8izbcdn {
  stop-color: var(--svg-color--ffbe3b, #FFBE3B);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.ecm0zqbhs {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.368 14.502a3.25 3.25 0 0 1-1.57-.075c-.164-.048-.29.154-.17.273a2.076 2.076 0 0 0 3.429-.66c.066-.162-.125-.297-.259-.19c-.39.314-.875.545-1.43.652Z");
}

.eevw7bbab {
  d: path("M16.837 8.374c1.4.011 2.275.82 2.401 1.625c-1.197-.582-2.008-.519-2.482-.374z");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.emrn-tmef {
  d: path("M8.4 25.58h2.452c.425-.69 1.037-1.514 1.36-1.841a7 7 0 0 0-.531-1.663c-1.125.974-2.657 2.742-3.282 3.504");
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eoa632ltp {
  stop-color: var(--svg-color--9165d0, #9165D0);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.exv2s-bbh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.93 22.88l2.094 1.727");
}

.f65hhupfk {
  stroke: var(--svg-color--b45c48, #B45C48);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.321 8.141c.325-.148 1.18-.27 1.823.026");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fbpp2-h2x {
  stop-color: var(--svg-color--d29f26, #D29F26);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fl7kbbbgj {
  d: path("M18.83 10.083c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51s-.63-.03-.86-.23a.3.3 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.39");
}

.fpntxsvxv {
  stop-color: var(--svg-color--6440b8, #6440B8);
}

.ft5dv1b6b {
  fill: none;
}

.ftxo3fi5a {
  stop-color: var(--svg-color--8c60d9, #8C60D9);
}

.fxslr17fv {
  stop-color: var(--svg-color--f69449, #F69449);
}

.g228gpr1w {
  stop-color: var(--svg-color--ffc339, #FFC339);
  stop-opacity: 0;
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gtope1bxc {
  stop-color: var(--svg-color--e6ac25, #E6AC25);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hf7j1mwxc {
  d: path("M23.607 11.19a3.5 3.5 0 0 0 .051-1.572a3.5 3.5 0 0 0-.549-1.323l.006-.001a3.4 3.4 0 0 0-.401-.484l-.003-.003a3.5 3.5 0 0 1-.916-1.762l-.002-.011a3.547 3.547 0 0 0-4.153-2.81a.58.58 0 0 1-.528-.153a3.55 3.55 0 0 0-3.11-.907a3.55 3.55 0 0 0-2.55 1.998a.6.6 0 0 1-.434.338l-.09.019a3.547 3.547 0 0 0-2.72 4.134l.002.01a3.5 3.5 0 0 1-.195 1.977l-.002.004a3.55 3.55 0 0 0 .428 3.47a.55.55 0 0 1 .092.48a3.5 3.5 0 0 0-.055 1.55a3.454 3.454 0 0 0 4.05 2.742l9.058-1.746a3.454 3.454 0 0 0 2.741-4.051a3.5 3.5 0 0 0-.628-1.419a.55.55 0 0 1-.092-.48m-13.483-.326l-.013.002l1.744 2.242c.7 2.933 1.285-.247 4.104-.79c2.82-.544 4.683 2.51 4.243-.472l.549-3.605c-.31-1.303-1.28-1.212-1.47-1.175l-3.398.655a4.15 4.15 0 0 1-3.707-1.117a.283.283 0 0 0-.476.148l-.047.221a2.48 2.48 0 0 1-1.055 1.577q-.026.018-.05.032c-.223.177-.733.677-.562 1.683l.073.32z");
}

.hfn_x0p8e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.477 25.78l1.157.609");
}

.hokoarktc {
  fill-rule: evenodd;
  d: path("M23.607 11.19a3.5 3.5 0 0 0 .051-1.572a3.5 3.5 0 0 0-.549-1.323l.006-.001a3.4 3.4 0 0 0-.401-.484l-.003-.003a3.5 3.5 0 0 1-.916-1.762l-.002-.011a3.547 3.547 0 0 0-4.153-2.81a.58.58 0 0 1-.528-.153a3.55 3.55 0 0 0-3.11-.907a3.55 3.55 0 0 0-2.55 1.998a.6.6 0 0 1-.434.338l-.09.019a3.547 3.547 0 0 0-2.72 4.134l.002.01a3.5 3.5 0 0 1-.195 1.977l-.002.004a3.55 3.55 0 0 0 .428 3.47a.55.55 0 0 1 .092.48a3.5 3.5 0 0 0-.055 1.55a3.454 3.454 0 0 0 4.05 2.742l9.058-1.746a3.454 3.454 0 0 0 2.741-4.051a3.5 3.5 0 0 0-.628-1.419a.55.55 0 0 1-.092-.48m-13.483-.326l-.013.002l1.744 2.242c.7 2.933 1.285-.247 4.104-.79c2.82-.544 4.683 2.51 4.243-.472l.549-3.605c-.31-1.303-1.28-1.212-1.47-1.175l-3.398.655a4.15 4.15 0 0 1-3.707-1.117a.283.283 0 0 0-.476.148l-.047.221a2.48 2.48 0 0 1-1.055 1.577q-.026.018-.05.032c-.223.177-.733.677-.562 1.683l.073.32z");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.htafuph4g {
  stop-color: var(--svg-color--7b2f2a, #7B2F2A);
}

.i4-il_z6k {
  d: path("m15.26 10.86l-.215 1.902a.58.58 0 0 0 .692.633l.83-.16a.58.58 0 0 0 .407-.844l-.907-1.686c-.197-.375-.758-.267-.807.155");
}

.i54m18vgp {
  stop-color: var(--svg-color--51e398, #51E398);
  stop-opacity: 0;
}

.ide6vizoj {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.03 13.247a1.154 1.154 0 1 0-.436-2.267a1.154 1.154 0 0 0 .437 2.267");
}

.if-fw02py {
  stop-color: var(--svg-color--ffc132, #FFC132);
  stop-opacity: 0;
}

.ihi4ay12v {
  stop-color: var(--svg-color--dd9318, #DD9318);
}

.ilmkod2my {
  stop-color: var(--svg-color--ffc43d, #FFC43D);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iv8lx-bbk {
  d: path("M10.415 25.654h1.57l.977-1.594c-1.675-.138-2.396 1.005-2.547 1.594");
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j3monpcls {
  stop-color: var(--svg-color--db7725, #DB7725);
  stop-opacity: 0;
}

.j4yu7gpks {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M21.05 11.315a1.154 1.154 0 1 0-.437-2.267a1.154 1.154 0 0 0 .437 2.267");
}

.jfgmi3bgp {
  d: path("M12.277 11.492c.13.122.518.352 1.022.298c.504-.055.947-.543 1.06-.728");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jswq_j2dq {
  stop-color: var(--svg-color--34e38b, #34E38B);
}

.jyzijgb5l {
  stop-color: var(--svg-color--248571, #248571);
  stop-opacity: 0;
}

.k27foaczd {
  stop-color: var(--svg-color--e5ad2a, #E5AD2A);
}

.k7gdagbzg {
  stop-color: var(--svg-color--ce6826, #CE6826);
  stop-opacity: 0;
}

.kc6luf8ah {
  stop-color: var(--svg-color--7556b0, #7556B0);
}

.kc6u0dx1c {
  stop-color: var(--svg-color--d06e54, #D06E54);
}

.khg6a5-nz {
  stop-color: var(--svg-color--248571, #248571);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.l_uz_8har {
  stop-color: var(--svg-color--c45011, #C45011);
}

.l99uylilx {
  stop-color: var(--svg-color--309972, #309972);
}

.la4e9obft {
  stop-color: var(--svg-color--ac7ff8, #AC7FF8);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lk8w5cclk {
  stop-color: var(--svg-color--a176df, #A176DF);
}

.lsn1jtqvl {
  stop-color: var(--svg-color--f1a028, #F1A028);
}

.lzdnytbwv {
  stop-color: var(--svg-color--a673ff, #A673FF);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m4uik1qzh {
  d: path("m15.196 10.655l-.215 1.902a.58.58 0 0 0 .692.633l.83-.16a.58.58 0 0 0 .407-.844l-.907-1.687c-.197-.374-.758-.266-.807.156");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mo17i3bvc {
  d: path("M23.077 27.013a4.3 4.3 0 1 0 0-8.6c-2.375 0-3.553 1.925-3.553 4.3s1.178 4.3 3.553 4.3");
}

.mpub8bbrg {
  stop-color: var(--svg-color--ffc53e, #FFC53E);
  stop-opacity: 0;
}

.n2a634bwb {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
}

.n34issb-z {
  stop-color: var(--svg-color--8c450c, #8C450C);
}

.n7fe64b-m {
  stop-color: var(--svg-color--6a428c, #6A428C);
}

.n84vunlix {
  stop-color: var(--svg-color--e39723, #E39723);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nqfu_dp4n {
  stop-color: var(--svg-color--f8c640, #F8C640);
  stop-opacity: 0;
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nx-0f1bho {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.282 26.412c.273.906.367 2.164-.797 3.18");
}

.nxcp7drxh {
  d: path("M11.12 13.815a1.73 1.73 0 1 0-.655-3.396a1.73 1.73 0 0 0 .654 3.396");
}

.nybv-x_bu {
  stop-color: var(--svg-color--51e398, #51E398);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o2nbnyboi {
  stop-color: var(--svg-color--d67e02, #D67E02);
}

.o3yqmrbrg {
  stop-color: var(--svg-color--885ebc, #885EBC);
  stop-opacity: 0;
}

.o4olk18av {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.493 24.255l1.906 1.211");
}

.o5fmjwvfp {
  stop-color: var(--svg-color--ffe144, #FFE144);
}

.ol5q01bzf {
  d: path("M17.017 16.313c-.72 0-1.42.08-2.09.22v2.42c0 3.48 2.93 6.25 6.41 6.06l5.58-.31c-.7-4.74-4.86-8.39-9.9-8.39");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pij34sbcm {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
  stop-opacity: 0;
}

.pjb1_mveq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.355 4.848c.074.252.483 1.173.922 1.694");
}

.pl207l2go {
  d: path("M7.337 27.013h6.034v2.188H7.337z");
}

.pwe9avbwo {
  stop-color: var(--svg-color--ffe43a, #FFE43A);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qarzv5b-l {
  stop-color: var(--svg-color--37ba71, #37BA71);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qbmhocbuh {
  stop-color: var(--svg-color--f9b130, #F9B130);
}

.qbyjgz8xo {
  stop-color: var(--svg-color--ee9627, #EE9627);
}

.qe8hvs01u {
  stroke: var(--svg-color--b45c48, #B45C48);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.3 8.845c-.356-.017-1.195.187-1.682.701");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qnozvmjjn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.867 22.978l2.11 2.14");
}

.qo4bk2z1r {
  stop-color: var(--svg-color--eb9a0d, #EB9A0D);
  stop-opacity: 0;
}

.qrasocbfu {
  stop-color: var(--svg-color--a176df, #A176DF);
  stop-opacity: 0;
}

.qswustbfm {
  d: path("M9.348 5.812c.543-.71 1.487-.898 2.036-.906l.687 1.28c-.279.011-.502.152-.668.386c-.225 1.423-1.737 2.475-2.465 2.824c-.462-1.544-.527-2.357.41-3.584");
}

.qtbzeirls {
  stop-color: var(--svg-color--a980f3, #A980F3);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qwzeypbhs {
  fill: var(--svg-color--a64023, #A64023);
  fill-rule: evenodd;
  d: path("m19.24 7.921l-.098.271za.288.288 0 0 1-.197.541h-.001l-.005-.002l-.026-.008l-.105-.03a3 3 0 0 0-.39-.073a2.44 2.44 0 0 0-1.15.12a.288.288 0 0 1-.205-.538c.523-.2 1.043-.2 1.424-.155a3.5 3.5 0 0 1 .638.138l.011.004l.004.002z");
}

.r2l3kgbhd {
  stop-color: var(--svg-color--f1a028, #F1A028);
  stop-opacity: 0;
}

.r4jombc7m {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.3 21.014c.344.635 1.032 2.28 1.032 3.78");
}

.r5lqkxb5o {
  stop-color: var(--svg-color--ffc132, #FFC132);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rjaj9xbwv {
  d: path("M27.184 27.357c-.013-.404-.165-2.417-.222-3.117l-2.825.18l-3.008 3.324c0 1.264.513 1.95.805 2.108h4.39c.97-.963.869-2.21.86-2.495");
}

.rlw3b4b7i {
  stop-color: var(--svg-color--9565e9, #9565E9);
}

.rm6lemo-n {
  stop-color: var(--svg-color--3db155, #3DB155);
}

.rru85ybco {
  d: path("M21.05 11.315a1.154 1.154 0 1 0-.437-2.267a1.154 1.154 0 0 0 .437 2.267");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.sq95r4vix {
  stop-color: var(--svg-color--a476f3, #A476F3);
  stop-opacity: 0;
}

.srddfxbul {
  d: path("M21.159 11.88a1.73 1.73 0 1 0-.655-3.396a1.73 1.73 0 0 0 .655 3.396");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t11jj7g0p {
  fill: var(--svg-color--642fc5, #642FC5);
  d: path("M25.247 29.853c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.t9k7tiocc {
  stop-color: var(--svg-color--e39723, #E39723);
}

.tce23o4qc {
  stop-color: var(--svg-color--a980f3, #A980F3);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tv-41kbsn {
  stop-color: var(--svg-color--ab461c, #AB461C);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.udb4a2bwg {
  d: path("m13.12 23.767l.068-.038a54 54 0 0 0 1.456-.825l.495-.286l.04-.024l.69-.396l-.005-.007a4.253 4.253 0 0 1 5.603 1.672c1.18 2.04.48 4.64-1.56 5.8l-.3.18h-5.584c.102-.705.151-1.977-.054-3.12c-.11-.612-.721-.996-1.342-.996h-1.193q.072-.167.156-.329c.159-.288.425-.695.8-1.066q.328-.316.73-.565");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uny69rbro {
  stop-color: var(--svg-color--38aa6f, #38AA6F);
}

.up7b_htug {
  stop-color: var(--svg-color--ab84ee, #AB84EE);
}

.uz71m0bcb {
  d: path("M11.03 13.247a1.154 1.154 0 1 0-.436-2.267a1.154 1.154 0 0 0 .437 2.267");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vrjrrpcnz {
  stop-color: var(--svg-color--349373, #349373);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w-wd4mb8i {
  stop-color: var(--svg-color--53ffa2, #53FFA2);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x22v_oxmd {
  d: path("M14.2 10.892c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51c-.31.06-.62-.03-.86-.22a.25.25 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.4");
}

.xb-sglp8w {
  d: path("M21.207 23.793a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.xjvfic_gd {
  stop-color: var(--svg-color--309972, #309972);
  stop-opacity: 0;
}

.xllr1s1ox {
  stop-color: var(--svg-color--b76f5c, #B76F5C);
}

.xn8v49gcn {
  stop-color: var(--svg-color--f8c640, #F8C640);
}

.xoq3wtioq {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
}

.y3ozgf0rs {
  stop-color: var(--svg-color--b76f5c, #B76F5C);
  stop-opacity: 0;
}

.y8a_xmbaj {
  stop-color: var(--svg-color--96442e, #96442E);
}

.y8ddjqa_l {
  d: path("M25.247 29.853c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.y9owwpbix {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
  stop-opacity: 0;
}

.yasfqbb-e {
  stop-color: var(--svg-color--a673ff, #A673FF);
  stop-opacity: 0;
}

.yd5uj4llx {
  d: path("M13.515 3.065c-1.246-.034-2.282 1.485-2.32 1.951c2.363 3.508 4.792 2.662 7.505 1.82c1.624-.505 1.95.216 2.162.555c-1.285-4.192-4.507-4.25-7.347-4.326");
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yit44gm3t {
  stop-color: var(--svg-color--9165d2, #9165D2);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yueg0n5my {
  d: path("M20.604 21.956a.64.64 0 0 1 .913.019c.447.475 1.16 1.226 1.82 1.886a.05.05 0 0 0 .085-.04l-.089-.925a.67.67 0 0 1 1.32-.21l.693 3.103q.087.293.088.615c0 1.064-.766 1.95-1.777 2.136c-.697.2-1.485-.121-1.794-.308l-2.78-1.69a.632.632 0 0 1 .627-1.097l-.597-.429a.62.62 0 1 1 .737-1l.186.142l-.656-.52a.648.648 0 1 1 .837-.989l1.157 1.046l-.791-.853a.636.636 0 0 1 .02-.886");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z47nt4bif {
  d: path("M11.977 9.623c1.375-.263 2.391.359 2.672 1.125c-1.287-.338-2.07-.118-2.507.117z");
}

.z6eg73bhs {
  stop-color: var(--svg-color--e88128, #E88128);
  stop-opacity: 0;
}

.zdmgu47df {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.277 11.008l-.375 1.934a.58.58 0 0 0 .691.632l.83-.16a.58.58 0 0 0 .408-.844l-.907-1.686c-.197-.375-.598-.297-.647.124");
}

</style>
