<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="os3tpdb0m"/><path class="qbp8n6vpn"/><path class="x-10vwpqp"/><path class="q_fdapbwk"/><path class="cjy0tkb9p"/><path class="igombw0ln"/><path class="byulolb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fbx" /></template>
<style>
.byulolb-n {
  fill: var(--svg-color--006c6e, #006c6e);
  d: path("m7.895 27.447l4.735 1.414L16.419 30l.123-18.104z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cjy0tkb9p {
  fill: var(--svg-color--009b9d, #009b9d);
  d: path("M22.375 3.222L16.597 2l-.041 6.464l7.549-1.276z");
}

.igombw0ln {
  fill: var(--svg-color--002526, #002526);
  d: path("m8.252 6.378l-.371 2.704l.014 18.365l8.647-15.551z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.os3tpdb0m {
  fill: var(--svg-color--008f90, #008f90);
  d: path("M16.597 2L8.252 6.378l-.371 2.704l.014 18.365L16.419 30");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.q_fdapbwk {
  fill: var(--svg-color--004748, #004748);
  d: path("m8.225 6.378l-.371 2.691l8.702-.605L16.597 2z");
}

.qbp8n6vpn {
  fill: var(--svg-color--00393a, #00393a);
  d: path("M7.895 11.896v3.033l5.435 2.746l3.157 2.031l.043-7.817z");
}

.x-10vwpqp {
  fill: var(--svg-color--008f90, #008f90);
  d: path("m16.53 11.889l-.043 7.817l6.904-2.663l.755-5.161z");
}

</style>
