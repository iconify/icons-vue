<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedAstr0)" class="r268qqbxu"/><path fill="url(#tokenBrandedAstrj)" class="uo5na3ink"/><path class="injnfwz3r"/><path fill="url(#tokenBrandedAstrk)" class="b_25ueb0t"/><path fill="url(#tokenBrandedAstr1)" class="qk-klebel"/><path fill="url(#tokenBrandedAstrl)" class="khggs1b5f"/><path class="hyuo6b01r"/><path fill="url(#tokenBrandedAstrm)" class="ms3c_6zov"/><path fill="url(#tokenBrandedAstr2)" class="ca61j54nb"/><path fill="url(#tokenBrandedAstrn)" class="zier6v7pd"/><path class="quy2khbta"/><path fill="url(#tokenBrandedAstro)" class="hbc89wqwt"/><path fill="url(#tokenBrandedAstr3)" class="ghqj5bc6h"/><path fill="url(#tokenBrandedAstr4)" class="c3xy9j_fj"/><path fill="url(#tokenBrandedAstr5)" class="y8z2ufqdv"/><path fill="url(#tokenBrandedAstr6)" class="gmhrctb-a"/><path fill="url(#tokenBrandedAstr7)" class="nf7blgbou"/><path fill="url(#tokenBrandedAstr8)" class="d-taosbnt"/><path fill="url(#tokenBrandedAstr9)" class="kryeveeeq"/><path fill="url(#tokenBrandedAstra)" class="cwggqqbtd"/><path fill="url(#tokenBrandedAstrb)" class="vul7kvb-z"/><path fill="url(#tokenBrandedAstrc)" class="z7h49bsez"/><path fill="url(#tokenBrandedAstrd)" class="to_028fru"/><path fill="url(#tokenBrandedAstre)" class="wxsouifcl"/><path fill="url(#tokenBrandedAstrf)" class="ppfy-3jig"/><path fill="url(#tokenBrandedAstrg)" class="t4nmu4h1z"/><path fill="url(#tokenBrandedAstrh)" class="j6x6cuh2u"/><path fill="url(#tokenBrandedAstri)" class="dawca5oxo"/><defs><linearGradient id="tokenBrandedAstr0" x1="5.177" x2="17.927" y1="18.825" y2="6.074" gradientUnits="userSpaceOnUse"><stop class="zgkm01wcd"/><stop offset=".21" class="i6ngiacan"/><stop offset=".46" class="ttplkd_yd"/><stop offset=".77" class="nwchjeb5f"/><stop offset="1" class="c22tdqbtu"/></linearGradient><linearGradient id="tokenBrandedAstr1" x1="5.911" x2="8.044" y1="16.655" y2="16.626" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr2" x1="19.077" x2="17.985" y1="14.945" y2="13.113" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr3" x1="11.014" x2="9.973" y1="4.397" y2="6.259" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr4" x1="11.478" x2="8.219" y1="3.453" y2="4.399" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr5" x1="5.321" x2="8.044" y1="15.877" y2="18.72" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr6" x1="19.942" x2="20.891" y1="15.448" y2="12.566" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr7" x1="12.962" x2="17.328" y1="5.101" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr8" x1="17.496" x2="14.448" y1="16.282" y2="19.563" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstr9" x1="5.545" x2="4.229" y1="14.619" y2="10.337" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstra" x1="13.915" x2="12.533" y1="6.712" y2="8.094" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstrb" x1="6.464" x2="8.352" y1="12.986" y2="13.491" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstrc" x1="15.62" x2="15.115" y1="16.301" y2="14.413" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstrd" x1="12.749" x2="13.577" y1="14.622" y2="13.478" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstre" x1="9.894" x2="8.235" y1="14.127" y2="14.917" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstrf" x1="9.293" x2="9.805" y1="11.366" y2="12.432" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstrg" x1="11.68" x2="11.324" y1="8.073" y2="6.85" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstrh" x1="15.511" x2="16.536" y1="13.678" y2="13.916" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="tokenBrandedAstri" x1="13.899" x2="12.595" y1="10.211" y2="9.973" gradientUnits="userSpaceOnUse"><stop class="wavkffbjb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><radialGradient id="tokenBrandedAstrj" cx="0" cy="0" r="1" gradientTransform="matrix(3.80091 0 0 3.80092 14.85 9.975)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="tokenBrandedAstrk" cx="0" cy="0" r="1" gradientTransform="translate(9.231 17.027)scale(2.21247)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="tokenBrandedAstrl" cx="0" cy="0" r="1" gradientTransform="rotate(-120 7.456 2.724)scale(3.80092)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="tokenBrandedAstrm" cx="0" cy="0" r="1" gradientTransform="rotate(-120 12.3 .82)scale(2.21247)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="tokenBrandedAstrn" cx="0" cy="0" r="1" gradientTransform="rotate(120 1.657 11.158)scale(3.80092)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="tokenBrandedAstro" cx="0" cy="0" r="1" gradientTransform="rotate(120 2.47 6.15)scale(2.21247)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:astr" /></template>
<style>
.b_25ueb0t {
  d: path("M11.423 16.52q-.134-.105-.263-.212c-1.411.59-3.367.958-5.312.508q.478.612 1.064 1.115c1.897.258 3.72-.343 4.963-1.083a12 12 0 0 1-.452-.329");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.c22tdqbtu {
  stop-color: var(--svg-color--0ae2ff, #0AE2FF);
}

.c3xy9j_fj {
  d: path("M11.321 2.023a9.96 9.96 0 0 0-6.835 3.382l-.038.043c.327.324 1.398.964 1.831 1.232a7.8 7.8 0 0 1 3.134-2.056q.126-.165.265-.322c1.13-1.276 2.671-1.95 4.461-1.95c.2 0 .604.032.613.032a10 10 0 0 0-3.43-.36");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.ca61j54nb {
  d: path("M16.15 10.574q-.014.083-.03.165c1.203.95 2.48 2.48 3.032 4.4q.048-.108.093-.22c-.58-1.908-1.879-3.417-3.095-4.345");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cwggqqbtd {
  d: path("M13.822 8.507q.121.014.236.011s-.052-1.04-.179-1.573s-.315-.885-.522-1.084c-.147-.143-.615-.322-.978.776a1.67 1.67 0 0 0 1.443 1.87");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.d-taosbnt {
  d: path("M17.287 17.642c-.13.18-.293.354-.458.502l-.023.02a7.9 7.9 0 0 1-2.444 1.282h-.004c.16.472.202 1.226.202 1.226s1.34-.343 2.346-1.47c.703-.79 2.054-2.71.617-5.238l.005.018c.088.177.168.357.231.545a3.43 3.43 0 0 1-.472 3.113z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.dawca5oxo {
  d: path("M10.073 9.936q.07.548.195 1.035a7.4 7.4 0 0 1 2.072-.195q.054.001.105.007h.004q.626.05 1.303.233c.095-.32.177-.65.233-.998c.064-.431.084-.83.08-1.178a9 9 0 0 0-2.97-.234q-.51.034-1.02.13c-.047.436-.05.846-.006 1.203z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ft5dv1b6b {
  fill: none;
}

.ghqj5bc6h {
  d: path("m8.69 9.12l.158-.06c.218-1.516.908-3.388 2.294-4.826q-.12.013-.236.03C9.545 5.72 8.886 7.598 8.69 9.116z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.gmhrctb-a {
  d: path("M21.975 11.32c-.306-.031-1.808.087-2.176.148a7.8 7.8 0 0 1-.118 1.98q.078.191.145.389c.54 1.616.352 3.288-.542 4.838q-.148.254-.315.488l-.007.009l.007-.007a9.98 9.98 0 0 0 3.006-7.844");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.hbc89wqwt {
  d: path("M8.376 9.242q.155-.063.315-.123c.195-1.515.856-3.397 2.217-4.853a8 8 0 0 0-1.498.363C8.24 6.142 7.847 8.02 7.865 9.467q.243-.117.51-.227z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.hyuo6b01r {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.766 10.333c-2.66 1.112-3.567 2.442-3.54 3.531q.036.044.075.084c0-1.08.914-2.387 3.54-3.485a8.6 8.6 0 0 1 2.723-.638a9 9 0 0 1 2.437.12l.014-.113a8.9 8.9 0 0 0-2.526-.136a8.5 8.5 0 0 0-2.723.637");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.i6ngiacan {
  stop-color: var(--svg-color--703ac2, #703AC2);
}

.injnfwz3r {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.06 10.031c.368-2.859-.33-4.309-1.286-4.83q-.055.009-.111.022c.937.538 1.611 1.988 1.248 4.808a8.6 8.6 0 0 1-.81 2.676a8.8 8.8 0 0 1-1.323 2.051l.09.068a8.8 8.8 0 0 0 1.38-2.12a8.5 8.5 0 0 0 .81-2.675z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.j6x6cuh2u {
  d: path("M19.68 13.44c-.725-1.772-2.159-3.052-3.42-3.758q-.023.27-.06.558a8.5 8.5 0 0 1-.413 1.73c.822.605 1.618 1.504 1.972 2.559a3.43 3.43 0 0 1-.472 3.113c-.129.18-.292.354-.458.502l-.007.007a7.84 7.84 0 0 0 2.862-4.7q-.001-.005-.005-.011");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.khggs1b5f {
  d: path("m4.95 13.367l.033.091q.096.225.245.406c-.027-1.089.88-2.417 3.54-3.53a8.6 8.6 0 0 1 2.723-.638a9 9 0 0 1 2.526.136c.043-.359.06-.695.057-.992a8.9 8.9 0 0 0-2.973-.234a8.5 8.5 0 0 0-2.723.638c-3.168 1.325-3.85 2.957-3.429 4.123");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.kryeveeeq {
  d: path("M4.473 13.76a3 3 0 0 1-.204-.65q-.002-.014-.007-.029a7.9 7.9 0 0 1 .111-2.757v-.004c-.488-.098-1.162-.438-1.162-.438s-.372 1.332.1 2.768c.331 1.005 1.318 3.132 4.228 3.154l-.019-.007a4 4 0 0 1-.587-.072a3.42 3.42 0 0 1-2.46-1.965");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ms3c_6zov {
  d: path("M16.202 10.24c-.013.111-.034.223-.052.334c1.216.928 2.514 2.437 3.095 4.345q.29-.719.434-1.477c-.724-1.77-2.158-3.05-3.418-3.758q-.023.268-.059.556");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.nf7blgbou {
  d: path("M14.244 4.601c.22.023.454.077.665.148l.03.009a7.9 7.9 0 0 1 2.336 1.48c.33-.375.96-.788.96-.788s-.966-.99-2.446-1.296c-1.035-.215-3.372-.424-4.845 2.083q.002 0 .014-.013c.109-.166.225-.325.356-.472a3.42 3.42 0 0 1 2.932-1.148z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.nwchjeb5f {
  stop-color: var(--svg-color--0297fb, #0297FB);
}

.ppfy-3jig {
  d: path("M11.973 14.012a7.4 7.4 0 0 1-1.205-1.696l-.048-.093v-.004a7 7 0 0 1-.45-1.248a8 8 0 0 0-.98.295a8 8 0 0 0-1.057.517a9 9 0 0 0 1.28 2.694q.282.423.62.814a5.2 5.2 0 0 0 1.043-.596c.295-.223.558-.452.799-.688z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qk-klebel {
  d: path("M11.162 16.306c-.043-.037-.086-.07-.13-.11c-1.422.568-3.387.909-5.325.425q.071.096.145.19c1.943.452 3.901.082 5.313-.508z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.quy2khbta {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.175 15.632c2.294 1.747 3.898 1.868 4.826 1.3q.02-.053.037-.106c-.935.542-2.526.401-4.788-1.323a8.5 8.5 0 0 1-1.913-2.04a9 9 0 0 1-1.114-2.172q-.054.022-.105.045a9 9 0 0 0 1.146 2.256a8.5 8.5 0 0 0 1.913 2.04z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.r268qqbxu {
  d: path("M21.976 11.32C21.6 5.813 16.83 1.65 11.322 2.023a9.96 9.96 0 0 0-6.835 3.382l-.005-.003l-.034.048a9.96 9.96 0 0 0-2.337 8.001q0 .017.005.034q.036.253.088.5v.008q.045.225.1.445c1.155 4.605 5.469 7.868 10.372 7.534c5.51-.375 9.672-5.144 9.297-10.654zm-2.177.148a7.8 7.8 0 0 1-.118 1.98q0-.005-.004-.01c-.724-1.773-2.158-3.053-3.42-3.758c.254-3.002-.762-4.266-1.915-4.473q-.048-.01-.095-.016a1.67 1.67 0 0 0-.427 3.313q.12.015.236.012q.009.152.01.322a9 9 0 0 0-2.971-.234q-.51.034-1.02.13c.114-1.015.496-2.152 1.233-2.985a3.42 3.42 0 0 1 2.932-1.148c.22.023.454.077.665.148l.03.009a7.83 7.83 0 0 1 4.862 6.712zm-6.968 1.527v.002a7 7 0 0 1-.856 1.012a7.4 7.4 0 0 1-1.205-1.695l-.047-.093v-.004a7 7 0 0 1-.45-1.248a7.4 7.4 0 0 1 2.072-.195q.053.002.104.006h.005q.625.051 1.303.234a7.5 7.5 0 0 1-.867 1.893l-.057.088zM9.413 4.624l-.007.007c-1.17 1.513-1.563 3.392-1.545 4.838c-2.727 1.28-3.313 2.795-2.916 3.896l.034.09a1.67 1.67 0 1 0 2.973-1.5a6 6 0 0 1 .277-.17a9 9 0 0 0 1.28 2.694q.282.422.62.815c-.936.408-2.111.649-3.203.426a3.42 3.42 0 0 1-2.46-1.965a3 3 0 0 1-.204-.649a8 8 0 0 1-.063-.576C3.956 8.949 6.177 5.759 9.41 4.624zm3.118 15.174a7.8 7.8 0 0 1-5.618-1.87c1.897.259 3.719-.342 4.962-1.082c2.474 1.722 4.078 1.475 4.834.578l.061-.074a1.67 1.67 0 1 0-2.787-1.825a5 5 0 0 1-.283-.154a9 9 0 0 0 1.69-2.458q.226-.459.397-.946c.822.606 1.618 1.505 1.972 2.56a3.43 3.43 0 0 1-.472 3.113c-.129.18-.292.354-.458.502l-.007.006a7.76 7.76 0 0 1-4.289 1.648z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t4nmu4h1z {
  d: path("M9.408 4.63c-1.17 1.515-1.563 3.394-1.545 4.84q.245-.115.513-.227a8.6 8.6 0 0 1 1.704-.508c.114-1.015.495-2.152 1.232-2.984A3.42 3.42 0 0 1 14.244 4.6c.22.023.454.077.665.148l.03.009a7.77 7.77 0 0 0-5.524-.132l-.007.007z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.to_028fru {
  d: path("M13.754 11.016a7.5 7.5 0 0 1-.867 1.893l-.057.088V13a7 7 0 0 1-.855 1.012c.23.242.476.479.749.703c.34.27.676.486.978.658a9 9 0 0 0 1.69-2.457q.226-.46.397-.947a5.3 5.3 0 0 0-1.037-.605a8 8 0 0 0-.996-.348z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ttplkd_yd {
  stop-color: var(--svg-color--0070eb, #0070EB);
}

.uo5na3ink {
  d: path("M14.342 5.21q-.048-.01-.096-.016a1.7 1.7 0 0 0-.474.006c.958.52 1.654 1.97 1.287 4.831a8.6 8.6 0 0 1-.81 2.676a9 9 0 0 1-1.38 2.12c.29.217.572.399.83.544a9 9 0 0 0 1.691-2.458a8.6 8.6 0 0 0 .81-2.675c.436-3.406-.635-4.813-1.856-5.03z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vul7kvb-z {
  d: path("M8.065 12.17a2 2 0 0 0-.109-.212s-.874.565-1.27.942c-.398.376-.611.717-.68.996c-.05.2.03.694 1.163.458a1.67 1.67 0 0 0 .896-2.185");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wavkffbjb {
  stop-color: var(--svg-color--231f20, #231F20);
}

.wxsouifcl {
  d: path("M6.912 17.928c1.897.259 3.72-.342 4.963-1.082a12 12 0 0 1-.452-.33a8.4 8.4 0 0 1-1.293-1.222c-.935.408-2.11.649-3.202.426a3.42 3.42 0 0 1-2.46-1.965a3 3 0 0 1-.204-.649a7.8 7.8 0 0 0 2.648 4.822");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y8z2ufqdv {
  d: path("M12.53 19.798a7.8 7.8 0 0 1-5.618-1.87a6 6 0 0 1-.42-.07c-1.668-.34-3.022-1.339-3.917-2.889a6 6 0 0 1-.27-.526c1.155 4.604 5.47 7.867 10.373 7.534c.023-.506-.127-1.677-.148-2.177z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.z7h49bsez {
  d: path("M14.115 15.323q-.071.097-.13.2s.927.474 1.453.63s.926.17 1.203.091c.197-.056.585-.372-.184-1.236a1.673 1.673 0 0 0-2.342.315");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.zgkm01wcd {
  stop-color: var(--svg-color--e6007a, #E6007A);
}

.zier6v7pd {
  d: path("m16.71 17.422l.062-.075q.149-.196.231-.415c-.928.568-2.532.447-4.826-1.3a8.5 8.5 0 0 1-1.913-2.04a9 9 0 0 1-1.146-2.256a8 8 0 0 0-.888.447a9 9 0 0 0 1.283 2.692a8.5 8.5 0 0 0 1.912 2.04c2.73 2.08 4.484 1.856 5.285.907");
  opacity: var(--svg-opacity--0-9, 0.9);
}

</style>
