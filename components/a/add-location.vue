<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dturrabwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-location" /></template>
<style>
.dturrabwk {
  fill: currentColor;
  d: path("M11.5 13.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zm.5 7.52q-3.525-3.118-5.31-5.815q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 2.212-1.785 4.909q-1.786 2.697-5.311 5.814");
}

</style>
