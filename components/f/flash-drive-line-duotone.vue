<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wy6juxypy"/><path class="nerkymkii"/><path class="fyr67fbfm"/><path class="xrl1iyx7n"/><path class="v_guwch_g"/><path class="gluf0itsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flash-drive-line-duotone" /></template>
<style>
.fyr67fbfm {
  d: path("M18.2959 12L19.8302 10.441C21.2767 8.97109 22 8.23615 22 7.32289C22 6.40962 21.2767 5.67469 19.8302 4.20481C18.3837 2.73494 17.6604 2 16.7617 2C15.8629 2 15.1396 2.73494 13.6931 4.20481L12 5.92526");
}

.gluf0itsl {
  d: path("M16.5962 5.28247L15.8891 5.98958");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nerkymkii {
  d: path("M5.25488 14.1426L9.85769 18.7454");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v_guwch_g {
  d: path("M18.7173 7.40381L18.0102 8.11092");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wy6juxypy {
  d: path("M14.4603 18.7454L15.2274 17.9782L15.2274 17.9782C17.3972 15.8084 18.4821 14.7235 18.4821 13.3754C18.4821 12.0273 17.3972 10.9424 15.2274 8.77262L15.2274 8.77262C13.0576 6.60284 11.9727 5.51794 10.6246 5.51794C9.27648 5.51794 8.19159 6.60284 6.02181 8.77262L5.25467 9.53975C3.08489 11.7095 2 12.7944 2 14.1426C2 15.4907 3.08489 16.5756 5.25467 18.7454C7.42446 20.9151 8.50935 22 9.85748 22C11.2056 22 12.2905 20.9151 14.4603 18.7454Z");
}

.xrl1iyx7n {
  d: path("M5.25467 18.7455C3.08489 16.5757 2 15.4908 2 14.1427C2 12.7945 3.08489 11.7097 5.25467 9.53987L6.02181 8.77274C8.19159 6.60296 9.27648 5.51807 10.6246 5.51807C11.9727 5.51807 13.0576 6.60296 15.2274 8.77274C17.3972 10.9425 18.4821 12.0274 18.4821 13.3755C18.4821 14.7237 17.3972 15.8086 15.2274 17.9783L14.4603 18.7455C12.2905 20.9153 11.2056 22.0002 9.85748 22.0002C8.50935 22.0002 7.42446 20.9153 5.25467 18.7455Z");
}

</style>
