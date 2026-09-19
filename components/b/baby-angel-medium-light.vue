<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGRbIQc)"><path fill="url(#iSvqZrc)" class="nrppcccoy"/><path fill="url(#iVTymKe)" class="nrppcccoy"/><path fill="url(#itkDPrs)" class="nrppcccoy"/><path fill="url(#iSIxRue)" class="nrppcccoy"/><path fill="url(#iK2sFBb)" class="nrppcccoy"/><path fill="url(#izpEITV)" class="nrppcccoy"/></g><path fill="url(#ia5fWVd)" class="nrppcccoy"/><path class="ghz5m_bfp"/><path fill="url(#i8Awcnb)" class="gl9izobcn"/><path fill="url(#iTar7Vb)" class="gl9izobcn"/><path fill="url(#idvSGxc)" class="gl9izobcn"/><path fill="url(#iDyvBtb)" class="gl9izobcn"/><g filter="url(#iwfRGhD)"><path class="o1eq0ncmd"/><path fill="url(#idyR2FG)" class="dqfxuybrk"/><path fill="url(#iRhcLKb)" class="dqfxuybrk"/><path fill="url(#iqzYI3c)" class="dqfxuybrk"/></g><g filter="url(#iL5zCPc)"><path class="js3ii64ht"/><path fill="url(#i30BmLc)" class="z53de0b4i"/><path fill="url(#iUU4cbb)" class="z53de0b4i"/><path fill="url(#iDbMFxE)" class="z53de0b4i"/></g><g filter="url(#iP6iGMe)"><rect transform="matrix(-1 0 0 1 24.129 23.718)" class="ljzk3pb-v"/><rect fill="url(#ir52G6c)" transform="matrix(-1 0 0 1 24.129 23.718)" class="spx4avb5u"/></g><g filter="url(#iK7KRpc)"><path class="xfz3hkpfj"/><path fill="url(#iqYNgAd)" class="rpdg7fn4n"/><path fill="url(#iLNq9Ug)" class="rpdg7fn4n"/></g><g filter="url(#iMYHaLc)"><path class="paeqn7zyv"/><path fill="url(#iQnH7Be)" class="wlytqeyju"/><path fill="url(#i5Exblb)" class="wlytqeyju"/></g><path fill="url(#iq3f9md)" class="wlytqeyju"/><g filter="url(#iyEp0wd)"><path class="jxs1tbciu"/><path class="b6j4q-bzp"/><path fill="url(#idPoluH)" class="j0zneqbkw"/></g><path fill="url(#i8tTakH)" class="j0zneqbkw"/><g filter="url(#i32yuko)"><rect fill="url(#i38fRtP)" class="i7yuhdkni"/><rect fill="url(#iAgVlad)" class="i7yuhdkni"/></g><path fill="url(#iFEs87b)" class="gp16bnbyv"/><path fill="url(#iFFAeKb)" class="gp16bnbyv"/><g filter="url(#iJPgjqd)"><path fill="url(#ixwwsib)" class="m8axcpb1d"/></g><path fill="url(#iffvlpb)" class="ypb3pybtz"/><path fill="url(#iIW2ARd)" class="ypb3pybtz"/><path fill="url(#ihYl3XG)" class="ypb3pybtz"/><path fill="url(#iagCaTl)" class="ypb3pybtz"/><g filter="url(#iYxlh4b)"><path fill="url(#iip2ord)" class="adqa7dbjx"/></g><g filter="url(#iNjYAQb)"><path class="zbvptbbft"/><path fill="url(#i5Qi3zv)" class="wccw7qb8q"/><path fill="url(#i1eWVBb)" class="wccw7qb8q"/><path fill="url(#ir79GQd)" class="wccw7qb8q"/><path fill="url(#iMTN2Rd)" class="wccw7qb8q"/><path fill="url(#ibQYnyd)" class="wccw7qb8q"/><path fill="url(#iYL0b7b)" class="wccw7qb8q"/><path fill="url(#izPuENd)" class="wccw7qb8q"/></g><path fill="url(#iBDS8Cd)" class="wccw7qb8q"/><path fill="url(#iitlN9b)" class="wccw7qb8q"/><g filter="url(#ieVRgud)"><path stroke="url(#ilGCdke)" class="pd07-bcno"/></g><g filter="url(#i6F08Gc)"><path class="uycwipbki"/></g><path class="bgkb4sbto"/><path fill="url(#is4PG5d)" class="lfvq_ouae"/><path fill="url(#izTbqac)" class="v5z2z1b2h"/><path class="k21_qub0k"/><g filter="url(#iarsgHd)"><path class="no871xb4y"/></g><g filter="url(#icVzeCc)"><path stroke="url(#ia8aj6b)" class="ggfrtbcgr"/></g><g filter="url(#ijOxZOc)"><path class="dc9tl2udd"/></g><g filter="url(#iIV5cJc)"><path stroke="url(#iPBbVld)" class="ydp9v2bac"/></g><g filter="url(#iuKqxXc)"><path fill="url(#irMC2zc)" class="oqhwimbnp"/></g><g filter="url(#iNJypyx)"><path class="muyp72b3o"/><path fill="url(#isP3btb)" class="dm88szb0o"/><path fill="url(#iNcCqNb)" class="dm88szb0o"/><path fill="url(#iF75uJW)" class="dm88szb0o"/><path fill="url(#iGavGda)" class="dm88szb0o"/></g><g filter="url(#iUA8uYd)"><path class="sy6kv575h"/></g><g filter="url(#i0uuRyd)"><path fill="url(#itp410w)" class="j89jvbcli"/><path fill="url(#iNdHJHb)" class="j89jvbcli"/></g><g filter="url(#iA8Wfzc)"><path class="uy2f9acre"/><path fill="url(#ipdHDTc)" class="e1njngbsx"/></g><g filter="url(#iBRjR8N)"><path fill="url(#iIT2yic)" class="nnvkjjj2j"/></g><g filter="url(#iO4cJtc)"><path fill="url(#iOjZVyd)" class="nwjhx0baq"/></g><g filter="url(#ibYtg0c)"><ellipse transform="rotate(-27.914 11.006 19.61)" class="lxpu7rbhx"/><ellipse fill="url(#iBp0UZk)" transform="rotate(-27.914 11.006 19.61)" class="bvun35brj"/></g><g filter="url(#i0QduZd)"><path fill="url(#ikdlBTd)" class="ig6laenir"/></g><defs><radialGradient id="iSvqZrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.75003 3.6875 -9.72121 -1.97727 20.936 3.273)" gradientUnits="userSpaceOnUse"><stop class="j4e9jliyw"/><stop offset="1" class="t7aapjj0e"/></radialGradient><radialGradient id="iVTymKe" cx="0" cy="0" r="1" gradientTransform="rotate(-57.45 10.945 -4.159)scale(5.22735 10.6403)" gradientUnits="userSpaceOnUse"><stop class="v_ro-mcce"/><stop offset="1" class="ak0e0gbla"/></radialGradient><radialGradient id="itkDPrs" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.46875 -1.11569 1.02074 9.827 6.867)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="t82mlk1zf"/><stop offset="1" class="hrncwbz_t"/></radialGradient><radialGradient id="iSIxRue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 -.98438 .58816 -.61616 10.327 7.32)" gradientUnits="userSpaceOnUse"><stop class="oxnp2k1qi"/><stop offset="1" class="ih62nvbvg"/></radialGradient><radialGradient id="iK2sFBb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 1.85939 -1.34213 -1.93987 23.265 7.664)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="i2to8tbny"/><stop offset="1" class="rr59_uoqr"/></radialGradient><radialGradient id="izpEITV" cx="0" cy="0" r="1" gradientTransform="rotate(144.605 10.25 6.882)scale(1.45673 1.05149)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="ohd-ppblk"/><stop offset="1" class="c62dirbjk"/></radialGradient><radialGradient id="ia5fWVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93752 -7.271 18.54198 -4.94092 11.718 9.732)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="op4ic3bzn"/><stop offset="1" class="uoj15rbmy"/></radialGradient><radialGradient id="iTar7Vb" cx="0" cy="0" r="1" gradientTransform="matrix(.6072 2.64774 -4.70572 1.07914 25.39 27.518)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="idvSGxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.52434 .60868 -.33593 -.28939 26.855 28.02)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iRhcLKb" cx="0" cy="0" r="1" gradientTransform="matrix(.76907 2.71875 -5.8088 1.64318 26.539 25.413)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="iqzYI3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.66412 .625 -.34814 -.36993 28.395 25.93)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iUU4cbb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 2.71875 -6.83491 2.35687 27.733 23.32)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="m63xmacvx"/><stop offset=".922" class="ghrfdpdai"/></radialGradient><radialGradient id="iDbMFxE" cx="0" cy="0" r="1" gradientTransform="matrix(-.80957 .625 -.33743 -.43707 29.996 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iqYNgAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 1.73438 -1.37456 -.54486 8.812 28.492)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="y7rsoxb6i"/><stop offset="1" class="i8um3jglr"/></radialGradient><radialGradient id="iLNq9Ug" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 -2.21094 5.39927 1.3355 6.765 30.117)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="bs3nz4btd"/><stop offset="1" class="qxhhvqurd"/></radialGradient><radialGradient id="iQnH7Be" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 2.25 -2.22312 -.80279 8.78 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="mjdwlzfcx"/><stop offset="1" class="cb_xa0byd"/></radialGradient><radialGradient id="i5Exblb" cx="0" cy="0" r="1" gradientTransform="rotate(-69.661 23.009 9.976)scale(2.42119 7.08044)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="a-hxohb_j"/><stop offset="1" class="yi34m9bam"/></radialGradient><radialGradient id="iq3f9md" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0827 3.1875 -5.20641 -1.76845 5.832 25.21)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="i8tTakH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 3.46875 -6.65848 -2.33947 4.718 23.117)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="i38fRtP" cx="0" cy="0" r="1" gradientTransform="rotate(122.4 -2.426 16.404)scale(1.9246 3.13561)" gradientUnits="userSpaceOnUse"><stop class="uqd9t5bdt"/><stop offset="1" class="vsxpbmbdw"/></radialGradient><radialGradient id="iFFAeKb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27086 .1733 -.18022 -3.40126 7.257 20.78)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="ymutrvb0h"/><stop offset="1" class="dcp108bys"/></radialGradient><radialGradient id="ixwwsib" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.675 13.932)scale(1.86659)" gradientUnits="userSpaceOnUse"><stop class="vdhu5sbwc"/><stop offset="1" class="xdhwqtbkz"/></radialGradient><radialGradient id="iIW2ARd" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 2.974 22.117)scale(4.36175 4.18006)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="f_manrjbp"/><stop offset="1" class="a4f2nm63s"/></radialGradient><radialGradient id="ihYl3XG" cx="0" cy="0" r="1" gradientTransform="rotate(-48.351 35.104 -17.883)scale(2.57035 2.5364)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="vnf59qbgc"/><stop offset=".883" class="wjpixgrsk"/></radialGradient><radialGradient id="iagCaTl" cx="0" cy="0" r="1" gradientTransform="matrix(.75093 -3.52358 2.767 .58969 25.315 21.43)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="ypa0dqb5t"/><stop offset="1" class="op74yoooa"/></radialGradient><radialGradient id="iip2ord" cx="0" cy="0" r="1" gradientTransform="matrix(1.37188 .21662 -.32025 2.02816 25.446 20.753)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="n6775zkib"/><stop offset="1" class="a8evesbiu"/></radialGradient><radialGradient id="ir79GQd" cx="0" cy="0" r="1" gradientTransform="rotate(82.171 -8.613 13.778)scale(9.32913 2.84448)" gradientUnits="userSpaceOnUse"><stop class="j04i2bc2h"/><stop offset="1" class="ika7xqbdn"/></radialGradient><radialGradient id="iMTN2Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15526 -12.01479 18.85295 -1.81278 11.12 30.008)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="a4f2nm63s"/><stop offset="1" class="f_manrjbp"/></radialGradient><radialGradient id="ibQYnyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.29968 -2.42607 3.23476 1.7329 11.351 19.308)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="yap3dzbqh"/><stop offset="1" class="pkhanubeu"/></radialGradient><radialGradient id="iYL0b7b" cx="0" cy="0" r="1" gradientTransform="matrix(.46212 -2.51272 2.94204 .54108 20.881 19.538)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="be1prbbvx"/><stop offset="1" class="piifpilex"/></radialGradient><radialGradient id="izPuENd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.35029 -5.45866 0 22.817 20.867)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yse4ebceo"/></radialGradient><radialGradient id="iitlN9b" cx="0" cy="0" r="1" gradientTransform="rotate(-106.498 17.179 5.02)scale(17.29 24.9812)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="wu77zvqhp"/><stop offset="1" class="mmztprbmz"/></radialGradient><radialGradient id="is4PG5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84844 -2.94014 0 19.914 19.828)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ynn7rr4al"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="tzlh-yb0a"/></radialGradient><radialGradient id="izTbqac" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84844 -2.94014 0 11.624 19.828)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ynn7rr4al"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="tzlh-yb0a"/></radialGradient><radialGradient id="isP3btb" cx="0" cy="0" r="1" gradientTransform="rotate(-11.039 48.787 -59.239)scale(7.36522 6.14425)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="gqs8qobxe"/><stop offset="1" class="wxdt1jb_s"/></radialGradient><radialGradient id="iNcCqNb" cx="0" cy="0" r="1" gradientTransform="matrix(5.66094 -2.48383 2.39826 5.4659 12.246 8.737)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="uhbk1cbqf"/><stop offset=".912" class="qcx_m5b9c"/></radialGradient><radialGradient id="iF75uJW" cx="0" cy="0" r="1" gradientTransform="rotate(-122.764 11.017 .43)scale(6.21242 6.40492)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="itfb13gqc"/><stop offset="1" class="vder1tbnm"/></radialGradient><radialGradient id="iGavGda" cx="0" cy="0" r="1" gradientTransform="matrix(2.83041 4.50556 -4.32752 2.71857 15.279 6.975)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="yq-pa7bnx"/><stop offset=".966" class="e2nc-mb3x"/></radialGradient><radialGradient id="itp410w" cx="0" cy="0" r="1" gradientTransform="matrix(1.76179 .04332 -.0224 .91097 15.322 22.37)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="gyv3q3b9l"/><stop offset="1" class="fl5tp5bfj"/></radialGradient><radialGradient id="iNdHJHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.31412 -1.65866 0 16.037 21.806)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="k-93cikvm"/><stop offset="1" class="xujuduamj"/></radialGradient><radialGradient id="ipdHDTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.52838 -.68089 .93742 -.72745 19.394 20.02)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBp0UZk" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 15.491 4.763)scale(1.12576 1.3532)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iGRbIQc" width="17.94" height="7.94" x="7.011" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.596078 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iwfRGhD" width="7.412" height="2.194" x="20.982" y="25.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iL5zCPc" width="9.014" height="2.194" x="20.982" y="23.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iP6iGMe" width="4.369" height="6.627" x="20.16" y="23.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.54902 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iK7KRpc" width="6.273" height="2.439" x="4.645" y="27.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.541176 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iMYHaLc" width="7.813" height="2.494" x="3.105" y="25.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iyEp0wd" width="9.414" height="2.494" x="1.504" y="23.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="i32yuko" width="4.369" height="6.627" x="7.471" y="23.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.54902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iJPgjqd" width="4.233" height="4.233" x="5.14" y="18.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".125"/></filter><filter id="iYxlh4b" width="4.347" height="4.347" x="22.643" y="18.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".125"/></filter><filter id="iNjYAQb" width="21.983" height="24.03" x="5.489" y="5.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.760784 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22290" result="effect2_innerShadow_3987_22290"/></filter><filter id="ieVRgud" width="6.971" height="2.719" x="12.551" y="23.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".05"/></filter><filter id="i6F08Gc" width="6.47" height="2.218" x="12.802" y="23.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iarsgHd" width="3.533" height="1.57" x="9.511" y="15.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.247059 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="icVzeCc" width="2.983" height=".97" x="9.711" y="15.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".1"/></filter><filter id="ijOxZOc" width="3.533" height="1.57" x="18.846" y="15.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iIV5cJc" width="2.983" height=".97" x="18.996" y="15.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".1"/></filter><filter id="iuKqxXc" width="7.356" height="8.133" x="12.329" y="4.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".25"/></filter><filter id="iNJypyx" width="7.494" height="7.898" x="12.146" y="4.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.721569 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22290"/></filter><filter id="iUA8uYd" width="3.438" height="2.482" x="14.195" y="21.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".25"/></filter><filter id="i0uuRyd" width="2.938" height="1.982" x="14.568" y="21.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".125"/></filter><filter id="iA8Wfzc" width="1.537" height="1.331" x="18.369" y="18.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".05"/></filter><filter id="iBRjR8N" width="1.519" height="1.57" x="20.411" y="19.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".1"/></filter><filter id="iO4cJtc" width="1.736" height="1.859" x="11.941" y="19.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".1"/></filter><filter id="ibYtg0c" width="1.825" height="1.349" x="10.094" y="18.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation=".05"/></filter><filter id="i0QduZd" width="12.933" height="11.81" x="14.398" y="6.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22290" stdDeviation="1.25"/></filter><linearGradient id="i8Awcnb" x1="24.585" x2="24.585" y1="30.168" y2="28.673" gradientUnits="userSpaceOnUse"><stop offset=".079" class="ja2ta5btn"/><stop offset="1" class="oci36vbzb"/></linearGradient><linearGradient id="iDyvBtb" x1="24.436" x2="24.436" y1="27.906" y2="28.304" gradientUnits="userSpaceOnUse"><stop class="quz6sacji"/><stop offset="1" class="hw65_7bjg"/></linearGradient><linearGradient id="idyR2FG" x1="25.518" x2="25.518" y1="27.906" y2="26.859" gradientUnits="userSpaceOnUse"><stop offset=".216" class="e6rsc3sik"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="i30BmLc" x1="26.49" x2="26.49" y1="25.812" y2="24.765" gradientUnits="userSpaceOnUse"><stop offset=".216" class="rhghrobxp"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="ir52G6c" x1="0" x2=".958" y1="5.398" y2="5.398" gradientUnits="userSpaceOnUse"><stop class="lwh7ev7yo"/><stop offset="1" class="lesqr_bdp"/></linearGradient><linearGradient id="idPoluH" x1="6.461" x2="6.461" y1="23.718" y2="24.601" gradientUnits="userSpaceOnUse"><stop class="gjp7xwfce"/><stop offset="1" class="lo1zrhbvw"/></linearGradient><linearGradient id="iAgVlad" x1="7.871" x2="9.124" y1="29.117" y2="29.117" gradientUnits="userSpaceOnUse"><stop class="gw5f7-xty"/><stop offset="1" class="v8imspx_m"/></linearGradient><linearGradient id="iFEs87b" x1="4.737" x2="6.903" y1="18.066" y2="23.611" gradientUnits="userSpaceOnUse"><stop class="fmllmi0vm"/><stop offset="1" class="ex13nsb1n"/></linearGradient><linearGradient id="iffvlpb" x1="27.482" x2="25.095" y1="19.048" y2="22.918" gradientUnits="userSpaceOnUse"><stop class="iw08qbcjx"/><stop offset="1" class="k8yy-p62i"/></linearGradient><linearGradient id="i5Qi3zv" x1="16.056" x2="16.056" y1="30.543" y2="25.806" gradientUnits="userSpaceOnUse"><stop offset=".195" class="ep5muxxmd"/><stop offset="1" class="bp184cb9v"/></linearGradient><linearGradient id="i1eWVBb" x1="7.539" x2="17.936" y1="18.99" y2="21.647" gradientUnits="userSpaceOnUse"><stop class="dvexzpbfd"/><stop offset="1" class="rtvwugb3k"/></linearGradient><linearGradient id="iBDS8Cd" x1="16.056" x2="16.056" y1="30.543" y2="27.308" gradientUnits="userSpaceOnUse"><stop offset=".195" class="kfuvhdcxh"/><stop offset="1" class="y8qlx76pm"/></linearGradient><linearGradient id="ilGCdke" x1="13.878" x2="14.34" y1="25.445" y2="24.607" gradientUnits="userSpaceOnUse"><stop class="g87cs9b-d"/><stop offset="1" class="ylr-iebya"/></linearGradient><linearGradient id="ia8aj6b" x1="10.34" x2="12.535" y1="16.535" y2="16.205" gradientUnits="userSpaceOnUse"><stop class="w9x82yb4n"/><stop offset="1" class="ysf50-btc"/></linearGradient><linearGradient id="iPBbVld" x1="21.431" x2="18.571" y1="16.708" y2="16.448" gradientUnits="userSpaceOnUse"><stop class="w9x82yb4n"/><stop offset="1" class="ysf50-btc"/></linearGradient><linearGradient id="irMC2zc" x1="16.336" x2="15.376" y1="5.122" y2="12.048" gradientUnits="userSpaceOnUse"><stop offset=".709" class="opjqgdepo"/><stop offset="1" class="jezlerabr"/></linearGradient><linearGradient id="iIT2yic" x1="21.686" x2="20.972" y1="19.95" y2="20.391" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOjZVyd" x1="13.319" x2="12.604" y1="19.95" y2="20.391" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikdlBTd" x1="17.582" x2="26.543" y1="15.726" y2="10.325" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-angel-medium-light" /></template>
<style>
.a-hxohb_j {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
  stop-opacity: 0;
}

.a4f2nm63s {
  stop-color: var(--svg-color--bc7c81, #BC7C81);
}

.a8evesbiu {
  stop-color: var(--svg-color--dd9d78, #DD9D78);
}

.adqa7dbjx {
  d: path("M24.817 22.531a1.924 1.924 0 1 0 0-3.847a1.924 1.924 0 0 0 0 3.847");
}

.ak0e0gbla {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
  stop-opacity: 0;
}

.b6j4q-bzp {
  fill: var(--svg-color--f1d2d6, #F1D2D6);
  d: path("M2.004 24.217c0-.275.223-.498.498-.498h8.416v2.093H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.be1prbbvx {
  stop-color: var(--svg-color--e1a08c, #E1A08C);
}

.bgkb4sbto {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.39 18.122a3.18 3.18 0 0 1 3.087 2.412a.625.625 0 0 1-.61.776h-5.083a.524.524 0 0 1-.518-.62a3.185 3.185 0 0 1 3.124-2.568m-9.242 0a3.18 3.18 0 0 0-3.087 2.412a.625.625 0 0 0 .61.776h5.083a.524.524 0 0 0 .518-.62a3.19 3.19 0 0 0-3.124-2.568");
}

.bp184cb9v {
  stop-color: var(--svg-color--b46f93, #B46F93);
  stop-opacity: 0;
}

.bs3nz4btd {
  stop-color: var(--svg-color--e7cbd8, #E7CBD8);
  stop-opacity: 0;
}

.bvun35brj {
  cx: 11.006px;
  cy: 19.61px;
  rx: 0.888px;
  ry: 0.449px;
}

.c62dirbjk {
  stop-color: var(--svg-color--439fb2, #439FB2);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cb_xa0byd {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dc9tl2udd {
  stroke: var(--svg-color--9b6433, #9B6433);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M21.629 16.292c-.546-.195-1.304-.333-2.283-.24");
}

.dcp108bys {
  stop-color: var(--svg-color--dda388, #DDA388);
}

.dm88szb0o {
  d: path("M15.758 4.203a3.95 3.95 0 0 0-3.512 2.051a8 8 0 0 1 1.738-.203h.138c1.673 0 3.078 1.368 3.069 3.04a3.02 3.02 0 0 1-.749 1.97a.502.502 0 0 0 .527.813a3.94 3.94 0 0 0 2.67-3.734c.01-2.144-1.737-3.91-3.88-3.937");
}

.dqfxuybrk {
  d: path("M28.395 26.31a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.dvexzpbfd {
  stop-color: var(--svg-color--ca957a, #CA957A);
}

.e1njngbsx {
  d: path("M19.77 19.17c.144.194-.159.43-.503.688s-.6.438-.744.245c-.145-.194.016-.56.36-.817c.345-.258.742-.31.886-.116");
}

.e2nc-mb3x {
  stop-color: var(--svg-color--ffcda4, #FFCDA4);
}

.e6rsc3sik {
  stop-color: var(--svg-color--c6bec8, #C6BEC8);
}

.ep5muxxmd {
  stop-color: var(--svg-color--b46f93, #B46F93);
}

.ex13nsb1n {
  stop-color: var(--svg-color--b97373, #B97373);
}

.f_manrjbp {
  stop-color: var(--svg-color--bc7c81, #BC7C81);
  stop-opacity: 0;
}

.fl5tp5bfj {
  stop-color: var(--svg-color--f8c2a3, #F8C2A3);
}

.fmllmi0vm {
  stop-color: var(--svg-color--bf8265, #BF8265);
}

.fr51zgblk {
  stop-color: var(--svg-color--f7f1f1, #F7F1F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g87cs9b-d {
  stop-color: var(--svg-color--d29992, #D29992);
}

.ggfrtbcgr {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.062 16.205c.545-.194 1.303-.333 2.282-.24");
}

.ghrfdpdai {
  stop-color: var(--svg-color--a89bb4, #A89BB4);
}

.ghz5m_bfp {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M26.856 28.392a.486.486 0 0 0-.486-.486h-5.288v2.04h4.22c.858 0 1.553-.697 1.553-1.555");
}

.gjp7xwfce {
  stop-color: var(--svg-color--cab1a7, #CAB1A7);
}

.gl9izobcn {
  d: path("M26.856 28.392a.486.486 0 0 0-.486-.486h-5.288v2.04h4.22c.858 0 1.553-.697 1.553-1.555");
}

.gp16bnbyv {
  d: path("M7.257 23.61a3.004 3.004 0 1 0 0-6.007a3.004 3.004 0 0 0 0 6.008");
}

.gqs8qobxe {
  stop-color: var(--svg-color--fffbbe, #FFFBBE);
  stop-opacity: 0;
}

.gw5f7-xty {
  stop-color: var(--svg-color--e7d1d9, #E7D1D9);
}

.gyv3q3b9l {
  stop-color: var(--svg-color--dc9f8f, #DC9F8F);
}

.hrncwbz_t {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
  stop-opacity: 0;
}

.hw65_7bjg {
  stop-color: var(--svg-color--feeeec, #FEEEEC);
  stop-opacity: 0;
}

.i2to8tbny {
  stop-color: var(--svg-color--4997c1, #4997C1);
}

.i7yuhdkni {
  width: 3.969px;
  height: 6.227px;
  x: 7.871px;
  y: 23.718px;
  rx: 1px;
}

.i8um3jglr {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
  stop-opacity: 0;
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.ig6laenir {
  d: path("m18.209 10.771l4.03-2.15c2.563 1.849 2.679 5.19 2.563 6.094l-5.094.694a2.476 2.476 0 0 1-1.5-4.638");
}

.ih62nvbvg {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
  stop-opacity: 0;
}

.ika7xqbdn {
  stop-color: var(--svg-color--da9f86, #DA9F86);
  stop-opacity: 0;
}

.itfb13gqc {
  stop-color: var(--svg-color--dfc38e, #DFC38E);
  stop-opacity: 0;
}

.iw08qbcjx {
  stop-color: var(--svg-color--f4c4a2, #F4C4A2);
}

.j04i2bc2h {
  stop-color: var(--svg-color--da9f86, #DA9F86);
}

.j0zneqbkw {
  d: path("M2.004 24.217c0-.275.223-.498.498-.498h8.416v2.093H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.j4e9jliyw {
  stop-color: var(--svg-color--4de2ff, #4DE2FF);
}

.j89jvbcli {
  d: path("M16.04 23.288c.47 0 .89-.26 1.13-.65c.221-.356-.01-.832-.41-.832h-1.442c-.4 0-.64.487-.41.833c.24.4.66.649 1.131.649");
}

.ja2ta5btn {
  stop-color: var(--svg-color--9a84af, #9A84AF);
}

.jezlerabr {
  stop-color: var(--svg-color--d59471, #D59471);
}

.js3ii64ht {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M29.996 24.217a.5.5 0 0 0-.498-.498h-8.416v2.093h7.319c.88 0 1.595-.714 1.595-1.595");
}

.jxs1tbciu {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M2.004 24.217c0-.275.223-.498.498-.498h8.416v2.093H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.k-93cikvm {
  stop-color: var(--svg-color--c9847d, #C9847D);
  stop-opacity: 0;
}

.k21_qub0k {
  fill: var(--svg-color--000, #000);
  d: path("M18.754 20.774a1.16 1.16 0 0 1 1.165-1.165a1.16 1.16 0 0 1 1.164 1.165c0 .194-.046.379-.13.536h-2.06a1.05 1.05 0 0 1-.139-.536m-5.97 0a1.16 1.16 0 0 0-1.165-1.165a1.16 1.16 0 0 0-1.164 1.165c0 .194.046.379.129.536h2.061c.083-.157.139-.342.139-.536");
}

.k8yy-p62i {
  stop-color: var(--svg-color--daa087, #DAA087);
}

.kfuvhdcxh {
  stop-color: var(--svg-color--b57096, #B57096);
}

.ki9dlqbnk {
  stop-color: var(--svg-color--d4c7cd, #D4C7CD);
  stop-opacity: 0;
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lesqr_bdp {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
  stop-opacity: 0;
}

.lfvq_ouae {
  d: path("M19.919 18.74a2.033 2.033 0 0 1 1.96 2.57H17.95a2 2 0 0 1-.074-.536c0-1.118.915-2.033 2.043-2.033");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljzk3pb-v {
  width: 3.969px;
  height: 6.227px;
  fill: var(--svg-color--f7e1ed, #F7E1ED);
  rx: 1px;
}

.lo1zrhbvw {
  stop-color: var(--svg-color--f2d3d7, #F2D3D7);
  stop-opacity: 0;
}

.lwh7ev7yo {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
}

.lxpu7rbhx {
  cx: 11.006px;
  cy: 19.61px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.888px;
  ry: 0.449px;
}

.m63xmacvx {
  stop-color: var(--svg-color--cebfd0, #CEBFD0);
  stop-opacity: 0;
}

.m8axcpb1d {
  d: path("M7.257 22.474a1.867 1.867 0 1 0 0-3.733a1.867 1.867 0 0 0 0 3.733");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjdwlzfcx {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
}

.mm6hvvbia {
  stop-color: var(--svg-color--a797b5, #A797B5);
}

.mmztprbmz {
  stop-color: var(--svg-color--c29d81, #C29D81);
}

.muyp72b3o {
  fill: var(--svg-color--ecc991, #ECC991);
  d: path("M15.758 4.203a3.95 3.95 0 0 0-3.512 2.051a8 8 0 0 1 1.738-.203h.138c1.673 0 3.078 1.368 3.069 3.04a3.02 3.02 0 0 1-.749 1.97a.502.502 0 0 0 .527.813a3.94 3.94 0 0 0 2.67-3.734c.01-2.144-1.737-3.91-3.88-3.937");
}

.n6775zkib {
  stop-color: var(--svg-color--dfa689, #DFA689);
}

.nnvkjjj2j {
  d: path("M21.73 20.506a1.9 1.9 0 0 0-.527-1.054l-.592.65l.267.52z");
}

.no871xb4y {
  stroke: var(--svg-color--935d2c, #935D2C);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M10.011 16.292c.546-.195 1.303-.333 2.283-.24");
}

.nrppcccoy {
  d: path("M15.972 3.492c2.16 0 4.26.37 5.75 1.01c1.25.54 1.72 1.12 1.72 1.36s-.47.82-1.72 1.36c-1.49.64-3.58 1.01-5.75 1.01s-4.26-.36-5.74-1c-1.26-.54-1.72-1.13-1.72-1.37s.47-.82 1.72-1.36c1.48-.64 3.58-1.01 5.74-1.01m0-1.5c-4.95 0-8.96 1.73-8.96 3.87s4.01 3.87 8.97 3.87s8.97-1.73 8.97-3.87s-4.02-3.87-8.98-3.87");
}

.nwjhx0baq {
  d: path("M13.477 20.535c0-.657-.534-1.095-.679-1.227l-.657.635l.405.823z");
}

.o1eq0ncmd {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M28.395 26.31a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.oci36vbzb {
  stop-color: var(--svg-color--c4b7cf, #C4B7CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohd-ppblk {
  stop-color: var(--svg-color--439fb2, #439FB2);
}

.op4ic3bzn {
  stop-color: var(--svg-color--43acc0, #43ACC0);
  stop-opacity: 0;
}

.op74yoooa {
  stop-color: var(--svg-color--e3b792, #E3B792);
}

.opjqgdepo {
  stop-color: var(--svg-color--c88b60, #C88B60);
}

.oqhwimbnp {
  d: path("M16.147 5.096c-1.361-.205-2.548-.002-3.318 1.027c1.843 0 4.363 1.13 3.998 3.55a2.74 2.74 0 0 1-.92 1.678a.456.456 0 0 0 .373.798a3.58 3.58 0 0 0 2.869-3.026c.276-1.928-1.076-3.735-3.002-4.027");
}

.oxnp2k1qi {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
}

.paeqn7zyv {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M3.605 26.31c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.pd07-bcno {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.286 23.758c-.345-.185-.711.21-.494.543l.063-.04z");
}

.piifpilex {
  stop-color: var(--svg-color--e1a08c, #E1A08C);
  stop-opacity: 0;
}

.pkhanubeu {
  stop-color: var(--svg-color--c0817c, #C0817C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qcx_m5b9c {
  stop-color: var(--svg-color--e4c089, #E4C089);
  stop-opacity: 0;
}

.quz6sacji {
  stop-color: var(--svg-color--cfcacf, #CFCACF);
}

.qxhhvqurd {
  stop-color: var(--svg-color--bfa9ad, #BFA9AD);
}

.rhghrobxp {
  stop-color: var(--svg-color--d3c5cf, #D3C5CF);
}

.rpdg7fn4n {
  d: path("M5.145 28.392c0-.269.217-.486.485-.486h5.288v2.04h-4.22a1.554 1.554 0 0 1-1.553-1.555");
}

.rr59_uoqr {
  stop-color: var(--svg-color--4997c1, #4997C1);
  stop-opacity: 0;
}

.rtvwugb3k {
  stop-color: var(--svg-color--ca957a, #CA957A);
  stop-opacity: 0;
}

.s781d-sgv {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
}

.spx4avb5u {
  width: 3.969px;
  height: 6.227px;
  rx: 1px;
}

.sy6kv575h {
  fill: var(--svg-color--cb877e, #CB877E);
  d: path("M15.916 23.611c.47 0 .892-.26 1.132-.649c.22-.357-.01-.833-.41-.833h-1.443c-.4 0-.64.487-.41.833c.24.4.66.649 1.131.649");
}

.t7aapjj0e {
  stop-color: var(--svg-color--33aed4, #33AED4);
}

.t82mlk1zf {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
}

.tzlh-yb0a {
  stop-color: var(--svg-color--704d49, #704D49);
}

.uh_-bgsil {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
  stop-opacity: 0;
}

.uhbk1cbqf {
  stop-color: var(--svg-color--e4c089, #E4C089);
}

.uoj15rbmy {
  stop-color: var(--svg-color--43acc0, #43ACC0);
}

.uqd9t5bdt {
  stop-color: var(--svg-color--d7b5ca, #D7B5CA);
}

.uy2f9acre {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.77 19.17c.144.194-.159.43-.503.688s-.6.438-.744.245c-.145-.194.016-.56.36-.817c.345-.258.742-.31.886-.116");
}

.uycwipbki {
  fill: var(--svg-color--89024e, #89024E);
  d: path("M16.03 24.501a5.9 5.9 0 0 1-2.78-.677c-.275-.148-.57.167-.395.436a3.78 3.78 0 0 0 3.184 1.744a3.8 3.8 0 0 0 3.184-1.744c.165-.26-.12-.575-.396-.436a6.06 6.06 0 0 1-2.797.677");
}

.v_ro-mcce {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
}

.v5z2z1b2h {
  d: path("M11.62 18.74a2.033 2.033 0 0 0-1.96 2.57h3.928c.046-.176.074-.351.074-.536a2.047 2.047 0 0 0-2.043-2.033");
}

.v8imspx_m {
  stop-color: var(--svg-color--dac4cc, #DAC4CC);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vder1tbnm {
  stop-color: var(--svg-color--dfc38e, #DFC38E);
}

.vdhu5sbwc {
  stop-color: var(--svg-color--b67663, #B67663);
}

.vnf59qbgc {
  stop-color: var(--svg-color--db9c78, #DB9C78);
}

.vsxpbmbdw {
  stop-color: var(--svg-color--dcbdc9, #DCBDC9);
}

.w9x82yb4n {
  stop-color: var(--svg-color--935d37, #935D37);
}

.wccw7qb8q {
  d: path("M22.718 7.633a8.2 8.2 0 0 0-4.904-1.654h-3.517c-1.754 0-3.47.582-4.904 1.654c-2.443 1.84-3.763 4.899-3.461 8.032l.83 7.497c.273 2.902 2.197 5.342 4.866 6.174c2.886.896 5.97.896 8.855 0c2.67-.832 4.593-3.272 4.866-6.174l.83-7.497c.302-3.133-1.018-6.192-3.46-8.032");
}

.wjpixgrsk {
  stop-color: var(--svg-color--db9c78, #DB9C78);
  stop-opacity: 0;
}

.wlytqeyju {
  d: path("M3.605 26.31c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.wu77zvqhp {
  stop-color: var(--svg-color--c29d81, #C29D81);
  stop-opacity: 0;
}

.wxdt1jb_s {
  stop-color: var(--svg-color--fffbbe, #FFFBBE);
}

.xdhwqtbkz {
  stop-color: var(--svg-color--ba7660, #BA7660);
}

.xfz3hkpfj {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M5.145 28.392c0-.269.217-.486.485-.486h5.288v2.04h-4.22a1.554 1.554 0 0 1-1.553-1.555");
}

.xujuduamj {
  stop-color: var(--svg-color--c9847d, #C9847D);
}

.y7rsoxb6i {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
}

.y8qlx76pm {
  stop-color: var(--svg-color--b57096, #B57096);
  stop-opacity: 0;
}

.yap3dzbqh {
  stop-color: var(--svg-color--c0817c, #C0817C);
}

.ydp9v2bac {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.629 16.157c-.546-.194-1.304-.333-2.283-.24");
}

.yi34m9bam {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
}

.ylr-iebya {
  stop-color: var(--svg-color--d29992, #D29992);
  stop-opacity: 0;
}

.ymutrvb0h {
  stop-color: var(--svg-color--dda388, #DDA388);
  stop-opacity: 0;
}

.ynn7rr4al {
  stop-color: var(--svg-color--865b4f, #865B4F);
}

.ypa0dqb5t {
  stop-color: var(--svg-color--e3b792, #E3B792);
  stop-opacity: 0;
}

.ypb3pybtz {
  d: path("M24.817 23.61a3.004 3.004 0 1 0 0-6.006a3.004 3.004 0 0 0 0 6.007");
}

.yq-pa7bnx {
  stop-color: var(--svg-color--ffcda4, #FFCDA4);
  stop-opacity: 0;
}

.yse4ebceo {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
  stop-opacity: 0;
}

.ysf50-btc {
  stop-color: var(--svg-color--935d37, #935D37);
  stop-opacity: 0;
}

.z53de0b4i {
  d: path("M29.996 24.217a.5.5 0 0 0-.498-.498h-8.416v2.093h7.319c.88 0 1.595-.714 1.595-1.595");
}

.zbvptbbft {
  fill: var(--svg-color--f0b39b, #F0B39B);
  d: path("M22.718 7.633a8.2 8.2 0 0 0-4.904-1.654h-3.517c-1.754 0-3.47.582-4.904 1.654c-2.443 1.84-3.763 4.899-3.461 8.032l.83 7.497c.273 2.902 2.197 5.342 4.866 6.174c2.886.896 5.97.896 8.855 0c2.67-.832 4.593-3.272 4.866-6.174l.83-7.497c.302-3.133-1.018-6.192-3.46-8.032");
}

</style>
