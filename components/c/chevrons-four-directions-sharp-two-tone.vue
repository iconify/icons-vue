<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ahfk4zday"/><path clip-rule="evenodd" class="gl6pk_qqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-four-directions-sharp-two-tone" /></template>
<style>
.ahfk4zday {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.5 19.14L12.686 22.73C12.301 23.09 11.7 23.09 11.315 22.73L7.5 19.14L8.871 17.68L12 20.63L15.13 17.68L16.5 19.14Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gl6pk_qqv {
  fill-rule: evenodd;
  d: path("M22.728 11.31C23.09 11.69 23.091 12.29 22.728 12.68L19.14 16.5L17.683 15.12L20.626 11.99L17.683 8.86L19.14 7.49L22.728 11.31ZM6.317 8.86L3.373 11.99L6.317 15.12L4.86 16.5L1.271 12.68C0.909 12.29 0.91 11.69 1.271 11.31L4.86 7.49L6.317 8.86ZM11.352 1.22C11.737 0.92 12.325 0.92 12.685 1.26L16.5 4.85L15.13 6.31L12 3.36L8.871 6.31L7.5 4.85L11.352 1.22Z");
}

</style>
