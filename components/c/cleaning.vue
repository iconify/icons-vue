<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tru1j6bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cleaning" /></template>
<style>
.tru1j6bbp {
  fill: currentColor;
  d: path("m9 7l1-2V4H9V2h6q.425 0 .713.288T16 3v1l-1 2h-3V5l-2 2zM8 22v-6.85q0-.275.088-.587T8.3 14L12 7h3q.35.35.675.938T16 9v13z");
}

</style>
