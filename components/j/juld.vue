<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG57IlTdtV)" clip-rule="evenodd" class="qrxin7pkc"/><path fill="url(#SVGkJiYlkxX)" class="udbnrcq9a"/><path fill="url(#SVGAYnhqbXf)" class="udloz91fc"/><path fill="url(#SVGQNwigewn)" class="mo_t8wxrj"/><path fill="url(#SVGUxjzzpBD)" class="uq907xqom"/><path fill="url(#SVGJy2nxdyh)" class="dd95kbclp"/><path class="v03_5167s"/><path fill="url(#SVGlCX2VvEu)" class="crnhtbcob"/><path class="gq8jzrb1t"/><path fill="url(#SVGm0ojmbAX)" class="fkxguqbou"/><path class="k8ufb2h_z"/><path class="fcspo-bcu"/><path fill="url(#SVG6wkTedxe)" class="z1ndtf0il"/><path class="jbv3a3bwa"/><path fill="url(#SVG10P1UdrI)" class="f7q5vtbeo"/><path fill="url(#SVGsArujdvQ)" class="sox-wmbth"/><path fill="url(#SVG1N9lgemj)" class="kb3h77b8p"/><path fill="url(#SVGaJ5vEeVw)" class="umtjtxn-b"/><path fill="url(#SVG2ft1Adln)" class="qlehlvmnm"/><path class="a5zp4xbbd"/><path fill="url(#SVGHu24FekK)" class="ebc8_ac3u"/><path class="e3mlm5j1v"/><path fill="url(#SVGuifiwc5i)" class="cx219acfo"/><path fill="url(#SVGVFsSIcUz)" class="fa_ahsb_d"/><path fill="url(#SVGqWhrxcip)" class="w2ruv-b-b"/><defs><linearGradient id="SVG57IlTdtV" x1="23.25" x2="4.454" y1="13.882" y2="19.184" gradientUnits="userSpaceOnUse"><stop offset=".32" class="osx-n1bpl"/><stop offset="1" class="w01kddccb"/></linearGradient><linearGradient id="SVGkJiYlkxX" x1="23.745" x2="2.996" y1="15.88" y2="15.482" gradientUnits="userSpaceOnUse"><stop class="lbxu652ew"/><stop offset="1" class="uz1fpccuf"/></linearGradient><linearGradient id="SVGAYnhqbXf" x1="12.017" x2="12.017" y1="4.001" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".14" class="o_qefezmu"/><stop offset="1" class="uz1fpccuf"/></linearGradient><linearGradient id="SVGQNwigewn" x1="24.726" x2="3.501" y1="8.453" y2="13.998" gradientUnits="userSpaceOnUse"><stop class="lbxu652ew"/><stop offset="1" class="uz1fpccuf"/></linearGradient><linearGradient id="SVGUxjzzpBD" x1="18.791" x2="3.199" y1="9.489" y2="11.563" gradientUnits="userSpaceOnUse"><stop class="hy5vnwb2k"/><stop offset="1" class="jbwje-4zv"/></linearGradient><linearGradient id="SVGJy2nxdyh" x1="18.588" x2="3" y1="4.024" y2="4.024" gradientUnits="userSpaceOnUse"><stop class="tj74fyb9j"/><stop offset="1" class="zkzj2ibcg"/></linearGradient><linearGradient id="SVGlCX2VvEu" x1="26.079" x2="15.244" y1="8.683" y2="30.064" gradientUnits="userSpaceOnUse"><stop class="dudklsbam"/><stop offset="1" class="uok4jvb2m"/></linearGradient><linearGradient id="SVGm0ojmbAX" x1="3" x2="21.604" y1="4.001" y2="24.328" gradientUnits="userSpaceOnUse"><stop class="fvy0jwemy"/><stop offset="1" class="l9ytmzxvk"/></linearGradient><linearGradient id="SVG6wkTedxe" x1="23.7" x2="11.124" y1="13.156" y2="19.691" gradientUnits="userSpaceOnUse"><stop class="a20me9bgy"/><stop offset="1" class="r-_46wb0j"/></linearGradient><linearGradient id="SVG10P1UdrI" x1="21.001" x2="2.953" y1="12.002" y2="12.002" gradientUnits="userSpaceOnUse"><stop class="fa3v4gqva"/><stop offset="1" class="utu97_b0t"/></linearGradient><linearGradient id="SVGsArujdvQ" x1="21.002" x2="6.496" y1="16.962" y2="18.15" gradientUnits="userSpaceOnUse"><stop class="hy5vnwb2k"/><stop offset="1" class="uz1fpccuf"/></linearGradient><linearGradient id="SVG1N9lgemj" x1="3.018" x2="4.048" y1="4.001" y2="20.499" gradientUnits="userSpaceOnUse"><stop offset=".14" class="uz1fpccuf"/><stop offset="1" class="ck-mg_gkt"/></linearGradient><linearGradient id="SVGaJ5vEeVw" x1="21.014" x2="5.054" y1="14.009" y2="24.783" gradientUnits="userSpaceOnUse"><stop class="og6o_0zrq"/><stop offset=".88" class="iur-kjbtb"/></linearGradient><linearGradient id="SVG2ft1Adln" x1="5.835" x2="8.834" y1="8.305" y2="22.565" gradientUnits="userSpaceOnUse"><stop class="hdwn8cp4s"/><stop offset="1" class="t_8ktvb5y"/></linearGradient><linearGradient id="SVGHu24FekK" x1="4.506" x2="20.012" y1="12.001" y2="12.599" gradientUnits="userSpaceOnUse"><stop offset=".15" class="j8nfetiil"/><stop offset="1" class="bhsi39bih"/></linearGradient><linearGradient id="SVGuifiwc5i" x1="20.973" x2="6.492" y1="5.819" y2="11.174" gradientUnits="userSpaceOnUse"><stop class="spjp8mbsz"/><stop offset="1" class="k-rsyxbfr"/></linearGradient><linearGradient id="SVGVFsSIcUz" x1="36.543" x2="3.392" y1="14.839" y2="19.785" gradientUnits="userSpaceOnUse"><stop class="dcn371vpc"/><stop offset="1" class="rwloedc9i"/></linearGradient><linearGradient id="SVGqWhrxcip" x1="20.836" x2="7.906" y1="13.78" y2="13.78" gradientUnits="userSpaceOnUse"><stop class="yqgqhci5b"/><stop offset="1" class="zbag2barj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:juld" /></template>
<style>
.a20me9bgy {
  stop-color: var(--svg-color--af53db, #af53db);
}

.a5zp4xbbd {
  fill: var(--svg-color--4c6eb5, #4c6eb5);
  d: path("M11.306 17.121c-.04-.175-.685-.7-1-.935c-.21.555.235 1.1.24 1.65c0 .44-.275.92-.415 1.1c1-.475 1.225-1.6 1.175-1.815");
}

.bhsi39bih {
  stop-color: var(--svg-color--4883af, #4883af);
}

.ck-mg_gkt {
  stop-color: var(--svg-color--446cb8, #446cb8);
}

.crnhtbcob {
  d: path("m18.216 6.285l.765-.585a2 2 0 0 0 0 .8l-.69.84c-.15-.3-.11-.83-.075-1.05z");
}

.cx219acfo {
  d: path("M8.816 18.77c.275-.035.415-.485.45-.705c-.215.325-.67.46-.875.485h-.86c-.31 0-.77.265-.925.47c-.125.16-.43.47-.565.6c-.025.1.07.295.115.38a1.23 1.23 0 0 1 1.05-.79h1.61a1.1 1.1 0 0 1-.725-.395c.125 0 .445-.005.725-.045");
}

.dcn371vpc {
  stop-color: var(--svg-color--4b8dae, #4b8dae);
}

.dd95kbclp {
  d: path("m15.75 7.445l-.1-.91c.666-.075 1.25.23 1.456.39l-.915.7a1.1 1.1 0 0 0-.435-.18z");
}

.dudklsbam {
  stop-color: var(--svg-color--924bc5, #924bc5);
}

.e3mlm5j1v {
  fill: var(--svg-color--497db7, #497db7);
  d: path("m9.226 17.4l-.255-.85a1.8 1.8 0 0 1-1.7 1.16c-.61.2-.76.89-.76 1.21a1.57 1.57 0 0 1 1.19-.5c.215.015.76 0 1.18-.2c.42-.185.405-.625.35-.82z");
}

.ebc8_ac3u {
  d: path("M8.941 16.316v-.275a2.135 2.135 0 0 1-2.91-.07c-1.08.25-1.075 1.26-.94 1.73c.8-.9 1.16-.16 2.29-.15c.905.005 1.42-.82 1.56-1.235");
}

.f7q5vtbeo {
  d: path("m17.426 8.772l.44-.54c.095.215.08 1.005.08 1.235c0 .18.125.385.185.465a1.05 1.05 0 0 1-.7-1.16z");
}

.fa_ahsb_d {
  d: path("M4.906 17.191c-.645.065-.97-.47-1.05-.74c-.175 1.36.685 1.62 1.135 1.575c-.09-.115-.095-.6-.085-.835");
}

.fa3v4gqva {
  stop-color: var(--svg-color--4c80b8, #4c80b8);
}

.fcspo-bcu {
  fill: var(--svg-color--ece2ff, #ece2ff);
  d: path("M16.511 10.135c0 .075.09.22.41.2c-.385.14-.435-.075-.41-.2");
}

.fkxguqbou {
  d: path("M15.316 9.376c.45.04 1.11.42 1.38.605c.405.315.38.985-.085.805c-.47-.18-1.26-1.405-1.295-1.41");
}

.ft5dv1b6b {
  fill: none;
}

.fvy0jwemy {
  stop-color: var(--svg-color--6051be, #6051be);
}

.gq8jzrb1t {
  fill: var(--svg-color--cd4bdf, #cd4bdf);
  d: path("M17.436 8.4c-.19-.24-.165-1.004-.13-1.36l.73-.59c-.038.361.013.725.15 1.06z");
}

.hdwn8cp4s {
  stop-color: var(--svg-color--67daa4, #67daa4);
}

.hy5vnwb2k {
  stop-color: var(--svg-color--4375b1, #4375b1);
}

.iur-kjbtb {
  stop-color: var(--svg-color--6ddfa4, #6ddfa4);
}

.j8nfetiil {
  stop-color: var(--svg-color--60d4ab, #60d4ab);
}

.jbv3a3bwa {
  fill: var(--svg-color--cc51e8, #cc51e8);
  d: path("M17.031 8.952c-.63-.35-.81-.865-.82-1.075l.915-.735c-.055.305-.085 1.01.226 1.39l-.32.415z");
}

.jbwje-4zv {
  stop-color: var(--svg-color--6ae3a3, #6ae3a3);
}

.k-rsyxbfr {
  stop-color: var(--svg-color--68dda4, #68dda4);
}

.k8ufb2h_z {
  fill: var(--svg-color--4848ba, #4848ba);
  d: path("M17.151 9.925c-.225-.075-.7.1-.9.2c.15.25.415.38.5.425c.08.035.4-.015.555-.045z");
}

.kb3h77b8p {
  d: path("M9.601 12.486a1.135 1.135 0 0 1 .82-.99c.41 1.56-.355 2.364-.4 2.515c-.04.125.04.154.08.154l.345-.304c.05.69.625 1.03.91 1.114c-.23.55.305 1.3.585 1.925c.22.5-.095.945-.28 1.1a1.5 1.5 0 0 0-.45-1.255c-.025-.05-.21-.26-.765-.665a2.3 2.3 0 0 1-.84-1.35c-.02-.49-.05-1.62 0-2.25z");
}

.l9ytmzxvk {
  stop-color: var(--svg-color--a754d8, #a754d8);
}

.lbxu652ew {
  stop-color: var(--svg-color--497db7, #497db7);
}

.mo_t8wxrj {
  d: path("M6.116 17.439c.07.06.655.185.935.24c-.435.225-.66.84-.715 1.125c-.77-.32-.47-1.045-.22-1.365");
}

.o_qefezmu {
  stop-color: var(--svg-color--4e97ae, #4e97ae);
}

.og6o_0zrq {
  stop-color: var(--svg-color--4775b3, #4775b3);
}

.osx-n1bpl {
  stop-color: var(--svg-color--c051e1, #c051e1);
}

.qlehlvmnm {
  d: path("M9.092 15.88c.185-.205.35-.665.415-.865c.1.48.49.894.67 1.04c-.01 0-.05.1-.08.46c-.045.45.335.7.3 1.35c-.035.64-.345 1.065-.81 1.185c-.375.1-.845-.04-1.03-.12c1.295.005.79-1.57.66-2.03a4 4 0 0 1-.125-1.02");
}

.qrxin7pkc {
  fill-rule: evenodd;
  d: path("M15.54 7.375c-.06-.71-.22-2.14-.35-2.155c-.13-.02-.885 1.475-1.25 2.225l-.035.08c-.245.03-.755.19-.875.625c-.115.43.305.665.53.73c.495.28 1.29 1.15.515 2.375c.05-.265-.08-.815-1.02-.915c.015.215-.01.725-.23 1.04l-.115.155c-.335.46-.95 1.305-.9 1.975c.07.75.805 1.115 1.32.515c.01.055 0 .2-.11.32l-.07.085c-.15.215-.455.63-1.445.58a.7.7 0 0 0-.065.285c.005.125.105.52.34.87c.235.345.41.91.39 1.15c.765 0 2.5-.185 3.355-.915a3.16 3.16 0 0 1-.565-3.095c-.44-.1-1.33-.52-1.355-1.39c.015-.04.06-.11.12-.12c.055-.01.085.075.095.12c.005.315.26 1 1.225 1.225c.97.225 1.575.25 1.75.24c.53.07 1.66.335 1.94.88c.28.54.81.36 1.04.205l-.515-.45c-.035-.05-.06-.14.08-.1s.56.245.75.345c.465-.36 1.26-1.27.74-2.04l-2.485-2.075a1.18 1.18 0 0 1-1.06-1.115c-.26.135-.87.085-1.26-1.2c-.055-.06-.275-.18-.685-.2a3.4 3.4 0 0 0-.975.095c.16-.525.53-1.575.69-1.59c.16-.01.2.1.225.2l.02.055c.035.07-.06.03-.11 0c-.01-.045-.05-.13-.085-.12q-.255.563-.44 1.15a3.3 3.3 0 0 1 .875-.045M20 12.35c-.085.075-.24.295-.175.55c.08.33.345.365.59.135c-.21.015-.585-.1-.415-.685");
}

.r-_46wb0j {
  stop-color: var(--svg-color--4e46bd, #4e46bd);
}

.rwloedc9i {
  stop-color: var(--svg-color--66d0a5, #66d0a5);
}

.sox-wmbth {
  d: path("M10.327 11.301c-.69-1.635-.6-2.8-.465-3.175a3 3 0 0 0-1.865 2.73c-.015.325.02 1.14.28 1.8s.07 1.35-.06 1.615c-.245.325-.885.75-1.5-.135a1.92 1.92 0 0 1 0-1.48c-.4.35-1.175 1.235-1.05 1.95c.16.9.32 1.74 1.86 1.825c1.23.07 1.75-.975 1.85-1.505v-1.525c-.08-.6-.01-1.86.95-2.1");
}

.spjp8mbsz {
  stop-color: var(--svg-color--66baab, #66baab);
}

.t_8ktvb5y {
  stop-color: var(--svg-color--4b8aae, #4b8aae);
}

.tj74fyb9j {
  stop-color: var(--svg-color--589cb6, #589cb6);
}

.udbnrcq9a {
  d: path("M3.901 18.287c-.4.02-.76-.33-.89-.51c-.09.595.39.99.64 1.11c.24.035.79.09 1.09.06c.375-.05.46-.335.45-.45c0-.115-.09-.28-.235-.295s-.54.065-1.05.085z");
}

.udloz91fc {
  d: path("M5.202 17.82c.13-.3.545-.405.73-.42c-.575.99.1 1.485.515 1.605c-.195.25-.41.475-.82.615c-.41.135-1.18-.165-1.425-.2c-.2-.025-.455.15-.56.245c.125-.455.425-.57.56-.57c.11.03.4.07.665 0c.325-.085.41-.4.45-.52a3 3 0 0 0-.115-.755");
}

.umtjtxn-b {
  d: path("M10.59 13.701c1.376-1.31 1.35-3.385 1.16-4.255a1.84 1.84 0 0 0 1.17.865c.036.32-.214 1.05-.47 1.33c-.21.23-.52.83-.65 1.1c-.494 1.34.34 1.755.82 1.8c-1.38.765-1.93-.235-2.03-.835z");
}

.uok4jvb2m {
  stop-color: var(--svg-color--cd4bdf, #cd4bdf);
}

.uq907xqom {
  d: path("m13.791 7.351l.57-1.21c-4-1.125-4.54 2.03-4.315 3.745c.2.615.625 1.935.69 2.285c.07.35-.19 1.125-.325 1.465c1.43-1.515 1.22-2.885 1.235-3.125c.02-.24-.065-1.045-.105-1.19a2.2 2.2 0 0 1 0-.56c.08-.72.69-1.37.85-1.405c.135-.03.105.06.075.11c-.26.235-.755.89-.665 1.62c.11.92 1.675 1.2 1.94 1.29c.215.075.39.32.45.43a1.504 1.504 0 0 0-.785-1.85c-.16-.01-.49-.17-.545-.725c-.05-.55.6-.815.93-.875z");
}

.utu97_b0t {
  stop-color: var(--svg-color--6dcbb2, #6dcbb2);
}

.uz1fpccuf {
  stop-color: var(--svg-color--67d1a5, #67d1a5);
}

.v03_5167s {
  fill: var(--svg-color--924bc5, #924bc5);
  d: path("M19.13 6.3a1.5 1.5 0 0 1 0-.685l1.196-.985c.104 0 .1.065.08.1z");
}

.w01kddccb {
  stop-color: var(--svg-color--4b47c0, #4b47c0);
}

.w2ruv-b-b {
  d: path("M6.501 4a1.5 1.5 0 0 0 1.5 1.5v4.3c.42-1.09 1.465-1.645 2-1.85V5.5h2.24c.83 0 1.625.155 2.35.44a3.1 3.1 0 0 1 .725-.99c.29.105.405 1.05.43 1.515a2.35 2.35 0 0 1 1.55.395l.98-.74A7.28 7.28 0 0 0 13.141 4zm12.51 2.96l-.925 1.16c.05.085.085.9.08 1.2a1 1 0 0 0 .18.555l2.155 1.845v-.25c0-1.69-.555-3.25-1.49-4.51m.965 7.84l-.105.025c-.99.205-1.235-.26-1.35-.49l-.05-.085c-.07-.1-.33-.225-.515-.295a6.28 6.28 0 0 1-5.715 3.545h-.145c-.2.614-.425.755-.56.744c.07-.35.06-.484 0-.59c-.4 1.3-1.95 1.786-2.335 1.826l-.04.02h3.98c3.1 0 5.75-1.945 6.835-4.7m-11.975-.525c.31-.4.395-.88.33-1.125l-.33-1.07v2.2z");
}

.yqgqhci5b {
  stop-color: var(--svg-color--4d45c2, #4d45c2);
}

.z1ndtf0il {
  d: path("M13.701 12.35c.24.575.9.875 1.26.955a3.22 3.22 0 0 0 .28 2.71c-1.6-.675-1.714-2.6-1.54-3.67z");
}

.zbag2barj {
  stop-color: var(--svg-color--4b46c2, #4b46c2);
}

.zkzj2ibcg {
  stop-color: var(--svg-color--6bc7b2, #6bc7b2);
}

</style>
