<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ss-opsbpo"/><circle class="eekt46bma"/><path class="uaz5g173c"/><g class="gr7bnx5qp"><circle class="g173frb2g"/><circle class="v33nztblr"/><circle class="nx0_5tb7u"/><circle class="tn-zyf0ff"/><circle class="kiwvr47rc"/><circle class="gjm4qcc3h"/><circle class="q07c56bkl"/></g><g class="iklylccho"><circle class="j209xrb_c"/><circle class="etqs0ktxp"/><circle class="m17ud4b5w"/><circle class="yg2rvkb_a"/><circle class="ymye4ntsw"/><circle class="dbz5p7bsm"/><circle class="bu4b_tb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:leopard" /></template>
<style>
.bu4b_tb9q {
  cx: 31.5px;
  cy: 18.5px;
  r: 1px;
}

.dbz5p7bsm {
  cx: 28.5px;
  cy: 23.5px;
  r: 1px;
}

.eekt46bma {
  cx: 4px;
  cy: 17px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.etqs0ktxp {
  cx: 17.5px;
  cy: 16.5px;
  r: 1px;
}

.g173frb2g {
  cx: 10.5px;
  cy: 16.5px;
  r: 2px;
}

.gjm4qcc3h {
  cx: 28.5px;
  cy: 23.5px;
  r: 2px;
}

.gr7bnx5qp {
  fill: var(--svg-color--f4900c, #f4900c);
}

.iklylccho {
  fill: var(--svg-color--ffac33, #ffac33);
}

.j209xrb_c {
  cx: 10.5px;
  cy: 16.5px;
  r: 1px;
}

.kiwvr47rc {
  cx: 24.5px;
  cy: 18.5px;
  r: 2px;
}

.m17ud4b5w {
  cx: 14.5px;
  cy: 21.5px;
  r: 1px;
}

.nx0_5tb7u {
  cx: 14.5px;
  cy: 21.5px;
  r: 2px;
}

.q07c56bkl {
  cx: 31.5px;
  cy: 18.5px;
  r: 2px;
}

.ss-opsbpo {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M32.855 16.484A8 8 0 0 0 32 16c-2-1-5 0-9 0c-2 0-4.901-3-10-3c-.801 0-2.256.635-4.341.89C8.62 12.837 8.044 12 7.333 12C6.597 12 6 12.895 6 14c0 .051.007.1.01.15C3.19 14.916 0 18.589 0 20.375C0 22.375 2 24 2 24s1 0 3-2c1.581-1.581 5-1 5-1l1 12s-1 1-2 1s-1 2-1 2h6l1-9h3c2 0 7-1 7-1c2 3 4 4 4 4v3l-2 1c-2 1-1 2-1 2h6s1-8 2-13v5a1 1 0 1 0 2 0v-7c0-2.666-1.357-3.928-3.145-4.516");
}

.tn-zyf0ff {
  cx: 21.5px;
  cy: 23.5px;
  r: 2px;
}

.uaz5g173c {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M0 20s0 2 1 2c0-2 1-2 1-2s-1-1-2 0");
}

.v33nztblr {
  cx: 17.5px;
  cy: 16.5px;
  r: 2px;
}

.yg2rvkb_a {
  cx: 21.5px;
  cy: 23.5px;
  r: 1px;
}

.ymye4ntsw {
  cx: 24.5px;
  cy: 18.5px;
  r: 1px;
}

</style>
