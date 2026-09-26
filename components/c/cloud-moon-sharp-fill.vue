<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="eh9efdkoj"/><path class="q-elplbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-moon-sharp-fill" /></template>
<style>
.eh9efdkoj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 23C7.7909 23 6 21.2091 6 19C6 17.1481 7.2712 15.5383 9.0727 15.109C9.509 12.4509 11.8063 10.5 14.5 10.5C17.1937 10.5 19.491 12.4509 19.9273 15.109C21.7288 15.5383 23 17.1481 23 19C23 21.2091 21.2091 23 19 23L10 23Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-elplbnj {
  d: path("M5.9258 14.5517L5.0758 14.0249C3.1634 12.8397 2 10.7498 2 8.5C2 4.9101 4.9101 2 8.5 2C7.844 2.82 7.4866 3.8388 7.4866 4.8889C7.4866 6.5491 8.3766 8.0819 9.8184 8.905L10.6868 9.4008");
}

</style>
