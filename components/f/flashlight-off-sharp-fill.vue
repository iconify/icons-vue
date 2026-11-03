<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="rk__8028q"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flashlight-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rk__8028q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 19L18.2361 19C16.6103 19 15.0069 18.6215 13.5528 17.8944C12.3764 17.3062 11.0792 17 9.7639 17L2 17C1.4477 17 1 16.5523 1 16L1 8C1 7.4477 1.4477 7 2 7L7 7L16 16L16 16.6996C16.2939 16.78 16.592 16.8445 16.8928 16.8928L19 19ZM10.6141 6.9572C11.6372 6.8541 12.633 6.5655 13.5528 6.1056C15.0069 5.3785 16.6103 5 18.2361 5L22 5C22.5523 5 23 5.4477 23 6L23 18C23.0002 18.3513 22.8158 18.677 22.5145 18.8577L18 14.3431L18 7.0033C17.3239 7.0221 16.6524 7.1219 16 7.3004L16 12.3431L10.6141 6.9572Z");
  stroke: none;
}

</style>
