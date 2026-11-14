<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt2xqrbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:immersive-space" /></template>
<style>
.lt2xqrbpp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.766 11.296q-.219 3.955 2.259 7.005q.232 1.358 2.604 2.176q2.242.773 5.371.773q7.634 0 7.983-2.96q2.47-3.046 2.251-6.994q-.225-4.075-3.189-6.88T12 1.611T4.955 4.416t-3.189 6.88M12 14.75q-3.129 0-5.371.773q-1.33.459-1.987 1.087q-1.539-2.331-1.379-5.232q.192-3.478 2.723-5.873T12 3.111q3.484 0 6.014 2.394t2.723 5.873q.156 2.831-1.306 5.119Q17.866 14.75 12 14.75");
}

</style>
