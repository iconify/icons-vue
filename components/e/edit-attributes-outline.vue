<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl2281e-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-attributes-outline" /></template>
<style>
.bl2281e-f {
  fill: currentColor;
  d: path("M7 17q-2.075 0-3.537-1.463T2 12t1.463-3.537T7 7h10q2.075 0 3.538 1.463T22 12t-1.463 3.538T17 17zm0-2h10q1.25 0 2.125-.875T20 12t-.875-2.125T17 9H7q-1.25 0-2.125.875T4 12t.875 2.125T7 15m1.05-.7l3.55-3.55l-1.05-1.05l-2.5 2.5l-1-1L6 12.25zM12 12");
}

</style>
