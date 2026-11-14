<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c27_4qhem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:court-trial" /></template>
<style>
.c27_4qhem {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.111 8L8 4.111q.732-.733 1.767-.733q1.036 0 1.768.733l.354.354q.733.732.733 1.767q0 1.036-.733 1.768l-1.414 1.415l4.555 4.555q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-4.555-4.555L8 11.889q-.732.733-1.767.733q-1.036 0-1.768-.733l-.354-.354q-.733-.732-.733-1.768q0-1.035.733-1.767m1.639 8.75h12.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732H5.75q-1.036 0-1.768-.732T3.25 19.25t.732-1.768t1.768-.732");
}

</style>
