<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr3j7gbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-hierarchy" /></template>
<style>
.yr3j7gbvm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75h2q2.5 0 2.5 2.5v3.5q0 2.5-2.5 2.5h-.25v1.25h3.5q2.25 0 2.25 2.25v.5h.25q2.5 0 2.5 2.5v3q0 1.036-.732 1.768t-1.768.732h-2q-1.036 0-1.768-.732t-.732-1.768v-3q0-2.5 2.5-2.5H17v-.5q0-.75-.75-.75h-8.5Q7 13 7 13.75v.5h.25q1.036 0 1.768.732t.732 1.768v3q0 1.036-.732 1.768t-1.768.732h-2q-1.036 0-1.768-.732T2.75 19.75v-3q0-2.5 2.5-2.5h.25v-.5q0-2.25 2.25-2.25h3.5v-1.25H11q-2.5 0-2.5-2.5v-3.5q0-2.5 2.5-2.5");
}

</style>
