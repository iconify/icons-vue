<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hvc_vyb0f"/><path class="e9jwd2bpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewall-duotone-round" /></template>
<style>
.e9jwd2bpq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm0 1h18M9 15v3m6 0v3M12 3c.25 1.25 1 2.25 2 3c.75.75 1 1.75 1 3a3 3 0 1 1-6 0c0-.75.25-1.25.5-1.5m0 0a1 1 0 1 0 2 0c0-.75-.25-1-.5-1.5c-.5-1-.25-2 1-3");
}

.ft5dv1b6b {
  fill: none;
}

.hvc_vyb0f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.5 7.5c0-.317-.068-.455-.219-.725a8 8 0 0 1-.175-.328c-.355-.71-.455-1.482-.217-2.245c.253-.808.837-1.463 1.486-1.983a1.002 1.002 0 0 1 1.606.585c.199.997.818 1.795 1.619 2.396a1 1 0 0 1 .107.093C15.71 6.296 16 7.626 16 9a4 4 0 0 1-.315 1.557A3.998 3.998 0 0 1 8 9c0-.79.22-1.634.793-2.207A1 1 0 0 1 10.5 7.5");
}

</style>
