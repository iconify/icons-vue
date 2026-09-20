<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGod1LRclg)" class="g1u2fjb1g"/><path fill="url(#SVGasTyTc6N)" class="teu1d_tkf"/><path class="dvuf5dbvt"/><path fill="url(#SVGmYVCSbZl)" class="bw7mgrbxf"/><path class="bt4_fdb6s"/><path fill="url(#SVGNHCom2XB)" class="oybyo-2jr"/><path class="fkadnzhrp"/><path class="rv_m37bfm"/><path fill="url(#SVGPFLEBbDO)" class="hty68hbqx"/><path fill="url(#SVG8CbzSdIL)" class="tqyayw09p"/><path fill="url(#SVGCrgnrb9K)" class="z61ar9b8h"/><path fill="url(#SVGqtKAiP3f)" class="fh64y7bkl"/><path class="s8gq2obeo"/><path fill="url(#SVG3CGh8hSJ)" class="prshltbrn"/><path fill="url(#SVGPYMHCeQe)" class="ab242dppo"/><path class="zd10j8b4p"/><path fill="url(#SVG3X40occj)" class="j29x06e8h"/><path fill="url(#SVGZpt1KdcW)" class="pez9-bc6w"/><path class="b_n4hrb7v"/><path class="v3w3_8bls"/><path fill="url(#SVGeTad0WFT)" class="r6o1rzt7x"/><path class="cccmb4blb"/><path class="g0ea0uylt"/><path class="k0x7jkssh"/><path class="r_2ke1sxn"/><path class="ev5n9i_tq"/><path fill="url(#SVG708KkbPb)" class="rdfba5wqt"/><path class="j3k63lesw"/><path class="y9rdrpblq"/><path class="opl5s0yvd"/><path fill="url(#SVGvOz37bXS)" class="j9ew6d4xs"/><path fill="url(#SVGaAxZlSlb)" class="y1m241suv"/><path fill="url(#SVGUaw4EeOe)" class="zib3b6blq"/><path fill="url(#SVGs4ojWdqB)" class="v2n8aty2n"/><path fill="url(#SVGwTe6Fd5k)" class="usz1f0-0t"/><path class="pryimobth"/><path fill="url(#SVGCJS8bnLS)" class="ji00oubfq"/><path class="fa_zvx-vd"/></g><defs><linearGradient id="SVGod1LRclg" x1="19.747" x2="3.408" y1="4.993" y2="11.959" gradientUnits="userSpaceOnUse"><stop class="p9azygbpg"/><stop offset=".13" class="gts-a2bll"/><stop offset=".34" class="g0kpxcq9n"/><stop offset=".51" class="ir5d_dw-d"/><stop offset="1" class="c7x8cibnx"/></linearGradient><linearGradient id="SVGasTyTc6N" x1="14.118" x2="7.978" y1="8.362" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="j6xwapbni"/><stop offset=".25" class="n_9gckc2a"/><stop offset=".48" class="sc534obhl"/><stop offset=".78" class="irfq6qzvt"/><stop offset="1" class="hqsoeac0j"/></linearGradient><linearGradient id="SVGmYVCSbZl" x1="8.619" x2="11.725" y1="8.449" y2="16.811" gradientUnits="userSpaceOnUse"><stop class="j6xwapbni"/><stop offset=".25" class="n_9gckc2a"/><stop offset=".48" class="sc534obhl"/><stop offset=".78" class="irfq6qzvt"/><stop offset="1" class="hqsoeac0j"/></linearGradient><linearGradient id="SVGNHCom2XB" x1="10.959" x2="7.115" y1="7.017" y2="12.171" gradientUnits="userSpaceOnUse"><stop class="j6xwapbni"/><stop offset=".25" class="n_9gckc2a"/><stop offset=".48" class="sc534obhl"/><stop offset=".78" class="irfq6qzvt"/><stop offset="1" class="hqsoeac0j"/></linearGradient><linearGradient id="SVGPFLEBbDO" x1="6.892" x2="21.313" y1="5.695" y2="13.175" gradientUnits="userSpaceOnUse"><stop class="k_26bhbri"/><stop offset=".35" class="x5tpypb8c"/><stop offset=".63" class="tdjiqjc7d"/><stop offset="1" class="d84lftbgx"/></linearGradient><linearGradient id="SVG8CbzSdIL" x1="18.893" x2="10.98" y1="4.507" y2="14.263" gradientUnits="userSpaceOnUse"><stop class="d33yvbb6p"/><stop offset=".45" class="at77yrnkw"/><stop offset=".98" class="r3s95mb8n"/></linearGradient><linearGradient id="SVGCrgnrb9K" x1="4.793" x2="9.284" y1="5.038" y2="19.785" gradientUnits="userSpaceOnUse"><stop class="zmoj2kbvj"/><stop offset=".13" class="dw4b5sbir"/><stop offset=".34" class="fvp_q9g-e"/><stop offset=".51" class="jib6nyb-u"/><stop offset="1" class="xf93wwt2p"/></linearGradient><linearGradient id="SVGqtKAiP3f" x1="11.892" x2="11.141" y1="5.17" y2="19.678" gradientUnits="userSpaceOnUse"><stop class="wgtwfccct"/><stop offset=".26" class="s82pzd3_v"/><stop offset=".47" class="oebkzccuu"/><stop offset=".66" class="fnzv44qsr"/><stop offset=".98" class="iure3fjhn"/></linearGradient><linearGradient id="SVG3CGh8hSJ" x1="12.027" x2="12.027" y1="4.526" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="wgtwfccct"/><stop offset=".26" class="s82pzd3_v"/><stop offset=".57" class="oebkzccuu"/><stop offset=".76" class="fnzv44qsr"/><stop offset="1" class="iure3fjhn"/></linearGradient><linearGradient id="SVGPYMHCeQe" x1="12" x2="12" y1="4.526" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="j-8gvpbrh"/><stop offset=".32" class="vqabr5quw"/><stop offset="1" class="bfmp7k-xp"/></linearGradient><linearGradient id="SVG3X40occj" x1="5.19" x2="15.199" y1="16.675" y2="7.675" gradientUnits="userSpaceOnUse"><stop class="afr87ubye"/><stop offset=".17" class="oy5zeebpv"/><stop offset=".37" class="c927qmbzh"/><stop offset=".7" class="mrtlx4b8a"/><stop offset="1" class="pvnw0cczo"/></linearGradient><linearGradient id="SVGZpt1KdcW" x1="11.357" x2="15.134" y1="4.67" y2="18.435" gradientUnits="userSpaceOnUse"><stop class="wjwtdjc2i"/><stop offset=".09" class="sqocahbjl"/><stop offset=".22" class="cgs16obza"/><stop offset=".53" class="t2aihyqyn"/><stop offset="1" class="oshsx8u5o"/></linearGradient><linearGradient id="SVGeTad0WFT" x1="5.933" x2="20.141" y1="5.348" y2="6.86" gradientUnits="userSpaceOnUse"><stop class="b8mxppbkz"/><stop offset=".09" class="v9irpjb-f"/><stop offset=".32" class="khg_jbckx"/><stop offset=".55" class="l13cw2bme"/><stop offset=".88" class="zyznwhvzv"/><stop offset="1" class="julpz4b7h"/></linearGradient><linearGradient id="SVG708KkbPb" x1="11.893" x2="11.927" y1="4.528" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="i3jx6crwh"/><stop offset="1" class="pob2u_zli"/></linearGradient><linearGradient id="SVGvOz37bXS" x1="4" x2="19.372" y1="12" y2="14.081" gradientUnits="userSpaceOnUse"><stop class="ulxvtkpwj"/><stop offset="1" class="q7fw84b7j"/></linearGradient><linearGradient id="SVGaAxZlSlb" x1="12.021" x2="11.354" y1="4.526" y2="18.904" gradientUnits="userSpaceOnUse"><stop class="ehyjxac6i"/><stop offset=".88" class="ybf_liycz"/><stop offset="1" class="cl0vaewzu"/></linearGradient><linearGradient id="SVGUaw4EeOe" x1="5.931" x2="21.913" y1="5.342" y2="9.105" gradientUnits="userSpaceOnUse"><stop offset=".32" class="f_vic6iji"/><stop offset=".62" class="jl1al0b3h"/><stop offset="1" class="pi253rhbf"/></linearGradient><linearGradient id="SVGs4ojWdqB" x1="6.26" x2="18.779" y1="5.605" y2="16.483" gradientUnits="userSpaceOnUse"><stop class="sv83-4b_f"/><stop offset=".32" class="isrc1f5vd"/><stop offset=".62" class="ts6tj1b9q"/><stop offset="1" class="qjg8gygsp"/></linearGradient><linearGradient id="SVGwTe6Fd5k" x1="6.249" x2="18.711" y1="5.613" y2="16.45" gradientUnits="userSpaceOnUse"><stop class="vz6fch2yu"/><stop offset=".32" class="vzebq9b_s"/><stop offset=".62" class="nnjqm4vcc"/><stop offset="1" class="j90f2tb2j"/></linearGradient><linearGradient id="SVGCJS8bnLS" x1="12" x2="12" y1="4.526" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".49" class="tl2ewnbhe"/><stop offset="1" class="alt4wly_v"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gsts-background" /></template>
<style>
.ab242dppo {
  d: path("M4.435 14.488c.24 0 .435-.41.435-.917s-.195-.918-.435-.918s-.435.411-.435.918c0 .506.195.917.435.917");
}

.afr87ubye {
  stop-color: var(--svg-color--f68701, #f68701);
}

.alt4wly_v {
  stop-color: var(--svg-color--a8a8a8, #a8a8a8);
}

.at77yrnkw {
  stop-color: var(--svg-color--fdd500, #fdd500);
}

.b_n4hrb7v {
  fill: var(--svg-color--ce4f2f, #ce4f2f);
  d: path("M7.2 15.977c-.047-.204-.056-.946-.056-1.286c.359.227 1.513.68 3.262.657c1.744-.024 4.336-1.022 5.414-1.518l.434 1.03c-.737.568-2.884 1.727-5.56 1.864s-3.442-.44-3.494-.748");
}

.b8mxppbkz {
  stop-color: var(--svg-color--fb0e2d, #fb0e2d);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bfmp7k-xp {
  stop-color: var(--svg-color--ecb002, #ecb002);
}

.bt4_fdb6s {
  fill: var(--svg-color--591c00, #591c00);
  d: path("M19.564 4.9a.255.255 0 0 1-.123-.332c.09.02.237.104.123.331");
}

.bw7mgrbxf {
  d: path("M18.421 4.786c-.137.256 0 .379.085.407l1.073-.25c.137-.27-.042-.388-.146-.417z");
}

.c7x8cibnx {
  stop-color: var(--svg-color--7c2204, #7c2204);
}

.c927qmbzh {
  stop-color: var(--svg-color--e64809, #e64809);
}

.cccmb4blb {
  fill: var(--svg-color--fdfa03, #fdfa03);
  d: path("M15.178 10.445h-.436c-.094 0-.302.37-.35 1.15h2.738c.095-.105.236-.568 0-.89l.203-1.087c.067-.142.095-.435-.321-.459l-1.485-.085zm1.196 1.291h.7l-.176 1.206c-.033-.364-.175-1.111-.524-1.206m-.265-2.033l.728.028l-.114.776l-.817-.028z");
}

.cgs16obza {
  stop-color: var(--svg-color--ff9e01, #ff9e01);
}

.cl0vaewzu {
  stop-color: var(--svg-color--be6604, #be6604);
}

.d33yvbb6p {
  stop-color: var(--svg-color--894e02, #894e02);
}

.d84lftbgx {
  stop-color: var(--svg-color--b78407, #b78407);
}

.dvuf5dbvt {
  fill: var(--svg-color--591c00, #591c00);
  d: path("M14.917 6.782a.37.37 0 0 1 .434-.255c0 .123-.085.345-.435.255");
}

.dw4b5sbir {
  stop-color: var(--svg-color--e48801, #e48801);
}

.ehyjxac6i {
  stop-color: var(--svg-color--ffeb0c, #ffeb0c);
}

.ev5n9i_tq {
  fill: var(--svg-color--fdfa03, #fdfa03);
  d: path("M16.836 14.002c.118-2.062-.629-2.459-1.016-2.407c-.398.076-1.197.733-1.197 2.752c0 2.52.79 2.577.965 2.577c.17 0 1.106-.34 1.248-2.922");
}

.f_vic6iji {
  stop-color: var(--svg-color--ffa302, #ffa302);
}

.fa_zvx-vd {
  fill: var(--svg-color--0c0e0d, #0c0e0d);
  d: path("M11.54 8.417a.376.376 0 0 0 .379-.374a.376.376 0 0 0-.378-.373a.376.376 0 0 0-.378.373c0 .207.169.374.378.374");
}

.fh64y7bkl {
  d: path("m6.737 12.943l-2.27-.227v1.773l2.034.203c.146-.175.44-.596.44-.917s-.138-.69-.204-.832");
}

.fkadnzhrp {
  fill: var(--svg-color--591c00, #591c00);
  d: path("M19.844 9.789a.2.2 0 0 1 .003-.146a.2.2 0 0 1 .105-.1c.038.057.071.18-.108.246");
}

.fnzv44qsr {
  stop-color: var(--svg-color--e77209, #e77209);
}

.ft5dv1b6b {
  fill: none;
}

.fvp_q9g-e {
  stop-color: var(--svg-color--bd4707, #bd4707);
}

.g0ea0uylt {
  fill: var(--svg-color--e89200, #e89200);
  d: path("m15.933 9.189l-.345-.029l-.293 1.23h.496zm-1.073 2.293h-.35c0-.232.047-.832.232-.832c.189 0 .156.6.118.832m.232 0c.094-.275.037-.719 0-.832l1.98.113c.209.232.086.624 0 .719h-1.985z");
}

.g0kpxcq9n {
  stop-color: var(--svg-color--b5380a, #b5380a);
}

.g1u2fjb1g {
  d: path("M15.962 8.905c-.487.477-1.985 1.46-2.676 1.891l1.253 1.433c.629-.241 2.071-.804 2.794-1.15c.724-.344.729-.812.639-1.001c.283-.251.274-.72.236-.918a.66.66 0 0 0 .037-.753a.7.7 0 0 0-.183-.192c.127-.199.283-.686-.09-1.031c-.464-.43-1.395 1.116-2.005 1.721z");
}

.gts-a2bll {
  stop-color: var(--svg-color--d85a0a, #d85a0a);
}

.hqsoeac0j {
  stop-color: var(--svg-color--fbe008, #fbe008);
}

.hty68hbqx {
  d: path("M15.674 18.413c-.047-.156-1.106-.544-1.631-.714l.643-.402c.27.222.86.662 1.045.662c.236 0 .061-.402.35-.378c.293.033.061.576.35.832c.293.26.846.118.993.378c.113.203-.265.217-.473.199c.07.037.198.174.151.425c-.047.255-.756-.388-1.106-.742c.01.18-.02.548-.204.572c-.236.028-.061-.629-.118-.832");
}

.i3jx6crwh {
  stop-color: var(--svg-color--d76701, #d76701);
}

.ir5d_dw-d {
  stop-color: var(--svg-color--a83308, #a83308);
}

.irfq6qzvt {
  stop-color: var(--svg-color--ee8e06, #ee8e06);
}

.isrc1f5vd {
  stop-color: var(--svg-color--531200, #531200);
}

.iure3fjhn {
  stop-color: var(--svg-color--fca615, #fca615);
}

.j-8gvpbrh {
  stop-color: var(--svg-color--ffcd02, #ffcd02);
}

.j29x06e8h {
  d: path("M17.305 11.798c.113 1.04.061 3.451-1.078 4.785c-1.428 1.66-4.511 1.716-4.95 1.688c-.436-.029-3.727-.015-4.19-3.58a4 4 0 0 1 .047-1.304a.54.54 0 0 1-.34-.015c.175-.26 1.428-2.44 1.513-2.921c.09-.488-.142-1.636.147-2.492a1.43 1.43 0 0 1 1.163-.946c-.038-.137 0-.468.468-.718c.463-.251.756-.105.841 0l.062.52a.66.66 0 0 1 .61-.062v.459c.16.094.321.766.378 1.087a3.48 3.48 0 0 0 2.416 2.322h-.558c1.338.624 2.766 1.22 3.47 1.177");
}

.j3k63lesw {
  fill: var(--svg-color--facd02, #facd02);
  d: path("M12.236 13.314h-.52v2.062h.406c.185.123.591.373.757.373c.203 0 1.31-.26 1.371-1.489c.057-1.23-.875-1.29-1.286-1.319c-.326-.024-.615.236-.728.373");
}

.j6xwapbni {
  stop-color: var(--svg-color--ffdf01, #ffdf01);
}

.j90f2tb2j {
  stop-color: var(--svg-color--550601, #550601);
  stop-opacity: 0.4;
}

.j9ew6d4xs {
  d: path("M11.655 14.834c.24 0 .435-.231.435-.516c0-.284-.195-.515-.435-.515s-.435.23-.435.515s.194.516.435.516");
}

.ji00oubfq {
  d: path("M11.192 9.963c.658 0 1.19-.59 1.19-1.319c0-.728-.532-1.319-1.19-1.319c-.659 0-1.192.59-1.192 1.32c0 .728.534 1.318 1.191 1.318");
}

.jib6nyb-u {
  stop-color: var(--svg-color--9a3809, #9a3809);
}

.jl1al0b3h {
  stop-color: var(--svg-color--ffdb06, #ffdb06);
}

.julpz4b7h {
  stop-color: var(--svg-color--e40d2c, #e40d2c);
}

.k_26bhbri {
  stop-color: var(--svg-color--522100, #522100);
}

.k0x7jkssh {
  fill: var(--svg-color--feee05, #feee05);
  d: path("M15.849 11.595h-1.953c-.26.056-.822.633-.988 2.463c-.16 1.835.516 2.6.875 2.752l1.773.085l.293-5.295z");
}

.khg_jbckx {
  stop-color: var(--svg-color--e30a27, #e30a27);
}

.l13cw2bme {
  stop-color: var(--svg-color--c6061f, #c6061f);
}

.mrtlx4b8a {
  stop-color: var(--svg-color--e84608, #e84608);
}

.n_9gckc2a {
  stop-color: var(--svg-color--e88f02, #e88f02);
}

.nnjqm4vcc {
  stop-color: var(--svg-color--900b0c, #900b0c);
}

.oebkzccuu {
  stop-color: var(--svg-color--ffe309, #ffe309);
}

.opl5s0yvd {
  fill: var(--svg-color--ffd304, #ffd304);
  d: path("M11.688 15.405c.546 0 .989-.474.989-1.059s-.443-1.059-.989-1.059c-.545 0-.988.474-.988 1.06c0 .584.443 1.058.988 1.058");
}

.oshsx8u5o {
  stop-color: var(--svg-color--ffb93d, #ffb93d);
}

.oy5zeebpv {
  stop-color: var(--svg-color--ef6205, #ef6205);
}

.oybyo-2jr {
  d: path("M19.272 9.14c-.208.076-.198.213-.165.27l.723.412c.217-.08.18-.237.137-.308z");
}

.p9azygbpg {
  stop-color: var(--svg-color--ef8807, #ef8807);
}

.pez9-bc6w {
  d: path("M10.085 6.266c.463-.25.756-.104.841 0l.062.52a.66.66 0 0 1 .61-.061v.458c.16.095.321.766.378 1.088a3.48 3.48 0 0 0 2.416 2.321h-1.078l.615 1.036l-1.107-.085v1.404l-1.75-.86l-.52 2.033l-1.777-1.433l-.96 1.234l-.293-.974c-.16.482-.553.468-.728.402c.175-.26 1.428-2.44 1.513-2.922c.09-.487-.142-1.636.147-2.497a1.43 1.43 0 0 1 1.163-.945c-.038-.133 0-.464.468-.714z");
}

.pi253rhbf {
  stop-color: var(--svg-color--a92c0e, #a92c0e);
}

.pob2u_zli {
  stop-color: var(--svg-color--7c0e07, #7c0e07);
}

.prshltbrn {
  d: path("m7.263 12.653l-.993.09c.118.114.368.468.44.974c.066.501-.303.936-.497 1.088l.785.17c.581-.426.553-.77.581-1.258a1.9 1.9 0 0 0-.316-1.064");
}

.pryimobth {
  fill: var(--svg-color--9e260d, #9e260d);
  d: path("M11.22 10.304c.738 0 1.337-.692 1.337-1.546s-.599-1.546-1.338-1.546s-1.338.692-1.338 1.546s.6 1.546 1.338 1.546");
}

.pvnw0cczo {
  stop-color: var(--svg-color--ee5205, #ee5205);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q7fw84b7j {
  stop-color: var(--svg-color--230100, #230100);
}

.qjg8gygsp {
  stop-color: var(--svg-color--000205, #000205);
}

.r_2ke1sxn {
  fill: var(--svg-color--f98d08, #f98d08);
  d: path("M15.295 11.826h-1.31a.68.68 0 0 0-.378.426h1.372c.09-.137.25-.34.316-.426m-.581.771h-1.282c-.094.142-.321.71-.434 1.834a3.07 3.07 0 0 0 .813 2.35l1.484.057c-.614-.544-.643-.917-.756-1.948c-.095-.823.075-1.872.175-2.293");
}

.r3s95mb8n {
  stop-color: var(--svg-color--bb7402, #bb7402);
}

.r6o1rzt7x {
  d: path("M9.589 6.952c-.629.024-1.017.662-1.135.974c.218-.397.7-.397.993-.397c1.22 0 2.392.851 2.936 1.461c.865.113 1.29.468 1.4.629v-.426l.175-.203c-.303-.118-.44-.298-.469-.378c.558-.109.899.052.993.146a.68.68 0 0 1 0-.714c-.903-.203-1.427-.028-1.806 0c-.378.029-.406.256-.818-.373c-.326-.506-1.645-.686-2.27-.719");
}

.rdfba5wqt {
  d: path("M15.858 12.77c-.123.03-.53.322-.525 1.447c0 .72.109 1.055.208 1.21c.047.072.09.105.118.12q.03.015.066.013c.02-.005.119-.037.237-.222c.127-.208.265-.6.302-1.329c.029-.581-.061-.898-.16-1.068c-.095-.156-.194-.175-.246-.17m.468.02c.142.236.227.624.198 1.229a3.1 3.1 0 0 1-.345 1.475c-.165.265-.35.35-.454.35c-.033 0-.094 0-.17-.038a.57.57 0 0 1-.236-.222c-.137-.222-.246-.629-.246-1.367c-.01-1.181.43-1.659.737-1.725h.01c.165-.029.364.052.51.298z");
}

.rv_m37bfm {
  fill: var(--svg-color--b20c0c, #b20c0c);
  d: path("M7.815 17.383c-.142-.298.308-.469.553-.516l.814.634c-.398.085-1.23.18-1.372-.119z");
}

.s82pzd3_v {
  stop-color: var(--svg-color--ec8a01, #ec8a01);
}

.s8gq2obeo {
  fill: var(--svg-color--fad502, #fad502);
  d: path("M6.766 12.682c.35-1.007.979-1.087 1.253-1.002l-.672 1.262zm.581 3.154c-.581-.208-.865-.832-.931-1.116l.875-.142z");
}

.sc534obhl {
  stop-color: var(--svg-color--ffe103, #ffe103);
}

.sqocahbjl {
  stop-color: var(--svg-color--f24b13, #f24b13);
}

.sv83-4b_f {
  stop-color: var(--svg-color--853301, #853301);
}

.t2aihyqyn {
  stop-color: var(--svg-color--ff9602, #ff9602);
}

.tdjiqjc7d {
  stop-color: var(--svg-color--ffd50a, #ffd50a);
}

.teu1d_tkf {
  d: path("M14.77 5.178c-.397-.113-.534.104-.553.227l.643 1.404c.416.114.544-.16.554-.312l-.644-1.323z");
}

.tl2ewnbhe {
  stop-color: var(--svg-color--dbd9da, #dbd9da);
}

.tqyayw09p {
  d: path("M7.465 17.585c.095-.255.308-.298.407-.284l.378.142c-.165.047-.52.156-.614.227c-.114.085-.057.284-.057.572c0 .284.061.232.293.459c.236.231.142.345-.118.43s-.638-.629-.96-.889c-.321-.255-.756-.17-1.016-.515c-.265-.346.463-.346.784-.284c.322.057.492.567.667.629c.175.057.118-.175.236-.487");
}

.ts6tj1b9q {
  stop-color: var(--svg-color--010000, #010000);
}

.ulxvtkpwj {
  stop-color: var(--svg-color--933905, #933905);
}

.usz1f0-0t {
  d: path("M8.804 10.134c-.255-.024-.416.317-.468.487a.95.95 0 0 1 .411-.114c.161 0 .336.327.407.488a.33.33 0 0 0 .26-.142c.07-.118.07-.336.061-.43a1.6 1.6 0 0 0-.671-.284z");
}

.v2n8aty2n {
  d: path("M9.239 8.791c-.095-.345-.463-.453-.638-.463l.141 2.922c.119.024.421.203.558.289c.44-.048.36-.766.26-1.116a26 26 0 0 0-.321-1.636z");
}

.v3w3_8bls {
  fill: var(--svg-color--9d2b13, #9d2b13);
  d: path("M9.296 15.665a3.96 3.96 0 0 1-1.977-.402v.804c.653.411 1.688.473 2.128.458c.274-.302.014-.7-.147-.86zm1.314.86c-.284-.279-.156-.766-.061-.978c.629.07 2.477-.331 3.319-.544l.236.86c-.865.435-2.69.62-3.499.662z");
}

.v9irpjb-f {
  stop-color: var(--svg-color--fe2e4e, #fe2e4e);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vqabr5quw {
  stop-color: var(--svg-color--ffd108, #ffd108);
}

.vz6fch2yu {
  stop-color: var(--svg-color--ff7887, #ff7887);
}

.vzebq9b_s {
  stop-color: var(--svg-color--c52726, #c52726);
}

.wgtwfccct {
  stop-color: var(--svg-color--fdde06, #fdde06);
}

.wjwtdjc2i {
  stop-color: var(--svg-color--fe5b16, #fe5b16);
}

.x5tpypb8c {
  stop-color: var(--svg-color--fed308, #fed308);
}

.xf93wwt2p {
  stop-color: var(--svg-color--c53d09, #c53d09);
}

.y1m241suv {
  d: path("M14.104 14.29c-.047-.899-.662-1.121-.964-1.121c.246.095.742.454.79 1.12c.047.662-.662 1.173-1.022 1.348c.416-.08 1.239-.454 1.196-1.348");
}

.y9rdrpblq {
  fill: var(--svg-color--ffa200, #ffa200);
  d: path("M13.342 13.458h-1.016c.208.07.416.373.496.52h.899c-.048-.35-.27-.492-.379-.52m-.203 1.806l-.898-.057c.094-.127.316-.42.435-.605c.141-.227.378-.284.666-.255c.293.028.44.17.293.425c-.118.208-.378.416-.496.492");
}

.ybf_liycz {
  stop-color: var(--svg-color--ca9307, #ca9307);
}

.z61ar9b8h {
  d: path("m6.241 7.727l2.388 3.64l-.96 1.031c-1.4-.544-1.778-1.518-1.863-1.976a.57.57 0 0 1 .289-.634a1.3 1.3 0 0 1-.289-.487c-.07-.227.029-.496.085-.6c-.141-.346-.26-.974-.085-1.173c.142-.16.35.066.435.199");
}

.zd10j8b4p {
  fill: var(--svg-color--751509, #751509);
  d: path("M4.435 14.086c.112 0 .203-.23.203-.515s-.091-.515-.203-.515s-.204.23-.204.515c0 .284.091.515.204.515");
}

.zib3b6blq {
  d: path("M9.092 7.813c-.321 0-.5.283-.548.43a.2.2 0 0 1 .057.142c.019.917.047 2.77.028 2.836c-.024.071-.142.048-.203.029c.104.184.406.548.756.548s.615-.317.615-.487l-.151-2.955c0-.369-.346-.543-.554-.543");
}

.zmoj2kbvj {
  stop-color: var(--svg-color--fff505, #fff505);
}

.zyznwhvzv {
  stop-color: var(--svg-color--ff314d, #ff314d);
}

</style>
