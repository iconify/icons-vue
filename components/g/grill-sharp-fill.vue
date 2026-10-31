<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="n8uuusbqa"/><path class="dd3k2gttb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grill-sharp-fill" /></template>
<style>
.dd3k2gttb {
  d: path("M5.9923 18.2635L8.3094 14.2085M15 14.4853L18.2512 22.6292M7 20L17.2016 20M8.5 10L8.5 8.8028C8.5 7.6273 8.848 6.4781 9.5 5.5C10.1521 4.5219 10.5 3.3727 10.5 2.1972L10.5 1M13.5 10L13.5 8.8028C13.5 7.6273 13.848 6.4781 14.5 5.5C15.1521 4.5219 15.5 3.3727 15.5 2.1972L15.5 1");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n8uuusbqa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 20C6 19.4475 5.5522 18.9997 4.9997 18.9997C4.4473 18.9997 3.9995 19.4475 3.9995 19.9999C3.9995 20.5523 4.4473 21.0002 4.9997 21.0002C5.2651 21.0002 5.5195 20.8948 5.7071 20.7071C5.8946 20.5206 6 20.2671 6 20.0026C6 20.0018 6 20.0009 6 20ZM17.2917 12C18.7547 10.7123 19.696 8.9339 19.9382 7L18.5 7L18.5 5L21 5C21.5523 5 22 5.4477 22 6C22.003 8.8305 20.8035 11.5291 18.7003 13.4235C16.8644 15.0847 14.4759 16.0032 12 16C9.1695 16.003 6.4709 14.8035 4.5765 12.7003C2.9153 10.8644 1.9968 8.4759 2 6C2 5.4477 2.4477 5 3 5L5.5 5L5.5 7L4.0618 7C4.304 8.9339 5.2453 10.7123 6.7083 12L17.2917 12ZM8 20C8 21.657 6.6568 23.0003 4.9997 23.0003C3.3427 23.0003 1.9995 21.6571 1.9995 20.0001C1.9995 18.3431 3.3427 16.9998 4.9997 16.9998C5.7955 16.9998 6.5587 17.316 7.1213 17.8787C7.6845 18.4409 8.0007 19.2042 8 20Z");
  stroke: none;
}

</style>
