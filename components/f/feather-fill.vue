<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ta433xgoa"/><path class="mipo-pbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:feather-fill" /></template>
<style>
.mipo-pbbw {
  d: path("M3 21L5.4532 18.5468");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ta433xgoa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.7461 19.2539C4.4156 18.9236 4.2075 18.4906 4.156 18.0262L3.5578 12.6421C3.5494 12.5667 3.5452 12.4908 3.5452 12.4149C3.5452 11.8692 3.762 11.3459 4.1479 10.9601L11.2663 3.8416C12.4455 2.6624 14.0448 2 15.7123 2C19.1849 2 22 4.8151 22 8.2877C22 9.9552 21.3376 11.5545 20.1584 12.7337L16.5992 16.2929L13.0399 19.8521C12.6541 20.238 12.1308 20.4548 11.5851 20.4548C11.5092 20.4548 11.4333 20.4506 11.3579 20.4422L5.9738 19.844C5.5094 19.7925 5.0764 19.5844 4.7461 19.2539ZM13.7433 16.3203L15.185 14.8787L15.389 14.6747L11.6809 13.7334L16.4195 8.9947C16.607 8.8072 16.7124 8.5529 16.7124 8.2876C16.7124 7.7354 16.2647 7.2876 15.7124 7.2876C15.4472 7.2876 15.1928 7.393 15.0053 7.5805L10.3238 12.262L9.5057 8.4307L7.8205 10.1159L8.6386 13.9472L6.0075 16.5783L6.1438 17.8054C6.1468 17.8321 6.1679 17.8532 6.1946 17.8562L7.4217 17.9925L10.0352 15.3791L13.7433 16.3203Z");
  stroke: none;
}

</style>
