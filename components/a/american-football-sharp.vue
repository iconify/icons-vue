<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p30e2bbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:american-football-sharp" /></template>
<style>
.p30e2bbbc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.0027 19.9973C3.3412 18.4708 2.9998 16.8249 2.9998 15.1613C2.9998 8.4447 8.4447 2.9999 15.1613 2.9998C16.8249 2.9998 18.4708 3.3412 19.9973 4.0027C20.6588 5.5292 21.0002 7.1751 21.0002 8.8387C21.0002 15.5553 15.5553 21.0002 8.8387 21.0002C7.1751 21.0002 5.5292 20.6588 4.0027 19.9973ZM8.7929 11.7929L9.0858 12.0858L11.9142 14.9142L12.2071 15.2071M11.7929 8.7929L12.0858 9.0858L14.9142 11.9142L15.2071 12.2071M12.1703 3.3734L20.6266 11.8297M3.3734 12.1703L11.8297 20.6266");
}

</style>
