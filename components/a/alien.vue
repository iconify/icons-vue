<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xyjmsbcpz"/><g class="cgvivj-gr"><path class="a2prf50vb"/><path class="t7o_q3b1a"/></g><path class="jv545si3t"/><g class="cgvivj-gr"><path class="ndyh8pb2h"/><path class="sir-ntx_u"/></g><path class="u5fe54iel"/><path class="d29k3of6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:alien" /></template>
<style>
.a2prf50vb {
  d: path("M23.4 26.4c4 3.8 5.1 8.9 2.6 11.4c-2.5 2.4-7.8 1.3-11.7-2.5c-4-3.8-5.1-8.9-2.6-11.4s7.7-1.4 11.7 2.5");
}

.cgvivj-gr {
  fill: var(--svg-color--454749, #454749);
}

.d29k3of6c {
  fill: var(--svg-color--454749, #454749);
  stroke: var(--svg-color--454749, #454749);
  stroke-miterlimit: 10;
  d: path("M32 48.6c-7.6 0-10.7-3.7-10.7-2.4c0 1.9 4.8 4.4 10.7 4.4s10.7-2.5 10.7-4.4c0-1.3-3.1 2.4-10.7 2.4z");
}

.jv545si3t {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 25c2 1.2 3.1 3.1 2.5 4.1c-.7 1-2.9.8-4.9-.4s-3.1-3.1-2.5-4.1c.7-1 2.8-.8 4.9.4");
}

.ndyh8pb2h {
  d: path("M40.6 26.4c-4 3.8-5.1 8.9-2.6 11.4c2.5 2.4 7.8 1.3 11.7-2.5c4-3.8 5.1-8.9 2.6-11.4s-7.7-1.4-11.7 2.5");
}

.sir-ntx_u {
  d: path("M37.6 30.6c.6-1.6 1.7-3 2.9-4.3c1.2-1.2 2.6-2.3 4.2-3.2c1.5-.9 3.2-1.5 4.9-1.8c1.7-.4 3.4-.5 5.2-.3c-1.6.6-3.2 1.1-4.7 1.8c-1.5.6-3 1.3-4.4 2.1c-2.9 1.5-5.5 3.4-8.1 5.7");
}

.t7o_q3b1a {
  d: path("M26.4 30.6c-2.6-2.3-5.2-4.1-8-5.7c-1.4-.8-2.9-1.5-4.4-2.1s-3.1-1.2-4.7-1.8c1.7-.2 3.5-.1 5.2.3s3.4 1 4.9 1.8s2.9 1.9 4.2 3.2c1.1 1.2 2.2 2.6 2.8 4.3");
}

.u5fe54iel {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.6 25c-2 1.2-3.1 3.1-2.5 4.1c.7 1 2.9.8 4.9-.4s3.1-3.1 2.5-4.1c-.7-1-2.8-.8-4.9.4");
}

.xyjmsbcpz {
  fill: var(--svg-color--c7e755, #c7e755);
  d: path("M59.5 30.6C59.5 54.1 32 62 32 62S4.5 54.1 4.5 30.6C4.5 13.1 15.5 2 32 2s27.5 11.1 27.5 28.6");
}

</style>
