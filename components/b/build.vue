<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5vgxobdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:build" /></template>
<style>
.q5vgxobdm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.823 3.581l4.596 4.596q.733.732.733 1.767q0 1.036-.733 1.768l-.707.707q-.732.733-1.768.733q-1.035 0-1.767-.733l-1.768-1.767L3.53 19.53q-.105.106-.243.163T3 19.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 19t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l8.878-8.879l-1.767-1.768q-.733-.732-.733-1.768q0-1.035.733-1.767l.707-.707q.732-.733 1.768-.733q1.035 0 1.767.733m.427 11.669h5q1.036 0 1.768.732t.732 1.768v2q0 1.036-.732 1.768t-1.768.732h-5q-1.036 0-1.768-.732t-.732-1.768v-2q0-2.5 2.5-2.5");
}

</style>
