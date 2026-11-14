<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blcm1ob4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diversity-inclusion" /></template>
<style>
.blcm1ob4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.137 4.575l1.14 1.878q.759 1.249.042 2.523T13.14 10.25h-2.28q-1.462 0-2.179-1.274t.042-2.523l1.14-1.878q.73-1.203 2.137-1.203t2.137 1.203M2 16.5q-.001-2.071 1.464-3.536T7 11.499t3.536 1.465T12 16.5q.001 2.071-1.464 3.536T7 21.501q-2.072 0-3.536-1.465Q1.999 18.571 2 16.5m18-4.75h-4.25q-2.5 0-2.5 2.5v4.25q0 1.036.732 1.768T15.75 21H20q1.036 0 1.768-.732T22.5 18.5v-4.25q0-2.5-2.5-2.5");
}

</style>
