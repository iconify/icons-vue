<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="pqzi749eu"/><path class="p067-gbwt"/><ellipse class="lrv23vp8o"/><path class="r68b5ebqs"/><ellipse class="qpow1icdz"/><path class="jup_tdbgt"/><g class="stn50abee"><path class="klbgqbh_n"/><path class="uhlzwo3at"/></g><path class="dhtqfxqql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:grimacing-face" /></template>
<style>
.dhtqfxqql {
  fill: var(--svg-color--a5692d, #a5692d);
  d: path("M46.23 55H18.266c-5.111 0-9.268-4.04-9.268-9s4.157-9 9.268-9h27.965c5.11 0 9.268 4.04 9.268 9s-4.158 9-9.269 9M18.266 40c-3.456 0-6.268 2.691-6.268 6s2.812 6 6.268 6h27.965c3.456 0 6.268-2.691 6.268-6s-2.812-6-6.268-6z");
}

.jup_tdbgt {
  fill: var(--svg-color--fff, #fff);
  d: path("M54 46.5c0 4.143-3.478 7.5-7.768 7.5H18.268c-4.29 0-7.768-3.357-7.768-7.5s3.478-7.5 7.768-7.5h27.965C50.522 39 54 42.357 54 46.5");
}

.klbgqbh_n {
  d: path("M10 45h44v2H10z");
}

.lrv23vp8o {
  cx: 42.44px;
  cy: 22.12px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.127px;
  ry: 5px;
}

.p067-gbwt {
  fill: var(--svg-color--fff, #fff);
  d: path("M48.813 22.12c0 5.278-2.854 9.549-6.375 9.549c-3.523 0-6.38-4.271-6.38-9.549c0-5.275 2.856-9.55 6.38-9.55c3.522 0 6.375 4.275 6.375 9.55");
}

.pqzi749eu {
  cx: 32.33px;
  cy: 32.32px;
  r: 31.674px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

.qpow1icdz {
  cx: 22.22px;
  cy: 22.12px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.128px;
  ry: 5px;
}

.r68b5ebqs {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.592 22.12c0 5.278-2.854 9.549-6.375 9.549c-3.523 0-6.38-4.271-6.38-9.549c0-5.275 2.856-9.55 6.38-9.55c3.521 0 6.375 4.275 6.375 9.55");
}

.stn50abee {
  fill: var(--svg-color--ccc, #ccc);
}

.uhlzwo3at {
  d: path("M19 37h2v17h-2zm8 0h2v17h-2zm9 0h2v17h-2zm8 0h2v17h-2z");
}

</style>
