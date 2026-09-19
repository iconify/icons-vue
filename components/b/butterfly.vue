<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gmkk_abyu"/><path fill="url(#i48kxzB)" class="yr_5zqwcz"/><path fill="url(#i3X8dxe)" class="yr_5zqwcz"/><path fill="url(#i48cFOd)" class="yr_5zqwcz"/><g filter="url(#iiWOZFv)" class="z6cgjeu-u"><path stroke="url(#isGZ3Ee)" class="aa48wepoz"/><path stroke="url(#iwSWhUd)" class="aa48wepoz"/><path stroke="url(#irJtX1b)" class="aa48wepoz"/></g><path fill="url(#iKVb2Fe)" class="ts7isee3e"/><g filter="url(#ip6Ff0b)" class="z6cgjeu-u"><path stroke="url(#i5Ja7Ge)" class="qttgbdu4b"/><path stroke="url(#ittUDfb)" class="qttgbdu4b"/><path stroke="url(#i6lONae)" class="qttgbdu4b"/></g><path fill="url(#iK4JLla)" class="v8dwgmbdy"/><path fill="url(#i2lQbYz)" class="f2cshvb5x"/><path fill="url(#icBiLlk)" class="f2cshvb5x"/><path class="ye9fdcb1e"/><path fill="url(#iTuwvbb)" class="fc7kijb9r"/><path fill="url(#iC0RMtd)" class="fc7kijb9r"/><path fill="url(#i01WyEb)" class="fc7kijb9r"/><g filter="url(#iqKVuMb)" class="z6cgjeu-u"><path stroke="url(#ievhUze)" class="cv273gq9o"/><path stroke="url(#ib3WkEe)" class="cv273gq9o"/><path stroke="url(#iJXONJb)" class="cv273gq9o"/></g><g filter="url(#iizYgJd)" class="z6cgjeu-u"><path stroke="url(#iKK9hGe)" class="arbtnhbqd"/><path stroke="url(#isAgoAV)" class="arbtnhbqd"/><path stroke="url(#i7N30ib)" class="arbtnhbqd"/></g><g filter="url(#ik7SBRd)"><path fill="url(#il7SNEZ)" class="bip_2vgjz"/></g><path fill="url(#ioi3Ygc)" class="e_6-arkcr"/><path fill="url(#io7dLmc)" class="hw0f-jg2z"/><path fill="url(#i4zAn1N)" class="odgiatffy"/><path fill="url(#iUDq1Wc)" class="odgiatffy"/><path class="b7g2jeb8j"/><path fill="url(#i7KX30d)" class="od7f9d_bs"/><path fill="url(#iMuCj7b)" class="od7f9d_bs"/><path fill="url(#i2tCAFc)" class="od7f9d_bs"/><path fill="url(#idIZ6ab)" class="od7f9d_bs"/><path fill="url(#i18MCBe)" class="od7f9d_bs"/><path class="ptuztmnqs"/><path fill="url(#iV5YQue)" class="uty-__uej"/><path fill="url(#icWEQUa)" class="uty-__uej"/><path fill="url(#i2vIWBd)" class="uty-__uej"/><path fill="url(#ifNZnZb)" class="uty-__uej"/><path fill="url(#ijqELHc)" class="uty-__uej"/><path fill="url(#i8W7h7k)" class="uty-__uej"/><g filter="url(#i6UPlFd)" class="z6cgjeu-u"><path stroke="url(#iPem7ed)" class="q35lcfbag"/><path stroke="url(#im0Ohyc)" class="q35lcfbag"/><path stroke="url(#iTfTXYc)" class="q35lcfbag"/></g><g filter="url(#iY4Rkec)" class="z6cgjeu-u"><path stroke="url(#ixXSagm)" class="io4zm5u9g"/><path stroke="url(#iAPQy3d)" class="io4zm5u9g"/><path stroke="url(#ijyo7kd)" class="io4zm5u9g"/></g><g filter="url(#iZU7cOe)" class="bbpfkd-8o"><path stroke="url(#iOZlcCr)" class="cpvuxlbie"/><path stroke="url(#i2kRJOb)" class="cpvuxlbie"/></g><path fill="url(#iIK6ere)" class="r3dwsubgy"/><path fill="url(#i1tyxlp)" class="hyu0njegj"/><path fill="url(#i7s0gwb)" class="cjl9j8_4r"/><path fill="url(#iTtGTMb)" class="cjl9j8_4r"/><g filter="url(#ixJdAae)" class="z6cgjeu-u"><path stroke="url(#i2TLEBb)" class="b9-6r0b0q"/><path stroke="url(#isXJYMG)" class="b9-6r0b0q"/><path stroke="url(#iwe2vrZ)" class="b9-6r0b0q"/></g><g filter="url(#ivf4EDd)" class="z6cgjeu-u"><path stroke="url(#ivqBxOV)" class="muozpswcm"/><path stroke="url(#iUHHi3b)" class="muozpswcm"/><path stroke="url(#i8XnY8c)" class="muozpswcm"/></g><g filter="url(#iVvS6ab)" class="z6cgjeu-u"><path stroke="url(#i4XCeTd)" class="ycehs1bet"/><path stroke="url(#icIRt6c)" class="ycehs1bet"/><path stroke="url(#iRpFh9c)" class="ycehs1bet"/></g><path fill="url(#iEefz2c)" class="h50bm5hgl"/><path fill="url(#i1S2Tjh)" class="e34xntd4q"/><path fill="url(#iDRQwib)" class="hoax0h36w"/><g filter="url(#iUbL2Eb)" class="wgovvk22o"><path stroke="url(#iE1ffac)" class="l-u2hq_sf"/><path stroke="url(#i9LXZdb)" class="l-u2hq_sf"/><path stroke="url(#iEslqId)" class="l-u2hq_sf"/><path stroke="url(#inT9esc)" class="l-u2hq_sf"/><path stroke="url(#i6yuUrd)" class="l-u2hq_sf"/></g><g filter="url(#i6Mfood)" class="wgovvk22o"><path stroke="url(#idp1Hle)" class="dgodk1b9h"/><path stroke="url(#i6i8HNe)" class="dgodk1b9h"/><path stroke="url(#iNwwKId)" class="dgodk1b9h"/></g><path fill="url(#iy3bbmb)" class="yg3-brplc"/><path fill="url(#i7CssEb)" class="yg3-brplc"/><path fill="url(#iT4U5Nc)" class="yg3-brplc"/><path fill="url(#i9EPqXt)" class="yg3-brplc"/><path fill="url(#iaovHIo)" class="yg3-brplc"/><path fill="url(#iBGwn3P)" class="yg3-brplc"/><path class="r9k1bxbpl"/><path fill="url(#ika4sOc)" class="w294e1bkz"/><path fill="url(#i4x5pPc)" class="w294e1bkz"/><path fill="url(#ijTNRmb)" class="w294e1bkz"/><path fill="url(#i9jK9Qd)" class="w294e1bkz"/><path fill="url(#ibAhwsb)" class="w294e1bkz"/><g filter="url(#iz8NVFb)"><path fill="url(#iq3Wanb)" class="tcacr8bjz"/></g><g filter="url(#iuZOYlb)"><path fill="url(#iYCzfrb)" class="zpo6ei1dh"/></g><g filter="url(#i3nEUfd)"><rect class="lo68qsk0f"/><rect fill="url(#iFKWjGd)" class="vawyy6j_h"/></g><g filter="url(#ipfwgHe)"><path stroke="url(#iVtRiCd)" class="ac14vmbbt"/></g><defs><linearGradient id="i48kxzB" x1="22.5" x2="22.5" y1="17.937" y2="19.437" gradientUnits="userSpaceOnUse"><stop class="jvcff0bvl"/><stop offset="1" class="x-64wbc5b"/></linearGradient><linearGradient id="i3X8dxe" x1="22.5" x2="22.5" y1="17.718" y2="18.296" gradientUnits="userSpaceOnUse"><stop class="pz59-2bfa"/><stop offset="1" class="p6ymstb0e"/></linearGradient><linearGradient id="isGZ3Ee" x1="21.837" x2="25.383" y1="26.267" y2="23.689" gradientUnits="userSpaceOnUse"><stop class="fc6sn7bgf"/><stop offset="1" class="i1553i9ba"/></linearGradient><linearGradient id="iwSWhUd" x1="25.25" x2="24.563" y1="20.437" y2="27.874" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="irJtX1b" x1="28.016" x2="25.242" y1="27.014" y2="25.373" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="iKVb2Fe" x1="27" x2="21.563" y1="21.624" y2="27.874" gradientUnits="userSpaceOnUse"><stop class="uey-0m3hm"/><stop offset="1" class="vsz495y6u"/></linearGradient><linearGradient id="i5Ja7Ge" x1="18.469" x2="21.172" y1="21.905" y2="20.874" gradientUnits="userSpaceOnUse"><stop class="fc6sn7bgf"/><stop offset="1" class="i1553i9ba"/></linearGradient><linearGradient id="ittUDfb" x1="20.45" x2="20.183" y1="19.062" y2="21.943" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="i6lONae" x1="21.938" x2="20.092" y1="22.999" y2="20.972" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="iK4JLla" x1="21.063" x2="21.063" y1="18.874" y2="24.499" gradientUnits="userSpaceOnUse"><stop class="rf9tslbwq"/><stop offset="1" class="vwg263b2p"/></linearGradient><linearGradient id="icBiLlk" x1="25.901" x2="25.901" y1="26.916" y2="25.385" gradientUnits="userSpaceOnUse"><stop class="g5purvbfq"/><stop offset="1" class="g91yi498p"/></linearGradient><linearGradient id="iTuwvbb" x1="9.5" x2="9.5" y1="17.937" y2="19.437" gradientUnits="userSpaceOnUse"><stop class="jvcff0bvl"/><stop offset="1" class="x-64wbc5b"/></linearGradient><linearGradient id="iC0RMtd" x1="9.5" x2="9.5" y1="17.718" y2="18.296" gradientUnits="userSpaceOnUse"><stop class="pz59-2bfa"/><stop offset="1" class="p6ymstb0e"/></linearGradient><linearGradient id="ievhUze" x1="10.188" x2="11.969" y1="22.562" y2="20.968" gradientUnits="userSpaceOnUse"><stop class="fc6sn7bgf"/><stop offset="1" class="i1553i9ba"/></linearGradient><linearGradient id="ib3WkEe" x1="11.59" x2="11.59" y1="19.437" y2="20.374" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="iJXONJb" x1="13.844" x2="12.5" y1="22.921" y2="22.312" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="iKK9hGe" x1="5.463" x2="9.009" y1="26.267" y2="23.689" gradientUnits="userSpaceOnUse"><stop class="fc6sn7bgf"/><stop offset="1" class="i1553i9ba"/></linearGradient><linearGradient id="isAgoAV" x1="6.563" x2="7.833" y1="19.593" y2="25.031" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="i7N30ib" x1="11.641" x2="7.553" y1="27.014" y2="25.236" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="il7SNEZ" x1="15.031" x2="11.875" y1="21.721" y2="29.44" gradientUnits="userSpaceOnUse"><stop class="kcj97v0jd"/><stop offset="1" class="mm65jx74a"/></linearGradient><linearGradient id="iUDq1Wc" x1="7.141" x2="7.141" y1="27.046" y2="25.515" gradientUnits="userSpaceOnUse"><stop class="g5purvbfq"/><stop offset="1" class="g91yi498p"/></linearGradient><linearGradient id="i7KX30d" x1="10.203" x2="9.953" y1="6.14" y2="6.452" gradientUnits="userSpaceOnUse"><stop class="usiyegbac"/><stop offset="1" class="ouamk74_t"/></linearGradient><linearGradient id="iMuCj7b" x1="9" x2="9" y1="17.937" y2="17.499" gradientUnits="userSpaceOnUse"><stop class="bqht_4bwh"/><stop offset="1" class="iqwa8bwfh"/></linearGradient><linearGradient id="i2tCAFc" x1="2" x2="2.578" y1="10.093" y2="10.093" gradientUnits="userSpaceOnUse"><stop class="dehqcdbba"/><stop offset="1" class="szf1irgro"/></linearGradient><linearGradient id="iV5YQue" x1="20.859" x2="21.203" y1="7.156" y2="7.593" gradientUnits="userSpaceOnUse"><stop class="klw6o5cas"/><stop offset="1" class="p62fbgb4s"/></linearGradient><linearGradient id="icWEQUa" x1="22.547" x2="22.672" y1="5.359" y2="5.507" gradientUnits="userSpaceOnUse"><stop class="d-7bbabdc"/><stop offset="1" class="nvldbybtz"/></linearGradient><linearGradient id="i2vIWBd" x1="30.047" x2="29.609" y1="5.499" y2="5.499" gradientUnits="userSpaceOnUse"><stop class="y1znsvb3h"/><stop offset="1" class="o9krjpbkd"/></linearGradient><linearGradient id="ijqELHc" x1="22.995" x2="22.995" y1="17.937" y2="17.499" gradientUnits="userSpaceOnUse"><stop class="bqht_4bwh"/><stop offset="1" class="iqwa8bwfh"/></linearGradient><linearGradient id="iPem7ed" x1="8.797" x2="11.263" y1="12.617" y2="7.856" gradientUnits="userSpaceOnUse"><stop class="sj2ye9dld"/><stop offset="1" class="vvtc93i_h"/></linearGradient><linearGradient id="im0Ohyc" x1="10.764" x2="8.95" y1="7.73" y2="10.306" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="iTfTXYc" x1="14.606" x2="12.493" y1="15.168" y2="13.144" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="ixXSagm" x1="7.125" x2="10.688" y1="14.249" y2="9.323" gradientUnits="userSpaceOnUse"><stop class="sj2ye9dld"/><stop offset="1" class="vvtc93i_h"/></linearGradient><linearGradient id="iAPQy3d" x1="7.96" x2="6.625" y1="12.58" y2="14.767" gradientUnits="userSpaceOnUse"><stop class="x0re1bc4o"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="ijyo7kd" x1="9.95" x2="6.825" y1="16.21" y2="14.947" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="iOZlcCr" x1="10.969" x2="11.158" y1="17.109" y2="15.498" gradientUnits="userSpaceOnUse"><stop offset=".019" class="sj2ye9dld"/><stop offset="1" class="vvtc93i_h"/></linearGradient><linearGradient id="i2kRJOb" x1="13.226" x2="13.42" y1="15.572" y2="16.678" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="iIK6ere" x1="5.375" x2="11.25" y1="4.374" y2="13.374" gradientUnits="userSpaceOnUse"><stop class="wzhsi5bwb"/><stop offset="1" class="a97sycc6f"/></linearGradient><linearGradient id="i1tyxlp" x1="8.688" x2="4.875" y1="16.937" y2="11.624" gradientUnits="userSpaceOnUse"><stop class="vc8tpuzjt"/><stop offset="1" class="jsg-90rwe"/></linearGradient><linearGradient id="i7s0gwb" x1="12.125" x2="12.125" y1="14.124" y2="17.624" gradientUnits="userSpaceOnUse"><stop class="p7kn0qb2g"/><stop offset="1" class="x4-3bvvcr"/></linearGradient><linearGradient id="iTtGTMb" x1="14.609" x2="12.793" y1="16.937" y2="16.937" gradientUnits="userSpaceOnUse"><stop class="n2q6kbbmh"/><stop offset="1" class="o46auebsn"/></linearGradient><linearGradient id="i2TLEBb" x1="20.994" x2="21.916" y1="9.605" y2="10.558" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="isXJYMG" x1="26.563" x2="26.563" y1="5.062" y2="6.843" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="iwe2vrZ" x1="24.898" x2="22.768" y1="11.603" y2="8.074" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="ivqBxOV" x1="25.219" x2="24.642" y1="11.812" y2="16.392" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="iUHHi3b" x1="27.125" x2="25.194" y1="16.852" y2="14.411" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="i8XnY8c" x1="24.031" x2="25.634" y1="16.852" y2="14.743" gradientUnits="userSpaceOnUse"><stop class="sj2ye9dld"/><stop offset="1" class="vvtc93i_h"/></linearGradient><linearGradient id="i4XCeTd" x1="20.91" x2="21.226" y1="14.887" y2="16.345" gradientUnits="userSpaceOnUse"><stop class="ybs2dkb-y"/><stop offset="1" class="n1-77fm8x"/></linearGradient><linearGradient id="icIRt6c" x1="21.331" x2="21.377" y1="17.262" y2="16.04" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="iRpFh9c" x1="21.844" x2="21.399" y1="16.741" y2="15.677" gradientUnits="userSpaceOnUse"><stop class="bs8i6j34h"/><stop offset="1" class="pg8-7jete"/></linearGradient><linearGradient id="iEefz2c" x1="22.5" x2="22.5" y1="1.86" y2="20.672" gradientUnits="userSpaceOnUse"><stop class="i46bc3-mx"/><stop offset="1" class="p475_abra"/></linearGradient><linearGradient id="i1S2Tjh" x1="24.85" x2="24.85" y1="3.367" y2="20.121" gradientUnits="userSpaceOnUse"><stop class="i46bc3-mx"/><stop offset="1" class="p475_abra"/></linearGradient><linearGradient id="iDRQwib" x1="19.436" x2="19.436" y1="3.367" y2="20.121" gradientUnits="userSpaceOnUse"><stop class="i46bc3-mx"/><stop offset="1" class="p475_abra"/></linearGradient><linearGradient id="iE1ffac" x1="14.172" x2="15.266" y1="5.984" y2="5.71" gradientUnits="userSpaceOnUse"><stop class="eq323ibmn"/><stop offset="1" class="za_7ikbys"/></linearGradient><linearGradient id="inT9esc" x1="15.031" x2="14.977" y1="7.304" y2="6.968" gradientUnits="userSpaceOnUse"><stop class="eujjssbuz"/><stop offset="1" class="giqp0jb3k"/></linearGradient><linearGradient id="idp1Hle" x1="17.844" x2="16.594" y1="5.921" y2="5.64" gradientUnits="userSpaceOnUse"><stop class="eq323ibmn"/><stop offset="1" class="za_7ikbys"/></linearGradient><linearGradient id="ika4sOc" x1="14.094" x2="15.656" y1="17.843" y2="17.843" gradientUnits="userSpaceOnUse"><stop class="zcpplh2dp"/><stop offset="1" class="h-wzjy81u"/></linearGradient><linearGradient id="i4x5pPc" x1="17.781" x2="17.125" y1="17.843" y2="17.843" gradientUnits="userSpaceOnUse"><stop class="zcpplh2dp"/><stop offset="1" class="h-wzjy81u"/></linearGradient><linearGradient id="iq3Wanb" x1="7.539" x2="6.758" y1="24.499" y2="25.085" gradientUnits="userSpaceOnUse"><stop offset=".325" class="ath_mu27p"/><stop offset="1" class="mm65jx74a"/></linearGradient><linearGradient id="iYCzfrb" x1="26.322" x2="25.541" y1="24.424" y2="25.01" gradientUnits="userSpaceOnUse"><stop offset=".325" class="ath_mu27p"/><stop offset="1" class="mm65jx74a"/></linearGradient><linearGradient id="iFKWjGd" x1="16.56" x2="16.56" y1="11.253" y2="13.999" gradientUnits="userSpaceOnUse"><stop class="dfh0_nbbm"/><stop offset="1" class="fmgyenbqm"/></linearGradient><linearGradient id="iVtRiCd" x1="18.781" x2="15.777" y1="3.226" y2="5.562" gradientUnits="userSpaceOnUse"><stop class="ylkkdab6e"/><stop offset="1" class="tin399b1v"/></linearGradient><radialGradient id="i48cFOd" cx="0" cy="0" r="1" gradientTransform="rotate(-35.712 55.056 -7.212)scale(17.9349 11.2963)" gradientUnits="userSpaceOnUse"><stop offset=".95" class="jq7rujmtg"/><stop offset="1" class="yf1m0ql_t"/></radialGradient><radialGradient id="i2lQbYz" cx="0" cy="0" r="1" gradientTransform="rotate(94.042 .986 24.516)scale(1.56076)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="sa-8-7bmm"/><stop offset="1" class="vo2t3-b1d"/></radialGradient><radialGradient id="i01WyEb" cx="0" cy="0" r="1" gradientTransform="rotate(-156.45 11.03 12.162)scale(15.4083 9.70488)" gradientUnits="userSpaceOnUse"><stop offset=".95" class="jq7rujmtg"/><stop offset="1" class="yf1m0ql_t"/></radialGradient><radialGradient id="ioi3Ygc" cx="0" cy="0" r="1" gradientTransform="matrix(2 -8.25 10.06662 2.4404 7.375 28.874)" gradientUnits="userSpaceOnUse"><stop class="hqjxbmbiw"/><stop offset="1" class="rrzs4ojbr"/></radialGradient><radialGradient id="io7dLmc" cx="0" cy="0" r="1" gradientTransform="rotate(-73.386 21.64 4.313)scale(4.13941 6.04406)" gradientUnits="userSpaceOnUse"><stop class="hqjxbmbiw"/><stop offset="1" class="rrzs4ojbr"/></radialGradient><radialGradient id="i4zAn1N" cx="0" cy="0" r="1" gradientTransform="rotate(94.042 -8.455 15.84)scale(1.56076)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="sa-8-7bmm"/><stop offset="1" class="vo2t3-b1d"/></radialGradient><radialGradient id="idIZ6ab" cx="0" cy="0" r="1" gradientTransform="matrix(-14.20301 -17.04698 8.82865 -7.35576 16.75 19.624)" gradientUnits="userSpaceOnUse"><stop offset=".961" class="szf1irgro"/><stop offset="1" class="dehqcdbba"/></radialGradient><radialGradient id="i18MCBe" cx="0" cy="0" r="1" gradientTransform="matrix(-14.0938 14.4218 -16.95622 -16.57059 16.875 2.28)" gradientUnits="userSpaceOnUse"><stop offset=".936" class="szf1irgro"/><stop offset="1" class="dehqcdbba"/></radialGradient><radialGradient id="ifNZnZb" cx="0" cy="0" r="1" gradientTransform="matrix(19.5 -11.06251 9.26468 16.33095 10.094 13.53)" gradientUnits="userSpaceOnUse"><stop offset=".959" class="o9krjpbkd"/><stop offset=".996" class="y1znsvb3h"/></radialGradient><radialGradient id="i8W7h7k" cx="0" cy="0" r="1" gradientTransform="matrix(14.09372 14.42186 -16.9563 16.5705 15.12 2.28)" gradientUnits="userSpaceOnUse"><stop offset=".936" class="szf1irgro"/><stop offset="1" class="dehqcdbba"/></radialGradient><radialGradient id="i9LXZdb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6292 -1.00531 1.99062 5.2061 12.699 6.16)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="lkio1obwo"/><stop offset=".943" class="xuz__qh7e"/></radialGradient><radialGradient id="iEslqId" cx="0" cy="0" r="1" gradientTransform="rotate(45.982 3.732 15.81)scale(.96689 2.13483)" gradientUnits="userSpaceOnUse"><stop class="gky138tzz"/><stop offset="1" class="oqwqoyuww"/></radialGradient><radialGradient id="i6yuUrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -1.75 .23838 -.02554 15.219 7.343)" gradientUnits="userSpaceOnUse"><stop class="kbkcusb7g"/><stop offset="1" class="y-3wbrt1c"/></radialGradient><radialGradient id="i6i8HNe" cx="0" cy="0" r="1" gradientTransform="rotate(134.018 9.292 5.205)scale(.96689 2.13483)" gradientUnits="userSpaceOnUse"><stop class="gky138tzz"/><stop offset="1" class="oqwqoyuww"/></radialGradient><radialGradient id="iNwwKId" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 -2.35157 .32032 .05534 17.078 7.468)" gradientUnits="userSpaceOnUse"><stop class="kbkcusb7g"/><stop offset="1" class="y-3wbrt1c"/></radialGradient><radialGradient id="iy3bbmb" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 -2.875 3.65561 .99337 16 10.187)" gradientUnits="userSpaceOnUse"><stop class="mn95ptqaa"/><stop offset="1" class="mhuc7zb2v"/></radialGradient><radialGradient id="i7CssEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.59375 -2.26005 0 16 8.343)" gradientUnits="userSpaceOnUse"><stop offset=".762" class="twffujbbe"/><stop offset="1" class="vosrojbhw"/></radialGradient><radialGradient id="iT4U5Nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.65956 1.22201 0 16 10.73)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="vosrojbhw"/><stop offset="1" class="twffujbbe"/></radialGradient><radialGradient id="i9EPqXt" cx="0" cy="0" r="1" gradientTransform="rotate(145.739 7.428 6.849)scale(1.30448 1.24434)" gradientUnits="userSpaceOnUse"><stop class="gf9129bao"/><stop offset="1" class="qwcj72rra"/></radialGradient><radialGradient id="iaovHIo" cx="0" cy="0" r="1" gradientTransform="matrix(1.01562 -1.5625 .84029 .54619 14 8.265)" gradientUnits="userSpaceOnUse"><stop class="gf9129bao"/><stop offset="1" class="qwcj72rra"/></radialGradient><radialGradient id="iBGwn3P" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.21875 -1.32031 0 16 6.656)" gradientUnits="userSpaceOnUse"><stop class="bwxfkrbsv"/><stop offset="1" class="txd1yopzs"/></radialGradient><radialGradient id="ijTNRmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.8594 8.33978 0 15.995 26.624)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="twffujbbe"/><stop offset="1" class="vosrojbhw"/></radialGradient><radialGradient id="i9jK9Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.22656 0 0 3.57813 15.914 23.5)" gradientUnits="userSpaceOnUse"><stop class="xggo5ccjt"/><stop offset="1" class="lcn2b03eg"/></radialGradient><radialGradient id="ibAhwsb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07251 0 0 4.1875 14.49 20.859)" gradientUnits="userSpaceOnUse"><stop class="xlg87rhfl"/><stop offset=".476" class="xllmtkvgb"/></radialGradient><filter id="iiWOZFv" width="10.266" height="10.27" x="19.074" y="18.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="ip6Ff0b" width="6.731" height="5.769" x="17.085" y="18.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="iqKVuMb" width="6.731" height="5.769" x="8.224" y="18.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="iizYgJd" width="10.266" height="10.27" x="2.7" y="18.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="ik7SBRd" width="5.842" height="8.038" x="9.44" y="21.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".25"/></filter><filter id="i6UPlFd" width="12.42" height="12.455" x="3.52" y="4.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="iY4Rkec" width="7.702" height="7.324" x="3.526" y="10.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="iZU7cOe" width="5.739" height="2.944" x="9.923" y="14.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".1"/></filter><filter id="ixJdAae" width="12.42" height="12.455" x="16.29" y="4.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="ivf4EDd" width="7.714" height="7.336" x="20.996" y="10.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="iVvS6ab" width="6.139" height="3.344" x="16.369" y="14.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".15"/></filter><filter id="iUbL2Eb" width="3.515" height="8.548" x="12.199" y="1.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.392157 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6242"/></filter><filter id="i6Mfood" width="3.515" height="8.548" x="16.386" y="1.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.392157 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6242"/></filter><filter id="iz8NVFb" width="2.142" height="2.514" x="6.121" y="23.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".175"/></filter><filter id="iuZOYlb" width="2.142" height="2.514" x="24.904" y="23.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".175"/></filter><filter id="i3nEUfd" width="2.652" height="13.188" x="15.234" y="10.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".5"/></filter><filter id="ipfwgHe" width="2.75" height="5.016" x="16.781" y="2.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6242" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:butterfly" /></template>
<style>
.a97sycc6f {
  stop-color: var(--svg-color--df604a, #DF604A);
}

.aa48wepoz {
  d: path("M20.063 24.31a1.505 1.505 0 0 0-.313 1.663v.047l.054.055a4.72 4.72 0 0 0 4.33 2.612a4.725 4.725 0 0 0 4.656-4.75a4.75 4.75 0 0 0-2.66-4.264a1.48 1.48 0 0 0-1.717.287z");
}

.ac14vmbbt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.156 2.632c-.61.505-1.862 2.066-2 4.266");
}

.arbtnhbqd {
  d: path("m12.263 26.022l.02-.042l.007-.014v-.003a1.505 1.505 0 0 0-.313-1.663l-4.35-4.34l-.177.177l.177-.177a1.48 1.48 0 0 0-1.718-.287a4.75 4.75 0 0 0-2.659 4.264a4.725 4.725 0 0 0 4.656 4.75a4.72 4.72 0 0 0 4.348-2.65l.006-.01z");
}

.ath_mu27p {
  stop-color: var(--svg-color--604977, #604977);
}

.b7g2jeb8j {
  fill: var(--svg-color--5b3e78, #5B3E78);
  d: path("m16 10.937l-9.87-8.4c-.44-.37-1.01-.6-1.63-.6a2.5 2.5 0 0 0-2.5 2.5v9.75c0 2.07 1.68 3.75 3.75 3.75H16z");
}

.b9-6r0b0q {
  d: path("m16.932 12.7l-.092.075v3.208l.375-.217l9.846-5.685a2.2 2.2 0 0 0 1.099-1.909V5.99c0-.986-1.148-1.54-1.913-.912z");
}

.bbpfkd-8o {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
}

.bip_2vgjz {
  d: path("M14.773 21.956a.125.125 0 0 0-.23-.095zm-1.928 4.327l-.115-.047v.001zm1.697-4.422l-1.812 4.375l.23.095l1.813-4.375zm-1.813 4.376c-.314.789-1.15 1.711-2.789 2.352l.091.233c1.687-.66 2.585-1.624 2.93-2.492z");
}

.bqht_4bwh {
  stop-color: var(--svg-color--542976, #542976);
}

.bs8i6j34h {
  stop-color: var(--svg-color--392340, #392340);
}

.bwxfkrbsv {
  stop-color: var(--svg-color--3b2a4b, #3B2A4B);
}

.cjl9j8_4r {
  d: path("m12.46 15.187l2.77 1.6v.15h-4.41c-.41 0-.62-.5-.33-.79l.8-.8c.31-.31.79-.37 1.17-.16");
}

.cpvuxlbie {
  d: path("m12.583 15.07l-.003-.002a1.12 1.12 0 0 0-1.328.183l-.744.744c-.398.398-.109 1.077.448 1.077h4.305v-.455l-.1-.058z");
}

.cv273gq9o {
  d: path("M13.39 23.325v-.002l.9-2.149c.402-.938-.305-1.987-1.33-1.987H9.64c-.77 0-1.157.928-.606 1.468l2.95 2.948a.865.865 0 0 0 1.406-.278Z");
}

.d-7bbabdc {
  stop-color: var(--svg-color--645d6c, #645D6C);
}

.dehqcdbba {
  stop-color: var(--svg-color--48345e, #48345E);
}

.dfh0_nbbm {
  stop-color: var(--svg-color--866d9e, #866D9E);
}

.dgodk1b9h {
  d: path("M19.301 2.437c-2.21 1.812-2.537 4.422-2.381 7.448");
}

.e_6-arkcr {
  d: path("M6.02 19.897a4.5 4.5 0 0 0-2.52 4.04c0 2.47 1.95 4.46 4.41 4.5a4.47 4.47 0 0 0 4.12-2.51l.01-.02c0-.01.01-.01.01-.02c.22-.47.12-1.04-.25-1.41l-4.35-4.34c-.38-.38-.95-.48-1.43-.24");
}

.e34xntd4q {
  d: path("m26.78 11.147l-4.76 2.75a.62.62 0 0 0-.13.98l1.37 1.37c.44.44 1.04.69 1.66.69c1.7 0 3.08-1.38 3.08-3.08v-2c0-.63-.68-1.03-1.22-.71");
}

.eq323ibmn {
  stop-color: var(--svg-color--512f71, #512F71);
}

.eujjssbuz {
  stop-color: var(--svg-color--3c2b4c, #3C2B4C);
}

.f2cshvb5x {
  d: path("M25.4 26.817a1.64 1.64 0 1 0 0-3.28a1.64 1.64 0 0 0 0 3.28");
}

.fc6sn7bgf {
  stop-color: var(--svg-color--594d63, #594D63);
}

.fc7kijb9r {
  d: path("M13.38 26.597c.11-.23.21-.46.29-.7l3.33-7.96H8c-3.31 0-6 2.69-6 6s2.69 6 6 6c2.36 0 4.4-1.36 5.38-3.34");
}

.fmgyenbqm {
  stop-color: var(--svg-color--6a577d, #6A577D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5purvbfq {
  stop-color: var(--svg-color--4f246b, #4F246B);
}

.g91yi498p {
  stop-color: var(--svg-color--4f246b, #4F246B);
  stop-opacity: 0;
}

.gf9129bao {
  stop-color: var(--svg-color--695a7b, #695A7B);
}

.giqp0jb3k {
  stop-color: var(--svg-color--3c2b4c, #3C2B4C);
  stop-opacity: 0;
}

.gky138tzz {
  stop-color: var(--svg-color--503a66, #503A66);
}

.gmkk_abyu {
  fill: var(--svg-color--462b5d, #462B5D);
  d: path("M18.62 26.597c-.11-.23-.21-.46-.29-.7L15 17.937h9c3.31 0 6 2.69 6 6s-2.69 6-6 6c-2.36 0-4.4-1.36-5.38-3.34");
}

.h-wzjy81u {
  stop-color: var(--svg-color--2c1638, #2C1638);
  stop-opacity: 0;
}

.h50bm5hgl {
  d: path("M28 8.137v-2.22c0-.79-.92-1.23-1.53-.73L17 12.937v2.7l10.01-5.78c.61-.35.99-1.01.99-1.72");
}

.hoax0h36w {
  d: path("m19.77 15.187l-2.77 1.6v.15h4.41c.41 0 .62-.5.33-.79l-.8-.8a.984.984 0 0 0-1.17-.16");
}

.hqjxbmbiw {
  stop-color: var(--svg-color--ee614f, #EE614F);
}

.hw0f-jg2z {
  d: path("M12.96 19.437H9.64c-.55 0-.82.66-.43 1.04l2.95 2.95c.31.31.83.2 1-.2l.9-2.15c.33-.77-.25-1.64-1.1-1.64");
}

.hyu0njegj {
  d: path("m5.45 11.147l4.76 2.75c.36.21.42.69.13.98l-1.37 1.37c-.44.44-1.04.69-1.66.69c-1.7 0-3.08-1.38-3.08-3.08v-2c0-.63.68-1.03 1.22-.71");
}

.i1553i9ba {
  stop-color: var(--svg-color--594d63, #594D63);
  stop-opacity: 0;
}

.i46bc3-mx {
  stop-color: var(--svg-color--ff8c00, #FF8C00);
}

.io4zm5u9g {
  d: path("m10.25 13.684l-.002-.001l-4.613-2.665c-.696-.412-1.559.107-1.559.904v1.939a3.237 3.237 0 0 0 3.236 3.235c.668 0 1.313-.269 1.786-.742l1.328-1.328a.85.85 0 0 0-.177-1.342Z");
}

.iqwa8bwfh {
  stop-color: var(--svg-color--542976, #542976);
  stop-opacity: 0;
}

.jq7rujmtg {
  stop-color: var(--svg-color--78747c, #78747C);
  stop-opacity: 0;
}

.jsg-90rwe {
  stop-color: var(--svg-color--e55043, #E55043);
}

.jvcff0bvl {
  stop-color: var(--svg-color--4e3d5f, #4E3D5F);
}

.kbkcusb7g {
  stop-color: var(--svg-color--604d72, #604D72);
}

.kcj97v0jd {
  stop-color: var(--svg-color--543f69, #543F69);
}

.klw6o5cas {
  stop-color: var(--svg-color--513f63, #513F63);
}

.l-u2hq_sf {
  d: path("M12.699 2.437c2.21 1.812 2.537 4.422 2.381 7.448");
}

.lcn2b03eg {
  stop-color: var(--svg-color--552574, #552574);
  stop-opacity: 0;
}

.lkio1obwo {
  stop-color: var(--svg-color--6d5d7e, #6D5D7E);
  stop-opacity: 0;
}

.lo68qsk0f {
  width: 0.652px;
  height: 11.188px;
  x: 16.234px;
  y: 11.253px;
  fill: var(--svg-color--6c5a7f, #6C5A7F);
  rx: 0.326px;
}

.mhuc7zb2v {
  stop-color: var(--svg-color--4e3d5e, #4E3D5E);
}

.mm65jx74a {
  stop-color: var(--svg-color--543f69, #543F69);
  stop-opacity: 0;
}

.mn95ptqaa {
  stop-color: var(--svg-color--542878, #542878);
}

.muozpswcm {
  d: path("M21.976 13.683h-.001a.853.853 0 0 0-.177 1.345l1.33 1.33a2.54 2.54 0 0 0 1.79.744a3.243 3.243 0 0 0 3.242-3.242v-1.942c0-.798-.864-1.318-1.561-.906z");
}

.n1-77fm8x {
  stop-color: var(--svg-color--552575, #552575);
  stop-opacity: 0;
}

.n2q6kbbmh {
  stop-color: var(--svg-color--cc4736, #CC4736);
}

.nvldbybtz {
  stop-color: var(--svg-color--645d6c, #645D6C);
  stop-opacity: 0;
}

.o46auebsn {
  stop-color: var(--svg-color--cc4736, #CC4736);
  stop-opacity: 0;
}

.o9krjpbkd {
  stop-color: var(--svg-color--6f5f7f, #6F5F7F);
  stop-opacity: 0;
}

.od7f9d_bs {
  d: path("m16 10.937l-9.87-8.4c-.44-.37-1.01-.6-1.63-.6a2.5 2.5 0 0 0-2.5 2.5v9.75c0 2.07 1.68 3.75 3.75 3.75H16z");
}

.odgiatffy {
  d: path("M6.64 26.947a1.64 1.64 0 1 0 0-3.28a1.64 1.64 0 0 0 0 3.28");
}

.oqwqoyuww {
  stop-color: var(--svg-color--503a66, #503A66);
  stop-opacity: 0;
}

.ouamk74_t {
  stop-color: var(--svg-color--665677, #665677);
  stop-opacity: 0;
}

.p475_abra {
  stop-color: var(--svg-color--ff2c00, #FF2C00);
}

.p62fbgb4s {
  stop-color: var(--svg-color--513f63, #513F63);
  stop-opacity: 0;
}

.p6ymstb0e {
  stop-color: var(--svg-color--160923, #160923);
  stop-opacity: 0;
}

.p7kn0qb2g {
  stop-color: var(--svg-color--de5c4b, #DE5C4B);
}

.pg8-7jete {
  stop-color: var(--svg-color--392340, #392340);
  stop-opacity: 0;
}

.ptuztmnqs {
  fill: var(--svg-color--5b3e79, #5B3E79);
  d: path("m15.995 10.937l9.87-8.4c.44-.37 1.01-.6 1.63-.6a2.5 2.5 0 0 1 2.5 2.5v9.75c0 2.07-1.68 3.75-3.75 3.75h-10.25z");
}

.pz59-2bfa {
  stop-color: var(--svg-color--160923, #160923);
}

.q35lcfbag {
  d: path("M15.39 12.775v3.208l-.375-.217l-9.846-5.685A2.2 2.2 0 0 1 4.07 8.172V5.99c0-.986 1.148-1.54 1.913-.912m9.407 7.698L5.983 5.077m9.407 7.698l-.092-.075m.092.075l-.092-.075M5.983 5.077l9.315 7.623M5.983 5.077l9.315 7.623");
}

.qttgbdu4b {
  d: path("M18.65 23.323v.002a.865.865 0 0 0 1.407.279l2.949-2.95c.551-.539.164-1.467-.606-1.467h-3.32c-1.025 0-1.732 1.049-1.33 1.987z");
}

.qwcj72rra {
  stop-color: var(--svg-color--695a7b, #695A7B);
  stop-opacity: 0;
}

.r3dwsubgy {
  d: path("M4.23 8.137v-2.22c0-.79.92-1.23 1.53-.73l9.47 7.75v2.7L5.22 9.857c-.61-.35-.99-1.01-.99-1.72");
}

.r9k1bxbpl {
  fill: var(--svg-color--4c2f69, #4C2F69);
  d: path("M16.05 23.937h-.11c-.8 0-1.45-.65-1.45-1.45v-10.61c0-.8.65-1.45 1.45-1.45h.11c.8 0 1.45.65 1.45 1.45v10.61c0 .8-.65 1.45-1.45 1.45");
}

.rf9tslbwq {
  stop-color: var(--svg-color--e2474c, #E2474C);
}

.rrzs4ojbr {
  stop-color: var(--svg-color--e7444b, #E7444B);
}

.sa-8-7bmm {
  stop-color: var(--svg-color--4f3964, #4F3964);
}

.sj2ye9dld {
  stop-color: var(--svg-color--657, #657);
}

.szf1irgro {
  stop-color: var(--svg-color--48345e, #48345E);
  stop-opacity: 0;
}

.tcacr8bjz {
  d: path("M7.634 25.721a.125.125 0 0 0 .247.04zm-1.152-1.417c.258-.012.596.053.842.259c.237.199.41.548.31 1.158l.247.04c.111-.678-.079-1.123-.396-1.39c-.31-.259-.717-.33-1.014-.317z");
}

.tin399b1v {
  stop-color: var(--svg-color--5d3e7b, #5D3E7B);
  stop-opacity: 0;
}

.ts7isee3e {
  d: path("M26.02 19.897c1.49.73 2.52 2.27 2.52 4.04c0 2.47-1.95 4.46-4.41 4.5a4.47 4.47 0 0 1-4.12-2.51l-.01-.01c0-.01-.01-.01-.01-.02c-.22-.47-.12-1.04.25-1.41l4.35-4.35c.38-.38.95-.48 1.43-.24");
}

.twffujbbe {
  stop-color: var(--svg-color--32194a, #32194A);
  stop-opacity: 0;
}

.txd1yopzs {
  stop-color: var(--svg-color--3b2a4b, #3B2A4B);
  stop-opacity: 0;
}

.uey-0m3hm {
  stop-color: var(--svg-color--e3454c, #E3454C);
}

.usiyegbac {
  stop-color: var(--svg-color--665677, #665677);
}

.uty-__uej {
  d: path("m15.995 10.937l9.87-8.4c.44-.37 1.01-.6 1.63-.6a2.5 2.5 0 0 1 2.5 2.5v9.75c0 2.07-1.68 3.75-3.75 3.75h-10.25z");
}

.v8dwgmbdy {
  d: path("M19.08 19.437h3.32c.55 0 .82.66.43 1.04l-2.95 2.95c-.31.31-.83.2-1-.2l-.9-2.15c-.33-.77.25-1.64 1.1-1.64");
}

.vawyy6j_h {
  width: 0.652px;
  height: 11.188px;
  x: 16.234px;
  y: 11.253px;
  rx: 0.326px;
}

.vc8tpuzjt {
  stop-color: var(--svg-color--e46749, #E46749);
}

.vo2t3-b1d {
  stop-color: var(--svg-color--372337, #372337);
}

.vosrojbhw {
  stop-color: var(--svg-color--32194a, #32194A);
}

.vsz495y6u {
  stop-color: var(--svg-color--ea5f45, #EA5F45);
}

.vvtc93i_h {
  stop-color: var(--svg-color--63506f, #63506F);
  stop-opacity: 0;
}

.vwg263b2p {
  stop-color: var(--svg-color--e7504d, #E7504D);
}

.w294e1bkz {
  d: path("M16.05 23.937h-.11c-.8 0-1.45-.65-1.45-1.45v-10.61c0-.8.65-1.45 1.45-1.45h.11c.8 0 1.45.65 1.45 1.45v10.61c0 .8-.65 1.45-1.45 1.45");
}

.wgovvk22o {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}

.wzhsi5bwb {
  stop-color: var(--svg-color--e74747, #E74747);
}

.x-64wbc5b {
  stop-color: var(--svg-color--4e3d5f, #4E3D5F);
  stop-opacity: 0;
}

.x0re1bc4o {
  stop-color: var(--svg-color--4f246d, #4F246D);
}

.x4-3bvvcr {
  stop-color: var(--svg-color--df624a, #DF624A);
}

.xggo5ccjt {
  stop-color: var(--svg-color--552574, #552574);
}

.xlg87rhfl {
  stop-color: var(--svg-color--511f31, #511F31);
}

.xllmtkvgb {
  stop-color: var(--svg-color--511f31, #511F31);
  stop-opacity: 0;
}

.xuz__qh7e {
  stop-color: var(--svg-color--6d5d7e, #6D5D7E);
}

.y-3wbrt1c {
  stop-color: var(--svg-color--604d72, #604D72);
  stop-opacity: 0;
}

.y1znsvb3h {
  stop-color: var(--svg-color--6f5f7f, #6F5F7F);
}

.ybs2dkb-y {
  stop-color: var(--svg-color--552575, #552575);
}

.ycehs1bet {
  d: path("m19.626 15.024l-.004.003l-2.578 1.489l-.125.072v.534h4.355c.6 0 .913-.732.483-1.162l-.744-.745a1.17 1.17 0 0 0-1.387-.19Z");
}

.ye9fdcb1e {
  fill: var(--svg-color--462b5d, #462B5D);
  d: path("M13.38 26.597c.11-.23.21-.46.29-.7l3.33-7.96H8c-3.31 0-6 2.69-6 6s2.69 6 6 6c2.36 0 4.4-1.36 5.38-3.34");
}

.yf1m0ql_t {
  stop-color: var(--svg-color--78747c, #78747C);
}

.yg3-brplc {
  d: path("M16 10.937a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.ylkkdab6e {
  stop-color: var(--svg-color--5d3e7b, #5D3E7B);
}

.yr_5zqwcz {
  d: path("M18.62 26.597c-.11-.23-.21-.46-.29-.7L15 17.937h9c3.31 0 6 2.69 6 6s-2.69 6-6 6c-2.36 0-4.4-1.36-5.38-3.34");
}

.z6cgjeu-u {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.za_7ikbys {
  stop-color: var(--svg-color--4e415a, #4E415A);
}

.zcpplh2dp {
  stop-color: var(--svg-color--2c1638, #2C1638);
}

.zpo6ei1dh {
  d: path("M26.417 25.646a.125.125 0 0 0 .247.04zm-1.152-1.417c.257-.012.596.052.842.259c.237.199.41.548.31 1.158l.247.04c.111-.679-.079-1.123-.397-1.39c-.308-.259-.716-.331-1.014-.317z");
}

</style>
