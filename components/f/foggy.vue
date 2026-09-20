<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGH6ECSdnf" class="dyhd8xpxy"/></defs><use href="#SVGH6ECSdnf" class="blrieubjf"/><clipPath id="SVGGnzhYcmD"><use href="#SVGH6ECSdnf"/></clipPath><g clip-path="url(#SVGGnzhYcmD)"><path class="rc9bz3bqx"/><path class="ihz5b8qnx"/><path class="snch7td8z"/><path class="qh409mb6f"/><path class="x0_dbzbxv"/></g><defs><use href="#SVGH6ECSdnf" id="SVGNMeSxcYE"/></defs><clipPath id="SVG3FvjDeRp"><use href="#SVGNMeSxcYE"/></clipPath><g clip-path="url(#SVG3FvjDeRp)"><defs><path id="SVGOpUlkesN" class="j6em86aok"/></defs><clipPath id="SVGVDLhjbQw"><use href="#SVGOpUlkesN"/></clipPath><g clip-path="url(#SVGVDLhjbQw)"><linearGradient id="SVGgzLEVdCa" x1="-18.899" x2="103.56" y1="89.517" y2="93.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGgzLEVdCa)" class="gmud0o9ny"/><linearGradient id="SVGVNdAxbqp" x1="-18.812" x2="103.467" y1="86.198" y2="94.562" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGVNdAxbqp)" class="migbz9b5c"/><linearGradient id="SVGuA1lLzOb" x1="-18.582" x2="103.231" y1="82.889" y2="95.412" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGuA1lLzOb)" class="ohthkh_fu"/><linearGradient id="SVGv3VTMedk" x1="-18.21" x2="102.855" y1="79.602" y2="96.242" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGv3VTMedk)" class="u-febf53a"/><linearGradient id="SVGRrITbboI" x1="-17.7" x2="102.34" y1="76.344" y2="97.041" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGRrITbboI)" class="tg0zlbbbx"/><linearGradient id="SVGR8eIined" x1="-17.052" x2="101.688" y1="73.126" y2="97.8" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGR8eIined)" class="x9w5edcbk"/><linearGradient id="SVGkrlE3b8H" x1="-16.27" x2="100.901" y1="69.957" y2="98.511" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGkrlE3b8H)" class="u0a13xbmj"/><linearGradient id="SVGmhKwhd6K" x1="-15.357" x2="99.985" y1="66.846" y2="99.163" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGmhKwhd6K)" class="d_3npjb5n"/><linearGradient id="SVGa0W5XcKL" x1="-14.319" x2="98.942" y1="63.801" y2="99.749" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGa0W5XcKL)" class="emq-xdb5v"/><linearGradient id="SVGvnnbTcmO" x1="-13.16" x2="97.78" y1="60.831" y2="100.259" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGvnnbTcmO)" class="yp1sonbsb"/><linearGradient id="SVGAIDX7cTy" x1="-11.886" x2="96.502" y1="57.944" y2="100.686" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGAIDX7cTy)" class="yl_l2xbkv"/><linearGradient id="SVGYhjyNVcU" x1="-10.502" x2="95.115" y1="55.147" y2="101.023" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGYhjyNVcU)" class="tb63m5b8m"/><linearGradient id="SVGO5TFzd6e" x1="-9.014" x2="93.625" y1="52.448" y2="101.261" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGO5TFzd6e)" class="l4s9kbcpu"/><linearGradient id="SVGKQ0SEcph" x1="-7.431" x2="92.039" y1="49.854" y2="101.395" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGKQ0SEcph)" class="gwpf9ybaw"/><linearGradient id="SVGTEb4zdWt" x1="-5.76" x2="90.365" y1="47.37" y2="101.419" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGTEb4zdWt)" class="lgfx-4bcb"/><linearGradient id="SVGIKl1MmBT" x1="-4.007" x2="88.611" y1="45.003" y2="101.325" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGIKl1MmBT)" class="yw-6iwbpt"/><linearGradient id="SVGlIdTqbhE" x1="-2.181" x2="86.784" y1="42.758" y2="101.11" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGlIdTqbhE)" class="xyz4a5bzt"/><linearGradient id="SVGNVc1fdjy" x1="-.292" x2="84.894" y1="40.638" y2="100.769" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGNVc1fdjy)" class="c9dcj5b3e"/><linearGradient id="SVGasWIc8aX" x1="1.653" x2="82.949" y1="38.649" y2="100.297" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGasWIc8aX)" class="bw826cdvj"/><linearGradient id="SVGa5CaGduz" x1="3.644" x2="80.957" y1="36.794" y2="99.692" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGa5CaGduz)" class="cacwbtbzo"/><linearGradient id="SVGiB3OoeAW" x1="5.672" x2="78.929" y1="35.074" y2="98.952" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGiB3OoeAW)" class="uzgrgubru"/><linearGradient id="SVGTz3aFo5l" x1="7.728" x2="76.874" y1="33.494" y2="98.073" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGTz3aFo5l)" class="ybvpn22jh"/><linearGradient id="SVGBHHDibVE" x1="9.802" x2="74.802" y1="32.053" y2="97.053" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGBHHDibVE)" class="j-hbpsobf"/><linearGradient id="SVGkPHG4bqr" x1="11.884" x2="72.721" y1="30.753" y2="95.893" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGkPHG4bqr)" class="cg2-fybxe"/><linearGradient id="SVGvKZu2bSb" x1="13.965" x2="70.641" y1="29.594" y2="94.593" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGvKZu2bSb)" class="t2-cz-fgw"/><linearGradient id="SVGnhsUm1aM" x1="16.036" x2="68.573" y1="28.575" y2="93.152" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGnhsUm1aM)" class="g59shqboc"/><linearGradient id="SVGXtYxMdqe" x1="18.086" x2="66.525" y1="27.697" y2="91.573" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXtYxMdqe)" class="fxdl7ybek"/><linearGradient id="SVG6rlqsbpK" x1="20.106" x2="64.507" y1="26.954" y2="89.856" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG6rlqsbpK)" class="aolu5-7aj"/><linearGradient id="SVGDgEjfdAS" x1="22.088" x2="62.529" y1="26.349" y2="88.005" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGDgEjfdAS)" class="xmf5cyevk"/><linearGradient id="SVGSQG7fdwj" x1="24.021" x2="60.598" y1="25.873" y2="86.022" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGSQG7fdwj)" class="qla-0gbpo"/><linearGradient id="SVGueLmPeYz" x1="25.898" x2="58.725" y1="25.527" y2="83.911" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGueLmPeYz)" class="c-b7hfbdo"/><linearGradient id="SVGiPuevdAg" x1="27.708" x2="56.918" y1="25.305" y2="81.677" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGiPuevdAg)" class="zi_h2vylf"/><linearGradient id="SVGdj1H7wvI" x1="29.445" x2="55.184" y1="25.202" y2="79.324" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGdj1H7wvI)" class="qj_ecbbau"/><linearGradient id="SVG0BkAuduS" x1="31.101" x2="53.533" y1="25.213" y2="76.857" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG0BkAuduS)" class="o52c4kwbw"/><linearGradient id="SVGJDmYicVZ" x1="32.667" x2="51.97" y1="25.332" y2="74.283" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGJDmYicVZ)" class="ycyihab1q"/><linearGradient id="SVGRNvX8bWU" x1="34.136" x2="50.504" y1="25.552" y2="71.608" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGRNvX8bWU)" class="lwkfmvmkj"/><linearGradient id="SVGXQLSjebf" x1="35.503" x2="49.141" y1="25.867" y2="68.839" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXQLSjebf)" class="lccmmgbbg"/><linearGradient id="SVGBDBdCbEg" x1="36.76" x2="47.887" y1="26.27" y2="65.983" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGBDBdCbEg)" class="vokmh9b4j"/><linearGradient id="SVGIiyQEbpc" x1="37.903" x2="46.748" y1="26.752" y2="63.048" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGIiyQEbpc)" class="z0cuqebnp"/><linearGradient id="SVGFPGKJdgE" x1="38.925" x2="45.728" y1="27.305" y2="60.042" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGFPGKJdgE)" class="d0cdx_3zy"/><linearGradient id="SVG7Q2CKb8Z" x1="39.824" x2="44.833" y1="27.922" y2="56.974" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG7Q2CKb8Z)" class="e3og4lbnr"/><linearGradient id="SVGKm2E0cEb" x1="40.594" x2="44.065" y1="28.594" y2="53.851" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGKm2E0cEb)" class="ov3swbvnu"/><linearGradient id="SVGJktW7c6f" x1="41.232" x2="43.429" y1="29.311" y2="50.683" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGJktW7c6f)" class="g6eolibaw"/><linearGradient id="SVGM7O1Jcoe" x1="41.736" x2="42.927" y1="30.064" y2="47.48" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGM7O1Jcoe)" class="pvd15-b3z"/><linearGradient id="SVGKiqYrddA" x1="42.103" x2="42.561" y1="30.845" y2="44.249" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGKiqYrddA)" class="y543irbme"/><linearGradient id="SVGyVOUIbLt" x1="42.333" x2="42.333" y1="31.643" y2="41.001" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGyVOUIbLt)" class="osbfskbhy"/></g><defs><path id="SVGxjSkabpa" class="r64bc6b-u"/></defs><clipPath id="SVGV3yQtbhJ"><use href="#SVGxjSkabpa"/></clipPath><g clip-path="url(#SVGV3yQtbhJ)"><linearGradient id="SVGPKdw7b6x" x1="12.642" x2="135.151" y1="60.236" y2="64.421" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGPKdw7b6x)" class="qii94rb5z"/><linearGradient id="SVGcn1Axepz" x1="12.704" x2="135.083" y1="56.729" y2="65.1" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGcn1Axepz)" class="drmcvabsd"/><linearGradient id="SVGaIEfvdrd" x1="12.91" x2="134.873" y1="53.231" y2="65.769" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGaIEfvdrd)" class="qagz8jyba"/><linearGradient id="SVGClP65tfO" x1="13.258" x2="134.52" y1="49.753" y2="66.42" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGClP65tfO)" class="v2eese03r"/><linearGradient id="SVGxQYX9cQr" x1="13.745" x2="134.028" y1="46.303" y2="67.042" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGxQYX9cQr)" class="hl3-xobqw"/><linearGradient id="SVGadB3VcCZ" x1="14.371" x2="133.399" y1="42.891" y2="67.626" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGadB3VcCZ)" class="gtm_h2bjx"/><linearGradient id="SVGmuKBaeVT" x1="15.13" x2="132.634" y1="39.526" y2="68.162" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGmuKBaeVT)" class="sf2-foj0k"/><linearGradient id="SVGCrcDNd4h" x1="16.021" x2="131.739" y1="36.218" y2="68.641" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGCrcDNd4h)" class="yk4tycc-x"/><linearGradient id="SVGXX9ede3e" x1="17.039" x2="130.718" y1="32.974" y2="69.055" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXX9ede3e)" class="ds14i6b9h"/><linearGradient id="SVGzwiS7cjT" x1="18.178" x2="129.575" y1="29.805" y2="69.395" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGzwiS7cjT)" class="sjowh9mho"/><linearGradient id="SVGaIShkbrd" x1="19.434" x2="128.315" y1="26.717" y2="69.654" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGaIShkbrd)" class="l315q6azx"/><linearGradient id="SVGiy09GdCQ" x1="20.801" x2="126.945" y1="23.718" y2="69.822" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGiy09GdCQ)" class="z__xbejhs"/><linearGradient id="SVGvrcmDcGS" x1="22.272" x2="125.471" y1="20.815" y2="69.895" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGvrcmDcGS)" class="pnc3nfbua"/><linearGradient id="SVGtqJsuecl" x1="23.841" x2="123.9" y1="18.017" y2="69.863" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGtqJsuecl)" class="utf8gibpb"/><linearGradient id="SVG2grEWcDQ" x1="25.499" x2="122.239" y1="15.328" y2="69.722" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG2grEWcDQ)" class="xn2vo5bne"/><linearGradient id="SVGs4BrFc4n" x1="27.24" x2="120.497" y1="12.754" y2="69.465" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGs4BrFc4n)" class="o5ina5bmi"/><linearGradient id="SVGkXIgxdrU" x1="29.055" x2="118.68" y1="10.302" y2="69.087" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGkXIgxdrU)" class="vpd8gwbnl"/><linearGradient id="SVGb0mC7yRe" x1="30.936" x2="116.799" y1="7.975" y2="68.584" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGb0mC7yRe)" class="swup-blog"/><linearGradient id="SVGiCzN2c3b" x1="32.873" x2="114.861" y1="5.778" y2="67.951" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGiCzN2c3b)" class="gl3h43b7y"/><linearGradient id="SVGQihC7dsy" x1="34.859" x2="112.875" y1="3.713" y2="67.184" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGQihC7dsy)" class="zt4klmb-r"/><linearGradient id="SVGfO8n0tJH" x1="36.883" x2="110.851" y1="1.786" y2="66.282" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGfO8n0tJH)" class="co9zh5bjm"/><linearGradient id="SVGW43BfdNA" x1="38.937" x2="108.798" y1="-.004" y2="65.242" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGW43BfdNA)" class="ya2uccb0l"/><linearGradient id="SVGkV0nVdpe" x1="41.01" x2="106.726" y1="-1.654" y2="64.062" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGkV0nVdpe)" class="ypnqu4bru"/><linearGradient id="SVGICe8pdYB" x1="43.094" x2="104.644" y1="-3.163" y2="62.741" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGICe8pdYB)" class="qpfz3gbxt"/><linearGradient id="SVGWLnqicrW" x1="45.178" x2="102.561" y1="-4.531" y2="61.28" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGWLnqicrW)" class="awxefu7el"/><linearGradient id="SVG26DYudFn" x1="47.252" x2="100.489" y1="-5.758" y2="59.678" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG26DYudFn)" class="vykqxg54v"/><linearGradient id="SVGJia5gdhn" x1="49.309" x2="98.435" y1="-6.846" y2="57.937" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGJia5gdhn)" class="sm1d2jyaf"/><linearGradient id="SVGcUm4Ho6b" x1="51.337" x2="96.409" y1="-7.795" y2="56.058" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGcUm4Ho6b)" class="x8jlytbry"/><linearGradient id="SVGjENZrdhg" x1="53.327" x2="94.421" y1="-8.609" y2="54.044" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGjENZrdhg)" class="lqoe37ybe"/><linearGradient id="SVGug6N1dKf" x1="55.271" x2="92.481" y1="-9.29" y2="51.898" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGug6N1dKf)" class="de1cv5b1f"/><linearGradient id="SVGxfHunbHw" x1="57.16" x2="90.595" y1="-9.842" y2="49.622" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGxfHunbHw)" class="u6eey1b9v"/><linearGradient id="SVGILbUobZT" x1="58.984" x2="88.774" y1="-10.269" y2="47.223" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGILbUobZT)" class="td43gdeof"/><linearGradient id="SVGpAoJWdrh" x1="60.736" x2="87.026" y1="-10.576" y2="44.704" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGpAoJWdrh)" class="hzwbf8bqw"/><linearGradient id="SVGp8pmPbIK" x1="62.407" x2="85.358" y1="-10.768" y2="42.07" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGp8pmPbIK)" class="u9nz55blw"/><linearGradient id="SVGJpb6N0Zc" x1="63.991" x2="83.778" y1="-10.85" y2="39.328" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGJpb6N0Zc)" class="htezcibqu"/><linearGradient id="SVGEbKtZdru" x1="65.479" x2="82.294" y1="-10.83" y2="36.483" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGEbKtZdru)" class="pk7_3oiss"/><linearGradient id="SVGohig3eYi" x1="66.865" x2="80.912" y1="-10.714" y2="33.544" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGohig3eYi)" class="g1otpmbex"/><linearGradient id="SVGwZ3xQZqx" x1="68.143" x2="79.637" y1="-10.509" y2="30.515" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGwZ3xQZqx)" class="d_5sw2b_a"/><linearGradient id="SVGvQVYYdmi" x1="69.307" x2="78.477" y1="-10.224" y2="27.407" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGvQVYYdmi)" class="dsv0o98ti"/><linearGradient id="SVGSsRkucrg" x1="70.351" x2="77.435" y1="-9.865" y2="24.225" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGSsRkucrg)" class="p9e8fvcks"/><linearGradient id="SVG5rWCf8fj" x1="71.272" x2="76.517" y1="-9.442" y2="20.981" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG5rWCf8fj)" class="ifrcnclxi"/><linearGradient id="SVGyPGvreEu" x1="72.065" x2="75.727" y1="-8.962" y2="17.68" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGyPGvreEu)" class="g79qdq42d"/><linearGradient id="SVGUgsCKbZX" x1="72.727" x2="75.067" y1="-8.435" y2="14.332" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGUgsCKbZX)" class="b0r8li7km"/><linearGradient id="SVGLABb4GSl" x1="73.254" x2="74.541" y1="-7.87" y2="10.946" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGLABb4GSl)" class="f19d_be4i"/><linearGradient id="SVG210vKfQO" x1="73.646" x2="74.152" y1="-7.277" y2="7.533" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG210vKfQO)" class="f1199cc1b"/><linearGradient id="SVGwLQkBcXh" x1="73.899" x2="73.899" y1="-6.663" y2="4.101" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGwLQkBcXh)" class="dy4faobbx"/></g><defs><path id="SVGRoUMtbzd" class="h_p6r_bws"/></defs><clipPath id="SVG5IFPoc7X"><use href="#SVGRoUMtbzd"/></clipPath><g clip-path="url(#SVG5IFPoc7X)"><linearGradient id="SVG7OgKxeum" x1="19.558" x2="141.908" y1="128.38" y2="132.559" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG7OgKxeum)" class="jupx80kwr"/><linearGradient id="SVGjWOpqeus" x1="19.699" x2="141.762" y1="125.472" y2="133.821" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGjWOpqeus)" class="qyh67pbxf"/><linearGradient id="SVGzjNQhdoF" x1="19.982" x2="141.473" y1="122.579" y2="135.069" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGzjNQhdoF)" class="ndijhpb6j"/><linearGradient id="SVGReZ3BeEE" x1="20.406" x2="141.044" y1="119.711" y2="136.292" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGReZ3BeEE)" class="lh_sbdbxs"/><linearGradient id="SVGGqBrGeZH" x1="20.969" x2="140.477" y1="116.876" y2="137.481" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGGqBrGeZH)" class="jut3tbgoj"/><linearGradient id="SVGDpRhhbSt" x1="21.667" x2="139.774" y1="114.084" y2="138.627" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGDpRhhbSt)" class="aww6aibth"/><linearGradient id="SVG93i6Fl4u" x1="22.498" x2="138.939" y1="111.345" y2="139.72" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG93i6Fl4u)" class="hasc_4bpt"/><linearGradient id="SVGhDJRteUm" x1="23.457" x2="137.976" y1="108.666" y2="140.752" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGhDJRteUm)" class="hu5jk_bec"/><linearGradient id="SVGPohXGc1l" x1="24.54" x2="136.888" y1="106.057" y2="141.715" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGPohXGc1l)" class="emnzno0cs"/><linearGradient id="SVGgmFIOcwu" x1="25.742" x2="135.683" y1="103.525" y2="142.599" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGgmFIOcwu)" class="no_n8vbtr"/><linearGradient id="SVGbpPGuiAf" x1="27.057" x2="134.365" y1="101.08" y2="143.397" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGbpPGuiAf)" class="m0sz2a9jy"/><linearGradient id="SVGx8e5i1ww" x1="28.479" x2="132.94" y1="98.728" y2="144.101" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGx8e5i1ww)" class="ast6uibyn"/><linearGradient id="SVGy1uBNe3h" x1="30.001" x2="131.415" y1="96.476" y2="144.706" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGy1uBNe3h)" class="k5svombzl"/><linearGradient id="SVGXWanberL" x1="31.617" x2="129.797" y1="94.331" y2="145.203" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXWanberL)" class="zsm0x0bpl"/><linearGradient id="SVGLxi3Pe4K" x1="33.318" x2="128.094" y1="92.298" y2="145.588" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGLxi3Pe4K)" class="zcn1s8c4k"/><linearGradient id="SVGpmQ4QgSf" x1="35.097" x2="126.313" y1="90.384" y2="145.854" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGpmQ4QgSf)" class="q01xrgb7i"/><linearGradient id="SVGr530RbXe" x1="36.945" x2="124.464" y1="88.593" y2="145.997" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGr530RbXe)" class="tl4es0b_w"/><linearGradient id="SVGxugAMv9r" x1="38.853" x2="122.555" y1="86.929" y2="146.012" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGxugAMv9r)" class="alpyg9b6r"/><linearGradient id="SVGzIRiUdeN" x1="40.814" x2="120.594" y1="85.397" y2="145.896" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGzIRiUdeN)" class="nhi_e7bmh"/><linearGradient id="SVGlecA5c5G" x1="42.817" x2="118.59" y1="84" y2="145.645" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGlecA5c5G)" class="fqjlrsbey"/><linearGradient id="SVGbpItnbMA" x1="44.854" x2="116.554" y1="82.74" y2="145.259" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGbpItnbMA)" class="gv-4u8buu"/><linearGradient id="SVGnVPDrPqg" x1="46.915" x2="114.494" y1="81.618" y2="144.733" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGnVPDrPqg)" class="g5k63d_jz"/><linearGradient id="SVGw8vvycgq" x1="48.99" x2="112.42" y1="80.637" y2="144.067" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGw8vvycgq)" class="wbd7aonfb"/><linearGradient id="SVGCY1gOgcS" x1="51.07" x2="110.341" y1="79.797" y2="143.26" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGCY1gOgcS)" class="fyddshm6r"/><linearGradient id="SVGKEqIdbVD" x1="53.146" x2="108.267" y1="79.097" y2="142.313" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGKEqIdbVD)" class="ocjbps60c"/><linearGradient id="SVGXQGkMccd" x1="55.207" x2="106.209" y1="78.537" y2="141.227" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXQGkMccd)" class="sgczb9bgn"/><linearGradient id="SVG26eUyejB" x1="57.244" x2="104.174" y1="78.115" y2="140.002" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG26eUyejB)" class="lrh-kdb6o"/><linearGradient id="SVGSVTXteXv" x1="59.247" x2="102.173" y1="77.83" y2="138.642" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGSVTXteXv)" class="tk9e-gbss"/><linearGradient id="SVG3f1oqdlp" x1="61.209" x2="100.215" y1="77.679" y2="137.148" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG3f1oqdlp)" class="k8h7xy22s"/><linearGradient id="SVGMPeKsepu" x1="63.119" x2="98.308" y1="77.658" y2="135.524" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGMPeKsepu)" class="kki9sz7hr"/><linearGradient id="SVGn0Uk97BM" x1="64.969" x2="96.461" y1="77.764" y2="133.773" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGn0Uk97BM)" class="w-6naubee"/><linearGradient id="SVGSoFQudko" x1="66.75" x2="94.683" y1="77.992" y2="131.901" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGSoFQudko)" class="h-mxq_bix"/><linearGradient id="SVGRyVq7bCH" x1="68.454" x2="92.982" y1="78.337" y2="129.913" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGRyVq7bCH)" class="nyl69vu8g"/><linearGradient id="SVGiJKNfmxr" x1="70.074" x2="91.366" y1="78.794" y2="127.814" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGiJKNfmxr)" class="js8iaybrs"/><linearGradient id="SVGITLYkd8X" x1="71.602" x2="89.842" y1="79.356" y2="125.609" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGITLYkd8X)" class="os3rmn57b"/><linearGradient id="SVG3kdbCdLN" x1="73.031" x2="88.416" y1="80.017" y2="123.306" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG3kdbCdLN)" class="u81y-6b9t"/><linearGradient id="SVGUkH9LciQ" x1="74.355" x2="87.096" y1="80.769" y2="120.913" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGUkH9LciQ)" class="o5_c4obov"/><linearGradient id="SVGovxrNZMR" x1="75.567" x2="85.886" y1="81.606" y2="118.435" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGovxrNZMR)" class="qr67lgd5k"/><linearGradient id="SVGXgikTvri" x1="76.663" x2="84.793" y1="82.519" y2="115.881" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXgikTvri)" class="mevatdbra"/><linearGradient id="SVG7cENdd1i" x1="77.638" x2="83.822" y1="83.502" y2="113.26" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG7cENdd1i)" class="os8x04rjd"/><linearGradient id="SVGDEIp9b4D" x1="78.487" x2="82.976" y1="84.543" y2="110.579" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGDEIp9b4D)" class="yxxhryjkc"/><linearGradient id="SVG8gs6Ne7n" x1="79.206" x2="82.259" y1="85.636" y2="107.848" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG8gs6Ne7n)" class="pqhjz7b8r"/><linearGradient id="SVGqRPaKbkK" x1="79.793" x2="81.674" y1="86.77" y2="105.075" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGqRPaKbkK)" class="hipakjw2r"/><linearGradient id="SVGYkU0O0Ac" x1="80.244" x2="81.224" y1="87.939" y2="102.269" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGYkU0O0Ac)" class="glmbi308i"/><linearGradient id="SVGEhi30bCf" x1="80.559" x2="80.911" y1="89.129" y2="99.441" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGEhi30bCf)" class="irphkbbhj"/><linearGradient id="SVGiQkUxdOE" x1="80.735" x2="80.735" y1="90.335" y2="96.598" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGiQkUxdOE)" class="qbx1ff6gq"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:foggy" /></template>
<style>
.alpyg9b6r {
  d: path("M19.56 113.26h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-391, 0.391);
}

.aolu5-7aj {
  d: path("M-18.84 53.62h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-609, 0.609);
}

.ast6uibyn {
  d: path("M19.56 118.2h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-261, 0.261);
}

.aww6aibth {
  d: path("M19.56 123.13h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.awxefu7el {
  d: path("M12.72 22.86h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-543, 0.543);
}

.b0r8li7km {
  d: path("M12.72-2.58h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-935, 0.935);
}

.blrieubjf {
  fill: var(--svg-color--b9e8f4, #b9e8f4);
}

.bw826cdvj {
  d: path("M-18.84 64.67h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-413, 0.413);
}

.c-b7hfbdo {
  d: path("M-18.84 49.93h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-674, 0.674);
}

.c9dcj5b3e {
  d: path("M-18.84 65.9h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-391, 0.391);
}

.cacwbtbzo {
  d: path("M-18.84 63.45h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-435, 0.435);
}

.cg2-fybxe {
  d: path("M-18.84 58.53h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-522, 0.522);
}

.co9zh5bjm {
  d: path("M12.72 28.51h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-457, 0.457);
}

.d_3npjb5n {
  d: path("M-18.84 78.19h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-174, 0.174);
}

.d_5sw2b_a {
  d: path("M12.72 4.49h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-826, 0.826);
}

.d0cdx_3zy {
  d: path("M-18.84 38.88h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-87, 0.87);
}

.de1cv5b1f {
  d: path("M12.72 15.79h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-652, 0.652);
}

.drmcvabsd {
  d: path("M12.72 55.36h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-043, 0.043);
}

.ds14i6b9h {
  d: path("M12.72 45.47h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-196, 0.196);
}

.dsv0o98ti {
  d: path("M12.72 3.07h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-848, 0.848);
}

.dy4faobbx {
  d: path("M12.72-6.82h122.35v11.1H12.72z");
}

.dyhd8xpxy {
  d: path("M128 115.89c0 6.65-5.44 12.1-12.09 12.1H12.1c-6.65 0-12.09-5.44-12.09-12.1V12.1C.01 5.44 5.45 0 12.1 0h103.8c6.66 0 12.1 5.44 12.1 12.1z");
}

.e3og4lbnr {
  d: path("M-18.84 37.65h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-891, 0.891);
}

.emnzno0cs {
  d: path("M19.56 120.66h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-196, 0.196);
}

.emq-xdb5v {
  d: path("M-18.84 76.96h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-196, 0.196);
}

.f1199cc1b {
  d: path("M12.72-5.41h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-978, 0.978);
}

.f19d_be4i {
  d: path("M12.72-3.99h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-957, 0.957);
}

.fqjlrsbey {
  d: path("M19.56 111.62h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-435, 0.435);
}

.fxdl7ybek {
  d: path("M-18.84 54.85h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-587, 0.587);
}

.fyddshm6r {
  d: path("M19.56 108.33h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-522, 0.522);
}

.g1otpmbex {
  d: path("M12.72 5.9h122.35V17H12.72z");
  opacity: var(--svg-opacity--0-804, 0.804);
}

.g59shqboc {
  d: path("M-18.84 56.07h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-565, 0.565);
}

.g5k63d_jz {
  d: path("M19.56 109.97h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-478, 0.478);
}

.g6eolibaw {
  d: path("M-18.84 35.19h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-935, 0.935);
}

.g79qdq42d {
  d: path("M12.72-1.17h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-913, 0.913);
}

.gl3h43b7y {
  d: path("M12.72 31.34h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-413, 0.413);
}

.glmbi308i {
  d: path("M19.56 91.89h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-957, 0.957);
}

.gmud0o9ny {
  d: path("M-18.84 86.79h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-022, 0.022);
}

.gtm_h2bjx {
  d: path("M12.72 49.71h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.gv-4u8buu {
  d: path("M19.56 110.8h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-457, 0.457);
}

.gwpf9ybaw {
  d: path("M-18.84 70.82h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-304, 0.304);
}

.h_p6r_bws {
  d: path("M127.3 128.47c1.87-.21 3.04-1.61 3.73-3.55c1.21-3.41 1.38-18.61.56-21.37c-.61-2.07-.37-6.64-.37-6.64s-45.54 0-55.38.24c-1.66.04-7.43-.15-10.34 3.5c-3.79 4.73 1.8 7.55 3.24 8.03c3.84 1.27 9.5.03 9 3.48c-.2 1.36-.95 2-4.79 2.08c-17.11.37-28.55.58-39.94.69c-4.8.04-6.59 1.21-8.52 2.93c-2.12 1.89-2.79 6.17-.3 8.93c2.17 2.39 5.83 2.55 8.68 2.55c34.25-.01 84.95.21 94.43-.87");
}

.h-mxq_bix {
  d: path("M19.56 101.75h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-696, 0.696);
}

.hasc_4bpt {
  d: path("M19.56 122.31h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-152, 0.152);
}

.hipakjw2r {
  d: path("M19.56 92.71h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-935, 0.935);
}

.hl3-xobqw {
  d: path("M12.72 51.12h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-109, 0.109);
}

.htezcibqu {
  d: path("M12.72 8.73h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-761, 0.761);
}

.hu5jk_bec {
  d: path("M19.56 121.49h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-174, 0.174);
}

.hzwbf8bqw {
  d: path("M12.72 11.55h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-717, 0.717);
}

.ifrcnclxi {
  d: path("M12.72.25h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-891, 0.891);
}

.ihz5b8qnx {
  fill: var(--svg-color--7d7d7d, #7d7d7d);
  d: path("M52 89.68c0-4.99-4.08-9.07-9.07-9.07h-25.3c-4.99 0-9.07 4.08-9.07 9.07v30.39c0 4.99 4.08 9.07 9.07 9.07h25.3c4.99 0 9.07-4.08 9.07-9.07z");
}

.irphkbbhj {
  d: path("M19.56 91.06h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-978, 0.978);
}

.j-hbpsobf {
  d: path("M-18.84 59.76h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.j6em86aok {
  d: path("M-5.06 88.01c-3.53.05-8.9-1.48-8.9-6.43c0-8.88.54-24.89.54-30.89c0-4.39.48-8.83 5.44-8.83h22.94c4.69 0 11.93-.26 16.6.46c6.07.93 10.88 2.68 8.73 8.73c-2 5.63-11.02 3.75-12.39 7.98c-.77 2.38-.02 3.9 1.54 4.86c3.91 2.41 35.8 1.38 52.48 2.54c3.85.27 10.38 3.35 10.38 9.48c0 6.7-3.97 10.34-13.32 10.95C59.89 88.1-.96 87.95-5.06 88.01");
}

.js8iaybrs {
  d: path("M19.56 100.11h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-739, 0.739);
}

.jupx80kwr {
  d: path("M19.56 127.24h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-022, 0.022);
}

.jut3tbgoj {
  d: path("M19.56 123.95h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-109, 0.109);
}

.k5svombzl {
  d: path("M19.56 117.37h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-283, 0.283);
}

.k8h7xy22s {
  d: path("M19.56 104.22h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-63, 0.63);
}

.kki9sz7hr {
  d: path("M19.56 103.4h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-652, 0.652);
}

.l315q6azx {
  d: path("M12.72 42.64h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-239, 0.239);
}

.l4s9kbcpu {
  d: path("M-18.84 72.04h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-283, 0.283);
}

.lccmmgbbg {
  d: path("M-18.84 42.56h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-804, 0.804);
}

.lgfx-4bcb {
  d: path("M-18.84 69.59h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-326, 0.326);
}

.lh_sbdbxs {
  d: path("M19.56 124.77h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-087, 0.087);
}

.lqoe37ybe {
  d: path("M12.72 17.2h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-63, 0.63);
}

.lrh-kdb6o {
  d: path("M19.56 105.86h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-587, 0.587);
}

.lwkfmvmkj {
  d: path("M-18.84 43.79h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-783, 0.783);
}

.m0sz2a9jy {
  d: path("M19.56 119.02h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-239, 0.239);
}

.mevatdbra {
  d: path("M19.56 96h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-848, 0.848);
}

.migbz9b5c {
  d: path("M-18.84 85.56h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-043, 0.043);
}

.ndijhpb6j {
  d: path("M19.56 125.6h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-065, 0.065);
}

.nhi_e7bmh {
  d: path("M19.56 112.44h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-413, 0.413);
}

.no_n8vbtr {
  d: path("M19.56 119.84h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-217, 0.217);
}

.nyl69vu8g {
  d: path("M19.56 100.93h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-717, 0.717);
}

.o5_c4obov {
  d: path("M19.56 97.64h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-804, 0.804);
}

.o52c4kwbw {
  d: path("M-18.84 46.25h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-739, 0.739);
}

.o5ina5bmi {
  d: path("M12.72 35.58h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-348, 0.348);
}

.ocjbps60c {
  d: path("M19.56 107.51h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-543, 0.543);
}

.ohthkh_fu {
  d: path("M-18.84 84.33h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-065, 0.065);
}

.os3rmn57b {
  d: path("M19.56 99.29h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-761, 0.761);
}

.os8x04rjd {
  d: path("M19.56 95.18h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-87, 0.87);
}

.osbfskbhy {
  d: path("M-18.84 31.51h122.35v9.65H-18.84z");
}

.ov3swbvnu {
  d: path("M-18.84 36.42h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-913, 0.913);
}

.p9e8fvcks {
  d: path("M12.72 1.66h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-87, 0.87);
}

.pk7_3oiss {
  d: path("M12.72 7.31h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-783, 0.783);
}

.pnc3nfbua {
  d: path("M12.72 39.82h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-283, 0.283);
}

.pqhjz7b8r {
  d: path("M19.56 93.53h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-913, 0.913);
}

.pvd15-b3z {
  d: path("M-18.84 33.96h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-957, 0.957);
}

.q01xrgb7i {
  d: path("M19.56 114.91h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-348, 0.348);
}

.qagz8jyba {
  d: path("M12.72 53.95h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-065, 0.065);
}

.qbx1ff6gq {
  d: path("M19.56 90.24h122.35v6.46H19.56z");
}

.qh409mb6f {
  fill: var(--svg-color--7d7d7d, #7d7d7d);
  d: path("M120.03 64.62c0-4.99-4.08-9.07-9.07-9.07H86.97c-4.99 0-9.07 4.08-9.07 9.07v55.46c0 4.99 4.08 9.07 9.07 9.07h23.99c4.99 0 9.07-4.08 9.07-9.07z");
}

.qii94rb5z {
  d: path("M12.72 56.78h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-022, 0.022);
}

.qj_ecbbau {
  d: path("M-18.84 47.48h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-717, 0.717);
}

.qla-0gbpo {
  d: path("M-18.84 51.16h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-652, 0.652);
}

.qpfz3gbxt {
  d: path("M12.72 24.27h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-522, 0.522);
}

.qr67lgd5k {
  d: path("M19.56 96.82h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-826, 0.826);
}

.qyh67pbxf {
  d: path("M19.56 126.42h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-043, 0.043);
}

.r64bc6b-u {
  d: path("M132.5 58.36c.34-2.15 1.05-48.14.06-55.15c-.53-3.82-4.16-4.78-12.39-4.78c-11.84 0-75.87.23-85.9 1.28C28.82.27 25.01.86 23.2 1.54c-4.89 1.8-8.76 8.47-4.54 13.56c2.34 2.83 6.6 3.34 10 3.69c15.82 1.65 29.66.49 41.03 1.05c2.7.13 7.65.48 7.88 3.63c.22 3.14-1.94 3.38-4.66 3.97c-4.05.91-8.32 2.49-8.62 6.68c-.17 2.34.6 5.73 4.67 7.43c4.57 1.93 12.37 1.23 15.82 1.72c3.74.53 18.08-.45 18.67 3.94c.46 3.45-7.97.24-7.97 8.94c0 5.89 10.22 5.88 14.74 6.6c3 .48 11.95.78 17.24-.02c3.78-.58 4.58-1.48 5.04-4.37");
}

.rc9bz3bqx {
  fill: var(--svg-color--7d7d7d, #7d7d7d);
  d: path("M8.59 109.28h111.49v19.87H8.59z");
}

.sf2-foj0k {
  d: path("M12.72 48.3h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-152, 0.152);
}

.sgczb9bgn {
  d: path("M19.56 106.69h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-565, 0.565);
}

.sjowh9mho {
  d: path("M12.72 44.06h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-217, 0.217);
}

.sm1d2jyaf {
  d: path("M12.72 20.03h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-587, 0.587);
}

.snch7td8z {
  fill: var(--svg-color--7d7d7d, #7d7d7d);
  d: path("M43.76 94.87H85.9v34.28H43.76z");
}

.swup-blog {
  d: path("M12.72 32.75h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-391, 0.391);
}

.t2-cz-fgw {
  d: path("M-18.84 57.3h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-543, 0.543);
}

.tb63m5b8m {
  d: path("M-18.84 73.27h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-261, 0.261);
}

.td43gdeof {
  d: path("M12.72 12.96h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-696, 0.696);
}

.tg0zlbbbx {
  d: path("M-18.84 81.87h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-109, 0.109);
}

.tk9e-gbss {
  d: path("M19.56 105.04h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-609, 0.609);
}

.tl4es0b_w {
  d: path("M19.56 114.09h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-37, 0.37);
}

.u-febf53a {
  d: path("M-18.84 83.1h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-087, 0.087);
}

.u0a13xbmj {
  d: path("M-18.84 79.41h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-152, 0.152);
}

.u6eey1b9v {
  d: path("M12.72 14.38h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-674, 0.674);
}

.u81y-6b9t {
  d: path("M19.56 98.46h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-783, 0.783);
}

.u9nz55blw {
  d: path("M12.72 10.14h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-739, 0.739);
}

.utf8gibpb {
  d: path("M12.72 38.4h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-304, 0.304);
}

.uzgrgubru {
  d: path("M-18.84 62.22h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-457, 0.457);
}

.v2eese03r {
  d: path("M12.72 52.54h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-087, 0.087);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vokmh9b4j {
  d: path("M-18.84 41.33h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-826, 0.826);
}

.vpd8gwbnl {
  d: path("M12.72 34.16h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-37, 0.37);
}

.vykqxg54v {
  d: path("M12.72 21.44h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-565, 0.565);
}

.w-6naubee {
  d: path("M19.56 102.58h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-674, 0.674);
}

.wbd7aonfb {
  d: path("M19.56 109.15h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x0_dbzbxv {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M93.83 72.95c0 1.37-1.12 2.5-2.49 2.5h-2.92c-1.37 0-2.49-1.12-2.49-2.5v-4.63c0-1.37 1.12-2.49 2.49-2.49h2.92c1.37 0 2.49 1.12 2.49 2.49zm19.49.91c0 .46-1.12 1.58-2.49 1.58h-2.92c-1.37 0-2.5-1.12-2.5-2.5v-4.63c0-1.37 1.13-2.49 2.5-2.49h2.92c1.37 0 2.49 1.12 2.49 1.58zm0 15.32c0 .46-1.12 1.58-2.49 1.58h-2.92c-1.37 0-2.5-1.12-2.5-2.49v-4.63c0-1.37 1.13-2.5 2.5-2.5h2.92c1.37 0 2.49 1.12 2.49 1.58zm-10.67 13.86c0 .46-1.12 1.58-2.49 1.58h-2.92c-1.37 0-2.5-1.12-2.5-2.49V97.5c0-1.37 1.12-2.5 2.5-2.5h2.92c1.37 0 2.49 1.12 2.49 1.58zm-79.24-.82c0 1.37-1.12 2.5-2.5 2.5H18a2.5 2.5 0 0 1-2.5-2.5v-4.63c0-1.37 1.12-2.49 2.5-2.49h2.91c1.37 0 2.5 1.12 2.5 2.49zm11.11 0c0 1.37-1.13 2.5-2.5 2.5h-2.91a2.5 2.5 0 0 1-2.5-2.5v-4.63c0-1.37 1.12-2.49 2.5-2.49h2.91c1.37 0 2.5 1.12 2.5 2.49zm11.11 0c0 1.37-1.13 2.5-2.5 2.5h-2.91a2.5 2.5 0 0 1-2.5-2.5v-4.63c0-1.37 1.12-2.49 2.5-2.49h2.91c1.37 0 2.5 1.12 2.5 2.49zM23.41 116.4c0 1.37-1.12 2.5-2.5 2.5H18a2.5 2.5 0 0 1-2.5-2.5v-4.63c0-1.37 1.12-2.49 2.5-2.49h2.91c1.37 0 2.5 1.12 2.5 2.49zm11.11 0c0 1.37-1.13 2.5-2.5 2.5h-2.91a2.5 2.5 0 0 1-2.5-2.5v-4.63c0-1.37 1.12-2.49 2.5-2.49h2.91c1.37 0 2.5 1.12 2.5 2.49zm22.22 0c0 1.37-1.13 2.5-2.5 2.5h-2.91a2.5 2.5 0 0 1-2.5-2.5v-4.63c0-1.37 1.12-2.49 2.5-2.49h2.91c1.37 0 2.5 1.12 2.5 2.49z");
}

.x8jlytbry {
  d: path("M12.72 18.62h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-609, 0.609);
}

.x9w5edcbk {
  d: path("M-18.84 80.64h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.xmf5cyevk {
  d: path("M-18.84 52.39h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-63, 0.63);
}

.xn2vo5bne {
  d: path("M12.72 36.99h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-326, 0.326);
}

.xyz4a5bzt {
  d: path("M-18.84 67.13h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-37, 0.37);
}

.y543irbme {
  d: path("M-18.84 32.73h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-978, 0.978);
}

.ya2uccb0l {
  d: path("M12.72 27.1h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-478, 0.478);
}

.ybvpn22jh {
  d: path("M-18.84 60.99h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-478, 0.478);
}

.ycyihab1q {
  d: path("M-18.84 45.02h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-761, 0.761);
}

.yk4tycc-x {
  d: path("M12.72 46.88h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-174, 0.174);
}

.yl_l2xbkv {
  d: path("M-18.84 74.5h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-239, 0.239);
}

.yp1sonbsb {
  d: path("M-18.84 75.73h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-217, 0.217);
}

.ypnqu4bru {
  d: path("M12.72 25.68h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yw-6iwbpt {
  d: path("M-18.84 68.36h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-348, 0.348);
}

.yxxhryjkc {
  d: path("M19.56 94.35h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-891, 0.891);
}

.z__xbejhs {
  d: path("M12.72 41.23h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-261, 0.261);
}

.z0cuqebnp {
  d: path("M-18.84 40.1h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-848, 0.848);
}

.zcn1s8c4k {
  d: path("M19.56 115.73h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-326, 0.326);
}

.zi_h2vylf {
  d: path("M-18.84 48.7h122.35v9.65H-18.84z");
  opacity: var(--svg-opacity--0-696, 0.696);
}

.zsm0x0bpl {
  d: path("M19.56 116.55h122.35v6.46H19.56z");
  opacity: var(--svg-opacity--0-304, 0.304);
}

.zt4klmb-r {
  d: path("M12.72 29.92h122.35v11.1H12.72z");
  opacity: var(--svg-opacity--0-435, 0.435);
}

</style>
