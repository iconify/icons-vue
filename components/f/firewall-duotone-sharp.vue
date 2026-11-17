<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j8m6wclzu"/><path class="fd_6gv4oq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewall-duotone-sharp" /></template>
<style>
.fd_6gv4oq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15h18v6H3Zm0 3h18M9 15v3m6 0v3M12 3c.25 1.25 1 2.25 2 3c.75.75 1 1.75 1 3a3 3 0 1 1-6 0c0-.75.25-1.25.5-1.5m0 0a1 1 0 1 0 2 0c0-.75-.25-1-.5-1.5c-.5-1-.25-2 1-3");
}

.ft5dv1b6b {
  fill: none;
}

.j8m6wclzu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3c.248 1.235 1.005 2.253 2 3c.807.807 1 1.901 1 3a3 3 0 1 1-6 0c0-.514.122-1.122.5-1.5a1 1 0 0 0 2 0c0-.75-.25-1-.5-1.5c-.612-1.226.028-2.222 1-3");
}

</style>
