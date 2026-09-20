<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG4m9HsccG)" class="bq_hunj5b"/><path fill="url(#SVGcydH6dUf)" class="w8l2kl27f"/><path class="c8ju-8bhr"/><path class="hrf98gm7f"/><path fill="url(#SVGjNIU4dGV)" class="i-5ddsbou"/><path fill="url(#SVGpXF1lcrk)" class="fko-o2bpw"/><path fill="url(#SVG4rd91CeI)" class="gs_v3-i_b"/><path fill="url(#SVGLv5ZCPxs)" class="uuoms_8-y"/><path fill="url(#SVG54O2Hbba)" class="y32iz-bcp"/><path class="wtr9jie9x"/><path class="x_b1lmkug"/><path fill="url(#SVGDFoM1c8U)" class="oagg3i8rj"/><path fill="url(#SVGv0x6PeWi)" class="tldabebcn"/><path fill="url(#SVGTLK6ObCo)" class="zbo8t_bdl"/><path fill="url(#SVGEBrEYdmk)" class="qkh8v9u7j"/><path fill="url(#SVGfmJ7AdiT)" class="rfpz_ruou"/><path class="v33q5wbfb"/><path class="qvhvdvbom"/><path fill="url(#SVGMGa3KUoV)" class="nslfc7bua"/><path class="ym583m23p"/><path class="ckvtppbbj"/><path fill="url(#SVGBVZgtAGV)" class="cy5rjy-jc"/><path class="b9gei4b0d"/><path fill="url(#SVGz5D8tZsI)" class="c3zhivkkl"/><path fill="url(#SVGi5cBkc0H)" class="hgml7g8me"/><path fill="url(#SVGMDBiZdEK)" class="qywwj7hhs"/><path fill="url(#SVG9QYsIdsC)" clip-rule="evenodd" class="jo9wy9e6t"/></g><defs><linearGradient id="SVG4m9HsccG" x1="15.816" x2="12.451" y1="11.997" y2="11.997" gradientUnits="userSpaceOnUse"><stop offset=".42" class="pzq9w9r-z"/><stop offset=".56" class="eztjh12zh"/><stop offset=".64" class="j1z_bd6zn"/><stop offset=".89" class="pah8wbbim"/><stop offset="1" class="wu31gdcmy"/></linearGradient><linearGradient id="SVGcydH6dUf" x1="16.211" x2="12.422" y1="10.683" y2="10.683" gradientUnits="userSpaceOnUse"><stop offset=".27" class="g0lzk0d0p"/><stop offset=".42" class="dyly8dirg"/><stop offset=".67" class="llsznpb4g"/></linearGradient><linearGradient id="SVGjNIU4dGV" x1="5.879" x2="5.879" y1="13.393" y2="17.052" gradientUnits="userSpaceOnUse"><stop class="lc1cjybsp"/><stop offset="1" class="bz-cjybhr"/></linearGradient><linearGradient id="SVGpXF1lcrk" x1="5.087" x2="5.087" y1="10.965" y2="13.925" gradientUnits="userSpaceOnUse"><stop class="i247-56py"/><stop offset="1" class="dfwpml94h"/></linearGradient><linearGradient id="SVG4rd91CeI" x1="6.997" x2="6.997" y1="11.856" y2="17.052" gradientUnits="userSpaceOnUse"><stop class="jga12jetw"/><stop offset="1" class="k3ekmu1zq"/></linearGradient><linearGradient id="SVGLv5ZCPxs" x1="5.423" x2="5.423" y1="13.988" y2="16.898" gradientUnits="userSpaceOnUse"><stop class="odhqnn32q"/><stop offset="1" class="q6r8l7blc"/></linearGradient><linearGradient id="SVG54O2Hbba" x1="6.203" x2="6.313" y1="9.634" y2="11.352" gradientUnits="userSpaceOnUse"><stop offset=".08" class="xsdc5kbga"/><stop offset=".15" class="o2s8vwbmy"/><stop offset=".42" class="jr_2a2mie"/></linearGradient><linearGradient id="SVGDFoM1c8U" x1="6.657" x2="5.95" y1="10.127" y2="10.796" gradientUnits="userSpaceOnUse"><stop class="irk2pjhja"/><stop offset=".32" class="ia3ol-mxd"/><stop offset=".53" class="fgrimybvd"/><stop offset=".72" class="b2dyaabkp"/><stop offset="1" class="e9_yoi2gg"/></linearGradient><linearGradient id="SVGv0x6PeWi" x1="4.594" x2="5.525" y1="11.171" y2="11.226" gradientUnits="userSpaceOnUse"><stop class="l7aydfiyl"/><stop offset="1" class="cvbkfeb3r"/></linearGradient><linearGradient id="SVGTLK6ObCo" x1="7.184" x2="8.586" y1="11.146" y2="11.281" gradientUnits="userSpaceOnUse"><stop class="l7aydfiyl"/><stop offset="1" class="cvbkfeb3r"/></linearGradient><linearGradient id="SVGEBrEYdmk" x1="4.754" x2="4.519" y1="9.951" y2="11.323" gradientUnits="userSpaceOnUse"><stop offset=".31" class="g1b6akb_k"/><stop offset="1" class="n_77cjbij"/></linearGradient><linearGradient id="SVGfmJ7AdiT" x1="10.265" x2="10.265" y1="9.846" y2="13.686" gradientUnits="userSpaceOnUse"><stop offset=".09" class="oli1qbc6g"/><stop offset=".26" class="rholo2byn"/><stop offset=".43" class="affxs5b2m"/><stop offset=".61" class="qfw73ibsw"/><stop offset=".76" class="odgoljv5n"/><stop offset=".93" class="rzwbe1teq"/></linearGradient><linearGradient id="SVGMGa3KUoV" x1="18.265" x2="18.265" y1="9.846" y2="13.686" gradientUnits="userSpaceOnUse"><stop offset=".09" class="oli1qbc6g"/><stop offset=".26" class="rholo2byn"/><stop offset=".43" class="affxs5b2m"/><stop offset=".61" class="qfw73ibsw"/><stop offset=".76" class="odgoljv5n"/><stop offset=".93" class="rzwbe1teq"/></linearGradient><linearGradient id="SVGBVZgtAGV" x1="12.842" x2="12.842" y1="14.282" y2="16.875" gradientUnits="userSpaceOnUse"><stop offset=".54" class="g_f1mcawx"/><stop offset=".66" class="uik8v9b0b"/></linearGradient><linearGradient id="SVGz5D8tZsI" x1="9.684" x2="9.684" y1="14.527" y2="16.632" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><linearGradient id="SVGi5cBkc0H" x1="11.578" x2="11.578" y1="14.527" y2="16.632" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><linearGradient id="SVGMDBiZdEK" x1="13.896" x2="13.896" y1="14.527" y2="16.632" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><linearGradient id="SVG9QYsIdsC" x1="16.215" x2="16.215" y1="14.527" y2="16.632" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fara-background" /></template>
<style>
.affxs5b2m {
  stop-color: var(--svg-color--ccc8c4, #ccc8c4);
}

.b2dyaabkp {
  stop-color: var(--svg-color--6c0425, #6c0425);
}

.b9gei4b0d {
  fill: var(--svg-color--2c1f18, #2c1f18);
  d: path("M7.959 15.878v-.8l.791-.8h8.185l.792.8v.8l-1.087.998H9.045z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bq_hunj5b {
  d: path("M12.422 13.517v-3.78l.408.1l.543 1.024h2.72l-.151.9a2.3 2.3 0 0 0-.973-.269c-.396 0-.745.257-.871.387v1.23l-.27.215l-1.12.362z");
}

.bz-cjybhr {
  stop-color: var(--svg-color--b9b1ab, #b9b1ab);
}

.c3zhivkkl {
  d: path("M9.473 14.527h-.42v2.105h1.262v-.421h-.842z");
}

.c8ju-8bhr {
  fill: var(--svg-color--bcbbb9, #bcbbb9);
  d: path("M12.666 13.12V9.848l.336-.084h.72l.21.084v.615h.456l.644-.703h.758l.155.219v1.3l-.16.17c-.075-.09-.34-.274-.8-.274c-.66 0-.972.408-1.052.61v1.07l-.935.429l-.332-.168z");
}

.ckvtppbbj {
  fill: var(--svg-color--bcbbb9, #bcbbb9);
  d: path("M16.837 9.895v.67c.085-.06.363-.173.805-.173c.56 0 .8.168.8.61c0 .438-.24.518-.8.623c-.442.085-.653.316-.7.422v1.082c.022.05.085.151.144.151c.425-.219 1.92-.194 2.614-.151v-2.784c0-.219-.467-.715-1.498-.715c-.83 0-1.255.172-1.365.26z");
}

.cvbkfeb3r {
  stop-color: var(--svg-color--c99f4b, #c99f4b);
}

.cy5rjy-jc {
  d: path("m7.79 15.002l.887-.897h8.329l.888.897v.955l-1.191 1.095H8.98l-1.192-1.095z");
}

.dfwpml94h {
  stop-color: var(--svg-color--a4a5a7, #a4a5a7);
}

.dyly8dirg {
  stop-color: var(--svg-color--88857c, #88857c);
}

.e9_yoi2gg {
  stop-color: var(--svg-color--fd67b4, #fd67b4);
}

.eztjh12zh {
  stop-color: var(--svg-color--f7f4ef, #f7f4ef);
}

.fgrimybvd {
  stop-color: var(--svg-color--73001e, #73001e);
}

.fko-o2bpw {
  d: path("M5.34 10.965c.151.273.345.766.345 1.33c0 .695-.522 1.377-.775 1.63h-.42l.155-.224c.316-.442.606-.934.619-1.456c.008-.236.004-.48-.156-.725c0-.033.017-.063.038-.1c.046-.085.118-.207.072-.455h.126z");
}

.ft5dv1b6b {
  fill: none;
}

.g_f1mcawx {
  stop-color: var(--svg-color--281c1e, #281c1e);
}

.g0lzk0d0p {
  stop-color: var(--svg-color--f3f3f3, #f3f3f3);
}

.g1b6akb_k {
  stop-color: var(--svg-color--6b3b04, #6b3b04);
}

.gs_v3-i_b {
  d: path("m7.506 11.856l-.56 1.12c0 .918.038 3.045-.59 4.063l.01.013c.63-.77 1.262-2.644 1.262-3.47c0-.42-.058-1.115-.122-1.726");
}

.hgml7g8me {
  d: path("m11.342 14.527l-.606 2.105h.476l.366-1.28l.366 1.28h.476l-.606-2.105z");
}

.hrf98gm7f {
  fill: var(--svg-color--c6c6c6, #c6c6c6);
  d: path("M7.411 10.965h-2.19c.06.362-.113.454-.113.555c.598.906-.126 1.71-.602 2.409c1.739 1.225 1.777 2.917 1.86 3.124c.632-.77 1.264-2.644 1.264-3.47c0-.66-.147-2.02-.223-2.618z");
}

.i-5ddsbou {
  d: path("m6.99 15.957l.261-1.617c-.193-.32-.682-1.078-1.073-1.078c-.392 0-1.01.48-1.268.657h-.404l-.004.009a4.34 4.34 0 0 1 1.823 2.939q.014.094.042.185c.22-.265.434-.661.628-1.095z");
}

.i247-56py {
  stop-color: var(--svg-color--7c8280, #7c8280);
}

.ia3ol-mxd {
  stop-color: var(--svg-color--cb7493, #cb7493);
}

.irk2pjhja {
  stop-color: var(--svg-color--eca0b2, #eca0b2);
}

.j1z_bd6zn {
  stop-color: var(--svg-color--af7239, #af7239);
}

.jga12jetw {
  stop-color: var(--svg-color--e8e8ed, #e8e8ed);
}

.jo9wy9e6t {
  fill-rule: evenodd;
  d: path("M16.005 14.527h-.636v2.105h.636a1.052 1.052 0 0 0 0-2.105m-.005.42h-.21v1.264H16a.631.631 0 1 0 0-1.263");
}

.jr_2a2mie {
  stop-color: var(--svg-color--8c5012, #8c5012);
}

.jr_d1qboy {
  stop-color: var(--svg-color--d7922b, #d7922b);
}

.k3ekmu1zq {
  stop-color: var(--svg-color--f3f5ea, #f3f5ea);
}

.l7aydfiyl {
  stop-color: var(--svg-color--896322, #896322);
}

.lc1cjybsp {
  stop-color: var(--svg-color--bfbfbf, #bfbfbf);
}

.lg92gcczw {
  stop-color: var(--svg-color--dab15f, #dab15f);
}

.llsznpb4g {
  stop-color: var(--svg-color--cecac7, #cecac7);
}

.n_77cjbij {
  stop-color: var(--svg-color--c3942c, #c3942c);
}

.nslfc7bua {
  d: path("M16.632 10.823v-.977l3.023.139l.244 2.067l-.11 1.47c-.126-.047-.589-.144-1.418-.144c-.826 0-1.335.207-1.487.308l-.252-.24v-1.394c.046-.114.252-.37.72-.493c.585-.151.854-.311.854-.505c0-.19-.105-.37-.614-.37c-.409 0-.674.185-.758.277z");
}

.o2s8vwbmy {
  stop-color: var(--svg-color--9d7126, #9d7126);
}

.oagg3i8rj {
  d: path("m6.948 10.417l-.7-.522l-.563.682l.711.581z");
}

.odgoljv5n {
  stop-color: var(--svg-color--79787d, #79787d);
}

.odhqnn32q {
  stop-color: var(--svg-color--7f7366, #7f7366);
}

.oli1qbc6g {
  stop-color: var(--svg-color--7d7975, #7d7975);
}

.pah8wbbim {
  stop-color: var(--svg-color--896d57, #896d57);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pzq9w9r-z {
  stop-color: var(--svg-color--af764b, #af764b);
}

.q6r8l7blc {
  stop-color: var(--svg-color--c2a963, #c2a963);
}

.qfw73ibsw {
  stop-color: var(--svg-color--85867b, #85867b);
}

.qkh8v9u7j {
  d: path("m4.535 11.26l.308-.564l-.838-.661c.042.484.32.956.53 1.22z");
}

.qvhvdvbom {
  fill: var(--svg-color--bcbbb9, #bcbbb9);
  d: path("M8.839 9.895v.67c.084-.06.362-.173.804-.173c.56 0 .8.168.8.61c0 .438-.24.518-.8.623c-.442.085-.653.316-.699.422v1.082c.021.05.084.151.143.151c.426-.219 1.92-.194 2.615-.151v-2.784c0-.219-.467-.715-1.499-.715c-.83 0-1.255.172-1.364.26z");
}

.qywwj7hhs {
  d: path("m13.256 14.527l1.271 1.162v-1.162h.421v2.105h-.341l-1.343-1.217v1.217h-.421v-2.105z");
}

.rdk0dpevl {
  stop-color: var(--svg-color--a47316, #a47316);
}

.rfpz_ruou {
  d: path("M8.632 10.823v-.977l3.023.139l.244 2.067l-.11 1.47c-.126-.047-.589-.144-1.418-.144c-.825 0-1.335.207-1.487.308l-.252-.24v-1.394c.046-.114.252-.37.72-.493c.585-.151.854-.311.854-.505c0-.19-.105-.37-.614-.37c-.409 0-.674.185-.758.277z");
}

.rholo2byn {
  stop-color: var(--svg-color--bb802d, #bb802d);
}

.rzwbe1teq {
  stop-color: var(--svg-color--a9814e, #a9814e);
}

.tldabebcn {
  d: path("M5.525 11.327c.008-.24-.059-.59-.404-.59c-.295 0-.455.32-.522.598l.012.017c.076-.105.266-.311.447-.311c.176 0 .374.21.45.311l.017-.021z");
}

.uik8v9b0b {
  stop-color: var(--svg-color--70614a, #70614a);
}

.uuoms_8-y {
  d: path("M6.329 16.898a3.4 3.4 0 0 0-1.415-2.973h-.43a4.56 4.56 0 0 1 1.84 2.952v.02z");
}

.v33q5wbfb {
  fill: var(--svg-color--eeeae9, #eeeae9);
  d: path("M9.474 9.473c-.522 0-.779.245-.842.367l1.907.547l1.065 2.455l.19.644l.206-.181v-2.922c0-.53-.551-.83-.825-.91z");
}

.w8l2kl27f {
  d: path("m12.788 9.92l-.366-.193l.139-.134h1.347l.181.24v.517l.783-.757h1.129l.21.324v1.515l-.27.325l-.155-.325l-.278-.589l-1.54-.219l-1.18-.707z");
}

.wtr9jie9x {
  fill: var(--svg-color--776e5f, #776e5f);
  d: path("M7.218 6.947c-.22 0-.598.312-.758.463l.703.725c.21-.127.64-.421.64-.632c0-.261-.311-.556-.585-.556");
}

.wu31gdcmy {
  stop-color: var(--svg-color--7a7975, #7a7975);
}

.x_b1lmkug {
  fill: var(--svg-color--614108, #614108);
  d: path("m7.369 8.295l-.906-.926l-.618.623l.126.118l-.126.181h-.16v1.604c.244-.03.842-.117 1.28-.21c-.047-.969.252-1.335.404-1.394z");
}

.xsdc5kbga {
  stop-color: var(--svg-color--e1c08d, #e1c08d);
}

.y32iz-bcp {
  d: path("M6.174 9.744a4.9 4.9 0 0 1-2.148-.085c-.143.67.333 1.407.59 1.693c.071-.122.26-.366.442-.366c.177 0 .375.244.45.366c.06-.105.295-.312.775-.312c.476 0 .737.186.808.278c.106-.134.405-.408.733-.408c.409 0 .67.303.809.442c-.093-1.916-1.234-1.827-2.46-1.608");
}

.ym583m23p {
  fill: var(--svg-color--eeeae9, #eeeae9);
  d: path("M17.474 9.473c-.522 0-.78.245-.842.367l1.907.547l1.065 2.455l.19.644l.206-.181v-2.922c0-.53-.552-.83-.825-.91z");
}

.zbo8t_bdl {
  d: path("M8.59 11.314c-.084-.227-.316-.576-.695-.576c-.307 0-.568.273-.711.484c.143-.127.379-.274.64-.274c.37 0 .619.227.766.362z");
}

</style>
