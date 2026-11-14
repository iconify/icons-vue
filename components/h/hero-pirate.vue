<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ametlob6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hero-pirate" /></template>
<style>
.ametlob6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.118 4.625L3.893 6.309Q3 7.539 3.689 8.894q.656 1.287 2.061 1.353V14q0 2.589 1.831 4.419Q9.411 20.25 12 20.25t4.419-1.831T18.25 14v-3.753q1.405-.066 2.061-1.353q.689-1.355-.204-2.585l-1.225-1.684q-1.107-1.522-2.876-.88l-3.664 1.333q-.342.124-.684 0L7.994 3.745q-1.769-.642-2.876.88m2.132 8.696l4.026.366q.23 1.813 2.474 1.813q1.002 0 1.726-.62q.774-.664.774-1.63t-.774-1.63Q14.752 11 13.75 11q-1.822 0-2.316 1.195l-4.184-.38V10.25h9.5V14q0 1.968-1.391 3.359T12 18.75t-3.359-1.391T7.25 14z");
}

</style>
