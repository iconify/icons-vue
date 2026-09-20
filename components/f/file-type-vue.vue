<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-9rbcbtq"/><path class="pyma49_ig"/><path class="g-gtsqakh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vue" /></template>
<style>
.g-gtsqakh {
  fill: var(--svg-color--35495e, #35495e);
  d: path("M7.53 3.925L16 18.485l8.4-14.56h-5.18L16 9.525l-3.29-5.6Z");
}

.pyma49_ig {
  fill: var(--svg-color--41b883, #41b883);
  d: path("m2 3.925l14 24.15l14-24.15h-5.6L16 18.415L7.53 3.925Z");
}

.z-9rbcbtq {
  fill: var(--svg-color--41b883, #41b883);
  d: path("M24.4 3.925H30l-14 24.15L2 3.925h10.71l3.29 5.6l3.22-5.6Z");
}

</style>
