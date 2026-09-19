<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="j0key6b1a"/><path class="ihs74ybru"/><circle class="tmwjywuki"/><g class="n1mjunbsu"><ellipse class="z-z016bdy"/><ellipse class="u4j3n2bka"/><path class="jf-e8xbyh"/></g><circle class="audogt4-k"/><g class="n1mjunbsu"><ellipse class="ve3vp1biq"/><ellipse class="pybl5s6mk"/></g><path class="vmy178-4z"/><path class="gajl0ybug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:crying-face" /></template>
<style>
.audogt4-k {
  cx: 19px;
  cy: 31px;
  r: 6px;
  fill: var(--svg-color--664e27, #664e27);
}

.gajl0ybug {
  fill: var(--svg-color--917524, #917524);
  d: path("M53.2 20.7c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-30.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.ihs74ybru {
  fill: var(--svg-color--fff, #fff);
  d: path("M54 31c0 5-4 9-9 9s-9-4-9-9s4-9 9-9s9 4 9 9");
}

.j0key6b1a {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.6 46.4c-5.4-2.5-11.8-2.5-17.2 0c-1.3.6.3 4.2 1.7 3.5c3.6-1.7 8.9-2.3 13.9 0c1.3.6 3-2.8 1.6-3.5");
}

.jf-e8xbyh {
  d: path("M28 31c0 5-4 9-9 9s-9-4-9-9s4-9 9-9s9 4 9 9");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.pybl5s6mk {
  cx: 16.8px;
  cy: 31px;
  rx: 1.6px;
  ry: 1.9px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.tmwjywuki {
  cx: 45px;
  cy: 31px;
  r: 6px;
  fill: var(--svg-color--664e27, #664e27);
}

.u4j3n2bka {
  cx: 42.8px;
  cy: 31px;
  rx: 1.6px;
  ry: 1.9px;
}

.ve3vp1biq {
  cx: 20.6px;
  cy: 35.5px;
  rx: 2.8px;
  ry: 3.2px;
}

.vmy178-4z {
  fill: var(--svg-color--65b1ef, #65b1ef);
  d: path("M47 36c-5.1 6.8-8 13-8 18.1c0 4.4 3.6 7.9 8 7.9s8-3.5 8-7.9c0-5.1-3-11.4-8-18.1");
}

.z-z016bdy {
  cx: 46.6px;
  cy: 35.5px;
  rx: 2.8px;
  ry: 3.2px;
}

</style>
