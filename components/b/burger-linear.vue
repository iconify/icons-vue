<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ivujnxcot"/><path class="wta-f7bpr"/><path class="ve-x2-bxx"/><path class="ocn32objk"/><path class="dle-az8pg"/><path class="bo-z83rum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:burger-linear" /></template>
<style>
.bo-z83rum {
  d: path("M15 9.34998H15.0001");
}

.dle-az8pg {
  d: path("M12 8.34998H12.0001");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivujnxcot {
  d: path("M4.3998 11.65H19.5998C20.4835 11.65 21.1998 12.3663 21.1998 13.25C21.1998 14.1337 20.4835 14.85 19.5998 14.85H4.3998C3.5161 14.85 2.7998 14.1337 2.7998 13.25C2.7998 12.3663 3.5161 11.65 4.3998 11.65Z");
}

.ocn32objk {
  d: path("M9 9.25H9.0001");
}

.ve-x2-bxx {
  d: path("M4 14.85V16.05C4 17.35 5.2 18.05 7.3 18.05H16.7C18.8 18.05 20 17.35 20 16.05V14.85");
}

.wta-f7bpr {
  d: path("M4 11.65C4 8.05001 7.2 5.95001 12 5.95001C16.8 5.95001 20 8.05001 20 11.65");
}

</style>
