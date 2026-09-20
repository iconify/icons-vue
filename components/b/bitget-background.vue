<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gr5_hkbjf"/><path class="la694x0xx"/><path class="d1_7shbdz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitget-background" /></template>
<style>
.d1_7shbdz {
  fill: var(--svg-color--00040c, #00040c);
  d: path("M12.769 14.258H9.022L5.188 10.21a.706.706 0 0 1-.003-.956L10.102 4h3.86l-1.167 1.206L8.51 9.732l4.23 4.526");
}

.ft5dv1b6b {
  fill: none;
}

.gr5_hkbjf {
  fill: var(--svg-color--00f0ff, #00f0ff);
  d: path("M24 0H0v24h24z");
}

.la694x0xx {
  fill: var(--svg-color--00040c, #00040c);
  d: path("M11.23 9.742h3.748l3.834 4.05c.25.263.25.69.003.956L13.898 20h-3.86l1.167-1.206l4.285-4.526l-4.23-4.526");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
