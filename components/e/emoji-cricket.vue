<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pajkpgbum"/><path class="grwlf0b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-cricket" /></template>
<style>
.grwlf0b3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.41 27.388l-2.237 5.523H14.04m8.43-3.476l-1.316 3.476H24m14.942 0h-2.846l3.558-17.822l-12.808 10.693");
}

.pajkpgbum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.946 23.644H42.5s-3.558 7.129-16.365 6.416c0 0-4.981 0-10.674-5.703c0 0 .712 4.99-2.846 3.564s-4.269-3.564-2.846-8.555l20.757 3.344M5.5 16.515l4.27 2.851l-2.135-4.277");
}

</style>
