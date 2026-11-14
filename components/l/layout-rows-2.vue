<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na6pmmhsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-rows-2" /></template>
<style>
.na6pmmhsy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 2H4.25q-2.5 0-2.5 2.5v4.25q0 2.5 2.5 2.5h15.5q1.036 0 1.768-.732t.732-1.768V4.5q0-1.036-.732-1.768T19.75 2M4.25 12.5h15.5q1.036 0 1.768.732T22.25 15v4.25q0 1.036-.732 1.768t-1.768.732H4.25q-1.036 0-1.768-.732T1.75 19.25V15q0-2.5 2.5-2.5");
}

</style>
