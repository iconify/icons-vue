<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_zoxfbhf"/><path class="aikkdybxx"/><path class="si8_b1byp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bee-duotone" /></template>
<style>
.aikkdybxx {
  fill: currentColor;
  d: path("M17.1832 17.5502C16.5468 19.0624 15.0763 21.3939 12.4961 22.8682C12.345 22.9546 12.174 23 12 23C11.826 23 11.655 22.9546 11.5039 22.8682C8.9239 21.3939 7.4533 19.0626 6.8169 17.5504C9.0679 16.8092 10.9265 15.2039 12.0001 13.127C12.4288 13.9564 12.9825 14.7105 13.636 15.364C14.6194 16.3474 15.8305 17.1047 17.1832 17.5502ZM14.8284 3.1716C15.5512 3.8943 16 4.8957 16 6C16 7.1046 15.1046 8 14 8L10 8C8.8954 8 8 7.1046 8 6C8 3.7908 9.7908 2 12 2C13.1043 2 14.1057 2.4488 14.8284 3.1716Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.si8_b1byp {
  d: path("M9.5 3.5L8 2M14.5 3.5L16 2");
}

.w_zoxfbhf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.0001 13.127C10.5039 16.0215 7.483 18 4 18C2.8954 18 2 17.1046 2 16L2 15C2 12.515 3.0084 10.2636 4.636 8.636C6.2636 7.0084 8.515 6 11 6C11.3643 6 11.7058 6.0974 12 6.2675C12.2942 6.0974 12.6357 6 13 6C17.9706 6 22 10.0294 22 15L22 16C22 17.1046 21.1046 18 20 18C17.515 18 15.2636 16.9916 13.636 15.364C12.9825 14.7105 12.4288 13.9564 12.0001 13.127Z");
  stroke: none;
}

</style>
