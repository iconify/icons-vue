<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x0y1spogz"/><path clip-rule="evenodd" class="y3dikf8-d"/><path class="bb7l78g9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:breakfast-duotone" /></template>
<style>
.bb7l78g9o {
  d: path("M10.5 6C10.5 5.2131 10.8705 4.4721 11.5 4C12.1295 3.5279 12.5 2.7869 12.5 2M15.5 6C15.5 5.2131 15.8705 4.4721 16.5 4C17.1295 3.5279 17.5 2.7869 17.5 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x0y1spogz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 13.3626L5 11C5 9.8954 5.8954 9 7 9L17 9C18.1046 9 19 9.8954 19 11L19 12C21.2091 12 23 13.7909 23 16C23 18.2091 21.2091 20 19 20L18.8737 20C18.5872 21.1069 17.8414 22.0387 16.8241 22.5606C16.941 22.2036 17.0004 21.8302 17 21.4545C17.0001 17.9227 14.8052 14.7628 11.4956 13.5298C10.5517 13.1787 9.5526 12.9993 8.5455 13L7.4546 13C6.623 12.9995 5.7959 13.1217 5 13.3626Z");
  stroke: none;
}

.y3dikf8-d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 15L8.5455 15C11.2419 14.9999 13.6544 16.6755 14.5959 19.2023C14.8639 19.9229 15.0007 20.6857 15 21.4545C15 22.3081 14.3081 23 13.4545 23L2.5455 23C1.6919 23 1 22.308 1 21.4545C0.9999 18.7581 2.6755 16.3455 5.2023 15.4041C5.9229 15.1361 6.6857 14.9993 7.4546 15L8 15ZM9 17.0228C8.849 17.0076 8.6973 17 8.5455 17L7.4546 17C7.3027 17 7.151 17.0076 7 17.0228L7 21L9 21L9 17.0228Z");
  stroke: none;
}

</style>
