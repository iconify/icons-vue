<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="elu8tbbmd"/><path fill="url(#iVy989b)" class="aalw2hzij"/><path fill="url(#iGyBcQc)" class="aalw2hzij"/><path fill="url(#icKYrRF)" class="aalw2hzij"/><path fill="url(#idK9K0s)" class="aalw2hzij"/><path fill="url(#iiQuYoe)" class="aalw2hzij"/><path fill="url(#iXMRUge)" class="lswc4e84y"/><path fill="url(#iOCfY0b)" class="lswc4e84y"/><path fill="url(#ic1Mkun)" class="lswc4e84y"/><path fill="url(#iHsygWb)" class="lswc4e84y"/><path fill="url(#iYK2lPZ)" class="lswc4e84y"/><path class="fjqvmwb_n"/><path fill="url(#iRw5C3d)" class="pbgdrbcuf"/><path class="ni_gbmbcl"/><path fill="url(#iui2EJc)" class="nbqj-rsxo"/><path fill="url(#izUaH7d)" class="nbqj-rsxo"/><path fill="url(#i2dRdce)" class="nbqj-rsxo"/><path fill="url(#izYrSjb)" class="ca4pl6baq"/><path fill="url(#i8I48Un)" class="ca4pl6baq"/><path fill="url(#ioAR5be)" class="ca4pl6baq"/><path fill="url(#i6XXQIe)" class="ca4pl6baq"/><path fill="url(#iyD47pd)" class="ca4pl6baq"/><path fill="url(#ipgLA0d)" class="ca4pl6baq"/><path fill="url(#iTY4pGc)" class="ca4pl6baq"/><path fill="url(#iXNjpue)" class="ca4pl6baq"/><path fill="url(#ipsBoyV)" class="ca4pl6baq"/><g filter="url(#i71W5hb)"><path fill="url(#i2fIUIc)" class="mps04kbvv"/></g><g filter="url(#iwiNE2c)"><path fill="url(#i1ijCdd)" class="cv9bk0bia"/></g><g filter="url(#iXm4Acc)"><path stroke="url(#igJuvye)" class="u3vhq2b9u"/></g><path fill="url(#iBXHykd)" class="a9ye6ub7g"/><path fill="url(#i1PoHld)" class="a9ye6ub7g"/><path fill="url(#iT7Bs5d)" class="a9ye6ub7g"/><g filter="url(#iDeCyId)"><path class="hvwi4btbh"/></g><g filter="url(#i8cLSXc)"><path class="hwtba-v1w"/></g><g filter="url(#i7UzKNc)"><path class="ruplkxb3f"/></g><g filter="url(#iRD6Tmd)"><path class="q9qx5l22d"/></g><g filter="url(#is6Isvd)"><path class="d9jfj405j"/></g><g filter="url(#i68cC7d)"><path class="tyubj0bhu"/></g><g filter="url(#iqZAUom)"><path class="v1o2eswoe"/></g><g filter="url(#i4FYAQe)"><path class="a37hogi1k"/></g><g filter="url(#i8HsONd)"><path class="uzgd4ibeh"/></g><g filter="url(#ifBUNje)"><path class="w80pfxb7z"/></g><g filter="url(#i6lHafe)"><path class="g06wslkso"/></g><g filter="url(#iXSoxtd)"><path class="dajr3wbwe"/></g><path fill="url(#ijAcEoQ)" class="mdyf2c68b"/><path fill="url(#iFiIgod)" class="mdyf2c68b"/><path fill="url(#iuiV7xd)" class="mdyf2c68b"/><path fill="url(#idhcKTc)" class="mdyf2c68b"/><path fill="url(#iSjjFHb)" class="mdyf2c68b"/><path fill="url(#iPEzYfe)" class="iy_nbkwoa"/><path fill="url(#iKoCMmc)" class="iy_nbkwoa"/><path fill="url(#i5J7uPW)" class="iy_nbkwoa"/><path fill="url(#iDdv8Lb)" class="iy_nbkwoa"/><path fill="url(#iO9GuoT)" class="iy_nbkwoa"/><path fill="url(#iwvatpc)" class="pwphcub6h"/><path fill="url(#i2OGmqe)" class="pwphcub6h"/><path fill="url(#iWFOAae)" class="pwphcub6h"/><path fill="url(#i00fLub)" class="pwphcub6h"/><path fill="url(#iJVVFNe)" class="pwphcub6h"/><path fill="url(#iJRF7zd)" class="uyoj1vbsw"/><path fill="url(#iWZIy6d)" class="uyoj1vbsw"/><path fill="url(#iDpSN9c)" class="uyoj1vbsw"/><path fill="url(#iLHDY2o)" class="uyoj1vbsw"/><path fill="url(#iic2tMb)" class="uyoj1vbsw"/><path fill="url(#ijtgWAb)" class="yoi3okh1j"/><path fill="url(#ikSQTpc)" class="yoi3okh1j"/><path fill="url(#iBDjONe)" class="yoi3okh1j"/><path fill="url(#iqO1WQc)" class="yoi3okh1j"/><path fill="url(#iEZ6ptq)" class="yoi3okh1j"/><path fill="url(#iH7NwEL)" class="dyqpn6bjs"/><path fill="url(#i0cWqvd)" class="dyqpn6bjs"/><path fill="url(#icUqHec)" class="dyqpn6bjs"/><path fill="url(#iAwcpJe)" class="dyqpn6bjs"/><path fill="url(#ikjFGsb)" class="dyqpn6bjs"/><path fill="url(#iY7XdTb)" class="ih4vu3bbp"/><path fill="url(#igyWFwb)" class="ih4vu3bbp"/><path fill="url(#iJwPUec)" class="ih4vu3bbp"/><path fill="url(#if6RREc)" class="ih4vu3bbp"/><path fill="url(#iRFTETu)" class="ih4vu3bbp"/><path fill="url(#iEeaQId)" class="q5pbr54jt"/><path fill="url(#iSTCpob)" class="q5pbr54jt"/><path fill="url(#i3bimAe)" class="q5pbr54jt"/><path fill="url(#ivGzWjc)" class="q5pbr54jt"/><path fill="url(#icR20Wc)" class="q5pbr54jt"/><path fill="url(#inACheU)" class="aws_zhblc"/><path fill="url(#iigZW4i)" class="aws_zhblc"/><path fill="url(#iz5EGfb)" class="aws_zhblc"/><path fill="url(#iI7hHFd)" class="aws_zhblc"/><path fill="url(#iaDVZeC)" class="aws_zhblc"/><path fill="url(#iPDzsDR)" class="jcsl22zuk"/><path fill="url(#iHIqmDc)" class="jcsl22zuk"/><path fill="url(#i8TSyzd)" class="jcsl22zuk"/><path fill="url(#iIIhZrc)" class="jcsl22zuk"/><path fill="url(#ic19Vyc)" class="jcsl22zuk"/><path fill="url(#ikyBXku)" class="sizgkbbuc"/><path fill="url(#i6l8MRb)" class="sizgkbbuc"/><path fill="url(#iHZctob)" class="sizgkbbuc"/><path fill="url(#iU39usb)" class="sizgkbbuc"/><path fill="url(#i7gvtuI)" class="sizgkbbuc"/><path fill="url(#ijr3jZb)" class="g80a78wxe"/><path fill="url(#i4j1iIe)" class="g80a78wxe"/><path fill="url(#iGbJYLc)" class="g80a78wxe"/><path fill="url(#idXDmTd)" class="g80a78wxe"/><path fill="url(#iGFq49V)" class="g80a78wxe"/><g filter="url(#isLEvbe)"><path class="zet1ykmrt"/></g><g filter="url(#iC33mQb)"><ellipse fill="url(#ilUimqb)" class="wjzi-cb1f"/></g><g filter="url(#iDuTytc)"><ellipse fill="url(#iIiW8Md)" class="ekx8okr2l"/></g><g filter="url(#iucWi5c)"><ellipse fill="url(#iWN52Zb)" class="tbigl3bfr"/></g><g filter="url(#iQNFWZc)"><rect class="k__zecces"/></g><g filter="url(#iNkznyn)"><rect class="b24ibobmq"/></g><g filter="url(#ieHMlxc)"><rect class="h8cbgxp8j"/></g><g filter="url(#ioMRYeG)"><path class="kkuo2hbgi"/></g><path fill="url(#i7mzsge)" class="xo6193_ea"/><path fill="url(#ivPYl9b)" class="xo6193_ea"/><path fill="url(#iy2oezb)" class="xo6193_ea"/><path fill="url(#iepxr0b)" class="xo6193_ea"/><defs><linearGradient id="iGyBcQc" x1="25.625" x2="26.484" y1="11.188" y2="11.188" gradientUnits="userSpaceOnUse"><stop class="x715qabdy"/><stop offset="1" class="ds879lbry"/></linearGradient><linearGradient id="idK9K0s" x1="28.875" x2="27.75" y1="9.266" y2="10.641" gradientUnits="userSpaceOnUse"><stop class="mjqm49hev"/><stop offset="1" class="pifqvqb2e"/></linearGradient><linearGradient id="iiQuYoe" x1="28.688" x2="28.688" y1="16.234" y2="13.359" gradientUnits="userSpaceOnUse"><stop class="srqymac6k"/><stop offset="1" class="isalu6byh"/></linearGradient><linearGradient id="iOCfY0b" x1="14.063" x2="15.75" y1="8.516" y2="10.172" gradientUnits="userSpaceOnUse"><stop class="gh2c8ccdf"/><stop offset="1" class="p4c6-4bmt"/></linearGradient><linearGradient id="ic1Mkun" x1="11.656" x2="12.906" y1="13.828" y2="13.828" gradientUnits="userSpaceOnUse"><stop class="gh2c8ccdf"/><stop offset="1" class="p4c6-4bmt"/></linearGradient><linearGradient id="iHsygWb" x1="16.383" x2="15.031" y1="10.828" y2="10.734" gradientUnits="userSpaceOnUse"><stop class="b6uu1xbww"/><stop offset="1" class="kpax5sbgb"/></linearGradient><linearGradient id="iYK2lPZ" x1="14.047" x2="14.047" y1="15.875" y2="15.094" gradientUnits="userSpaceOnUse"><stop class="s270m9b9l"/><stop offset="1" class="ugxtkxb3n"/></linearGradient><linearGradient id="iRw5C3d" x1="16.781" x2="14.813" y1="19.984" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="n_n-lybof"/><stop offset="1" class="fh74e0bwp"/></linearGradient><linearGradient id="izYrSjb" x1="4.438" x2="20.84" y1="-2.376" y2="32.876" gradientUnits="userSpaceOnUse"><stop class="qko9x2c_t"/><stop offset="1" class="n0pscv9zz"/></linearGradient><linearGradient id="i8I48Un" x1="14.101" x2="14.101" y1="31.408" y2="26.573" gradientUnits="userSpaceOnUse"><stop class="gyr-eff1e"/><stop offset="1" class="ln2vi4b-v"/></linearGradient><linearGradient id="i2fIUIc" x1="16.65" x2="28.23" y1="14.61" y2="14.61" gradientUnits="userSpaceOnUse"><stop class="wy_lp3b3h"/><stop offset="1" class="ay6y6pota"/></linearGradient><linearGradient id="i1ijCdd" x1="13.938" x2="24.281" y1="27.922" y2="19.578" gradientUnits="userSpaceOnUse"><stop class="t_iize7bw"/><stop offset="1" class="h7s21ebdl"/></linearGradient><linearGradient id="igJuvye" x1="22.654" x2="22.654" y1="8.206" y2="32.063" gradientUnits="userSpaceOnUse"><stop class="zm67kbc3a"/><stop offset="1" class="qrejiebsz"/></linearGradient><linearGradient id="iT7Bs5d" x1="16.402" x2="16.058" y1="24.904" y2="24.685" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ijAcEoQ" x1="18.359" x2="19.242" y1="18.649" y2="18.649" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="iFiIgod" x1="19.414" x2="19.711" y1="18.649" y2="18.649" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iSjjFHb" x1="18.422" x2="18.727" y1="18.359" y2="18.359" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iPEzYfe" x1="20.296" x2="21.179" y1="18.649" y2="18.649" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="iKoCMmc" x1="21.351" x2="21.648" y1="18.649" y2="18.649" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iO9GuoT" x1="20.358" x2="20.663" y1="18.359" y2="18.359" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iwvatpc" x1="22.232" x2="23.115" y1="18.649" y2="18.649" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="i2OGmqe" x1="23.287" x2="23.583" y1="18.649" y2="18.649" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iJVVFNe" x1="22.295" x2="22.599" y1="18.359" y2="18.359" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iJRF7zd" x1="18.359" x2="19.242" y1="15.592" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="iWZIy6d" x1="19.414" x2="19.711" y1="15.592" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iic2tMb" x1="18.422" x2="18.727" y1="15.302" y2="15.302" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="ijtgWAb" x1="20.296" x2="21.179" y1="15.592" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="ikSQTpc" x1="21.351" x2="21.648" y1="15.592" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iEZ6ptq" x1="20.358" x2="20.663" y1="15.302" y2="15.302" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iH7NwEL" x1="22.232" x2="23.115" y1="15.628" y2="15.628" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="i0cWqvd" x1="23.287" x2="23.584" y1="15.628" y2="15.628" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="ikjFGsb" x1="22.295" x2="22.599" y1="15.339" y2="15.339" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iY7XdTb" x1="18.359" x2="19.242" y1="12.534" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="igyWFwb" x1="19.414" x2="19.711" y1="12.534" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iRFTETu" x1="18.422" x2="18.727" y1="12.245" y2="12.245" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iEeaQId" x1="20.296" x2="21.179" y1="12.534" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="iSTCpob" x1="21.351" x2="21.648" y1="12.534" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="icR20Wc" x1="20.358" x2="20.663" y1="12.245" y2="12.245" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="inACheU" x1="22.232" x2="23.115" y1="12.534" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="iigZW4i" x1="23.287" x2="23.584" y1="12.534" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iaDVZeC" x1="22.295" x2="22.599" y1="12.245" y2="12.245" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="iPDzsDR" x1="18.359" x2="19.242" y1="9.472" y2="9.472" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="iHIqmDc" x1="19.414" x2="19.711" y1="9.472" y2="9.472" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="ic19Vyc" x1="18.422" x2="18.727" y1="9.181" y2="9.181" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="ikyBXku" x1="20.296" x2="21.179" y1="9.472" y2="9.472" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="i6l8MRb" x1="21.351" x2="21.648" y1="9.472" y2="9.472" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="i7gvtuI" x1="20.358" x2="20.663" y1="9.181" y2="9.181" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><linearGradient id="ijr3jZb" x1="22.232" x2="23.115" y1="9.472" y2="9.472" gradientUnits="userSpaceOnUse"><stop class="lw-m-hkka"/><stop offset="1" class="y20gzy81k"/></linearGradient><linearGradient id="i4j1iIe" x1="23.287" x2="23.584" y1="9.472" y2="9.472" gradientUnits="userSpaceOnUse"><stop class="cbmsh2x3k"/><stop offset="1" class="lw-m-hkka"/></linearGradient><linearGradient id="iGFq49V" x1="22.295" x2="22.599" y1="9.181" y2="9.181" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></linearGradient><radialGradient id="iVy989b" cx="0" cy="0" r="1" gradientTransform="matrix(3.65625 0 0 8.92967 25.75 11.68)" gradientUnits="userSpaceOnUse"><stop class="uh5do5ufj"/><stop offset="1" class="tdupos2tq"/></radialGradient><radialGradient id="icKYrRF" cx="0" cy="0" r="1" gradientTransform="scale(2.37432 4.39067)rotate(90 5.04 7.62)" gradientUnits="userSpaceOnUse"><stop class="q735gvbgh"/><stop offset="1" class="fmyqgy64y"/></radialGradient><radialGradient id="iXMRUge" cx="0" cy="0" r="1" gradientTransform="rotate(-73.679 16.464 -2.221)scale(5.89375 3.3427)" gradientUnits="userSpaceOnUse"><stop class="bfjs6__bg"/><stop offset="1" class="lyce7wboq"/></radialGradient><radialGradient id="iui2EJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 .76563 -1.51735 2.35344 25.094 23.063)" gradientUnits="userSpaceOnUse"><stop class="yih3x6boe"/><stop offset="1" class="wzh6kwb0v"/></radialGradient><radialGradient id="izUaH7d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37334 2.68748 -2.09225 -1.84768 29.998 23.422)" gradientUnits="userSpaceOnUse"><stop class="e8jh6nbvb"/><stop offset="1" class="ecjyp-l4l"/></radialGradient><radialGradient id="i2dRdce" cx="0" cy="0" r="1" gradientTransform="matrix(2.60937 .25 -.25637 2.67586 24.813 25.89)" gradientUnits="userSpaceOnUse"><stop class="qssleenir"/><stop offset=".994" class="maj0nkk7y"/></radialGradient><radialGradient id="ioAR5be" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 2.35947 -4.15779 2.25778 9.094 5.094)" gradientUnits="userSpaceOnUse"><stop class="bpmnz5v1t"/><stop offset="1" class="evzy2z74d"/></radialGradient><radialGradient id="i6XXQIe" cx="0" cy="0" r="1" gradientTransform="rotate(140.505 11.957 6.59)scale(5.75048 14.4918)" gradientUnits="userSpaceOnUse"><stop class="csktc5b0m"/><stop offset="1" class="zw8xl55aq"/></radialGradient><radialGradient id="iyD47pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 -.03125 .06384 7.5336 16.031 10.203)" gradientUnits="userSpaceOnUse"><stop class="blf0onbuc"/><stop offset="1" class="s91xd2nkn"/></radialGradient><radialGradient id="ipgLA0d" cx="0" cy="0" r="1" gradientTransform="matrix(5.59375 -7.5 3.84735 2.86948 11.813 12.203)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="z-fvv4byp"/><stop offset="1" class="essgugbxg"/></radialGradient><radialGradient id="iTY4pGc" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 -4.18431 2.40988 1.83578 13.875 9.371)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="yupdpcblu"/><stop offset="1" class="s7iwozbky"/></radialGradient><radialGradient id="iXNjpue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15624 -1.95268 7.1111 -4.21069 9.844 9.99)" gradientUnits="userSpaceOnUse"><stop class="yupdpcblu"/><stop offset="1" class="s7iwozbky"/></radialGradient><radialGradient id="ipsBoyV" cx="0" cy="0" r="1" gradientTransform="rotate(-74.916 10.932 .284)scale(3.2422 10.8208)" gradientUnits="userSpaceOnUse"><stop class="yupdpcblu"/><stop offset=".71" class="s7iwozbky"/></radialGradient><radialGradient id="iBXHykd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 16.648 25.136)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i1PoHld" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 3.467 15.819)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iuiV7xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66777 0 19.082 19.875)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="idhcKTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40214 .48438 -.38832 -.32239 19.484 17.578)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="i5J7uPW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66777 0 21.019 19.875)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iDdv8Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40214 .48438 -.38832 -.32239 21.42 17.578)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iWFOAae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66754 0 22.955 19.875)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="i00fLub" cx="0" cy="0" r="1" gradientTransform="matrix(-.402 .48437 -.38829 -.32226 23.357 17.578)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iDpSN9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66777 0 19.082 16.818)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iLHDY2o" cx="0" cy="0" r="1" gradientTransform="matrix(-.40214 .48438 -.38832 -.32239 19.484 14.521)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iBDjONe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66777 0 21.019 16.818)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iqO1WQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40214 .48438 -.38832 -.32239 21.42 14.521)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="icUqHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66754 0 22.955 16.854)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iAwcpJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.402 .48437 -.38829 -.32226 23.357 14.557)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iJwPUec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66777 0 19.082 13.76)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="if6RREc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40214 .48438 -.38832 -.32239 19.484 11.464)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="i3bimAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66777 0 21.019 13.76)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="ivGzWjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40214 .48438 -.38832 -.32239 21.42 11.463)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iz5EGfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60156 .66754 0 22.955 13.76)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iI7hHFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.402 .48437 -.38829 -.32226 23.357 11.464)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="i8TSyzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60452 .66777 0 19.082 10.704)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iIIhZrc" cx="0" cy="0" r="1" gradientTransform="rotate(129.562 7.765 8.786)scale(.63139 .50571)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iHZctob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60452 .66777 0 21.019 10.704)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="iU39usb" cx="0" cy="0" r="1" gradientTransform="rotate(129.562 8.733 9.242)scale(.63139 .50571)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="iGbJYLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60452 .66754 0 22.955 10.704)" gradientUnits="userSpaceOnUse"><stop class="wh825ib8f"/><stop offset="1" class="k90w_6bwu"/></radialGradient><radialGradient id="idXDmTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.402 .48676 -.38984 -.32197 23.357 8.396)" gradientUnits="userSpaceOnUse"><stop class="ksbua9b0x"/><stop offset="1" class="lmc-nhb9z"/></radialGradient><radialGradient id="ilUimqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94531 .42014 0 27.547 27.422)" gradientUnits="userSpaceOnUse"><stop class="pz0_gxbgl"/><stop offset="1" class="j8uz-cb4w"/></radialGradient><radialGradient id="iIiW8Md" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94531 .42014 0 28.531 27.422)" gradientUnits="userSpaceOnUse"><stop class="pz0_gxbgl"/><stop offset="1" class="j8uz-cb4w"/></radialGradient><radialGradient id="iWN52Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94531 .42014 0 29.648 27.422)" gradientUnits="userSpaceOnUse"><stop class="pz0_gxbgl"/><stop offset="1" class="j8uz-cb4w"/></radialGradient><radialGradient id="i7mzsge" cx="0" cy="0" r="1" gradientTransform="rotate(106.887 -2.072 16.625)scale(.91443 1.64624)" gradientUnits="userSpaceOnUse"><stop class="nk60q7bbv"/><stop offset="1" class="nk2sfebje"/></radialGradient><radialGradient id="ivPYl9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.9339 -.66406 .94547 -1.32967 13.75 25.016)" gradientUnits="userSpaceOnUse"><stop class="j76nl8b7c"/><stop offset="1" class="rw93o_bzc"/></radialGradient><radialGradient id="iy2oezb" cx="0" cy="0" r="1" gradientTransform="matrix(.82813 .30281 -.50003 1.36748 11.71 24.367)" gradientUnits="userSpaceOnUse"><stop class="j76nl8b7c"/><stop offset=".712" class="rw93o_bzc"/></radialGradient><radialGradient id="iepxr0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.41221 -.25781 .14996 .82142 11.383 25.21)" gradientUnits="userSpaceOnUse"><stop class="j76nl8b7c"/><stop offset=".805" class="rw93o_bzc"/></radialGradient><filter id="i71W5hb" width="11.003" height="15.857" x="14.75" y="6.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation="1.25"/></filter><filter id="iwiNE2c" width="15.691" height="11.125" x="8.563" y="18.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".5"/></filter><filter id="iXm4Acc" width="10.5" height="24.438" x="17.403" y="2.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation="1.5"/></filter><filter id="iDeCyId" width="1.78" height="2.83" x="18.087" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="i8cLSXc" width="1.78" height="2.83" x="20.023" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="i7UzKNc" width="1.78" height="2.83" x="21.959" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="iRD6Tmd" width="1.78" height="2.83" x="18.087" y="14.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="is6Isvd" width="1.78" height="2.83" x="20.023" y="14.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="i68cC7d" width="1.78" height="2.83" x="21.959" y="14.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="iqZAUom" width="1.78" height="2.83" x="18.087" y="11.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="i4FYAQe" width="1.78" height="2.83" x="20.023" y="11.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="i8HsONd" width="1.78" height="2.83" x="21.959" y="11.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="ifBUNje" width="1.78" height="2.84" x="18.087" y="8.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="i6lHafe" width="1.78" height="2.84" x="20.023" y="8.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="iXSoxtd" width="1.78" height="2.84" x="21.959" y="8.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".2"/></filter><filter id="isLEvbe" width="13.409" height="8.798" x="4.063" y="2.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation="1"/></filter><filter id="iC33mQb" width=".975" height="1.444" x="27.098" y="26.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".15"/></filter><filter id="iDuTytc" width=".975" height="1.444" x="28.083" y="26.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".15"/></filter><filter id="iucWi5c" width=".975" height="1.444" x="29.2" y="26.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".15"/></filter><filter id="iQNFWZc" width=".883" height="1.223" x="27.023" y="14.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".125"/></filter><filter id="iNkznyn" width=".883" height="1.223" x="28.172" y="14.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".125"/></filter><filter id="ieHMlxc" width=".883" height="1.223" x="29.32" y="14.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".125"/></filter><filter id="ioMRYeG" width="5.563" height="4.286" x="11.125" y="17.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5401" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crocodile" /></template>
<style>
.a37hogi1k {
  fill: var(--svg-color--209858, #209858);
  d: path("M20.913 13.62a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.a9ye6ub7g {
  d: path("M16.5 25.797a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.aalw2hzij {
  d: path("M29.383 10.828L27 8.547s-.79-.906-1.39-.906h-.626l.922 4.922c.492 0 .977.132.977.648v1.844c0 .25.088.636.52.636c.609 0 .398-.847.515-.847s-.137.875.582.875c.621 0 .367-.875.496-.875s-.11.875.555.875c.43 0 .512-.384.512-.664v-2.086c0-.906-.12-1.58-.68-2.14");
}

.aws_zhblc {
  d: path("M22.955 13.55a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c0 .27-.22.49-.49.49");
}

.ay6y6pota {
  stop-color: var(--svg-color--3b9584, #3B9584);
  stop-opacity: 0;
}

.b24ibobmq {
  width: 0.383px;
  height: 0.723px;
  x: 28.422px;
  y: 14.754px;
  fill: var(--svg-color--59b698, #59B698);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.191px;
}

.b6uu1xbww {
  stop-color: var(--svg-color--2b7963, #2B7963);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bfjs6__bg {
  stop-color: var(--svg-color--429086, #429086);
}

.blf0onbuc {
  stop-color: var(--svg-color--83b6a0, #83B6A0);
}

.bpmnz5v1t {
  stop-color: var(--svg-color--69aa84, #69AA84);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.ca4pl6baq {
  d: path("M16.79 2.234c-2.225 0-4.21.295-5.892 1.806C8.492 6.202 6.976 6.948 5.25 7.085c-.586.047-2.234 0-2.234 0c-.28 0-.605-.036-.782.295c-.176.33.458.85.93 1.154c2.836 1.821 5.14 1.387 7.07.775s3.051-1.94 4.375-2.2c1.813-.357 1.547 1.425 1.547 2.533L16.086 21c0 .575-.002 1.15-.262 1.665c-.34.664-1.037.956-1.687 1.313c-.07.04-.16.03-.22-.03c-.233-.125-.487-.183-.87-.183c-.777 0-1.371.69-1.371 1.283c0 .079-.04.139-.11.168c0 0-1.816.909-2.332 1.203s-1.322 1.002-1.312 1.736c.01.982.906 1.612 2.25 1.612h6.297c3.42 0 6.57-1.794 8.27-4.74a9.43 9.43 0 0 0 1.26-4.692v-8.976c0-5.068-4.179-9.054-9.21-9.124");
}

.cbmsh2x3k {
  stop-color: var(--svg-color--b6ba46, #B6BA46);
  stop-opacity: 0;
}

.csktc5b0m {
  stop-color: var(--svg-color--61c08b, #61C08B);
}

.cv9bk0bia {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m16.625 25.297l-7.062 2.875c2.343 0 5.656-.127 7.343-.438c4.818-.887 6.427-6.52 6.344-8.687h-2.437c0 3.35-2.792 5.562-4.188 6.25");
}

.d9jfj405j {
  fill: var(--svg-color--209858, #209858);
  d: path("M20.913 16.677a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.dajr3wbwe {
  fill: var(--svg-color--209858, #209858);
  d: path("M22.85 10.562a.49.49 0 0 1-.49-.49v-1.06a.49.49 0 0 1 .98 0v1.05a.5.5 0 0 1-.49.5");
}

.ds879lbry {
  stop-color: var(--svg-color--27a367, #27A367);
  stop-opacity: 0;
}

.dyqpn6bjs {
  d: path("M22.955 16.643a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c0 .27-.22.49-.49.49");
}

.e8jh6nbvb {
  stop-color: var(--svg-color--5ada9a, #5ADA9A);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ecjyp-l4l {
  stop-color: var(--svg-color--5ada9a, #5ADA9A);
  stop-opacity: 0;
}

.ekx8okr2l {
  cx: 28.57px;
  cy: 27.086px;
  rx: 0.188px;
  ry: 0.422px;
}

.elu8tbbmd {
  fill: var(--svg-color--45a895, #45A895);
  d: path("M29.383 10.828L27 8.547s-.79-.906-1.39-.906h-.626l.922 4.922c.492 0 .977.132.977.648v1.844c0 .25.088.636.52.636c.609 0 .398-.847.515-.847s-.137.875.582.875c.621 0 .367-.875.496-.875s-.11.875.555.875c.43 0 .512-.384.512-.664v-2.086c0-.906-.12-1.58-.68-2.14");
}

.essgugbxg {
  stop-color: var(--svg-color--347e74, #347E74);
  stop-opacity: 0;
}

.evzy2z74d {
  stop-color: var(--svg-color--69aa84, #69AA84);
  stop-opacity: 0;
}

.fh74e0bwp {
  stop-color: var(--svg-color--2f906e, #2F906E);
  stop-opacity: 0;
}

.fjqvmwb_n {
  fill: var(--svg-color--37a979, #37A979);
  d: path("M12.71 17.836c-.86 0-1.712.757-1.712 1.617v2.79c0 .27.115.554.443.554c.586 0 .36-.906.557-.906s-.13.906.5.906c.588 0 .323-.906.5-.906c.178 0-.084.906.56.906c.36 0 .44-.275.44-.555v-1.27c0-.14.11-.175.25-.175h5.13v-2.961z");
}

.fmyqgy64y {
  stop-color: var(--svg-color--5bc59a, #5BC59A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g06wslkso {
  fill: var(--svg-color--209858, #209858);
  d: path("M20.913 10.562a.49.49 0 0 1-.49-.49v-1.06a.49.49 0 0 1 .98 0v1.05c.01.27-.21.5-.49.5");
}

.g80a78wxe {
  d: path("M22.955 10.492a.49.49 0 0 1-.49-.49v-1.06a.49.49 0 0 1 .98 0v1.05a.5.5 0 0 1-.49.5");
}

.gh2c8ccdf {
  stop-color: var(--svg-color--319068, #319068);
}

.gyr-eff1e {
  stop-color: var(--svg-color--6f85d2, #6F85D2);
}

.h7s21ebdl {
  stop-color: var(--svg-color--55c9ba, #55C9BA);
  stop-opacity: 0;
}

.h8cbgxp8j {
  width: 0.383px;
  height: 0.723px;
  x: 29.57px;
  y: 14.754px;
  fill: var(--svg-color--59b698, #59B698);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.191px;
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hvwi4btbh {
  fill: var(--svg-color--209858, #209858);
  d: path("M18.977 19.734a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.hwtba-v1w {
  fill: var(--svg-color--209858, #209858);
  d: path("M20.913 19.734a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.ih4vu3bbp {
  d: path("M19.082 13.55a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.isalu6byh {
  stop-color: var(--svg-color--3a9c83, #3A9C83);
  stop-opacity: 0;
}

.iy_nbkwoa {
  d: path("M21.019 19.664a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.j76nl8b7c {
  stop-color: var(--svg-color--58ce99, #58CE99);
}

.j8uz-cb4w {
  stop-color: var(--svg-color--5cc6a8, #5CC6A8);
  stop-opacity: 0;
}

.jcsl22zuk {
  d: path("M19.082 10.492a.49.49 0 0 1-.49-.49v-1.06a.49.49 0 0 1 .98 0v1.05c.01.27-.21.5-.49.5");
}

.k__zecces {
  width: 0.383px;
  height: 0.723px;
  x: 27.273px;
  y: 14.754px;
  fill: var(--svg-color--59b698, #59B698);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.191px;
}

.k90w_6bwu {
  stop-color: var(--svg-color--bfb665, #BFB665);
  stop-opacity: 0;
}

.kkuo2hbgi {
  stroke: var(--svg-color--4eab96, #4EAB96);
  d: path("M15.688 19.464h-2.063a1 1 0 0 0-1 1v.786");
}

.kpax5sbgb {
  stop-color: var(--svg-color--2b7963, #2B7963);
  stop-opacity: 0;
}

.ksbua9b0x {
  stop-color: var(--svg-color--c9e14a, #C9E14A);
}

.lmc-nhb9z {
  stop-color: var(--svg-color--c9e14a, #C9E14A);
  stop-opacity: 0;
}

.ln2vi4b-v {
  stop-color: var(--svg-color--8798d6, #8798D6);
  stop-opacity: 0;
}

.lswc4e84y {
  d: path("m16.383 7.305l-.235 5.304c-.91 0-.937.438-.937 1.102v1.453c0 .172-.035.524-.484.524c-.61 0-.38-.852-.536-.852s.133.851-.535.851s-.402-.851-.547-.851c-.144 0 .121.851-.546.851c-.356 0-.47-.253-.47-.523v-3.078c0-.64.671-1.33 1.087-1.734c1.242-1.211 3.203-3.047 3.203-3.047");
}

.lw-m-hkka {
  stop-color: var(--svg-color--b6ba46, #B6BA46);
}

.lyce7wboq {
  stop-color: var(--svg-color--2c7b66, #2C7B66);
}

.maj0nkk7y {
  stop-color: var(--svg-color--4b7996, #4B7996);
  stop-opacity: 0;
}

.mdyf2c68b {
  d: path("M19.082 19.664a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.mjqm49hev {
  stop-color: var(--svg-color--58c28e, #58C28E);
}

.mps04kbvv {
  d: path("M17.25 8.807h6.003v10.857H17.25z");
}

.n_n-lybof {
  stop-color: var(--svg-color--2f906e, #2F906E);
}

.n0pscv9zz {
  stop-color: var(--svg-color--53d096, #53D096);
}

.nbqj-rsxo {
  d: path("M28.438 22.797c.86 0 1.56.7 1.56 1.56v2.94c0 .262-.186.426-.5.426c-.615 0-.373-.871-.521-.871s.101.87-.489.87c-.66 0-.379-.87-.535-.87s.14.87-.512.87c-.28 0-.443-.145-.443-.425v-1.313c0-.14-.11-.25-.25-.25h-5.13v-2.937z");
}

.ni_gbmbcl {
  fill: var(--svg-color--4eb3a6, #4EB3A6);
  d: path("M28.438 22.797c.86 0 1.56.7 1.56 1.56v2.94c0 .262-.186.426-.5.426c-.615 0-.373-.871-.521-.871s.101.87-.489.87c-.66 0-.379-.87-.535-.87s.14.87-.512.87c-.28 0-.443-.145-.443-.425v-1.313c0-.14-.11-.25-.25-.25h-5.13v-2.937z");
}

.nk2sfebje {
  stop-color: var(--svg-color--3cb26f, #3CB26F);
  stop-opacity: 0;
}

.nk60q7bbv {
  stop-color: var(--svg-color--3cb26f, #3CB26F);
}

.p4c6-4bmt {
  stop-color: var(--svg-color--319068, #319068);
  stop-opacity: 0;
}

.pbgdrbcuf {
  d: path("M12.71 17.836c-.86 0-1.712.757-1.712 1.617v2.79c0 .27.115.554.443.554c.586 0 .36-.906.557-.906s-.13.906.5.906c.588 0 .323-.906.5-.906c.178 0-.084.906.56.906c.36 0 .44-.275.44-.555v-1.27c0-.14.11-.175.25-.175h5.13v-2.961z");
}

.pifqvqb2e {
  stop-color: var(--svg-color--58c28e, #58C28E);
  stop-opacity: 0;
}

.pwphcub6h {
  d: path("M22.955 19.664a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c0 .27-.22.49-.49.49");
}

.pz0_gxbgl {
  stop-color: var(--svg-color--5cc6a8, #5CC6A8);
}

.q5pbr54jt {
  d: path("M21.019 13.55a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.q735gvbgh {
  stop-color: var(--svg-color--5bc59a, #5BC59A);
}

.q9qx5l22d {
  fill: var(--svg-color--209858, #209858);
  d: path("M18.977 16.677a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.qko9x2c_t {
  stop-color: var(--svg-color--2e8873, #2E8873);
}

.qrejiebsz {
  stop-color: var(--svg-color--52e484, #52E484);
}

.qssleenir {
  stop-color: var(--svg-color--4b7996, #4B7996);
}

.ruplkxb3f {
  fill: var(--svg-color--209858, #209858);
  d: path("M22.85 19.734a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c0 .27-.22.49-.49.49");
}

.rw93o_bzc {
  stop-color: var(--svg-color--58ce99, #58CE99);
  stop-opacity: 0;
}

.s270m9b9l {
  stop-color: var(--svg-color--488b8a, #488B8A);
}

.s7iwozbky {
  stop-color: var(--svg-color--6982ac, #6982AC);
  stop-opacity: 0;
}

.s91xd2nkn {
  stop-color: var(--svg-color--76a18f, #76A18F);
  stop-opacity: 0;
}

.sizgkbbuc {
  d: path("M21.019 10.492a.49.49 0 0 1-.49-.49v-1.06a.49.49 0 0 1 .98 0v1.05c.01.27-.21.5-.49.5");
}

.srqymac6k {
  stop-color: var(--svg-color--3a9c83, #3A9C83);
}

.t_iize7bw {
  stop-color: var(--svg-color--55c9ba, #55C9BA);
}

.tbigl3bfr {
  cx: 29.688px;
  cy: 27.086px;
  rx: 0.188px;
  ry: 0.422px;
}

.tdupos2tq {
  stop-color: var(--svg-color--3fb07c, #3FB07C);
  stop-opacity: 0;
}

.tyubj0bhu {
  fill: var(--svg-color--209858, #209858);
  d: path("M22.85 16.714a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c0 .27-.22.49-.49.49");
}

.u3vhq2b9u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21.404 6.428c.833.459 2.5 2.025 2.5 4.626v11.812");
}

.ugxtkxb3n {
  stop-color: var(--svg-color--488b8a, #488B8A);
  stop-opacity: 0;
}

.uh5do5ufj {
  stop-color: var(--svg-color--3fb07c, #3FB07C);
}

.uyoj1vbsw {
  d: path("M19.082 16.607a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.uzgd4ibeh {
  fill: var(--svg-color--209858, #209858);
  d: path("M22.85 13.62a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c0 .27-.22.49-.49.49");
}

.v1o2eswoe {
  fill: var(--svg-color--209858, #209858);
  d: path("M18.977 13.62a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.w80pfxb7z {
  fill: var(--svg-color--209858, #209858);
  d: path("M18.977 10.563a.49.49 0 0 1-.49-.49v-1.06a.49.49 0 0 1 .98 0v1.05c.01.27-.21.5-.49.5");
}

.wh825ib8f {
  stop-color: var(--svg-color--bfb665, #BFB665);
}

.wjzi-cb1f {
  cx: 27.586px;
  cy: 27.086px;
  rx: 0.188px;
  ry: 0.422px;
}

.wy_lp3b3h {
  stop-color: var(--svg-color--3b9584, #3B9584);
}

.wzh6kwb0v {
  stop-color: var(--svg-color--36815c, #36815C);
  stop-opacity: 0;
}

.x715qabdy {
  stop-color: var(--svg-color--27a367, #27A367);
}

.xo6193_ea {
  d: path("M11.584 25.207c.19.242.931.544 1.63.242c.467-.2.864-.832.781-1.455a.2.2 0 0 1-.078-.046c-.233-.126-.487-.184-.87-.184c-.777 0-1.371.69-1.371 1.283a.17.17 0 0 1-.092.16");
}

.y20gzy81k {
  stop-color: var(--svg-color--c8d35a, #C8D35A);
}

.yih3x6boe {
  stop-color: var(--svg-color--36815c, #36815C);
}

.yoi3okh1j {
  d: path("M21.019 16.607a.49.49 0 0 1-.49-.49v-1.05a.49.49 0 0 1 .98 0v1.05c.01.27-.21.49-.49.49");
}

.yupdpcblu {
  stop-color: var(--svg-color--6982ac, #6982AC);
}

.z-fvv4byp {
  stop-color: var(--svg-color--347e74, #347E74);
}

.zet1ykmrt {
  fill: var(--svg-color--60b0a8, #60B0A8);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M11.594 7.422c-2.05 1.525-4.542 1.49-5.531 1.281c.651.02 2.452-.387 4.437-2.187c1.535-1.392 3.06-2.139 4.012-2.469c.383-.132.776.093.912.474c.227.635-.401 1.42-1.06 1.566c-.769.17-1.727.559-2.77 1.335");
}

.zm67kbc3a {
  stop-color: var(--svg-color--63d099, #63D099);
}

.zw8xl55aq {
  stop-color: var(--svg-color--61c08b, #61C08B);
  stop-opacity: 0;
}

</style>
