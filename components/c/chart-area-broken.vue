<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wyack71iq"/><path class="y04tigbvy"/><path class="aitu2e91o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-area-broken" /></template>
<style>
.aitu2e91o {
  d: path("M5.5 16.5V14.2C5.5 11.8 7.2 9 9.5 9C11.3 9 12.2 12.4 14 12.4C15.8 12.4 17.4 5.25 19.6 5.25C20.9 5.25 21.5 6.2 21.5 8.2V16.5C21.5 17.4428 21.5 17.9142 21.2071 18.2071C20.9142 18.5 20.4428 18.5 19.5 18.5H7.5C6.5572 18.5 6.0858 18.5 5.7929 18.2071C5.5 17.9142 5.5 17.4428 5.5 16.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wyack71iq {
  d: path("M22 22H6C4.1144 22 3.1716 22 2.5858 21.4142C2 20.8284 2 19.8856 2 18V9");
}

.y04tigbvy {
  d: path("M2 5.4V2");
}

</style>
