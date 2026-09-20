<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGjTxEig5t)" class="zew5yq8ib"/><path fill="url(#SVGFj6H3dKg)" class="ky5gt48kf"/><path fill="url(#SVGofnIfdgq)" class="zyueaopjb"/><defs><linearGradient id="SVGjTxEig5t" x1="22.199" x2="22.199" y1="-3.541" y2="21" gradientUnits="userSpaceOnUse"><stop class="lp62i_bph"/><stop offset="1" class="ms--htbps"/></linearGradient><linearGradient id="SVGFj6H3dKg" x1="12" x2="12" y1="3" y2="47.998" gradientUnits="userSpaceOnUse"><stop class="lp62i_bph"/><stop offset="1" class="ms--htbps"/></linearGradient><linearGradient id="SVGofnIfdgq" x1="12" x2="12" y1="3" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="lp62i_bph"/><stop offset="1" class="ms--htbps"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blox" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ky5gt48kf {
  d: path("M12 3L3.602 6.6L12 10.2l8.398-3.6z");
}

.lp62i_bph {
  stop-color: var(--svg-color--84f9c8, #84f9c8);
}

.ms--htbps {
  stop-color: var(--svg-color--7fb7f6, #7fb7f6);
}

.zew5yq8ib {
  d: path("M11.437 11.399L3 7.799v9L11.437 21z");
}

.zyueaopjb {
  d: path("m21 7.5l-8.437 3.898v9.601L21 16.798z");
}

</style>
