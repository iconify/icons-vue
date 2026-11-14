<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzn7p9l4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-contact-form" /></template>
<style>
.bzn7p9l4u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.725 4.557Q10.243 2.75 8.5 2.75h-3q-2.75 0-2.75 2.75q0 6.311 4.72 11.03q4.719 4.72 11.03 4.72q2.75 0 2.75-2.75v-3q0-1.743-1.818-2.228l-3-.75l-.035-.007q-1.595-.32-2.521 1.069l-.633.949q-2.398-1.299-3.77-3.781l.943-.628q1.389-.926 1.069-2.521l-.007-.035zm5.639 6.586Q12.5 8.825 12.5 6q0-3.25 2.75-3.25q.928 0 1.5.447q.572-.447 1.5-.447Q21 2.75 21 6q0 2.825-3.864 5.143q-.088.053-.186.08t-.2.027t-.2-.027t-.186-.08");
}

</style>
