<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nn5x3ob3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-16-filled" /></template>
<style>
.nn5x3ob3g {
  d: path("M7.832 1.755L8 1.75a2.75 2.75 0 0 1 2.745 2.582l.005.168V5h.75A1.5 1.5 0 0 1 13 6.5v6a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 12.5v-6A1.5 1.5 0 0 1 4.5 5h.75v-.5a2.75 2.75 0 0 1 2.582-2.745L8 1.75l-.168.005zM8 8.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2zm.128-5.244L8 3.25a1.25 1.25 0 0 0-1.244 1.122L6.75 4.5V5h2.5v-.5a1.25 1.25 0 0 0-1.122-1.244L8 3.25l.128.006z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
