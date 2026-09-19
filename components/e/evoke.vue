<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ann4kzb1k"/><path class="l5g-hlb7n"/><path class="g7jpxc_jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:evoke" /></template>
<style>
.ann4kzb1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.628 17.933c-1.286-3.672 1.861-8.212 5.02-8.129c6.839.181 10.186 10.002 6.68 15.32m-12.025-.222c-2.624 5.631-1.223 8.26 3.305 3.416");
}

.g7jpxc_jz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.544 34.174c-2.498 3.452.377 14.777 10.942 6.157c5.281-4.309 11.968-12.007 12.675-19.815c.49-5.418-.036-12.7-6.187-15.101c-8.749-3.417-14.712 3.494-16.433 8.229");
}

.l5g-hlb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.973 19.994a5.2 5.2 0 0 1-1.345-2.061c8.105-3.921 11.792 8.7 2.98 10.384");
}

</style>
