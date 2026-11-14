<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1dc44jds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donor-pyramid" /></template>
<style>
.s1dc44jds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 2.5h-1Q9 2.5 9 5v.5q0 1.036.732 1.768T11.5 8h1q1.036 0 1.768-.732T15 5.5V5q0-1.036-.732-1.768T12.5 2.5M7.75 9.25h1q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-1q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5m8.5 0h-1q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h1q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768T16.25 9.25M4.25 16h1q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-1q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5m8.25 0h-1Q9 16 9 18.5v.5q0 2.5 2.5 2.5h1q1.036 0 1.768-.732T15 19v-.5q0-2.5-2.5-2.5m6.25 0h1q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-1q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5");
}

</style>
