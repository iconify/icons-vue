<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agjc_gbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:labor-law" /></template>
<style>
.agjc_gbpe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.853 4.258l3.889 3.889q.733.732.733 1.768q0 1.035-.733 1.767l-1.06 1.06q-.732.733-1.767.733q-1.036 0-1.768-.733l-1.415-1.414L5.03 18.03q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l6.702-6.702l-1.414-1.415q-.733-.732-.733-1.767q0-1.036.733-1.768l1.06-1.06q.732-.733 1.767-.733q1.036 0 1.768.733M14.5 17.25h5q2.25 0 2.25 2.25t-2.25 2.25h-5q-2.25 0-2.25-2.25t2.25-2.25");
}

</style>
