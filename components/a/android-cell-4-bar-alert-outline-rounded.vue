<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3dq2_hkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-cell-4-bar-alert-outline-rounded" /></template>
<style>
.w3dq2_hkw {
  fill: currentColor;
  d: path("M2.866 18.154v-4.885q0-.352.247-.6q.247-.246.6-.246t.6.247t.245.6v4.884q0 .352-.248.6t-.6.246t-.6-.247q-.244-.246-.244-.6m5.519 0v-7.191q0-.353.247-.6t.601-.246t.599.246t.245.6v7.192q0 .353-.247.6T9.229 19t-.6-.247t-.244-.6m5.519 0V8.636q0-.353.247-.6t.601-.246t.599.246t.245.6v9.519q0 .353-.247.6t-.601.246t-.599-.247t-.245-.6m5.519-6.612V5.846q0-.352.248-.6t.6-.246t.6.247t.245.6v5.542q-.126-.012-.244-.018t-.257-.006q-.313 0-.618.047q-.306.046-.574.128m.672 7.25q-.21-.21-.21-.52t.21-.521t.52-.21t.52.21t.211.52t-.21.52q-.21.211-.52.211t-.52-.21m.02-2.751v-2.616q0-.213.143-.356q.144-.144.357-.144t.356.144t.144.356v2.616q0 .212-.144.356t-.357.143t-.356-.143t-.144-.357");
}

</style>
