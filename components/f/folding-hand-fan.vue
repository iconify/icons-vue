<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iM2O5eP)" clip-rule="evenodd" class="k5tblvnvr"/><path fill="url(#ibeA3ub)" clip-rule="evenodd" class="k5tblvnvr"/><path fill="url(#ilWNwhb)" clip-rule="evenodd" class="k5tblvnvr"/><path fill="url(#i2khaue)" clip-rule="evenodd" class="k5tblvnvr"/><path fill="url(#iSIBmEe)" clip-rule="evenodd" class="y1-3ekbwt"/><path fill="url(#i5LJrBe)" clip-rule="evenodd" class="y1-3ekbwt"/><path fill="url(#iYd5FRd)" class="vq4cbsbmu"/><path fill="url(#isDaaPc)" class="vq4cbsbmu"/><path fill="url(#iSqfTpB)" class="vq4cbsbmu"/><path fill="url(#iWBxJme)" class="vq4cbsbmu"/><path fill="url(#imFrQ5b)" class="vq4cbsbmu"/><path fill="url(#iNBbpgn)" clip-rule="evenodd" class="viaii4ssw"/><path clip-rule="evenodd" class="eqxygsbiw"/><path fill="url(#iwnO0Gc)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#i8BXFxd)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#iTGC5vc)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#it9gC3c)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#ihrNNDn)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#iMlEEPb)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#i5uFhdb)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#iFdBVLe)" clip-rule="evenodd" class="t55hy4our"/><path fill="url(#ihDlbcb)" clip-rule="evenodd" class="t55hy4our"/><path clip-rule="evenodd" class="f9nyzbcrj"/><path fill="url(#ihxCUrd)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#ixK6DEe)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#i1OSGdb)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#i2LK0Nd)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#iwSvsAc)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#ix1LHFb)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#iBGgJad)" clip-rule="evenodd" class="b-ygq8b3k"/><path fill="url(#iYJguac)" clip-rule="evenodd" class="b-ygq8b3k"/><path clip-rule="evenodd" class="jx3tdzbpb"/><path fill="url(#iw095hY)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#iQeK7nd)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#i0moJrd)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#iVtJlHb)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#iKNqQcR)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#inzHxZc)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#ifHB3dc)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#izSufRd)" clip-rule="evenodd" class="srhmncmvz"/><path fill="url(#izpiRbb)" clip-rule="evenodd" class="srhmncmvz"/><path clip-rule="evenodd" class="w58w-yb9j"/><path fill="url(#iEnB5ec)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#i0bBsId)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#iAVmkgF)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#iS1mtHg)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#i7JFoFe)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#iJKZYjd)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#iUL1kRh)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#ier8NFd)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#icBRgnd)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#iFGVEgX)" clip-rule="evenodd" class="n3zhp2kxd"/><path fill="url(#i1AZ4Td)" clip-rule="evenodd" class="n3zhp2kxd"/><path clip-rule="evenodd" class="pr3if9ufk"/><path fill="url(#ivusYPb)" clip-rule="evenodd" class="furiw9amr"/><path fill="url(#iGGbfqd)" clip-rule="evenodd" class="furiw9amr"/><path fill="url(#iQ5GQvQ)" clip-rule="evenodd" class="furiw9amr"/><path fill="url(#i97Dteb)" clip-rule="evenodd" class="nfgmxpbei"/><path fill="url(#irgeBUd)" clip-rule="evenodd" class="nfgmxpbei"/><path fill="url(#iSUTxrb)" clip-rule="evenodd" class="nfgmxpbei"/><path fill="url(#i0m7OJF)" clip-rule="evenodd" class="p6rs_7b1f"/><path fill="url(#iGoPjrb)" clip-rule="evenodd" class="p6rs_7b1f"/><path fill="url(#iVJ190b)" clip-rule="evenodd" class="j44oedbkw"/><path fill="url(#icj1VHb)" clip-rule="evenodd" class="j44oedbkw"/><path fill="url(#inT0rIe)" clip-rule="evenodd" class="pwi47fbae"/><path fill="url(#iIAnhkc)" clip-rule="evenodd" class="pwi47fbae"/><path fill="url(#iP5v4Nb)" clip-rule="evenodd" class="ziv_2mfft"/><path fill="url(#ib7uZXd)" clip-rule="evenodd" class="ziv_2mfft"/><path fill="url(#iPp98Yb)" clip-rule="evenodd" class="fhdbg6ujc"/><path fill="url(#imnsE5W)" clip-rule="evenodd" class="fhdbg6ujc"/><path fill="url(#i1LSiSc)" clip-rule="evenodd" class="bmtl_ohcx"/><path fill="url(#ieovM9c)" clip-rule="evenodd" class="r_fh92bsv"/><circle class="d41vj6ggh"/><circle fill="url(#iNewcFe)" class="dbdyi8u3o"/><circle fill="url(#iAlXdre)" class="dbdyi8u3o"/><path fill="url(#iCIC5Gd)" clip-rule="evenodd" class="kwd9jy65i"/><path fill="url(#izFecxe)" clip-rule="evenodd" class="nse4z9bpx"/><path fill="url(#itkd0Pe)" clip-rule="evenodd" class="q3klehbor"/><circle class="ksq_e4brk"/><circle fill="url(#iSLfDsN)" class="huprstbsk"/><circle fill="url(#iwOQAGT)" class="huprstbsk"/><circle fill="url(#i3Vw30P)" class="huprstbsk"/><circle fill="url(#iqHaGMe)" class="huprstbsk"/><circle class="bzbd886rw"/><defs><linearGradient id="iNBbpgn" x1="23.344" x2="24.219" y1="27.813" y2="27.656" gradientUnits="userSpaceOnUse"><stop class="lkoz8kbar"/><stop offset=".531" class="c19oo1s2a"/><stop offset=".834" class="u_q3q3b3h"/></linearGradient><linearGradient id="iwnO0Gc" x1="18.25" x2="6.438" y1="6.156" y2="22.906" gradientUnits="userSpaceOnUse"><stop class="p_bqpvbka"/><stop offset=".195" class="yxyl29bnm"/><stop offset=".687" class="rm3q10b8v"/><stop offset="1" class="u6pd3cblt"/></linearGradient><linearGradient id="i8BXFxd" x1="17.344" x2="15.688" y1="13.031" y2="12.094" gradientUnits="userSpaceOnUse"><stop offset=".126" class="as5c_2j3v"/><stop offset=".529" class="id71b27va"/></linearGradient><linearGradient id="iTGC5vc" x1="17.219" x2="14.844" y1="12.313" y2="11.938" gradientUnits="userSpaceOnUse"><stop offset=".113" class="id71b27va"/><stop offset=".401" class="as5c_2j3v"/><stop offset=".681" class="id71b27va"/></linearGradient><linearGradient id="it9gC3c" x1="16" x2="13.219" y1="11.156" y2="11.719" gradientUnits="userSpaceOnUse"><stop offset=".143" class="id71b27va"/><stop offset=".401" class="as5c_2j3v"/><stop offset=".681" class="id71b27va"/></linearGradient><linearGradient id="ihrNNDn" x1="13.656" x2="11.688" y1="10.906" y2="12.063" gradientUnits="userSpaceOnUse"><stop class="id71b27va"/><stop offset=".507" class="yspjt5szs"/><stop offset=".852" class="hn56k5h2m"/></linearGradient><linearGradient id="iMlEEPb" x1="11.406" x2="9.813" y1="11.25" y2="13.156" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".507" class="dpzhp9big"/><stop offset=".852" class="t5w3suqgj"/></linearGradient><linearGradient id="i5uFhdb" x1="9.469" x2="8.719" y1="12.875" y2="15.031" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".507" class="un4buxyfs"/><stop offset=".852" class="m9vb9k_kq"/></linearGradient><linearGradient id="iFdBVLe" x1="7.719" x2="7.719" y1="15.344" y2="17.406" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".455" class="un4buxyfs"/><stop offset=".852" class="m9vb9k_kq"/></linearGradient><linearGradient id="ihDlbcb" x1="7.531" x2="8.125" y1="18.281" y2="20.125" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".455" class="un4buxyfs"/><stop offset=".852" class="m9vb9k_kq"/></linearGradient><linearGradient id="ihxCUrd" x1="16.769" x2="15.823" y1="14.175" y2="13.64" gradientUnits="userSpaceOnUse"><stop offset=".126" class="qpsw47uyk"/><stop offset=".942" class="modqunbqp"/></linearGradient><linearGradient id="ixK6DEe" x1="16.698" x2="15.341" y1="13.765" y2="13.55" gradientUnits="userSpaceOnUse"><stop class="bqa25xb8v"/><stop offset=".638" class="tv6p64b0s"/><stop offset=".956" class="bqa25xb8v"/></linearGradient><linearGradient id="i1OSGdb" x1="16.002" x2="14.412" y1="13.104" y2="13.425" gradientUnits="userSpaceOnUse"><stop offset=".084" class="bqa25xb8v"/><stop offset=".564" class="tv6p64b0s"/><stop offset=".942" class="bqa25xb8v"/></linearGradient><linearGradient id="i2LK0Nd" x1="14.662" x2="13.537" y1="12.961" y2="13.622" gradientUnits="userSpaceOnUse"><stop class="d0m_eabcp"/><stop offset=".677" class="n518e0fei"/><stop offset="1" class="d0m_eabcp"/></linearGradient><linearGradient id="iwSvsAc" x1="13.377" x2="12.466" y1="13.158" y2="14.247" gradientUnits="userSpaceOnUse"><stop class="j0eilp8wg"/><stop offset=".653" class="lyzlxzcje"/><stop offset="1" class="j0eilp8wg"/></linearGradient><linearGradient id="ix1LHFb" x1="12.27" x2="11.75" y1="14.086" y2="15.563" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".47" class="dim9e1tfy"/><stop offset="1" class="r7renrgni"/></linearGradient><linearGradient id="iBGgJad" x1="11.27" x2="11.27" y1="15.497" y2="16.675" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".613" class="z27ab3bao"/><stop offset="1" class="s5jgq_bgj"/></linearGradient><linearGradient id="iYJguac" x1="11.162" x2="11.594" y1="17.175" y2="18.313" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".556" class="r6ijrbgfl"/><stop offset="1" class="fwrzkqbgb"/></linearGradient><linearGradient id="iQeK7nd" x1="16.672" x2="15.844" y1="14.366" y2="13.898" gradientUnits="userSpaceOnUse"><stop offset=".375" class="fmnutjb2h"/><stop offset=".888" class="ljki8bbop"/></linearGradient><linearGradient id="i0moJrd" x1="16.609" x2="15.422" y1="14.007" y2="13.819" gradientUnits="userSpaceOnUse"><stop class="bqa25xb8v"/><stop offset=".638" class="lopn4vsjn"/><stop offset=".956" class="g88m66b1e"/></linearGradient><linearGradient id="iVtJlHb" x1="16" x2="14.609" y1="13.429" y2="13.71" gradientUnits="userSpaceOnUse"><stop offset=".084" class="bqa25xb8v"/><stop offset=".564" class="i8e5mgbvv"/><stop offset=".942" class="fz7cwldhh"/></linearGradient><linearGradient id="iKNqQcR" x1="14.828" x2="13.844" y1="13.304" y2="13.882" gradientUnits="userSpaceOnUse"><stop class="d0m_eabcp"/><stop offset=".677" class="slf7zspdc"/><stop offset="1" class="zhz5zib5p"/></linearGradient><linearGradient id="inzHxZc" x1="13.703" x2="12.906" y1="13.476" y2="14.429" gradientUnits="userSpaceOnUse"><stop class="j0eilp8wg"/><stop offset=".653" class="n5h33e23k"/><stop offset="1" class="rmttnqwei"/></linearGradient><linearGradient id="ifHB3dc" x1="12.734" x2="12.28" y1="14.288" y2="15.58" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".47" class="h-ul7wbvu"/><stop offset="1" class="hd_3ymbcc"/></linearGradient><linearGradient id="izSufRd" x1="11.859" x2="11.859" y1="15.523" y2="16.554" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".613" class="vd2xl0bhb"/><stop offset="1" class="vvq92abpd"/></linearGradient><linearGradient id="izpiRbb" x1="11.766" x2="12.143" y1="16.991" y2="17.986" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".556" class="dddf11u-o"/><stop offset="1" class="wc2903zfe"/></linearGradient><linearGradient id="iS1mtHg" x1="16.576" x2="15.866" y1="14.557" y2="14.155" gradientUnits="userSpaceOnUse"><stop offset=".375" class="e9st0sbxj"/><stop offset=".888" class="rmkn1jb_c"/></linearGradient><linearGradient id="i7JFoFe" x1="16.522" x2="15.505" y1="14.249" y2="14.088" gradientUnits="userSpaceOnUse"><stop class="bqa25xb8v"/><stop offset=".638" class="gddoheb0m"/><stop offset=".956" class="k3avo8j7a"/></linearGradient><linearGradient id="iJKZYjd" x1="16" x2="14.808" y1="13.753" y2="13.994" gradientUnits="userSpaceOnUse"><stop offset=".084" class="bqa25xb8v"/><stop offset=".585" class="rzdrg1bgg"/><stop offset=".942" class="bk3iqwx6f"/></linearGradient><linearGradient id="iUL1kRh" x1="14.995" x2="14.152" y1="13.646" y2="14.142" gradientUnits="userSpaceOnUse"><stop class="d0m_eabcp"/><stop offset=".677" class="hjze_ac2v"/><stop offset="1" class="p00pytbzx"/></linearGradient><linearGradient id="ier8NFd" x1="14.031" x2="13.348" y1="13.793" y2="14.611" gradientUnits="userSpaceOnUse"><stop class="j0eilp8wg"/><stop offset=".653" class="gu-z4vbqv"/><stop offset="1" class="our7-pbrp"/></linearGradient><linearGradient id="icBRgnd" x1="13.201" x2="12.811" y1="14.49" y2="15.597" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".47" class="lahyopbtb"/><stop offset="1" class="dw43d2bhc"/></linearGradient><linearGradient id="iFGVEgX" x1="12.451" x2="12.451" y1="15.548" y2="16.432" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".613" class="rbws9u6oz"/><stop offset="1" class="ojcmu9bcs"/></linearGradient><linearGradient id="i1AZ4Td" x1="12.37" x2="12.694" y1="16.807" y2="17.66" gradientUnits="userSpaceOnUse"><stop offset=".021" class="id71b27va"/><stop offset=".556" class="w9speobyp"/><stop offset="1" class="mk27tccrr"/></linearGradient><linearGradient id="ivusYPb" x1="16.625" x2="17.656" y1="9.063" y2="9.239" gradientUnits="userSpaceOnUse"><stop offset=".11" class="r10g3ybid"/><stop offset=".582" class="h5nabebrz"/><stop offset="1" class="l20869bbj"/></linearGradient><linearGradient id="i97Dteb" x1="14.344" x2="15.25" y1="8.531" y2="8.375" gradientUnits="userSpaceOnUse"><stop class="s2i6y7bgg"/><stop offset=".27" class="x7es02b4h"/><stop offset=".566" class="t_t0shb-v"/><stop offset=".856" class="mlpyr4bvu"/></linearGradient><linearGradient id="i0m7OJF" x1="11.969" x2="12.719" y1="9.5" y2="9.078" gradientUnits="userSpaceOnUse"><stop class="bn7aq8car"/><stop offset=".286" class="zpev2qbfl"/><stop offset=".661" class="qelzzcbql"/><stop offset=".883" class="ctu_-oy8j"/></linearGradient><linearGradient id="iVJ190b" x1="10" x2="10.625" y1="11.156" y2="10.406" gradientUnits="userSpaceOnUse"><stop class="kte9s4bdw"/><stop offset=".285" class="uu2y_eb7a"/><stop offset=".541" class="ss5hu2uca"/><stop offset=".779" class="trdrorfem"/></linearGradient><linearGradient id="inT0rIe" x1="8.406" x2="8.781" y1="13.456" y2="12.391" gradientUnits="userSpaceOnUse"><stop offset=".042" class="y2-q9xbjq"/><stop offset=".265" class="rcz5ll4ii"/><stop offset=".589" class="c42kcd2db"/><stop offset=".843" class="qrn0-5b1x"/></linearGradient><linearGradient id="iP5v4Nb" x1="7.813" x2="7.813" y1="16.139" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="a6tldnqtn"/><stop offset=".265" class="i0ej1sbkj"/><stop offset=".48" class="ymr_eybzo"/><stop offset=".784" class="f4tudiyhy"/></linearGradient><linearGradient id="iPp98Yb" x1="8.344" x2="7.938" y1="19.047" y2="17.944" gradientUnits="userSpaceOnUse"><stop offset=".12" class="vrskulb0z"/><stop offset=".333" class="sdprqxbvx"/><stop offset=".44" class="uk4ff7vqt"/><stop offset=".795" class="ctn7pvbtv"/></linearGradient><linearGradient id="i1LSiSc" x1="9.422" x2="8.844" y1="21.906" y2="21.219" gradientUnits="userSpaceOnUse"><stop offset=".162" class="pthncqbka"/><stop offset=".458" class="q-tghsb_m"/><stop offset="1" class="utbk8fboz"/></linearGradient><linearGradient id="ieovM9c" x1="17.438" x2="18.297" y1="12.156" y2="12.656" gradientUnits="userSpaceOnUse"><stop offset=".142" class="k-tynkd-c"/><stop offset=".561" class="i2o8xyy4n"/><stop offset="1" class="kyn-13u-g"/></linearGradient><linearGradient id="iCIC5Gd" x1="22.516" x2="23.258" y1="28.164" y2="28.102" gradientUnits="userSpaceOnUse"><stop class="txig1xbox"/><stop offset=".588" class="dpbbx8bny"/><stop offset="1" class="jb7635beg"/></linearGradient><linearGradient id="izFecxe" x1="21.828" x2="22.453" y1="27.453" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="h945bk7yh"/><stop offset=".548" class="a-foipbpt"/><stop offset="1" class="dwd9h0b_a"/></linearGradient><linearGradient id="itkd0Pe" x1="20.875" x2="21.844" y1="27.469" y2="27.609" gradientUnits="userSpaceOnUse"><stop class="bl6dndb1j"/><stop offset=".566" class="c9cn0tbtq"/><stop offset="1" class="dz5vdbbgu"/></linearGradient><radialGradient id="iM2O5eP" cx="0" cy="0" r="1" gradientTransform="rotate(117.423 4.126 16.8)scale(3.73186 4.30311)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="inr63ubis"/><stop offset=".325" class="pzgmiebvd"/><stop offset=".448" class="bmd2o8b-e"/><stop offset=".705" class="row51-uhw"/></radialGradient><radialGradient id="ibeA3ub" cx="0" cy="0" r="1" gradientTransform="rotate(85.073 -.195 20.112)scale(.90961 2.09211)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="v57eacczk"/><stop offset="1" class="e3on_nbfx"/></radialGradient><radialGradient id="ilWNwhb" cx="0" cy="0" r="1" gradientTransform="rotate(100.235 1.454 19.949)scale(2.28638 1.31664)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="gtjqrabid"/><stop offset="1" class="z605i0bxm"/></radialGradient><radialGradient id="i2khaue" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 1.25 -1.2755 -.63775 21.125 20.813)" gradientUnits="userSpaceOnUse"><stop offset=".48" class="he-fr3b5z"/><stop offset="1" class="tqos3qb8z"/></radialGradient><radialGradient id="iSIBmEe" cx="0" cy="0" r="1" gradientTransform="rotate(135.522 5.624 13.05)scale(4.24834 5.89664)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="dad0bbbcn"/><stop offset=".244" class="on95lmbis"/><stop offset=".329" class="gomm1dv0i"/><stop offset=".397" class="q_dltacds"/></radialGradient><radialGradient id="i5LJrBe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36719 .42188 -.12905 -.41821 20.602 18.875)" gradientUnits="userSpaceOnUse"><stop offset=".338" class="v57eacczk"/><stop offset="1" class="e3on_nbfx"/></radialGradient><radialGradient id="iYd5FRd" cx="0" cy="0" r="1" gradientTransform="rotate(30 -21.952 40.155)scale(1.3125 2.625)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="ey2w-4bue"/><stop offset="1" class="crz1tolxq"/></radialGradient><radialGradient id="isDaaPc" cx="0" cy="0" r="1" gradientTransform="rotate(48.629 -8.233 26.248)scale(1.70213)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="mavnlkjii"/><stop offset="1" class="gv55ymbsy"/></radialGradient><radialGradient id="iSqfTpB" cx="0" cy="0" r="1" gradientTransform="rotate(16.682 -45.284 62.376)scale(2.5446)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="nkogj_b7o"/><stop offset=".746" class="dzkt94_8c"/><stop offset=".861" class="f5-bt-z8y"/></radialGradient><radialGradient id="iWBxJme" cx="0" cy="0" r="1" gradientTransform="rotate(32.471 -20.906 35.948)scale(2.03725 2.43338)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="ec3mdccep"/><stop offset="1" class="mxbjpnbfi"/></radialGradient><radialGradient id="imFrQ5b" cx="0" cy="0" r="1" gradientTransform="rotate(45 -10.936 27.157)scale(2.60746)" gradientUnits="userSpaceOnUse"><stop offset=".517" class="v8c8umbmi"/><stop offset=".648" class="fnz83rb8q"/></radialGradient><radialGradient id="iw095hY" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.25 -6.25 0 16 15.656)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="r2tzyjbrt"/><stop offset=".9" class="l1y0f3bez"/></radialGradient><radialGradient id="iEnB5ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -5.25 0 16 15.656)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="pss9c1r8j"/><stop offset=".952" class="l50z3dz-s"/></radialGradient><radialGradient id="i0bBsId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 6.4375 -5.20367 -1.26304 15.469 11.969)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="af4ljpy3n"/><stop offset="1" class="vlbxffbxu"/></radialGradient><radialGradient id="iAVmkgF" cx="0" cy="0" r="1" gradientTransform="matrix(0 5 -5 0 16 15.656)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="d82-h5npn"/><stop offset=".931" class="l50z3dz-s"/></radialGradient><radialGradient id="iGGbfqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 .3125 -.06641 .37192 18.313 2.5)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="iQ5GQvQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 .46875 -.58765 -.07835 18.5 2.656)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="owpd8jbtl"/><stop offset="1" class="ld930cb1v"/></radialGradient><radialGradient id="irgeBUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 .375 -.07971 -.33212 13.75 2.438)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="iSUTxrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34375 -.43088 0 13.906 2.594)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="owpd8jbtl"/><stop offset="1" class="ld930cb1v"/></radialGradient><radialGradient id="iGoPjrb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34008 .88685 -.1885 -.28483 9.35 4.005)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="icj1VHb" cx="0" cy="0" r="1" gradientTransform="rotate(126.504 1.115 4.941)scale(1.60695 .34155)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="iIAnhkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45658 1.54089 -.32748 -.09703 3.387 11.015)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="ib7uZXd" cx="0" cy="0" r="1" gradientTransform="matrix(.09798 1.60385 -.34092 .02083 2.546 15.612)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="imnsE5W" cx="0" cy="0" r="1" gradientTransform="matrix(.64079 1.47409 -.31324 .13616 3.326 20.218)" gradientUnits="userSpaceOnUse"><stop class="aw6d_sbem"/><stop offset="1" class="pt4a7le-d"/></radialGradient><radialGradient id="iNewcFe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14063 .85937 -.61835 -.82073 16.844 15.047)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="n2hau1b7s"/><stop offset="1" class="soopopbvk"/></radialGradient><radialGradient id="iAlXdre" cx="0" cy="0" r="1" gradientTransform="rotate(90 .15 15.85)scale(1.3125)" gradientUnits="userSpaceOnUse"><stop offset=".875" class="mkyfihmtu"/><stop offset=".918" class="pqmm-5b4p"/></radialGradient><radialGradient id="iSLfDsN" cx="0" cy="0" r="1" gradientTransform="rotate(129.341 5.824 17.072)scale(1.2324 1.14731)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="y3ecpw_4z"/><stop offset="1" class="cykezrbjv"/></radialGradient><radialGradient id="iwOQAGT" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.5 23)scale(1.5)" gradientUnits="userSpaceOnUse"><stop offset=".823" class="m1_d1461w"/><stop offset=".906" class="r9f2uxbxw"/></radialGradient><radialGradient id="i3Vw30P" cx="0" cy="0" r="1" gradientTransform="rotate(126.961 5.601 17.227)scale(1.975 2.89361)" gradientUnits="userSpaceOnUse"><stop offset=".923" class="rvbm4sbgu"/><stop offset=".975" class="f01jnmb5s"/></radialGradient><radialGradient id="iqHaGMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.51562 -1.98912 1.76354 21.953 23.328)" gradientUnits="userSpaceOnUse"><stop offset=".923" class="rvbm4sbgu"/><stop offset=".975" class="f01jnmb5s"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:folding-hand-fan" /></template>
<style>
.a-foipbpt {
  stop-color: var(--svg-color--ff4761, #FF4761);
}

.a6tldnqtn {
  stop-color: var(--svg-color--a10f42, #A10F42);
}

.af4ljpy3n {
  stop-color: var(--svg-color--917f99, #917F99);
}

.as5c_2j3v {
  stop-color: var(--svg-color--ce203a, #CE203A);
}

.aw6d_sbem {
  stop-color: var(--svg-color--a4283f, #A4283F);
}

.b-ygq8b3k {
  fill-rule: evenodd;
  d: path("M19.542 9.661a7 7 0 0 0-7.081 12.08z");
}

.bk3iqwx6f {
  stop-color: var(--svg-color--6d5279, #6D5279);
  stop-opacity: 0;
}

.bl6dndb1j {
  stop-color: var(--svg-color--f02e43, #F02E43);
}

.bmd2o8b-e {
  stop-color: var(--svg-color--bfb6ca, #BFB6CA);
}

.bmtl_ohcx {
  fill-rule: evenodd;
  d: path("M5.61 24.419a.44.44 0 0 1 .053-.617l10.055-8.436a.438.438 0 0 1 .562.67L6.226 24.473a.44.44 0 0 1-.617-.054");
}

.bn7aq8car {
  stop-color: var(--svg-color--930f33, #930F33);
}

.bqa25xb8v {
  stop-color: var(--svg-color--8a1f44, #8A1F44);
  stop-opacity: 0;
}

.bzbd886rw {
  cx: 22.5px;
  cy: 23.5px;
  r: 0.5px;
  fill: var(--svg-color--b72e5d, #B72E5D);
}

.c19oo1s2a {
  stop-color: var(--svg-color--ff586a, #FF586A);
}

.c42kcd2db {
  stop-color: var(--svg-color--ba405a, #BA405A);
}

.c9cn0tbtq {
  stop-color: var(--svg-color--ff3c57, #FF3C57);
}

.crz1tolxq {
  stop-color: var(--svg-color--605069, #605069);
}

.ctn7pvbtv {
  stop-color: var(--svg-color--a71531, #A71531);
}

.ctu_-oy8j {
  stop-color: var(--svg-color--bc2945, #BC2945);
}

.cykezrbjv {
  stop-color: var(--svg-color--ff6775, #FF6775);
  stop-opacity: 0;
}

.d0m_eabcp {
  stop-color: var(--svg-color--892146, #892146);
  stop-opacity: 0;
}

.d41vj6ggh {
  cx: 16px;
  cy: 15.701px;
  r: 1.313px;
  fill: var(--svg-color--2f1d1d, #2F1D1D);
}

.d82-h5npn {
  stop-color: var(--svg-color--6d6071, #6D6071);
}

.dad0bbbcn {
  stop-color: var(--svg-color--b3b0b5, #B3B0B5);
}

.dbdyi8u3o {
  cx: 16px;
  cy: 15.701px;
  r: 1.313px;
}

.dddf11u-o {
  stop-color: var(--svg-color--2e1934, #2E1934);
}

.dim9e1tfy {
  stop-color: var(--svg-color--881f48, #881F48);
}

.dpbbx8bny {
  stop-color: var(--svg-color--ff4e63, #FF4E63);
}

.dpzhp9big {
  stop-color: var(--svg-color--e1274b, #E1274B);
}

.dw43d2bhc {
  stop-color: var(--svg-color--6c4c7d, #6C4C7D);
  stop-opacity: 0;
}

.dwd9h0b_a {
  stop-color: var(--svg-color--ff1c3b, #FF1C3B);
}

.dz5vdbbgu {
  stop-color: var(--svg-color--ff0d2c, #FF0D2C);
}

.dzkt94_8c {
  stop-color: var(--svg-color--4c4156, #4C4156);
  stop-opacity: 0.673;
}

.e3on_nbfx {
  stop-color: var(--svg-color--898689, #898689);
  stop-opacity: 0;
}

.e9st0sbxj {
  stop-color: var(--svg-color--634d68, #634D68);
}

.ec3mdccep {
  stop-color: var(--svg-color--5d506a, #5D506A);
}

.eqxygsbiw {
  fill: var(--svg-color--a52b51, #A52B51);
  fill-rule: evenodd;
  d: path("M22.639 4.376A13.06 13.06 0 0 0 16 2.576c-7.249 0-13.125 5.876-13.125 13.125a13.12 13.12 0 0 0 6.486 11.325z");
}

.ey2w-4bue {
  stop-color: var(--svg-color--655773, #655773);
}

.f01jnmb5s {
  stop-color: var(--svg-color--e8549e, #E8549E);
}

.f4tudiyhy {
  stop-color: var(--svg-color--b21938, #B21938);
}

.f5-bt-z8y {
  stop-color: var(--svg-color--4c4156, #4C4156);
  stop-opacity: 0;
}

.f9nyzbcrj {
  fill: var(--svg-color--8f2949, #8F2949);
  fill-rule: evenodd;
  d: path("M19.542 9.661a7 7 0 0 0-7.081 12.08z");
}

.fhdbg6ujc {
  fill-rule: evenodd;
  d: path("M3.255 20.339a.44.44 0 0 1 .261-.56l12.334-4.49a.438.438 0 0 1 .299.822l-12.334 4.49a.44.44 0 0 1-.56-.262");
}

.fmnutjb2h {
  stop-color: var(--svg-color--2a1628, #2A1628);
}

.fnz83rb8q {
  stop-color: var(--svg-color--4f425a, #4F425A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.furiw9amr {
  fill-rule: evenodd;
  d: path("M15.925 16.133a.44.44 0 0 1-.355-.507l2.279-12.925a.437.437 0 1 1 .861.152l-2.279 12.925a.437.437 0 0 1-.507.355");
}

.fwrzkqbgb {
  stop-color: var(--svg-color--8c1e48, #8C1E48);
  stop-opacity: 0;
}

.fz7cwldhh {
  stop-color: var(--svg-color--2b162c, #2B162C);
  stop-opacity: 0;
}

.g88m66b1e {
  stop-color: var(--svg-color--291729, #291729);
  stop-opacity: 0;
}

.gddoheb0m {
  stop-color: var(--svg-color--72597d, #72597D);
}

.gomm1dv0i {
  stop-color: var(--svg-color--9e85b6, #9E85B6);
}

.gtjqrabid {
  stop-color: var(--svg-color--83697c, #83697C);
}

.gu-z4vbqv {
  stop-color: var(--svg-color--6e4e80, #6E4E80);
}

.gv55ymbsy {
  stop-color: var(--svg-color--807a84, #807A84);
  stop-opacity: 0;
}

.h-ul7wbvu {
  stop-color: var(--svg-color--2c162f, #2C162F);
}

.h5nabebrz {
  stop-color: var(--svg-color--b83759, #B83759);
}

.h945bk7yh {
  stop-color: var(--svg-color--ff1131, #FF1131);
}

.hd_3ymbcc {
  stop-color: var(--svg-color--2c162f, #2C162F);
  stop-opacity: 0;
}

.he-fr3b5z {
  stop-color: var(--svg-color--8b59a9, #8B59A9);
}

.hjze_ac2v {
  stop-color: var(--svg-color--6a4681, #6A4681);
}

.hn56k5h2m {
  stop-color: var(--svg-color--dd2b4b, #DD2B4B);
  stop-opacity: 0;
}

.huprstbsk {
  cx: 22.5px;
  cy: 23.5px;
  r: 1.5px;
}

.i0ej1sbkj {
  stop-color: var(--svg-color--b12263, #B12263);
}

.i2o8xyy4n {
  stop-color: var(--svg-color--b72c5b, #B72C5B);
}

.i8e5mgbvv {
  stop-color: var(--svg-color--2b162c, #2B162C);
}

.id71b27va {
  stop-color: var(--svg-color--ce203a, #CE203A);
  stop-opacity: 0;
}

.inr63ubis {
  stop-color: var(--svg-color--8d5cab, #8D5CAB);
}

.j0eilp8wg {
  stop-color: var(--svg-color--821d44, #821D44);
  stop-opacity: 0;
}

.j44oedbkw {
  fill-rule: evenodd;
  d: path("M5.61 6.983a.44.44 0 0 1 .616-.054l10.054 8.437a.438.438 0 1 1-.562.67L5.663 7.6a.44.44 0 0 1-.054-.617");
}

.jb7635beg {
  stop-color: var(--svg-color--ff2243, #FF2243);
}

.jx3tdzbpb {
  fill: var(--svg-color--352438, #352438);
  fill-rule: evenodd;
  d: path("M19.098 10.416a6.125 6.125 0 0 0-6.196 10.57z");
}

.k-tynkd-c {
  stop-color: var(--svg-color--9f152b, #9F152B);
}

.k3avo8j7a {
  stop-color: var(--svg-color--72597d, #72597D);
  stop-opacity: 0;
}

.k5tblvnvr {
  fill-rule: evenodd;
  d: path("M16.813 18.086v-1.072h1v1.072a1.25 1.25 0 0 0 1.645 1.186l.643-.215a2.25 2.25 0 0 1 2.962 2.135v1.947h-1v-1.947a1.25 1.25 0 0 0-1.646-1.186l-.643.214a2.25 2.25 0 0 1-2.962-2.134");
}

.ksq_e4brk {
  cx: 22.5px;
  cy: 23.5px;
  r: 1.5px;
  fill: var(--svg-color--dc3743, #DC3743);
}

.kte9s4bdw {
  stop-color: var(--svg-color--940d37, #940D37);
}

.kwd9jy65i {
  fill-rule: evenodd;
  d: path("M22.541 24.162a.4.4 0 0 0-.364.432l.439 5.11a.4.4 0 0 0 .797-.069l-.44-5.109a.4.4 0 0 0-.432-.364");
}

.kyn-13u-g {
  stop-color: var(--svg-color--b72b4f, #B72B4F);
}

.l1y0f3bez {
  stop-color: var(--svg-color--241827, #241827);
  stop-opacity: 0;
}

.l20869bbj {
  stop-color: var(--svg-color--b82847, #B82847);
}

.l50z3dz-s {
  stop-color: var(--svg-color--6d6071, #6D6071);
  stop-opacity: 0;
}

.lahyopbtb {
  stop-color: var(--svg-color--6c4c7d, #6C4C7D);
}

.ld930cb1v {
  stop-color: var(--svg-color--bd3851, #BD3851);
  stop-opacity: 0;
}

.ljki8bbop {
  stop-color: var(--svg-color--2a1628, #2A1628);
  stop-opacity: 0;
}

.lkoz8kbar {
  stop-color: var(--svg-color--fe1338, #FE1338);
}

.lopn4vsjn {
  stop-color: var(--svg-color--291729, #291729);
}

.lyzlxzcje {
  stop-color: var(--svg-color--821d44, #821D44);
}

.m1_d1461w {
  stop-color: var(--svg-color--ff325e, #FF325E);
}

.m9vb9k_kq {
  stop-color: var(--svg-color--e3284d, #E3284D);
  stop-opacity: 0;
}

.mavnlkjii {
  stop-color: var(--svg-color--807a84, #807A84);
}

.mk27tccrr {
  stop-color: var(--svg-color--7b598c, #7B598C);
  stop-opacity: 0;
}

.mkyfihmtu {
  stop-color: var(--svg-color--3d273f, #3D273F);
}

.mlpyr4bvu {
  stop-color: var(--svg-color--bf2343, #BF2343);
}

.modqunbqp {
  stop-color: var(--svg-color--821a39, #821A39);
  stop-opacity: 0;
}

.mxbjpnbfi {
  stop-color: var(--svg-color--5d506a, #5D506A);
  stop-opacity: 0;
}

.n2hau1b7s {
  stop-color: var(--svg-color--655f5f, #655F5F);
}

.n3zhp2kxd {
  fill-rule: evenodd;
  d: path("M18.656 11.171a5.25 5.25 0 1 0-5.311 9.06z");
}

.n518e0fei {
  stop-color: var(--svg-color--842247, #842247);
}

.n5h33e23k {
  stop-color: var(--svg-color--2d1730, #2D1730);
}

.nfgmxpbei {
  fill-rule: evenodd;
  d: path("M13.644 2.346a.44.44 0 0 1 .507.355l2.279 12.925a.437.437 0 1 1-.862.152l-2.28-12.925a.437.437 0 0 1 .356-.507");
}

.nkogj_b7o {
  stop-color: var(--svg-color--4c4156, #4C4156);
}

.nse4z9bpx {
  fill-rule: evenodd;
  d: path("M22.459 24.162a.4.4 0 0 1 .364.432l-.439 5.11a.4.4 0 0 1-.797-.069l.44-5.109a.4.4 0 0 1 .432-.364");
}

.ojcmu9bcs {
  stop-color: var(--svg-color--694f76, #694F76);
  stop-opacity: 0;
}

.on95lmbis {
  stop-color: var(--svg-color--bfb5c9, #BFB5C9);
}

.our7-pbrp {
  stop-color: var(--svg-color--6e4e80, #6E4E80);
  stop-opacity: 0;
}

.owpd8jbtl {
  stop-color: var(--svg-color--cc6170, #CC6170);
}

.p_bqpvbka {
  stop-color: var(--svg-color--ff3152, #FF3152);
}

.p00pytbzx {
  stop-color: var(--svg-color--6a4681, #6A4681);
  stop-opacity: 0;
}

.p6rs_7b1f {
  fill-rule: evenodd;
  d: path("M9.219 3.955a.44.44 0 0 1 .597.16l6.563 11.367a.437.437 0 0 1-.758.437L9.06 4.553a.44.44 0 0 1 .16-.598");
}

.pqmm-5b4p {
  stop-color: var(--svg-color--3d273f, #3D273F);
  stop-opacity: 0;
}

.pr3if9ufk {
  fill: var(--svg-color--25162b, #25162B);
  fill-rule: evenodd;
  d: path("M18.213 11.926a4.375 4.375 0 1 0-4.426 7.55z");
}

.pss9c1r8j {
  stop-color: var(--svg-color--a89caf, #A89CAF);
}

.pt4a7le-d {
  stop-color: var(--svg-color--a4283f, #A4283F);
  stop-opacity: 0;
}

.pthncqbka {
  stop-color: var(--svg-color--b9174b, #B9174B);
}

.pwi47fbae {
  fill-rule: evenodd;
  d: path("M3.255 11.062a.437.437 0 0 1 .56-.262l12.335 4.49a.438.438 0 0 1-.299.822l-12.334-4.49a.44.44 0 0 1-.262-.56");
}

.pzgmiebvd {
  stop-color: var(--svg-color--a18bb4, #A18BB4);
}

.q_dltacds {
  stop-color: var(--svg-color--8d5ead, #8D5EAD);
}

.q-tghsb_m {
  stop-color: var(--svg-color--b92c62, #B92C62);
}

.q3klehbor {
  fill-rule: evenodd;
  d: path("M21.903 24.2a.4.4 0 0 1 .33.46l-.838 5.06a.4.4 0 1 1-.79-.13l.838-5.06a.4.4 0 0 1 .46-.33");
}

.qelzzcbql {
  stop-color: var(--svg-color--cd6575, #CD6575);
}

.qpsw47uyk {
  stop-color: var(--svg-color--821a39, #821A39);
}

.qrn0-5b1x {
  stop-color: var(--svg-color--b61a3a, #B61A3A);
}

.r_fh92bsv {
  fill-rule: evenodd;
  d: path("M9.219 27.447a.44.44 0 0 1-.16-.597L22.184 4.116a.438.438 0 0 1 .757.438L9.816 27.287a.437.437 0 0 1-.597.16");
}

.r10g3ybid {
  stop-color: var(--svg-color--8e0f2c, #8E0F2C);
}

.r2tzyjbrt {
  stop-color: var(--svg-color--241827, #241827);
}

.r6ijrbgfl {
  stop-color: var(--svg-color--8c1e48, #8C1E48);
}

.r7renrgni {
  stop-color: var(--svg-color--881f48, #881F48);
  stop-opacity: 0;
}

.r9f2uxbxw {
  stop-color: var(--svg-color--ff325e, #FF325E);
  stop-opacity: 0;
}

.rbws9u6oz {
  stop-color: var(--svg-color--694f76, #694F76);
}

.rcz5ll4ii {
  stop-color: var(--svg-color--a71f59, #A71F59);
}

.rm3q10b8v {
  stop-color: var(--svg-color--fc3155, #FC3155);
}

.rmkn1jb_c {
  stop-color: var(--svg-color--634d68, #634D68);
  stop-opacity: 0;
}

.rmttnqwei {
  stop-color: var(--svg-color--2d1730, #2D1730);
  stop-opacity: 0;
}

.row51-uhw {
  stop-color: var(--svg-color--b0afb1, #B0AFB1);
}

.rvbm4sbgu {
  stop-color: var(--svg-color--e8549e, #E8549E);
  stop-opacity: 0;
}

.rzdrg1bgg {
  stop-color: var(--svg-color--734a8a, #734A8A);
}

.s2i6y7bgg {
  stop-color: var(--svg-color--8d0e2d, #8D0E2D);
}

.s5jgq_bgj {
  stop-color: var(--svg-color--7f1a42, #7F1A42);
  stop-opacity: 0;
}

.sdprqxbvx {
  stop-color: var(--svg-color--b82467, #B82467);
}

.slf7zspdc {
  stop-color: var(--svg-color--2b162d, #2B162D);
}

.soopopbvk {
  stop-color: var(--svg-color--655f5f, #655F5F);
  stop-opacity: 0;
}

.srhmncmvz {
  fill-rule: evenodd;
  d: path("M19.098 10.416a6.125 6.125 0 0 0-6.196 10.57z");
}

.ss5hu2uca {
  stop-color: var(--svg-color--c65769, #C65769);
}

.t_t0shb-v {
  stop-color: var(--svg-color--c55468, #C55468);
}

.t55hy4our {
  fill-rule: evenodd;
  d: path("M22.196 5.131A12.2 12.2 0 0 0 16 3.451c-6.765 0-12.25 5.485-12.25 12.25c0 4.505 2.432 8.442 6.054 10.57z");
}

.t5w3suqgj {
  stop-color: var(--svg-color--e02b4d, #E02B4D);
  stop-opacity: 0;
}

.tqos3qb8z {
  stop-color: var(--svg-color--8b59a9, #8B59A9);
  stop-opacity: 0;
}

.trdrorfem {
  stop-color: var(--svg-color--bb2240, #BB2240);
}

.tv6p64b0s {
  stop-color: var(--svg-color--8a1f44, #8A1F44);
}

.txig1xbox {
  stop-color: var(--svg-color--ff0c2a, #FF0C2A);
}

.u_q3q3b3h {
  stop-color: var(--svg-color--ff5464, #FF5464);
}

.u6pd3cblt {
  stop-color: var(--svg-color--ff3158, #FF3158);
}

.uk4ff7vqt {
  stop-color: var(--svg-color--b82860, #B82860);
}

.un4buxyfs {
  stop-color: var(--svg-color--db254b, #DB254B);
}

.utbk8fboz {
  stop-color: var(--svg-color--9c132e, #9C132E);
}

.uu2y_eb7a {
  stop-color: var(--svg-color--af2856, #AF2856);
}

.v57eacczk {
  stop-color: var(--svg-color--898689, #898689);
}

.v8c8umbmi {
  stop-color: var(--svg-color--362841, #362841);
}

.vd2xl0bhb {
  stop-color: var(--svg-color--2d1632, #2D1632);
}

.viaii4ssw {
  fill-rule: evenodd;
  d: path("M23.097 24.2a.4.4 0 0 0-.33.46l.838 5.06a.4.4 0 1 0 .79-.13l-.838-5.06a.4.4 0 0 0-.46-.33");
}

.vlbxffbxu {
  stop-color: var(--svg-color--917f99, #917F99);
  stop-opacity: 0;
}

.vq4cbsbmu {
  d: path("M18.273 17.012a2.625 2.625 0 0 0-.96-3.586l-2.625 4.547a2.625 2.625 0 0 0 3.585-.961");
}

.vrskulb0z {
  stop-color: var(--svg-color--ad1043, #AD1043);
}

.vvq92abpd {
  stop-color: var(--svg-color--2d1632, #2D1632);
  stop-opacity: 0;
}

.w58w-yb9j {
  fill: var(--svg-color--826990, #826990);
  fill-rule: evenodd;
  d: path("M18.656 11.171a5.25 5.25 0 1 0-5.311 9.06z");
}

.w9speobyp {
  stop-color: var(--svg-color--7b598c, #7B598C);
}

.wc2903zfe {
  stop-color: var(--svg-color--2e1934, #2E1934);
  stop-opacity: 0;
}

.x7es02b4h {
  stop-color: var(--svg-color--a7244a, #A7244A);
}

.y1-3ekbwt {
  fill-rule: evenodd;
  d: path("M16.813 18.086v-1.072h1v1.072a1.25 1.25 0 0 0 1.645 1.186l.321-.108l.317.949l-.322.107a2.25 2.25 0 0 1-2.962-2.134");
}

.y2-q9xbjq {
  stop-color: var(--svg-color--9b1243, #9B1243);
}

.y3ecpw_4z {
  stop-color: var(--svg-color--ff6775, #FF6775);
}

.ymr_eybzo {
  stop-color: var(--svg-color--b53156, #B53156);
}

.yspjt5szs {
  stop-color: var(--svg-color--dd284a, #DD284A);
}

.yxyl29bnm {
  stop-color: var(--svg-color--ff3052, #FF3052);
}

.z27ab3bao {
  stop-color: var(--svg-color--7f1a42, #7F1A42);
}

.z605i0bxm {
  stop-color: var(--svg-color--83697c, #83697C);
  stop-opacity: 0;
}

.zhz5zib5p {
  stop-color: var(--svg-color--2b162d, #2B162D);
  stop-opacity: 0;
}

.ziv_2mfft {
  fill-rule: evenodd;
  d: path("M2.438 15.701c0-.242.195-.437.437-.437H16a.437.437 0 1 1 0 .875H2.875a.44.44 0 0 1-.437-.438");
}

.zpev2qbfl {
  stop-color: var(--svg-color--ab2552, #AB2552);
}

</style>
