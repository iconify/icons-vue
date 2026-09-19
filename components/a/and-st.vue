<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="y8eu_xbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:and-st" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y8eu_xbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.681 16.5h9.975m-4.988 14.999V16.5M17.866 29.857c.923 1.197 2.081 1.644 3.692 1.644h2.23a3.75 3.75 0 1 0 0-7.5h-2.46a3.753 3.753 0 0 1-3.76-3.748a3.76 3.76 0 0 1 3.768-3.752h2.217c1.611 0 2.77.446 3.692 1.643m-17.13 1.886c-.978 0-1.771-.79-1.771-1.764c0-.975.793-1.765 1.771-1.765h1.151c.979 0 1.772.79 1.772 1.765s-.793 1.764-1.772 1.764m-2.922 0h4.694m-4.694 5.735h2.923c.978 0 1.77-.79 1.77-1.764c0-.975-.792-1.765-1.77-1.765m-2.923 0h4.694m-1.771 9.263c.978 0 1.771-.79 1.771-1.764c0-.975-.793-1.765-1.771-1.765h-1.151c-.979 0-1.772.79-1.772 1.765s.793 1.764 1.772 1.764m-1.772 0h7.085");
}

</style>
