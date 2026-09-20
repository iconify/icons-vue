<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezl7pfbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eyebrow-outline-sharp" /></template>
<style>
.ezl7pfbvi {
  fill: currentColor;
  d: path("M14.923 13.558q-.967 0-1.947.131t-2.312.475t-3.191.934t-4.598 1.533l-1.086-.752V9.642q3.257-.578 6.549-1.11T14.941 8q2.966 0 4.88 1.949q1.915 1.949 2.376 5.436l-.948.386q-1.523-1-3.294-1.606t-3.033-.607m0-1q1.235 0 2.673.43t3.356 1.404q-.633-2.678-2.145-4.035T14.923 9q-3.064 0-6.095.449q-3.032.449-6.04 1.017v5.086q2.916-.94 4.805-1.523q1.89-.583 3.196-.917t2.24-.445q.935-.11 1.894-.11m-3.056-1.722");
}

</style>
