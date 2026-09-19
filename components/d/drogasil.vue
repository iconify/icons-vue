<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n4dh7pbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drogasil" /></template>
<style>
.n4dh7pbwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.062 16.123l.254-12.002a.607.607 0 0 0-1.036-.442L3.68 21.28a.607.607 0 0 0 .441 1.036l12.002-.254a6.07 6.07 0 0 0 5.939-5.94m3.876 15.755l-.254 12.002a.607.607 0 0 0 1.036.442l17.6-17.601a.607.607 0 0 0-.441-1.036l-12.002.254a6.07 6.07 0 0 0-5.939 5.94m5.939-9.816l12.002.254a.607.607 0 0 0 .442-1.036L26.72 3.68a.607.607 0 0 0-1.036.441l.254 12.002a6.07 6.07 0 0 0 5.94 5.939m-15.755 3.876L4.12 25.684a.607.607 0 0 0-.442 1.036l17.601 17.6a.607.607 0 0 0 1.036-.441l-.254-12.002a6.07 6.07 0 0 0-5.94-5.939");
}

</style>
