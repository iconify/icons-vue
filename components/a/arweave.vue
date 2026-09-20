<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="uriu8acom"><path class="dyno9eksr"/><path class="vutmown-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arweave" /></template>
<style>
.dyno9eksr {
  d: path("M12 4.414a7.586 7.586 0 1 0 0 15.173a7.586 7.586 0 0 0 0-15.173M3 12a9 9 0 1 1 18 0a9 9 0 0 1-18 0");
}

.uriu8acom {
  fill: var(--svg-color--222326, #222326);
}

.vutmown-r {
  d: path("M13.268 14.71a1.5 1.5 0 0 1-.102-.279a4 4 0 0 1-.073-.332a2.2 2.2 0 0 1-1.207.67a2.6 2.6 0 0 1-.575.061a2.8 2.8 0 0 1-.924-.145a2.2 2.2 0 0 1-.718-.405c-.2-.17-.36-.38-.472-.616a1.8 1.8 0 0 1-.17-.785q0-1.033.768-1.595c.516-.379 1.283-.59 2.302-.59h.737v-.365c0-.566-.43-1.02-.997-1.02c-.342 0-.592.118-.75.267q-.234.217-.235.586H9.173q0-.417.181-.791c.125-.25.304-.513.538-.703a2.7 2.7 0 0 1 .864-.447q.513-.17 1.171-.169q.592 0 1.1.145q.513.145.889.43q.373.283.585.718q.211.429.212.997v2.802q0 .527.066.87q.067.345.193.593v.102zm-.939-1.397a1.3 1.3 0 0 0 .502-.47v-1.085h-.656c-.5 0-1.154.053-1.383.577c-.145.32-.112.724.151.973c.393.363.972.234 1.386.005");
}

</style>
