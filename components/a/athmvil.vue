<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dun9p-rvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:athmvil" /></template>
<style>
.dun9p-rvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.129 36.279l10.45 7.221V29.057zm10.451 0h17.094a6.077 6.077 0 0 0 6.076-6.077v-11.03m2.121-7.451L31.421 4.5v14.443zm-10.451 0H14.327a6.077 6.077 0 0 0-6.076 6.077v11.03");
}

</style>
