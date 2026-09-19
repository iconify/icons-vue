<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r467u9c7h"/><path class="uqceica2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-admin" /></template>
<style>
.r467u9c7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.07 5.663H15.93a4.36 4.36 0 0 0-3.776 2.179l-8.07 13.979a4.36 4.36 0 0 0 0 4.359l8.07 13.978a4.36 4.36 0 0 0 3.776 2.18h16.14a4.36 4.36 0 0 0 3.775-2.18l8.071-13.978a4.36 4.36 0 0 0 0-4.36l-8.07-13.978a4.36 4.36 0 0 0-3.776-2.18Z");
}

.uqceica2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.32 31.785h12.185l6.093 10.552m13.484-28.89L32.989 24l6.093 10.553M7.32 16.215h12.185l6.093-10.553m2.897 10.553h-8.99L15.011 24l4.494 7.785h8.99L32.989 24z");
}

</style>
