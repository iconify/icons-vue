<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="onahezt4c"/><path class="jjmo1abzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-hourglass" /></template>
<style>
.jjmo1abzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.127 13.656c-14.087-7.234-9.954 13.227-28.254 0");
}

.onahezt4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5h-9.377c-4.708 0-7.46 5.306-4.75 9.156c0 0 4.897 7.689 7.281 10.344c2.385 2.655 6.438 9.694 3.346 12.2c-3.092 2.508-2.752-4.171-10.627-1.856M24 43.5h-9.377c-4.708 0-7.46-5.306-4.75-9.156l6.066-8.618M24 4.5h9.377c4.709 0 7.46 5.306 4.75 9.156c0 0-4.897 7.689-7.281 10.344c-2.385 2.655-6.438 9.694-3.346 12.2c3.092 2.508 2.752-4.171 10.627-1.856M24 43.5h9.377c4.709 0 7.46-5.306 4.75-9.156l-6.066-8.618");
}

</style>
