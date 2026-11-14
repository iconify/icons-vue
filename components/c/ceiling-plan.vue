<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbagozbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ceiling-plan" /></template>
<style>
.mbagozbzy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 1.75h15.5q1.036 0 1.768.732t.732 1.768v15.5q0 1.036-.732 1.768t-1.768.732H4.25q-1.036 0-1.768-.732T1.75 19.75V4.25q0-1.036.732-1.768T4.25 1.75m3.75 3Q4.75 4.75 4.75 8T8 11.25q1.346 0 2.298-.952T11.25 8t-.952-2.298T8 4.75M12.75 8q0 3.25 3.25 3.25T19.25 8T16 4.75T12.75 8M8 12.75q-3.25 0-3.25 3.25T8 19.25q1.346 0 2.298-.952T11.25 16t-.952-2.298T8 12.75M12.75 16q0 3.25 3.25 3.25T19.25 16T16 12.75T12.75 16");
}

</style>
