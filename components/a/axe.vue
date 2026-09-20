<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kfmu_5anu"/><path class="lo-vie9ng"/><path class="aou9x_bia"/><path class="jly-qbcos"/><path fill="url(#SVG8p3QJcHN)" class="nnk9uw4es"/><defs><linearGradient id="SVG8p3QJcHN" x1="12" x2="12" y1="3.102" y2="21" gradientUnits="userSpaceOnUse"><stop class="mr77isbrf"/><stop offset="1" class="rcm8jgzzc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:axe" /></template>
<style>
.aou9x_bia {
  fill: var(--svg-color--3052f1, #3052f1);
  d: path("M11.91 13.227L7.33 21l4.579-4.804L16.742 21z");
}

.ft5dv1b6b {
  fill: none;
}

.jly-qbcos {
  fill: var(--svg-color--193fe0, #193fe0);
  d: path("M12.017 13.39L16.742 21l-1.716-1.71l-3.01-5.906zM9.13 19.116L7.331 21l4.5-7.633z");
}

.kfmu_5anu {
  fill: var(--svg-color--6d47ec, #6d47ec);
  d: path("M11.91 10.773L7.33 3l4.579 4.804L16.742 3z");
}

.lo-vie9ng {
  fill: var(--svg-color--193fe0, #193fe0);
  d: path("M12.017 10.61L16.742 3l-1.716 1.71zM9.13 4.884L7.331 3l4.5 7.633z");
}

.mr77isbrf {
  stop-color: var(--svg-color--dd76f9, #dd76f9);
}

.nnk9uw4es {
  d: path("M7.742 12.05L3 7.248l4.09-4.145l4.87 7.683l4.95-7.683L21 7.247l-4.742 4.804L21 16.854L16.91 21l-4.95-7.706L7.09 21L3 16.854z");
}

.rcm8jgzzc {
  stop-color: var(--svg-color--00c1e3, #00c1e3);
}

</style>
