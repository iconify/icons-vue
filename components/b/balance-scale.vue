<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qjuaj6r-c"/><path class="ex7dfrjtw"/><path class="zn45uuk2t"/><path class="mmd0qab8w"/><path class="v4_y9kb3k"/><path class="n8d6z3blv"/><circle class="i2kovwbdw"/><g class="xklmb_cgz"><circle class="wv1zm22ym"/><circle class="q50gp65ga"/></g><g class="n1mjunbsu"><circle class="jxrjyqbbl"/><circle class="sn_ub2goo"/></g><g class="j9357eg9x"><circle class="y33hw8b0e"/><path class="alopf5b3b"/></g><path class="tl-fqxqdl"/><path class="jhsfo-bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:balance-scale" /></template>
<style>
.alopf5b3b {
  d: path("M32 45.1c-8.3 0-15 4.2-15 9.4h30c0-5.2-6.7-9.4-15-9.4");
}

.ex7dfrjtw {
  fill: var(--svg-color--b8c2c4, #b8c2c4);
  d: path("M50.3 10.2s-2.2-.8-3.4-1.3C42.6 7.1 37.3 5 32 5S21.4 7.2 17.1 9c-1.2.5-3.4 1.3-3.4 1.3l-3.3 2.5s2.7 1.7 4 1.2c1.1-.4 2.2-.9 3.5-1.4C22 10.9 27.1 8.8 32 8.8s10 2.1 14.1 3.8c1.2.5 2.4 1 3.5 1.4c1.4.5 4-1.2 4-1.2z");
}

.i2kovwbdw {
  cx: 13.2px;
  cy: 13.2px;
  r: 3.8px;
  fill: var(--svg-color--dbb471, #dbb471);
}

.j9357eg9x {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

.jhsfo-bvu {
  fill: var(--svg-color--6b767c, #6b767c);
  d: path("M11.4 58.2h41.2V62H11.4z");
}

.jxrjyqbbl {
  cx: 13.2px;
  cy: 13.2px;
  r: 1.9px;
}

.mmd0qab8w {
  fill: var(--svg-color--b8c2c4, #b8c2c4);
  d: path("M30.1 12.3h3.8v41.2h-3.8z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n8d6z3blv {
  fill: var(--svg-color--545b60, #545b60);
  d: path("M27.7 36.7h8.6v19.7h-8.6z");
}

.q50gp65ga {
  cx: 13.2px;
  cy: 13.2px;
  r: 3.8px;
}

.qjuaj6r-c {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M23.6 36.7H2.9l10.3-26.2zm-18-1.9h15.3l-7.7-19.5zm55.5 1.9H40.4l10.3-26.2zm-18-1.9h15.3l-7.7-19.5z");
}

.sn_ub2goo {
  cx: 50.8px;
  cy: 13.2px;
  r: 1.9px;
}

.tl-fqxqdl {
  fill: var(--svg-color--545b60, #545b60);
  d: path("M15.1 54.5h33.8v3.8H15.1z");
}

.v4_y9kb3k {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M29 18.6h6.1v34.9H29z");
}

.wv1zm22ym {
  cx: 50.8px;
  cy: 13.2px;
  r: 3.8px;
}

.xklmb_cgz {
  fill: var(--svg-color--545b60, #545b60);
}

.y33hw8b0e {
  cx: 32px;
  cy: 7.6px;
  r: 5.6px;
}

.zn45uuk2t {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M2 34.8C2 41 7 46 13.2 46s11.2-5 11.2-11.2zm37.5 0c0 6.2 5 11.2 11.2 11.2S62 41 62 34.8z");
}

</style>
