<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq87_cc_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:colorize-sharp" /></template>
<style>
.aq87_cc_p {
  fill: currentColor;
  d: path("M3 21v-4.75l8.95-8.95l-1.45-1.4l1.45-1.4l1.9 1.9l3.8-3.8l3.75 3.75l-3.775 3.775l1.9 1.95L18.1 13.5l-1.4-1.45L7.75 21zm2-2h1.95l8.3-8.35l-1.9-1.9L5 17.05z");
}

</style>
