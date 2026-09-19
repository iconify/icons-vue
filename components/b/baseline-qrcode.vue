<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvi62ywkn"/><path class="mjmyqtb8h"/><path class="pq4lpsq2e"/><path class="wvk2fvb5k"/><path class="izhmmzbbn"/><path class="xhw1bue_m"/><path class="agblb8b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-qrcode" /></template>
<style>
.agblb8b7t {
  fill: currentColor;
  d: path("M23 19h-4v4h-6V13h1h-1v6h2v2h2v-6h-2v-2h-1h3v2h2v2h2v-4h2zm0 2v2h-2v-2z");
}

.izhmmzbbn {
  fill: currentColor;
  d: path("M1 13h10v10H1zm2 2v6h6v-6z");
}

.mjmyqtb8h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5h2v2H5z");
}

.nvi62ywkn {
  fill: currentColor;
  d: path("M1 1h10v10H1zm2 2v6h6V3z");
}

.pq4lpsq2e {
  fill: currentColor;
  d: path("M13 1h10v10H13zm2 2v6h6V3z");
}

.wvk2fvb5k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 5h2v2h-2z");
}

.xhw1bue_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 17h2v2H5z");
}

</style>
