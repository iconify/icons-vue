<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-7o9iovm"/><path class="jdozq-rrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atalk" /></template>
<style>
.b-7o9iovm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.357c-10.77 0-19.5 7.051-19.5 15.75a13 13 0 0 0 .087 1.396q.024.217.055.433c1.39 9.622 13.25 18.078 18.054 19.657A.998.998 0 0 0 24 41.637v-4.78c10.77 0 19.5-7.051 19.5-15.75S34.77 5.357 24 5.357");
}

.jdozq-rrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 14.107a7.2 7.2 0 0 0-3 0c-5.837 2.545-6.633 14.126-13 14c-3.072-.061-5.998-2.657-6-7s2.927-6.94 6-7c6.367-.127 7.163 11.454 13 14a7.2 7.2 0 0 0 3 0");
}

</style>
