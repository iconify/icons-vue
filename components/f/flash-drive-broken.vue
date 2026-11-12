<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fyr67fbfm"/><path class="e_wor2bbs"/><path class="lm7otu1mj"/><path class="bu-wc30dp"/><path class="gvinp5b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flash-drive-broken" /></template>
<style>
.bu-wc30dp {
  d: path("M18.7173 7.40381L18.0102 8.11092");
}

.e_wor2bbs {
  d: path("M15.2274 17.9783L15.2274 17.9783C17.3972 15.8086 18.4821 14.7237 18.4821 13.3755C18.4821 12.0274 17.3972 10.9425 15.2274 8.77275L15.2274 8.77274C13.0576 6.60296 11.9727 5.51807 10.6246 5.51807C9.27648 5.51807 8.19159 6.60296 6.02181 8.77274L6.02181 8.77274L5.25467 9.53987L5.25467 9.53988C3.08489 11.7097 2 12.7945 2 14.1427C2 15.4908 3.08489 16.5757 5.25467 18.7455C7.42446 20.9153 8.50935 22.0002 9.85748 22.0002C10.5782 22.0002 11.2237 21.6901 12 21.0699");
}

.fyr67fbfm {
  d: path("M18.2959 12L19.8302 10.441C21.2767 8.97109 22 8.23615 22 7.32289C22 6.40962 21.2767 5.67469 19.8302 4.20481C18.3837 2.73494 17.6604 2 16.7617 2C15.8629 2 15.1396 2.73494 13.6931 4.20481L12 5.92526");
}

.gvinp5b1p {
  d: path("M16.5962 5.28247L15.8891 5.98958");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lm7otu1mj {
  d: path("M5.25488 14.1426L9.85769 18.7454");
}

</style>
