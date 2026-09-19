<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6tc2ab-f"/><path class="gyj9v_mhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-greater-than-equal" /></template>
<style>
.gyj9v_mhe {
  fill: currentColor;
  d: path("M18 20.998H6v-2h12z");
}

.j6tc2ab-f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.5 15.5l8.25-5.5L6.5 4.5l1-1.5L18 10L7.5 17z");
}

</style>
