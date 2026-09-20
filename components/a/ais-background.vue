<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGLFh5tepF)" class="lxqo2uhft"/><path fill="url(#SVGxEobkejg)" class="xhmuko4xs"/><path class="mpnb_cp5f"/><path class="fjqfcy0-x"/><path class="bc_47ej1a"/><path class="vayom3b-g"/><path class="a_acimbqo"/><path fill="url(#SVGr1ySXdqv)" class="uvit9eb_d"/><path fill="url(#SVGuZBW1dQH)" class="mtzm38b2u"/><path class="wvyhesbxx"/><path fill="url(#SVGvr2xIbko)" class="bt3uylbfb"/><path class="i3-9uz0ly"/><path class="rv8xtbcaj"/><path fill="url(#SVGXUgx0cPe)" class="ecru8ibjr"/><path class="b6ggcrrgw"/><path fill="url(#SVGzh6bAdbJ)" class="xzqzak3rs"/><path class="ccuxeoz1d"/><path class="s-gnxlk4r"/><path fill="url(#SVGlToZXdRf)" class="pzynk9beb"/><path class="sadcfqbgv"/><path fill="url(#SVGZt2tFgHo)" class="d-rcidftz"/><path fill="url(#SVGiS8slcRZ)" class="a2f_r4qrq"/><path class="hiiisdzjq"/><path fill="url(#SVGyK7OQbfx)" class="mqqwxvw0a"/><path fill="url(#SVGB3NWDbft)" class="q91lappxs"/><path fill="url(#SVG7d4Ywcqm)" class="illlxwbsv"/><path class="ujvl3-b1u"/><path class="svqghdagk"/><path fill="url(#SVGvRsotbZW)" class="ku2bjfbny"/><path class="qojbsddut"/><path class="wcu2_3bas"/><path fill="url(#SVGMlb1dcPU)" class="rneqb2b7a"/><path class="f_maa2buj"/><path class="ene--ibct"/><path fill="url(#SVGJr1DcepW)" class="lpx30oyrj"/></g><defs><linearGradient id="SVGLFh5tepF" x1="16.202" x2="9.011" y1="11.879" y2="17.462" gradientUnits="userSpaceOnUse"><stop class="mzvkjibil"/><stop offset=".89" class="g__t-db2o"/><stop offset="1" class="n6e5qnizr"/></linearGradient><linearGradient id="SVGxEobkejg" x1="9.513" x2="15.519" y1="11.982" y2="11.982" gradientUnits="userSpaceOnUse"><stop class="eot9-iboe"/><stop offset="1" class="zqe3sfp-o"/></linearGradient><linearGradient id="SVGr1ySXdqv" x1="10.993" x2="15.045" y1="12.073" y2="11.658" gradientUnits="userSpaceOnUse"><stop class="i3mjz2_ek"/><stop offset="1" class="lqtad391h"/></linearGradient><linearGradient id="SVGuZBW1dQH" x1="12.034" x2="12.034" y1="4" y2="11.191" gradientUnits="userSpaceOnUse"><stop class="xu26p64eq"/><stop offset=".84" class="pefctsiyw"/><stop offset=".98" class="bk9x7iqge"/></linearGradient><linearGradient id="SVGvr2xIbko" x1="11.96" x2="11.96" y1="5.847" y2="10.712" gradientUnits="userSpaceOnUse"><stop class="ooh_9k4ad"/><stop offset="1" class="kmjnxhbim"/></linearGradient><linearGradient id="SVGXUgx0cPe" x1="6.512" x2="6.512" y1="4.22" y2="9.176" gradientUnits="userSpaceOnUse"><stop class="xu26p64eq"/><stop offset="1" class="y_om08fzx"/></linearGradient><linearGradient id="SVGzh6bAdbJ" x1="6.118" x2="6.118" y1="7.131" y2="8.558" gradientUnits="userSpaceOnUse"><stop class="ey368abkl"/><stop offset="1" class="asgqqo9zr"/></linearGradient><linearGradient id="SVGlToZXdRf" x1="17.487" x2="17.487" y1="4.22" y2="9.176" gradientUnits="userSpaceOnUse"><stop class="xu26p64eq"/><stop offset="1" class="y_om08fzx"/></linearGradient><linearGradient id="SVGZt2tFgHo" x1="17.886" x2="17.886" y1="7.131" y2="8.558" gradientUnits="userSpaceOnUse"><stop class="ey368abkl"/><stop offset="1" class="asgqqo9zr"/></linearGradient><linearGradient id="SVGiS8slcRZ" x1="8.471" x2="15.325" y1="7.46" y2="7.46" gradientUnits="userSpaceOnUse"><stop class="b3b5x9hgv"/><stop offset=".61" class="gp9o56bzr"/><stop offset="1" class="c05z9abfq"/></linearGradient><linearGradient id="SVGyK7OQbfx" x1="9.951" x2="9.817" y1="6.469" y2="7.848" gradientUnits="userSpaceOnUse"><stop class="w2_a9w03v"/><stop offset="1" class="su-qurb2l"/></linearGradient><linearGradient id="SVGB3NWDbft" x1="10.531" x2="10.531" y1="6.892" y2="8.864" gradientUnits="userSpaceOnUse"><stop class="tcwfh8r2x"/><stop offset="1" class="fs7qicbfv"/></linearGradient><linearGradient id="SVG7d4Ywcqm" x1="13.656" x2="13.656" y1="6.892" y2="8.864" gradientUnits="userSpaceOnUse"><stop class="tcwfh8r2x"/><stop offset="1" class="fs7qicbfv"/></linearGradient><linearGradient id="SVGvRsotbZW" x1="7.053" x2="7.053" y1="11.727" y2="18.019" gradientUnits="userSpaceOnUse"><stop class="k62h8_bnf"/><stop offset="1" class="ukk4ckuxn"/></linearGradient><linearGradient id="SVGMlb1dcPU" x1="16.852" x2="16.852" y1="11.727" y2="18.019" gradientUnits="userSpaceOnUse"><stop class="k62h8_bnf"/><stop offset="1" class="ukk4ckuxn"/></linearGradient><linearGradient id="SVGJr1DcepW" x1="10.148" x2="14.057" y1="14.474" y2="14.474" gradientUnits="userSpaceOnUse"><stop class="sz1ookb5h"/><stop offset="1" class="y67b_kfcx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ais-background" /></template>
<style>
.a_acimbqo {
  fill: var(--svg-color--9ea3b6, #9ea3b6);
  d: path("m9.535 11.152l-.554-.104c.013.324.52.947 2.409.834c-1.414-.064-1.825-.514-1.86-.735z");
}

.a2f_r4qrq {
  d: path("M13.418 5.942H10.69c-.684 0-2.219.16-2.219 1.66c0 1.506 1.254 3.019 3.473 3.019c2.214 0 3.506-1.336 3.506-3.018c0-1.34-1.353-1.665-2.032-1.66");
}

.asgqqo9zr {
  stop-color: var(--svg-color--5ea3e0, #5ea3e0);
}

.b3b5x9hgv {
  stop-color: var(--svg-color--27213b, #27213b);
}

.b6ggcrrgw {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M6.807 5.536c-.44.073-.756 0-.791 0c-.052.013-.03.07-.017.1c.043.012.164.034.367.034c.255 0 .415-.017.441-.035c.018-.017.009-.073 0-.1");
}

.bc_47ej1a {
  fill: var(--svg-color--335ca7, #335ca7);
  d: path("M7.817 11.265c0-.151.23-.35.346-.433l.338.13l-.143.666a4 4 0 0 1-.523-.16a.7.7 0 0 1-.018-.199z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bk9x7iqge {
  stop-color: var(--svg-color--4a6dd8, #4a6dd8);
}

.bt3uylbfb {
  d: path("M13.5 5.851h-2.885c-.722 0-2.34.165-2.34 1.73c0 1.557 1.324 3.13 3.66 3.13c2.339 0 3.7-1.383 3.7-3.134c0-1.397-1.426-1.73-2.14-1.73z");
}

.c05z9abfq {
  stop-color: var(--svg-color--28223c, #28223c);
}

.ccuxeoz1d {
  fill: var(--svg-color--c9d3e8, #c9d3e8);
  d: path("M16.73 7.088c.095.013.246.462.311.683c.043.225.113.765.104 1.15c-.013.39-.073.51-.104.519c-.173 0-.311-.519-.346-.9c-.043-.376-.077-1.47.035-1.452");
}

.d-rcidftz {
  d: path("M17.825 8.558a1.9 1.9 0 0 1-.108-.649c0-.384.203-.657.337-.778c.007.485-.07.968-.229 1.427");
}

.ecru8ibjr {
  d: path("M5.945 7.01c0 1.612.498 2.118.748 2.166c.498 0 .394-.852.33-2.465c-.066-1.613-.273-2.49-.412-2.49s-.661.773-.661 2.788z");
}

.ene--ibct {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M16.937 16.12c.575 0 .887.043.995.065l.03-.13c-.121-.022-.445-.065-1.025-.065c-.501 0-.774.07-.943.108l-.073.022l.03.13l.078-.022c.173-.043.424-.108.908-.108");
}

.eot9-iboe {
  stop-color: var(--svg-color--6192e0, #6192e0);
}

.ey368abkl {
  stop-color: var(--svg-color--32469f, #32469f);
}

.f_maa2buj {
  fill: var(--svg-color--829fd1, #829fd1);
  d: path("M17.739 15.923c0 .63-.178.795-.269.8c-.211 0-.207-.563-.181-.844c0-.415.03-1.245.181-1.245c.195 0 .269.501.269 1.288");
}

.fjqfcy0-x {
  fill: var(--svg-color--4470d1, #4470d1);
  d: path("M12.125 11.628c-1.436 0-1.756-.346-1.73-.519h3.455v.06c.022.152-.294.459-1.73.459z");
}

.fs7qicbfv {
  stop-color: var(--svg-color--fcbe43, #fcbe43);
}

.ft5dv1b6b {
  fill: none;
}

.g__t-db2o {
  stop-color: var(--svg-color--1b5ccf, #1b5ccf);
}

.gp9o56bzr {
  stop-color: var(--svg-color--4a3f73, #4a3f73);
}

.hiiisdzjq {
  fill: var(--svg-color--483d6f, #483d6f);
  d: path("M15.11 9.005a7.1 7.1 0 0 1-3.036.596c-1.427 0-2.478-.229-3.122-.428c.557.835 1.578 1.449 2.992 1.449c1.548 0 2.642-.649 3.165-1.617");
}

.i3-9uz0ly {
  fill: var(--svg-color--c9d3e8, #c9d3e8);
  d: path("M7.27 7.088c-.091.013-.243.462-.308.683a6.7 6.7 0 0 0-.103 1.15c.008.39.073.51.103.519c.173 0 .307-.519.346-.9c.044-.376.078-1.47-.039-1.452");
}

.i3mjz2_ek {
  stop-color: var(--svg-color--b9c5de, #b9c5de);
}

.illlxwbsv {
  d: path("M13.656 8.864c.518 0 .938-.441.938-.986s-.42-.986-.938-.986s-.938.441-.938.986s.42.986.938.986");
}

.k62h8_bnf {
  stop-color: var(--svg-color--87b7fd, #87b7fd);
}

.kmjnxhbim {
  stop-color: var(--svg-color--d2dbed, #d2dbed);
}

.ku2bjfbny {
  d: path("M6.006 15.59c0 1.802.58 2.369.865 2.43c.826 0 1.124-2.029 1.168-3.04c.1-1.086.147-3.253-.441-3.253c-.735 0-1.592 1.614-1.592 3.862");
}

.lpx30oyrj {
  d: path("m10.469 13.285l-.593 1.461h.346l.588-1.396a.09.09 0 0 1 .078-.048a.09.09 0 0 1 .078.048l.553 1.396h.355l-.575-1.457a.45.45 0 0 0-.415-.277a.44.44 0 0 0-.415.273m1.638-.273h.355v1.734h-.355zm.718 1.743v-.324h1.038c.12 0 .22-.095.22-.208a.21.21 0 0 0-.216-.203h-.562a.507.507 0 0 1-.519-.493c0-.273.234-.493.52-.493h.946v.307h-.93c-.116 0-.216.09-.216.203c0 .108.1.199.216.199h.532c.299 0 .536.23.536.506a.52.52 0 0 1-.536.506z");
}

.lqtad391h {
  stop-color: var(--svg-color--667ab0, #667ab0);
}

.lxqo2uhft {
  d: path("M7.99 15.14c-.086-.952-.16-3.04-.185-3.961c.052-.212.346-.364.48-.415c1.989-.014 6.144-.044 6.888-.044c.74 0 .995.42 1.03.636c-.053.32-.156 1.375-.156 3.044c0 2.084-1.998 5.6-4.017 5.6s-3.927-3.671-4.04-4.86");
}

.mpnb_cp5f {
  fill: var(--svg-color--26203a, #26203a);
  d: path("M12.126 11.9c-2.188 0-2.672-.528-2.642-.796h5.276v.1c.034.229-.446.696-2.634.696");
}

.mqqwxvw0a {
  d: path("M9.83 7.213h-.735a.934.934 0 0 1 .93-.744zm1.08-.74h-.808l-.169.727h.978zm-1.841.822h.743l-.069.302h-.752z");
}

.mtzm38b2u {
  d: path("M14.352 11.191H9.868c-.472 0-1.6-.138-2.335-.683c-.93-.688-.64-2.478-.537-2.863C7.1 7.265 8.06 4 11.986 4c3.931 0 5.146 3.546 5.19 4.082V8.1a3.57 3.57 0 0 1-.329 1.985c-.329.735-1.777 1.051-2.495 1.107");
}

.mzvkjibil {
  stop-color: var(--svg-color--89b9ed, #89b9ed);
}

.n6e5qnizr {
  stop-color: var(--svg-color--6095d0, #6095d0);
}

.ooh_9k4ad {
  stop-color: var(--svg-color--8091bf, #8091bf);
}

.pefctsiyw {
  stop-color: var(--svg-color--3856dc, #3856dc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pzynk9beb {
  d: path("M18.054 7.01c0 1.612-.497 2.118-.744 2.166c-.497 0-.398-.852-.328-2.465c.064-1.613.272-2.49.41-2.49c.139 0 .662.773.662 2.788");
}

.q91lappxs {
  d: path("M10.53 8.864c.519 0 .94-.441.94-.986s-.421-.986-.94-.986s-.938.441-.938.986s.42.986.939.986");
}

.qojbsddut {
  fill: var(--svg-color--829fd1, #829fd1);
  d: path("M6.17 15.923c0 .63.173.795.264.8c.216 0 .212-.563.182-.844c.004-.415-.026-1.245-.182-1.245c-.19 0-.264.501-.264 1.288");
}

.rneqb2b7a {
  d: path("M17.898 15.59c0 1.802-.575 2.369-.864 2.43c-.822 0-1.125-2.029-1.168-3.04c-.095-1.086-.143-3.253.445-3.253c.736 0 1.587 1.614 1.587 3.862");
}

.rv8xtbcaj {
  fill: var(--svg-color--251f38, #251f38);
  d: path("M7.282 7.286c-.083.013-.217.39-.273.57c-.03.182-.095.632-.086.952c.008.32.06.424.086.433c.156 0 .273-.433.303-.749c.039-.31.069-1.219-.03-1.206");
}

.s-gnxlk4r {
  fill: var(--svg-color--251f38, #251f38);
  d: path("M16.722 7.286c.082.013.216.39.268.57c.035.182.1.632.086.952c-.004.32-.06.424-.086.433c-.151 0-.268-.433-.303-.749c-.034-.31-.065-1.219.035-1.206");
}

.sadcfqbgv {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M17.197 5.536c.441.073.757 0 .792 0c.052.013.03.07.013.1q-.18.04-.364.034c-.255 0-.415-.017-.44-.035c-.022-.017-.01-.073 0-.1");
}

.su-qurb2l {
  stop-color: var(--svg-color--9490a1, #9490a1);
  stop-opacity: 0;
}

.svqghdagk {
  fill: var(--svg-color--28233e, #28233e);
  d: path("M7.806 11.715v.1c-.043.501-.139 1.53-.139 1.613s.195.614.295.873c.06-.168.181-.661.181-1.28a2.7 2.7 0 0 0-.337-1.306");
}

.sz1ookb5h {
  stop-color: var(--svg-color--c6ad40, #c6ad40);
}

.tcwfh8r2x {
  stop-color: var(--svg-color--fff962, #fff962);
}

.ujvl3-b1u {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M9.237 6.09c-.217-.26-.476-.744-.589-.987l.16-.125c.018.164.364.77.541 1.05c-.026.022-.082.061-.112.061m5.435-.018q.395-.42.679-.921l-.173-.13c-.03.16-.41.714-.623.982a.4.4 0 0 0 .117.07");
}

.ukk4ckuxn {
  stop-color: var(--svg-color--325ca9, #325ca9);
}

.uvit9eb_d {
  d: path("M11.317 11.882h-.744c2.932.429 4.882-.268 4.593-.821l-.498.086c.005.692-2.23.779-3.35.735");
}

.vayom3b-g {
  fill: var(--svg-color--496bac, #496bac);
  d: path("M8.16 11.321c0 .165.168.294.25.338c.433.073 1.445.22 2.033.212c-1.124-.16-1.427-.614-1.431-.822l-.558-.087c-.095.048-.294.195-.294.36");
}

.w2_a9w03v {
  stop-color: var(--svg-color--9490a1, #9490a1);
}

.wcu2_3bas {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M6.966 16.12c-.571 0-.882.043-.995.065l-.026-.13c.121-.022.441-.065 1.02-.065c.502 0 .78.07.944.108l.077.022l-.034.13l-.078-.022a3.3 3.3 0 0 0-.908-.108");
}

.wvyhesbxx {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M13.552 5.769h-2.98c-.743 0-2.416.173-2.416 1.786s1.366 3.243 3.783 3.243c2.418 0 3.823-1.44 3.823-3.243c0-1.444-1.47-1.795-2.21-1.786");
}

.xhmuko4xs {
  d: path("M10.412 11.857q-1.021-.054-2.032-.216c.372.212 1.643.627 3.762.627c2.65 0 3.74-.51 3.74-.822c0-.255-.246-.402-.371-.45l-.342.074q.04.058.039.13c-.355.722-2.05.821-3.07.821a8.7 8.7 0 0 1-1.73-.164z");
}

.xu26p64eq {
  stop-color: var(--svg-color--72cdff, #72cdff);
}

.xzqzak3rs {
  d: path("M6.174 8.558c.056-.156.112-.376.112-.649a1.07 1.07 0 0 0-.337-.778c.009.649.104 1.111.225 1.427");
}

.y_om08fzx {
  stop-color: var(--svg-color--252b8c, #252b8c);
}

.y67b_kfcx {
  stop-color: var(--svg-color--ffe45b, #ffe45b);
}

.zqe3sfp-o {
  stop-color: var(--svg-color--97c1ef, #97c1ef);
}

</style>
