<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwUShWr)" class="m_f6c8b6a"/><path fill="url(#iFRmxDe)" class="v3usx3bwv"/><path fill="url(#iKi2X3b)" class="v3usx3bwv"/><g filter="url(#iYFV5Tb)"><path fill="url(#ib4Vkxb)" class="bbq0uybhr"/></g><path class="t5v_l2big"/><path fill="url(#iF8aDEZ)" class="te97h0xad"/><path fill="url(#igAYhqk)" class="vj6k8zb9a"/><path fill="url(#i994Zwe)" class="vj6k8zb9a"/><path fill="url(#ip4y95c)" class="vai20f3-l"/><path fill="url(#it8beRb)" class="vai20f3-l"/><g filter="url(#iIcKDZb)"><path fill="url(#iDvycOb)" class="h0k1czboq"/><path fill="url(#inhRu3C)" class="h0k1czboq"/><path fill="url(#iP61Dqb)" class="h0k1czboq"/></g><path fill="url(#if2wFEh)" class="h0k1czboq"/><path fill="url(#i4fG45b)" class="h0k1czboq"/><path fill="url(#iNusvMe)" class="qvn8oa7_c"/><path fill="url(#iaAXJxd)" class="jyzs683gq"/><path fill="url(#iyQNDyc)" class="jyzs683gq"/><path fill="url(#iLtKAld)" class="c6rg6t55t"/><path fill="url(#iO237oO)" class="hxp-k6btr"/><g filter="url(#irksyle)"><path class="rv80nzbup"/><path fill="url(#irFrNCb)" class="rlsyursqj"/></g><g filter="url(#iTsCFte)"><path fill="url(#immGUve)" class="qquotkp_x"/></g><path fill="url(#iq1XbFb)" class="i6onwv30g"/><path fill="url(#iRq2dld)" class="i6onwv30g"/><g filter="url(#iiNtrOG)"><path fill="url(#ivTCeAc)" class="bwoddgbvm"/></g><path fill="url(#iBpk1Od)" class="mvk7zqyoq"/><path fill="url(#iihWjnd)" class="mvk7zqyoq"/><path fill="url(#iz2EeMb)" class="mvk7zqyoq"/><path fill="url(#i9bwoTb)" class="mvk7zqyoq"/><path fill="url(#icY1ZuD)" class="mvk7zqyoq"/><g filter="url(#iKLy2qb)"><path class="di_6yub_o"/></g><g filter="url(#iW8KtNi)"><path fill="url(#ijjR2se)" class="vnw5j8hjv"/></g><g filter="url(#icMUNNe)"><path fill="url(#irfwegd)" class="zpt9zsbrj"/></g><path fill="url(#i1mPqWu)" class="zpt9zsbrj"/><path fill="url(#i1pGnqc)" class="zpt9zsbrj"/><path fill="url(#iGIzMHb)" class="zpt9zsbrj"/><path fill="url(#iZGiB2c)" class="zpt9zsbrj"/><g filter="url(#igoBs4b)"><path class="n-k7ghg7j"/></g><g filter="url(#i2JgZbd)"><path class="hw3687b4a"/><path fill="url(#i4UVKdL)" class="ili-q4b-s"/><path fill="url(#iJjOXMe)" class="ili-q4b-s"/><path fill="url(#iKQlUXb)" class="ili-q4b-s"/><path fill="url(#iZdyfub)" class="ili-q4b-s"/><path fill="url(#iShlgBe)" class="ili-q4b-s"/></g><g filter="url(#iEgNlne)"><path stroke="url(#iBZIbcd)" class="gwmgs95wh"/></g><path fill="url(#ijZzEsb)" class="ibmkw3jhm"/><g filter="url(#i2LbThh)"><path class="yqlj3owyh"/></g><g filter="url(#iY6PpQc)"><path class="fn6uscc6m"/></g><g filter="url(#iCnALlb)"><path class="ntj0-_b0s"/></g><g filter="url(#i2zL0Jb)"><path class="u89dwtb2u"/></g><g filter="url(#iAFJznc)"><path fill="url(#iOUX5kc)" class="cri-ttb-z"/></g><path fill="url(#iJDNeDe)" class="oseiggbng"/><path fill="url(#iKewJDq)" class="oseiggbng"/><path fill="url(#iCmpkJW)" class="ympk5wb7u"/><path fill="url(#iY1ozab)" class="ympk5wb7u"/><path fill="url(#iAKIyeI)" class="qm2y0dbqq"/><path fill="url(#iyGx7oT)" class="qm2y0dbqq"/><path fill="url(#irC8kvb)" class="qm2y0dbqq"/><g filter="url(#iH70PlO)"><path class="qg2y7f5vf"/></g><path class="sb_q-rbno"/><path fill="url(#iksbncb)" class="bwenl-dhx"/><path class="akzhfdxuo"/><g filter="url(#iCRRIJc)"><path class="umdpcutlj"/><path fill="url(#iDzsrKc)" class="fjish_b1f"/></g><g filter="url(#imYYeib)"><path fill="url(#iU2BOpc)" class="yrzljiztk"/></g><path class="fhaieldrb"/><path fill="url(#iQosLpb)" class="da2a_fwsh"/><path class="t28qzvndg"/><g filter="url(#if4VJOc)"><path fill="url(#iSYgUgb)" class="loa-jrs0h"/></g><g filter="url(#iHJvWUd)"><ellipse transform="rotate(-27.914 12.73 9.896)" class="ekzlqabop"/><ellipse fill="url(#iydViFF)" transform="rotate(-27.914 12.73 9.896)" class="qkoxj934f"/></g><g filter="url(#idtQzfe)"><path fill="url(#i3C13Ie)" class="n0mfkw0sc"/><path fill="url(#iiFDnYb)" class="n0mfkw0sc"/><path fill="url(#iNE2cOc)" class="n0mfkw0sc"/><path fill="url(#ijQpOGc)" class="n0mfkw0sc"/><path fill="url(#iNn8c0d)" class="n0mfkw0sc"/></g><g filter="url(#ioJJOIc)"><path stroke="url(#iSM0yPW)" class="dtnycdcis"/></g><g filter="url(#iNw9Rpb)"><path stroke="url(#iL2UGbe)" class="iu03wzlwv"/></g><g filter="url(#irLrdgb)"><path stroke="url(#iMLLx6b)" class="qr5otjtmk"/></g><defs><radialGradient id="iwUShWr" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.037 3.983)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iFRmxDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 18.912 5.145)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="ib4Vkxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.50793 20.3496 0 15.85 14.34)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="tvmqlbbhs"/><stop offset="1" class="h-c7wyugb"/></radialGradient><radialGradient id="iF8aDEZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.149 16.308)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="i994Zwe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.006 25.27)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="it8beRb" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.179 24.733)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iDvycOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 15.22 16.18)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iP61Dqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 14.364 19.575)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="i4fG45b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 14.612 15.993)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iNusvMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.139 19.675)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iaAXJxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87968 -1.90863 0 15.149 16.814)" gradientUnits="userSpaceOnUse"><stop class="s7aakmgnr"/><stop offset="1" class="l212nr2yp"/></radialGradient><radialGradient id="iyQNDyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50225 -2.55179 0 15.149 15.353)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="az3jcdmty"/><stop offset=".944" class="z48shob3w"/></radialGradient><radialGradient id="iLtKAld" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 2.65625 -2.11192 -.74538 20.678 12.11)" gradientUnits="userSpaceOnUse"><stop class="fzhruhbyt"/><stop offset="1" class="pft2s7y0a"/><stop offset="1" class="iheq2ib8b"/></radialGradient><radialGradient id="irFrNCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.99999 -1.375 1.3434 -.977 10.6 12.126)" gradientUnits="userSpaceOnUse"><stop class="en-2vgkms"/><stop offset="1" class="vvdbjrbwx"/></radialGradient><radialGradient id="immGUve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41345 0 0 -2.09099 10.46 10.794)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="ebnsn321w"/><stop offset="1" class="quk3dgi1t"/></radialGradient><radialGradient id="iRq2dld" cx="0" cy="0" r="1" gradientTransform="rotate(-51.009 22.997 -15.291)scale(1.68866)" gradientUnits="userSpaceOnUse"><stop class="guri77_rx"/><stop offset="1" class="jvouqxrlb"/></radialGradient><radialGradient id="ivTCeAc" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 4.948 15.136)scale(1.11515)" gradientUnits="userSpaceOnUse"><stop class="f4dh4oqdr"/><stop offset=".912" class="uspdh30af"/></radialGradient><radialGradient id="iihWjnd" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.138 11.707)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="icY1ZuD" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.159 18.833)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="irfwegd" cx="0" cy="0" r="1" gradientTransform="rotate(168.631 8.271 6.343)scale(5.03632 7.24341)" gradientUnits="userSpaceOnUse"><stop class="mc-usrgaa"/><stop offset="1" class="kgmaj5bdw"/></radialGradient><radialGradient id="i1mPqWu" cx="0" cy="0" r="1" gradientTransform="matrix(-.89088 10.72366 -10.88879 -.9046 16.542 6.495)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="obavl3bll"/><stop offset="1" class="dku91olyw"/></radialGradient><radialGradient id="i1pGnqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21626 1.85126 0 17.536 9.648)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iGIzMHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 1.54763 0 12.834 9.68)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iZGiB2c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.61952 .44238 -.92 -17.9257 18.65 12.739)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="svfkjdxef"/><stop offset="1" class="qk70xkspj"/></radialGradient><radialGradient id="iJjOXMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22684 -.76458 0 15.684 12.26)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iZdyfub" cx="0" cy="0" r="1" gradientTransform="rotate(156.852 6.698 7.484)scale(1.64873 2.52797)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="ijZzEsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.78645 3.09358 0 15.158 14.412)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iOUX5kc" cx="0" cy="0" r="1" gradientTransform="matrix(2.14063 0 0 .4039 17.6 7.099)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="h3qsa1h8x"/><stop offset="1" class="f_1ak3b9g"/></radialGradient><radialGradient id="iJDNeDe" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 11.038 15.176)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iKewJDq" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.747 23.64)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iY1ozab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 25.332 24.794)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iAKIyeI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 25.356 21.614)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="iyGx7oT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 24.857 21.997)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="iksbncb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 17.433 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iDzsrKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.201 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQosLpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 13.005 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iydViFF" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 12.714 10.216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiFDnYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.11 25.308)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iNE2cOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.11 26.602)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ijQpOGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.11 27.852)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iNn8c0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.11 29.204)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><filter id="iYFV5Tb" width="20.537" height="10.328" x="4.7" y="4.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1813" result="effect2_innerShadow_4002_1813"/></filter><filter id="iIcKDZb" width="8" height="6.44" x="11.219" y="15.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="irksyle" width="3.44" height="3.34" x="8.579" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.643137 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="iTsCFte" width="2.658" height="2.658" x="8.92" y="9.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".125"/></filter><filter id="iiNtrOG" width="2.827" height="2.827" x="18.625" y="9.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".125"/></filter><filter id="iKLy2qb" width="8.45" height="4.612" x="10.949" y="25.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".125"/></filter><filter id="iW8KtNi" width="8.05" height="4.28" x="11.099" y="25.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="icMUNNe" width="10.869" height="10.18" x="10.031" y="6.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.662745 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="igoBs4b" width="3.871" height="4.695" x="13.091" y="9.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".5"/></filter><filter id="i2JgZbd" width="2.271" height="3.095" x="14.083" y="9.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".1"/></filter><filter id="iEgNlne" width="3.833" height="1.572" x="13.242" y="13.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".05"/></filter><filter id="i2LbThh" width="2.195" height="1.016" x="16.798" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="iY6PpQc" width="2.095" height=".766" x="16.848" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".075"/></filter><filter id="iCnALlb" width="2.195" height="1.016" x="11.438" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="i2zL0Jb" width="2.095" height=".766" x="11.489" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".075"/></filter><filter id="iAFJznc" width="4.103" height=".85" x="15.919" y="6.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="iH70PlO" width="7.625" height="9.853" x="21.072" y="10.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1813" result="effect2_innerShadow_4002_1813"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1813" result="effect3_innerShadow_4002_1813"/></filter><filter id="iCRRIJc" width=".795" height=".703" x="16.689" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".05"/></filter><filter id="imYYeib" width=".898" height=".921" x="17.543" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".1"/></filter><filter id="if4VJOc" width=".995" height="1.05" x="13.035" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".1"/></filter><filter id="iHJvWUd" width=".923" height=".712" x="12.268" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".05"/></filter><filter id="idtQzfe" width="4.468" height="5.556" x="22.673" y="24.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1813"/></filter><filter id="ioJJOIc" width="2.097" height=".3" x="23.044" y="25.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".05"/></filter><filter id="iNw9Rpb" width="2.097" height=".3" x="22.965" y="27.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".05"/></filter><filter id="irLrdgb" width="2.097" height=".3" x="23.044" y="28.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1813" stdDeviation=".05"/></filter><linearGradient id="iKi2X3b" x1="15.139" x2="15.139" y1="4.033" y2="4.087" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="igAYhqk" x1="8.159" x2="4.568" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="ip4y95c" x1="25.721" x2="22.179" y1="22.888" y2="29.194" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="inhRu3C" x1="19.219" x2="18.284" y1="18.52" y2="18.52" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="if2wFEh" x1="11.219" x2="11.553" y1="18.52" y2="18.52" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iO237oO" x1="9.93" x2="10.844" y1="12.203" y2="14.425" gradientUnits="userSpaceOnUse"><stop class="e_gzvlbzc"/><stop offset="1" class="lu6xp3cta"/></linearGradient><linearGradient id="iq1XbFb" x1="21.145" x2="20.039" y1="9.783" y2="12.283" gradientUnits="userSpaceOnUse"><stop class="vgzo13b2o"/><stop offset="1" class="ccj7rwekm"/></linearGradient><linearGradient id="iBpk1Od" x1="16.381" x2="15.169" y1="29.145" y2="22.02" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iz2EeMb" x1="22.233" x2="22.006" y1="29.677" y2="29.677" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="i9bwoTb" x1="8.159" x2="8.283" y1="29.677" y2="29.677" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="ijjR2se" x1="13.006" x2="19.537" y1="28.364" y2="28.364" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="i4UVKdL" x1="16.054" x2="15.219" y1="11.623" y2="11.661" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iKQlUXb" x1="15.219" x2="15.219" y1="12.682" y2="12.25" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iShlgBe" x1="15.219" x2="15.219" y1="10.048" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iBZIbcd" x1="13.876" x2="14.23" y1="14.244" y2="13.338" gradientUnits="userSpaceOnUse"><stop class="i4xwdrbot"/><stop offset="1" class="a2_5cmbky"/></linearGradient><linearGradient id="iCmpkJW" x1="24.829" x2="24.829" y1="21.614" y2="24.794" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="irC8kvb" x1="24.857" x2="24.857" y1="22.317" y2="21.724" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="iU2BOpc" x1="18.222" x2="17.904" y1="10.048" y2="10.244" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSYgUgb" x1="13.76" x2="13.441" y1="10.048" y2="10.244" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3C13Ie" x1="26.701" x2="22.673" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iSM0yPW" x1="23.194" x2="24.903" y1="26.06" y2="26.06" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iL2UGbe" x1="23.115" x2="24.825" y1="27.364" y2="27.364" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iMLLx6b" x1="23.194" x2="24.903" y1="28.669" y2="28.669" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:farmer-light" /></template>
<style>
.a2_5cmbky {
  stop-color: var(--svg-color--dfaca3, #DFACA3);
  stop-opacity: 0;
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.akzhfdxuo {
  fill: var(--svg-color--000, #000);
  d: path("M16.916 10.415c0-.288.23-.519.519-.519a.516.516 0 0 1 .46.757h-.917a.47.47 0 0 1-.062-.238");
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.az3jcdmty {
  stop-color: var(--svg-color--906549, #906549);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bbq0uybhr {
  d: path("M10.782 4.833c-.849.031-2.678.229-4.101 1.336c-1.238.962-1.477 2.117-1.477 3.086v.476c-.093 1.782 1.446 4.93 6.883 4.93h6.264c5.437 0 6.976-3.148 6.883-4.93v-.476c0-.969-.24-2.124-1.477-3.086c-1.424-1.107-3.253-1.305-4.102-1.336z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bwenl-dhx {
  d: path("M17.435 9.51a.905.905 0 0 1 .872 1.143h-1.749a.91.91 0 0 1 .877-1.144");
}

.bwoddgbvm {
  d: path("M20.039 11.777a1.163 1.163 0 1 0 0-2.327a1.163 1.163 0 0 0 0 2.327");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.c6rg6t55t {
  d: path("M17.659 10.273v5.35l1.89-.65c.88-.3 1.46-1.13 1.46-2.06v-2.53c-1.12-.04-2.24-.08-3.35-.11");
}

.ccj7rwekm {
  stop-color: var(--svg-color--e9b69f, #E9B69F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cri-ttb-z {
  d: path("M17.629 7.634h2.393c-.35-.48-.923-.8-1.553-.8h-2.55c.42.5 1.05.8 1.71.8");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.da2a_fwsh {
  d: path("M13.003 9.51a.906.906 0 0 0-.873 1.143h1.75a1 1 0 0 0 .033-.238a.91.91 0 0 0-.91-.906");
}

.di_6yub_o {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M18.64 25.834h-6.941a.49.49 0 0 0-.5.491v3.62h7.95v-3.62a.513.513 0 0 0-.51-.491");
}

.dku91olyw {
  stop-color: var(--svg-color--b18585, #B18585);
}

.dtnycdcis {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.194 25.981h1.796");
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e_gzvlbzc {
  stop-color: var(--svg-color--3f312f, #3F312F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.ebnsn321w {
  stop-color: var(--svg-color--c68976, #C68976);
}

.ekzlqabop {
  cx: 12.73px;
  cy: 9.896px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.en-2vgkms {
  stop-color: var(--svg-color--d09480, #D09480);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.f_1ak3b9g {
  stop-color: var(--svg-color--2d282a, #2D282A);
}

.f4dh4oqdr {
  stop-color: var(--svg-color--efbba2, #EFBBA2);
}

.fhaieldrb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.793 9.233c-.663 0-1.222.457-1.375 1.075a.278.278 0 0 0 .272.345h2.264c.144 0 .26-.131.23-.275a1.42 1.42 0 0 0-1.39-1.145");
}

.fjish_b1f {
  d: path("M17.368 9.7c.065.087-.07.192-.223.307c-.154.114-.267.195-.332.109c-.064-.087.008-.25.16-.364c.154-.115.33-.138.395-.051");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fn6uscc6m {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.743 8.24s-.625-.474-1.695-.345");
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.fzhruhbyt {
  stop-color: var(--svg-color--3c3135, #3C3135);
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.guri77_rx {
  stop-color: var(--svg-color--e4b39c, #E4B39C);
}

.gwmgs95wh {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.703 13.31c-.199-.106-.392.12-.276.3a2.07 2.07 0 0 0 1.732.944a2.07 2.07 0 0 0 1.732-.943a.2.2 0 0 0-.024-.256a.21.21 0 0 0-.25-.046h-.002a3.1 3.1 0 0 1-1.456.355a3.1 3.1 0 0 1-1.457-.354Z");
}

.h-c7wyugb {
  stop-color: var(--svg-color--693e3f, #693E3F);
}

.h0k1czboq {
  d: path("m12.183 21.497l3.036-2.124l2.987 2.085c.421.324 1.013.465 1.013-.355v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.691c0 .953.594.823.964.563");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h3qsa1h8x {
  stop-color: var(--svg-color--454142, #454142);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hw3687b4a {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m14.839 10.333l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hxp-k6btr {
  d: path("m9.289 10.214l-.01 2.69c0 .93.59 1.75 1.46 2.06l1.89.65v-5.43c-1.1 0-2.22 0-3.34.03");
}

.i4xwdrbot {
  stop-color: var(--svg-color--dfaca3, #DFACA3);
}

.i6onwv30g {
  d: path("M20.039 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibmkw3jhm {
  d: path("M15.159 13.714c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.iheq2ib8b {
  stop-color: var(--svg-color--251c28, #251C28);
}

.ili-q4b-s {
  d: path("m14.839 10.333l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.iu03wzlwv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.115 27.286h1.797");
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jvouqxrlb {
  stop-color: var(--svg-color--e4b39c, #E4B39C);
  stop-opacity: 0;
}

.jyzs683gq {
  d: path("M15.149 18.693c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.kgmaj5bdw {
  stop-color: var(--svg-color--d9a393, #D9A393);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l212nr2yp {
  stop-color: var(--svg-color--bb9282, #BB9282);
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.loa-jrs0h {
  d: path("M13.83 10.308c0-.292-.238-.487-.302-.546l-.293.283l.18.366z");
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lu6xp3cta {
  stop-color: var(--svg-color--241c29, #241C29);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m_f6c8b6a {
  d: path("M21.139 5.933h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc-usrgaa {
  stop-color: var(--svg-color--ffd7bc, #FFD7BC);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mvk7zqyoq {
  d: path("M22.179 18.064c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.n-k7ghg7j {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.646 10.558l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.n0mfkw0sc {
  d: path("M22.673 25.329c0-.401.326-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H23.4a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.ntj0-_b0s {
  stroke: var(--svg-color--130e18, #130E18);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.689 8.302s.624-.473 1.695-.344");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.obavl3bll {
  stop-color: var(--svg-color--c59293, #C59293);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.oseiggbng {
  d: path("M25.991 23.144c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qg2y7f5vf {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M21.974 11.067a.6.6 0 0 0-.602.602v6.851a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.85a.601.601 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.602");
}

.qk70xkspj {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
}

.qkoxj934f {
  cx: 12.73px;
  cy: 9.896px;
  rx: 0.395px;
  ry: 0.2px;
}

.qm2y0dbqq {
  d: path("M24.096 20.013h1.523v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.qquotkp_x {
  d: path("M10.249 11.693a1.08 1.08 0 1 0 0-2.159a1.08 1.08 0 0 0 0 2.159");
}

.qr5otjtmk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.194 28.59h1.796");
}

.quk3dgi1t {
  stop-color: var(--svg-color--cd9282, #CD9282);
}

.qvn8oa7_c {
  d: path("m16.069 19.713l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rlsyursqj {
  d: path("M10.249 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.rv80nzbup {
  fill: var(--svg-color--cd9684, #CD9684);
  d: path("M10.249 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.s7aakmgnr {
  stop-color: var(--svg-color--b58885, #B58885);
}

.sb_q-rbno {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 9.233c.663 0 1.222.457 1.375 1.075a.278.278 0 0 1-.272.345h-2.264a.233.233 0 0 1-.23-.275c.127-.65.7-1.145 1.39-1.145");
}

.svfkjdxef {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
  stop-opacity: 0;
}

.t28qzvndg {
  fill: var(--svg-color--000, #000);
  d: path("M13.522 10.415a.516.516 0 0 0-.52-.519a.516.516 0 0 0-.46.757h.918a.5.5 0 0 0 .061-.238");
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t5v_l2big {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.149 15.523c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.te97h0xad {
  d: path("M15.149 15.523c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tvmqlbbhs {
  stop-color: var(--svg-color--79554f, #79554F);
}

.u89dwtb2u {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.689 8.24s.624-.474 1.695-.345");
}

.umdpcutlj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.368 9.7c.065.087-.07.192-.223.307c-.154.114-.267.195-.332.109c-.064-.087.008-.25.16-.364c.154-.115.33-.138.395-.051");
}

.uspdh30af {
  stop-color: var(--svg-color--e4af95, #E4AF95);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v3usx3bwv {
  d: path("m9.319 5.573l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vai20f3-l {
  d: path("M22.179 30.003v-11.97h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vgzo13b2o {
  stop-color: var(--svg-color--edc0ab, #EDC0AB);
}

.vj6k8zb9a {
  d: path("M8.159 30.003v-11.97h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vnw5j8hjv {
  d: path("M18.639 25.834h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.vvdbjrbwx {
  stop-color: var(--svg-color--d09480, #D09480);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.ympk5wb7u {
  d: path("M25.332 21.794h-1v3h1z");
}

.yqlj3owyh {
  stroke: var(--svg-color--130e18, #130E18);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.743 8.302s-.625-.473-1.695-.344");
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yrzljiztk {
  d: path("M18.241 10.296a.85.85 0 0 0-.234-.47l-.264.29l.119.231z");
}

.z48shob3w {
  stop-color: var(--svg-color--906549, #906549);
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zpt9zsbrj {
  d: path("m20.389 8.984l.01-.11c.04-1.09-.83-2.04-1.93-2.04h-6.5c-1.14 0-2.03.97-1.93 2.1l.3 4.65a3.95 3.95 0 0 0 3.92 3.43h1.9c1.98 0 3.66-1.47 3.92-3.43z");
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
