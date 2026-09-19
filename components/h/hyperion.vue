<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wfoyzb_vo"/><path class="ixojokbgn"/><path class="nvgvvxb9v"/><circle class="c45_3nzru"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hyperion" /></template>
<style>
.c45_3nzru {
  cx: 23.981px;
  cy: 14.405px;
  r: 1.962px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ixojokbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.458 26.557s.035 5.604-2.25 7.742c0 0-4.035-.897-4.5 2.764h-2.111a1.314 1.314 0 0 0-1.388-.801h-2.75c-.275.013-.758.115-1.135 1.307m19.41-10.931a13 13 0 0 0 1.551 6.483s5.219-1.85 6.277 3.995a1.725 1.725 0 0 0 1.947 0s.1-.879.879-.879h2.96a.735.735 0 0 1 .785.752");
}

.nvgvvxb9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.935 27.993s.47 5.63-2.036 9.277h-1.564a1.96 1.96 0 0 0-2.066 2.05c-1.441.644-1.098-.68-2.413-.716c-1.26 0-2.987-.163-2.987 1.955c0 0-1.361-.427-1.405.144m14.702-12.878s.137 5.649 1.695 8.266h2.995a1.924 1.924 0 0 1 1.874 1.874c0 1.774 1.033 1.29 1.033 1.29s-.192-.632 1.736-.632s2.548.955 2.548 1.892l.702.014M19.95 25.405a50 50 0 0 1-1.563-5.143m9.624 5.143a50 50 0 0 0 1.563-5.143");
}

.wfoyzb_vo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.374 27.269c-.64-.864-.922-1.151-2.134.316s-2.121-.107-2.778-2.56l-1.34-5l1.944-1.955A10.65 10.65 0 0 1 23.98 7.059a10.65 10.65 0 0 1 5.915 11.011l1.944 1.955l-1.34 5c-.657 2.453-1.566 4.028-2.778 2.56s-1.494-1.18-2.134-.316s-.956 1.294-1.607 1.294s-.966-.43-1.606-1.294");
}

</style>
