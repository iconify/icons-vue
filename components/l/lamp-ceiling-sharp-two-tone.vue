<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lxm5i66vs"/><path class="c_s0dlb-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-ceiling-sharp-two-tone" /></template>
<style>
.c_s0dlb-a {
  d: path("M8 2L16 2M12 2L12 10M8.0002 10L15.9998 10L19.9993 18L4.0007 18ZM8 18C8 20.2091 9.7909 22 12 22C14.2091 22 16 20.2091 16 18");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lxm5i66vs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.1 19L4.0007 19C3.4484 19 3.0007 18.5523 3.0007 18C3.0007 17.8448 3.0368 17.6917 3.1063 17.5528L7.1058 9.5528C7.2751 9.214 7.6214 9 8.0002 9L15.9998 9C16.3786 9 16.7249 9.214 16.8942 9.5528L20.8937 17.5528C20.9632 17.6917 20.9993 17.8448 20.9993 18C20.9993 18.5523 20.5516 19 19.9993 19L16.9 19C16.4367 21.2822 14.4189 23 12 23C9.5811 23 7.5633 21.2822 7.1 19Z");
  stroke: none;
}

</style>
